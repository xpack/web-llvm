---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regbankselect/repairingplacement
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RepairingPlacement` Class Reference

<p>Struct used to represent the placement of a repairing point for a given operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegBankSelect::RepairingPlacement { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RepairingKind { <a href="#a66bdd17ee82024ea0ccbb0288b379dd6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define the kind of action this repairing needs. <a href="#a66bdd17ee82024ea0ccbb0288b379dd6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40139f3ca5fa604f87136efa9ca611ca">RepairingPlacement</a> (MachineInstr &amp;MI, unsigned OpIdx, const TargetRegisterInfo &amp;TRI, Pass &amp;P, RepairingKind Kind=RepairingKind::Insert)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a repairing placement for the <span class="doxyComputerOutput">OpIdx-th</span> operand of <span class="doxyComputerOutput">MI</span>. <a href="#a40139f3ca5fa604f87136efa9ca611ca">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2d45f98e7457256296b0943ddd4a6c">switchTo</a> (RepairingKind NewKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the type of this repairing placement to <span class="doxyComputerOutput">NewKind</span>. <a href="#adb2d45f98e7457256296b0943ddd4a6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a66bdd17ee82024ea0ccbb0288b379dd6">RepairingKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b8d4d6af70c4773cfe00be1953a75b">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kind of repairing. <a href="#a75b8d4d6af70c4773cfe00be1953a75b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8a308925d56f9e2b01d0c1537c4743">OpIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index of the operand that will be repaired. <a href="#aed8a308925d56f9e2b01d0c1537c4743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc79ff4b4c1ecb48bab8dc456985dde4">CanMaterialize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are all the insert points materializeable? <a href="#afc79ff4b4c1ecb48bab8dc456985dde4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf7b5a127d1eaa4e374a030ea0adf8a">HasSplit</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is there any of the insert points needing splitting? <a href="#a8bf7b5a127d1eaa4e374a030ea0adf8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aadf6a4c523811c7749ecaced8e449854">InsertionPoints</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5115e9ae5400a0b3b77717b941053e61">InsertPoints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point for the repair code. <a href="#a5115e9ae5400a0b3b77717b941053e61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312e3f9b040ce9dfa030f00705863360">P</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some insertion points may need to update the liveness and such. <a href="#a312e3f9b040ce9dfa030f00705863360">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Convenient types for a list of insertion points. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf6a4c523811c7749ecaced8e449854">InsertionPoints</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint">InsertPoint</a> &gt;, 2 &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac084e5dcf8b5623c02615b39fb15346e">insertpt_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">InsertionPoints::iterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb3abc567d90e2e308cde17b004366a">const_insertpt_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">InsertionPoints::const_iterator</a></td>
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

## Getters. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a66bdd17ee82024ea0ccbb0288b379dd6">RepairingKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7cdfa61d3992d77bec94e1eda33bbc9">getKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f51880f9bdd786f0d0983c4f15122b">getOpIdx</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39535988981c86b512949745cbfab81c">canMaterialize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05dcab804adfa11b36715dddba6c52db">hasSplit</a> ()</td>
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

## Overloaded methods to add an insertion point. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc878eab773e206b796e5b9790343a8e">addInsertPoint</a> (MachineBasicBlock &amp;MBB, bool Beginning)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22a932feb5afaad1fc119d2d1b32767">addInsertPoint</a> (MachineInstr &amp;MI, bool Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a InstrInsertionPoint to the list of InsertPoints. <a href="#ab22a932feb5afaad1fc119d2d1b32767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7280cb5ef0246479249f33a11b1cf92a">addInsertPoint</a> (MachineBasicBlock &amp;Src, MachineBasicBlock &amp;Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an EdgeInsertionPoint (<span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Dst</span>) to the list of InsertPoints. <a href="#a7280cb5ef0246479249f33a11b1cf92a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6716d42c1c9dcd8f86c27dd6ab4619ce">addInsertPoint</a> (InsertPoint &amp;Point)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint">InsertPoint</a> to the list of insert points. <a href="#a6716d42c1c9dcd8f86c27dd6ab4619ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Accessors related to the insertion points. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac084e5dcf8b5623c02615b39fb15346e">insertpt_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79339174ad58248f97f5f008a433f6f7">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac084e5dcf8b5623c02615b39fb15346e">insertpt_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc2edf955a201c02efec132befd5c67">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3bb3abc567d90e2e308cde17b004366a">const_insertpt_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a0b239822776d782569d9f2f175c83">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3bb3abc567d90e2e308cde17b004366a">const_insertpt_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70f18ca7fb9f39bddb22fe25e93ae63">end</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dead5300c592bf7b44fadc46d5d1f3">getNumInsertPoints</a> () const</td>
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

<p>Struct used to represent the placement of a repairing point for a given operand.</p>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RepairingKind {#a66bdd17ee82024ea0ccbb0288b379dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RegBankSelect::RepairingPlacement::RepairingKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define the kind of action this repairing needs.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a66bdd17ee82024ea0ccbb0288b379dd6a1b5edfd2f0ed3f87981ab15c425b0165"></a></td>
<td class="doxyEnumItemDescription">Nothing to repair, just drop this action</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Insert<a id="a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195"></a></td>
<td class="doxyEnumItemDescription">Reparing code needs to happen before InsertPoints</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Reassign<a id="a66bdd17ee82024ea0ccbb0288b379dd6a756e97b1942ca89260909cfdfb64b957"></a></td>
<td class="doxyEnumItemDescription">(Re)assign the register bank of the operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Impossible<a id="a66bdd17ee82024ea0ccbb0288b379dd6a98e66b30e93d741af07a3fefeb66ab1b"></a></td>
<td class="doxyEnumItemDescription">Mark this repairing placement as impossible</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RepairingPlacement() {#a40139f3ca5fa604f87136efa9ca611ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankSelect::RepairingPlacement::RepairingPlacement (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp; P, <a href="#a66bdd17ee82024ea0ccbb0288b379dd6">RepairingKind</a> Kind=<a href="#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">RepairingKind::Insert</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a repairing placement for the <span class="doxyComputerOutput">OpIdx-th</span> operand of <span class="doxyComputerOutput">MI</span>.</p>


<p><span class="doxyComputerOutput">TRI</span> is used to make some checks on the register aliases if the machine operand is a physical register. <span class="doxyComputerOutput">P</span> is used to to update liveness information and such when materializing the points.</p>


<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="#afc878eab773e206b796e5b9790343a8e">addInsertPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a66bdd17ee82024ea0ccbb0288b379dd6a98e66b30e93d741af07a3fefeb66ab1b">Impossible</a>, <a href="#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a98f7afadeec4309cbce64ca040635c04">llvm::RegBankSelect::TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### switchTo() {#adb2d45f98e7457256296b0943ddd4a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegBankSelect::RepairingPlacement::switchTo (<a href="#a66bdd17ee82024ea0ccbb0288b379dd6">RepairingKind</a> NewKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the type of this repairing placement to <span class="doxyComputerOutput">NewKind</span>.</p>


<p>It is not possible to switch a repairing placement to the <a href="#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">RepairingKind::Insert</a>. There is no fundamental problem with that, but no uses as well, so do not support it for now.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>NewKind != <a href="#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">RepairingKind::Insert</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><a href="#aa7cdfa61d3992d77bec94e1eda33bbc9">getKind()</a> == NewKind</p></dd>
</dl>


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66bdd17ee82024ea0ccbb0288b379dd6a98e66b30e93d741af07a3fefeb66ab1b">Impossible</a> and <a href="#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">Insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CanMaterialize {#afc79ff4b4c1ecb48bab8dc456985dde4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegBankSelect::RepairingPlacement::CanMaterialize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are all the insert points materializeable?</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### HasSplit {#a8bf7b5a127d1eaa4e374a030ea0adf8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegBankSelect::RepairingPlacement::HasSplit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is there any of the insert points needing splitting?</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### InsertPoints {#a5115e9ae5400a0b3b77717b941053e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertionPoints llvm::RegBankSelect::RepairingPlacement::InsertPoints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insertion point for the repair code.</p>


<p>The repairing code needs to happen just before these points.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### Kind {#a75b8d4d6af70c4773cfe00be1953a75b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RepairingKind llvm::RegBankSelect::RepairingPlacement::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kind of repairing.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### OpIdx {#aed8a308925d56f9e2b01d0c1537c4743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegBankSelect::RepairingPlacement::OpIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index of the operand that will be repaired.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### P {#a312e3f9b040ce9dfa030f00705863360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass&amp; llvm::RegBankSelect::RepairingPlacement::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some insertion points may need to update the liveness and such.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Convenient types for a list of insertion points.

### const\_insertpt\_iterator {#a3bb3abc567d90e2e308cde17b004366a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegBankSelect::RepairingPlacement::const_insertpt_iterator =  InsertionPoints::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### InsertionPoints {#aadf6a4c523811c7749ecaced8e449854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegBankSelect::RepairingPlacement::InsertionPoints =  SmallVector&lt;std::unique_ptr&lt;InsertPoint&gt;, 2&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### insertpt\_iterator {#ac084e5dcf8b5623c02615b39fb15346e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::RegBankSelect::RepairingPlacement::insertpt_iterator =  InsertionPoints::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Getters.

### canMaterialize {#a39535988981c86b512949745cbfab81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegBankSelect::RepairingPlacement::canMaterialize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a>.</p>

</div>
</div>

### getKind {#aa7cdfa61d3992d77bec94e1eda33bbc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RepairingKind llvm::RegBankSelect::RepairingPlacement::getKind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### getOpIdx {#a54f51880f9bdd786f0d0983c4f15122b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegBankSelect::RepairingPlacement::getOpIdx ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>.</p>

</div>
</div>

### hasSplit {#a05dcab804adfa11b36715dddba6c52db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegBankSelect::RepairingPlacement::hasSplit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a> and <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Overloaded methods to add an insertion point.



<p>Add a MBBInsertionPoint to the list of InsertPoints.</p>


### addInsertPoint {#afc878eab773e206b796e5b9790343a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::RepairingPlacement::addInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, bool Beginning)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="#afc878eab773e206b796e5b9790343a8e">addInsertPoint</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#afc878eab773e206b796e5b9790343a8e">addInsertPoint</a>, <a href="#a7280cb5ef0246479249f33a11b1cf92a">addInsertPoint</a>, <a href="#ab22a932feb5afaad1fc119d2d1b32767">addInsertPoint</a> and <a href="#a40139f3ca5fa604f87136efa9ca611ca">RepairingPlacement</a>.</p>

</div>
</div>

### addInsertPoint {#ab22a932feb5afaad1fc119d2d1b32767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::RepairingPlacement::addInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool Before)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a InstrInsertionPoint to the list of InsertPoints.</p>

<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="#afc878eab773e206b796e5b9790343a8e">addInsertPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### addInsertPoint {#a7280cb5ef0246479249f33a11b1cf92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::RepairingPlacement::addInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an EdgeInsertionPoint (<span class="doxyComputerOutput">Src</span>, <span class="doxyComputerOutput">Dst</span>) to the list of InsertPoints.</p>

<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>Reference <a href="#afc878eab773e206b796e5b9790343a8e">addInsertPoint</a>.</p>

</div>
</div>

### addInsertPoint {#a6716d42c1c9dcd8f86c27dd6ab4619ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::RepairingPlacement::addInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint">InsertPoint</a> &amp; Point)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint">InsertPoint</a> to the list of insert points.</p>


<p>This method takes the ownership of &amp;<span class="doxyComputerOutput">Point</span>.</p>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#ae449014b2e72fef6f2f952ea5e44e0f1">llvm::RegBankSelect::InsertPoint::canMaterialize</a> and <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#aed32195671c69b83c41212d5e67d5b62">llvm::RegBankSelect::InsertPoint::isSplit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Accessors related to the insertion points.

### begin {#a79339174ad58248f97f5f008a433f6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">insertpt_iterator llvm::RegBankSelect::RepairingPlacement::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### begin {#a68a0b239822776d782569d9f2f175c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_insertpt_iterator llvm::RegBankSelect::RepairingPlacement::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### end {#a2cc2edf955a201c02efec132befd5c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">insertpt_iterator llvm::RegBankSelect::RepairingPlacement::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### end {#aa70f18ca7fb9f39bddb22fe25e93ae63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_insertpt_iterator llvm::RegBankSelect::RepairingPlacement::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### getNumInsertPoints {#a14dead5300c592bf7b44fadc46d5d1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegBankSelect::RepairingPlacement::getNumInsertPoints ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
