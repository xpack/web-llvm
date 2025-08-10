---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCBranchCoalescing` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8333a5e76125bbe69af183e99c00eb">PPCBranchCoalescing</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae2b3027535582801166cef1673ecbc">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a2ae2b3027535582801166cef1673ecbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7b7a33fa713262053c514d1a30801a">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a2a7b7a33fa713262053c514d1a30801a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072a336f973a3de4daa8fe16e5b4570f">mergeCandidates</a> (CoalescingCandidateInfo &amp;SourceRegion, CoalescingCandidateInfo &amp;TargetRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the instructions from SourceRegion.BranchBlock, SourceRegion.BranchTargetBlock, and SourceRegion.FallThroughBlock into TargetRegion.BranchBlock, TargetRegion.BranchTargetBlock and TargetRegion.FallThroughBlock respectively. <a href="#a072a336f973a3de4daa8fe16e5b4570f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8661c8ac8b1cb3810a45d201972e5d5">canMoveToBeginning</a> (const MachineInstr &amp;MI, const MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks if MI can be moved to the beginning of the TargetMBB following PHI instructions. <a href="#aa8661c8ac8b1cb3810a45d201972e5d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd833dc91598d5a3c3f327b47b98a4cf">canMoveToEnd</a> (const MachineInstr &amp;MI, const MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks if MI can be moved to the end of the TargetMBB, immediately before the first terminator. <a href="#afd833dc91598d5a3c3f327b47b98a4cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481db3ca9a03829503a402a2318a27b1">canMerge</a> (CoalescingCandidateInfo &amp;SourceRegion, CoalescingCandidateInfo &amp;TargetRegion) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method determines whether the two coalescing candidates can be merged. <a href="#a481db3ca9a03829503a402a2318a27b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a11298ee3a7cfcfa678f8b9a3df20db">moveAndUpdatePHIs</a> (MachineBasicBlock *SourceRegionMBB, MachineBasicBlock *TargetRegionMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Moves ALL PHI instructions in SourceMBB to beginning of TargetMBB and update them to refer to the new block. <a href="#a2a11298ee3a7cfcfa678f8b9a3df20db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afba5986a2e44a080a9dddaef311b04ee">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#afba5986a2e44a080a9dddaef311b04ee">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5701bccfdebf41a67361e187fc26a8eb">initialize</a> (MachineFunction &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8537fa42c3064c2c1ae3e4efae6bd532">canCoalesceBranch</a> (CoalescingCandidateInfo &amp;Cand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the branch statement to determine if it can be coalesced. <a href="#a8537fa42c3064c2c1ae3e4efae6bd532">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674e4e8b91867f7bc8bf5b100738b5a5">identicalOperands</a> (ArrayRef&lt; MachineOperand &gt; OperandList1, ArrayRef&lt; MachineOperand &gt; OperandList2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the two operand lists are identical. <a href="#a674e4e8b91867f7bc8bf5b100738b5a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f748598b03c916b31ff4a11c764db6a">validateCandidates</a> (CoalescingCandidateInfo &amp;SourceRegion, CoalescingCandidateInfo &amp;TargetRegion) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method checks to ensure the two coalescing candidates follows the expected pattern required for coalescing. <a href="#a8f748598b03c916b31ff4a11c764db6a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce473afdeee3a8e6d9fd8d16710ea2b">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7561e0ce62fbc4a6ee86fd98759cc6ab">MPDT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a6b1b96bf5ce9d5584be16a4d9862a">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e564f35d0d55519b9f9e0193d2b4401">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a211cc96989f7db223bf7fc2e4df1a">ID</a> = 0</td>
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


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCBranchCoalescing() {#add8333a5e76125bbe69af183e99c00eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::PPCBranchCoalescing ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ae4a211cc96989f7db223bf7fc2e4df1a">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab244810713452481a92b477a5a9852b7">llvm::initializePPCBranchCoalescingPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9c813c2fc78ffd9ab828f345b6f37a80">llvm::createPPCBranchCoalescingPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canMerge() {#a481db3ca9a03829503a402a2318a27b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::canMerge (CoalescingCandidateInfo &amp; SourceRegion, CoalescingCandidateInfo &amp; TargetRegion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method determines whether the two coalescing candidates can be merged.</p>


<p>In order to be merged, all instructions must be able to</p>


<ol class="doxyList" type="1">
<li>Move to the beginning of the SourceRegion.BranchTargetBlock;</li>
<li>Move to the end of the TargetRegion.BranchBlock. Merging involves moving the instructions in the TargetRegion.BranchTargetBlock (also SourceRegion.BranchBlock).</li>
</ol>

<p>This function first try to move instructions from the TargetRegion.BranchTargetBlock down, to the beginning of the SourceRegion.BranchTargetBlock. This is not possible if any register defined in TargetRegion.BranchTargetBlock is used in a PHI node in the SourceRegion.BranchTargetBlock. In this case, check whether the statement can be moved up, to the end of the TargetRegion.BranchBlock (immediately before the branch statement). If it cannot move, then these blocks cannot be merged.</p>


<p>Note that there is no analysis for moving instructions past the fall-through blocks because they are confirmed to be empty. An assert is thrown if they are not.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceRegion</td>
<td class="doxyParamItemDescription"><p>The candidate to move statements from</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetRegion</td>
<td class="doxyParamItemDescription"><p>The candidate to move statements to</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all instructions in SourceRegion.BranchBlock can be merged into a block in TargetRegion, false otherwise.</p></dd>
</dl>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="#aa8661c8ac8b1cb3810a45d201972e5d5">canMoveToBeginning</a>, <a href="#afd833dc91598d5a3c3f327b47b98a4cf">canMoveToEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7dc7faaab4856b8f0014b8283e26c7b">llvm::MachineBasicBlock::getFirstNonPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a172e7bd9150eb0519ef04c796086f93d">llvm::MachineBasicBlock::instr_begin</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#afba5986a2e44a080a9dddaef311b04ee">runOnMachineFunction</a>.</p>

</div>
</div>

### canMoveToBeginning() {#aa8661c8ac8b1cb3810a45d201972e5d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::canMoveToBeginning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TargetMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function checks if MI can be moved to the beginning of the TargetMBB following PHI instructions.</p>


<p>A MI instruction can be moved to beginning of the TargetMBB if there are no uses of it within the TargetMBB PHI nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MI</td>
<td class="doxyParamItemDescription"><p>the machine instruction to move.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetMBB</td>
<td class="doxyParamItemDescription"><p>the machine basic block to move to</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is safe to move MI to beginning of TargetMBB, false otherwise.</p></dd>
</dl>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a481db3ca9a03829503a402a2318a27b1">canMerge</a>.</p>

</div>
</div>

### canMoveToEnd() {#afd833dc91598d5a3c3f327b47b98a4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::canMoveToEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TargetMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function checks if MI can be moved to the end of the TargetMBB, immediately before the first terminator.</p>


<p>A MI instruction can be moved to then end of the TargetMBB if no PHI node defines what MI uses within it's own MBB.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] MI</td>
<td class="doxyParamItemDescription"><p>the machine instruction to move.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetMBB</td>
<td class="doxyParamItemDescription"><p>the machine basic block to move to</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it is safe to move MI to end of TargetMBB, false otherwise.</p></dd>
</dl>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad43bf1af480830a4d6604e969e3f38e9">llvm::MachineInstr::isPHI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a481db3ca9a03829503a402a2318a27b1">canMerge</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a2ae2b3027535582801166cef1673ecbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#a2a7b7a33fa713262053c514d1a30801a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::getPassName ()</td>
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


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### mergeCandidates() {#a072a336f973a3de4daa8fe16e5b4570f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::mergeCandidates (CoalescingCandidateInfo &amp; SourceRegion, CoalescingCandidateInfo &amp; TargetRegion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the instructions from SourceRegion.BranchBlock, SourceRegion.BranchTargetBlock, and SourceRegion.FallThroughBlock into TargetRegion.BranchBlock, TargetRegion.BranchTargetBlock and TargetRegion.FallThroughBlock respectively.</p>


<p>The successors for blocks in TargetRegion will be updated to use the successors from blocks in SourceRegion. Finally, the blocks in SourceRegion will be removed from the function.</p>


<p>A region consists of a BranchBlock, a FallThroughBlock, and a BranchTargetBlock. Branch coalesce works on patterns where the TargetRegion's BranchTargetBlock must also be the SourceRegions's BranchBlock.</p>


<p>Before mergeCandidates:</p>


<p>+------------------------—+ | TargetRegion.BranchBlock | +------------------------—+ / | / +-----------------------------—+ | | TargetRegion.FallThroughBlock | \ +-----------------------------—+ \ | +-------------------------------—+ | TargetRegion.BranchTargetBlock | | SourceRegion.BranchBlock | +-------------------------------—+ / | / +-----------------------------—+ | | SourceRegion.FallThroughBlock | \ +-----------------------------—+ \ | +-------------------------------—+ | SourceRegion.BranchTargetBlock | +-------------------------------—+</p>


<p>After mergeCandidates:</p>


<p>+--------------------------—+ | TargetRegion.BranchBlock | | SourceRegion.BranchBlock | +--------------------------—+ / | / +------------------------------—+ | | TargetRegion.FallThroughBlock | | | SourceRegion.FallThroughBlock | \ +------------------------------—+ \ | +-------------------------------—+ | SourceRegion.BranchTargetBlock | +-------------------------------—+</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceRegion</td>
<td class="doxyParamItemDescription"><p>The candidate to move blocks from</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetRegion</td>
<td class="doxyParamItemDescription"><p>The candidate to move blocks to</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range/#af5a020bd9dd7bc8487dd53ce443fdd8f">llvm::iterator_range&lt; IteratorT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range/#aa0344673da91896d39f1b35755ee5d4e">llvm::iterator_range&lt; IteratorT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac421fe6513e43aedbba712e4a981744e">llvm::MachineBasicBlock::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7dc7faaab4856b8f0014b8283e26c7b">llvm::MachineBasicBlock::getFirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5891cdb51072f67e65f7ebd9be1205e7">llvm::MachineInstr::isBranch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a2a11298ee3a7cfcfa678f8b9a3df20db">moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7114bb360b922025e7a4fec442676db">llvm::MachineBasicBlock::removeSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab9a54fdc7456ee97cb54ff30d625b6b7">llvm::MachineBasicBlock::ReplaceUsesOfBlockWith</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad56ff27a502cd519f9aaf5cc028b4ea5">llvm::MachineBasicBlock::terminators</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="#afba5986a2e44a080a9dddaef311b04ee">runOnMachineFunction</a>.</p>

</div>
</div>

### moveAndUpdatePHIs() {#a2a11298ee3a7cfcfa678f8b9a3df20db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCBranchCoalescing::moveAndUpdatePHIs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SourceMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TargetMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Moves ALL PHI instructions in SourceMBB to beginning of TargetMBB and update them to refer to the new block.</p>


<p>PHI node ordering cannot be assumed so it does not matter where the PHI instructions are moved to in TargetMBB.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceMBB</td>
<td class="doxyParamItemDescription"><p>block to move PHI instructions from</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetMBB</td>
<td class="doxyParamItemDescription"><p>block to move PHI instructions to</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7dc7faaab4856b8f0014b8283e26c7b">llvm::MachineBasicBlock::getFirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a98e9c9e8ef7cbb6c4aa89a38f21decfa">llvm::MachineOperand::setMBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>.</p>


<p>Referenced by <a href="#a072a336f973a3de4daa8fe16e5b4570f">mergeCandidates</a>.</p>

</div>
</div>

### runOnMachineFunction() {#afba5986a2e44a080a9dddaef311b04ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a481db3ca9a03829503a402a2318a27b1">canMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d931af4280c80a837ee409eb85104f7">llvm::MachineFunction::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#acc3c7c3ac8c5d35c59cea8e782926620">llvm::MachineFunction::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a072a336f973a3de4daa8fe16e5b4570f">mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8efc9cbc802adc2bb2673b4ba6308869">llvm::MachineFunction::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canCoalesceBranch() {#a8537fa42c3064c2c1ae3e4efae6bd532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::canCoalesceBranch (CoalescingCandidateInfo &amp; Cand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the branch statement to determine if it can be coalesced.</p>


<p>This method analyses the branch statement for the given candidate to determine if it can be coalesced. If the branch can be coalesced, then the BranchTargetBlock and the FallThroughBlock are recorded in the specified Candidate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] Cand</td>
<td class="doxyParamItemDescription"><p>The coalescing candidate to analyze</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if and only if the branch can be coalesced, false otherwise</p></dd>
</dl>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### identicalOperands() {#a674e4e8b91867f7bc8bf5b100738b5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::identicalOperands (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; OpList1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; OpList2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the two operand lists are identical.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OpList1</td>
<td class="doxyParamItemDescription"><p>operand list</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OpList2</td>
<td class="doxyParamItemDescription"><p>operand list</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if and only if the operands lists are identical</p></dd>
</dl>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### initialize() {#a5701bccfdebf41a67361e187fc26a8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCBranchCoalescing::initialize (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### validateCandidates() {#a8f748598b03c916b31ff4a11c764db6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCBranchCoalescing::validateCandidates (CoalescingCandidateInfo &amp; SourceRegion, CoalescingCandidateInfo &amp; TargetRegion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method checks to ensure the two coalescing candidates follows the expected pattern required for coalescing.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SourceRegion</td>
<td class="doxyParamItemDescription"><p>The candidate to move statements from</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] TargetRegion</td>
<td class="doxyParamItemDescription"><p>The candidate to move statements to</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all instructions in SourceRegion.BranchBlock can be merged into a block in TargetRegion; false otherwise.</p></dd>
</dl>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MDT {#a6ce473afdeee3a8e6d9fd8d16710ea2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### MPDT {#a7561e0ce62fbc4a6ee86fd98759cc6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree* anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::MPDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### MRI {#a4e564f35d0d55519b9f9e0193d2b4401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

### TII {#aa4a6b1b96bf5ce9d5584be16a4d9862a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ae4a211cc96989f7db223bf7fc2e4df1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char PPCBranchCoalescing::ID = 0</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a>.</p>


<p>Referenced by <a href="#add8333a5e76125bbe69af183e99c00eb">PPCBranchCoalescing</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchcoalescing-cpp">PPCBranchCoalescing.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
