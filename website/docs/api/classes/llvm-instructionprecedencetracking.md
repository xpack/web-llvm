---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instructionprecedencetracking
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstructionPrecedenceTracking` Class



## Declaration

<div class="doxyDeclaration">
class llvm::InstructionPrecedenceTracking { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">llvm/Analysis/InstructionPrecedenceTracking.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking">ImplicitControlFlowTracking</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class allows to keep track on instructions with implicit control flow. <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorywritetracking">MemoryWriteTracking</a></td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee2ec060b8eacc68f09075f6a53d323">~InstructionPrecedenceTracking</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34fd9bb2702922bd9ac7b4974a9cb4bb">insertInstructionTo</a> (const Instruction *Inst, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notifies this tracking that we are going to insert a new instruction <span class="doxyComputerOutput">Inst</span> to the basic block <span class="doxyComputerOutput">BB</span>. <a href="#a34fd9bb2702922bd9ac7b4974a9cb4bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614d4e92df83b9df2bac960e656fb722">removeInstruction</a> (const Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notifies this tracking that we are going to remove the instruction <span class="doxyComputerOutput">Inst</span> It makes all necessary updates to internal caches to keep them consistent. <a href="#a614d4e92df83b9df2bac960e656fb722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd8fd10b417c6205bd128a3c660df4b">removeUsersOf</a> (const Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notifies this tracking that we are going to replace all uses of <span class="doxyComputerOutput">Inst</span>. <a href="#a2dd8fd10b417c6205bd128a3c660df4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19812b1271dc020c7338dc52ba36c46e">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidates all information from this tracking. <a href="#a19812b1271dc020c7338dc52ba36c46e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ef5d23f007e4ce8845300f1d2dbf1d">getFirstSpecialInstruction</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the topmost special instruction from the block <span class="doxyComputerOutput">BB</span>. <a href="#ac2ef5d23f007e4ce8845300f1d2dbf1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd15c92b5dc613f2de577182e4e04d9">hasSpecialInstructions</a> (const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff at least one instruction from the basic block <span class="doxyComputerOutput">BB</span> is special. <a href="#adcd15c92b5dc613f2de577182e4e04d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeff4bfc41e787e8074a500fe3f2fbb7">isPreceededBySpecialInstruction</a> (const Instruction *Insn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the first special instruction of <span class="doxyComputerOutput">Insn's</span> block exists and dominates <span class="doxyComputerOutput">Insn</span>. <a href="#adeff4bfc41e787e8074a500fe3f2fbb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad557cd72cd34de96e4d0bc67f4037643">isSpecialInstruction</a> (const Instruction *Insn) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A predicate that defines whether or not the instruction <span class="doxyComputerOutput">Insn</span> is considered special and needs to be tracked. <a href="#ad557cd72cd34de96e4d0bc67f4037643">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f6d6912144a72b7ed33a25bf6e2d85">fill</a> (const BasicBlock *BB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1268e6e0ddb66db22874ec31a50189">validate</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asserts that the cached info for <span class="doxyComputerOutput">BB</span> is up-to-date. <a href="#abc1268e6e0ddb66db22874ec31a50189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16087a4927ab66d8eec430f0c7e607a">validateAll</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asserts whether or not the contents of this tracking is up-to-date. <a href="#aa16087a4927ab66d8eec430f0c7e607a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2c70088753c1c2554d0fd6ba8294df">FirstSpecialInsts</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>


<div class="doxySectionDef">

## Protected Destructor

### \~InstructionPrecedenceTracking() {#a2ee2ec060b8eacc68f09075f6a53d323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InstructionPrecedenceTracking::~InstructionPrecedenceTracking ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a19812b1271dc020c7338dc52ba36c46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidates all information from this tracking.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>

</div>
</div>

### insertInstructionTo() {#a34fd9bb2702922bd9ac7b4974a9cb4bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::insertInstructionTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notifies this tracking that we are going to insert a new instruction <span class="doxyComputerOutput">Inst</span> to the basic block <span class="doxyComputerOutput">BB</span>.</p>


<p>It makes all necessary updates to internal caches to keep them consistent.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>Reference <a href="#ad557cd72cd34de96e4d0bc67f4037643">isSpecialInstruction</a>.</p>

</div>
</div>

### removeInstruction() {#a614d4e92df83b9df2bac960e656fb722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::removeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notifies this tracking that we are going to remove the instruction <span class="doxyComputerOutput">Inst</span> It makes all necessary updates to internal caches to keep them consistent.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>.</p>


<p>Referenced by <a href="#a2dd8fd10b417c6205bd128a3c660df4b">removeUsersOf</a>.</p>

</div>
</div>

### removeUsersOf() {#a2dd8fd10b417c6205bd128a3c660df4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::removeUsersOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notifies this tracking that we are going to replace all uses of <span class="doxyComputerOutput">Inst</span>.</p>


<p>It makes all necessary updates to internal caches to keep them consistent. Should typically be called before a RAUW.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a614d4e92df83b9df2bac960e656fb722">removeInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getFirstSpecialInstruction() {#ac2ef5d23f007e4ce8845300f1d2dbf1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * InstructionPrecedenceTracking::getFirstSpecialInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the topmost special instruction from the block <span class="doxyComputerOutput">BB</span>.</p>


<p>Returns nullptr if there is no special instructions in the block.</p>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp/#a4f4ce8caded0b75faf4ee91bb9c950c2">ExpensiveAsserts</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking/#a462bb685cd45aed006cc467ccbcacd62">llvm::ImplicitControlFlowTracking::getFirstICFI</a>, <a href="/web-llvm/docs/api/classes/llvm/memorywritetracking/#af0b69a5d42b625148101e8fdd653ebee">llvm::MemoryWriteTracking::getFirstMemoryWrite</a>, <a href="#adcd15c92b5dc613f2de577182e4e04d9">hasSpecialInstructions</a> and <a href="#adeff4bfc41e787e8074a500fe3f2fbb7">isPreceededBySpecialInstruction</a>.</p>

</div>
</div>

### hasSpecialInstructions() {#adcd15c92b5dc613f2de577182e4e04d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstructionPrecedenceTracking::hasSpecialInstructions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true iff at least one instruction from the basic block <span class="doxyComputerOutput">BB</span> is special.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>Reference <a href="#ac2ef5d23f007e4ce8845300f1d2dbf1d">getFirstSpecialInstruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking/#acbe6442a02a15b138ff870eeeb6da50b">llvm::ImplicitControlFlowTracking::hasICF</a> and <a href="/web-llvm/docs/api/classes/llvm/memorywritetracking/#a2cb3fb44d23476159e627032e6fd9d42">llvm::MemoryWriteTracking::mayWriteToMemory</a>.</p>

</div>
</div>

### isPreceededBySpecialInstruction() {#adeff4bfc41e787e8074a500fe3f2fbb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstructionPrecedenceTracking::isPreceededBySpecialInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Insn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true iff the first special instruction of <span class="doxyComputerOutput">Insn's</span> block exists and dominates <span class="doxyComputerOutput">Insn</span>.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a784097fca76abad9e815cf1692de79c4">llvm::Instruction::comesBefore</a>, <a href="#ac2ef5d23f007e4ce8845300f1d2dbf1d">getFirstSpecialInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking/#a6680bd71c9d15033f99c787b50d09e47">llvm::ImplicitControlFlowTracking::isDominatedByICFIFromSameBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/memorywritetracking/#a43d110285c732a61a66f2c91a6f02d2f">llvm::MemoryWriteTracking::isDominatedByMemoryWriteFromSameBlock</a>.</p>

</div>
</div>

### isSpecialInstruction() {#ad557cd72cd34de96e4d0bc67f4037643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::InstructionPrecedenceTracking::isSpecialInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Insn)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A predicate that defines whether or not the instruction <span class="doxyComputerOutput">Insn</span> is considered special and needs to be tracked.</p>


<p>Implementing this method in children classes allows to implement tracking of implicit control flow, memory writing instructions or any other kinds of instructions we might be interested in.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>


<p>Referenced by <a href="#a34fd9bb2702922bd9ac7b4974a9cb4bb">insertInstructionTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### fill() {#a22f6d6912144a72b7ed33a25bf6e2d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::fill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>

</div>
</div>

### validate() {#abc1268e6e0ddb66db22874ec31a50189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::validate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asserts that the cached info for <span class="doxyComputerOutput">BB</span> is up-to-date.</p>


<p>This helps to catch the usage error of accessing a block without properly invalidating after a previous transform.</p>


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>

</div>
</div>

### validateAll() {#aa16087a4927ab66d8eec430f0c7e607a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionPrecedenceTracking::validateAll ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asserts whether or not the contents of this tracking is up-to-date.</p>


<p>This helps to catch the usage error of accessing a block without properly invalidating after a previous transform.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionprecedencetracking-cpp">InstructionPrecedenceTracking.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FirstSpecialInsts {#a8d2c70088753c1c2554d0fd6ba8294df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, const Instruction *&gt; llvm::InstructionPrecedenceTracking::FirstSpecialInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionprecedencetracking-h">InstructionPrecedenceTracking.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
