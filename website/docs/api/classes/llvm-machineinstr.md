---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineinstr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineInstr` Class

<p>Representation of each machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineInstr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent">ilist_node_with_parent&lt;NodeTy, ParentTy, Options&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ilist node that can access its parent list. <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for all GenericMachineInstrs. <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e87ec17cd2a1eaeb65d82c698b61d6">mmo_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt;::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>iterator/begin/end - Iterate over all operands of a machine instruction. <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9206189b1d54e585e0d3d0c9fd698b29">filtered_mop_iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a>, bool(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50cb55604768b56d55eba76ed4568be">filtered_const_mop_iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a>, bool(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;)&gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4439c0896d3c1b03846173f0e49751cd">OperandCapacity</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler">ArrayRecycler</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt;::Capacity</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CommentFlag { <a href="#a0ac990e2b3f7973d16c33555e9adf9ae">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags to specify different kinds of comments to output in assembly code. <a href="#a0ac990e2b3f7973d16c33555e9adf9ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MIFlag { <a href="#aafacf84de1cb994a92dc045f4aa1d518">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">QueryType { <a href="#a26e1467ec6a91a35dfc32239e50f0fb5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>API for querying <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> properties. <a href="#a26e1467ec6a91a35dfc32239e50f0fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MICheckType { <a href="#ab7650f958c093f7c5faf8c69dbc8c462">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExtraInfoInlineKinds { <a href="#a3bcea80716879e989df4147a48b0bd29">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumeration of the kinds of inline extra info available. <a href="#a3bcea80716879e989df4147a48b0bd29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5acbf433c0f6fc94a353ddaed7bdaa28">ilist_traits&lt; MachineInstr &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd6646c0c037f87ce89191e20336d77">ilist_callback_traits&lt; MachineBasicBlock &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b6b28587169b4ac00f806e448782a5">MachineInstr</a> (const MachineInstr &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78645f0f9262e1a7357308177f8ec23a">MachineInstr</a> (MachineFunction &amp;, const MachineInstr &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor creates a copy of the given <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> in the given <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#a78645f0f9262e1a7357308177f8ec23a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa221dd55a2ed253b3d2e4bb982ccd5">MachineInstr</a> (MachineFunction &amp;, const MCInstrDesc &amp;TID, DebugLoc DL, bool NoImp=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor create a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> and add the implicit operands. <a href="#a2aa221dd55a2ed253b3d2e4bb982ccd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff89b555a3272b39e2185acd5741da04">~MachineInstr</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796234c977cac1502fdedc7bf67569ea">operator=</a> (const MachineInstr &amp;)=delete</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dbc9a748353035febcc488160ba9956">getTypeToPrint</a> (unsigned OpIdx, SmallBitVector &amp;PrintedTypes, const MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debugging support

Determine the generic type to be printed (if needed) on uses and defs. <a href="#a9dbc9a748353035febcc488160ba9956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2b6142e2253bdad20b1f980f53f216">hasComplexRegisterTies</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true when an instruction has tied register that can't be determined by the instruction's descriptor. <a href="#a9d2b6142e2253bdad20b1f980f53f216">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab419785650ef9728b5305d220179017c">print</a> (raw_ostream &amp;OS, bool IsStandalone=true, bool SkipOpers=false, bool SkipDebugLoc=false, bool AddNewLine=true, const TargetInstrInfo *TII=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this MI to <span class="doxyComputerOutput">OS</span>. <a href="#ab419785650ef9728b5305d220179017c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e904486c2be7b98450bc2306c10648">print</a> (raw_ostream &amp;OS, ModuleSlotTracker &amp;MST, bool IsStandalone=true, bool SkipOpers=false, bool SkipDebugLoc=false, bool AddNewLine=true, const TargetInstrInfo *TII=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc60d2019e9dff57bb0918a94422ebb">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b14770ed9fb839f309757ca2adc80d">dumpr</a> (const MachineRegisterInfo &amp;MRI, unsigned MaxDepth=UINT_MAX) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> the current instruction and the instructions defining its operands and so on until we reach <span class="doxyComputerOutput">MaxDepth</span>. <a href="#a47b14770ed9fb839f309757ca2adc80d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e855100f407ca4be098d0050be403b0">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec2ff43deaac49822bf15f2bac50bb3">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc00f43b2ea96bd57a1d9ceb316dccb7">moveBefore</a> (MachineInstr *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the instruction before <span class="doxyComputerOutput">MovePos</span>. <a href="#afc00f43b2ea96bd57a1d9ceb316dccb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function that contains the basic block that this instruction belongs to. <a href="#ab05719438bdf4b46871e5ecd9730caeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269e83f53595da3ec459010b8f945afc">getMF</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cbe06065807dd01b0785c3f47490c0">getAsmPrinterFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the asm printer flags bitvector. <a href="#a88cbe06065807dd01b0785c3f47490c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc4487354633e23a68f6ca683d593f1">clearAsmPrinterFlags</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> bitvector. <a href="#a1cc4487354633e23a68f6ca683d593f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4866593b666b1cbcb3c95802c12bcfb5">getAsmPrinterFlag</a> (CommentFlag Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> flag is set. <a href="#a4866593b666b1cbcb3c95802c12bcfb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698b6937d98b7ee400dee8b7b3c8a4bd">setAsmPrinterFlag</a> (uint8_t Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a flag for the <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>. <a href="#a698b6937d98b7ee400dee8b7b3c8a4bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3381aa77ac8bf4b65adf2d02a78c4dc9">clearAsmPrinterFlag</a> (CommentFlag Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear specific <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> flags. <a href="#a3381aa77ac8bf4b65adf2d02a78c4dc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73e18478cd951f76d35a88c4d43ef5a">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the MI flags bitvector. <a href="#ad73e18478cd951f76d35a88c4d43ef5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33365204be9cb132de322e3713253b57">getFlag</a> (MIFlag Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether an MI flag is set. <a href="#a33365204be9cb132de322e3713253b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba86b0738c2ab2a52688b846c45bfe59">setFlag</a> (MIFlag Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a MI flag. <a href="#aba86b0738c2ab2a52688b846c45bfe59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264402282f599b6181b6415278fbf849">setFlags</a> (unsigned flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859897c8a9706acd4c065d857254d58c">clearFlag</a> (MIFlag Flag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearFlag - Clear a MI flag. <a href="#a859897c8a9706acd4c065d857254d58c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7751cd90dd24d01b61a431d2a2929f74">clearFlags</a> (unsigned flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97496994b12c49c3141d8f15bc871eb">isInsideBundle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI is in a bundle (but not the first MI in a bundle). <a href="#aa97496994b12c49c3141d8f15bc871eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd00129f7ee0f594aad95a71abe9eddc">isBundled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction part of a bundle. <a href="#afd00129f7ee0f594aad95a71abe9eddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">isBundledWithPred</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is part of a bundle, and it is not the first instruction in the bundle. <a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07416ea31edd139a4ebe5b42a6f80b0">isBundledWithSucc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is part of a bundle, and it is not the last instruction in the bundle. <a href="#ad07416ea31edd139a4ebe5b42a6f80b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aad617bc1bdef5bda2689f7a9fd06f6">bundleWithPred</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bundle this instruction with its predecessor. <a href="#a0aad617bc1bdef5bda2689f7a9fd06f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21273844821e851afa28968bdd6ff10f">bundleWithSucc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bundle this instruction with its successor. <a href="#a21273844821e851afa28968bdd6ff10f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6780a3b4a7f87d5fc85574207fa02c60">unbundleFromPred</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Break bundle above this instruction. <a href="#a6780a3b4a7f87d5fc85574207fa02c60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1d83105d6c2d3de29fca286f9d1b5a">unbundleFromSucc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Break bundle below this instruction. <a href="#ade1d83105d6c2d3de29fca286f9d1b5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb10ef030fba4ea901518a0c8dbef3e2">getDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the debug location id of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#abb10ef030fba4ea901518a0c8dbef3e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbcc97c288440883cc78c74fed7066e">getDebugOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand containing the offset to be used if this DBG_VALUE instruction is indirect; will be an invalid register if this value is not indirect, and an immediate with value 0 otherwise. <a href="#acdbcc97c288440883cc78c74fed7066e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51da1bfa6bdaa6cd06be2a3b92ccae1a">getDebugOffset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfcdb704dc6511a2c0b93fe4e5987182">getDebugVariableOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand for the debug variable referenced by this DBG_VALUE instruction. <a href="#abfcdb704dc6511a2c0b93fe4e5987182">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac916b8cc2bbad1b2fad0d16486ee7593">getDebugVariableOp</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce3843932b6ae1c23228017f11eef25">getDebugVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the debug variable referenced by this DBG_VALUE instruction. <a href="#a9ce3843932b6ae1c23228017f11eef25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3736f5c23004fc6d6b0d0dc773efe7e2">getDebugExpressionOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand for the complex address expression referenced by this DBG_VALUE instruction. <a href="#a3736f5c23004fc6d6b0d0dc773efe7e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539133bbbe620ce232f698234544b990">getDebugExpressionOp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab367ba2f45afaba6e941bd54c9c95a9f">getDebugExpression</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the complex address expression referenced by this DBG_VALUE instruction. <a href="#ab367ba2f45afaba6e941bd54c9c95a9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de5351053b099124a2e2ea477ed54c9">getDebugLabel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the debug label referenced by this DBG_LABEL instruction. <a href="#a8de5351053b099124a2e2ea477ed54c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26a74fb0ad868f0867cce317269d721">getDebugInstrNum</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fetch the instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#ad26a74fb0ad868f0867cce317269d721">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8cfd2dc5bfc62862b1c75c20a1ee66">getDebugInstrNum</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fetch instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> – but before it's inserted into <span class="doxyComputerOutput">MF</span>. <a href="#a1e8cfd2dc5bfc62862b1c75c20a1ee66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524f9c8ad90631347eeaa311ba919b8f">peekDebugInstrNum</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine the instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a524f9c8ad90631347eeaa311ba919b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443787beae18cf65517b239aa15d74e4">setDebugInstrNum</a> (unsigned Num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a443787beae18cf65517b239aa15d74e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209695ff10faf55ead93f3c26a61f642">dropDebugNumber</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop any variable location debugging information associated with this instruction. <a href="#a209695ff10faf55ead93f3c26a61f642">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea65fa322ddcff0ca4cd6f83ccef77e0">getLocCookieMD</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For inline asm, get the !srcloc metadata node if we have it, and decode the loc cookie from it. <a href="#aea65fa322ddcff0ca4cd6f83ccef77e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72245681f0ae02a2d4574d434bc813d">emitInlineAsmError</a> (const Twine &amp;ErrMsg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an error referring to the source location of this instruction. <a href="#ad72245681f0ae02a2d4574d434bc813d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee16070891b230788ad237d5ba6476d">emitGenericError</a> (const Twine &amp;ErrMsg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">getDesc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the target instruction descriptor of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the opcode of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a0363204b5fbab08a46f5a7cd7f376f78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retuns the total number of operands. <a href="#a432824f0975bb863478bf4ef3a5df258">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4275c0f770726594387d7bfc85ea8d64">getNumDebugOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total number of operands which are debug locations. <a href="#a4275c0f770726594387d7bfc85ea8d64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6197870d7271620c9bad9f4a649fc26a">getOperand</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace50f23b8d1566bccb42a36100a9b818">getDebugOperand</a> (unsigned Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adebad355655dfb512517e2f55bc98fb7">getDebugOperand</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067c1c89704407541cbed8d65ac8dd66">hasDebugOperandForReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this debug value has at least one debug operand with the register <span class="doxyComputerOutput">Reg</span>. <a href="#a067c1c89704407541cbed8d65ac8dd66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>)&gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af06fa0062be2cb3feb58ad49814b9b2a">getDebugOperandsForReg</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>)&gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e69cc2fdf3daec4ae61c572d71bf43">getDebugOperandsForReg</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a225209000f521430877a269f61083">isDebugOperand</a> (const MachineOperand *Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd30a83560c3674627e36af9175e9e1f">getDebugOperandIndex</a> (const MachineOperand *Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5036d7a6318520089e8c654b95e76c1">getNumDefs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total number of definitions. <a href="#ae5036d7a6318520089e8c654b95e76c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5879bc3bd2b8f21ba2d83a1f97a020d9">hasImplicitDef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction has implicit definition. <a href="#a5879bc3bd2b8f21ba2d83a1f97a020d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04430301e461dbb2e962ae7d711cbbc6">getNumImplicitOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the implicit operands number. <a href="#a04430301e461dbb2e962ae7d711cbbc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a> (unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if operand <span class="doxyComputerOutput">OpIdx</span> is a subregister index. <a href="#a894f447628559f53d2279c9f9fae0780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of non-implicit operands. <a href="#a56b7fed94faeb5bc67ee2b71608d2665">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of non-implicit definitions. <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa16a8f17fdb13884cf0b164d2225ff">operands_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663a3293492f4dac5169d811991b521d">operands_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d2452d3e44037d5247fb125480634c">operands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f1fa9d5384d3b9c157a8216fef671d">explicit_operands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471354c2bb81524bd5924f7290104f55">explicit_operands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0666b4ee4d5d2ade97f5f1e63865bab">implicit_operands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14071becb4727630d1f983391fd718d">implicit_operands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range over all operands that are used to determine the variable location for this DBG_VALUE instruction. <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc07273003a0c8e17c23f2d257ea6a9">debug_operands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range over all operands that are used to determine the variable location for this DBG_VALUE instruction. <a href="#a7dc07273003a0c8e17c23f2d257ea6a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b9fba7fd848bb37e43040b66f6c051">defs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range over all explicit operands that are register definitions. <a href="#aa3b9fba7fd848bb37e43040b66f6c051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52be2a25e3a107f532b38ce311b0717b">defs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range over all explicit operands that are register definitions. <a href="#a52be2a25e3a107f532b38ce311b0717b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3949f157e1034f6cb5d16ad708059aa3">uses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range that includes all operands which may be register uses. <a href="#a3949f157e1034f6cb5d16ad708059aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15bc8fb07e719b5a47a7c9070c5e26af">uses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range that includes all operands which may be register uses. <a href="#a15bc8fb07e719b5a47a7c9070c5e26af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0773fc3d8cd259c587ec29b5902de0f4">explicit_uses</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a3e7027c93fbf5f29af591087170f41">explicit_uses</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9206189b1d54e585e0d3d0c9fd698b29">filtered_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4229c653b0cbcaca057e8af5002783">all_defs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator range over all operands that are (explicit or implicit) register defs. <a href="#ade4229c653b0cbcaca057e8af5002783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ad50cb55604768b56d55eba76ed4568be">filtered_const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed7df9f98920ad21ef28dc7e0e70f39">all_defs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator range over all operands that are (explicit or implicit) register defs. <a href="#a9ed7df9f98920ad21ef28dc7e0e70f39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9206189b1d54e585e0d3d0c9fd698b29">filtered_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3daf8e155bf0aa3e65b5260bfe3698c5">all_uses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator range over all operands that are (explicit or implicit) register uses. <a href="#a3daf8e155bf0aa3e65b5260bfe3698c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ad50cb55604768b56d55eba76ed4568be">filtered_const_mop_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7954d5796d6983c4a71e1cf1a838d7df">all_uses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator range over all operands that are (explicit or implicit) register uses. <a href="#a7954d5796d6983c4a71e1cf1a838d7df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5574b8f058874009cab01e055a44338a">getOperandNo</a> (const_mop_iterator I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of the operand iterator <span class="doxyComputerOutput">I</span> points to. <a href="#a5574b8f058874009cab01e055a44338a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access to memory operands of the instruction. <a href="#ab37075d621acbbfc96ef2662f2e29883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00e87ec17cd2a1eaeb65d82c698b61d6">mmo_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access to memory operands of the instruction. <a href="#aa5ff177bc1498508696aaf27235db3fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00e87ec17cd2a1eaeb65d82c698b61d6">mmo_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">memoperands_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access to memory operands of the instruction. <a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we don't have any memory operands which described the memory access done by this instruction. <a href="#a4cd2e2c219c477019aa343c92dcf56cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999795324f5e7c578a97992d780080f1">hasOneMemOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has exactly one <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>. <a href="#a999795324f5e7c578a97992d780080f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820e6d6b9b0a0cacce473925803ba569">getNumMemOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of memory operands. <a href="#a820e6d6b9b0a0cacce473925803ba569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to extract a pre-instruction symbol if one has been added. <a href="#ac7561e84ab87828a4c700c2e05ca8302">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to extract a post-instruction symbol if one has been added. <a href="#add92393d0dae36ec6d41435e11d09884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to extract a heap alloc marker if one has been added. <a href="#ad17b8014d3272aa5121425e2bcef34db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to extract PCSections metadata target sections. <a href="#a7545019dcaee79c0d03335e6648c8bab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to extract mmra.op metadata. <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to extract a CFI type hash if one has been added. <a href="#a22b83742938bc0b4477b0f19d563ebfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> (unsigned MCFlag, QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction (or in the case of a bundle, the instructions inside the bundle) has the specified property. <a href="#a257b68a68cb55f34cb704eb776afda1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed10acdf0b7b55818ce0179b3f57331">isPreISelOpcode</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an instruction that should go through the usual legalization steps. <a href="#abed10acdf0b7b55818ce0179b3f57331">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33de0b50f93d38f9fab12e8adf7ba62">isVariadic</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction can have a variable number of operands. <a href="#af33de0b50f93d38f9fab12e8adf7ba62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca12cb3163511b8cfa235a411d789d46">hasOptionalDef</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if this instruction has an optional definition, e.g. <a href="#aca12cb3163511b8cfa235a411d789d46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf37b74e017f80f204221fe3143ab89f">isPseudo</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a pseudo instruction that doesn't correspond to a real machine instruction. <a href="#abf37b74e017f80f204221fe3143ab89f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffeb27bd92437aa2fd7b7567b01d078">isMetaInstruction</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction doesn't produce any output in the form of executable instructions. <a href="#aeffeb27bd92437aa2fd7b7567b01d078">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04af1d639a21e7ef4357facd283b42c4">isReturn</a> (QueryType Type=AnyInBundle) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefa2936f2beea06e735ee3887f5b6c4">isEHScopeReturn</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an instruction that marks the end of an EH scope, i.e., a catchpad or a cleanuppad instruction. <a href="#abefa2936f2beea06e735ee3887f5b6c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a> (QueryType Type=AnyInBundle) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806028855ad5c3431de7958e031e5ee1">isCandidateForAdditionalCallInfo</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a call instruction that may have an additional information associated with it. <a href="#a806028855ad5c3431de7958e031e5ee1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad957f14a0cd72c10f5117fd1b9f30173">shouldUpdateAdditionalCallInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if copying, moving, or erasing this instruction requires updating additional call info (see copyCallInfo, moveCallInfo, eraseCallInfo). <a href="#ad957f14a0cd72c10f5117fd1b9f30173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dbc79cfed570a9127d2853385162bdf">isBarrier</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified instruction stops control flow from executing the instruction immediately following it. <a href="#a2dbc79cfed570a9127d2853385162bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e85c20fe804527f12c86db38ec947ea">isTerminator</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction part of the terminator for a basic block. <a href="#a0e85c20fe804527f12c86db38ec947ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5891cdb51072f67e65f7ebd9be1205e7">isBranch</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a conditional, unconditional, or indirect branch. <a href="#a5891cdb51072f67e65f7ebd9be1205e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ce3659ba05d62794e306f6d070a850">isIndirectBranch</a> (QueryType Type=AnyInBundle, bool IncludeJumpTable=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an indirect branch, such as a branch through a register. <a href="#a19ce3659ba05d62794e306f6d070a850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe223b320036ba5a1ed344b1d44b0045">isComputedGoto</a> (QueryType Type=AnyInBundle) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d17cf681d7702d672b01153abf97be2">isConditionalBranch</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a branch which may fall through to the next instruction or may transfer control flow to some other block. <a href="#a7d17cf681d7702d672b01153abf97be2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c590e8191655a6739eb4df9c443896">isUnconditionalBranch</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a branch which always transfers control flow to some other block. <a href="#a91c590e8191655a6739eb4df9c443896">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b224b59ee2bd22bdfb5fbbd74c4f773">isPredicable</a> (QueryType Type=AllInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has a predicate operand that controls execution. <a href="#a2b224b59ee2bd22bdfb5fbbd74c4f773">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586262a958ca1593548855334ba99a12">isCompare</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a comparison. <a href="#a586262a958ca1593548855334ba99a12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec39b9fa59dac3c090092213bfc61c6">isMoveImmediate</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a move immediate (including conditional moves) instruction. <a href="#abec39b9fa59dac3c090092213bfc61c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1c2054afa973564e0c2dd7fc5d2382">isMoveReg</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a register move. <a href="#a9a1c2054afa973564e0c2dd7fc5d2382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac974851e3567cb3469a9aa1f27cc3063">isBitcast</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a bitcast instruction. <a href="#ac974851e3567cb3469a9aa1f27cc3063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e4fdd20c6b04f83aef00924bc65e15">isSelect</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is a select instruction. <a href="#a30e4fdd20c6b04f83aef00924bc65e15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ffc14f594434308433335d6b62ded60">isNotDuplicable</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction cannot be safely duplicated. <a href="#a7ffc14f594434308433335d6b62ded60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9df5fbb2543faa0659f9b31f907df9">isConvergent</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is convergent. <a href="#aaf9df5fbb2543faa0659f9b31f907df9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a996207483728c6ed75938076623eb642">hasDelaySlot</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the specified instruction has a delay slot which must be filled by the code generator. <a href="#a996207483728c6ed75938076623eb642">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b9443e375680a7b849d56ab42e19d6">canFoldAsLoad</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for instructions that can be folded as memory operands in other instructions. <a href="#af1b9443e375680a7b849d56ab42e19d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5346eae1e87fbd0af3b5080fb9c4f78">isRegSequenceLike</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves the same way as the generic REG_SEQUENCE instructions. <a href="#af5346eae1e87fbd0af3b5080fb9c4f78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc9150d35e4fe96ae38928498f2b5dc">isExtractSubregLike</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves the same way as the generic EXTRACT_SUBREG instructions. <a href="#a8dc9150d35e4fe96ae38928498f2b5dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24ef6c881a03e82d4644dbaadafff79">isInsertSubregLike</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves the same way as the generic INSERT_SUBREG instructions. <a href="#ad24ef6c881a03e82d4644dbaadafff79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction could possibly read memory. <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction could possibly modify memory. <a href="#ab96f3235c18e659758517d0532d606c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f5d15a7320dec2cfefb6617f711ab7">mayLoadOrStore</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction could possibly read or modify memory. <a href="#a17f5d15a7320dec2cfefb6617f711ab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00966a294fe7a54bf2f6a296e82fc8e1">mayRaiseFPException</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction could possibly raise a floating-point exception. <a href="#a00966a294fe7a54bf2f6a296e82fc8e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7961501e56424e3a7e21d34d6e109461">isCommutable</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this may be a 2- or 3-address instruction (of the form "X = op Y, Z, ..."), which produces the same result if Y and Z are exchanged. <a href="#a7961501e56424e3a7e21d34d6e109461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48b10169448732b2c0b13b8e7a256bf">isConvertibleTo3Addr</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 2-address instruction which can be changed into a 3-address instruction if needed. <a href="#aa48b10169448732b2c0b13b8e7a256bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320180749c883b427d229d1a2f3fefc3">usesCustomInsertionHook</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction requires custom insertion support when the DAG scheduler is inserting it into a machine basic block. <a href="#a320180749c883b427d229d1a2f3fefc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6808b4dcf3486acfdccbcefe27d9cb1d">hasPostISelHook</a> (QueryType Type=IgnoreBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction requires <em>adjustment</em> after instruction selection by calling a target hook. <a href="#a6808b4dcf3486acfdccbcefe27d9cb1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd72682fb9a02aab87877d61a66339a8">isRematerializable</a> (QueryType Type=AllInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction is a candidate for remat. <a href="#afd72682fb9a02aab87877d61a66339a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af782269e076a1a0e8911977433a02559">isAsCheapAsAMove</a> (QueryType Type=AllInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction has the same cost (or less) than a move instruction. <a href="#af782269e076a1a0e8911977433a02559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77fb7702a3aa266e97eaf2ee2b19542f">hasExtraSrcRegAllocReq</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction source operands have special register allocation requirements that are not captured by the operand register classes. <a href="#a77fb7702a3aa266e97eaf2ee2b19542f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a0c117b9aedd8ed85cd4a747ebb77c">hasExtraDefRegAllocReq</a> (QueryType Type=AnyInBundle) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction def operands have special register allocation requirements that are not captured by the operand register classes. <a href="#a11a0c117b9aedd8ed85cd4a747ebb77c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a> (const MachineInstr &amp;Other, MICheckType Check=CheckDefs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction is identical to <span class="doxyComputerOutput">Other</span>. <a href="#aab9a96f10af025498520e00ff044bec1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a> (const MachineInstr &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction is a debug instruction that represents an identical debug value to <span class="doxyComputerOutput">Other</span>. <a href="#a8d4914ca78a5bd34e64807479fc057cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc2f14c5e0de3c7ba77ed8d892a4c5a">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink 'this' from the containing basic block, and return it without deleting it. <a href="#a1bc2f14c5e0de3c7ba77ed8d892a4c5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471e524f23e926d8d76bcdaa6355d7eb">removeFromBundle</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this instruction from its basic block and return it without deleting it. <a href="#a471e524f23e926d8d76bcdaa6355d7eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2421adbb9996e1b15f03a8abb6c70a8">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink 'this' from the containing basic block and delete it. <a href="#ac2421adbb9996e1b15f03a8abb6c70a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9891e442de101ced8a1533a71511dbed">eraseFromBundle</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink 'this' from its basic block and delete it. <a href="#a9891e442de101ced8a1533a71511dbed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad803ef666d44b78308d571df8b445f63">isEHLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85cc92e3de77dfa4c19718a43b02eb16">isGCLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a500ac55b1c16a71c77fc50c482df643a">isAnnotationLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f137387193043b6e4f37112d60f748d">isLifetimeMarker</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b944330612f60ce857aebffe954e57">isLabel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> represents a label. <a href="#ab3b944330612f60ce857aebffe954e57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75489f444c9e3bdc12cb985c54d84a37">isCFIInstruction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82bec8563e9409362aaedd5346a3f17">isPseudoProbe</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0caab77831c0ee52b93185bcf64d180a">isPosition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071ce84bf9c71b9b7d6ffb30639ce602">isDebugValueList</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2502a65c42b09e02d163611edb263c84">isDebugLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f5ab028b0c4242fd4409a3e50028339">isDebugRef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d26e3ed3815037e0cc1b25a85c3a0e5">isDebugPHI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b77ab21dcde46feb97e401cfb444570">isDebugOrPseudoInstr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252a85dbac85d89e26fae5f8e3b87eff">isDebugOffsetImm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c4f9c9cf73f1c869a1c0eae73c150f">isIndirectDebugValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A DBG_VALUE is indirect iff the location operand is a register and the offset operand is an immediate. <a href="#ae4c4f9c9cf73f1c869a1c0eae73c150f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae45a9559b6fd1578fb4d12f341cbed57">isDebugEntryValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A DBG_VALUE is an entry value iff its debug expression contains the DW_OP_LLVM_entry_value operation. <a href="#ae45a9559b6fd1578fb4d12f341cbed57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7a3826a25ef43294d3434da71811e9">isUndefDebugValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a debug value which describes a part of a variable as unavailable. <a href="#adb7a3826a25ef43294d3434da71811e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a974b18e3dd15be812200ec75dc0d3137">isJumpTableDebugInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43bf1af480830a4d6604e969e3f38e9">isPHI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9723ca940711fa1a09c0d53efeef5fe">isKill</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120ccebe70e1b0ddf72fc776229d0025">isImplicitDef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1802220ee7c164e882ade3d80f1845">mayFoldInlineAsmRegOp</a> (unsigned OpId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the register operand can be folded with a load or store into a frame index. <a href="#afe1802220ee7c164e882ade3d80f1845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b98ba8c44d9287df1be03859570b589">isStackAligningInlineAsm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8">InlineAsm::AsmDialect</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b94b1143638cb1b18d976bba0b0ec3a">getInlineAsmDialect</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de0e8de0615ba9a3e4fa551e25ddcee">isInsertSubreg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5822e16afda1fcf154cfb4179bacef3c">isSubregToReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d97d09150ddcbcf5039f938111358ee">isRegSequence</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2f795dfcb9269e1263453796f4b994">isBundle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1912d4fbc40c61a12b1f770ad54dfd74">isCopy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee45760c97bf2dda6bee91508e6946e">isFullCopy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41b2896b8454188401b6e11a972a2d0">isExtractSubreg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2df666e80610d028fc34fc23a82dd27">isFakeUse</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3c8255141a4f5b7ed15fcf60118eb1">isCopyLike</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction behaves like a copy. <a href="#a1f3c8255141a4f5b7ed15fcf60118eb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add5255eb40b106f13738476389bfa5a6">isIdentityCopy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true is the instruction is an identity copy. <a href="#add5255eb40b106f13738476389bfa5a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaeaa72d4f5f8423ebade5ac38060b42">isTransient</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a transient instruction that is either very likely to be eliminated during register allocation (such as copy-like instructions), or if this instruction doesn't have an execution-time cost. <a href="#acaeaa72d4f5f8423ebade5ac38060b42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b0b34adc3bc0648be36c663c0e046b">getBundleSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of instructions inside the MI bundle, excluding the bundle header. <a href="#a76b0b34adc3bc0648be36c663c0e046b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2380c209ae5339835b5e6ea6d5c197ad">readsRegister</a> (Register Reg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> reads the specified register. <a href="#a2380c209ae5339835b5e6ea6d5c197ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac823eae276c8bfe6d8c819a3927b7333">readsVirtualRegister</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> reads the specified virtual register. <a href="#ac823eae276c8bfe6d8c819a3927b7333">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a374fc9d9064a93ef8a408f269d02389d">readsWritesVirtualRegister</a> (Register Reg, SmallVectorImpl&lt; unsigned &gt; *Ops=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pair of bools (reads, writes) indicating if this instruction reads or writes Reg. <a href="#a374fc9d9064a93ef8a408f269d02389d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81547ddac1cc7ddad9428925e49ab42b">killsRegister</a> (Register Reg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> kills the specified register. <a href="#a81547ddac1cc7ddad9428925e49ab42b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9024bfb74506b66f45d153234a802000">definesRegister</a> (Register Reg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> fully defines the specified register. <a href="#a9024bfb74506b66f45d153234a802000">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e91c5407ade0326e5dbd87e986e648">modifiesRegister</a> (Register Reg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> modifies (fully define or partially define) the specified register. <a href="#a66e91c5407ade0326e5dbd87e986e648">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e705934ca4178520c75d7ed1218cfc5">registerDefIsDead</a> (Register Reg, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the register is dead in this machine instruction. <a href="#a8e705934ca4178520c75d7ed1218cfc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad890cb0ba6262569913be1269acbf590">hasRegisterImplicitUseOperand</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> has an implicit-use operand of exactly the given register (not considering sub/super-registers). <a href="#ad890cb0ba6262569913be1269acbf590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a> (Register Reg, const TargetRegisterInfo *TRI, bool isKill=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the operand index that is a use of the specific register or -1 if it is not found. <a href="#a6f42d93281a5cbf5360f836c09166c06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab692b90c6e0e9b450f407896cbbe4b02">findRegisterUseOperand</a> (Register Reg, const TargetRegisterInfo *TRI, bool isKill=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper for findRegisterUseOperandIdx, it returns a pointer to the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> rather than an index. <a href="#ab692b90c6e0e9b450f407896cbbe4b02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a934c36cbb52619d7d75dfc0766e2b946">findRegisterUseOperand</a> (Register Reg, const TargetRegisterInfo *TRI, bool isKill=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a> (Register Reg, const TargetRegisterInfo *TRI, bool isDead=false, bool Overlap=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the operand index that is a def of the specified register or -1 if it is not found. <a href="#aeeed341d0f3c7220d070d766e3a0f584">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1df0cb1a8c3103a4266def94c3a670">findRegisterDefOperand</a> (Register Reg, const TargetRegisterInfo *TRI, bool isDead=false, bool Overlap=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper for findRegisterDefOperandIdx, it returns a pointer to the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> rather than an index. <a href="#afc1df0cb1a8c3103a4266def94c3a670">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedaafad0e3bea3243199613910e2a7ce">findRegisterDefOperand</a> (Register Reg, const TargetRegisterInfo *TRI, bool isDead=false, bool Overlap=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75925d9ebd5a8017581c9d07316be793">findFirstPredOperandIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the index of the first operand in the operand list that is used to represent the predicate. <a href="#a75925d9ebd5a8017581c9d07316be793">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a> (unsigned OpIdx, unsigned *GroupNo=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the index of the flag word operand that corresponds to operand OpIdx on an inline asm instruction. <a href="#af3caca8b1c9e27890d57f5755dc142fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a> (unsigned OpIdx, const TargetInstrInfo *TII, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the static register class constraint for operand OpIdx. <a href="#af551bfe7ee8756cbe50de3bb97478723">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3fa67a3a5da00dd6bc096cfbacd3a4">getRegClassConstraintEffectForVReg</a> (Register Reg, const TargetRegisterClass *CurRC, const TargetInstrInfo *TII, const TargetRegisterInfo *TRI, bool ExploreBundle=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Applies the constraints (def/use) implied by this MI on <span class="doxyComputerOutput">Reg</span> to the given <span class="doxyComputerOutput">CurRC</span>. <a href="#a3b3fa67a3a5da00dd6bc096cfbacd3a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f8cb24fba67649c1f32531d0f6ab90">getRegClassConstraintEffect</a> (unsigned OpIdx, const TargetRegisterClass *CurRC, const TargetInstrInfo *TII, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Applies the constraints (def/use) implied by the <span class="doxyComputerOutput">OpIdx</span> operand to the given <span class="doxyComputerOutput">CurRC</span>. <a href="#a88f8cb24fba67649c1f32531d0f6ab90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37e31e5df481d2f8a6f9f022886cf5e">tieOperands</a> (unsigned DefIdx, unsigned UseIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a tie between the register operands at DefIdx and UseIdx. <a href="#aa37e31e5df481d2f8a6f9f022886cf5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a> (unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the index of a tied register operand, find the operand it is tied to. <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df9a6b70a33aee123056cec0ed052c4">isRegTiedToUseOperand</a> (unsigned DefOpIdx, unsigned *UseOpIdx=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the index of a register def operand, check if the register def is tied to a source operand, due to either two-address elimination or inline assembly constraints. <a href="#a6df9a6b70a33aee123056cec0ed052c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391694f8040173dc0670bd273b170502">isRegTiedToDefOperand</a> (unsigned UseOpIdx, unsigned *DefOpIdx=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the use operand of the specified index is tied to a def operand. <a href="#a391694f8040173dc0670bd273b170502">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26854c9925fc93880d644c0dcac8ba7">clearKillInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears kill flags on all operands. <a href="#ae26854c9925fc93880d644c0dcac8ba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f59e1f6dd6677348ba082a10fc09061">substituteRegister</a> (Register FromReg, Register ToReg, unsigned SubIdx, const TargetRegisterInfo &amp;RegInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all occurrences of FromReg with ToReg:SubIdx, properly composing subreg indices where necessary. <a href="#a9f59e1f6dd6677348ba082a10fc09061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a> (Register IncomingReg, const TargetRegisterInfo *RegInfo, bool AddIfNotFound=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We have determined MI kills a register. <a href="#ac78902263d351fd8540aeb449d9cb53f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">clearRegisterKills</a> (Register Reg, const TargetRegisterInfo *RegInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all kill flags affecting Reg. <a href="#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a> (Register Reg, const TargetRegisterInfo *RegInfo, bool AddIfNotFound=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We have determined MI defined a register without a use. <a href="#afda2c0f22be043ae42b0ec71b661f565">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a32b52ea36d2c35a9860fe263d0574">clearRegisterDeads</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all dead flags on operands defining register <span class="doxyComputerOutput">Reg</span>. <a href="#ad4a32b52ea36d2c35a9860fe263d0574">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05427132a2cb380432ed752b5f2dea6b">setRegisterDefReadUndef</a> (Register Reg, bool IsUndef=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark all subregister defs of register <span class="doxyComputerOutput">Reg</span> with the undef flag. <a href="#a05427132a2cb380432ed752b5f2dea6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a79b68db2b8f84f92b1ee24352b3ce">addRegisterDefined</a> (Register Reg, const TargetRegisterInfo *RegInfo=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We have determined MI defines a register. <a href="#ad0a79b68db2b8f84f92b1ee24352b3ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2afcfcff9187a2201549d75d4e16149">setPhysRegsDeadExcept</a> (ArrayRef&lt; Register &gt; UsedRegs, const TargetRegisterInfo &amp;TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark every physreg used by this instruction as dead except those in the UsedRegs list. <a href="#ac2afcfcff9187a2201549d75d4e16149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a> (bool &amp;SawStore) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is safe to move this instruction. <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction would be trivially dead if all of its defined registers were dead. <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb834744243c11cb677261382ac15bea">isDead</a> (const MachineRegisterInfo &amp;MRI, LiveRegUnits *LivePhysRegs=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether an MI is dead. <a href="#abb834744243c11cb677261382ac15bea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a> (BatchAAResults *AA, const MachineInstr &amp;Other, bool UseTBAA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this instruction's memory access aliases the memory access of Other. <a href="#a3da773a37ef4e3325379dd6718317b74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55aec6d9959470668bae2aeb8a7c0768">mayAlias</a> (AAResults *AA, const MachineInstr &amp;Other, bool UseTBAA) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction may have an ordered or volatile memory reference, or if the information describing the memory reference is not available. <a href="#aabc3917d917c6247778c88107945d13b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2626405eab33f6bae29077772fd63115">isDereferenceableInvariantLoad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this load instruction never traps and points to a memory location whose value doesn't change during the execution of this function. <a href="#a2626405eab33f6bae29077772fd63115">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37fa340555fb189bce42efadf42c5253">isConstantValuePHI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified instruction is a PHI that always merges together the same virtual register, return the register, otherwise return <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register()</a>. <a href="#a37fa340555fb189bce42efadf42c5253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has side effects that are not modeled by mayLoad / mayStore, etc. <a href="#a8c161f5f015730ac6853c802c3693a41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c5324ccddfa1e364a70087e0434a0a">isLoadFoldBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is illegal to fold a load across this instruction. <a href="#ab7c5324ccddfa1e364a70087e0434a0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af408efad64e3aa0eef6c3a37c7794a83">allDefsAreDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all the defs of this instruction are dead. <a href="#af408efad64e3aa0eef6c3a37c7794a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f79b8dd21fa75c7c273ebb9177a6a7">allImplicitDefsAreDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all the implicit defs of this instruction are dead. <a href="#a39f79b8dd21fa75c7c273ebb9177a6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7a2f3baa7050ba9f95be0c1b71339f">getSpillSize</a> (const TargetInstrInfo *TII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a valid size if the instruction is a spill instruction. <a href="#acf7a2f3baa7050ba9f95be0c1b71339f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64aa9b0d6022db9f727893972c0bd9f0">getFoldedSpillSize</a> (const TargetInstrInfo *TII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a valid size if the instruction is a folded spill instruction. <a href="#a64aa9b0d6022db9f727893972c0bd9f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d1bd4ee7e40a15f8d22acca228dbc3">getRestoreSize</a> (const TargetInstrInfo *TII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a valid size if the instruction is a restore instruction. <a href="#a54d1bd4ee7e40a15f8d22acca228dbc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d05d77b880d0d3e4a480affaf85f5d">getFoldedRestoreSize</a> (const TargetInstrInfo *TII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a valid size if the instruction is a folded restore instruction. <a href="#a87d05d77b880d0d3e4a480affaf85f5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f26cdb79c726f4616b1cd7ae1996cd">copyImplicitOps</a> (MachineFunction &amp;MF, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy implicit register operands from specified instruction to this instruction. <a href="#a67f26cdb79c726f4616b1cd7ae1996cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a> (MachineFunction &amp;MF, const MachineOperand &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified operand to the instruction. <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf3514a1ace5d142cc33b48f3eb3f63">addOperand</a> (const MachineOperand &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an operand without providing an MF reference. <a href="#aabf3514a1ace5d142cc33b48f3eb3f63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a> (mop_iterator InsertBefore, ArrayRef&lt; MachineOperand &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts Ops BEFORE It. Can untie/retie tied operands. <a href="#a904f484cd7cfe20a0e7673399c88cc3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9117508fb00fda14207e7f968389544c">setDesc</a> (const MCInstrDesc &amp;TID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the instruction descriptor (thus opcode) of the current instruction with a new one. <a href="#a9117508fb00fda14207e7f968389544c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2641f071128da26317fab5b9594ec71">setDebugLoc</a> (DebugLoc DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace current source information with new such. <a href="#af2641f071128da26317fab5b9594ec71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b161ec90385105cb46a08b52139e60">removeOperand</a> (unsigned OpNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase an operand from an instruction, leaving it with one fewer operand than it started with. <a href="#ac3b161ec90385105cb46a08b52139e60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s memory reference descriptor list. <a href="#a6e05e3bfe64497149a8800b1830c4001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a> (MachineFunction &amp;MF, ArrayRef&lt; MachineMemOperand * &gt; MemRefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s memory reference descriptor list. <a href="#a5981137a17cad3d9b2276ad63e15ee40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4107c92fd8d37e8d0cb596f2a25d98">addMemOperand</a> (MachineFunction &amp;MF, MachineMemOperand *MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> to the machine instruction. <a href="#afc4107c92fd8d37e8d0cb596f2a25d98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a> (MachineFunction &amp;MF, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone another <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s memory reference descriptor list and replace ours with it. <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a> (MachineFunction &amp;MF, ArrayRef&lt; const MachineInstr * &gt; MIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the merge of multiple MachineInstrs' memory reference descriptors list and replace ours with it. <a href="#a7a5607fcb0a195620036bb0f1217c8a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a> (MachineFunction &amp;MF, MCSymbol *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a symbol that will be emitted just prior to the instruction itself. <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> (MachineFunction &amp;MF, MCSymbol *Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a symbol that will be emitted just after the instruction itself. <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a> (MachineFunction &amp;MF, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone another <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s pre- and post- instruction symbols and replace ours with it. <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a> (MachineFunction &amp;MF, MDNode *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a marker on instructions that denotes where we should create and emit heap alloc site labels. <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae76989792a75b7735546e69711d22209">setPCSections</a> (MachineFunction &amp;MF, MDNode *MD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a> (MachineFunction &amp;MF, MDNode *MMRAs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a> (MachineFunction &amp;MF, uint32_t Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the CFI type for the instruction. <a href="#a1902a720147e652fa4a4857e069f4dd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36538e83424d5c406c294a6c365f9fe9">mergeFlagsWith</a> (const MachineInstr &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the MIFlags which represent both MachineInstrs. <a href="#a36538e83424d5c406c294a6c365f9fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ac3225c216191d957cf56ad28f1c84">copyIRFlags</a> (const Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy all flags to MachineInst MIFlags. <a href="#a49ac3225c216191d957cf56ad28f1c84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e66e9ca7739874b25b9337940c26a0a">untieRegOperand</a> (unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Break any tie involving OpIdx. <a href="#a8e66e9ca7739874b25b9337940c26a0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be4041e5133aa22135fa2890cc7aeae">addImplicitDefUseOperands</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add all implicit def and use operands to this instruction. <a href="#a2be4041e5133aa22135fa2890cc7aeae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5105322139844c10dc05539f70ff3eca">collectDebugValues</a> (SmallVectorImpl&lt; MachineInstr * &gt; &amp;DbgValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan instructions immediately following MI and collect any matching DBG_VALUEs. <a href="#a5105322139844c10dc05539f70ff3eca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf972edd3d60e198b996c65e05c4a5a">changeDebugValuesDefReg</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all DBG_VALUEs that point to the register def in this instruction and point them to <span class="doxyComputerOutput">Reg</span> instead. <a href="#aaaf972edd3d60e198b996c65e05c4a5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf83915bd66f2a610c72f3d028f8704">setDebugValueUndef</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets all register debug operands in this debug value instruction to be undef. <a href="#a0cf83915bd66f2a610c72f3d028f8704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb98e93a7bcdce78a80a51a00610c2c">getFirst2Regs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98055346309284ec85c366c2802bd265">getFirst3Regs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b18514df4193347c1d9ff3773ca850">getFirst4Regs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c0bab24b110610c39c166eb5db9ddf">getFirst5Regs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620b1d8de0e32491f106ddc997914153">getFirst2LLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb0ed106bd6d33c0cf49a89083a74ad">getFirst3LLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b80d7b9f05e663c35bd72cece6ebd7">getFirst4LLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e82295f594d02e8290f214b5a4c3551">getFirst5LLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817d92911624542113807dc07a46bfb5">getFirst2RegLLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31012ec441c425a3eeb652d31ab0a8ab">getFirst3RegLLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80edb692b5f12ebc13ea0c6558e2cc85">getFirst4RegLLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1345402d2906eacc2db93c4bb59cf861">getFirst5RegLLTs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916df6545831877c774f5ba9a7963805">setParent</a> (MachineBasicBlock *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61de1bcd9c9e1603005789971115446d">dumprImpl</a> (const MachineRegisterInfo &amp;MRI, unsigned Depth, unsigned MaxDepth, SmallPtrSetImpl&lt; const MachineInstr * &gt; &amp;AlreadySeenInstrs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8fe33d35fa1a1033b4e8f9fdcc00d0">getRegInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this instruction is embedded into a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>, return the <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> object for the current function, otherwise return null. <a href="#a4d8fe33d35fa1a1033b4e8f9fdcc00d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d8f4791d88a244924d67cf5fa89ef4e">getRegInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024b74f208e958ab92813318ce5daf00">removeRegOperandsFromUseLists</a> (MachineRegisterInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink all of the register operands in this instruction from their respective use lists. <a href="#a024b74f208e958ab92813318ce5daf00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340bd0c437deaa0c106d2f7bd77f7370">addRegOperandsToUseLists</a> (MachineRegisterInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add all of the register operands in this instruction from their respective use lists. <a href="#a340bd0c437deaa0c106d2f7bd77f7370">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9722fe61892279688b0c88e652d0c6d">hasPropertyInBundle</a> (uint64_t Mask, QueryType Type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Slow path for hasProperty when we're dealing with a bundle. <a href="#aa9722fe61892279688b0c88e652d0c6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b81f3a02c0820b0084a17687a5cbed">getRegClassConstraintEffectForVRegImpl</a> (unsigned OpIdx, Register Reg, const TargetRegisterClass *CurRC, const TargetInstrInfo *TII, const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements the logic of getRegClassConstraintEffectForVReg for the this MI and the given operand index <span class="doxyComputerOutput">OpIdx</span>. <a href="#a57b81f3a02c0820b0084a17687a5cbed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab266e3f685642c42995b2fe3dab43dd1">setExtraInfo</a> (MachineFunction &amp;MF, ArrayRef&lt; MachineMemOperand * &gt; MMOs, MCSymbol *PreInstrSymbol, MCSymbol *PostInstrSymbol, MDNode *HeapAllocMarker, MDNode *PCSections, uint32_t CFIType, MDNode *MMRAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores extra instruction information inline or allocates as ExtraInfo based on the number of pointers. <a href="#ab266e3f685642c42995b2fe3dab43dd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfef9b79b44d26ec7c470ec309774b58">MCID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae743252fbb1f60699b04bde8750b313c">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb9c9ca08ddcb2f8fee62b3609028d2">Operands</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e48a6fa0197595a03b3464271f7ec0">NumOperands</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of operands on instruction. <a href="#ab8e48a6fa0197595a03b3464271f7ec0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity">OperandCapacity</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c85a084eb406b8b51b9f41f2a3d96a">CapOperands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44041bc3d1bf9635849d20804dc6a2b5">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Various bits of additional information about the machine instruction. <a href="#a44041bc3d1bf9635849d20804dc6a2b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab813c2d1ea8236843211deae264842a6">AsmPrinterFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Various bits of information used by the <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> to emit helpful comments. <a href="#ab813c2d1ea8236843211deae264842a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointersumtype">PointerSumType</a>&lt; ExtraInfoInlineKinds, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; EIIK_MMO, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; EIIK_PreInstrSymbol, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; EIIK_PostInstrSymbol, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; EIIK_OutOfLine, ExtraInfo * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac88cf2c3434a399afb937fb6d1598d0d">Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afedced451fcdddffdd8963a710c1d721">DbgLoc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf59d7ef807d43ca5d21e7da64f8900">DebugInstrNum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique instruction number. <a href="#acbf59d7ef807d43ca5d21e7da64f8900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed808f363d7186350fe6892e223eeebe">Opcode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached opcode from <a href="/web-llvm/docs/api/namespaces/llvm/mcid">MCID</a>. <a href="#aed808f363d7186350fe6892e223eeebe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Operand, typename Instruction&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05c54bfb75dbb555ab457e768bbcfe73">getDebugOperandsForReg</a> (Instruction *MI, Register Reg) -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; Operand *, std::function&lt; bool(Operand &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>)&gt; &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range of all of the operands that correspond to a debug use of <span class="doxyComputerOutput">Reg</span>. <a href="#a05c54bfb75dbb555ab457e768bbcfe73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa9ad46c9ec8c4de6dca3245edeedfe">copyFlagsFromInstruction</a> (const Instruction &amp;I)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e92a9ed8a30f709a7e85bf43fe47e8">opIsRegDef</a> (const MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e69335c61f27c5866da1f5bac6812df">opIsRegUse</a> (const MachineOperand &amp;Op)</td>
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

<p>Representation of each machine instruction.</p>


<p>This class isn't a POD type, but it must have a trivial destructor. When a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> is deleted, all the contained MachineInstrs are deallocated without having their destructor called.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_mop\_iterator {#a476971826fa13b07e28ad971ec5a3234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineInstr::const_mop_iterator =  const MachineOperand *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### filtered\_const\_mop\_iterator {#ad50cb55604768b56d55eba76ed4568be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineInstr::filtered_const_mop_iterator = 
      filter_iterator&lt;const_mop_iterator, bool (*)(const MachineOperand &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### filtered\_mop\_iterator {#a9206189b1d54e585e0d3d0c9fd698b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineInstr::filtered_mop_iterator = 
      filter_iterator&lt;mop_iterator, bool (*)(const MachineOperand &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### mmo\_iterator {#a00e87ec17cd2a1eaeb65d82c698b61d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineInstr::mmo_iterator =  ArrayRef&lt;MachineMemOperand *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### mop\_iterator {#ab5b1fcfd0e1eddba786fefcdf28f1689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineInstr::mop_iterator =  MachineOperand *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>iterator/begin/end - Iterate over all operands of a machine instruction.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### OperandCapacity {#a4439c0896d3c1b03846173f0e49751cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineInstr::OperandCapacity =  ArrayRecycler&lt;MachineOperand&gt;::Capacity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### CommentFlag {#a0ac990e2b3f7973d16c33555e9adf9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineInstr::CommentFlag </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags to specify different kinds of comments to output in assembly code.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ReloadReuse<a id="a0ac990e2b3f7973d16c33555e9adf9aeade2c15857e3d2b12a4459c3510421493"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSchedComment<a id="a0ac990e2b3f7973d16c33555e9adf9aea7a908f8bc1963408ea34c83be857ae67"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAsmComments<a id="a0ac990e2b3f7973d16c33555e9adf9aea4752d20baac7b6876b6cc5c7d46a29a9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

</table>
</dd>
</dl>


<p>These flags carry semantic information not otherwise easily derivable from the IR text.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### ExtraInfoInlineKinds {#a3bcea80716879e989df4147a48b0bd29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineInstr::ExtraInfoInlineKinds </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumeration of the kinds of inline extra info available.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EIIK_MMO<a id="a3bcea80716879e989df4147a48b0bd29acc9352b602b9eaaafac1ae2c8bb8b0f8"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EIIK_PreInstrSymbol<a id="a3bcea80716879e989df4147a48b0bd29a4da1a4dfd8f5b071e27662fa831c6ece"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EIIK_PostInstrSymbol<a id="a3bcea80716879e989df4147a48b0bd29afd2e59f9ca6deac967dcbabba283d09c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EIIK_OutOfLine<a id="a3bcea80716879e989df4147a48b0bd29a038ba057ef9eb55ffb082f2164801c4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>It is important that the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a></span> inline kind has a tag value of zero to make it accessible as an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a></span>.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### MICheckType {#ab7650f958c093f7c5faf8c69dbc8c462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineInstr::MICheckType </td>
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
<td class="doxyEnumItemName">CheckDefs<a id="ab7650f958c093f7c5faf8c69dbc8c462a35b423af55ddd5d9081754328aa7f9c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CheckKillDead<a id="ab7650f958c093f7c5faf8c69dbc8c462ad84865ceeee6b326942a3ed2ad37f815"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IgnoreDefs<a id="ab7650f958c093f7c5faf8c69dbc8c462a24c57e99cada0b167e5132984979bc83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IgnoreVRegDefs<a id="ab7650f958c093f7c5faf8c69dbc8c462a5f3288f908142ddad3dd5d8a95cfa364"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### MIFlag {#aafacf84de1cb994a92dc045f4aa1d518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineInstr::MIFlag </td>
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
<td class="doxyEnumItemName">NoFlags<a id="aafacf84de1cb994a92dc045f4aa1d518a75967179a013c48b7d5b1690cb0b47cc"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrameSetup<a id="aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrameDestroy<a id="aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BundledPred<a id="aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BundledSucc<a id="aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmNoNans<a id="aafacf84de1cb994a92dc045f4aa1d518aba11aa58176a446ba70d4f0ad0e04418"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmNoInfs<a id="aafacf84de1cb994a92dc045f4aa1d518a45ffd15293a16979f698cec4e2c60ad0"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmNsz<a id="aafacf84de1cb994a92dc045f4aa1d518adc42a7d40f8bd9c7f1a9c2beb0135fdc"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmArcp<a id="aafacf84de1cb994a92dc045f4aa1d518a43892bfec2e4bb79639d4b4f1cf28ae8"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmContract<a id="aafacf84de1cb994a92dc045f4aa1d518a9a1da4c7c2a2a2ed0d083327dd28277c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmAfn<a id="aafacf84de1cb994a92dc045f4aa1d518a4802af6d0cf3b900adb6296bccedf2a0"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FmReassoc<a id="aafacf84de1cb994a92dc045f4aa1d518a7e452f6e23b696b4701cb18790b32992"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoUWrap<a id="aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSWrap<a id="aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsExact<a id="aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoFPExcept<a id="aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoMerge<a id="aafacf84de1cb994a92dc045f4aa1d518a4a1592bf2f68ec050798e3aeb6a7b095"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unpredictable<a id="aafacf84de1cb994a92dc045f4aa1d518a87ff88efff0f69c3e3f902410756ddef"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoConvergent<a id="aafacf84de1cb994a92dc045f4aa1d518a09808ae32b91764194984d6892e40a2e"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonNeg<a id="aafacf84de1cb994a92dc045f4aa1d518a3453657a772c3023f6ef942525db0d5d"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Disjoint<a id="aafacf84de1cb994a92dc045f4aa1d518ab9f2d292718c407a75b2f2c829c1c874"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoUSWrap<a id="aafacf84de1cb994a92dc045f4aa1d518a1eb5c75dbc40abd0d7998aeefd1c758b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SameSign<a id="aafacf84de1cb994a92dc045f4aa1d518ae6a23fd6cabf87a0e53689d9b18620ad"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 21)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### QueryType {#a26e1467ec6a91a35dfc32239e50f0fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineInstr::QueryType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>API for querying <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> properties.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IgnoreBundle<a id="a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnyInBundle<a id="a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllInBundle<a id="a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>They are the same as <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> queries but they are bundle aware.</p>


<p>Definition at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ilist\_callback\_traits&lt; MachineBasicBlock &gt; {#acbd6646c0c037f87ce89191e20336d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/ilist-callback-traits">ilist_callback_traits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### ilist\_traits&lt; MachineInstr &gt; {#a5acbf433c0f6fc94a353ddaed7bdaa28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/ilist-traits">ilist_traits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### MachineFunction {#ac423fefe048ace18159808c5592ae74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a2be4041e5133aa22135fa2890cc7aeae">addImplicitDefUseOperands</a>, <a href="#afc4107c92fd8d37e8d0cb596f2a25d98">addMemOperand</a>, <a href="#aabf3514a1ace5d142cc33b48f3eb3f63">addOperand</a>, <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a>, <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="#a67f26cdb79c726f4616b1cd7ae1996cd">copyImplicitOps</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#a1e8cfd2dc5bfc62862b1c75c20a1ee66">getDebugInstrNum</a>, <a href="#a269e83f53595da3ec459010b8f945afc">getMF</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="#ab419785650ef9728b5305d220179017c">print</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineInstr() {#ae8b6b28587169b4ac00f806e448782a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstr::MachineInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MachineInstr() {#a78645f0f9262e1a7357308177f8ec23a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr::MachineInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor creates a copy of the given <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> in the given <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> ctor - Copies <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> arg exactly.</p>


<p>Does not copy the number from debug instruction numbering, to preserve uniqueness.</p>


<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### MachineInstr() {#a2aa221dd55a2ed253b3d2e4bb982ccd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr::MachineInstr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; TID, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, bool NoImp=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor create a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> and add the implicit operands.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> ctor - This constructor creates a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> and adds the implicit operands.</p>


<p>It reserves space for number of operands specified by <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>. An explicit <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> is supplied.</p>


<p>It reserves space for the number of operands specified by the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>.</p>


<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineInstr() {#aff89b555a3272b39e2185acd5741da04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstr::~MachineInstr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a796234c977cac1502fdedc7bf67569ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; llvm::MachineInstr::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### dump() {#accc60d2019e9dff57bb0918a94422ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineInstr::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ab419785650ef9728b5305d220179017c">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9eb43774a0046a364f5c45f94576bc43">llvm::PPCInstrInfo::foldFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a2eff58d9105525f19d5cbe2fa6969d6e">llvm::SMSchedule::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4da36cb65ef881f12fe1d40a47223a61">MoveVPNOTBeforeFirstUser</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>.</p>

</div>
</div>

### dumpr() {#a47b14770ed9fb839f309757ca2adc80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineInstr::dumpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned MaxDepth=UINT_MAX)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> the current instruction and the instructions defining its operands and so on until we reach <span class="doxyComputerOutput">MaxDepth</span>.</p>

<p>Declaration at line 1868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getTypeToPrint() {#a9dbc9a748353035febcc488160ba9956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT MachineInstr::getTypeToPrint (unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; PrintedTypes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debugging support

Determine the generic type to be printed (if needed) on uses and defs.</p>

<p>Declaration at line 1841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1670 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">getDesc</a>, <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="#af33de0b50f93d38f9fab12e8adf7ba62">isVariadic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>.</p>


<p>Referenced by <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### hasComplexRegisterTies() {#a9d2b6142e2253bdad20b1f980f53f216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::hasComplexRegisterTies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true when an instruction has tied register that can't be determined by the instruction's descriptor.</p>


<p>This is useful for MIR printing, to determine whether we need to print the ties or not.</p>


<p>Declaration at line 1847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">getDesc</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>.</p>


<p>Referenced by <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### print() {#ab419785650ef9728b5305d220179017c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsStandalone=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool SkipOpers=false, bool SkipDebugLoc=false, bool AddNewLine=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this MI to <span class="doxyComputerOutput">OS</span>.</p>


<p>Don't print information that can be inferred from other instructions if <span class="doxyComputerOutput">IsStandalone</span> is false. It is usually true when only a fragment of the function is printed. Only print the defs and the opcode if <span class="doxyComputerOutput">SkipOpers</span> is true. Otherwise, also print operands if <span class="doxyComputerOutput">SkipDebugLoc</span> is true. Otherwise, also print the debug loc, with a terminating newline. <span class="doxyComputerOutput">TII</span> is used to print the opcode name. If it's not present, but the MI is in a function, the opcode will be printed using the function's TII.</p>


<p>Declaration at line 1858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="#ab419785650ef9728b5305d220179017c">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#accc60d2019e9dff57bb0918a94422ebb">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afbb37cc24abd3ed381b0fd496351bd17">llvm::ScheduleDAGInstrs::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="#ab419785650ef9728b5305d220179017c">print</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a3460671809bfea01d71388f2e45c3c50">llvm::SMSchedule::print</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a>.</p>

</div>
</div>

### print() {#a48e904486c2be7b98450bc2306c10648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsStandalone=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool SkipOpers=false, bool SkipDebugLoc=false, bool AddNewLine=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1750 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca">llvm::InlineAsm::AD_ATT</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ac2322cfab42cb6c46aa198861244231e">llvm::InlineAsm::AD_Intel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ab9f2d292718c407a75b2f2c829c1c874">Disjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a68a61079919e61d3af1002124c2f1ff9">llvm::InlineAsm::Extra_HasSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ada6152484586a08fa711d4b0d44c87e5">llvm::InlineAsm::Extra_IsAlignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a9921f5d5868939f49675e7fe34d1be70">llvm::InlineAsm::Extra_IsConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370aa21b27c3cc4550dcd3ff599dbe76d0c3">llvm::InlineAsm::Extra_MayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab01e1dce8dabbbb3d14ed5f34c366008">llvm::InlineAsm::Extra_MayStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a4802af6d0cf3b900adb6296bccedf2a0">FmAfn</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a43892bfec2e4bb79639d4b4f1cf28ae8">FmArcp</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a1da4c7c2a2a2ed0d083327dd28277c">FmContract</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a45ffd15293a16979f698cec4e2c60ad0">FmNoInfs</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518aba11aa58176a446ba70d4f0ad0e04418">FmNoNans</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518adc42a7d40f8bd9c7f1a9c2beb0135fdc">FmNsz</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a7e452f6e23b696b4701cb18790b32992">FmReassoc</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">FrameDestroy</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">FrameSetup</a>, <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="#abb10ef030fba4ea901518a0c8dbef3e2">getDebugLoc</a>, <a href="#a9ce3843932b6ae1c23228017f11eef25">getDebugVariable</a>, <a href="#abfcdb704dc6511a2c0b93fe4e5987182">getDebugVariableOp</a>, <a href="#a33365204be9cb132de322e3713253b57">getFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a8b94b1143638cb1b18d976bba0b0ec3a">getInlineAsmDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#ade110db5cd02d02d8d11534fa679b52b">llvm::InlineAsm::getMemConstraintName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57b590606040d1c856a1d43aa0680364">llvm::MachineOperand::getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#a9dbc9a748353035febcc488160ba9956">getTypeToPrint</a>, <a href="#a9d2b6142e2253bdad20b1f980f53f216">hasComplexRegisterTies</a>, <a href="#a75489f444c9e3bdc12cb985c54d84a37">isCFIInstruction</a>, <a href="#a2502a65c42b09e02d163611edb263c84">isDebugLabel</a>, <a href="#a4f5ab028b0c4242fd4409a3e50028339">isDebugRef</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a>, <a href="#a071ce84bf9c71b9b7d6ffb30639ce602">isDebugValueList</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">IsExact</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="#ae4c4f9c9cf73f1c869a1c0eae73c150f">isIndirectDebugValue</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7bce8907b3cea3c34b9eeac6480bc955">llvm::MachineOperand::isMetadata</a>, <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>, <a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>, <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370aae2aa90a74f555d8cc300b2b36403d1d">llvm::InlineAsm::MIOp_AsmString</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ad8e4e0d44daebe8c07cf5d6d60a4fc30">llvm::InlineAsm::MIOp_FirstOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893">NoFPExcept</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a4a1592bf2f68ec050798e3aeb6a7b095">NoMerge</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a3453657a772c3023f6ef942525db0d5d">NonNeg</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">NoSWrap</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">NoUWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aedeaf186a99c875b4196318a4083ff77">llvm::MachineOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#abea60f56bef2a0f9437eed8c8bb9ec58">llvm::Metadata::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2c59687e1086bf24ffa307eaee13c3d3">llvm::MachineOperand::printSubRegIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af04079051720988fb6801f962d034e03">llvm::MachineOperand::printSymbol</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ae6a23fd6cabf87a0e53689d9b18620ad">SameSign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#ab48e3dab3c79330a34264424247f0276">tryToGetTargetInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addImplicitDefUseOperands() {#a2be4041e5133aa22135fa2890cc7aeae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::addImplicitDefUseOperands (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add all implicit def and use operands to this instruction.</p>

<p>Declaration at line 2001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>.</p>

</div>
</div>

### addMemOperand() {#afc4107c92fd8d37e8d0cb596f2a25d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::addMemOperand (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> to the machine instruction.</p>


<p>This function should be used only occasionally. The setMemRefs function is the primary method for setting up a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s MemRefs list.</p>


<p>Declaration at line 1927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin</a>, <a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">memoperands_end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae565d45627e1678a3e37bd6a016c561c">llvm::MachineInstrBuilder::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2432d0bb09d9fe3b6bb004d8dbf77a99">llvm::TargetInstrInfo::foldMemoryOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>.</p>

</div>
</div>

### addOperand() {#a469e271fba3a9b52dad4fa54eaf44e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::addOperand (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the specified operand to the instruction.</p>


<p>addOperand - Add the specified operand to the instruction.</p>


<p>If it is an implicit operand, it is added to the end of the operand list. If it is an explicit operand it is added at the end of the explicit operand list (before the first implicit operand).</p>


<p>MF must be the machine function that was used to allocate this instruction.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> provides a more convenient interface for creating instructions and adding operands.</p>


<p>If it is an implicit operand, it is added to the end of the operand list. If it is an explicit operand it is added at the end of the explicit operand list (before the first implicit operand).</p>


<p>Declaration at line 1885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a7cc879238c148aac2540bca0ae4e0695">llvm::MachineFunction::allocateOperandArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a5c48ac93280e646c7d7837db0fc7ffb3">llvm::MachineFunction::deallocateOperandArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1aa8498cb1d31308a367c23286fa443716">llvm::MCOI::EARLY_CLOBBER</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity/#ab52c84454e451fabe417985306501afb">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::get</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity/#a1d916c19b79f38116c50c3f5a23c12ec">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::getNext</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity/#a43f20d00d7dda4241616ef78bad7b1d3">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::getSize</a>, <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a1c81cc103e832c555a8b2df1b597c72a">moveOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab986279c9e6cf7ba9afd4c7da198bacf">llvm::MachineOperand::setIsDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9fcb795c017b82c1a259882b060ddc06">llvm::MachineOperand::setIsEarlyClobber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a> and <a href="#aa37e31e5df481d2f8a6f9f022886cf5e">tieOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6eb17a3fc032cb29dbc1908f1d4ba046">llvm::MachineInstrBuilder::addBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3348f4e81264ccfe03832f141fdf44a3">llvm::MachineInstrBuilder::addCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a95c7b5ed23471212aeaba1eee6501261">llvm::MachineInstrBuilder::addFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9117be19af857a7bdcee7bdf0279024c">llvm::MachineInstrBuilder::addGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="#a2be4041e5133aa22135fa2890cc7aeae">addImplicitDefUseOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7ac6e2ee4b04561d22ba0bdc2d32897f">llvm::MachineInstrBuilder::addIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#aaa7ad3e87d858a3ed3b3dc8b05b70078">llvm::MachineInstrBuilder::addJumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="#aabf3514a1ace5d142cc33b48f3eb3f63">addOperand</a>, <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6d40d83c14042582354b5d875ed7f2d8">llvm::MachineInstrBuilder::addPredicate</a>, <a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a>, <a href="#ad0a79b68db2b8f84f92b1ee24352b3ce">addRegisterDefined</a>, <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a8880ccaea51a4ee9b48c3c8d7fbfebf4">llvm::MachineInstrBuilder::addRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a846993bea18636f4fd47bbe401fece04">llvm::MachineInstrBuilder::addShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7ffeb5b3940506a54e69e72e26e2a6cd">llvm::MachineInstrBuilder::addSym</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a0bc7ed8aefe042984bce6ea95ad5f1ec">llvm::MachineInstrBuilder::addTargetIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="#a67f26cdb79c726f4616b1cd7ae1996cd">copyImplicitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a851a237b27ce366221fcb1daf2f0d119">llvm::HexagonFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>.</p>

</div>
</div>

### addOperand() {#aabf3514a1ace5d142cc33b48f3eb3f63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::addOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an operand without providing an MF reference.</p>


<p>This only works for instructions that are inserted in a basic block.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> and the two-argument addOperand(MF, MO) should be preferred.</p>


<p>Declaration at line 1892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### addRegisterDead() {#afda2c0f22be043ae42b0ec71b661f565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::addRegisterDead (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * RegInfo, bool AddIfNotFound=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We have determined MI defined a register without a use.</p>


<p>Look for the operand that defines it and mark it as IsDead. If AddIfNotFound is true, add a implicit operand if it's not found. Returns true if the operand exists / is added.</p>


<p>Declaration at line 1724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ac3b161ec90385105cb46a08b52139e60">removeOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a52300ffc2cad932b8451cdd3ae41a470">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionrethardening-cpp-/x86loadvalueinjectionrethardeningpass/#a555db007ae6df71fb9fa02662e2c8643">anonymous{X86LoadValueInjectionRetHardening.cpp}::X86LoadValueInjectionRetHardeningPass::runOnMachineFunction</a>.</p>

</div>
</div>

### addRegisterDefined() {#ad0a79b68db2b8f84f92b1ee24352b3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::addRegisterDefined (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * RegInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We have determined MI defines a register.</p>


<p>Make sure there is an operand defining Reg.</p>


<p>Declaration at line 1737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="#ade4229c653b0cbcaca057e8af5002783">all_defs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="#afc1df0cb1a8c3103a4266def94c3a670">findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a9cb1dd3dd16025fc64f52adb12c9ce5f">llvm::SparcInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a669f90d5fe703ecfe25fb738553f6ea5">copyPhysSubRegs</a> and <a href="#ac2afcfcff9187a2201549d75d4e16149">setPhysRegsDeadExcept</a>.</p>

</div>
</div>

### addRegisterKilled() {#ac78902263d351fd8540aeb449d9cb53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::addRegisterKilled (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> IncomingReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * RegInfo, bool AddIfNotFound=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We have determined MI kills a register.</p>


<p>Look for the operand that uses it and mark it as IsKill. If AddIfNotFound is true, add a implicit operand if it's not found. Returns true if the operand exists / is added.</p>


<p>Declaration at line 1712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2070 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">llvm::MachineOperand::isDebug</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a391694f8040173dc0670bd273b170502">isRegTiedToDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ac3b161ec90385105cb46a08b52139e60">removeOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a9cb1dd3dd16025fc64f52adb12c9ce5f">llvm::SparcInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad8b8d94aaf80cefc49bc3263f05cd741">llvm::VEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a669f90d5fe703ecfe25fb738553f6ea5">copyPhysSubRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a404db50d68f1ca8d28396b5e2deb061d">llvm::VEInstrInfo::expandPostRAPseudo</a>.</p>

</div>
</div>

### all\_defs() {#ade4229c653b0cbcaca057e8af5002783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filtered_mop_iterator &gt; llvm::MachineInstr::all_defs ()</td>
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

<p>Returns an iterator range over all operands that are (explicit or implicit) register defs.</p>

<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a> and <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>.</p>


<p>Referenced by <a href="#ad0a79b68db2b8f84f92b1ee24352b3ce">addRegisterDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="#ad4a32b52ea36d2c35a9860fe263d0574">clearRegisterDeads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="#abb834744243c11cb677261382ac15bea">isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>, <a href="#a05427132a2cb380432ed752b5f2dea6b">setRegisterDefReadUndef</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>.</p>

</div>
</div>

### all\_defs() {#a9ed7df9f98920ad21ef28dc7e0e70f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filtered_const_mop_iterator &gt; llvm::MachineInstr::all_defs ()</td>
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

<p>Returns an iterator range over all operands that are (explicit or implicit) register defs.</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a> and <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>.</p>

</div>
</div>

### all\_uses() {#a3daf8e155bf0aa3e65b5260bfe3698c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filtered_mop_iterator &gt; llvm::MachineInstr::all_uses ()</td>
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

<p>Returns an iterator range over all operands that are (explicit or implicit) register uses.</p>

<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a> and <a href="#a3949f157e1034f6cb5d16ad708059aa3">uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8625c1e6c9bc82f2eaef39d3fff65a8">llvm::ScheduleDAGInstrs::addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>.</p>

</div>
</div>

### all\_uses() {#a7954d5796d6983c4a71e1cf1a838d7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filtered_const_mop_iterator &gt; llvm::MachineInstr::all_uses ()</td>
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

<p>Returns an iterator range over all operands that are (explicit or implicit) register uses.</p>

<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a> and <a href="#a3949f157e1034f6cb5d16ad708059aa3">uses</a>.</p>

</div>
</div>

### allDefsAreDead() {#af408efad64e3aa0eef6c3a37c7794a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::allDefsAreDead ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all the defs of this instruction are dead.</p>


<p>allDefsAreDead - Return true if all the defs of this instruction are dead.</p>


<p>Declaration at line 1815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a> and <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>.</p>

</div>
</div>

### allImplicitDefsAreDead() {#a39f79b8dd21fa75c7c273ebb9177a6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::allImplicitDefsAreDead ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all the implicit defs of this instruction are dead.</p>

<p>Declaration at line 1818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad0666b4ee4d5d2ade97f5f1e63865bab">implicit_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>.</p>

</div>
</div>

### bundleWithPred() {#a0aad617bc1bdef5bda2689f7a9fd06f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::bundleWithPred ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bundle this instruction with its predecessor.</p>


<p>This can be an unbundled instruction, or it can be the first instruction in a bundle.</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">BundledSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a>, <a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">isBundledWithPred</a> and <a href="#aba86b0738c2ab2a52688b846c45bfe59">setFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3c50b05be0be83e693f50b87284c76d6">llvm::MachineFunction::cloneMachineInstrBundle</a> and <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>.</p>

</div>
</div>

### bundleWithSucc() {#a21273844821e851afa28968bdd6ff10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::bundleWithSucc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bundle this instruction with its successor.</p>


<p>This can be an unbundled instruction, or it can be the last instruction in a bundle.</p>


<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">BundledSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a>, <a href="#ad07416ea31edd139a4ebe5b42a6f80b0">isBundledWithSucc</a> and <a href="#aba86b0738c2ab2a52688b846c45bfe59">setFlag</a>.</p>

</div>
</div>

### canFoldAsLoad() {#af1b9443e375680a7b849d56ab42e19d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::canFoldAsLoad (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true for instructions that can be folded as memory operands in other instructions.</p>


<p>The most common use for this is instructions that are simple loads from memory that don't modify the loaded value in any way, but it can also be used for instructions that can be expressed as constant-pool loads, such as V_SETALLONES on x86, to allow them to be folded when it is beneficial. This should only be set on instructions that return a value in their only virtual register definition.</p>


<p>Definition at line 1100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023aae43507b1a7708c07602a361936f7de3">llvm::MCID::FoldableAsLoad</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2432d0bb09d9fe3b6bb004d8dbf77a99">llvm::TargetInstrInfo::foldMemoryOperand</a>.</p>

</div>
</div>

### changeDebugValuesDefReg() {#aaaf972edd3d60e198b996c65e05c4a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::changeDebugValuesDefReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all DBG_VALUEs that point to the register def in this instruction and point them to <span class="doxyComputerOutput">Reg</span> instead.</p>

<p>Declaration at line 2009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2480 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### clearAsmPrinterFlag() {#a3381aa77ac8bf4b65adf2d02a78c4dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::clearAsmPrinterFlag (<a href="#a0ac990e2b3f7973d16c33555e9adf9ae">CommentFlag</a> Flag)</td>
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

<p>Clear specific <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> flags.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### clearAsmPrinterFlags() {#a1cc4487354633e23a68f6ca683d593f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::clearAsmPrinterFlags ()</td>
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

<p>Clear the <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> bitvector.</p>

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### clearFlag() {#a859897c8a9706acd4c065d857254d58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::clearFlag (<a href="#aafacf84de1cb994a92dc045f4aa1d518">MIFlag</a> Flag)</td>
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

<p>clearFlag - Clear a MI flag.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="#a6780a3b4a7f87d5fc85574207fa02c60">unbundleFromPred</a> and <a href="#ade1d83105d6c2d3de29fca286f9d1b5a">unbundleFromSucc</a>.</p>

</div>
</div>

### clearFlags() {#a7751cd90dd24d01b61a431d2a2929f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::clearFlags (unsigned flags)</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a6fb8cb185ccaff7f2b60160ad3717d8c">llvm::GenericMachineInstr::dropPoisonGeneratingFlags</a>.</p>

</div>
</div>

### clearKillInfo() {#ae26854c9925fc93880d644c0dcac8ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::clearKillInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clears kill flags on all operands.</p>


<p>clearKillInfo - Clears kill flags on all operands.</p>


<p>Declaration at line 1701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### clearRegisterDeads() {#ad4a32b52ea36d2c35a9860fe263d0574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::clearRegisterDeads (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear all dead flags on operands defining register <span class="doxyComputerOutput">Reg</span>.</p>

<p>Declaration at line 1728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ade4229c653b0cbcaca057e8af5002783">all_defs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>.</p>

</div>
</div>

### clearRegisterKills() {#ad61dd8c3be8a7f284aa7ac8f2c8bca5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::clearRegisterKills (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * RegInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear all kill flags affecting Reg.</p>


<p>If <a href="/web-llvm/docs/api/structs/reginfo">RegInfo</a> is provided, this includes all aliasing registers.</p>


<p>Declaration at line 1718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>.</p>

</div>
</div>

### cloneInstrSymbols() {#aa63ab5e3e1630ddb53a1a0def539a34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::cloneInstrSymbols (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone another <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s pre- and post- instruction symbols and replace ours with it.</p>

<p>Declaration at line 1964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>.</p>

</div>
</div>

### cloneMemRefs() {#a3a26f11d1735bf0f25261aefd2bee9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::cloneMemRefs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone another <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s memory reference descriptor list and replace ours with it.</p>


<p>Note that <span class="doxyComputerOutput">*this</span> may be the incoming MI!</p>


<p>Prefer this API whenever possible as it can avoid allocations in common cases.</p>


<p>Declaration at line 1936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad84ebe08bb098cd283e922fd186f77e9">llvm::MachineInstrBuilder::cloneMemRefs</a> and <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>.</p>

</div>
</div>

### cloneMergedMemRefs() {#a7a5607fcb0a195620036bb0f1217c8a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::cloneMergedMemRefs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; MIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the merge of multiple MachineInstrs' memory reference descriptors list and replace ours with it.</p>


<p>Note that <span class="doxyComputerOutput">*this</span> may be one of the incoming MIs!</p>


<p>Prefer this API whenever possible as it can avoid allocations in common cases.</p>


<p>Declaration at line 1945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#ae1749ab178302b86bb0cb8903cec1a9d">hasIdenticalMMOs</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a651dc9ad820d3c7cdd28f671e0d6d2e2">llvm::make_pointee_range</a>, <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>, <a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin</a>, <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>, <a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">memoperands_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a0a8d0cceecd0424aefb44ea46a27be4d">llvm::MachineInstrBuilder::cloneMergedMemRefs</a>.</p>

</div>
</div>

### collectDebugValues() {#a5105322139844c10dc05539f70ff3eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::collectDebugValues (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DbgValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan instructions immediately following MI and collect any matching DBG_VALUEs.</p>

<p>Declaration at line 2005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>.</p>

</div>
</div>

### copyImplicitOps() {#a67f26cdb79c726f4616b1cd7ae1996cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::copyImplicitOps (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy implicit register operands from specified instruction to this instruction.</p>


<p>copyImplicitOps - Copy implicit register operands from specified instruction to this instruction.</p>


<p>Declaration at line 1836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a55fdcb2a9df9a69067eed1bc17a0b927">llvm::MachineOperand::isRegMask</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ae4cfeb86ad3780d71eb022485e91d211">llvm::MachineInstrBuilder::copyImplicitOps</a>.</p>

</div>
</div>

### copyIRFlags() {#a49ac3225c216191d957cf56ad28f1c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::copyIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy all flags to MachineInst MIFlags.</p>

<p>Declaration at line 1989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a8fa9ad46c9ec8c4de6dca3245edeedfe">copyFlagsFromInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### debug\_operands() {#a1e2899f5dd649a9f82c32b99e5d77dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::debug_operands ()</td>
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

<p>Returns a range over all operands that are used to determine the variable location for this DBG_VALUE instruction.</p>

<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a>, <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="#ace50f23b8d1566bccb42a36100a9b818">getDebugOperand</a>, <a href="#adebad355655dfb512517e2f55bc98fb7">getDebugOperand</a>, <a href="#acd30a83560c3674627e36af9175e9e1f">getDebugOperandIndex</a>, <a href="#a4275c0f770726594387d7bfc85ea8d64">getNumDebugOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a>, <a href="#a067c1c89704407541cbed8d65ac8dd66">hasDebugOperandForReg</a>, <a href="#ad2a225209000f521430877a269f61083">isDebugOperand</a>, <a href="#adb7a3826a25ef43294d3434da71811e9">isUndefDebugValue</a> and <a href="#a0cf83915bd66f2a610c72f3d028f8704">setDebugValueUndef</a>.</p>

</div>
</div>

### debug\_operands() {#a7dc07273003a0c8e17c23f2d257ea6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::debug_operands ()</td>
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

<p>Returns a range over all operands that are used to determine the variable location for this DBG_VALUE instruction.</p>

<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a>, <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>

</div>
</div>

### definesRegister() {#a9024bfb74506b66f45d153234a802000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::definesRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> fully defines the specified register.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> is non-null, then it also checks if there is a def of a super-register. NOTE: It's ignoring subreg indices on virtual registers.</p>


<p>Definition at line 1533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#aed8bb289e710a4687f5dbdc1b0b35fd3">checkAndUpdateCCRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a551cf4f2a46a96b347d222acc8df059c">checkAndUpdateCPSRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ace4b26a3e7058a0e723088fdd9f95563">checkCCKill</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#aac55ba69021576846ac03b0050c022a7">isCCSelectPair</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpumacrofusion-cpp-/#af5da450a1411e5b2e09527cb36568ff1">anonymous{AMDGPUMacroFusion.cpp}::shouldScheduleAdjacent</a>.</p>

</div>
</div>

### defs() {#aa3b9fba7fd848bb37e43040b66f6c051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::defs ()</td>
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

<p>Returns a range over all explicit operands that are register definitions.</p>


<p>Implicit definition are not included!</p>


<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a1d85560fff9b526eda51892cd899e098">findSingleRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#a894fb383cc3e3a326646b5f3366881d2">getSalvageOpsForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a7685ee8f0cb0ee9e255a169a8765e54f">llvm::SPIRVGlobalRegistry::getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a506d59d745bce4ecf472b2a3580219bd">llvm::MipsInstrInfo::SafeInFPUDelaySlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a64bfddcfc4db367cec978a34653a69f3">llvm::MipsInstrInfo::SafeInLoadDelaySlot</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>.</p>

</div>
</div>

### defs() {#a52be2a25e3a107f532b38ce311b0717b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::defs ()</td>
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

<p>Returns a range over all explicit operands that are register definitions.</p>


<p>Implicit definition are not included!</p>


<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>

</div>
</div>

### dropDebugNumber() {#a209695ff10faf55ead93f3c26a61f642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::dropDebugNumber ()</td>
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

<p>Drop any variable location debugging information associated with this instruction.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> when an instruction is modified in such a way that it no longer defines the value it used to. Variable locations using that value will be dropped.</p>


<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### dropMemRefs() {#a6e05e3bfe64497149a8800b1830c4001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::dropMemRefs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s memory reference descriptor list.</p>


<p>This resets the memrefs to their most conservative state. This should be used only as a last resort since it greatly pessimizes our knowledge of the memory access performed by the instruction.</p>


<p>Declaration at line 1916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>.</p>


<p>Referenced by <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a> and <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>.</p>

</div>
</div>

### emitGenericError() {#aaee16070891b230788ad237d5ba6476d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::emitGenericError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">llvm::LLVMContext::diagnose</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="#abb10ef030fba4ea901518a0c8dbef3e2">getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>.</p>

</div>
</div>

### emitInlineAsmError() {#ad72245681f0ae02a2d4574d434bc813d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::emitInlineAsmError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an error referring to the source location of this instruction.</p>


<p>This should only be used for inline assembly that is somehow impossible to compile. Other errors should have been handled much earlier.</p>


<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">llvm::LLVMContext::diagnose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#aea65fa322ddcff0ca4cd6f83ccef77e0">getLocCookieMD</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>.</p>

</div>
</div>

### eraseFromBundle() {#a9891e442de101ced8a1533a71511dbed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::eraseFromBundle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink 'this' from its basic block and delete it.</p>


<p>If the instruction is part of a bundle, the other instructions in the bundle remain bundled.</p>


<p>Declaration at line 1336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3a892dcf265c384644ffac47d97b7e53">llvm::MachineBasicBlock::erase_instr</a> and <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>.</p>

</div>
</div>

### eraseFromParent() {#ac2421adbb9996e1b15f03a8abb6c70a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink 'this' from the containing basic block and delete it.</p>


<p>If this instruction is the header of a bundle, the whole bundle is erased. This function can not be used for instructions inside a bundle, use <a href="#a9891e442de101ced8a1533a71511dbed">eraseFromBundle()</a> to erase individual bundled instructions.</p>


<p>Declaration at line 1330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad26bff839257f220557ce812b2159c72">llvm::MachineBasicBlock::erase</a> and <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa61674464afddf4b2a24ab65f3833233">llvm::AArch64InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a5a2e063255e7f9ff6cbfab2dfcfeb5a1">llvm::ARCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a9c27deca75181d5b0986eb74bc38a1b1">llvm::ARMBaseInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#ab2592d528f736ade8f940d8b80c8d040">llvm::SparcInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ab536cb6776e394559d7109c0d6840c2e">llvm::VEInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2b46e1c0d91a5df6f3f45d573f833b1a">llvm::CombinerHelper::applyBuildFnMO</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac2377979438dcdab9e664ccd5f975dac">llvm::CombinerHelper::applyCombineDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a72848dca494afcf56b2bc2bea4322dc1">llvm::CombinerHelper::applyCombineIndexedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa09e8f13910a43ba1b8edc182c7a212c">llvm::CombinerHelper::applyExtendThroughPhis</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a75ae99f242b3954f52d12c85e53d5f41">llvm::CombinerHelper::applySextInRegOfLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad8a483afeb99148394d2586c5601e441">llvm::CombinerHelper::applyShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a67821f8310008d3e9ef7c911db364cc7">AMDGPURegBankLegalizeCombiner::cleanUpAfterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#ae86f2900b76b99dd19e12c819c5449cd">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64framelowering-cpp-/tagstoreedit/#ab4901e1671ebf2e213e931b5a44311db">anonymous{AArch64FrameLowering.cpp}::TagStoreEdit::emitCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9eb43774a0046a364f5c45f94576bc43">llvm::PPCInstrInfo::foldFrameOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a3a67d4b5306c3571138e241d77393283">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#abbab66c4fbf9fd6512efa4efae8f69ef">llvm::HexagonInstrInfo::genAllInsnTimingClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac1a085b3eb182136b9d98a7d6916421f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoopbreakBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afc26610b4c561e17a9ceb497233f34cc">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::modifyCmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a4fc59ce12e2dc07246561737f195c0c6">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::moveCopyInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-smepeepholeopt-cpp-/smepeepholeopt/#a5c603866e25916faea1af9c83ee89286">anonymous{SMEPeepholeOpt.cpp}::SMEPeepholeOpt::optimizeStartStopPairs</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a68cd342c50f56c8da7e9c41ce92d14b1">RemoveDeadAddBetweenLEAAndJT</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac9608ee656bad26eae3b7188510f43d1">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::removeRedundantConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a892f776a360693f609ef055a45a6f6a8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::removeUnconditionalBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a873bcbe8d28d96773cbdf2fd2c9ce07e">anonymous{PPCBranchSelector.cpp}::PPCBSel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoreframetoargsoffsetelim-cpp-/xcoreftaoelim/#a2ef5edc1bc3d0736ef24263d9e6b0d69">anonymous{XCoreFrameToArgsOffsetElim.cpp}::XCoreFTAOElim::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a92e31a04c0a1b5d17db90c99fa48f6aa">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::splitTwoPartImm</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a>.</p>

</div>
</div>

### explicit\_operands() {#a51f1fa9d5384d3b9c157a8216fef671d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::explicit_operands ()</td>
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



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>


<p>Referenced by <a href="#ad0666b4ee4d5d2ade97f5f1e63865bab">implicit_operands</a>, <a href="#ac14071becb4727630d1f983391fd718d">implicit_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>.</p>

</div>
</div>

### explicit\_operands() {#a471354c2bb81524bd5924f7290104f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::explicit_operands ()</td>
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



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>

</div>
</div>

### explicit\_uses() {#a0773fc3d8cd259c587ec29b5902de0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::explicit_uses ()</td>
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



<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>

</div>
</div>

### explicit\_uses() {#a3a3e7027c93fbf5f29af591087170f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::explicit_uses ()</td>
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



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>

</div>
</div>

### findFirstPredOperandIdx() {#a75925d9ebd5a8017581c9d07316be793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineInstr::findFirstPredOperandIdx ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the index of the first operand in the operand list that is used to represent the predicate.</p>


<p><a href="#a75925d9ebd5a8017581c9d07316be793">findFirstPredOperandIdx()</a> - Find the index of the first operand in the operand list that is used to represent the predicate.</p>


<p>It returns -1 if none is found.</p>


<p>Declaration at line 1608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">getDesc</a> and <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#af76e71e7ea189719baa6f8819724fac5">llvm::ARMBaseInstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### findInlineAsmFlagIdx() {#af3caca8b1c9e27890d57f5755dc142fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineInstr::findInlineAsmFlagIdx (unsigned OpIdx, unsigned * GroupNo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the index of the flag word operand that corresponds to operand OpIdx on an inline asm instruction.</p>


<p>Returns -1 if getOperand(OpIdx) does not belong to an inline asm operand group.</p>


<p>If GroupNo is not NULL, it will receive the number of the operand group containing OpIdx.</p>


<p>Declaration at line 1616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ad8e4e0d44daebe8c07cf5d6d60a4fc30">llvm::InlineAsm::MIOp_FirstOperand</a>.</p>


<p>Referenced by <a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a>, <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a> and <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>.</p>

</div>
</div>

### findRegisterDefOperand() {#afc1df0cb1a8c3103a4266def94c3a670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * llvm::MachineInstr::findRegisterDefOperand (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool isDead=false, bool Overlap=false)</td>
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

<p>Wrapper for findRegisterDefOperandIdx, it returns a pointer to the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> rather than an index.</p>

<p>Definition at line 1589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#abb834744243c11cb677261382ac15bea">isDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ad0a79b68db2b8f84f92b1ee24352b3ce">addRegisterDefined</a>, <a href="#aedaafad0e3bea3243199613910e2a7ce">findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf735f22db2a6cb417e73392e0934bb1">llvm::X86InstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ac671c3b34aac49144d2688fd6ed160bc">llvm::X86InstrInfo::setSpecialOperandAttr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp/#a24181d1b7cdfbb8fd9710139d861ca6c">transferDeadCC</a>.</p>

</div>
</div>

### findRegisterDefOperand() {#aedaafad0e3bea3243199613910e2a7ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand * llvm::MachineInstr::findRegisterDefOperand (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool isDead=false, bool Overlap=false)</td>
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



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#afc1df0cb1a8c3103a4266def94c3a670">findRegisterDefOperand</a>, <a href="#abb834744243c11cb677261382ac15bea">isDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### findRegisterDefOperandIdx() {#aeeed341d0f3c7220d070d766e3a0f584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineInstr::findRegisterDefOperandIdx (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool isDead=false, bool Overlap=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the operand index that is a def of the specified register or -1 if it is not found.</p>


<p><a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx()</a> - Returns the operand index that is a def of the specified register or -1 if it is not found.</p>


<p>If isDead is true, defs that are not dead are skipped. If Overlap is true, then it also looks for defs that merely overlap the specified register. If <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> is non-null, then it also checks if there is a def of a super-register. This may also return a register mask operand when Overlap is true.</p>


<p>If isDead is true, defs that are not dead are skipped. If <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> is non-null, then it also checks if there is a def of a super-register.</p>


<p>Declaration at line 1583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#abb834744243c11cb677261382ac15bea">isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a55fdcb2a9df9a69067eed1bc17a0b927">llvm::MachineOperand::isRegMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a9024bfb74506b66f45d153234a802000">definesRegister</a>, <a href="#afc1df0cb1a8c3103a4266def94c3a670">findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a054d573171c2fcf38b33a60e412dba7b">getMaddPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab6a37e8549580d302c7c98852a4ddc11">getMiscPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a9de31756d24ba6d5dbe75c2d425720d4">hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0f3bc0c5478dd84e0831b5d78a274b47">llvm::CombinerHelper::matchEqualDefs</a>, <a href="#a66e91c5407ade0326e5dbd87e986e648">modifiesRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a> and <a href="#a8e705934ca4178520c75d7ed1218cfc5">registerDefIsDead</a>.</p>

</div>
</div>

### findRegisterUseOperand() {#ab692b90c6e0e9b450f407896cbbe4b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * llvm::MachineInstr::findRegisterUseOperand (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool isKill=false)</td>
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

<p>Wrapper for findRegisterUseOperandIdx, it returns a pointer to the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> rather than an index.</p>

<p>Definition at line 1563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#ae9723ca940711fa1a09c0d53efeef5fe">isKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a934c36cbb52619d7d75dfc0766e2b946">findRegisterUseOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae2bd5329e5726d560529de68df90503c">llvm::CombinerHelper::matchFreezeOfSingleMaybePoisonOperand</a>.</p>

</div>
</div>

### findRegisterUseOperand() {#a934c36cbb52619d7d75dfc0766e2b946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand * llvm::MachineInstr::findRegisterUseOperand (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool isKill=false)</td>
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



<p>Definition at line 1570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ab692b90c6e0e9b450f407896cbbe4b02">findRegisterUseOperand</a>, <a href="#ae9723ca940711fa1a09c0d53efeef5fe">isKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### findRegisterUseOperandIdx() {#a6f42d93281a5cbf5360f836c09166c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachineInstr::findRegisterUseOperandIdx (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool isKill=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the operand index that is a use of the specific register or -1 if it is not found.</p>


<p><a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx()</a> - Returns the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> that is a use of the specific register or -1 if it is not found.</p>


<p>It further tightens the search criteria to a use that kills the register if isKill is true.</p>


<p>Declaration at line 1558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ae9723ca940711fa1a09c0d53efeef5fe">isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ab692b90c6e0e9b450f407896cbbe4b02">findRegisterUseOperand</a>, <a href="#a81547ddac1cc7ddad9428925e49ab42b">killsRegister</a>, <a href="#a2380c209ae5339835b5e6ea6d5c197ad">readsRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#a7e75a4f6568424bf0940a7c509a6d18c">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>.</p>

</div>
</div>

### findTiedOperandIdx() {#aa2dfd6ae7ded046f5e5e03e0f745d5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineInstr::findTiedOperandIdx (unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given the index of a tied register operand, find the operand it is tied to.</p>


<p>Defs are tied to uses and vice versa. Returns the index of the tied operand which must exist.</p>


<p>Declaration at line 1671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a85ea607a43ea9b3eb84ed72058693d4a">llvm::StatepointOpers::getFirstGCPtrIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a0678a1f52ff04158310e4157e81282f6">llvm::StackMaps::getNextMetaArgIdx</a>, <a href="#ae5036d7a6318520089e8c654b95e76c1">getNumDefs</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ad8e4e0d44daebe8c07cf5d6d60a4fc30">llvm::InlineAsm::MIOp_FirstOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a058531ea6c1669bc3fb3b598d25da429">TiedMax</a>.</p>


<p>Referenced by <a href="#a9d2b6142e2253bdad20b1f980f53f216">hasComplexRegisterTies</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="#a391694f8040173dc0670bd273b170502">isRegTiedToDefOperand</a>, <a href="#a6df9a6b70a33aee123056cec0ed052c4">isRegTiedToUseOperand</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a> and <a href="#a8e66e9ca7739874b25b9337940c26a0a">untieRegOperand</a>.</p>

</div>
</div>

### getAsmPrinterFlag() {#a4866593b666b1cbcb3c95802c12bcfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::getAsmPrinterFlag (<a href="#a0ac990e2b3f7973d16c33555e9adf9ae">CommentFlag</a> Flag)</td>
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

<p>Return whether an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> flag is set.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### getAsmPrinterFlags() {#a88cbe06065807dd01b0785c3f47490c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachineInstr::getAsmPrinterFlags ()</td>
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

<p>Return the asm printer flags bitvector.</p>

<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### getBundleSize() {#a76b0b34adc3bc0648be36c663c0e046b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineInstr::getBundleSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of instructions inside the MI bundle, excluding the bundle header.</p>


<p>Return the number of instructions inside the MI bundle, not counting the header instruction.</p>


<p>This is the number of instructions that <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> skips, 0 for unbundled instructions.</p>


<p>Declaration at line 1498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getCFIType() {#a22b83742938bc0b4477b0f19d563ebfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachineInstr::getCFIType ()</td>
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

<p>Helper to extract a CFI type hash if one has been added.</p>

<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

### getDebugExpression() {#ab367ba2f45afaba6e941bd54c9c95a9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression * MachineInstr::getDebugExpression ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the complex address expression referenced by this DBG_VALUE instruction.</p>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a3736f5c23004fc6d6b0d0dc773efe7e2">getDebugExpressionOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a>, <a href="#ae45a9559b6fd1578fb4d12f341cbed57">isDebugEntryValue</a>, <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>.</p>

</div>
</div>

### getDebugExpressionOp() {#a3736f5c23004fc6d6b0d0dc773efe7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; MachineInstr::getDebugExpressionOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the operand for the complex address expression referenced by this DBG_VALUE instruction.</p>

<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>


<p>Referenced by <a href="#ab367ba2f45afaba6e941bd54c9c95a9f">getDebugExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1f42f634cff46c0380f80cc600c19f3b">llvm::updateDbgValueForSpill</a>.</p>

</div>
</div>

### getDebugExpressionOp() {#a539133bbbe620ce232f698234544b990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; MachineInstr::getDebugExpressionOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>

</div>
</div>

### getDebugInstrNum() {#ad26a74fb0ad868f0867cce317269d721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineInstr::getDebugInstrNum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fetch the instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>If it does not have one already, a new and unique number will be assigned.</p>


<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d18a270ea6efcfc902cf506a5cc5ecc">llvm::MachineFunction::getNewDebugInstrNum</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a> and <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>.</p>

</div>
</div>

### getDebugInstrNum() {#a1e8cfd2dc5bfc62862b1c75c20a1ee66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineInstr::getDebugInstrNum (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fetch instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> – but before it's inserted into <span class="doxyComputerOutput">MF</span>.</p>


<p>Needed for transformations that create an instruction but don't immediately insert them.</p>


<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d18a270ea6efcfc902cf506a5cc5ecc">llvm::MachineFunction::getNewDebugInstrNum</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>

</div>
</div>

### getDebugLabel() {#a8de5351053b099124a2e2ea477ed54c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILabel * MachineInstr::getDebugLabel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the debug label referenced by this DBG_LABEL instruction.</p>

<p>Declaration at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="#a2502a65c42b09e02d163611edb263c84">isDebugLabel</a>.</p>

</div>
</div>

### getDebugLoc() {#abb10ef030fba4ea901518a0c8dbef3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::MachineInstr::getDebugLoc ()</td>
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

<p>Returns the debug location id of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a19dd673b5e34f3c83c6c17f780836bc7">addUnreachableAfterTryTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a4689c1a05c58cd8e0dbb57bc84fdc8cf">llvm::ARCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ab30ade3265bd079731057aafc0ff6e9f">llvm::MSP430FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a03870219d36d778b50b9d2b1a5f775c7">llvm::Thumb1FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a0ab2cc201e1521acab599966d10b815d">llvm::XCoreFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="#aaee16070891b230788ad237d5ba6476d">emitGenericError</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac1a085b3eb182136b9d98a7d6916421f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoopbreakBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afc26610b4c561e17a9ceb497233f34cc">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::modifyCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a873bcbe8d28d96773cbdf2fd2c9ce07e">anonymous{PPCBranchSelector.cpp}::PPCBSel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a>.</p>

</div>
</div>

### getDebugOffset() {#acdbcc97c288440883cc78c74fed7066e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::MachineInstr::getDebugOffset ()</td>
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

<p>Return the operand containing the offset to be used if this DBG_VALUE instruction is indirect; will be an invalid register if this value is not indirect, and an immediate with value 0 otherwise.</p>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>


<p>Referenced by <a href="#a252a85dbac85d89e26fae5f8e3b87eff">isDebugOffsetImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1f42f634cff46c0380f80cc600c19f3b">llvm::updateDbgValueForSpill</a>.</p>

</div>
</div>

### getDebugOffset() {#a51da1bfa6bdaa6cd06be2a3b92ccae1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; llvm::MachineInstr::getDebugOffset ()</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>

</div>
</div>

### getDebugOperand() {#ace50f23b8d1566bccb42a36100a9b818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; llvm::MachineInstr::getDebugOperand (unsigned Index)</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> and <a href="#a4275c0f770726594387d7bfc85ea8d64">getNumDebugOperands</a>.</p>


<p>Referenced by <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a> and <a href="#ae4c4f9c9cf73f1c869a1c0eae73c150f">isIndirectDebugValue</a>.</p>

</div>
</div>

### getDebugOperand() {#adebad355655dfb512517e2f55bc98fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::MachineInstr::getDebugOperand (unsigned Index)</td>
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



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> and <a href="#a4275c0f770726594387d7bfc85ea8d64">getNumDebugOperands</a>.</p>

</div>
</div>

### getDebugOperandIndex() {#acd30a83560c3674627e36af9175e9e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getDebugOperandIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Op)</td>
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



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1d927e3bff8edf86442c52cc36a35cc8">llvm::adl_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> and <a href="#ad2a225209000f521430877a269f61083">isDebugOperand</a>.</p>

</div>
</div>

### getDebugOperandsForReg() {#af06fa0062be2cb3feb58ad49814b9b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filter_iterator&lt; const MachineOperand *, std::function&lt; bool(const MachineOperand &amp;Op)&gt; &gt; &gt; llvm::MachineInstr::getDebugOperandsForReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a05c54bfb75dbb555ab457e768bbcfe73">getDebugOperandsForReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getDebugOperandsForReg() {#aa0e69cc2fdf3daec4ae61c572d71bf43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filter_iterator&lt; MachineOperand *, std::function&lt; bool(MachineOperand &amp;Op)&gt; &gt; &gt; llvm::MachineInstr::getDebugOperandsForReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a05c54bfb75dbb555ab457e768bbcfe73">getDebugOperandsForReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getDebugVariable() {#a9ce3843932b6ae1c23228017f11eef25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocalVariable * MachineInstr::getDebugVariable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the debug variable referenced by this DBG_VALUE instruction.</p>

<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#abfcdb704dc6511a2c0b93fe4e5987182">getDebugVariableOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### getDebugVariableOp() {#abfcdb704dc6511a2c0b93fe4e5987182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; MachineInstr::getDebugVariableOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the operand for the debug variable referenced by this DBG_VALUE instruction.</p>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>


<p>Referenced by <a href="#a9ce3843932b6ae1c23228017f11eef25">getDebugVariable</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### getDebugVariableOp() {#ac916b8cc2bbad1b2fad0d16486ee7593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; MachineInstr::getDebugVariableOp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>

</div>
</div>

### getDesc() {#a75a5f7e3b3d4ec79610b4e556d2f35ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc &amp; llvm::MachineInstr::getDesc ()</td>
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

<p>Returns the target instruction descriptor of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a87edaaaaa788f8bc30dfad90aecdb343">llvm::HexagonPacketizerList::canPromoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#adfd05fb40b63f3fde78a81e119ed89e3">llvm::ResourceManager::canReserveResources</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="#a75925d9ebd5a8017581c9d07316be793">findFirstPredOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#abbab66c4fbf9fd6512efa4efae8f69ef">llvm::HexagonInstrInfo::genAllInsnTimingClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a100d476a583a34879b296908da01fdac">llvm::ScheduleDAG::getInstrDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#aaec6e6ec16a011ef89299012d0dbe146">getTargetMBB</a>, <a href="#a9dbc9a748353035febcc488160ba9956">getTypeToPrint</a>, <a href="#a9d2b6142e2253bdad20b1f980f53f216">hasComplexRegisterTies</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac485643e66f0cec45d40f99288d3e25c">llvm::HexagonInstrInfo::isDependent</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinepipeliner-cpp-/funcunitsorter/#a64d0e66977892f563370dbbcde3b8fc1">anonymous{MachinePipeliner.cpp}::FuncUnitSorter::minFuncUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a66b0369aaa8c87a6969ec5b56700d0d8">llvm::ResourceManager::reserveResources</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>.</p>

</div>
</div>

### getFirst2LLTs() {#a620b1d8de0e32491f106ddc997914153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; LLT, LLT &gt; MachineInstr::getFirst2LLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2572 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst2RegLLTs() {#a817d92911624542113807dc07a46bfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, LLT, Register, LLT &gt; MachineInstr::getFirst2RegLLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst2Regs() {#afeb98e93a7bcdce78a80a51a00610c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, Register &gt; llvm::MachineInstr::getFirst2Regs ()</td>
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



<p>Definition at line 2023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>.</p>

</div>
</div>

### getFirst3LLTs() {#abeb0ed106bd6d33c0cf49a89083a74ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; LLT, LLT, LLT &gt; MachineInstr::getFirst3LLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2577 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst3RegLLTs() {#a31012ec441c425a3eeb652d31ab0a8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, LLT, Register, LLT, Register, LLT &gt; MachineInstr::getFirst3RegLLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2607 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst3Regs() {#a98055346309284ec85c366c2802bd265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, Register, Register &gt; llvm::MachineInstr::getFirst3Regs ()</td>
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



<p>Definition at line 2027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>.</p>

</div>
</div>

### getFirst4LLTs() {#ad2b80d7b9f05e663c35bd72cece6ebd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; LLT, LLT, LLT, LLT &gt; MachineInstr::getFirst4LLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2583 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst4RegLLTs() {#a80edb692b5f12ebc13ea0c6558e2cc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, LLT, Register, LLT, Register, LLT, Register, LLT &gt; MachineInstr::getFirst4RegLLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2617 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst4Regs() {#a11b18514df4193347c1d9ff3773ca850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, Register, Register, Register &gt; llvm::MachineInstr::getFirst4Regs ()</td>
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



<p>Definition at line 2032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>.</p>

</div>
</div>

### getFirst5LLTs() {#a2e82295f594d02e8290f214b5a4c3551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; LLT, LLT, LLT, LLT, LLT &gt; MachineInstr::getFirst5LLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2047 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2590 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst5RegLLTs() {#a1345402d2906eacc2db93c4bb59cf861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, LLT, Register, LLT, Register, LLT, Register, LLT, Register, LLT &gt; MachineInstr::getFirst5RegLLTs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2629 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>.</p>

</div>
</div>

### getFirst5Regs() {#a01c0bab24b110610c39c166eb5db9ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Register, Register, Register, Register, Register &gt; llvm::MachineInstr::getFirst5Regs ()</td>
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



<p>Definition at line 2038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>.</p>

</div>
</div>

### getFlag() {#a33365204be9cb132de322e3713253b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::getFlag (<a href="#aafacf84de1cb994a92dc045f4aa1d518">MIFlag</a> Flag)</td>
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

<p>Return whether an MI flag is set.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a337903856769965870a905f37f63790d">getFNEGPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab3d65d6e0daa1da2c564a3803f207b2">llvm::AArch64InstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8d93b0ff1b64f553c4e86fdebacff56">llvm::PPCInstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ade726ab992f758b88dcc4d6691efd90d">llvm::RISCVInstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a5183ec05f7f9d8e1211aa1fd88200fd9">llvm::SystemZInstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a6809308720683fc5bf1cb8ac00529ecb">llvm::X86InstrInfo::isAssociativeAndCommutative</a>, <a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">isBundledWithPred</a>, <a href="#ad07416ea31edd139a4ebe5b42a6f80b0">isBundledWithSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a89fae3db628b477b713990d7a58732ea">isCombineInstrCandidateFP</a>, <a href="#aaf9df5fbb2543faa0659f9b31f907df9">isConvergent</a>, <a href="#aa97496994b12c49c3141d8f15bc871eb">isInsideBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a0f95f5fe4853d046274eb0edfb483d70">isNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab46d848f3726829246738eb9d78aebf9">llvm::CombinerHelper::matchAddOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a7b617a5a6a2773b70ea354e1dffceff7">llvm::CombinerHelper::matchExtOfExt</a>, <a href="#a00966a294fe7a54bf2f6a296e82fc8e1">mayRaiseFPException</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af198192a5c89e8186de61e89112a1765">propagateFrameFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp/#a28b825c91d72def7c69724ef60ec4142">transferMIFlag</a>.</p>

</div>
</div>

### getFlags() {#ad73e18478cd951f76d35a88c4d43ef5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachineInstr::getFlags ()</td>
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

<p>Return the MI flags bitvector.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64framelowering-cpp-/tagstoreedit/#ab4901e1671ebf2e213e931b5a44311db">anonymous{AArch64FrameLowering.cpp}::TagStoreEdit::emitCode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a6db801cf083221e113de833e7564f906">llvm::GenericMachineInstr::hasPoisonGeneratingFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac88c813e35b6d1a4966b0ee24a5c8b9a">llvm::CombinerHelper::matchSubOfVScale</a>, <a href="#a36538e83424d5c406c294a6c365f9fe9">mergeFlagsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>.</p>

</div>
</div>

### getFoldedRestoreSize() {#a87d05d77b880d0d3e4a480affaf85f5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocationSize &gt; MachineInstr::getFoldedRestoreSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a valid size if the instruction is a folded restore instruction.</p>

<p>Declaration at line 1832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2553 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a213eed2958a020a3cb8a92627acd4577">getSpillSlotSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getFoldedSpillSize() {#a64aa9b0d6022db9f727893972c0bd9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocationSize &gt; MachineInstr::getFoldedSpillSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a valid size if the instruction is a folded spill instruction.</p>

<p>Declaration at line 1825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a213eed2958a020a3cb8a92627acd4577">getSpillSlotSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getHeapAllocMarker() {#ad17b8014d3272aa5121425e2bcef34db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MachineInstr::getHeapAllocMarker ()</td>
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

<p>Helper to extract a heap alloc marker if one has been added.</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

### getInlineAsmDialect() {#a8b94b1143638cb1b18d976bba0b0ec3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAsm::AsmDialect MachineInstr::getInlineAsmDialect ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370abff974c258dde829c1c6b6f32667be3a">llvm::InlineAsm::Extra_AsmDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a>.</p>


<p>Referenced by <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>.</p>

</div>
</div>

### getLocCookieMD() {#aea65fa322ddcff0ca4cd6f83ccef77e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDNode * MachineInstr::getLocCookieMD ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For inline asm, get the !srcloc metadata node if we have it, and decode the loc cookie from it.</p>

<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a7f12b8ac7462ea82d735ac7d56f6260b">llvm::mdconst::hasa</a>.</p>


<p>Referenced by <a href="#ad72245681f0ae02a2d4574d434bc813d">emitInlineAsmError</a>.</p>

</div>
</div>

### getMF() {#ab05719438bdf4b46871e5ecd9730caeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction * MachineInstr::getMF ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the function that contains the basic block that this instruction belongs to.</p>


<p>Note: this is undefined behaviour if the instruction does not have a parent.</p>


<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="#aaee16070891b230788ad237d5ba6476d">emitGenericError</a>, <a href="#ad72245681f0ae02a2d4574d434bc813d">emitInlineAsmError</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa8aa7be4bd12d2e18b08a87805017131">llvm::RISCVInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a4ffd0a0399bead8c2759b5487ea997c6">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnBackward</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4862e12e65a868264ab84a2252104dda">llvm::RISCVInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6875e5a149ffdf299b10e8f969d379d4">llvm::TargetInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="#a87d05d77b880d0d3e4a480affaf85f5d">getFoldedRestoreSize</a>, <a href="#a64aa9b0d6022db9f727893972c0bd9f0">getFoldedSpillSize</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="#a54d1bd4ee7e40a15f8d22acca228dbc3">getRestoreSize</a>, <a href="#acf7a2f3baa7050ba9f95be0c1b71339f">getSpillSize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2f1cfe9c040112cbf97a025655d3595e">llvm::RISCVInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="#a9117508fb00fda14207e7f968389544c">setDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a48560701bbaa0465f8ef8d92874caaf0">llvm::SIInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>.</p>

</div>
</div>

### getMF() {#a269e83f53595da3ec459010b8f945afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * llvm::MachineInstr::getMF ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>

</div>
</div>

### getMMRAMetadata() {#a20c1f72cf20853c89c6e92a21c5f49ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MachineInstr::getMMRAMetadata ()</td>
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

<p>Helper to extract mmra.op metadata.</p>

<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

### getNumDebugOperands() {#a4275c0f770726594387d7bfc85ea8d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getNumDebugOperands ()</td>
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

<p>Returns the total number of operands which are debug locations.</p>

<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a>.</p>


<p>Referenced by <a href="#ace50f23b8d1566bccb42a36100a9b818">getDebugOperand</a>, <a href="#adebad355655dfb512517e2f55bc98fb7">getDebugOperand</a> and <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a>.</p>

</div>
</div>

### getNumDefs() {#ae5036d7a6318520089e8c654b95e76c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getNumDefs ()</td>
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

<p>Returns the total number of definitions.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>.</p>


<p>Referenced by <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf735f22db2a6cb417e73392e0934bb1">llvm::X86InstrInfo::hasReassociableOperands</a> and <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryopc-match/#a7a3bed68c87689c4510c602f959f32f0">llvm::MIPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable &gt;::match</a>.</p>

</div>
</div>

### getNumExplicitDefs() {#a9839b7e1d8811ea9d41f901ab6a0f23b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineInstr::getNumExplicitDefs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of non-implicit definitions.</p>

<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="#aa3b9fba7fd848bb37e43040b66f6c051">defs</a>, <a href="#a52be2a25e3a107f532b38ce311b0717b">defs</a>, <a href="#a0773fc3d8cd259c587ec29b5902de0f4">explicit_uses</a>, <a href="#a3a3e7027c93fbf5f29af591087170f41">explicit_uses</a>, <a href="/web-llvm/docs/api/classes/llvm/gintrinsic/#a5fa14f1396039c08f7b64717bdc2b830">llvm::GIntrinsic::getIntrinsicID</a>, <a href="#ae5036d7a6318520089e8c654b95e76c1">getNumDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf735f22db2a6cb417e73392e0934bb1">llvm::X86InstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#aa737e66804d935143b89db74d5646610">isConstReg</a>, <a href="#a3949f157e1034f6cb5d16ad708059aa3">uses</a> and <a href="#a15bc8fb07e719b5a47a7c9070c5e26af">uses</a>.</p>

</div>
</div>

### getNumExplicitOperands() {#a56b7fed94faeb5bc67ee2b71608d2665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineInstr::getNumExplicitOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of non-implicit operands.</p>

<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="#a51f1fa9d5384d3b9c157a8216fef671d">explicit_operands</a>, <a href="#a471354c2bb81524bd5924f7290104f55">explicit_operands</a>, <a href="#a0773fc3d8cd259c587ec29b5902de0f4">explicit_uses</a>, <a href="#a3a3e7027c93fbf5f29af591087170f41">explicit_uses</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9f95e557fb675ab6ef80f2fc4b8b3e01">llvm::AArch64InstrInfo::getMemOpBaseRegImmOfsOffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="#a04430301e461dbb2e962ae7d711cbbc6">getNumImplicitOperands</a>, <a href="#a9dbc9a748353035febcc488160ba9956">getTypeToPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf735f22db2a6cb417e73392e0934bb1">llvm::X86InstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>.</p>

</div>
</div>

### getNumImplicitOperands() {#a04430301e461dbb2e962ae7d711cbbc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getNumImplicitOperands ()</td>
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

<p>Returns the implicit operands number.</p>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a> and <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>.</p>

</div>
</div>

### getNumMemOperands() {#a820e6d6b9b0a0cacce473925803ba569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getNumMemOperands ()</td>
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

<p>Return the number of memory operands.</p>

<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a> and <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>.</p>

</div>
</div>

### getNumOperands() {#a432824f0975bb863478bf4ef3a5df258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getNumOperands ()</td>
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

<p>Retuns the total number of operands.</p>

<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a>, <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a126f327d0727647f3daa7cf0da944f9e">allPhiOperandsUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad304b10479d6791deee8ad1b157fb37f">llvm::X86InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4ab4c0bfcb70883e983a325153b5a44e">llvm::HexagonInstrInfo::canExecuteInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8853b2033702691c17576d5acc430460">anonymous{PPCMIPeephole.cpp}::collectUnprimedAccPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="#a75925d9ebd5a8017581c9d07316be793">findFirstPredOperandIdx</a>, <a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a977522c71b9c7099aa74222cc12bbf17">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4aadfbe4795304e72a1a7be77ac88be7">findLoopComponents</a>, <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>, <a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a>, <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="#aea65fa322ddcff0ca4cd6f83ccef77e0">getLocCookieMD</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a934f16bd434319b64e63ae8f622991ce">llvm::LanaiInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/gunmerge/#a2016607245da986216c5fa788412efbe">llvm::GUnmerge::getNumDefs</a>, <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="#a04430301e461dbb2e962ae7d711cbbc6">getNumImplicitOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/gphi/#af92785377a0e54a02528fd873d9b69ff">llvm::GPhi::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/gmergelikeinstr/#a90d314382626dec7379b4d2ec02b7a4b">llvm::GMergeLikeInstr::getNumSources</a>, <a href="#a6197870d7271620c9bad9f4a649fc26a">getOperand</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#af30efc6374f891c0dd222ed8610919fd">llvm::PeelingModuloScheduleExpander::getPhiCanonicalReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="#a9d2b6142e2253bdad20b1f980f53f216">hasComplexRegisterTies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a>, <a href="#a37fa340555fb189bce42efadf42c5253">isConstantValuePHI</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aeb5e4e41c7dda3b942168ed881fa1d13">llvm::SPIRV::make_descr_sampled_image</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryop-match/#aa22431f74a092ef2095e5e7fdfa9e9c9">llvm::MIPatternMatch::BinaryOp_match&lt; LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryopc-match/#a7a3bed68c87689c4510c602f959f32f0">llvm::MIPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/ternaryop-match/#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/unaryop-match/#a03468639caa1fb6be4bb742a181faf81">llvm::MIPatternMatch::UnaryOp_match&lt; SrcTy, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="#a374fc9d9064a93ef8a408f269d02389d">readsWritesVirtualRegister</a>, <a href="#ac3b161ec90385105cb46a08b52139e60">removeOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a5536577e4a955f5327410bda9cf3e7ed">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::reuseDUP</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30233b5b4decf678ec7ed144ac1f729b">llvm::MachineFunction::substituteDebugValuesForInst</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#aaaa5a895e6a8003daae912a9bf636040">llvm::LegalizationArtifactCombiner::tryCombineExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>.</p>

</div>
</div>

### getOpcode() {#a0363204b5fbab08a46f5a7cd7f376f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getOpcode ()</td>
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

<p>Returns the opcode of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#ae5ced970396c0f7c3cb7644340597544">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::adjustCmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#adcb6972d31690d306b5843c060e1aa9a">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::adjustTo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa61674464afddf4b2a24ab65f3833233">llvm::AArch64InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a9c27deca75181d5b0986eb74bc38a1b1">llvm::ARMBaseInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#ac741087fd882a50ae09491bdaebcaad9">llvm::NVPTXInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedb2f85719d229f0c9bc62ab1d17e918">llvm::PPCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#ab2592d528f736ade8f940d8b80c8d040">llvm::SparcInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ab536cb6776e394559d7109c0d6840c2e">llvm::VEInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a092553d9bd8edd039d855fb411c6d887">llvm::XCoreInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a51f54f2b0fd916f4c01b600905180782">llvm::AArch64InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad304b10479d6791deee8ad1b157fb37f">llvm::X86InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab359f8ff91954b23a1e8366666e59cbb">llvm::AArch64InstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a637fe9208c860066ecf02233cd258f9b">llvm::ARMBaseInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac91aca84eade26acea192464a9cfcde8">llvm::CombinerHelper::applyCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afe9d6cb97689cb5efb1a5b8f9dc68ea0">llvm::CombinerHelper::applyCombineUnmergeZExtToZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa09e8f13910a43ba1b8edc182c7a212c">llvm::CombinerHelper::applyExtendThroughPhis</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad8a483afeb99148394d2586c5601e441">llvm::CombinerHelper::applyShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a30157a5020934199c281913d8d077f55">areCandidatesToMergeOrPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#aa67934d23b1e9ff1901ec570930128e4">areCombinableOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a69f0bf266f1e42f9d65ec549a6481ba6">bbIsJumpedOver</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a13a8c4d3fbc72e8e2f7080411e2ea9cf">llvm::ResourceManager::calculateResMII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a7dc60439888b36449abcb98f47d23ec6">canCmpInstrBeRemoved</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a364fb004e57163fc1a3e2adc754af9b1">canCompareBeNewValueJump</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a2a5ba8caf566b63bea759399eb58927f">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#acc9e7924e2ef2b569d74df940b3dc0fb">canEmitConjunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a80ba8826b4f8e7008ae9453968ed35fa">canInstrSubstituteCmpInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#af2048f0f8425833d77baeb4baeadc779">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::checkMovImmInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a148883092b4d2dfdc994bc095ec153d7">anonymous{PPCMacroFusion.cpp}::checkOpConstraints</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a46b2b58b4eaac69bb5cf98a05b2ab1be">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a413489f8f91ace88c20648ec2aa8b776">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a31acc131777ac8a1074a5d1985ef1285">llvm::HexagonInstrInfo::doesNotReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcncreatevopd-cpp-/gcncreatevopd/#afc677780cbd237adfee6dd02bf20541f">anonymous{GCNCreateVOPD.cpp}::GCNCreateVOPD::doReplace</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer/#a8a2ae56dfdc087ade919e8712369134a">llvm::SystemZHazardRecognizer::dumpSU</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8be157bc7b2bed40b10198e8b6a2bfcf">anonymous{PPCMIPeephole.cpp}::eligibleForCompareElimination</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a4689c1a05c58cd8e0dbb57bc84fdc8cf">llvm::ARCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ab30ade3265bd079731057aafc0ff6e9f">llvm::MSP430FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a03870219d36d778b50b9d2b1a5f775c7">llvm::Thumb1FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a0ab2cc201e1521acab599966d10b815d">llvm::XCoreFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a851a237b27ce366221fcb1daf2f0d119">llvm::HexagonFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#a561e8197481b2a01d7f75fd567c7801e">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a6e8a4f85c8a56769ce682ff88d5b60f1">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acd9a409ba62041c36090fe42bfdf16d7">llvm::M68kInstrInfo::ExpandCCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ab69e2cd15cb4ac3f0262a15fdd65befa">expandXorFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a1511e75a5fe8384a21552151b86eac3b">llvm::AArch64GISelUtils::extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa8aa7be4bd12d2e18b08a87805017131">llvm::RISCVInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4aadfbe4795304e72a1a7be77ac88be7">findLoopComponents</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#afa5ee2f4a09f62ebe217673407877974">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnForward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#ac962fea3028517b39dcd1f4cff0c0112">foldImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a5278ce924df77790e6a938f5065ba5a0">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a3a67d4b5306c3571138e241d77393283">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a52300ffc2cad932b8451cdd3ae41a470">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#abbab66c4fbf9fd6512efa4efae8f69ef">llvm::HexagonInstrInfo::genAllInsnTimingClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515c6055dea0a74d18c4549511921e8c">llvm::generateDotOrFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#aa598b3407f82a894e4f5a82676e5bc43">llvm::ARMAsmPrinter::getCodeViewJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af668609d5285820d674d655ab3990c91">llvm::HexagonInstrInfo::getCompoundOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c64e87ab3dd6ef5ea0c229712f1fd63">llvm::X86InstrInfo::getConstValDefinedInReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a7b4dfdd596d675a34ee339b581424255">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a5077615197d034930b58d221032e96f0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc8c7c7ca66d38ff9fd8c34f64a0fd4e">llvm::getDefInstrMaybeConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a1f24abade2ffdb0e55559d552552692c">getFMAPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a337903856769965870a905f37f63790d">getFNEGPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a0efa4ac98b741f2ab0520ab1d2f8a115">llvm::X86InstrInfo::getMachineCombinerPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a054d573171c2fcf38b33a60e412dba7b">getMaddPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ad7b408f8f589425b7ba7eb3e3be6e818">llvm::LanaiInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa04c64c287d0b42c8a1714011a943e3d">llvm::RISCVInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a934f16bd434319b64e63ae8f622991ce">llvm::LanaiInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab6a37e8549580d302c7c98852a4ddc11">getMiscPatterns</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47bf073dca31bf981a1a425cf537454f">llvm::getNumSizeComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6d986da977a884fc79751da79c4e6f84">llvm::SPIRVGlobalRegistry::getPointeeType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8c80c43434acec4d262a13013d993dd3">llvm::SPIRVGlobalRegistry::getPointeeTypeOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6c14f246ebdc035b01f2c56df0b7ce89">llvm::RISCVInstrInfo::getReassociateOperandIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a903e4ccbdb00b36a08f5e84a8010c3cd">llvm::TargetInstrInfo::getReassociationOpcodes</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ab6e454de3dfa112cc7e30219ac7298cd">llvm::SPIRVGlobalRegistry::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#a894fb383cc3e3a326646b5f3366881d2">getSalvageOpsForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/gvecreduce/#a7248cdbc5ca8ce9465bcc2372a4dc90f">llvm::GVecReduce::getScalarOpcForReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a625767127423cea458550a1505f80d39">llvm::SPIRVGlobalRegistry::getScalarOrVectorComponentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a7685ee8f0cb0ee9e255a169a8765e54f">llvm::SPIRVGlobalRegistry::getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#aff059e4f5e8216de3172acd39a6e0ff8">anonymous{PPCMIPeephole.cpp}::getSrcVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad64a5996fef41f1e035a44837da865c2">getTypeReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7c6fd268e11e2eb6e8d13ed32b1820c">llvm::getVRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a1cfc09d31eaed5d0ca0725d09e044b47">llvm::RISCV::hasEqualFRM</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a334e7c41df90efd700b045c03de6777d">anonymous{ARMLowOverheadLoops.cpp}::VPTState::hasImplicitlyValidVPT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2f1cfe9c040112cbf97a025655d3595e">llvm::RISCVInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea784a4f9e9aba7792c23484e2498e8d">llvm::TargetInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/gintrinsic/#af50bdc16c0237060dce1cd67be3fee27">llvm::GIntrinsic::hasSideEffects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a2eff58d9105525f19d5cbe2fa6969d6e">llvm::SMSchedule::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/gaddsubcarryout/#a03bddab5de1aabdab0c2344803fc119e">llvm::GAddSubCarryOut::isAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinescheduler-cpp/#a39cb081a14bceac85a10e7a987109c1f">isADDIInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a919a65c38470ee5665afa859cda18025">llvm::PPCInstrInfo::isADDIInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a849ceee707ad46510fd6a651de065478">llvm::PPCInstrInfo::isADDInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a4bfef92511266e23c47f58129e287b40">isAddressLdStPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a2510546173c41b2a0bd6c02fedacb656">isAddSub2RegAndConstOnePair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a98c653d2ef785dcf4a6afb45e98f011f">isAdrpAddPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a86a21c7671a0b528ed3634aa3314a851">isAESPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a045747da87fc8c9fdfd52b47aac112c1">llvm::isAESPair</a>, <a href="#a500ac55b1c16a71c77fc50c482df643a">isAnnotationLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a32b9b3cc2b63db0558c672148f375cae">isArithmeticBccPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a6c0f387dd7dc401e5a50c0cdb1cd3035">isArithmeticCbzPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#abb2f88865c1a6f9c476edd8b18c4b360">isArithmeticLogicPair</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab3d65d6e0daa1da2c564a3803f207b2">llvm::AArch64InstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8d93b0ff1b64f553c4e86fdebacff56">llvm::PPCInstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ade726ab992f758b88dcc4d6691efd90d">llvm::RISCVInstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a5183ec05f7f9d8e1211aa1fd88200fd9">llvm::SystemZInstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a6809308720683fc5bf1cb8ac00529ecb">llvm::X86InstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a596366d4034015c0668d2070e597425f">llvm::GIMatchTableExecutor::isBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4760bd5cfc1e3283253a7b0d06beaf90">llvm::SPIRVGlobalRegistry::isBitcastCompatible</a>, <a href="#a3e2f795dfcb9269e1263453796f4b994">isBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a1bcf009f708fdf8a9c5cf20646d86007">isCacheInvOrWBInst</a>, <a href="#a806028855ad5c3431de7958e031e5ee1">isCandidateForAdditionalCallInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#aac55ba69021576846ac03b0050c022a7">isCCSelectPair</a>, <a href="#a75489f444c9e3bdc12cb985c54d84a37">isCFIInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#aecef689b4ba2a5bf1d3609151f448180">llvm::AArch64GISelUtils::isCMN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a89fae3db628b477b713990d7a58732ea">isCombineInstrCandidateFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#aa737e66804d935143b89db74d5646610">isConstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gintrinsic/#a318f8e09dbafc6938faa91aa457835fa">llvm::GIntrinsic::isConvergent</a>, <a href="#a1912d4fbc40c61a12b1f770ad54dfd74">isCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#ad3d81e8369f2ca48db8ce9ec078d2cf1">isCryptoEORPair</a>, <a href="#a2502a65c42b09e02d163611edb263c84">isDebugLabel</a>, <a href="#a5d26e3ed3815037e0cc1b25a85c3a0e5">isDebugPHI</a>, <a href="#a4f5ab028b0c4242fd4409a3e50028339">isDebugRef</a>, <a href="#a071ce84bf9c71b9b7d6ffb30639ce602">isDebugValueList</a>, <a href="#ad803ef666d44b78308d571df8b445f63">isEHLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a791f9b87aba84585f9777360bb26d84b">llvm::AArch64InstrInfo::isExtendLikelyToBeFolded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a44896316bcf65958ba14a3afa8fa193f">isExtractHiElt</a>, <a href="#ab41b2896b8454188401b6e11a972a2d0">isExtractSubreg</a>, <a href="#af2df666e80610d028fc34fc23a82dd27">isFakeUse</a>, <a href="#a85cc92e3de77dfa4c19718a43b02eb16">isGCLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a3b0f315e261e572d6f0b357e4404ca42">isGuaranteedNotToBeUndefOrPoison</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a120ccebe70e1b0ddf72fc776229d0025">isImplicitDef</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="#a9de0e8de0615ba9a3e4fa551e25ddcee">isInsertSubreg</a>, <a href="#a974b18e3dd15be812200ec75dc0d3137">isJumpTableDebugInfo</a>, <a href="#ae9723ca940711fa1a09c0d53efeef5fe">isKill</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="#a9f137387193043b6e4f37112d60f748d">isLifetimeMarker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#afb7db40b967a5d8798362bc1c818917b">isLiteralsPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf088bf4647185e93afce15d8235c2bb">llvm::isLiteralsPair</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b26bab239d68047b97e5785f802c183">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::isMatchingMovConstInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a0f95f5fe4853d046274eb0edfb483d70">isNoUnsignedWrap</a>, <a href="#ad43bf1af480830a4d6604e969e3f38e9">isPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#aef3719986b91bc4fac189135bd3795a8">isPreLdStPairCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a3790c110e8f9d3ffde8dfde05bd53edb">llvm::ARMBaseInstrInfo::isProfitableToIfCvt</a>, <a href="#ad82bec8563e9409362aaedd5346a3f17">isPseudoProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp/#adf2ee57aa544018b7e0092782fe00170">isRedundantFlagInstr</a>, <a href="#a8d97d09150ddcbcf5039f938111358ee">isRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#afa113683bb9cebc99c2711ac4a4c36dd">llvm::VLIWResourceModel::isResourceAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ab91827a04a8d97aa04d5fd0d86ec790e">llvm::SPIRVGlobalRegistry::isScalarOrVectorOfType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64fastisel-cpp/#a493ce0d59d5453a9230bcc292b7c8a26">isSExtLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/gaddcarryout/#a176e82ed5825065ccfffeeb5735f9198">llvm::GAddCarryOut::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/gaddsubcarryout/#a8bc59b9ea9a39894c67b1e745338576a">llvm::GAddSubCarryOut::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/gsubcarryout/#ac6455126213be6a5e2e7be0d2dd3bc91">llvm::GSubCarryOut::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/gsucmp/#a840aee2a7e43caec45bd5a0ff05b3065">llvm::GSUCmp::isSigned</a>, <a href="#a5822e16afda1fcf154cfb4179bacef3c">isSubregToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="#acaeaa72d4f5f8423ebade5ac38060b42">isTransient</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a5cfcaf632d98be49b27f2ff3a3c8cbb1">IsVPNOTEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a80ca145710cb63f6d1484dacf37a8620">isWaitInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64fastisel-cpp/#ad02b77dfc53da932b027dd1af33f96bc">isZExtLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aeb5e4e41c7dda3b942168ed881fa1d13">llvm::SPIRV::make_descr_sampled_image</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad1ced720461881db2f1371e0f30ff744">llvm::ARMOverrideBypasses::makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryop-match/#aa22431f74a092ef2095e5e7fdfa9e9c9">llvm::MIPatternMatch::BinaryOp_match&lt; LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryopc-match/#a7a3bed68c87689c4510c602f959f32f0">llvm::MIPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/compareop-match/#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/implicitdefmatch/#a7d62ea67a54a46c98b4eddb83e1e70f9">llvm::MIPatternMatch::ImplicitDefMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/ternaryop-match/#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/unaryop-match/#a03468639caa1fb6be4bb742a181faf81">llvm::MIPatternMatch::UnaryOp_match&lt; SrcTy, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae88fdd4a40851c70c1f04282174034c2">llvm::CombinerHelper::matchCastOfBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aeb8af468cabe232d8d64944acf6930b7">llvm::CombinerHelper::matchCastOfInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afaeb891d2410d3aaf4d95fc61028f7b4">llvm::CombinerHelper::matchCastOfSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af73a2a8f01e0df7eb8908768292dd30e">llvm::CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMAAggressive</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a045bd704a82578777117625df4358b32">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5fd133d3cc0d8e1b33fe7ae34657d45c">llvm::CombinerHelper::matchExtendThroughPhis</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a6288bdc9c0864757a314ab233c31590d">anonymous{AArch64PostLegalizerLowering.cpp}::matchExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a7b617a5a6a2773b70ea354e1dffceff7">llvm::CombinerHelper::matchExtOfExt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a21a291953b9b99793faf8bea9286ebd7">llvm::CombinerHelper::matchExtractVecEltBuildVec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a8106e2049da0be5e2759557e0c7cd971">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aca13b2618c4733bb6b46c2667fbd847b">llvm::AMDGPUCombinerHelper::matchFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#ab3b5b3cb426c4343af3b06f32bd5f568">anonymous{SPIRVPreLegalizerCombiner.cpp}::matchLengthToDistance</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a59e682863250eb07290a348d548eee0d">llvm::CombinerHelper::matchNarrowBinopFeedingAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab40d01e80ca225a11dcdb8adbf4e843a">llvm::CombinerHelper::matchOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a33c6405fe05b24b5d3f9c0ec0ed7f9ae">llvm::CombinerHelper::matchShiftImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8434510d79fe87971bb903ab82cc1fc3">llvm::CombinerHelper::matchShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2e6e1c84d8b84dbd2101236bca332d95">llvm::CombinerHelper::matchSimplifyNegMinMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9e44e0e5bdc7526a1b299ae804752709">llvm::CombinerHelper::matchUseVectorTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinescheduler-cpp/#a069f6bd5e8ca662cfbeeb43f90a5a97a">mayOverlapWrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ab7cbed44cf5366935e93c0a0182dfd5f">llvm::CallLowering::parametersInCSRMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a51b6112b4ae42ce9cd677fcb2bb1af19">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::processSeqRegInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a8ca037899f2fcee956e635f6f5c0cb2c">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::promoteSoftWaitCnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#a6641c29e6f96fdf149d7f9f5dddec48f">llvm::VLIWResourceModel::reserveResources</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a5536577e4a955f5327410bda9cf3e7ed">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::reuseDUP</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sipeepholesdwa/#a1bdd26eea6b96e305497ca5ed1a983c6">anonymous{SIPeepholeSDWA.cpp}::SIPeepholeSDWA::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a506d59d745bce4ecf472b2a3580219bd">llvm::MipsInstrInfo::SafeInFPUDelaySlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpumacrofusion-cpp-/#af5da450a1411e5b2e09527cb36568ff1">anonymous{AMDGPUMacroFusion.cpp}::shouldScheduleAdjacent</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a5362d2941268801aae99c4ea089c25cf">anonymous{PPCMacroFusion.cpp}::shouldScheduleAdjacent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnvopdutils-cpp/#ad07ebf0671a72f8469ed76bab0846ac2">shouldScheduleVOPDAdjacent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="#aa37e31e5df481d2f8a6f9f022886cf5e">tieOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#af4696dcc1ada21996da960c711f26ee1">llvm::LegalizationArtifactCombiner::tryCombineAnyExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a5ccd1c1459e615587ee51ab55dea54bc">llvm::LegalizationArtifactCombiner::tryCombineSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acab876eafd3f522831a5d002faecc72b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldZeroHighBits</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a7c833b32f9576a77193082ed28b7a5cf">AMDGPURegBankLegalizeCombiner::tryMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9a9739cf49c46adcb76ac7e2dc13545c">llvm::CombinerHelper::tryReassocBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3dc1ad6a578f69fed203a6022699080f">updateGetPCBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad6611e7ee084ecf0ef7b23ca25b50db0">validateAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#abbe8c4ff227aafd9e016eeb143490bcc">validateGroupWaitEventsPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a51ac6439b177bf76b27b1fd1a4f30ca3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a34005879daabad613a9f682bc30c0fb1">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSERT</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ad457d12e54f0a38894c84aa6901838b5">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSvi64lane</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a> and <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a>.</p>

</div>
</div>

### getOperand() {#ad67c9230577a0b640c52852c75c93939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineOperand &amp; llvm::MachineInstr::getOperand (unsigned i)</td>
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



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a>, <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a76f229e9f5c9ffd689f6b437accb522d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::AddVCTP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#ae5ced970396c0f7c3cb7644340597544">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::adjustCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a83aa1663ebe23169979a76be989b1144">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::adjustTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a126f327d0727647f3daa7cf0da944f9e">allPhiOperandsUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa61674464afddf4b2a24ab65f3833233">llvm::AArch64InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#ac741087fd882a50ae09491bdaebcaad9">llvm::NVPTXInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedb2f85719d229f0c9bc62ab1d17e918">llvm::PPCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#ab2592d528f736ade8f940d8b80c8d040">llvm::SparcInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ab536cb6776e394559d7109c0d6840c2e">llvm::VEInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a092553d9bd8edd039d855fb411c6d887">llvm::XCoreInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a51f54f2b0fd916f4c01b600905180782">llvm::AArch64InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad304b10479d6791deee8ad1b157fb37f">llvm::X86InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab359f8ff91954b23a1e8366666e59cbb">llvm::AArch64InstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac2377979438dcdab9e664ccd5f975dac">llvm::CombinerHelper::applyCombineDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a00301689820a26a9f3b438f6dece6ef0">llvm::CombinerHelper::applyCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac91aca84eade26acea192464a9cfcde8">llvm::CombinerHelper::applyCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afe9d6cb97689cb5efb1a5b8f9dc68ea0">llvm::CombinerHelper::applyCombineUnmergeZExtToZExt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa09e8f13910a43ba1b8edc182c7a212c">llvm::CombinerHelper::applyExtendThroughPhis</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afa907eb6ba127a5f4167f5a1671efed0">llvm::CombinerHelper::applyOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad8a483afeb99148394d2586c5601e441">llvm::CombinerHelper::applyShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#aa67934d23b1e9ff1901ec570930128e4">areCombinableOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a69f0bf266f1e42f9d65ec549a6481ba6">bbIsJumpedOver</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a7bc05bcba45ed1e4e903c1c952d09178">buildRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a544e5e38d5032dd862ab44953c2c173b">buildScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aab7185336f5a266b994341f14bc8faac">canCombineShiftIntoShXAdd</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a2a5ba8caf566b63bea759399eb58927f">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#acc9e7924e2ef2b569d74df940b3dc0fb">canEmitConjunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4ab4c0bfcb70883e983a325153b5a44e">llvm::HexagonInstrInfo::canExecuteInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a80ba8826b4f8e7008ae9453968ed35fa">canInstrSubstituteCmpInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="#aaaf972edd3d60e198b996c65e05c4a5a">changeDebugValuesDefReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#af2048f0f8425833d77baeb4baeadc779">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::checkMovImmInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a148883092b4d2dfdc994bc095ec153d7">anonymous{PPCMacroFusion.cpp}::checkOpConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a93c989266fe445bd8d6466480699665e">llvm::WebAssemblyDebugValueManager::cloneSink</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8853b2033702691c17576d5acc430460">anonymous{PPCMIPeephole.cpp}::collectUnprimedAccPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#af76e71e7ea189719baa6f8819724fac5">llvm::ARMBaseInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#ac1e0d325060a529e2c20cc9eebc23351">ConsecutiveInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae780082016f8641ba5a18009b135d01e">llvm::R600InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#ae5e50a6a8cb928fb34cd4fde19384381">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::createCRLogicalOpInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a08073cedfc0efeff220a6af9b84d2cb6">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a46b2b58b4eaac69bb5cf98a05b2ab1be">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a413489f8f91ace88c20648ec2aa8b776">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8be157bc7b2bed40b10198e8b6a2bfcf">anonymous{PPCMIPeephole.cpp}::eligibleForCompareElimination</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a4689c1a05c58cd8e0dbb57bc84fdc8cf">llvm::ARCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a0ab2cc201e1521acab599966d10b815d">llvm::XCoreFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#a561e8197481b2a01d7f75fd567c7801e">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a6e8a4f85c8a56769ce682ff88d5b60f1">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acd9a409ba62041c36090fe42bfdf16d7">llvm::M68kInstrInfo::ExpandCCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#acf2585460bbea1e2bac210c9588d4bc4">expandNOVLXLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a44f31fb5ea31b5062b22b05cb8fddee4">expandNOVLXStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a9dec32763bff61fb024d352592596f99">expandSMEPPRToZPRSpillPseudos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a1511e75a5fe8384a21552151b86eac3b">llvm::AArch64GISelUtils::extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa8aa7be4bd12d2e18b08a87805017131">llvm::RISCVInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a977522c71b9c7099aa74222cc12bbf17">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a85299a5742cf6712729343b973727ab7">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findLongFormInRangeCPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4aadfbe4795304e72a1a7be77ac88be7">findLoopComponents</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="#afc1df0cb1a8c3103a4266def94c3a670">findRegisterDefOperand</a>, <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>, <a href="#ab692b90c6e0e9b450f407896cbbe4b02">findRegisterUseOperand</a>, <a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a>, <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3e3daf4218b791b2796b808627b7f864">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9eb43774a0046a364f5c45f94576bc43">llvm::PPCInstrInfo::foldFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#ac962fea3028517b39dcd1f4cff0c0112">foldImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a5278ce924df77790e6a938f5065ba5a0">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a3a67d4b5306c3571138e241d77393283">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a52300ffc2cad932b8451cdd3ae41a470">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#abdd08d782bfb8c6b53e27485a53a3477">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4862e12e65a868264ab84a2252104dda">llvm::RISCVInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6875e5a149ffdf299b10e8f969d379d4">llvm::TargetInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af64fc386f3fc81f753830641399254b9">genFNegatedMAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6893512d8a2c2aaf9d6758440d1bc583">genMaddR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a875d4d0bf620bc2515b57e5554a510fb">genNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a4b49090437c0021f09fa86c3965bb855">getAS</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#ac0bde568b3078ec6c6fce434997dcfe5">llvm::GIndexedLoad::getBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a697bae68deffc62d869832a6a9d618a8">llvm::GIndexedStore::getBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#a7f5a93aed60bbe1badb84e5e06f46b31">llvm::GInsertSubvector::getBigVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee97b28988a36d015094f659294ef99d">llvm::getBlockStructInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac8e4876fffd2ceada8ef6428258d7236">llvm::HexagonInstrInfo::getBundleNoShuf</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#aa598b3407f82a894e4f5a82676e5bc43">llvm::ARMAsmPrinter::getCodeViewJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af668609d5285820d674d655ab3990c91">llvm::HexagonInstrInfo::getCompoundOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/ganycmp/#a9b5d6b8ad9231f5abbb1bb86497c0133">llvm::GAnyCmp::getCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c64e87ab3dd6ef5ea0c229712f1fd63">llvm::X86InstrInfo::getConstValDefinedInReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a7b4dfdd596d675a34ee339b581424255">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a5077615197d034930b58d221032e96f0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getCPEAlign</a>, <a href="#a539133bbbe620ce232f698234544b990">getDebugExpressionOp</a>, <a href="#a3736f5c23004fc6d6b0d0dc773efe7e2">getDebugExpressionOp</a>, <a href="#a8de5351053b099124a2e2ea477ed54c9">getDebugLabel</a>, <a href="#a51da1bfa6bdaa6cd06be2a3b92ccae1a">getDebugOffset</a>, <a href="#acdbcc97c288440883cc78c74fed7066e">getDebugOffset</a>, <a href="#ac916b8cc2bbad1b2fad0d16486ee7593">getDebugVariableOp</a>, <a href="#abfcdb704dc6511a2c0b93fe4e5987182">getDebugVariableOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc8c7c7ca66d38ff9fd8c34f64a0fd4e">llvm::getDefInstrMaybeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#a4fe5ff0257f5b8749cbe223b848b2570">llvm::GAnyLoad::getDstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#aa4a6851394161d4ede155772de827f68">llvm::GIndexedLoad::getDstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertvectorelement/#adedb063efa4089b32b852b1fc2df03e2">llvm::GInsertVectorElement::getElementReg</a>, <a href="#a620b1d8de0e32491f106ddc997914153">getFirst2LLTs</a>, <a href="#a817d92911624542113807dc07a46bfb5">getFirst2RegLLTs</a>, <a href="#afeb98e93a7bcdce78a80a51a00610c2c">getFirst2Regs</a>, <a href="#abeb0ed106bd6d33c0cf49a89083a74ad">getFirst3LLTs</a>, <a href="#a31012ec441c425a3eeb652d31ab0a8ab">getFirst3RegLLTs</a>, <a href="#a98055346309284ec85c366c2802bd265">getFirst3Regs</a>, <a href="#ad2b80d7b9f05e663c35bd72cece6ebd7">getFirst4LLTs</a>, <a href="#a80edb692b5f12ebc13ea0c6558e2cc85">getFirst4RegLLTs</a>, <a href="#a11b18514df4193347c1d9ff3773ca850">getFirst4Regs</a>, <a href="#a2e82295f594d02e8290f214b5a4c3551">getFirst5LLTs</a>, <a href="#a1345402d2906eacc2db93c4bb59cf861">getFirst5RegLLTs</a>, <a href="#a01c0bab24b110610c39c166eb5db9ddf">getFirst5Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a1f24abade2ffdb0e55559d552552692c">getFMAPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a337903856769965870a905f37f63790d">getFNEGPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/gphi/#a4e1601b459e7cb36d7a623f500595600">llvm::GPhi::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/gphi/#a75d330f905b8fad10f17f93c05dca4bb">llvm::GPhi::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractsubvector/#a4d73c6ddaba313a4f41e0fc1b16bb197">llvm::GExtractSubvector::getIndexImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#aa2e5c0f1932c6d84f43c0f2a7ca780eb">llvm::GInsertSubvector::getIndexImm</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertvectorelement/#a8bb403957bec222954776225dcb40117">llvm::GInsertVectorElement::getIndexReg</a>, <a href="#a8b94b1143638cb1b18d976bba0b0ec3a">getInlineAsmDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/gintrinsic/#a5fa14f1396039c08f7b64717bdc2b830">llvm::GIntrinsic::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#a0a6ba285db730057d220b52b594c0870">llvm::GBinOpCarryOut::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#abc631c430bcd8a73482dd4ea8495a38a">llvm::GBinOpCarryOut::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gsucmp/#aa63d83a3ebb133b4cb37bd2d1e72b8d0">llvm::GSUCmp::getLHSReg</a>, <a href="#aea65fa322ddcff0ca4cd6f83ccef77e0">getLocCookieMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a819a79471317d350cbad8cfe9ad1c98e">llvm::getMachineInstrType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a054d573171c2fcf38b33a60e412dba7b">getMaddPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#accb4d1c10e950e995f808829b4f3a106">llvm::GShuffleVector::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9f95e557fb675ab6ef80f2fc4b8b3e01">llvm::AArch64InstrInfo::getMemOpBaseRegImmOfsOffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a934f16bd434319b64e63ae8f622991ce">llvm::LanaiInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab6a37e8549580d302c7c98852a4ddc11">getMiscPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#af58cbab9cb762f2d2a4baae6177e30e4">getNewSource</a>, <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="#a56b7fed94faeb5bc67ee2b71608d2665">getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47bf073dca31bf981a1a425cf537454f">llvm::getNumSizeComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#a55ae2aa029e53a42aeac16f01e0c42ad">llvm::GIndexedLoad::getOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a11b1c0ab42243c261e9876a66ee11d05">llvm::GIndexedStore::getOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3dddf52f700258ac37fa137527588809">llvm::SPIRVGlobalRegistry::getOrCreateConsIntVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abab34b1cb73af8519772979270773492">llvm::SPIRVGlobalRegistry::getOrCreateConstIntArray</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#af30efc6374f891c0dd222ed8610919fd">llvm::PeelingModuloScheduleExpander::getPhiCanonicalReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6d986da977a884fc79751da79c4e6f84">llvm::SPIRVGlobalRegistry::getPointeeType</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a55bb47729cc153812bf4c00989460022">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::GetPoisonVal</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a584585671a7593c76cc4499d6d75791e">anonymous{PPCMIPeephole.cpp}::getPredicateToDecImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a47d74d7e9fe3fe56430321c2a238536d">anonymous{PPCMIPeephole.cpp}::getPredicateToIncImm</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ab6e454de3dfa112cc7e30219ac7298cd">llvm::SPIRVGlobalRegistry::getRegClass</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="#a88f8cb24fba67649c1f32531d0f6ab90">getRegClassConstraintEffect</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#a05b14746ff716d7e41076dc953e85f4c">llvm::GBinOpCarryOut::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#a9f92d09b678eb63420aade92877ee278">llvm::GBinOpCarryOut::getRHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gsucmp/#a0231b89d00ac00db99eabe02a0225aed">llvm::GSUCmp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#a894fb383cc3e3a326646b5f3366881d2">getSalvageOpsForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/gsplatvector/#ac79651a4264897232305a8abf81dbe76">llvm::GSplatVector::getScalarReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshl/#aa8482d32667b4117740e52c87ff6c45a">llvm::GShl::getShiftReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a61c12dc12b135090e87fcfb959c58f47">getSingleUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/gfreeze/#a3eb22715cd9f29136f9d6f7ba914c5ef">llvm::GFreeze::getSourceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gunmerge/#a5f5a5fac10a0aadbff8eb0ec3cad5b60">llvm::GUnmerge::getSourceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gvscale/#a7c67c8f218bb124662af98cc5a846e98">llvm::GVScale::getSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#a54b06a5a5effc72c6bc4b9b678f20be2">llvm::GShuffleVector::getSrc1Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#a4ae3c15df3186decf42fd763ef386c43">llvm::GShuffleVector::getSrc2Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshl/#af0470ee08a8edb0aea1b769274cf853d">llvm::GShl::getSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractsubvector/#a46b0ae0d1f1b432d5c49b1e0103cab23">llvm::GExtractSubvector::getSrcVec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#aff059e4f5e8216de3172acd39a6e0ff8">anonymous{PPCMIPeephole.cpp}::getSrcVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gstepvector/#a3d228390eddc89596585e7392a679792">llvm::GStepVector::getStep</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#a2045dc53a7fe26b15fca8c2904955fa0">llvm::GInsertSubvector::getSubVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#aaec6e6ec16a011ef89299012d0dbe146">getTargetMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad64a5996fef41f1e035a44837da865c2">getTypeReg</a>, <a href="#a9dbc9a748353035febcc488160ba9956">getTypeToPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a34948b6b7734673470a3d7fcc5a16676">llvm::GIndexedStore::getValueReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gstore/#ab80d0571fdf63877734e0f7bea4e886b">llvm::GStore::getValueReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#a9bdb58d595df6f79845de5cf0139ad8c">llvm::GExtractVectorElement::getVectorReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertvectorelement/#a1e833adbe8c062dc441eb3426bad4390">llvm::GInsertVectorElement::getVectorReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7c6fd268e11e2eb6e8d13ed32b1820c">llvm::getVRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#a863dae0fbf6415e6c7cf58ac82f348e7">llvm::GIndexedLoad::getWritebackReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#abf110cb21758b8ed3417e46417434b06">llvm::GIndexedStore::getWritebackReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="#a9d2b6142e2253bdad20b1f980f53f216">hasComplexRegisterTies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a1cfc09d31eaed5d0ca0725d09e044b47">llvm::RISCV::hasEqualFRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab7919507c578187e698ff01a1f204478">llvm::RISCVInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6034cfb230c4698caa60bdc3a9bf209b">llvm::TargetInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2f1cfe9c040112cbf97a025655d3595e">llvm::RISCVInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea784a4f9e9aba7792c23484e2498e8d">llvm::TargetInstrInfo::hasReassociableSibling</a>, <a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a648e69f41d62376b996b0b5209022fbd">llvm::R600InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad73e9b3e610bd8cac60e740a61fcf5bf">llvm::SIInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa859694dc733dcc4def80843314a9666">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::insertCondBranchBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ef020b54917711fa4fbe9b8ad48258b">llvm::SIInstrInfo::insertScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a919a65c38470ee5665afa859cda18025">llvm::PPCInstrInfo::isADDIInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a4bfef92511266e23c47f58129e287b40">isAddressLdStPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a2510546173c41b2a0bd6c02fedacb656">isAddSub2RegAndConstOnePair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a32b9b3cc2b63db0558c672148f375cae">isArithmeticBccPair</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a596366d4034015c0668d2070e597425f">llvm::GIMatchTableExecutor::isBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#aecef689b4ba2a5bf1d3609151f448180">llvm::AArch64GISelUtils::isCMN</a>, <a href="#a37fa340555fb189bce42efadf42c5253">isConstantValuePHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#aa737e66804d935143b89db74d5646610">isConstReg</a>, <a href="#aaf9df5fbb2543faa0659f9b31f907df9">isConvergent</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ad1c6e08944b4fbe61244afe2ca4b113d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::isCPEntryInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a31eb3e86e2c774c4c03267a7368cadf0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::isCPEntryInRange</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a360c1f17e2f45595561f8b80c76dbf8e">anonymous{PPCMIPeephole.cpp}::isEqOrNe</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a791f9b87aba84585f9777360bb26d84b">llvm::AArch64InstrInfo::isExtendLikelyToBeFolded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a44896316bcf65958ba14a3afa8fa193f">isExtractHiElt</a>, <a href="#a6ee45760c97bf2dda6bee91508e6946e">isFullCopy</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="#add5255eb40b106f13738476389bfa5a6">isIdentityCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#afb7db40b967a5d8798362bc1c818917b">isLiteralsPair</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b26bab239d68047b97e5785f802c183">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::isMatchingMovConstInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a7ee076808f65d7b724d9a94d48b2cee8">isMatchingStartStopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#ae773ebcbd5bb0d4b4dea1250877dc716">llvm::GIndexedLoad::isPre</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a9720bac244d8ac1281ce92b11390d73b">llvm::GIndexedStore::isPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp/#adf2ee57aa544018b7e0092782fe00170">isRedundantFlagInstr</a>, <a href="#a391694f8040173dc0670bd273b170502">isRegTiedToDefOperand</a>, <a href="#a6df9a6b70a33aee123056cec0ed052c4">isRegTiedToUseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a2142c4566b7d15a35687f955d946a277">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::isSafetoMove</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4eb4dcdccf96e4fd24c31db70617c00e">llvm::SPIRVGlobalRegistry::isScalarOrVectorSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="#a6b98ba8c44d9287df1be03859570b589">isStackAligningInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a809bcfaa5a36e8e145a700b3e0e21926">llvm::PPCInstrInfo::isValidToBeChangedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a5cfcaf632d98be49b27f2ff3a3c8cbb1">IsVPNOTEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a80ca145710cb63f6d1484dacf37a8620">isWaitInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#accc5aa5171b3bf3b455bbbac12dd405e">llvm::X86InstrInfo::loadStoreTileReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aeb5e4e41c7dda3b942168ed881fa1d13">llvm::SPIRV::make_descr_sampled_image</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryop-match/#aa22431f74a092ef2095e5e7fdfa9e9c9">llvm::MIPatternMatch::BinaryOp_match&lt; LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryopc-match/#a7a3bed68c87689c4510c602f959f32f0">llvm::MIPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/compareop-match/#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/ternaryop-match/#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/unaryop-match/#a03468639caa1fb6be4bb742a181faf81">llvm::MIPatternMatch::UnaryOp_match&lt; SrcTy, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a54d65481969f8d9628b5ee128c99212b">llvm::CombinerHelper::matchCombineFAddFMAFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a246c328def50bbd9e892666ae3fb1947">llvm::CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af73a2a8f01e0df7eb8908768292dd30e">llvm::CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMAAggressive</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ade46635032e4ec34657bc9b237d37e0b">llvm::CombinerHelper::matchCombineFSubFNegFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4c9b7bf9027b6c116d92fbebd2ba8372">llvm::CombinerHelper::matchCombineFSubFpExtFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac4a2ebe747c416cbe4efb4b77ba2b588">llvm::CombinerHelper::matchCombineFSubFpExtFNegFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a045bd704a82578777117625df4358b32">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a6288bdc9c0864757a314ab233c31590d">anonymous{AArch64PostLegalizerLowering.cpp}::matchExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a21a291953b9b99793faf8bea9286ebd7">llvm::CombinerHelper::matchExtractVecEltBuildVec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a74c47491ee867baa1f14586d759342ee">anonymous{AArch64PostLegalizerCombiner.cpp}::matchExtractVecEltPairwiseAdd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a8106e2049da0be5e2759557e0c7cd971">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aca13b2618c4733bb6b46c2667fbd847b">llvm::AMDGPUCombinerHelper::matchFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#aafc3cb0155754ef1fb6ed53375e4d3dd">anonymous{PPCMacroFusion.cpp}::matchingRegOps</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a59e682863250eb07290a348d548eee0d">llvm::CombinerHelper::matchNarrowBinopFeedingAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab40d01e80ca225a11dcdb8adbf4e843a">llvm::CombinerHelper::matchOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a33c6405fe05b24b5d3f9c0ec0ed7f9ae">llvm::CombinerHelper::matchShiftImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8434510d79fe87971bb903ab82cc1fc3">llvm::CombinerHelper::matchShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a12794dfd41dd116d9e295524d932f6c0">llvm::CombinerHelper::matchUnmergeValuesAnyExtBuildVector</a>, <a href="#afe1802220ee7c164e882ade3d80f1845">mayFoldInlineAsmRegOp</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a>, <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afc26610b4c561e17a9ceb497233f34cc">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::modifyCmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4da36cb65ef881f12fe1d40a47223a61">MoveVPNOTBeforeFirstUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a776834e825e7fd9cd90c27f7ace1d9d2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::needToBeConvertedToVALU</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ab7cbed44cf5366935e93c0a0182dfd5f">llvm::CallLowering::parametersInCSRMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a51b6112b4ae42ce9cd677fcb2bb1af19">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::processSeqRegInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a61326cd6384971e828511e500b3367c6">processSwitchesConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="#a374fc9d9064a93ef8a408f269d02389d">readsWritesVirtualRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aa86a4d647e79dbdeb3d2d43ec301abcd">llvm::SGPRSpillBuilder::readWriteTmpVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a68cd342c50f56c8da7e9c41ce92d14b1">RemoveDeadAddBetweenLEAAndJT</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a5536577e4a955f5327410bda9cf3e7ed">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::reuseDUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd46906c25e4d5703a8e422283d03bde">llvm::RevertLoopDec</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a71a08885f7838dc5a544816a357e2ec7">llvm::MachineSSAUpdater::RewriteUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a1ee52a66badadfe0d31d88d614305f41">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#aaf4297850ccff6052205f45bc2ba2f87">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#a7e75a4f6568424bf0940a7c509a6d18c">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoreframetoargsoffsetelim-cpp-/xcoreftaoelim/#a2ef5edc1bc3d0736ef24263d9e6b0d69">anonymous{XCoreFrameToArgsOffsetElim.cpp}::XCoreFTAOElim::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a45ffb8b95e5b75eeb68be7d300eb9618">llvm::MachineInstrBuilder::setOperandDead</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#a9d9c7bebc5b5d451511265937418ed6a">splitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a92e31a04c0a1b5d17db90c99fa48f6aa">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::splitTwoPartImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30233b5b4decf678ec7ed144ac1f729b">llvm::MachineFunction::substituteDebugValuesForInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>, <a href="#aa37e31e5df481d2f8a6f9f022886cf5e">tieOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#aaaa5a895e6a8003daae912a9bf636040">llvm::LegalizationArtifactCombiner::tryCombineExtract</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a553d8629e18f8acb82dbadd0a160b877">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a7c833b32f9576a77193082ed28b7a5cf">AMDGPURegBankLegalizeCombiner::tryMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9a9739cf49c46adcb76ac7e2dc13545c">llvm::CombinerHelper::tryReassocBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="#a8e66e9ca7739874b25b9337940c26a0a">untieRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a062ea093e135121a384a1c6c4cd3d96c">llvm::HexagonPacketizerList::updateOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad6611e7ee084ecf0ef7b23ca25b50db0">validateAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adc3ecee5ecd3f86b45e6779653ca10da">validateFunCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a51ac6439b177bf76b27b1fd1a4f30ca3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ad457d12e54f0a38894c84aa6901838b5">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSvi64lane</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a>.</p>

</div>
</div>

### getOperand() {#a6197870d7271620c9bad9f4a649fc26a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; llvm::MachineInstr::getOperand (unsigned i)</td>
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



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>.</p>

</div>
</div>

### getOperandNo() {#a5574b8f058874009cab01e055a44338a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::getOperandNo (<a href="#a476971826fa13b07e28ad971ec5a3234">const_mop_iterator</a> I)</td>
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

<p>Returns the number of the operand iterator <span class="doxyComputerOutput">I</span> points to.</p>

<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a> and <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>.</p>

</div>
</div>

### getParent() {#a1e855100f407ca4be098d0050be403b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * llvm::MachineInstr::getParent ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#aabf3514a1ace5d142cc33b48f3eb3f63">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac3d33d3a8e2cf3bdc2932450f90f078f">llvm::LiveIntervals::addSegmentToEndOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a19dd673b5e34f3c83c6c17f780836bc7">addUnreachableAfterTryTables</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#afd833dc91598d5a3c3f327b47b98a4cf">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMoveToEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a9899e618878cac6bb75eafe4d46810f4">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#ae5e50a6a8cb928fb34cd4fde19384381">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::createCRLogicalOpInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8be157bc7b2bed40b10198e8b6a2bfcf">anonymous{PPCMIPeephole.cpp}::eligibleForCompareElimination</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#afea2f73a2971b1c2238c0996efdb1201">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="#a9891e442de101ced8a1533a71511dbed">eraseFromBundle</a>, <a href="#ac2421adbb9996e1b15f03a8abb6c70a8">eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d6c4616e2c2cc90d58377868eda6102">llvm::examineCFlagsUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ab69e2cd15cb4ac3f0262a15fdd65befa">expandXorFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a079add9cf3b7069c79b91a3d8c7c28a3">llvm::findCMPToFoldIntoCBZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a541bb79da42e4b8f77617678e7f47d83">findPrologueEndLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a349ccb69c0901c3188afbce59873f56b">findSingleRegUse</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#ab273671903c0baabbbf098a0a4581101">llvm::ARMBlockPlacement::fixBackwardsWLS</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a52300ffc2cad932b8451cdd3ae41a470">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6875e5a149ffdf299b10e8f969d379d4">llvm::TargetInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="#ad26a74fb0ad868f0867cce317269d721">getDebugInstrNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a1f24abade2ffdb0e55559d552552692c">getFMAPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a337903856769965870a905f37f63790d">getFNEGPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a23c3c91648996442b88f0c53cf1415d8">getFoldableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6154e5a73b50ec0dbf9d6790b70da1a2">llvm::SPIRVGlobalRegistry::getFunctionDefinition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseregisterinfo-cpp/#ae4f8119e930e450734d4903391aca1fa">getLoadStoreOffsetSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a054d573171c2fcf38b33a60e412dba7b">getMaddPatterns</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab6a37e8549580d302c7c98852a4ddc11">getMiscPatterns</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#a5bfbd2de15729b28a19c4816c280878a">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::getParentInst</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#af30efc6374f891c0dd222ed8610919fd">llvm::PeelingModuloScheduleExpander::getPhiCanonicalReg</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#aff059e4f5e8216de3172acd39a6e0ff8">anonymous{PPCMIPeephole.cpp}::getSrcVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a334e7c41df90efd700b045c03de6777d">anonymous{ARMLowOverheadLoops.cpp}::VPTState::hasImplicitlyValidVPT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab7919507c578187e698ff01a1f204478">llvm::RISCVInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6034cfb230c4698caa60bdc3a9bf209b">llvm::TargetInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea784a4f9e9aba7792c23484e2498e8d">llvm::TargetInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa859694dc733dcc4def80843314a9666">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::insertCondBranchBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a4eb10bbe55466736b6d97ce923f4c973">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::insertInstrBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a8b2189b37dac8aba6dc3f5a39824d00b">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::insertReloads</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aab3d65d6e0daa1da2c564a3803f207b2">llvm::AArch64InstrInfo::isAssociativeAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a89fae3db628b477b713990d7a58732ea">isCombineInstrCandidateFP</a>, <a href="#a2626405eab33f6bae29077772fd63115">isDereferenceableInvariantLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#acc7375926290b7d52cce5ef2c03505f7">llvm::GIMatchTableExecutor::isObviouslySafeToFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a6d530d8d8d88a30d5fbf877f62f2ef30">isReachable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ace9f804c4f1407df72588bb00db16deb">llvm::TargetInstrInfo::isReassociationCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a2142c4566b7d15a35687f955d946a277">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::isSafetoMove</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a7bc46cb4bc77e9715066c204bd98e309">llvm::ReachingDefAnalysis::isSafeToMoveBackwards</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a09e2271431de53cc4cc5057148c18c93">llvm::ReachingDefAnalysis::isSafeToMoveForwards</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aeddbadaf9b53e5eee3dade2e9cd3512d">llvm::SIInstrInfo::isSafeToSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a22895e7a8fa9fc2f5a3306dd7aebbb33">jumpTableFollowsTB</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae2bd5329e5726d560529de68df90503c">llvm::CombinerHelper::matchFreezeOfSingleMaybePoisonOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afc26610b4c561e17a9ceb497233f34cc">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::modifyCmp</a>, <a href="#afc00f43b2ea96bd57a1d9ceb316dccb7">moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/hexagonconstextenders/#acd5e632a52045addda819968f7c4dc8f">anonymous{HexagonConstExtenders.cpp}::HexagonConstExtenders::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="#a471e524f23e926d8d76bcdaa6355d7eb">removeFromBundle</a>, <a href="#a1bc2f14c5e0de3c7ba77ed8d892a4c5a">removeFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#aed1c1aa1329f36eef4940283a1d30859">rescheduleCanonically</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#a7e75a4f6568424bf0940a7c509a6d18c">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>, <a href="#a9117508fb00fda14207e7f968389544c">setDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpumacrofusion-cpp-/#af5da450a1411e5b2e09527cb36568ff1">anonymous{AMDGPUMacroFusion.cpp}::shouldScheduleAdjacent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#a9d9c7bebc5b5d451511265937418ed6a">splitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3dc1ad6a578f69fed203a6022699080f">updateGetPCBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adc3ecee5ecd3f86b45e6779653ca10da">validateFunCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a1894915deb9e2c5abb856c02fe1513ff">validThroughout</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a>.</p>

</div>
</div>

### getParent() {#a2ec2ff43deaac49822bf15f2bac50bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineInstr::getParent ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### getPCSections() {#a7545019dcaee79c0d03335e6648c8bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::MachineInstr::getPCSections ()</td>
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

<p>Helper to extract PCSections metadata target sections.</p>

<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

### getPostInstrSymbol() {#add92393d0dae36ec6d41435e11d09884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MachineInstr::getPostInstrSymbol ()</td>
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

<p>Helper to extract a post-instruction symbol if one has been added.</p>

<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="#a7ffc14f594434308433335d6b62ded60">isNotDuplicable</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

### getPreInstrSymbol() {#ac7561e84ab87828a4c700c2e05ca8302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MachineInstr::getPreInstrSymbol ()</td>
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

<p>Helper to extract a pre-instruction symbol if one has been added.</p>

<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="#a7ffc14f594434308433335d6b62ded60">isNotDuplicable</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#a5981137a17cad3d9b2276ad63e15ee40">setMemRefs</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a> and <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a>.</p>

</div>
</div>

### getRegClassConstraint() {#af551bfe7ee8756cbe50de3bb97478723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * MachineInstr::getRegClassConstraint (unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the static register class constraint for operand OpIdx.</p>


<p>For normal instructions, this is derived from the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>. For inline assembly it is derived from the flag words.</p>


<p>Returns NULL if the static register class constraint cannot be determined.</p>


<p>Declaration at line 1625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a>, <a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">getDesc</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="#a391694f8040173dc0670bd273b170502">isRegTiedToDefOperand</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a88f8cb24fba67649c1f32531d0f6ab90">getRegClassConstraintEffect</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>.</p>

</div>
</div>

### getRegClassConstraintEffect() {#a88f8cb24fba67649c1f32531d0f6ab90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * MachineInstr::getRegClassConstraintEffect (unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * CurRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Applies the constraints (def/use) implied by the <span class="doxyComputerOutput">OpIdx</span> operand to the given <span class="doxyComputerOutput">CurRC</span>.</p>


<p>Returns the register class that satisfies both <span class="doxyComputerOutput">CurRC</span> and the constraints set by <span class="doxyComputerOutput">OpIdx</span> MI. Returns NULL if such a register class does not exist.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>CurRC must not be NULL.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The operand at <span class="doxyComputerOutput">OpIdx</span> must be a register.</p></dd>
</dl>


<p>Declaration at line 1656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getRegClassConstraintEffectForVReg() {#a3b3fa67a3a5da00dd6bc096cfbacd3a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * MachineInstr::getRegClassConstraintEffectForVReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * CurRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool ExploreBundle=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Applies the constraints (def/use) implied by this MI on <span class="doxyComputerOutput">Reg</span> to the given <span class="doxyComputerOutput">CurRC</span>.</p>


<p>If <span class="doxyComputerOutput">ExploreBundle</span> is set and MI is part of a bundle, all the instructions inside the bundle will be taken into account. In other words, this method accumulates all the constraints of the operand of this MI and the related bundle if MI is a bundle or inside a bundle.</p>


<p>Returns the register class that satisfies both <span class="doxyComputerOutput">CurRC</span> and the constraints set by MI. Returns NULL if such a register class does not exist.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>CurRC must not be NULL.</p></dd>
</dl>


<p>Declaration at line 1641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase/#a74c921d2258b6ce681a00ff5603ea43b">llvm::MIBundleOperandIteratorBase&lt; ValueT &gt;::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getRestoreSize() {#a54d1bd4ee7e40a15f8d22acca228dbc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocationSize &gt; MachineInstr::getRestoreSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a valid size if the instruction is a restore instruction.</p>

<p>Declaration at line 1828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a91b0115deec3489d7e082a4a13f022ff">llvm::MachineFrameInfo::isSpillSlotObjectIndex</a>, <a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getSpillSize() {#acf7a2f3baa7050ba9f95be0c1b71339f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocationSize &gt; MachineInstr::getSpillSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a valid size if the instruction is a spill instruction.</p>

<p>Declaration at line 1821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a91b0115deec3489d7e082a4a13f022ff">llvm::MachineFrameInfo::isSpillSlotObjectIndex</a>, <a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### hasDebugOperandForReg() {#a067c1c89704407541cbed8d65ac8dd66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasDebugOperandForReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Returns whether this debug value has at least one debug operand with the register <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>.</p>

</div>
</div>

### hasDelaySlot() {#a996207483728c6ed75938076623eb642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasDelaySlot (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Returns true if the specified instruction has a delay slot which must be filled by the code generator.</p>

<p>Definition at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a35dba8ebfddf32172dee2f54483c044a">llvm::MCID::DelaySlot</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>.</p>

</div>
</div>

### hasExtraDefRegAllocReq() {#a11a0c117b9aedd8ed85cd4a747ebb77c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasExtraDefRegAllocReq (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Returns true if this instruction def operands have special register allocation requirements that are not captured by the operand register classes.</p>


<p>e.g. ARM::LDRD's two def registers must be an even / odd pair, ARM::LDM registers have to be in ascending order. Post-register allocation passes should not attempt to change allocations for definitions of instructions with this flag.</p>


<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a136b35119a9335091735d1faf665281d">llvm::MCID::ExtraDefRegAllocReq</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>

</div>
</div>

### hasExtraSrcRegAllocReq() {#a77fb7702a3aa266e97eaf2ee2b19542f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasExtraSrcRegAllocReq (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Returns true if this instruction source operands have special register allocation requirements that are not captured by the operand register classes.</p>


<p>e.g. ARM::STRD's two source registers must be an even / odd pair, ARM::STM registers have to be in ascending order. Post-register allocation passes should not attempt to change allocations for sources of instructions with this flag.</p>


<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a986397153989297cba4e0cf19b75412a">llvm::MCID::ExtraSrcRegAllocReq</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>

</div>
</div>

### hasImplicitDef() {#a5879bc3bd2b8f21ba2d83a1f97a020d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasImplicitDef ()</td>
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

<p>Returns true if the instruction has implicit definition.</p>

<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ad0666b4ee4d5d2ade97f5f1e63865bab">implicit_operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>.</p>

</div>
</div>

### hasOneMemOperand() {#a999795324f5e7c578a97992d780080f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasOneMemOperand ()</td>
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

<p>Return true if this instruction has exactly one <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>.</p>

<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a>.</p>

</div>
</div>

### hasOptionalDef() {#aca12cb3163511b8cfa235a411d789d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasOptionalDef (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Set if this instruction has an optional definition, e.g.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> instructions which can set condition code if 's' bit is set.</p>


<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a330ed49df68eb049e1a7f9f331a07d08">llvm::MCID::HasOptionalDef</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### hasOrderedMemoryRef() {#aabc3917d917c6247778c88107945d13b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::hasOrderedMemoryRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction may have an ordered or volatile memory reference, or if the information describing the memory reference is not available.</p>


<p>hasOrderedMemoryRef - Return true if this instruction may have an ordered or volatile memory reference, or if the information describing the memory reference is not available.</p>


<p>Return false if it is known to have no ordered or volatile memory references.</p>


<p>Return false if it is known to have no ordered memory references.</p>


<p>Declaration at line 1787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1533 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a>, <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a55d6f8587efdb9efb8cb374f11fe4408">llvm::MachineMemOperand::isUnordered</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a>, <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>, <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a> and <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a30157a5020934199c281913d8d077f55">areCandidatesToMergeOrPair</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af724c54b41bc0a366bf3197f2855ce83">llvm::SIInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a> and <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### hasPostISelHook() {#a6808b4dcf3486acfdccbcefe27d9cb1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasPostISelHook (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction requires <em>adjustment</em> after instruction selection by calling a target hook.</p>


<p>For example, this can be used to fill in <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> 's' optional operand depending on whether the conditional flag register is used.</p>


<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a4dd7557d1d8cb30db26e0e28228c1cc7">llvm::MCID::HasPostISelHook</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>

</div>
</div>

### hasProperty() {#a257b68a68cb55f34cb704eb776afda1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::hasProperty (unsigned MCFlag, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if the instruction (or in the case of a bundle, the instructions inside the bundle) has the specified property.</p>


<p>The first argument is the property being queried. The second argument indicates whether the query should look inside instruction bundles.</p>


<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a75a5f7e3b3d4ec79610b4e556d2f35ce">getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a07cd91a67e9972e665c43a85c5b53b9d">llvm::MCInstrDesc::getFlags</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>, <a href="#afd00129f7ee0f594aad95a71abe9eddc">isBundled</a> and <a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">isBundledWithPred</a>.</p>


<p>Referenced by <a href="#af1b9443e375680a7b849d56ab42e19d6">canFoldAsLoad</a>, <a href="#a996207483728c6ed75938076623eb642">hasDelaySlot</a>, <a href="#a11a0c117b9aedd8ed85cd4a747ebb77c">hasExtraDefRegAllocReq</a>, <a href="#a77fb7702a3aa266e97eaf2ee2b19542f">hasExtraSrcRegAllocReq</a>, <a href="#aca12cb3163511b8cfa235a411d789d46">hasOptionalDef</a>, <a href="#a6808b4dcf3486acfdccbcefe27d9cb1d">hasPostISelHook</a>, <a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a>, <a href="#af782269e076a1a0e8911977433a02559">isAsCheapAsAMove</a>, <a href="#a2dbc79cfed570a9127d2853385162bdf">isBarrier</a>, <a href="#ac974851e3567cb3469a9aa1f27cc3063">isBitcast</a>, <a href="#a5891cdb51072f67e65f7ebd9be1205e7">isBranch</a>, <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>, <a href="#a7961501e56424e3a7e21d34d6e109461">isCommutable</a>, <a href="#a586262a958ca1593548855334ba99a12">isCompare</a>, <a href="#aaf9df5fbb2543faa0659f9b31f907df9">isConvergent</a>, <a href="#aa48b10169448732b2c0b13b8e7a256bf">isConvertibleTo3Addr</a>, <a href="#abefa2936f2beea06e735ee3887f5b6c4">isEHScopeReturn</a>, <a href="#a8dc9150d35e4fe96ae38928498f2b5dc">isExtractSubregLike</a>, <a href="#a19ce3659ba05d62794e306f6d070a850">isIndirectBranch</a>, <a href="#ad24ef6c881a03e82d4644dbaadafff79">isInsertSubregLike</a>, <a href="#aeffeb27bd92437aa2fd7b7567b01d078">isMetaInstruction</a>, <a href="#abec39b9fa59dac3c090092213bfc61c6">isMoveImmediate</a>, <a href="#a9a1c2054afa973564e0c2dd7fc5d2382">isMoveReg</a>, <a href="#a7ffc14f594434308433335d6b62ded60">isNotDuplicable</a>, <a href="#a2b224b59ee2bd22bdfb5fbbd74c4f773">isPredicable</a>, <a href="#abed10acdf0b7b55818ce0179b3f57331">isPreISelOpcode</a>, <a href="#abf37b74e017f80f204221fe3143ab89f">isPseudo</a>, <a href="#af5346eae1e87fbd0af3b5080fb9c4f78">isRegSequenceLike</a>, <a href="#afd72682fb9a02aab87877d61a66339a8">isRematerializable</a>, <a href="#a04af1d639a21e7ef4357facd283b42c4">isReturn</a>, <a href="#a30e4fdd20c6b04f83aef00924bc65e15">isSelect</a>, <a href="#a0e85c20fe804527f12c86db38ec947ea">isTerminator</a>, <a href="#af33de0b50f93d38f9fab12e8adf7ba62">isVariadic</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a>, <a href="#a00966a294fe7a54bf2f6a296e82fc8e1">mayRaiseFPException</a>, <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a> and <a href="#a320180749c883b427d229d1a2f3fefc3">usesCustomInsertionHook</a>.</p>

</div>
</div>

### hasRegisterImplicitUseOperand() {#ad890cb0ba6262569913be1269acbf590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::hasRegisterImplicitUseOperand (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> has an implicit-use operand of exactly the given register (not considering sub/super-registers).</p>

<p>Declaration at line 1553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ad0666b4ee4d5d2ade97f5f1e63865bab">implicit_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>.</p>

</div>
</div>

### hasUnmodeledSideEffects() {#a8c161f5f015730ac6853c802c3693a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::hasUnmodeledSideEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has side effects that are not modeled by mayLoad / mayStore, etc.</p>


<p>For all instructions, the property is encoded in <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a27d4264231f86aafeaf8fb38e53342ee">MCInstrDesc::Flags</a> (see <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a927b12dc654f2d95fbaf6a2d2ef67e68">MCInstrDesc::hasUnmodeledSideEffects()</a>. The only exception is INLINEASM instruction, in which case the side effect property is encoded in one of its operands (see InlineAsm::Extra_HasSideEffect).</p>


<p>Declaration at line 1809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a68a61079919e61d3af1002124c2f1ff9">llvm::InlineAsm::Extra_HasSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023af8bff71a05bf850313aede4b0f0af856">llvm::MCID::UnmodeledSideEffects</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af724c54b41bc0a366bf3197f2855ce83">llvm::SIInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a9de31756d24ba6d5dbe75c2d425720d4">hasSameValue</a>, <a href="#ab7c5324ccddfa1e364a70087e0434a0a">isLoadFoldBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a> and <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### implicit\_operands() {#ad0666b4ee4d5d2ade97f5f1e63865bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::implicit_operands ()</td>
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



<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a51f1fa9d5384d3b9c157a8216fef671d">explicit_operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>


<p>Referenced by <a href="#a39f79b8dd21fa75c7c273ebb9177a6a7">allImplicitDefsAreDead</a>, <a href="#a5879bc3bd2b8f21ba2d83a1f97a020d9">hasImplicitDef</a>, <a href="#ad890cb0ba6262569913be1269acbf590">hasRegisterImplicitUseOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>.</p>

</div>
</div>

### implicit\_operands() {#ac14071becb4727630d1f983391fd718d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::implicit_operands ()</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a51f1fa9d5384d3b9c157a8216fef671d">explicit_operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>

</div>
</div>

### insert() {#a904f484cd7cfe20a0e7673399c88cc3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::insert (<a href="#ab5b1fcfd0e1eddba786fefcdf28f1689">mop_iterator</a> InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts Ops BEFORE It. Can untie/retie tied operands.</p>

<p>Declaration at line 1895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2641 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a5574b8f058874009cab01e055a44338a">getOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>, <a href="#ac3b161ec90385105cb46a08b52139e60">removeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="#aa37e31e5df481d2f8a6f9f022886cf5e">tieOperands</a> and <a href="#a8e66e9ca7739874b25b9337940c26a0a">untieRegOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>.</p>

</div>
</div>

### isAnnotationLabel() {#a500ac55b1c16a71c77fc50c482df643a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isAnnotationLabel ()</td>
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



<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#ab3b944330612f60ce857aebffe954e57">isLabel</a>.</p>

</div>
</div>

### isAsCheapAsAMove() {#af782269e076a1a0e8911977433a02559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isAsCheapAsAMove (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed">AllInBundle</a>)</td>
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

<p>Returns true if this instruction has the same cost (or less) than a move instruction.</p>


<p>This is useful during certain types of optimizations (e.g., remat during two-address conversion or machine licm) where we would like to remat or hoist the instruction, but not if it costs more than moving the instruction into the appropriate register. Note, we are not marking copies from and to the same register class with this flag.</p>


<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed">AllInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a483f86b4470ddff0e7cf0e94253e07af">llvm::MCID::CheapAsAMove</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>

</div>
</div>

### isBarrier() {#a2dbc79cfed570a9127d2853385162bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBarrier (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Returns true if the specified instruction stops control flow from executing the instruction immediately following it.</p>


<p>Examples include unconditional branches and return instructions.</p>


<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a24b6e620b18edd37201fb9c0897835a8">llvm::MCID::Barrier</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8625c1e6c9bc82f2eaef39d3fff65a8">llvm::ScheduleDAGInstrs::addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a63671bab1a5a09de954177796404fe02">llvm::HexagonPacketizerList::hasControlDependence</a>, <a href="#a7d17cf681d7702d672b01153abf97be2">isConditionalBranch</a>, <a href="#a91c590e8191655a6739eb4df9c443896">isUnconditionalBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a905140abedaee343fc7ef33707052792">ProfitableToMerge</a>.</p>

</div>
</div>

### isBitcast() {#ac974851e3567cb3469a9aa1f27cc3063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBitcast (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction is a bitcast instruction.</p>

<p>Definition at line 1054 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a1f4c637ab112633eebd0f503b71be732">llvm::MCID::Bitcast</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>

</div>
</div>

### isBranch() {#a5891cdb51072f67e65f7ebd9be1205e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBranch (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Returns true if this is a conditional, unconditional, or indirect branch.</p>


<p>Predicates below can be used to discriminate between these cases, and the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0dfb0c744373d4b6112eb343a5b07fc7">TargetInstrInfo::analyzeBranch</a> method can be used to get more information.</p>


<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a359237c780f7c8e40645575826da8a3c">llvm::MCID::Branch</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a63671bab1a5a09de954177796404fe02">llvm::HexagonPacketizerList::hasControlDependence</a>, <a href="#a7d17cf681d7702d672b01153abf97be2">isConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="#a91c590e8191655a6739eb4df9c443896">isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#a9d9c7bebc5b5d451511265937418ed6a">splitBlock</a>.</p>

</div>
</div>

### isBundle() {#a3e2f795dfcb9269e1263453796f4b994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBundle ()</td>
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



<p>Definition at line 1445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac8e4876fffd2ceada8ef6428258d7236">llvm::HexagonInstrInfo::getBundleNoShuf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a> and <a href="#ad957f14a0cd72c10f5117fd1b9f30173">shouldUpdateAdditionalCallInfo</a>.</p>

</div>
</div>

### isBundled() {#afd00129f7ee0f594aad95a71abe9eddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBundled ()</td>
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

<p>Return true if this instruction part of a bundle.</p>


<p>This is true if either itself or its following instruction is marked "InsideBundle".</p>


<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">isBundledWithPred</a> and <a href="#ad07416ea31edd139a4ebe5b42a6f80b0">isBundledWithSucc</a>.</p>


<p>Referenced by <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3dc1ad6a578f69fed203a6022699080f">updateGetPCBundle</a>.</p>

</div>
</div>

### isBundledWithPred() {#a5cc5933defcffa4e4eca689dfeaf0a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBundledWithPred ()</td>
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

<p>Return true if this instruction is part of a bundle, and it is not the first instruction in the bundle.</p>

<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a> and <a href="#a33365204be9cb132de322e3713253b57">getFlag</a>.</p>


<p>Referenced by <a href="#a0aad617bc1bdef5bda2689f7a9fd06f6">bundleWithPred</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#afd00129f7ee0f594aad95a71abe9eddc">isBundled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a> and <a href="#a6780a3b4a7f87d5fc85574207fa02c60">unbundleFromPred</a>.</p>

</div>
</div>

### isBundledWithSucc() {#ad07416ea31edd139a4ebe5b42a6f80b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isBundledWithSucc ()</td>
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

<p>Return true if this instruction is part of a bundle, and it is not the last instruction in the bundle.</p>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">BundledSucc</a> and <a href="#a33365204be9cb132de322e3713253b57">getFlag</a>.</p>


<p>Referenced by <a href="#a21273844821e851afa28968bdd6ff10f">bundleWithSucc</a>, <a href="#afd00129f7ee0f594aad95a71abe9eddc">isBundled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a263c68370ee4203b80d388fd7b89ebb5">moveInstrOut</a> and <a href="#ade1d83105d6c2d3de29fca286f9d1b5a">unbundleFromSucc</a>.</p>

</div>
</div>

### isCall() {#a30e7d619f3195fd890116da8b3ed6bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isCall (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a463baf545246fea9718664d933ffe66f">llvm::MCID::Call</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8625c1e6c9bc82f2eaef39d3fff65a8">llvm::ScheduleDAGInstrs::addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a99791c9647b053fc872d35a3f0faafd7">llvm::ARMBaseInstrInfo::getOutliningCandidateInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a63671bab1a5a09de954177796404fe02">llvm::HexagonPacketizerList::hasControlDependence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#af4d1857aa86e6720b373f08a74982c93">llvm::HexagonPacketizerList::hasDeadDependence</a>, <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#afe0ff327925132355807b97771a7a4f5">llvm::HexagonPacketizerList::hasRegMaskDependence</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aea53e647298055af644a50c3a29e1411">llvm::MIRParserImpl::initializeCallSiteInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a8e190b21eafd467bfcb3cad647c2b3d3">interpretNextInstr</a>, <a href="#a806028855ad5c3431de7958e031e5ee1">isCandidateForAdditionalCallInfo</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="#ab7c5324ccddfa1e364a70087e0434a0a">isLoadFoldBarrier</a>, <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9d33681dd1899a420e4b30bf11f4b58e">llvm::TargetInstrInfo::isTailCall</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a9d55670b674a7d3bc9f2df1668d63be8">llvm::MIRParserImpl::parseCalledGlobals</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### isCandidateForAdditionalCallInfo() {#a806028855ad5c3431de7958e031e5ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isCandidateForAdditionalCallInfo (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is a call instruction that may have an additional information associated with it.</p>

<p>Declaration at line 964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a> and <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abc52118fc8160efd2667defd485e4a8e">llvm::MachineFunction::addCallSiteInfo</a> and <a href="#ad957f14a0cd72c10f5117fd1b9f30173">shouldUpdateAdditionalCallInfo</a>.</p>

</div>
</div>

### isCFIInstruction() {#a75489f444c9e3bdc12cb985c54d84a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isCFIInstruction ()</td>
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



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a8d5210bd68a86582390a6fbf1f57e319">llvm::TargetInstrInfo::duplicate</a>, <a href="#a0caab77831c0ee52b93185bcf64d180a">isPosition</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### isCommutable() {#a7961501e56424e3a7e21d34d6e109461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isCommutable (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this may be a 2- or 3-address instruction (of the form "X = op Y, Z, ..."), which produces the same result if Y and Z are exchanged.</p>


<p>If this flag is set, then the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa41720cc33b0511709c92abcb164a59d">TargetInstrInfo::commuteInstruction</a> method may be used to hack on the instruction.</p>


<p>Note that this flag may be set on instructions that are only commutable sometimes. In these cases, the call to commuteInstruction will fail. Also note that some instructions require non-trivial modification to commute them.</p>


<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a3ef69fec39e2c626336993c9774dc406">llvm::MCID::Commutable</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>

</div>
</div>

### isCompare() {#a586262a958ca1593548855334ba99a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isCompare (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction is a comparison.</p>

<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a1328ed43be8173506f59f88c9bfd8b8c">llvm::MCID::Compare</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>.</p>

</div>
</div>

### isComputedGoto() {#afe223b320036ba5a1ed344b1d44b0045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isComputedGoto (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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



<p>Definition at line 1005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a> and <a href="#a19ce3659ba05d62794e306f6d070a850">isIndirectBranch</a>.</p>

</div>
</div>

### isConditionalBranch() {#a7d17cf681d7702d672b01153abf97be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isConditionalBranch (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this is a branch which may fall through to the next instruction or may transfer control flow to some other block.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0dfb0c744373d4b6112eb343a5b07fc7">TargetInstrInfo::analyzeBranch</a> method can be used to get more information about this branch.</p>


<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a2dbc79cfed570a9127d2853385162bdf">isBarrier</a>, <a href="#a5891cdb51072f67e65f7ebd9be1205e7">isBranch</a> and <a href="#a19ce3659ba05d62794e306f6d070a850">isIndirectBranch</a>.</p>

</div>
</div>

### isConstantValuePHI() {#a37fa340555fb189bce42efadf42c5253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineInstr::isConstantValuePHI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the specified instruction is a PHI that always merges together the same virtual register, return the register, otherwise return <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register()</a>.</p>

<p>Declaration at line 1800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1591 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="#ad43bf1af480830a4d6604e969e3f38e9">isPHI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>.</p>

</div>
</div>

### isConvergent() {#aaf9df5fbb2543faa0659f9b31f907df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isConvergent (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this instruction is convergent.</p>


<p>Convergent instructions can not be made control-dependent on any additional values.</p>


<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a63a45e5b4f6037c05b07b9dc2c7ded46">llvm::MCID::Convergent</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a9921f5d5868939f49675e7fe34d1be70">llvm::InlineAsm::Extra_IsConvergent</a>, <a href="#a33365204be9cb132de322e3713253b57">getFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a> and <a href="#aafacf84de1cb994a92dc045f4aa1d518a09808ae32b91764194984d6892e40a2e">NoConvergent</a>.</p>

</div>
</div>

### isConvertibleTo3Addr() {#aa48b10169448732b2c0b13b8e7a256bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isConvertibleTo3Addr (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this is a 2-address instruction which can be changed into a 3-address instruction if needed.</p>


<p>Doing this transformation can be profitable in the register allocator, because it means that the instruction can use a 2-address form if possible, but degrade into a less efficient form if the source and dest register cannot be assigned to the same register. For example, this allows the x86 backend to turn a "shl reg, 3" instruction into an LEA instruction, which is the same speed as the shift but has bigger code size.</p>


<p>If this returns true, then the target must implement the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ada0a8cb9a764d058a63b77d50e9c0787">TargetInstrInfo::convertToThreeAddress</a> method for this instruction, which is allowed to fail if the transformation isn't valid for this specific instruction (e.g. shl reg, 4 on x86).</p>


<p>Definition at line 1224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a4dc2f8bf7dec9f3153e6aed4db5cb010">llvm::MCID::ConvertibleTo3Addr</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>

</div>
</div>

### isCopy() {#a1912d4fbc40c61a12b1f770ad54dfd74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isCopy ()</td>
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



<p>Definition at line 1449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="#a1f3c8255141a4f5b7ed15fcf60118eb1">isCopyLike</a>, <a href="#a6ee45760c97bf2dda6bee91508e6946e">isFullCopy</a>, <a href="#add5255eb40b106f13738476389bfa5a6">isIdentityCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a553d8629e18f8acb82dbadd0a160b877">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldRegSequence</a>.</p>

</div>
</div>

### isCopyLike() {#a1f3c8255141a4f5b7ed15fcf60118eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isCopyLike ()</td>
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

<p>Return true if the instruction behaves like a copy.</p>


<p>This does not include native copy instructions.</p>


<p>Definition at line 1465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a1912d4fbc40c61a12b1f770ad54dfd74">isCopy</a> and <a href="#a5822e16afda1fcf154cfb4179bacef3c">isSubregToReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>.</p>

</div>
</div>

### isDead() {#abb834744243c11cb677261382ac15bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> * LivePhysRegs=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether an MI is dead.</p>


<p>If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a></span> is provided, it is assumed to be at the position of MI and will be used to check the Liveness of physical register defs. If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a></span> is not provided, this will pessimistically assume any PhysReg def is live. For trivially dead instructions (i.e. those without hard to model effects / wouldBeTriviallyDead), this checks deadness by analyzing defs of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. If the instruction wouldBeTriviallyDead, and all the defs either have dead flags or have no uses, then the instruction is said to be dead.</p>


<p>Declaration at line 1766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ade4229c653b0cbcaca057e8af5002783">all_defs</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a5c249924553aa84c5927b2335c490583">llvm::LivePhysRegs::available</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="#a9f137387193043b6e4f37112d60f748d">isLifetimeMarker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a>.</p>


<p>Referenced by <a href="#afc1df0cb1a8c3103a4266def94c3a670">findRegisterDefOperand</a>, <a href="#aedaafad0e3bea3243199613910e2a7ce">findRegisterDefOperand</a> and <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>.</p>

</div>
</div>

### isDebugEntryValue() {#ae45a9559b6fd1578fb4d12f341cbed57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isDebugEntryValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A DBG_VALUE is an entry value iff its debug expression contains the DW_OP_LLVM_entry_value operation.</p>

<p>Declaration at line 1397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ab367ba2f45afaba6e941bd54c9c95a9f">getDebugExpression</a>, <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a>.</p>

</div>
</div>

### isDebugInstr() {#a42020afbcac5113c831c00294a0ac37f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugInstr ()</td>
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



<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a2502a65c42b09e02d163611edb263c84">isDebugLabel</a>, <a href="#a5d26e3ed3815037e0cc1b25a85c3a0e5">isDebugPHI</a>, <a href="#a4f5ab028b0c4242fd4409a3e50028339">isDebugRef</a> and <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a>.</p>


<p>Referenced by <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aa429e211fd041cb42d26e49dd5d95d75">llvm::SlotIndexes::getInstructionIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#af08090d2b358f57cbf6b3448a5ff2676">getMatchedEntries</a>, <a href="#a6b77ab21dcde46feb97e401cfb444570">isDebugOrPseudoInstr</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a> and <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### isDebugLabel() {#a2502a65c42b09e02d163611edb263c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugLabel ()</td>
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



<p>Definition at line 1374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a8de5351053b099124a2e2ea477ed54c9">getDebugLabel</a>, <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### isDebugOffsetImm() {#a252a85dbac85d89e26fae5f8e3b87eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugOffsetImm ()</td>
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



<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#acdbcc97c288440883cc78c74fed7066e">getDebugOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>


<p>Referenced by <a href="#ae4c4f9c9cf73f1c869a1c0eae73c150f">isIndirectDebugValue</a>.</p>

</div>
</div>

### isDebugOperand() {#ad2a225209000f521430877a269f61083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Op)</td>
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



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1d927e3bff8edf86442c52cc36a35cc8">llvm::adl_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4733843958c18c54ab61f2f972fa9a5f">llvm::adl_end</a> and <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a>.</p>


<p>Referenced by <a href="#acd30a83560c3674627e36af9175e9e1f">getDebugOperandIndex</a>.</p>

</div>
</div>

### isDebugOrPseudoInstr() {#a6b77ab21dcde46feb97e401cfb444570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugOrPseudoInstr ()</td>
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



<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a> and <a href="#ad82bec8563e9409362aaedd5346a3f17">isPseudoProbe</a>.</p>

</div>
</div>

### isDebugPHI() {#a5d26e3ed3815037e0cc1b25a85c3a0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugPHI ()</td>
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



<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a>.</p>

</div>
</div>

### isDebugRef() {#a4f5ab028b0c4242fd4409a3e50028339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugRef ()</td>
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



<p>Definition at line 1375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### isDebugValue() {#accb3520c6008297678829eed493b6c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugValue ()</td>
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



<p>Definition at line 1371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a071ce84bf9c71b9b7d6ffb30639ce602">isDebugValueList</a> and <a href="#ab46d35ae60812722cce0b701822ed04f">isNonListDebugValue</a>.</p>


<p>Referenced by <a href="#ae45a9559b6fd1578fb4d12f341cbed57">isDebugEntryValue</a>, <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a>, <a href="#adb7a3826a25ef43294d3434da71811e9">isUndefDebugValue</a> and <a href="#a0cf83915bd66f2a610c72f3d028f8704">setDebugValueUndef</a>.</p>

</div>
</div>

### isDebugValueLike() {#a49d5b7c2ba853713426d06b67513cdcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugValueLike ()</td>
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



<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a4f5ab028b0c4242fd4409a3e50028339">isDebugRef</a> and <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a>.</p>


<p>Referenced by <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a>, <a href="#a7dc07273003a0c8e17c23f2d257ea6a9">debug_operands</a>, <a href="#a539133bbbe620ce232f698234544b990">getDebugExpressionOp</a>, <a href="#a3736f5c23004fc6d6b0d0dc773efe7e2">getDebugExpressionOp</a>, <a href="#ac916b8cc2bbad1b2fad0d16486ee7593">getDebugVariableOp</a>, <a href="#abfcdb704dc6511a2c0b93fe4e5987182">getDebugVariableOp</a>, <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### isDebugValueList() {#a071ce84bf9c71b9b7d6ffb30639ce602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isDebugValueList ()</td>
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



<p>Definition at line 1368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a> and <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### isDereferenceableInvariantLoad() {#a2626405eab33f6bae29077772fd63115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isDereferenceableInvariantLoad ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this load instruction never traps and points to a memory location whose value doesn't change during the execution of this function.</p>


<p>isDereferenceableInvariantLoad - Return true if this instruction will never trap and is loading from a location whose value is invariant across a run of this function.</p>


<p>Examples include loading a value from the constant pool or from the argument area of a function (if it does not change). If the instruction does multiple loads, this returns true only if all of the loads are dereferenceable and invariant.</p>


<p>Declaration at line 1796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a>, <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a> and <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a9de31756d24ba6d5dbe75c2d425720d4">hasSameValue</a>, <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0f3bc0c5478dd84e0831b5d78a274b47">llvm::CombinerHelper::matchEqualDefs</a>.</p>

</div>
</div>

### isEHLabel() {#ad803ef666d44b78308d571df8b445f63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isEHLabel ()</td>
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



<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#ab3b944330612f60ce857aebffe954e57">isLabel</a>.</p>

</div>
</div>

### isEHScopeReturn() {#abefa2936f2beea06e735ee3887f5b6c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isEHScopeReturn (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this is an instruction that marks the end of an EH scope, i.e., a catchpad or a cleanuppad instruction.</p>

<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a5e4ba738cf7144b3dfc5ff4947351349">llvm::MCID::EHScopeReturn</a> and <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf1c64c05c8afb975b979543f8f850df">llvm::MachineBasicBlock::isEHScopeReturnBlock</a>.</p>

</div>
</div>

### isEquivalentDbgInstr() {#a8d4914ca78a5bd34e64807479fc057cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isEquivalentDbgInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this instruction is a debug instruction that represents an identical debug value to <span class="doxyComputerOutput">Other</span>.</p>


<p>This function considers these debug instructions equivalent if they have identical variables, debug locations, and debug operands, and if the DIExpressions combined with the directness flags are equivalent.</p>


<p>Declaration at line 1309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ab367ba2f45afaba6e941bd54c9c95a9f">getDebugExpression</a>, <a href="#abb10ef030fba4ea901518a0c8dbef3e2">getDebugLoc</a>, <a href="#ace50f23b8d1566bccb42a36100a9b818">getDebugOperand</a>, <a href="#a9ce3843932b6ae1c23228017f11eef25">getDebugVariable</a>, <a href="#a4275c0f770726594387d7bfc85ea8d64">getNumDebugOperands</a>, <a href="#a49d5b7c2ba853713426d06b67513cdcd">isDebugValueLike</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a3e2210b0af48ac382a4986510d1406bc">llvm::DIExpression::isEqualExpression</a>, <a href="#aab9a96f10af025498520e00ff044bec1">isIdenticalTo</a>, <a href="#ae4c4f9c9cf73f1c869a1c0eae73c150f">isIndirectDebugValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### isExtractSubreg() {#ab41b2896b8454188401b6e11a972a2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isExtractSubreg ()</td>
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



<p>Definition at line 1457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a>.</p>

</div>
</div>

### isExtractSubregLike() {#a8dc9150d35e4fe96ae38928498f2b5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isExtractSubregLike (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction behaves the same way as the generic EXTRACT_SUBREG instructions.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, rX, rY VMOVRRD dZ is equivalent to two EXTRACT_SUBREG: rX = EXTRACT_SUBREG dZ, ssub_0 rY = EXTRACT_SUBREG dZ, ssub_1</p>


<p>Note that for the optimizers to be able to take advantage of this property, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1c44734f854fb7f620d16097f2af637">TargetInstrInfo::getExtractSubregLikeInputs</a> has to be override accordingly.</p>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ade54f56905df7c591ac1baf60adf8ed5">llvm::MCID::ExtractSubreg</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>.</p>

</div>
</div>

### isFakeUse() {#af2df666e80610d028fc34fc23a82dd27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isFakeUse ()</td>
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



<p>Definition at line 1461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a>.</p>

</div>
</div>

### isFullCopy() {#a6ee45760c97bf2dda6bee91508e6946e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isFullCopy ()</td>
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



<p>Definition at line 1453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a> and <a href="#a1912d4fbc40c61a12b1f770ad54dfd74">isCopy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#aff059e4f5e8216de3172acd39a6e0ff8">anonymous{PPCMIPeephole.cpp}::getSrcVReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a51ac6439b177bf76b27b1fd1a4f30ca3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCopy</a>.</p>

</div>
</div>

### isGCLabel() {#a85cc92e3de77dfa4c19718a43b02eb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isGCLabel ()</td>
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



<p>Definition at line 1339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#ab3b944330612f60ce857aebffe954e57">isLabel</a>.</p>

</div>
</div>

### isIdenticalTo() {#aab9a96f10af025498520e00ff044bec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isIdenticalTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Other, <a href="#ab7650f958c093f7c5faf8c69dbc8c462">MICheckType</a> Check=<a href="#ab7650f958c093f7c5faf8c69dbc8c462a35b423af55ddd5d9081754328aa7f9c3">CheckDefs</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction is identical to <span class="doxyComputerOutput">Other</span>.</p>


<p>Two instructions are identical if they have the same opcode and all their operands are identical (with respect to <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">MachineOperand::isIdenticalTo()</a>). Note that this means liveness related flags (dead, undef, kill) do not affect the notion of identical.</p>


<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab7650f958c093f7c5faf8c69dbc8c462ad84865ceeee6b326942a3ed2ad37f815">CheckKillDead</a>, <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#abb10ef030fba4ea901518a0c8dbef3e2">getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ab7650f958c093f7c5faf8c69dbc8c462a24c57e99cada0b167e5132984979bc83">IgnoreDefs</a>, <a href="#ab7650f958c093f7c5faf8c69dbc8c462a5f3288f908142ddad3dd5d8a95cfa364">IgnoreVRegDefs</a>, <a href="#a3e2f795dfcb9269e1263453796f4b994">isBundle</a>, <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ac66abaa28810e0bb35ab77012a3ea997">llvm::TargetInstrInfo::produceSameValue</a>.</p>

</div>
</div>

### isIdentityCopy() {#add5255eb40b106f13738476389bfa5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isIdentityCopy ()</td>
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

<p>Return true is the instruction is an identity copy.</p>

<p>Definition at line 1470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a> and <a href="#a1912d4fbc40c61a12b1f770ad54dfd74">isCopy</a>.</p>

</div>
</div>

### isImplicitDef() {#a120ccebe70e1b0ddf72fc776229d0025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isImplicitDef ()</td>
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



<p>Definition at line 1420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a87edaaaaa788f8bc30dfad90aecdb343">llvm::HexagonPacketizerList::canPromoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a776834e825e7fd9cd90c27f7ace1d9d2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::needToBeConvertedToVALU</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a03912582e43afd7dad833dee8201240d">shouldPreventUndefRegUpdateMemFold</a>.</p>

</div>
</div>

### isIndirectBranch() {#a19ce3659ba05d62794e306f6d070a850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isIndirectBranch (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, bool IncludeJumpTable=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Return true if this is an indirect branch, such as a branch through a register.</p>

<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ac3c34b10dadcdbcc85552097cf077393">llvm::MCID::IndirectBranch</a> and <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="#afe223b320036ba5a1ed344b1d44b0045">isComputedGoto</a>, <a href="#a7d17cf681d7702d672b01153abf97be2">isConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a0900b0dbbda9bcb799da111f6ecfec1b">llvm::HexagonInstrInfo::isHVXMemWithAIndirect</a>, <a href="#a91c590e8191655a6739eb4df9c443896">isUnconditionalBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a703ba58bd58d60cd76ad205dda1634eb">llvm::MachineBasicBlock::terminatorIsComputedGoto</a>.</p>

</div>
</div>

### isIndirectDebugValue() {#ae4c4f9c9cf73f1c869a1c0eae73c150f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isIndirectDebugValue ()</td>
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

<p>A DBG_VALUE is indirect iff the location operand is a register and the offset operand is an immediate.</p>

<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#ace50f23b8d1566bccb42a36100a9b818">getDebugOperand</a>, <a href="#a252a85dbac85d89e26fae5f8e3b87eff">isDebugOffsetImm</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>.</p>


<p>Referenced by <a href="#a8d4914ca78a5bd34e64807479fc057cf">isEquivalentDbgInstr</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>.</p>

</div>
</div>

### isInlineAsm() {#a4b743093219cfca13b1ec2cb58903fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isInlineAsm ()</td>
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



<p>Definition at line 1421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a>, <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a284b9287f16ce98d3063620d92f54700">llvm::HexagonPacketizerList::canPromoteToDotCur</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a87edaaaaa788f8bc30dfad90aecdb343">llvm::HexagonPacketizerList::canPromoteToDotNew</a>, <a href="#ad72245681f0ae02a2d4574d434bc813d">emitInlineAsmError</a>, <a href="#af3caca8b1c9e27890d57f5755dc142fe">findInlineAsmFlagIdx</a>, <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="#a8b94b1143638cb1b18d976bba0b0ec3a">getInlineAsmDialect</a>, <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>, <a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a>, <a href="#aaf9df5fbb2543faa0659f9b31f907df9">isConvergent</a>, <a href="#abb834744243c11cb677261382ac15bea">isDead</a>, <a href="#a6b98ba8c44d9287df1be03859570b589">isStackAligningInlineAsm</a>, <a href="#afe1802220ee7c164e882ade3d80f1845">mayFoldInlineAsmRegOp</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a>, <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a506d59d745bce4ecf472b2a3580219bd">llvm::MipsInstrInfo::SafeInFPUDelaySlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a64bfddcfc4db367cec978a34653a69f3">llvm::MipsInstrInfo::SafeInLoadDelaySlot</a> and <a href="#aa37e31e5df481d2f8a6f9f022886cf5e">tieOperands</a>.</p>

</div>
</div>

### isInsertSubreg() {#a9de0e8de0615ba9a3e4fa551e25ddcee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isInsertSubreg ()</td>
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



<p>Definition at line 1433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a> and <a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a>.</p>

</div>
</div>

### isInsertSubregLike() {#ad24ef6c881a03e82d4644dbaadafff79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isInsertSubregLike (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction behaves the same way as the generic INSERT_SUBREG instructions.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, dX = VSETLNi32 dY, rZ, Imm is equivalent to a INSERT_SUBREG: dX = INSERT_SUBREG dY, rZ, translateImmToSubIdx(Imm)</p>


<p>Note that for the optimizers to be able to take advantage of this property, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2b51d2dd19b3859797509c03d5f451f1">TargetInstrInfo::getInsertSubregLikeInputs</a> has to be override accordingly.</p>


<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ad36e4d09ad9fb9f039b446fa505149ad">llvm::MCID::InsertSubreg</a>.</p>

</div>
</div>

### isInsideBundle() {#aa97496994b12c49c3141d8f15bc871eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isInsideBundle ()</td>
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

<p>Return true if MI is in a bundle (but not the first MI in a bundle).</p>



### A bundle looks like this before it's finalized: {#autotoc_md10}



### | MI | {#autotoc_md11}



### | {#autotoc_md12}



### | MI \* | {#autotoc_md13}



### | {#autotoc_md14}



### | MI \* | {#autotoc_md15}


<p>In this case, the first MI starts a bundle but is not inside a bundle, the next 2 MIs are considered "inside" the bundle.</p>



### After a bundle is finalized, it looks like this: {#autotoc_md16}



### | Bundle | {#autotoc_md17}



### | {#autotoc_md18}



### | MI \* | {#autotoc_md19}



### | {#autotoc_md20}



### | MI \* | {#autotoc_md21}



### | {#autotoc_md22}



### | MI \* | {#autotoc_md23}


<p>The first instruction has the special opcode "BUNDLE". It's not "inside" a bundle, but the next three MIs are.</p>


<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a> and <a href="#a33365204be9cb132de322e3713253b57">getFlag</a>.</p>

</div>
</div>

### isJumpTableDebugInfo() {#a974b18e3dd15be812200ec75dc0d3137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isJumpTableDebugInfo ()</td>
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



<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### isKill() {#ae9723ca940711fa1a09c0d53efeef5fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isKill ()</td>
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



<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#ab692b90c6e0e9b450f407896cbbe4b02">findRegisterUseOperand</a>, <a href="#a934c36cbb52619d7d75dfc0766e2b946">findRegisterUseOperand</a> and <a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a>.</p>

</div>
</div>

### isLabel() {#ab3b944330612f60ce857aebffe954e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isLabel ()</td>
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

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> represents a label.</p>

<p>Definition at line 1350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a500ac55b1c16a71c77fc50c482df643a">isAnnotationLabel</a>, <a href="#ad803ef666d44b78308d571df8b445f63">isEHLabel</a> and <a href="#a85cc92e3de77dfa4c19718a43b02eb16">isGCLabel</a>.</p>


<p>Referenced by <a href="#a0caab77831c0ee52b93185bcf64d180a">isPosition</a>.</p>

</div>
</div>

### isLifetimeMarker() {#a9f137387193043b6e4f37112d60f748d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isLifetimeMarker ()</td>
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



<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#abb834744243c11cb677261382ac15bea">isDead</a> and <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a>.</p>

</div>
</div>

### isLoadFoldBarrier() {#ab7c5324ccddfa1e364a70087e0434a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isLoadFoldBarrier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it is illegal to fold a load across this instruction.</p>

<p>Declaration at line 1812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a>, <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>, <a href="#ad82bec8563e9409362aaedd5346a3f17">isPseudoProbe</a> and <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>.</p>

</div>
</div>

### isMetaInstruction() {#aeffeb27bd92437aa2fd7b7567b01d078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isMetaInstruction (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction doesn't produce any output in the form of executable instructions.</p>

<p>Definition at line 944 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ad6fc37a26e7cdfb78a406be0ecf2f521">llvm::MCID::Meta</a>.</p>


<p>Referenced by <a href="#acaeaa72d4f5f8423ebade5ac38060b42">isTransient</a>.</p>

</div>
</div>

### isMoveImmediate() {#abec39b9fa59dac3c090092213bfc61c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isMoveImmediate (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction is a move immediate (including conditional moves) instruction.</p>

<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023aaeaafb46babde1143b2fa296b164a5c4">llvm::MCID::MoveImm</a>.</p>

</div>
</div>

### isMoveReg() {#a9a1c2054afa973564e0c2dd7fc5d2382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isMoveReg (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction is a register move.</p>


<p>(including moving values from subreg to reg)</p>


<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a37d39f9011275aa3445928f6b0037246">llvm::MCID::MoveReg</a>.</p>

</div>
</div>

### isNonListDebugValue() {#ab46d35ae60812722cce0b701822ed04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isNonListDebugValue ()</td>
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



<p>Definition at line 1365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a>, <a href="#a7dc07273003a0c8e17c23f2d257ea6a9">debug_operands</a>, <a href="#a539133bbbe620ce232f698234544b990">getDebugExpressionOp</a>, <a href="#a3736f5c23004fc6d6b0d0dc773efe7e2">getDebugExpressionOp</a>, <a href="#a51da1bfa6bdaa6cd06be2a3b92ccae1a">getDebugOffset</a>, <a href="#acdbcc97c288440883cc78c74fed7066e">getDebugOffset</a>, <a href="#ac916b8cc2bbad1b2fad0d16486ee7593">getDebugVariableOp</a>, <a href="#abfcdb704dc6511a2c0b93fe4e5987182">getDebugVariableOp</a>, <a href="#a252a85dbac85d89e26fae5f8e3b87eff">isDebugOffsetImm</a>, <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1f42f634cff46c0380f80cc600c19f3b">llvm::updateDbgValueForSpill</a>.</p>

</div>
</div>

### isNotDuplicable() {#a7ffc14f594434308433335d6b62ded60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isNotDuplicable (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this instruction cannot be safely duplicated.</p>


<p>For example, if the instruction has a unique labels attached to it, duplicating it would cause multiple definition errors.</p>


<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a8c84f3a089d61a5e72ba0a166cf74e2c">llvm::MCID::NotDuplicable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a8d5210bd68a86582390a6fbf1f57e319">llvm::TargetInstrInfo::duplicate</a>.</p>

</div>
</div>

### isOperandSubregIdx() {#a894f447628559f53d2279c9f9fae0780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isOperandSubregIdx (unsigned OpIdx)</td>
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

<p>Return true if operand <span class="doxyComputerOutput">OpIdx</span> is a subregister index.</p>

<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#ab41b2896b8454188401b6e11a972a2d0">isExtractSubreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a9de0e8de0615ba9a3e4fa551e25ddcee">isInsertSubreg</a>, <a href="#a8d97d09150ddcbcf5039f938111358ee">isRegSequence</a> and <a href="#a5822e16afda1fcf154cfb4179bacef3c">isSubregToReg</a>.</p>


<p>Referenced by <a href="#a48e904486c2be7b98450bc2306c10648">print</a>.</p>

</div>
</div>

### isPHI() {#ad43bf1af480830a4d6604e969e3f38e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isPHI ()</td>
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



<p>Definition at line 1415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#afd833dc91598d5a3c3f327b47b98a4cf">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMoveToEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#acfd4efd1c9f1a0174bd6f3942238c51b">llvm::SMSchedule::computeStart</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#af30efc6374f891c0dd222ed8610919fd">llvm::PeelingModuloScheduleExpander::getPhiCanonicalReg</a>, <a href="#a37fa340555fb189bce42efadf42c5253">isConstantValuePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae6911f11b05121e2c0deb7e45a6de110">llvm::SMSchedule::isLoopCarried</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae2bd5329e5726d560529de68df90503c">llvm::CombinerHelper::matchFreezeOfSingleMaybePoisonOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#adc90ef1bf034dfb4446b910d3795d218">llvm::PeelingModuloScheduleExpander::peelPrologAndEpilogs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a02320b2fe86927bf0dc6486f7c7faffa">llvm::SMSchedule::reorderInstructions</a> and <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a>.</p>

</div>
</div>

### isPosition() {#a0caab77831c0ee52b93185bcf64d180a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isPosition ()</td>
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



<p>Definition at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a75489f444c9e3bdc12cb985c54d84a37">isCFIInstruction</a> and <a href="#ab3b944330612f60ce857aebffe954e57">isLabel</a>.</p>


<p>Referenced by <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### isPredicable() {#a2b224b59ee2bd22bdfb5fbbd74c4f773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isPredicable (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed">AllInBundle</a>)</td>
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

<p>Return true if this instruction has a predicate operand that controls execution.</p>


<p>It may be set to 'always', or may be set to other values. There are various methods in <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> that can be used to control and modify the predicate in this instruction.</p>


<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed">AllInBundle</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a9222c946b8b605c95952eedf035a7eff">llvm::MCID::Predicable</a>.</p>

</div>
</div>

### isPreISelOpcode() {#abed10acdf0b7b55818ce0179b3f57331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isPreISelOpcode (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this is an instruction that should go through the usual legalization steps.</p>

<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a99de85e8619d9f7237f6434e655aa8af">llvm::MCID::PreISelOpcode</a>.</p>

</div>
</div>

### isPseudo() {#abf37b74e017f80f204221fe3143ab89f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isPseudo (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this is a pseudo instruction that doesn't correspond to a real machine instruction.</p>

<p>Definition at line 938 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ab96d69e82db1bb1326a1d12b8a1e0076">llvm::MCID::Pseudo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a435084f5e140c85f72921239385f9edb">canRenameUntilSecondLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#adfd05fb40b63f3fde78a81e119ed89e3">llvm::ResourceManager::canReserveResources</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcemanager/#a66b0369aaa8c87a6969ec5b56700d0d8">llvm::ResourceManager::reserveResources</a> and <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#af64a330eb150020132eb5c092cb3f454">llvm::ConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### isPseudoProbe() {#ad82bec8563e9409362aaedd5346a3f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isPseudoProbe ()</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a6b77ab21dcde46feb97e401cfb444570">isDebugOrPseudoInstr</a> and <a href="#ab7c5324ccddfa1e364a70087e0434a0a">isLoadFoldBarrier</a>.</p>

</div>
</div>

### isRegSequence() {#a8d97d09150ddcbcf5039f938111358ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isRegSequence ()</td>
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



<p>Definition at line 1441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a> and <a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a>.</p>

</div>
</div>

### isRegSequenceLike() {#af5346eae1e87fbd0af3b5080fb9c4f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isRegSequenceLike (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction behaves the same way as the generic REG_SEQUENCE instructions.</p>


<p>E.g., on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, dX VMOVDRR rY, rZ is equivalent to dX = REG_SEQUENCE rY, ssub_0, rZ, ssub_1.</p>


<p>Note that for the optimizers to be able to take advantage of this property, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a52e026925b73de52f7a563693ebff007">TargetInstrInfo::getRegSequenceLikeInputs</a> has to be override accordingly.</p>


<p>Definition at line 1114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023aabce0250d60b95b97ff41ff41ba030d6">llvm::MCID::RegSequence</a>.</p>

</div>
</div>

### isRegTiedToDefOperand() {#a391694f8040173dc0670bd273b170502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isRegTiedToDefOperand (unsigned UseOpIdx, unsigned * DefOpIdx=nullptr)</td>
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

<p>Return true if the use operand of the specified index is tied to a def operand.</p>


<p>It also returns the def operand index by reference if DefOpIdx is not null.</p>


<p>Definition at line 1690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>.</p>


<p>Referenced by <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a> and <a href="#af551bfe7ee8756cbe50de3bb97478723">getRegClassConstraint</a>.</p>

</div>
</div>

### isRegTiedToUseOperand() {#a6df9a6b70a33aee123056cec0ed052c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isRegTiedToUseOperand (unsigned DefOpIdx, unsigned * UseOpIdx=nullptr)</td>
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

<p>Given the index of a register def operand, check if the register def is tied to a source operand, due to either two-address elimination or inline assembly constraints.</p>


<p>Returns the first tied use operand index by reference if UseOpIdx is not null.</p>


<p>Definition at line 1677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>.</p>

</div>
</div>

### isRematerializable() {#afd72682fb9a02aab87877d61a66339a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isRematerializable (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed">AllInBundle</a>)</td>
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

<p>Returns true if this instruction is a candidate for remat.</p>


<p>This flag is deprecated, please don't use it anymore. If this flag is set, the isReallyTriviallyReMaterializable() method is called to verify the instruction is really rematerializable.</p>


<p>Definition at line 1252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a65200f52a6bd67def2a40397a565caed">AllInBundle</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a8862ede68c58eb6c127dc1f9fba7c8ab">llvm::MCID::Rematerializable</a>.</p>

</div>
</div>

### isReturn() {#a04af1d639a21e7ef4357facd283b42c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isReturn (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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



<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a5416d9f1bd5f533efddadf17d713e469">llvm::MCID::Return</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a0c5b673184f4d81114afba8a699cdb7e">llvm::RISCVInstrInfo::getOutliningCandidateInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a82f5d244972c88ff03ee56d6c090ac70">llvm::MachineBasicBlock::isReturnBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9d33681dd1899a420e4b30bf11f4b58e">llvm::TargetInstrInfo::isTailCall</a>.</p>

</div>
</div>

### isSafeToMove() {#a3c3bece1d6d099a7b6bc4c22ea768e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isSafeToMove (bool &amp; SawStore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is safe to move this instruction.</p>


<p>isSafeToMove - Return true if it is safe to move this instruction.</p>


<p>If SawStore is set to true, it means that there is a store (or call) between the instruction's location and its intended destination.</p>


<p>Declaration at line 1751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="#a8c161f5f015730ac6853c802c3693a41">hasUnmodeledSideEffects</a>, <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>, <a href="#a42020afbcac5113c831c00294a0ac37f">isDebugInstr</a>, <a href="#a2626405eab33f6bae29077772fd63115">isDereferenceableInvariantLoad</a>, <a href="#a974b18e3dd15be812200ec75dc0d3137">isJumpTableDebugInfo</a>, <a href="#ad43bf1af480830a4d6604e969e3f38e9">isPHI</a>, <a href="#a0caab77831c0ee52b93185bcf64d180a">isPosition</a>, <a href="#a0e85c20fe804527f12c86db38ec947ea">isTerminator</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a>, <a href="#a00966a294fe7a54bf2f6a296e82fc8e1">mayRaiseFPException</a> and <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a> and <a href="#a5c1ff2ea28f57b7c7afb9a02b5adfff0">wouldBeTriviallyDead</a>.</p>

</div>
</div>

### isSelect() {#a30e4fdd20c6b04f83aef00924bc65e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isSelect (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction is a select instruction.</p>

<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a32dbd2c72a98eaee90e3ad5ef7b5af16">llvm::MCID::Select</a>.</p>

</div>
</div>

### isStackAligningInlineAsm() {#a6b98ba8c44d9287df1be03859570b589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::isStackAligningInlineAsm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ada6152484586a08fa711d4b0d44c87e5">llvm::InlineAsm::Extra_IsAlignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a>.</p>

</div>
</div>

### isSubregToReg() {#a5822e16afda1fcf154cfb4179bacef3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isSubregToReg ()</td>
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



<p>Definition at line 1437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>.</p>


<p>Referenced by <a href="#a1f3c8255141a4f5b7ed15fcf60118eb1">isCopyLike</a> and <a href="#a894f447628559f53d2279c9f9fae0780">isOperandSubregIdx</a>.</p>

</div>
</div>

### isTerminator() {#a0e85c20fe804527f12c86db38ec947ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isTerminator (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Returns true if this instruction part of the terminator for a basic block.</p>


<p>Typically this is things like return and branch instructions.</p>


<p>Various passes use this to insert code into the bottom of a basic block, but before control flow occurs.</p>


<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023af121d798d2c14b32e81d537a1f0cff8d">llvm::MCID::Terminator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a> and <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### isTransient() {#acaeaa72d4f5f8423ebade5ac38060b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isTransient ()</td>
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

<p>Return true if this is a transient instruction that is either very likely to be eliminated during register allocation (such as copy-like instructions), or if this instruction doesn't have an execution-time cost.</p>

<p>Definition at line 1478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a> and <a href="#aeffeb27bd92437aa2fd7b7567b01d078">isMetaInstruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#aee17a5350fad1c56abf6f425ef4f6e92">llvm::SchedDFSImpl::visitPreorder</a>.</p>

</div>
</div>

### isUnconditionalBranch() {#a91c590e8191655a6739eb4df9c443896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isUnconditionalBranch (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this is a branch which always transfers control flow to some other block.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0dfb0c744373d4b6112eb343a5b07fc7">TargetInstrInfo::analyzeBranch</a> method can be used to get more information about this branch.</p>


<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a2dbc79cfed570a9127d2853385162bdf">isBarrier</a>, <a href="#a5891cdb51072f67e65f7ebd9be1205e7">isBranch</a> and <a href="#a19ce3659ba05d62794e306f6d070a850">isIndirectBranch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#a561e8197481b2a01d7f75fd567c7801e">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3e3daf4218b791b2796b808627b7f864">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupConditionalBr</a>.</p>

</div>
</div>

### isUndefDebugValue() {#adb7a3826a25ef43294d3434da71811e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isUndefDebugValue ()</td>
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

<p>Return true if the instruction is a debug value which describes a part of a variable as unavailable.</p>

<p>Definition at line 1401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> and <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a>.</p>

</div>
</div>

### isVariadic() {#af33de0b50f93d38f9fab12e8adf7ba62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::isVariadic (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction can have a variable number of operands.</p>


<p>In this case, the variable operands will be after the normal operands but before the implicit definitions and uses (if any are present).</p>


<p>Definition at line 926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a06448010e7faa3713221a1b768380957">llvm::MCID::Variadic</a>.</p>


<p>Referenced by <a href="#a9dbc9a748353035febcc488160ba9956">getTypeToPrint</a>.</p>

</div>
</div>

### killsRegister() {#a81547ddac1cc7ddad9428925e49ab42b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::killsRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> kills the specified register.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> is non-null, then it also checks if there is a kill of a super-register.</p>


<p>Definition at line 1525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### mayAlias() {#a3da773a37ef4e3325379dd6718317b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::mayAlias (<a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> * AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Other, bool UseTBAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this instruction's memory access aliases the memory access of Other.</p>


<p>Assumes any physical registers used to compute addresses have the same value for both instructions. Returns false if neither instruction writes to memory.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/aa"&gt;AA&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Optional alias analysis, used to compare memory operands.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Other</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> to check aliasing against.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UseTBAA</td>
<td class="doxyParamItemDescription"><p>Whether to pass TBAA information to alias analysis.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="#a820e6d6b9b0a0cacce473925803ba569">getNumMemOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a30e7d619f3195fd890116da8b3ed6bab">isCall</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="#a17f5d15a7320dec2cfefb6617f711ab7">mayLoadOrStore</a>, <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>, <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>, <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a85e6100733f4ae2c0946eeab33a9086c">UseTBAA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aee33e06ea8865a2fb2bf229325c07194">llvm::ScheduleDAGInstrs::addChainDependency</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b4a3c0105d0c1835725eaa33867b526">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingStore</a>, <a href="#a55aec6d9959470668bae2aeb8a7c0768">mayAlias</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a55450149fa2fc8fb50d587023814ea69">mayAlias</a>.</p>

</div>
</div>

### mayAlias() {#a55aec6d9959470668bae2aeb8a7c0768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::mayAlias (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Other, bool UseTBAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a85e6100733f4ae2c0946eeab33a9086c">UseTBAA</a>.</p>

</div>
</div>

### mayFoldInlineAsmRegOp() {#afe1802220ee7c164e882ade3d80f1845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::mayFoldInlineAsmRegOp (unsigned OpId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the register operand can be folded with a load or store into a frame index.</p>


<p>Does so by checking the <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag">InlineAsm::Flag</a> immediate operand at OpId - 1.</p>


<p>Declaration at line 1428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2686 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### mayLoad() {#a682028ac4a06c9e3550fa8e6e1909fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::mayLoad (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this instruction could possibly read memory.</p>


<p>Instructions with this flag set are not necessarily simple load instructions, they may load a value and modify it, for example.</p>


<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370aa21b27c3cc4550dcd3ff599dbe76d0c3">llvm::InlineAsm::Extra_MayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a530d5e41c3cf67937c373da61c65acd4">llvm::MCID::MayLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a4d5807670c4c32383f66d0e1df8936e0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType</a>, <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="#a2626405eab33f6bae29077772fd63115">isDereferenceableInvariantLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>, <a href="#a17f5d15a7320dec2cfefb6617f711ab7">mayLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aa7aeeaeea47cbad621b11556e9b19839">llvm::HexagonHazardRecognizer::ShouldPreferAnother</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnmaxmemoryclauseschedstrategy/#a9eba23f1b8a103c8e88a2ca6227d97b3">llvm::GCNMaxMemoryClauseSchedStrategy::tryCandidate</a>.</p>

</div>
</div>

### mayLoadOrStore() {#a17f5d15a7320dec2cfefb6617f711ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::mayLoadOrStore (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this instruction could possibly read or modify memory.</p>

<p>Definition at line 1177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a682028ac4a06c9e3550fa8e6e1909fa9">mayLoad</a> and <a href="#ab96f3235c18e659758517d0532d606c9">mayStore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af724c54b41bc0a366bf3197f2855ce83">llvm::SIInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5f8ea6535c262fbc8a16177783020314">llvm::TargetInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9f95e557fb675ab6ef80f2fc4b8b3e01">llvm::AArch64InstrInfo::getMemOpBaseRegImmOfsOffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a512855a97cf9032c007ca232000a81ba">llvm::AArch64InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa04c64c287d0b42c8a1714011a943e3d">llvm::RISCVInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a9de31756d24ba6d5dbe75c2d425720d4">hasSameValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0f3bc0c5478dd84e0831b5d78a274b47">llvm::CombinerHelper::matchEqualDefs</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### mayRaiseFPException() {#a00966a294fe7a54bf2f6a296e82fc8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::mayRaiseFPException ()</td>
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

<p>Return true if this instruction could possibly raise a floating-point exception.</p>


<p>This is the case if the instruction is a floating-point instruction that can in principle raise an exception, as indicated by the <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a6d8ad5d1cd35c1093591f1eb9512d3e8">MCID::MayRaiseFPException</a> property, <em>and</em> at the same time, the instruction is used in a context where we expect floating-point exceptions are not disabled, as indicated by the NoFPExcept MI flag.</p>


<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a33365204be9cb132de322e3713253b57">getFlag</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a6d8ad5d1cd35c1093591f1eb9512d3e8">llvm::MCID::MayRaiseFPException</a> and <a href="#aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893">NoFPExcept</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a> and <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>

</div>
</div>

### mayStore() {#ab96f3235c18e659758517d0532d606c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::mayStore (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>)</td>
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

<p>Return true if this instruction could possibly modify memory.</p>


<p>Instructions with this flag set are not necessarily simple store instructions, they may store a modified value based on their operands, or may not actually modify anything, for example.</p>


<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab01e1dce8dabbbb3d14ed5f34c366008">llvm::InlineAsm::Extra_MayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023a50b76935e53196d5d0610736ed52386d">llvm::MCID::MayStore</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab049673bbc307f5502c8aba23224a605">llvm::InlineAsm::MIOp_ExtraInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4ab4c0bfcb70883e983a325153b5a44e">llvm::HexagonInstrInfo::canExecuteInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a4d5807670c4c32383f66d0e1df8936e0">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a7bd17a975574e883de8508974c9b6184">llvm::HexagonPacketizerList::hasDualStoreDependence</a>, <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="#ab7c5324ccddfa1e364a70087e0434a0a">isLoadFoldBarrier</a>, <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="#a17f5d15a7320dec2cfefb6617f711ab7">mayLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### memoperands() {#ab37075d621acbbfc96ef2662f2e29883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MachineMemOperand * &gt; llvm::MachineInstr::memoperands ()</td>
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

<p>Access to memory operands of the instruction.</p>


<p>If there are none, that does not imply anything about whether the function accesses memory. Instead, the caller must behave conservatively.</p>


<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a5a49db9f3f84ee0258f9db321f1c7f9f">llvm::VLIWPacketizerList::alias</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2432d0bb09d9fe3b6bb004d8dbf77a99">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>, <a href="#a820e6d6b9b0a0cacce473925803ba569">getNumMemOperands</a>, <a href="#a999795324f5e7c578a97992d780080f1">hasOneMemOperand</a>, <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="#a2626405eab33f6bae29077772fd63115">isDereferenceableInvariantLoad</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin</a>, <a href="#a4cd2e2c219c477019aa343c92dcf56cb">memoperands_empty</a>, <a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">memoperands_end</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a120fc86306882eb2bd3c27c9f4063fd6">llvm::ARMOverrideBypasses::memoryRAWHazard</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="#a1902a720147e652fa4a4857e069f4dd3">setCFIType</a>, <a href="#a9a10f5acfd3fb2690d6bc2c78c26be13">setHeapAllocMarker</a>, <a href="#af4e52d47d0f7fa13dd23fae4cfc4f85b">setMMRAMetadata</a>, <a href="#ae76989792a75b7735546e69711d22209">setPCSections</a>, <a href="#ac8ce95857a66b3706a84d1fd5072f0dd">setPostInstrSymbol</a>, <a href="#a2517e88d2d947effcdaeaeec39b2e2c0">setPreInstrSymbol</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>.</p>

</div>
</div>

### memoperands\_begin() {#aa5ff177bc1498508696aaf27235db3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmo_iterator llvm::MachineInstr::memoperands_begin ()</td>
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

<p>Access to memory operands of the instruction.</p>


<p>If <span class="doxyComputerOutput"><a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin()</a> == <a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">memoperands_end()</a></span>, that does not imply anything about whether the function accesses memory. Instead, the caller must behave conservatively.</p>


<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#afc4107c92fd8d37e8d0cb596f2a25d98">addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2432d0bb09d9fe3b6bb004d8dbf77a99">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a130e12a0a8b3fe8149fe7b5eecfa603e">llvm::GMemOperation::getMMO</a>, <a href="#a54d1bd4ee7e40a15f8d22acca228dbc3">getRestoreSize</a>, <a href="#acf7a2f3baa7050ba9f95be0c1b71339f">getSpillSize</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>.</p>

</div>
</div>

### memoperands\_empty() {#a4cd2e2c219c477019aa343c92dcf56cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::memoperands_empty ()</td>
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

<p>Return true if we don't have any memory operands which described the memory access done by this instruction.</p>


<p>If this is true, calling code must be conservative.</p>


<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a5a49db9f3f84ee0258f9db321f1c7f9f">llvm::VLIWPacketizerList::alias</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="#aabc3917d917c6247778c88107945d13b">hasOrderedMemoryRef</a>, <a href="#a2626405eab33f6bae29077772fd63115">isDereferenceableInvariantLoad</a>, <a href="#a3da773a37ef4e3325379dd6718317b74">mayAlias</a>, <a href="#a48e904486c2be7b98450bc2306c10648">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>.</p>

</div>
</div>

### memoperands\_end() {#a4e9ab7e4e59e6a558a5b17757c1f17e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmo_iterator llvm::MachineInstr::memoperands_end ()</td>
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

<p>Access to memory operands of the instruction.</p>


<p>If <span class="doxyComputerOutput"><a href="#aa5ff177bc1498508696aaf27235db3fc">memoperands_begin()</a> == <a href="#a4e9ab7e4e59e6a558a5b17757c1f17e9">memoperands_end()</a></span>, that does not imply anything about whether the function accesses memory. Instead, the caller must behave conservatively.</p>


<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Reference <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#afc4107c92fd8d37e8d0cb596f2a25d98">addMemOperand</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2432d0bb09d9fe3b6bb004d8dbf77a99">llvm::TargetInstrInfo::foldMemoryOperand</a>.</p>

</div>
</div>

### mergeFlagsWith() {#a36538e83424d5c406c294a6c365f9fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachineInstr::mergeFlagsWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the MIFlags which represent both MachineInstrs.</p>


<p>This should be used when merging two MachineInstrs into one. This routine does not modify the MIFlags of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>Declaration at line 1984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad73e18478cd951f76d35a88c4d43ef5a">getFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>.</p>

</div>
</div>

### modifiesRegister() {#a66e91c5407ade0326e5dbd87e986e648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::modifiesRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> modifies (fully define or partially define) the specified register.</p>


<p>NOTE: It's ignoring subreg indices on virtual registers.</p>


<p>Definition at line 1540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>.</p>

</div>
</div>

### moveBefore() {#afc00f43b2ea96bd57a1d9ceb316dccb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the instruction before <span class="doxyComputerOutput">MovePos</span>.</p>

<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>.</p>

</div>
</div>

### operands() {#a999b8f3e58e7ca479f26445bae791a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::operands ()</td>
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



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="#ade4229c653b0cbcaca057e8af5002783">all_defs</a>, <a href="#a9ed7df9f98920ad21ef28dc7e0e70f39">all_defs</a>, <a href="#af408efad64e3aa0eef6c3a37c7794a83">allDefsAreDead</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#aba393b0035b052e3477fc32a72643750">canUsePressureDiffs</a>, <a href="#ae26854c9925fc93880d644c0dcac8ba7">clearKillInfo</a>, <a href="#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">clearRegisterKills</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a85299a5742cf6712729343b973727ab7">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findLongFormInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#af4d1857aa86e6720b373f08a74982c93">llvm::HexagonPacketizerList::hasDeadDependence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#afe0ff327925132355807b97771a7a4f5">llvm::HexagonPacketizerList::hasRegMaskDependence</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ae0d37a7eb6fa39a78f3bcb706766bd73">llvm::rdf::DataFlowGraph::hasUntrackedRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aa2eaa868ed1dfcc89946d7b7fc4d2149">hasWriteToReadDep</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="#a19ce3659ba05d62794e306f6d070a850">isIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a2142c4566b7d15a35687f955d946a277">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::isSafetoMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>, <a href="#ac2afcfcff9187a2201549d75d4e16149">setPhysRegsDeadExcept</a> and <a href="#a9f59e1f6dd6677348ba082a10fc09061">substituteRegister</a>.</p>

</div>
</div>

### operands() {#ab2d2452d3e44037d5247fb125480634c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::operands ()</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>

</div>
</div>

### operands\_begin() {#a0037ac891190e1408b04a48156c3368c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mop_iterator llvm::MachineInstr::operands_begin ()</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a>, <a href="#a7dc07273003a0c8e17c23f2d257ea6a9">debug_operands</a>, <a href="#aa3b9fba7fd848bb37e43040b66f6c051">defs</a>, <a href="#a52be2a25e3a107f532b38ce311b0717b">defs</a>, <a href="#a51f1fa9d5384d3b9c157a8216fef671d">explicit_operands</a>, <a href="#a471354c2bb81524bd5924f7290104f55">explicit_operands</a>, <a href="#a0773fc3d8cd259c587ec29b5902de0f4">explicit_uses</a>, <a href="#a3a3e7027c93fbf5f29af591087170f41">explicit_uses</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="#a5574b8f058874009cab01e055a44338a">getOperandNo</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>, <a href="#ab2d2452d3e44037d5247fb125480634c">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#abe1c22281512c39286cbb9bca97ae7b8">llvm::R600SchedStrategy::schedNode</a>, <a href="#a3949f157e1034f6cb5d16ad708059aa3">uses</a> and <a href="#a15bc8fb07e719b5a47a7c9070c5e26af">uses</a>.</p>

</div>
</div>

### operands\_begin() {#a8fa16a8f17fdb13884cf0b164d2225ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_mop_iterator llvm::MachineInstr::operands_begin ()</td>
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



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### operands\_end() {#a6e6014fca5895fa5f9487ff7c79678b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mop_iterator llvm::MachineInstr::operands_end ()</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a>, <a href="#a7dc07273003a0c8e17c23f2d257ea6a9">debug_operands</a>, <a href="#ad0666b4ee4d5d2ade97f5f1e63865bab">implicit_operands</a>, <a href="#ac14071becb4727630d1f983391fd718d">implicit_operands</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>, <a href="#ab2d2452d3e44037d5247fb125480634c">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#abe1c22281512c39286cbb9bca97ae7b8">llvm::R600SchedStrategy::schedNode</a>, <a href="#a3949f157e1034f6cb5d16ad708059aa3">uses</a> and <a href="#a15bc8fb07e719b5a47a7c9070c5e26af">uses</a>.</p>

</div>
</div>

### operands\_end() {#a663a3293492f4dac5169d811991b521d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_mop_iterator llvm::MachineInstr::operands_end ()</td>
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



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### peekDebugInstrNum() {#a524f9c8ad90631347eeaa311ba919b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::peekDebugInstrNum ()</td>
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

<p>Examine the instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>May be zero if it hasn't been assigned a number yet.</p>


<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30233b5b4decf678ec7ed144ac1f729b">llvm::MachineFunction::substituteDebugValuesForInst</a>.</p>

</div>
</div>

### readsRegister() {#a2380c209ae5339835b5e6ea6d5c197ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::readsRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> reads the specified register.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> is non-null, then it also checks if there is a read of a super-register. This does not count partial redefines of virtual registers as reads: reg1024:6 = OP.</p>


<p>Definition at line 1505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a6f42d93281a5cbf5360f836c09166c06">findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#aed8bb289e710a4687f5dbdc1b0b35fd3">checkAndUpdateCCRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a551cf4f2a46a96b347d222acc8df059c">checkAndUpdateCPSRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ace4b26a3e7058a0e723088fdd9f95563">checkCCKill</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a5a00ff1e3eb19fe4001d742d93f8fade">llvm::TargetSchedModel::computeOutputLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a143e4c2358a1f5d46268f20f0fc52ba7">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthTailCallHardening</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af668609d5285820d674d655ab3990c91">llvm::HexagonInstrInfo::getCompoundOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aa2eaa868ed1dfcc89946d7b7fc4d2149">hasWriteToReadDep</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fixupsetcc-cpp-/x86fixupsetccpass/#a88ff40585130ceeb06ea67057cc33b5d">anonymous{X86FixupSetCC.cpp}::X86FixupSetCCPass::runOnMachineFunction</a>.</p>

</div>
</div>

### readsVirtualRegister() {#ac823eae276c8bfe6d8c819a3927b7333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::readsVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> reads the specified virtual register.</p>


<p>Take into account that a partial define is a read-modify-write operation.</p>


<p>Definition at line 1512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a374fc9d9064a93ef8a408f269d02389d">readsWritesVirtualRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### readsWritesVirtualRegister() {#a374fc9d9064a93ef8a408f269d02389d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; MachineInstr::readsWritesVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; * Ops=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pair of bools (reads, writes) indicating if this instruction reads or writes Reg.</p>


<p>readsWritesVirtualRegister - Return a pair of bools (reads, writes) indicating if this instruction reads or writes Reg.</p>


<p>This also considers partial defines. If Ops is not null, all operand indices for Reg are added.</p>


<p>This also considers partial defines.</p>


<p>Declaration at line 1519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>.</p>


<p>Referenced by <a href="#ac823eae276c8bfe6d8c819a3927b7333">readsVirtualRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a506d59d745bce4ecf472b2a3580219bd">llvm::MipsInstrInfo::SafeInFPUDelaySlot</a>.</p>

</div>
</div>

### registerDefIsDead() {#a8e705934ca4178520c75d7ed1218cfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::registerDefIsDead (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Returns true if the register is dead in this machine instruction.</p>


<p>If <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> is non-null, then it also checks if there is a dead def of a super-register.</p>


<p>Definition at line 1547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aeeed341d0f3c7220d070d766e3a0f584">findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp/#a24181d1b7cdfbb8fd9710139d861ca6c">transferDeadCC</a>.</p>

</div>
</div>

### removeFromBundle() {#a471e524f23e926d8d76bcdaa6355d7eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineInstr::removeFromBundle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this instruction from its basic block and return it without deleting it.</p>


<p>If the instruction is part of a bundle, the other instructions in the bundle remain bundled.</p>


<p>Declaration at line 1323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1590a6d5d0f6d95dda90f2cf8954f3fb">llvm::MachineBasicBlock::remove_instr</a>.</p>

</div>
</div>

### removeFromParent() {#a1bc2f14c5e0de3c7ba77ed8d892a4c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineInstr::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink 'this' from the containing basic block, and return it without deleting it.</p>


<p>This function can not be used on bundled instructions, use <a href="#a471e524f23e926d8d76bcdaa6355d7eb">removeFromBundle()</a> to remove individual instructions from a bundle.</p>


<p>Declaration at line 1316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6a77acab2477f9eaf0de232a1d94ff3d">llvm::MachineBasicBlock::remove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a> and <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>.</p>

</div>
</div>

### removeOperand() {#ac3b161ec90385105cb46a08b52139e60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::removeOperand (unsigned OpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase an operand from an instruction, leaving it with one fewer operand than it started with.</p>

<p>Declaration at line 1910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a432824f0975bb863478bf4ef3a5df258">getNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a1c81cc103e832c555a8b2df1b597c72a">moveOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a8e66e9ca7739874b25b9337940c26a0a">untieRegOperand</a>.</p>


<p>Referenced by <a href="#afda2c0f22be043ae42b0ec71b661f565">addRegisterDead</a>, <a href="#ac78902263d351fd8540aeb449d9cb53f">addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### setAsmPrinterFlag() {#a698b6937d98b7ee400dee8b7b3c8a4bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setAsmPrinterFlag (uint8_t Flag)</td>
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

<p>Set a flag for the <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#adfdb32bd422a7613ae83c10f2841abf7">spillVGPRtoAGPR</a>.</p>

</div>
</div>

### setCFIType() {#a1902a720147e652fa4a4857e069f4dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setCFIType (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, uint32_t Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the CFI type for the instruction.</p>

<p>Declaration at line 1979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>

</div>
</div>

### setDebugInstrNum() {#a443787beae18cf65517b239aa15d74e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setDebugInstrNum (unsigned Num)</td>
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

<p>Set instruction number of this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>Avoid using unless you're deserializing this information.</p>


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>.</p>

</div>
</div>

### setDebugLoc() {#af2641f071128da26317fab5b9594ec71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
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

<p>Replace current source information with new such.</p>


<p>Avoid using this, the constructor argument is preferable.</p>


<p>Definition at line 1903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a93c989266fe445bd8d6466480699665e">llvm::WebAssemblyDebugValueManager::cloneSink</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>.</p>

</div>
</div>

### setDebugValueUndef() {#a0cf83915bd66f2a610c72f3d028f8704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setDebugValueUndef ()</td>
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

<p>Sets all register debug operands in this debug value instruction to be undef.</p>

<p>Definition at line 2013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1e2899f5dd649a9f82c32b99e5d77dcd">debug_operands</a> and <a href="#accb3520c6008297678829eed493b6c68">isDebugValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>.</p>

</div>
</div>

### setDesc() {#a9117508fb00fda14207e7f968389544c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setDesc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; TID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the instruction descriptor (thus opcode) of the current instruction with a new one.</p>

<p>Declaration at line 1899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ab05719438bdf4b46871e5ecd9730caeb">getMF</a>, <a href="#a1e855100f407ca4be098d0050be403b0">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8c08e500f0fa00d1e45871607846260b">llvm::MachineFunction::handleChangeDesc</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#adcb5f001406dc2b45024dd582c444e6d">llvm::MCInstrDesc::Opcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adf5d3b4379e4e570f14f6700d6e87467">llvm::SIInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a47d4233d9f4a5998d0b67ebd1414dc76">Expand2AddrKreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acd9a409ba62041c36090fe42bfdf16d7">llvm::M68kInstrInfo::ExpandCCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#acf2585460bbea1e2bac210c9588d4bc4">expandNOVLXLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a44f31fb5ea31b5062b22b05cb8fddee4">expandNOVLXStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ab69e2cd15cb4ac3f0262a15fdd65befa">expandXorFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findLongFormInRangeCPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator/#a8ca037899f2fcee956e635f6f5c0cb2c">anonymous{SIInsertWaitcnts.cpp}::WaitcntGenerator::promoteSoftWaitCnt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6711738d18f70c1843eac7255405df54">llvm::CombinerHelper::replaceOpcodeWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a0d70a38e8f0622515630e7e8672df270">selectMergeValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a838cd050490773e0349589c0d78618fc">selectUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ab2691fcbf8c425f40f56f085b5233783">llvm::HexagonPacketizerList::shouldAddToPacket</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>.</p>

</div>
</div>

### setFlag() {#aba86b0738c2ab2a52688b846c45bfe59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setFlag (<a href="#aafacf84de1cb994a92dc045f4aa1d518">MIFlag</a> Flag)</td>
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

<p>Set a MI flag.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="#a0aad617bc1bdef5bda2689f7a9fd06f6">bundleWithPred</a>, <a href="#a21273844821e851afa28968bdd6ff10f">bundleWithSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a055df59820235c32c403d7c78de5494b">emitQuietFCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#aa8a34f3a734cc8a58ab08ce66250b1e1">fuseInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a28645da3fb06003fe7d32756e5ff929b">anonymous{MIParser.cpp}::MIParser::parseBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp/#a28b825c91d72def7c69724ef60ec4142">transferMIFlag</a>.</p>

</div>
</div>

### setFlags() {#a264402282f599b6181b6415278fbf849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setFlags (unsigned flags)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">BundledSucc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>.</p>

</div>
</div>

### setHeapAllocMarker() {#a9a10f5acfd3fb2690d6bc2c78c26be13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setHeapAllocMarker (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a marker on instructions that denotes where we should create and emit heap alloc site labels.</p>


<p>This waits until after instruction selection and optimizations to create the label, so it should still work if the instruction is removed or duplicated.</p>


<p>Declaration at line 1970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### setMemRefs() {#a5981137a17cad3d9b2276ad63e15ee40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setMemRefs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; MemRefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign this <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>'s memory reference descriptor list.</p>


<p>Unlike other methods, this <em>will</em> allocate them into a new array associated with the provided <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></span>.</p>


<p>Declaration at line 1922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a6e05e3bfe64497149a8800b1830c4001">dropMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>


<p>Referenced by <a href="#afc4107c92fd8d37e8d0cb596f2a25d98">addMemOperand</a>, <a href="#a3a26f11d1735bf0f25261aefd2bee9c1">cloneMemRefs</a>, <a href="#a7a5607fcb0a195620036bb0f1217c8a2">cloneMergedMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a2432d0bb09d9fe3b6bb004d8dbf77a99">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1dfb0ae952397bf4c6d5cbcaff4c4b6d">llvm::MachineInstrBuilder::setMemRefs</a>.</p>

</div>
</div>

### setMMRAMetadata() {#af4e52d47d0f7fa13dd23fae4cfc4f85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setMMRAMetadata (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MMRAs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a72cc8dc853a4823eccff58bc0269b306">llvm::MachineInstrBuilder::setMMRAMetadata</a>.</p>

</div>
</div>

### setPCSections() {#ae76989792a75b7735546e69711d22209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setPCSections (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abdda4cba7788bae87378a6cbdc81dbe2">llvm::MachineInstrBuilder::setPCSections</a>.</p>

</div>
</div>

### setPhysRegsDeadExcept() {#ac2afcfcff9187a2201549d75d4e16149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setPhysRegsDeadExcept (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; UsedRegs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark every physreg used by this instruction as dead except those in the UsedRegs list.</p>


<p>On instructions with register mask operands, also add implicit-def operands for all registers in UsedRegs.</p>


<p>Declaration at line 1745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ad0a79b68db2b8f84f92b1ee24352b3ce">addRegisterDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a55fdcb2a9df9a69067eed1bc17a0b927">llvm::MachineOperand::isRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### setPostInstrSymbol() {#ac8ce95857a66b3706a84d1fd5072f0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setPostInstrSymbol (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a symbol that will be emitted just after the instruction itself.</p>


<p>Setting this to a null pointer will remove any such symbol.</p>


<p>FIXME: This is not fully implemented yet.</p>


<p>Declaration at line 1960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>.</p>

</div>
</div>

### setPreInstrSymbol() {#a2517e88d2d947effcdaeaeec39b2e2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setPreInstrSymbol (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a symbol that will be emitted just prior to the instruction itself.</p>


<p>Setting this to a null pointer will remove any such symbol.</p>


<p>FIXME: This is not fully implemented yet.</p>


<p>Declaration at line 1953 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a22b83742938bc0b4477b0f19d563ebfd">getCFIType</a>, <a href="#ad17b8014d3272aa5121425e2bcef34db">getHeapAllocMarker</a>, <a href="#a20c1f72cf20853c89c6e92a21c5f49ce">getMMRAMetadata</a>, <a href="#a7545019dcaee79c0d03335e6648c8bab">getPCSections</a>, <a href="#add92393d0dae36ec6d41435e11d09884">getPostInstrSymbol</a>, <a href="#ac7561e84ab87828a4c700c2e05ca8302">getPreInstrSymbol</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab37075d621acbbfc96ef2662f2e29883">memoperands</a>.</p>


<p>Referenced by <a href="#aa63ab5e3e1630ddb53a1a0def539a34c">cloneInstrSymbols</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>.</p>

</div>
</div>

### setRegisterDefReadUndef() {#a05427132a2cb380432ed752b5f2dea6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setRegisterDefReadUndef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool IsUndef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark all subregister defs of register <span class="doxyComputerOutput">Reg</span> with the undef flag.</p>


<p>This function is used when we determined to have a subregister def in an otherwise undefined super register.</p>


<p>Declaration at line 1733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 2207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#ade4229c653b0cbcaca057e8af5002783">all_defs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>.</p>

</div>
</div>

### shouldUpdateAdditionalCallInfo() {#ad957f14a0cd72c10f5117fd1b9f30173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::shouldUpdateAdditionalCallInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if copying, moving, or erasing this instruction requires updating additional call info (see copyCallInfo, moveCallInfo, eraseCallInfo).</p>

<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a26e1467ec6a91a35dfc32239e50f0fb5a255450aa2654dd8ed193764eafee2be4">AnyInBundle</a>, <a href="#a3e2f795dfcb9269e1263453796f4b994">isBundle</a> and <a href="#a806028855ad5c3431de7958e031e5ee1">isCandidateForAdditionalCallInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3c50b05be0be83e693f50b87284c76d6">llvm::MachineFunction::cloneMachineInstrBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aeb5dd54bce3bb99569a87f31bf7cc14a">llvm::MachineFunction::copyAdditionalCallInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1edf23fab2b9c28661068c487aeeb401">llvm::MachineFunction::moveAdditionalCallInfo</a>.</p>

</div>
</div>

### substituteRegister() {#a9f59e1f6dd6677348ba082a10fc09061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::substituteRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; RegInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all occurrences of FromReg with ToReg:SubIdx, properly composing subreg indices where necessary.</p>

<p>Declaration at line 1705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a999b8f3e58e7ca479f26445bae791a7c">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9842e6805ce84262b6bbe7da2b26772c">llvm::MachineOperand::substPhysReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a13a5b2fd837189405f1b07a6c9249d4f">llvm::MachineOperand::substVirtReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>.</p>

</div>
</div>

### tieOperands() {#aa37e31e5df481d2f8a6f9f022886cf5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::tieOperands (unsigned DefIdx, unsigned UseIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a tie between the register operands at DefIdx and UseIdx.</p>


<p>tieOperands - Mark operands at DefIdx and UseIdx as tied to each other.</p>


<p>The tie will cause the register allocator to ensure that the two operands are assigned the same physical register.</p>


<p>Tied operands are managed automatically for explicit operands in the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a>. This method is for exceptional cases like inline asm.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> and def operands can be tied together, indicated by a non-zero TiedTo field. TiedTo can have these values:</p>


<p>0: Operand is not tied to anything. 1 to TiedMax-1: Tied to getOperand(TiedTo-1). TiedMax: Tied to an operand &gt;= TiedMax-1.</p>


<p>The tied def must be one of the first TiedMax operands on a normal instruction. INLINEASM instructions allow more tied defs.</p>


<p>Declaration at line 1666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="#a4b743093219cfca13b1ec2cb58903fba">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a058531ea6c1669bc3fb3b598d25da429">TiedMax</a>.</p>


<p>Referenced by <a href="#a469e271fba3a9b52dad4fa54eaf44e2b">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a519410003771768aef013bd57efa6cf4">llvm::SIInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a> and <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>.</p>

</div>
</div>

### unbundleFromPred() {#a6780a3b4a7f87d5fc85574207fa02c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::unbundleFromPred ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Break bundle above this instruction.</p>

<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">BundledSucc</a>, <a href="#a859897c8a9706acd4c065d857254d58c">clearFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a> and <a href="#a5cc5933defcffa4e4eca689dfeaf0a2d">isBundledWithPred</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a263c68370ee4203b80d388fd7b89ebb5">moveInstrOut</a>.</p>

</div>
</div>

### unbundleFromSucc() {#ade1d83105d6c2d3de29fca286f9d1b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::unbundleFromSucc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Break bundle below this instruction.</p>

<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">BundledPred</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">BundledSucc</a>, <a href="#a859897c8a9706acd4c065d857254d58c">clearFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineInstr, Options... &gt;::type &gt;::getIterator</a> and <a href="#ad07416ea31edd139a4ebe5b42a6f80b0">isBundledWithSucc</a>.</p>

</div>
</div>

### untieRegOperand() {#a8e66e9ca7739874b25b9337940c26a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::untieRegOperand (unsigned OpIdx)</td>
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

<p>Break any tie involving OpIdx.</p>

<p>Definition at line 1992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#aa2dfd6ae7ded046f5e5e03e0f745d5c3">findTiedOperandIdx</a>, <a href="#ad67c9230577a0b640c52852c75c93939">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="#a904f484cd7cfe20a0e7673399c88cc3c">insert</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a> and <a href="#ac3b161ec90385105cb46a08b52139e60">removeOperand</a>.</p>

</div>
</div>

### uses() {#a3949f157e1034f6cb5d16ad708059aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mop_iterator &gt; llvm::MachineInstr::uses ()</td>
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

<p>Returns a range that includes all operands which may be register uses.</p>


<p>This may include unrelated operands which are not register uses.</p>


<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>


<p>Referenced by <a href="#a3daf8e155bf0aa3e65b5260bfe3698c5">all_uses</a>, <a href="#a7954d5796d6983c4a71e1cf1a838d7df">all_uses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a5fc63c934f29c38bfba9692a6a2166ee">collectCallSiteParameters</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a7685ee8f0cb0ee9e255a169a8765e54f">llvm::SPIRVGlobalRegistry::getSPIRVTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp/#a9de31756d24ba6d5dbe75c2d425720d4">hasSameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a3b0f315e261e572d6f0b357e4404ca42">isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae2bd5329e5726d560529de68df90503c">llvm::CombinerHelper::matchFreezeOfSingleMaybePoisonOperand</a>.</p>

</div>
</div>

### uses() {#a15bc8fb07e719b5a47a7c9070c5e26af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_mop_iterator &gt; llvm::MachineInstr::uses ()</td>
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

<p>Returns a range that includes all operands which may be register uses.</p>


<p>This may include unrelated operands which are not register uses.</p>


<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a9839b7e1d8811ea9d41f901ab6a0f23b">getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a0037ac891190e1408b04a48156c3368c">operands_begin</a> and <a href="#a6e6014fca5895fa5f9487ff7c79678b0">operands_end</a>.</p>

</div>
</div>

### usesCustomInsertionHook() {#a320180749c883b427d229d1a2f3fefc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::usesCustomInsertionHook (<a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type=<a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a>)</td>
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

<p>Return true if this instruction requires custom insertion support when the DAG scheduler is inserting it into a machine basic block.</p>


<p>If this is true for the instruction, it basically means that it is a pseudo instruction used at <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> time that is expanded out into magic code by the target when MachineInstrs are formed.</p>


<p>If this is true, the TargetLoweringInfo::InsertAtEndOfBasicBlock method is used to insert this into the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="#a257b68a68cb55f34cb704eb776afda1e">hasProperty</a>, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">IgnoreBundle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcid/#ab357441fcd1ea1f9b0d27c12700f6023ad14700fd3b1c636ccbbdac0e94dd8bf9">llvm::MCID::UsesCustomInserter</a>.</p>

</div>
</div>

### wouldBeTriviallyDead() {#a5c1ff2ea28f57b7c7afb9a02b5adfff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::wouldBeTriviallyDead ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction would be trivially dead if all of its defined registers were dead.</p>

<p>Declaration at line 1755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#a0363204b5fbab08a46f5a7cd7f376f78">getOpcode</a>, <a href="#af2df666e80610d028fc34fc23a82dd27">isFakeUse</a>, <a href="#a9f137387193043b6e4f37112d60f748d">isLifetimeMarker</a>, <a href="#ad43bf1af480830a4d6604e969e3f38e9">isPHI</a> and <a href="#a3c3bece1d6d099a7b6bc4c22ea768e8e">isSafeToMove</a>.</p>


<p>Referenced by <a href="#abb834744243c11cb677261382ac15bea">isDead</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRegOperandsToUseLists() {#a340bd0c437deaa0c106d2f7bd77f7370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::addRegOperandsToUseLists (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add all of the register operands in this instruction from their respective use lists.</p>


<p>This requires that the operands not be on their use lists yet.</p>


<p>Declaration at line 2073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### dumprImpl() {#a61de1bcd9c9e1603005789971115446d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineInstr::dumprImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned Depth, unsigned MaxDepth, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; AlreadySeenInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1700 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### getRegClassConstraintEffectForVRegImpl() {#a57b81f3a02c0820b0084a17687a5cbed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * MachineInstr::getRegClassConstraintEffectForVRegImpl (unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * CurRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements the logic of getRegClassConstraintEffectForVReg for the this MI and the given operand index <span class="doxyComputerOutput">OpIdx</span>.</p>


<p>If the related operand does not constrained Reg, this returns CurRC.</p>


<p>Declaration at line 2081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### getRegInfo() {#a4d8fe33d35fa1a1033b4e8f9fdcc00d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo * MachineInstr::getRegInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this instruction is embedded into a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>, return the <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> object for the current function, otherwise return null.</p>


<p>getRegInfo - If this instruction is embedded into a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>, return the <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> object for the current function, otherwise return null.</p>


<p>Declaration at line 2062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### getRegInfo() {#a2d8f4791d88a244924d67cf5fa89ef4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo * MachineInstr::getRegInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### hasPropertyInBundle() {#aa9722fe61892279688b0c88e652d0c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineInstr::hasPropertyInBundle (uint64_t Mask, <a href="#a26e1467ec6a91a35dfc32239e50f0fb5">QueryType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Slow path for hasProperty when we're dealing with a bundle.</p>

<p>Declaration at line 2076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### removeRegOperandsFromUseLists() {#a024b74f208e958ab92813318ce5daf00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::removeRegOperandsFromUseLists (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink all of the register operands in this instruction from their respective use lists.</p>


<p>This requires that the operands already be on their use lists.</p>


<p>Declaration at line 2068 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### setExtraInfo() {#ab266e3f685642c42995b2fe3dab43dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineInstr::setExtraInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; MMOs, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * PreInstrSymbol, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * PostInstrSymbol, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * HeapAllocMarker, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * PCSections, uint32_t CFIType, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MMRAs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores extra instruction information inline or allocates as ExtraInfo based on the number of pointers.</p>

<p>Declaration at line 2087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>

</div>
</div>

### setParent() {#a916df6545831877c774f5ba9a7963805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineInstr::setParent (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * P)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AsmPrinterFlags {#ab813c2d1ea8236843211deae264842a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachineInstr::AsmPrinterFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Various bits of information used by the <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> to emit helpful comments.</p>


<p>This is <em>not</em> semantic information. Do not use this for anything other than to convey comment information to <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>.</p>


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### CapOperands {#a02c85a084eb406b8b51b9f41f2a3d96a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperandCapacity llvm::MachineInstr::CapOperands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### DbgLoc {#afedced451fcdddffdd8963a710c1d721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::MachineInstr::DbgLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### DebugInstrNum {#acbf59d7ef807d43ca5d21e7da64f8900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineInstr::DebugInstrNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unique instruction number.</p>


<p>Used by DBG_INSTR_REFs to refer to the values defined by this instruction.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### Flags {#a44041bc3d1bf9635849d20804dc6a2b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachineInstr::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Various bits of additional information about the machine instruction.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### Info {#ac88cf2c3434a399afb937fb6d1598d0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerSumType&lt;ExtraInfoInlineKinds, PointerSumTypeMember&lt;EIIK_MMO, MachineMemOperand *&gt;, PointerSumTypeMember&lt;EIIK_PreInstrSymbol, MCSymbol *&gt;, PointerSumTypeMember&lt;EIIK_PostInstrSymbol, MCSymbol *&gt;, PointerSumTypeMember&lt;EIIK_OutOfLine, ExtraInfo *&gt; &gt; llvm::MachineInstr::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### MCID {#abfef9b79b44d26ec7c470ec309774b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc* llvm::MachineInstr::MCID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### NumOperands {#ab8e48a6fa0197595a03b3464271f7ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachineInstr::NumOperands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of operands on instruction.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### Opcode {#aed808f363d7186350fe6892e223eeebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachineInstr::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached opcode from <a href="/web-llvm/docs/api/namespaces/llvm/mcid">MCID</a>.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### Operands {#aefb9c9ca08ddcb2f8fee62b3609028d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand* llvm::MachineInstr::Operands = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### Parent {#ae743252fbb1f60699b04bde8750b313c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::MachineInstr::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### copyFlagsFromInstruction() {#a8fa9ad46c9ec8c4de6dca3245edeedfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachineInstr::copyFlagsFromInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Declaration at line 1986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a>.</p>


<p>References <a href="#aafacf84de1cb994a92dc045f4aa1d518ab9f2d292718c407a75b2f2c829c1c874">Disjoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a4802af6d0cf3b900adb6296bccedf2a0">FmAfn</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a43892bfec2e4bb79639d4b4f1cf28ae8">FmArcp</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a9a1da4c7c2a2a2ed0d083327dd28277c">FmContract</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a45ffd15293a16979f698cec4e2c60ad0">FmNoInfs</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518aba11aa58176a446ba70d4f0ad0e04418">FmNoNans</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518adc42a7d40f8bd9c7f1a9c2beb0135fdc">FmNsz</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a7e452f6e23b696b4701cb18790b32992">FmReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">IsExact</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a3453657a772c3023f6ef942525db0d5d">NonNeg</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">NoSWrap</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a1eb5c75dbc40abd0d7998aeefd1c758b">NoUSWrap</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">NoUWrap</a>, <a href="#aafacf84de1cb994a92dc045f4aa1d518ae6a23fd6cabf87a0e53689d9b18620ad">SameSign</a> and <a href="#aafacf84de1cb994a92dc045f4aa1d518a87ff88efff0f69c3e3f902410756ddef">Unpredictable</a>.</p>


<p>Referenced by <a href="#a49ac3225c216191d957cf56ad28f1c84">copyIRFlags</a>.</p>

</div>
</div>

### getDebugOperandsForReg() {#a05c54bfb75dbb555ab457e768bbcfe73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Operand, typename Instruction&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filter_iterator&lt; Operand *, std::function&lt; bool(Operand &amp;Op)&gt; &gt; &gt; llvm::MachineInstr::getDebugOperandsForReg (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Returns a range of all of the operands that correspond to a debug use of <span class="doxyComputerOutput">Reg</span>.</p>

<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="#aa0e69cc2fdf3daec4ae61c572d71bf43">getDebugOperandsForReg</a>, <a href="#af06fa0062be2cb3feb58ad49814b9b2a">getDebugOperandsForReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1f42f634cff46c0380f80cc600c19f3b">llvm::updateDbgValueForSpill</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### opIsRegDef() {#a24e92a9ed8a30f709a7e85bf43fe47e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::opIsRegDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

### opIsRegUse() {#a0e69335c61f27c5866da1f5bac6812df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstr::opIsRegUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">MachineInstr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp">MachineInstr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
