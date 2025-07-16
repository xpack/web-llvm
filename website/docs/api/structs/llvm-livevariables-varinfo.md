---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/livevariables/varinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarInfo` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> - This represents the regions where a virtual register is live in the program. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LiveVariables::VarInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e808b535590177bb00545b77a324288">removeKill</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeKill - Delete a kill corresponding to the specified machine instruction. <a href="#a1e808b535590177bb00545b77a324288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935158aa13ae361427aa4c76d40693a0">findKill</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>findKill - Find a kill instruction in MBB. Return NULL if none is found. <a href="#a935158aa13ae361427aa4c76d40693a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade24291007dd6f2b3c90c4323499d7eb">isLiveIn</a> (const MachineBasicBlock &amp;MBB, Register Reg, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLiveIn - Is Reg live in to MBB? <a href="#ade24291007dd6f2b3c90c4323499d7eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3daa26ce0a5bd5063ac74011e2e82d4">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578f01f3e0679351d97facbba44c583e">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparsebitvector">SparseBitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76321b20db4feab750d85c2329cfcbc6">AliveBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AliveBlocks - Set of blocks in which this value is alive completely through. <a href="#a76321b20db4feab750d85c2329cfcbc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c816771eca7465f5e3e0bb6624ad88">Kills</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kills - List of MachineInstruction's which are the last use of this virtual register (kill it) in their basic block. <a href="#a65c816771eca7465f5e3e0bb6624ad88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> - This represents the regions where a virtual register is live in the program.</p>


<p>We represent this with three different pieces of information: the set of blocks in which the instruction is live throughout, the set of blocks in which the instruction is actually used, and the set of non-phi instructions that are the last users of the value.</p>


<p>In the common case where a value is defined and killed in the same block, There is one killing instruction, and AliveBlocks is empty.</p>


<p>Otherwise, the value is live out of the block. If the value is live throughout any blocks, these blocks are listed in AliveBlocks. Blocks where the liveness range ends are not included in AliveBlocks, instead being captured by the Kills set. In these blocks, the value is live into the block (unless the value is defined and killed in the same block) and lives until the specified instruction. Note that there cannot ever be a value whose Kills set contains two instructions from the same basic block.</p>


<p>PHI nodes complicate things a bit. If a PHI node is the last user of a value in one of its predecessor blocks, it is not listed in the kills set, but does include the predecessor block in the AliveBlocks set (unless that block also defines the value). This leads to the (perfectly sensical) situation where a value is defined in a block, and the last use is a phi node in the successor. In this case, AliveBlocks is empty (the value is not live across any blocks) and Kills is empty (phi nodes are not included). This is sensical because the value must be live to the end of the block, but is not live in any successor blocks.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#a578f01f3e0679351d97facbba44c583e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveVariables::VarInfo::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a78798d8de583a196655b3cfb347da991">llvm::LiveVariables::print</a>.</p>

</div>
</div>

### findKill() {#a935158aa13ae361427aa4c76d40693a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * LiveVariables::VarInfo::findKill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>findKill - Find a kill instruction in MBB. Return NULL if none is found.</p>

<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="#a65c816771eca7465f5e3e0bb6624ad88">Kills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ade24291007dd6f2b3c90c4323499d7eb">isLiveIn</a>.</p>

</div>
</div>

### isLiveIn() {#ade24291007dd6f2b3c90c4323499d7eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveVariables::VarInfo::isLiveIn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isLiveIn - Is Reg live in to MBB?</p>


<p>This means that Reg is live through MBB, or it is killed in MBB. If Reg is only used by PHI instructions in MBB, it is not considered live in.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="#a76321b20db4feab750d85c2329cfcbc6">AliveBlocks</a>, <a href="#a935158aa13ae361427aa4c76d40693a0">findKill</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab47a3d3cac0564876929e77389dbe569">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectWaterfallCandidateRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a87536d29ad236f911a1e72dd210f9305">llvm::LiveVariables::isLiveIn</a>.</p>

</div>
</div>

### print() {#ac3daa26ce0a5bd5063ac74011e2e82d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::VarInfo::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="#a76321b20db4feab750d85c2329cfcbc6">AliveBlocks</a> and <a href="#a65c816771eca7465f5e3e0bb6624ad88">Kills</a>.</p>

</div>
</div>

### removeKill() {#a1e808b535590177bb00545b77a324288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveVariables::VarInfo::removeKill (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>removeKill - Delete a kill corresponding to the specified machine instruction.</p>


<p>Returns true if there was a kill corresponding to this instruction, false otherwise.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a65c816771eca7465f5e3e0bb6624ad88">Kills</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a536d28604beba413c49c1f731df008a7">llvm::LiveVariables::removeVirtualRegistersKilled</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AliveBlocks {#a76321b20db4feab750d85c2329cfcbc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseBitVector llvm::LiveVariables::VarInfo::AliveBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AliveBlocks - Set of blocks in which this value is alive completely through.</p>


<p>This is a bit set which uses the basic block number as an index.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afbcff91139fc89e3e8c0dda857e7b128">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afc347ae9e7fcba69b04162d7b4a73635">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a7339056d25e6a6d7d1525f2ac0d1fe69">llvm::LiveVariables::HandleVirtRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#ac7e33b16879b183b0a9058363e2061de">llvm::LiveVariables::HandleVirtRegUse</a>, <a href="#ade24291007dd6f2b3c90c4323499d7eb">isLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a296cf971c4bc03d1b469f52b687661db">llvm::LiveVariables::MarkVirtRegAliveInBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a86f2353949000eecd69fbbe3c669efc4">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeLiveRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#aa35ddcfd60c7c4587ea25cb27e25968e">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeWaterfallLiveRange</a>, <a href="#ac3daa26ce0a5bd5063ac74011e2e82d4">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ad445b6093f4c4a8237493928b1a7c6f9">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::updateLiveRangeInElseRegion</a> and <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a05ac0dbbd44f86b9fe34282e8109c1ee">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::updateLiveRangeInThenRegion</a>.</p>

</div>
</div>

### Kills {#a65c816771eca7465f5e3e0bb6624ad88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr*&gt; llvm::LiveVariables::VarInfo::Kills</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kills - List of MachineInstruction's which are the last use of this virtual register (kill it) in their basic block.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a722a7eaa41e03a18392be831f831627d">llvm::LiveVariables::addVirtualRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#ae58f90c0c07a77319dd769a8588a0fa7">llvm::LiveVariables::addVirtualRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="#a935158aa13ae361427aa4c76d40693a0">findKill</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a7339056d25e6a6d7d1525f2ac0d1fe69">llvm::LiveVariables::HandleVirtRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#ac7e33b16879b183b0a9058363e2061de">llvm::LiveVariables::HandleVirtRegUse</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a296cf971c4bc03d1b469f52b687661db">llvm::LiveVariables::MarkVirtRegAliveInBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#aa35ddcfd60c7c4587ea25cb27e25968e">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeWaterfallLiveRange</a>, <a href="#ac3daa26ce0a5bd5063ac74011e2e82d4">print</a>, <a href="#a1e808b535590177bb00545b77a324288">removeKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ad445b6093f4c4a8237493928b1a7c6f9">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::updateLiveRangeInElseRegion</a> and <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a05ac0dbbd44f86b9fe34282e8109c1ee">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::updateLiveRangeInThenRegion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
