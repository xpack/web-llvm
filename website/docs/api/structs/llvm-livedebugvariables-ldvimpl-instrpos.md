---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/livedebugvariables/ldvimpl/instrpos
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InstrPos` Struct Reference

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> for any debug instructions unlinked from their blocks during regalloc. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LiveDebugVariables::LDVImpl::InstrPos { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae858b68e34fd90770a544c1018361fb3">MI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug instruction, unlinked from it's block. <a href="#ae858b68e34fd90770a544c1018361fb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a9473c3e779c7bdeae436824afa637">Idx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Slot position where MI should be re-inserted. <a href="#a77a9473c3e779c7bdeae436824afa637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3679bc7be2aca61f2edca630bbcc5522">MBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Block that MI was in. <a href="#a3679bc7be2aca61f2edca630bbcc5522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> for any debug instructions unlinked from their blocks during regalloc.</p>


<p>Stores the instr and it's location, so that they can be re-inserted after regalloc is over.</p>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Idx {#a77a9473c3e779c7bdeae436824afa637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveDebugVariables::LDVImpl::InstrPos::Idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Slot position where MI should be re-inserted.</p>

<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### MBB {#a3679bc7be2aca61f2edca630bbcc5522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::LiveDebugVariables::LDVImpl::InstrPos::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Block that MI was in.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### MI {#ae858b68e34fd90770a544c1018361fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::LiveDebugVariables::LDVImpl::InstrPos::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug instruction, unlinked from it's block.</p>

<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
