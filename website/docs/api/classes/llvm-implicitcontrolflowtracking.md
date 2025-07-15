---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/implicitcontrolflowtracking
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ImplicitControlFlowTracking` Class Reference

<p>This class allows to keep track on instructions with implicit control flow. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ImplicitControlFlowTracking { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">llvm/Analysis/InstructionPrecedenceTracking.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking">InstructionPrecedenceTracking</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462bb685cd45aed006cc467ccbcacd62">getFirstICFI</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the topmost instruction with implicit control flow from the given basic block. <a href="#a462bb685cd45aed006cc467ccbcacd62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe6442a02a15b138ff870eeeb6da50b">hasICF</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if at least one instruction from the given basic block has implicit control flow. <a href="#acbe6442a02a15b138ff870eeeb6da50b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6680bd71c9d15033f99c787b50d09e47">isDominatedByICFIFromSameBlock</a> (const Instruction *Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the first ICFI of Insn's block exists and dominates Insn. <a href="#a6680bd71c9d15033f99c787b50d09e47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae08e452a5b7166504b29a1d9140e4525">isSpecialInstruction</a> (const Instruction *Insn) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A predicate that defines whether or not the instruction <span class="doxyComputerOutput">Insn</span> is considered special and needs to be tracked. <a href="#ae08e452a5b7166504b29a1d9140e4525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class allows to keep track on instructions with implicit control flow.</p>


<p>These are instructions that may not pass execution to their successors. For example, throwing calls and guards do not always do this. If we need to know for sure that some instruction is guaranteed to execute if the given block is reached, then we need to make sure that there is no implicit control flow instruction (ICFI) preceding it. For example, this check is required if we perform PRE moving non-speculable instruction to other place.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getFirstICFI() {#a462bb685cd45aed006cc467ccbcacd62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * llvm::ImplicitControlFlowTracking::getFirstICFI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the topmost instruction with implicit control flow from the given basic block.</p>


<p>Returns nullptr if there is no such instructions in the block.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#ac2ef5d23f007e4ce8845300f1d2dbf1d">llvm::InstructionPrecedenceTracking::getFirstSpecialInstruction</a>.</p>

</div>
</div>

### hasICF() {#acbe6442a02a15b138ff870eeeb6da50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImplicitControlFlowTracking::hasICF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if at least one instruction from the given basic block has implicit control flow.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#adcd15c92b5dc613f2de577182e4e04d9">llvm::InstructionPrecedenceTracking::hasSpecialInstructions</a>.</p>

</div>
</div>

### isDominatedByICFIFromSameBlock() {#a6680bd71c9d15033f99c787b50d09e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImplicitControlFlowTracking::isDominatedByICFIFromSameBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Insn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the first ICFI of Insn's block exists and dominates Insn.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#adeff4bfc41e787e8074a500fe3f2fbb7">llvm::InstructionPrecedenceTracking::isPreceededBySpecialInstruction</a>.</p>

</div>
</div>

### isSpecialInstruction() {#ae08e452a5b7166504b29a1d9140e4525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitControlFlowTracking::isSpecialInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Insn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A predicate that defines whether or not the instruction <span class="doxyComputerOutput">Insn</span> is considered special and needs to be tracked.</p>


<p>Implementing this method in children classes allows to implement tracking of implicit control flow, memory writing instructions or any other kinds of instructions we might be interested in.</p>


<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
