---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/instructionselect/miiteratormaintainer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MIIteratorMaintainer` Class

<p>This class observes instruction insertions/removals. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class InstructionSelect::MIIteratorMaintainer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver">GISelChangeObserver</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class that contains various methods for clients to notify about changes. <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3605e2e9f936929fe15de280eae49bdf">changingInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction is about to be mutated in some way. <a href="#a3605e2e9f936929fe15de280eae49bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4336acab7c5848f3bbce549a5f21b7">changedInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction was mutated in some way. <a href="#a2e4336acab7c5848f3bbce549a5f21b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae24a762b459a969ef62d4b8f30a760d2">createdInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction has been created and inserted into the function. <a href="#ae24a762b459a969ef62d4b8f30a760d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17bdd979f7655c0091237f11f62e8d25">erasingInstr</a> (MachineInstr &amp;MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction is about to be erased. <a href="#a17bdd979f7655c0091237f11f62e8d25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02b78d863d42ea8c9dd7feed49223b04">reportFullyCreatedInstrs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#abada92f8cd2854d2b747f14c4a7be0ed">MachineBasicBlock::reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01391ac728e588779f5a8bd323193ed5">MII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe94c5b1a0245805cae37d8d199b63e0">CreatedInstrs</a></td>
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

<p>This class observes instruction insertions/removals.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/instructionselect">InstructionSelect</a> stores an iterator of the instruction prior to the one that is currently being selected to determine which instruction to select next. Previously this meant that selecting multiple instructions at once was illegal behavior due to potential invalidation of this iterator. This is a non-obvious limitation for selector implementers. Therefore, to allow deletion of arbitrary instructions, we detect this case and continue selection with the predecessor of the deleted instruction.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### changedInstr() {#a2e4336acab7c5848f3bbce549a5f21b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionSelect::MIIteratorMaintainer::changedInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This instruction was mutated in some way.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### changingInstr() {#a3605e2e9f936929fe15de280eae49bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionSelect::MIIteratorMaintainer::changingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This instruction is about to be mutated in some way.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### createdInstr() {#ae24a762b459a969ef62d4b8f30a760d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionSelect::MIIteratorMaintainer::createdInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An instruction has been created and inserted into the function.</p>


<p>Note that the instruction might not be a fully fledged instruction at this point and won't be if the <a href="/web-llvm/docs/api/classes/llvm/machinefunction/delegate">MachineFunction::Delegate</a> is calling it. This is because the delegate only sees the construction of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> before operands have been added.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### erasingInstr() {#a17bdd979f7655c0091237f11f62e8d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionSelect::MIIteratorMaintainer::erasingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An instruction is about to be erased.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a01391ac728e588779f5a8bd323193ed5">llvm::InstructionSelect::MIIteratorMaintainer::MII</a>.</p>

</div>
</div>

### reportFullyCreatedInstrs() {#a02b78d863d42ea8c9dd7feed49223b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionSelect::MIIteratorMaintainer::reportFullyCreatedInstrs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MII {#a01391ac728e588779f5a8bd323193ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::reverse_iterator llvm::InstructionSelect::MIIteratorMaintainer::MII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>


<p>Referenced by <a href="#a17bdd979f7655c0091237f11f62e8d25">llvm::InstructionSelect::MIIteratorMaintainer::erasingInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CreatedInstrs {#afe94c5b1a0245805cae37d8d199b63e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;const MachineInstr *, 32&gt; llvm::InstructionSelect::MIIteratorMaintainer::CreatedInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/instructionselect-cpp">InstructionSelect.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
