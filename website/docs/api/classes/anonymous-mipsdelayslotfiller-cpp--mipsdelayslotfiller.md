---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipsdelayslotfiller-cpp-/mipsdelayslotfiller
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsDelaySlotFiller` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8e20cb5354225f3c488f4eaac4ea1d">MipsDelaySlotFiller</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01dfe2325853db6a928d5ae0e63b1dc">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#ad01dfe2325853db6a928d5ae0e63b1dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c2348e77ef6457d3fe5e9293f8b82e">runOnMachineFunction</a> (MachineFunction &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#ad8c2348e77ef6457d3fe5e9293f8b82e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2214ef0e9d9e5faa984b84304ac8886">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94dc249ca8d34e16710b6a150efe00d9">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a94dc249ca8d34e16710b6a150efe00d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12bbaf2ff79b0813af362fb00de513b2">searchRange</a> (MachineBasicBlock &amp;MBB, IterTy Begin, IterTy End, RegDefsUses &amp;RegDU, InspectMemInstr &amp;IM, Iter Slot, IterTy &amp;Filler) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad685353b92d23c91a67ad77cbace11fe">runOnMachineBasicBlock</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineBasicBlock - Fill in delay slots for the given basic block. <a href="#ad685353b92d23c91a67ad77cbace11fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#afb20d49071e674b831046b73d9208bbd">Iter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86e99da1a357a85ac3f41158d00d43b">replaceWithCompactBranch</a> (MachineBasicBlock &amp;MBB, Iter Branch, const DebugLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab392f9e22fe5810af52f728b27f1b476">delayHasHazard</a> (const MachineInstr &amp;Candidate, RegDefsUses &amp;RegDU, InspectMemInstr &amp;IM) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks if it is valid to move Candidate to the delay slot and returns true if it isn't. <a href="#ab392f9e22fe5810af52f728b27f1b476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a12bbaf2ff79b0813af362fb00de513b2">searchRange</a> (MachineBasicBlock &amp;MBB, IterTy Begin, IterTy End, RegDefsUses &amp;RegDU, InspectMemInstr &amp;IM, Iter Slot, IterTy &amp;Filler) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function searches range [Begin, End) for an instruction that can be moved to the delay slot. <a href="#a12bbaf2ff79b0813af362fb00de513b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879f4e0bb71b4be6a577f276ba56494e">searchBackward</a> (MachineBasicBlock &amp;MBB, MachineInstr &amp;Slot) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function searches in the backward direction for an instruction that can be moved to the delay slot. <a href="#a879f4e0bb71b4be6a577f276ba56494e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9e466b18662423f90edf7ca97f1d36">searchForward</a> (MachineBasicBlock &amp;MBB, Iter Slot) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function searches MBB in the forward direction for an instruction that can be moved to the delay slot. <a href="#a2e9e466b18662423f90edf7ca97f1d36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45fa82666cfeea10e523da110627ca7">searchSuccBBs</a> (MachineBasicBlock &amp;MBB, Iter Slot) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function searches one of MBB's successor blocks for an instruction that can be moved to the delay slot and inserts clones of the instruction into the successor's predecessor blocks. <a href="#af45fa82666cfeea10e523da110627ca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16b3f63f55386f45f11d6fe8c21d648c">selectSuccBB</a> (MachineBasicBlock &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pick a successor block of MBB. <a href="#a16b3f63f55386f45f11d6fe8c21d648c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#aabfa34ab3ab92062a24aaf2a4da8f1cb">MipsInstrInfo::BranchType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e354a2129f84fe94ece0c6d30f0885e">getBranch</a> (MachineBasicBlock &amp;MBB, const MachineBasicBlock &amp;Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function analyzes MBB and returns an instruction with an unoccupied slot that branches to Dst. <a href="#a8e354a2129f84fe94ece0c6d30f0885e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f9b8ee22849081d3ccbd02fd1fdf21d">examinePred</a> (MachineBasicBlock &amp;Pred, const MachineBasicBlock &amp;Succ, RegDefsUses &amp;RegDU, bool &amp;HasMultipleSuccs, BB2BrMap &amp;BrMap) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine Pred and see if it is possible to insert an instruction into one of its branches delay slot or its end. <a href="#a5f9b8ee22849081d3ccbd02fd1fdf21d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98fb10304f35460fa5c3704657b7cf22">terminateSearch</a> (const MachineInstr &amp;Candidate) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed4b321b531bcd1cf67f7d90a6d4744">TM</a> = nullptr</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a41a642ed5ae6bcbde10bd308a01ca2">ID</a> = 0</td>
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


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsDelaySlotFiller() {#a3b8e20cb5354225f3c488f4eaac4ea1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::MipsDelaySlotFiller ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a5a41a642ed5ae6bcbde10bd308a01ca2">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d2dd614e045c8efc6bc2899c68b7155">llvm::initializeMipsDelaySlotFillerPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a94dc249ca8d34e16710b6a150efe00d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#ad01dfe2325853db6a928d5ae0e63b1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### getRequiredProperties() {#ac2214ef0e9d9e5faa984b84304ac8886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::getRequiredProperties ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#ad8c2348e77ef6457d3fe5e9293f8b82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### searchRange() {#a12bbaf2ff79b0813af362fb00de513b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, IterTy Begin, IterTy End, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses">RegDefsUses</a> &amp; RegDU, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/inspectmeminstr">InspectMemInstr</a> &amp; IM, <a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#afb20d49071e674b831046b73d9208bbd">Iter</a> Slot, IterTy &amp; Filler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6c1e1834f81c5647f7605177b93587">llvm::baseRegNeedsLoadStoreMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a4870c381b12fc206ac1aee9b705325b7">llvm::MipsSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a856ec36e844545656044c24f78dbcbbd">llvm::MipsSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a6c595885100ac9cf852be70151cc51d6">llvm::MipsSubtarget::hasMips32</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a6709172c1e9c3deca20041dad9b39dbf">llvm::MipsSubtarget::hasMips5</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a102ee3949228f2c8c1902c3ab7b70efc">llvm::MipsSubtarget::inMicroMipsMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24f4ef3173f04abe9e43834cfa85de83">llvm::isBasePlusOffsetMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips-h/#a644bb3cf996365271debaf13502ddc17">IsMFLOMFHI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#ade22344fec068aba4bd0d1109d98140d">llvm::MipsSubtarget::isTargetNaCl</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#a47c8a030926eca62aae974bb55ecd995">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::update</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### delayHasHazard() {#ab392f9e22fe5810af52f728b27f1b476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::delayHasHazard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Candidate, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses">RegDefsUses</a> &amp; RegDU, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/inspectmeminstr">InspectMemInstr</a> &amp; IM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function checks if it is valid to move Candidate to the delay slot and returns true if it isn't.</p>


<p>It also updates memory and register dependence information.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### examinePred() {#a5f9b8ee22849081d3ccbd02fd1fdf21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::examinePred (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Succ, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses">RegDefsUses</a> &amp; RegDU, bool &amp; HasMultipleSuccs, <a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#ae5263fa70f24780d89920d691b59a38f">BB2BrMap</a> &amp; BrMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examine Pred and see if it is possible to insert an instruction into one of its branches delay slot or its end.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### getBranch() {#a8e354a2129f84fe94ece0c6d30f0885e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MipsInstrInfo::BranchType, MachineInstr * &gt; MipsDelaySlotFiller::getBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function analyzes MBB and returns an instruction with an unoccupied slot that branches to Dst.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### replaceWithCompactBranch() {#ad86e99da1a357a85ac3f41158d00d43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iter MipsDelaySlotFiller::replaceWithCompactBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#afb20d49071e674b831046b73d9208bbd">Iter</a> Branch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### runOnMachineBasicBlock() {#ad685353b92d23c91a67ad77cbace11fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::runOnMachineBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnMachineBasicBlock - Fill in delay slots for the given basic block.</p>


<p>We assume there is only one delay slot per delayed instruction.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### searchBackward() {#a879f4e0bb71b4be6a577f276ba56494e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::searchBackward (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function searches in the backward direction for an instruction that can be moved to the delay slot.</p>


<p>Returns true on success.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### searchForward() {#a2e9e466b18662423f90edf7ca97f1d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::searchForward (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#afb20d49071e674b831046b73d9208bbd">Iter</a> Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function searches MBB in the forward direction for an instruction that can be moved to the delay slot.</p>


<p>Returns true on success.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### searchRange() {#a12bbaf2ff79b0813af362fb00de513b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::searchRange (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, IterTy Begin, IterTy End, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses">RegDefsUses</a> &amp; RegDU, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/inspectmeminstr">InspectMemInstr</a> &amp; IM, <a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#afb20d49071e674b831046b73d9208bbd">Iter</a> Slot, IterTy &amp; Filler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function searches range [Begin, End) for an instruction that can be moved to the delay slot.</p>


<p>Returns true on success.</p>


<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### searchSuccBBs() {#af45fa82666cfeea10e523da110627ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::searchSuccBBs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/namespaces/anonymous-mipsdelayslotfiller-cpp-/#afb20d49071e674b831046b73d9208bbd">Iter</a> Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function searches one of MBB's successor blocks for an instruction that can be moved to the delay slot and inserts clones of the instruction into the successor's predecessor blocks.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### selectSuccBB() {#a16b3f63f55386f45f11d6fe8c21d648c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MipsDelaySlotFiller::selectSuccBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pick a successor block of MBB.</p>


<p>Return NULL if MBB doesn't have a successor block that is not a landing pad.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

### terminateSearch() {#a98fb10304f35460fa5c3704657b7cf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsDelaySlotFiller::terminateSearch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Candidate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TM {#a9ed4b321b531bcd1cf67f7d90a6d4744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* anonymous{MipsDelaySlotFiller.cpp}::MipsDelaySlotFiller::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a5a41a642ed5ae6bcbde10bd308a01ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char MipsDelaySlotFiller::ID = 0</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a>.</p>


<p>Referenced by <a href="#a3b8e20cb5354225f3c488f4eaac4ea1d">MipsDelaySlotFiller</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp">MipsDelaySlotFiller.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
