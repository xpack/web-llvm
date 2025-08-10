---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/icfloopsafetyinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ICFLoopSafetyInfo` Class

<p>This implementation of <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> use <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking">ImplicitControlFlowTracking</a> to give precise answers on "may throw" queries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ICFLoopSafetyInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Captures loop safety information. <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c89300129b6640ff5930d605c4f2b3e">blockMayThrow</a> (const BasicBlock *BB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the block <span class="doxyComputerOutput">BB</span> potentially may throw exception. <a href="#a5c89300129b6640ff5930d605c4f2b3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac037c7db5068a141e231cab8b2daeef2">anyBlockMayThrow</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff any block of the loop for which this info is contains an instruction that may throw or otherwise exit abnormally. <a href="#ac037c7db5068a141e231cab8b2daeef2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2badb4637a1c884bebc80828feac0a">computeLoopSafetyInfo</a> (const Loop *CurLoop) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes safety information for a loop checks loop body &amp; header for the possibility of may throw exception, it takes <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> and loop as argument. <a href="#aca2badb4637a1c884bebc80828feac0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40701961745d6467fa8e23b1e451c12">isGuaranteedToExecute</a> (const Instruction &amp;Inst, const DominatorTree *DT, const Loop *CurLoop) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction in a loop is guaranteed to execute at least once (under the assumption that the loop is entered). <a href="#ab40701961745d6467fa8e23b1e451c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639eff65ee8e468b3891fbe67db54788">doesNotWriteMemoryBefore</a> (const BasicBlock *BB, const Loop *CurLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we could not execute a memory-modifying instruction before we enter <span class="doxyComputerOutput">BB</span> under assumption that <span class="doxyComputerOutput">CurLoop</span> is entered. <a href="#a639eff65ee8e468b3891fbe67db54788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d2c0ed240c8f7f889eedc466380a0f">doesNotWriteMemoryBefore</a> (const Instruction &amp;I, const Loop *CurLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we could not execute a memory-modifying instruction before we execute <span class="doxyComputerOutput">I</span> under assumption that <span class="doxyComputerOutput">CurLoop</span> is entered. <a href="#ab5d2c0ed240c8f7f889eedc466380a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf635590a74bf4fdc2822b6f877afb7">insertInstructionTo</a> (const Instruction *Inst, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the safety info that we are planning to insert a new instruction <span class="doxyComputerOutput">Inst</span> into the basic block <span class="doxyComputerOutput">BB</span>. <a href="#acaf635590a74bf4fdc2822b6f877afb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2d5ff012ca10eb45c8b8cbca188dd6">removeInstruction</a> (const Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform safety info that we are planning to remove the instruction <span class="doxyComputerOutput">Inst</span> from its block. <a href="#aac2d5ff012ca10eb45c8b8cbca188dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfece8d3a50da05c2bc248b2699e7307">MayThrow</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking">ImplicitControlFlowTracking</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad824a59b6ccab26e696e1b6eb24d33b3">ICF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorywritetracking">MemoryWriteTracking</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13cd1b99980ddac07a0ffbf6bf6c4e1d">MW</a></td>
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

<p>This implementation of <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> use <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking">ImplicitControlFlowTracking</a> to give precise answers on "may throw" queries.</p>


<p>This implementation uses cache that should be invalidated by calling the methods insertInstructionTo and removeInstruction whenever we modify a basic block's contents by adding or removing instructions.</p>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### anyBlockMayThrow() {#ac037c7db5068a141e231cab8b2daeef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICFLoopSafetyInfo::anyBlockMayThrow ()</td>
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

<p>Returns true iff any block of the loop for which this info is contains an instruction that may throw or otherwise exit abnormally.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>.</p>

</div>
</div>

### blockMayThrow() {#a5c89300129b6640ff5930d605c4f2b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICFLoopSafetyInfo::blockMayThrow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Returns true iff the block <span class="doxyComputerOutput">BB</span> potentially may throw exception.</p>


<p>It can be false-positive in cases when we want to avoid complex analysis.</p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>

</div>
</div>

### computeLoopSafetyInfo() {#aca2badb4637a1c884bebc80828feac0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ICFLoopSafetyInfo::computeLoopSafetyInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
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

<p>Computes safety information for a loop checks loop body &amp; header for the possibility of may throw exception, it takes <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> and loop as argument.</p>


<p>Updates safety information in <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> argument. Note: This is defined to clear and reinitialize an already initialized <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a>. Some callers rely on this fact.</p>


<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a> and <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a183e3a3a68925c5689cd2149c940f59e">llvm::LoopSafetyInfo::computeBlockColors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a81f9271273f74a220003075573119a05">shouldInsertFreeze</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### doesNotWriteMemoryBefore() {#a639eff65ee8e468b3891fbe67db54788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICFLoopSafetyInfo::doesNotWriteMemoryBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we could not execute a memory-modifying instruction before we enter <span class="doxyComputerOutput">BB</span> under assumption that <span class="doxyComputerOutput">CurLoop</span> is entered.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a0f2532bb6e482a8f04b68585b8cfc032">collectTransitivePredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>.</p>


<p>Referenced by <a href="#ab5d2c0ed240c8f7f889eedc466380a0f">doesNotWriteMemoryBefore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>.</p>

</div>
</div>

### doesNotWriteMemoryBefore() {#ab5d2c0ed240c8f7f889eedc466380a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICFLoopSafetyInfo::doesNotWriteMemoryBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we could not execute a memory-modifying instruction before we execute <span class="doxyComputerOutput">I</span> under assumption that <span class="doxyComputerOutput">CurLoop</span> is entered.</p>

<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="#a639eff65ee8e468b3891fbe67db54788">doesNotWriteMemoryBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### insertInstructionTo() {#acaf635590a74bf4fdc2822b6f877afb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ICFLoopSafetyInfo::insertInstructionTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inform the safety info that we are planning to insert a new instruction <span class="doxyComputerOutput">Inst</span> into the basic block <span class="doxyComputerOutput">BB</span>.</p>


<p>It will make all cache updates to keep it correct after this insertion.</p>


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a22d7cc599c50e811dff1546c5ccb8794">moveInstructionBefore</a>.</p>

</div>
</div>

### isGuaranteedToExecute() {#ab40701961745d6467fa8e23b1e451c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICFLoopSafetyInfo::isGuaranteedToExecute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
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

<p>Returns true if the instruction in a loop is guaranteed to execute at least once (under the assumption that the loop is entered).</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a0937bbe895c7ed05d32c861b0f9e0f97">llvm::LoopSafetyInfo::allLoopPathsLeadToBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a3a3a3183a327e1186dbe900032390ec6">hoist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a81f9271273f74a220003075573119a05">shouldInsertFreeze</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### removeInstruction() {#aac2d5ff012ca10eb45c8b8cbca188dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ICFLoopSafetyInfo::removeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inform safety info that we are planning to remove the instruction <span class="doxyComputerOutput">Inst</span> from its block.</p>


<p>It will make all cache updates to keep it correct after this removal.</p>


<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#ab0cfc793d55940eac67854827dd365e9">eraseInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a22d7cc599c50e811dff1546c5ccb8794">moveInstructionBefore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ICF {#ad824a59b6ccab26e696e1b6eb24d33b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplicitControlFlowTracking llvm::ICFLoopSafetyInfo::ICF</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### MayThrow {#acfece8d3a50da05c2bc248b2699e7307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICFLoopSafetyInfo::MayThrow = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### MW {#a13cd1b99980ddac07a0ffbf6bf6c4e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryWriteTracking llvm::ICFLoopSafetyInfo::MW</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
