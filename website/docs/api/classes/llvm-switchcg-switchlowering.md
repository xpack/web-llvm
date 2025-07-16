---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/switchcg/switchlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SwitchLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SwitchCG::SwitchLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">llvm/CodeGen/SwitchLoweringUtils.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/sdagswitchlowering">SDAGSwitchLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea060a45dbec9e1066e5af56efb6d419">SwitchLowering</a> (FunctionLoweringInfo &amp;funcinfo)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d041eb1a9bb170de682e9b028a0bd58">~SwitchLowering</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2206b9896f6a294438739b86357af9c">init</a> (const TargetLowering &amp;tli, const TargetMachine &amp;tm, const DataLayout &amp;dl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41add37692675e7e74358acc1483f168">findJumpTables</a> (CaseClusterVector &amp;Clusters, const SwitchInst *SI, std::optional&lt; SDLoc &gt; SL, MachineBasicBlock *DefaultMBB, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae706b72bcadad3acf12a239b257aabc6">buildJumpTable</a> (const CaseClusterVector &amp;Clusters, unsigned First, unsigned Last, const SwitchInst *SI, const std::optional&lt; SDLoc &gt; &amp;SL, MachineBasicBlock *DefaultMBB, CaseCluster &amp;JTCluster)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5de88dc9568b784876478e316042ba6">findBitTestClusters</a> (CaseClusterVector &amp;Clusters, const SwitchInst *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225bed9cd6803933d859e79619abc590">buildBitTests</a> (CaseClusterVector &amp;Clusters, unsigned First, unsigned Last, const SwitchInst *SI, CaseCluster &amp;BTCluster)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a bit test cluster from Clusters[First..Last]. <a href="#a225bed9cd6803933d859e79619abc590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4222a54657e712a02c19875dd7e0d60">addSuccessorWithProb</a> (MachineBasicBlock *Src, MachineBasicBlock *Dst, BranchProbability Prob=BranchProbability::getUnknown())=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350ee9bc2296e756148f478ba9e850e0">caseClusterRank</a> (const CaseCluster &amp;CC, CaseClusterIt First, CaseClusterIt Last)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the rank by weight of CC in [First,Last]. <a href="#a350ee9bc2296e756148f478ba9e850e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/switchcg/switchlowering/splitworkiteminfo">SplitWorkItemInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23d9053e6c1acf31ff8244efba6e44b">computeSplitWorkItemInfo</a> (const SwitchWorkListItem &amp;W)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute information to balance the tree based on branch probabilities to create a near-optimal (in terms of search time given key frequency) binary search tree. <a href="#ae23d9053e6c1acf31ff8244efba6e44b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">CaseBlock</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286ec7b16992d5c9afbc8a634f264184">SwitchCases</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">CaseBlock</a> structures used to communicate <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> code generation information. <a href="#a286ec7b16992d5c9afbc8a634f264184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a09bb92997495ee27f5689b48fabdb4c1">JumpTableBlock</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af121412e6c04aaf607464f572a737a36">JTCases</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptable">JumpTable</a> structures used to communicate <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> code generation information. <a href="#af121412e6c04aaf607464f572a737a36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock">BitTestBlock</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b623b9a9376f177c19057bbe8452f0">BitTestCases</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock">BitTestBlock</a> structures used to communicate <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> code generation information. <a href="#ad0b623b9a9376f177c19057bbe8452f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b4e7026ee414d2864f4f9bb80bebe6">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0f1989ff38afeca0fbe6d3199a9fbd">TM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653b0ef051399651c1d5f890f76e90b7">DL</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d2399671a0c517fb48adb7c0d4d403">FuncInfo</a></td>
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


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SwitchLowering() {#aea060a45dbec9e1066e5af56efb6d419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchCG::SwitchLowering::SwitchLowering (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcinfo)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/sdagswitchlowering/#a4eded23b59e955c010b3f0c50fef239a">llvm::SelectionDAGBuilder::SDAGSwitchLowering::SDAGSwitchLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SwitchLowering() {#a0d041eb1a9bb170de682e9b028a0bd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::SwitchCG::SwitchLowering::~SwitchLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSuccessorWithProb() {#ab4222a54657e712a02c19875dd7e0d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SwitchCG::SwitchLowering::addSuccessorWithProb (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">llvm::BranchProbability::getUnknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>


<p>Referenced by <a href="#ae706b72bcadad3acf12a239b257aabc6">buildJumpTable</a>.</p>

</div>
</div>

### buildBitTests() {#a225bed9cd6803933d859e79619abc590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SwitchCG::SwitchLowering::buildBitTests (<a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a79baa30810b267c49d14b070a5a99110">CaseClusterVector</a> &amp; Clusters, unsigned First, unsigned Last, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">CaseCluster</a> &amp; BTCluster)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a bit test cluster from Clusters[First..Last].</p>


<p>Returns false if it decides it's not a good idea.</p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casebits/#aa020a40bff8b253b6ea6e481105a38fe">llvm::SwitchCG::CaseBits::Bits</a>, <a href="#ad0b623b9a9376f177c19057bbe8452f0">BitTestCases</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster/#af136623e6876cb81bf58483924ba9695">llvm::SwitchCG::CaseCluster::bitTests</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa5e6475cb2937c0cc4aabbaa8c2aac459">llvm::SwitchCG::CC_Range</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a568ff706b8c5991bd299c8c00b803897">llvm::BitVector::count</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casebits/#aefa39b697623aa50b628c932356b223d">llvm::SwitchCG::CaseBits::ExtraProb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afd00958cba7080048a84cccfcef55d71">llvm::BranchProbability::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05609d049bfe3c5c2f64711566131a86a28d0edd045e05cf5af64e35ae0c4c6ef">llvm::Low</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casebits/#a417ce45122cef3bf2f5a38076590a650">llvm::SwitchCG::CaseBits::Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#ab5de88dc9568b784876478e316042ba6">findBitTestClusters</a>.</p>

</div>
</div>

### buildJumpTable() {#ae706b72bcadad3acf12a239b257aabc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SwitchCG::SwitchLowering::buildJumpTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a79baa30810b267c49d14b070a5a99110">CaseClusterVector</a> &amp; Clusters, unsigned First, unsigned Last, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &gt; &amp; SL, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DefaultMBB, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">CaseCluster</a> &amp; JTCluster)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a>.</p>


<p>References <a href="#ab4222a54657e712a02c19875dd7e0d60">addSuccessorWithProb</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa5e6475cb2937c0cc4aabbaa8c2aac459">llvm::SwitchCG::CC_Range</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#a5a48ea8ae9371565b98b24668016e5ef">llvm::MachineJumpTableInfo::createJumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3c6ee10aa5e2d19af3872a019e2b9375">llvm::MachineFunction::getOrCreateJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afd00958cba7080048a84cccfcef55d71">llvm::BranchProbability::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#af121412e6c04aaf607464f572a737a36">JTCases</a>, <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster/#a7c12a1bbc0e27cc6e267de5a551aa4c9">llvm::SwitchCG::CaseCluster::jumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05609d049bfe3c5c2f64711566131a86a28d0edd045e05cf5af64e35ae0c4c6ef">llvm::Low</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0c54da24de983d197068425e718fb607">llvm::MachineBasicBlock::normalizeSuccProbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>.</p>


<p>Referenced by <a href="#a41add37692675e7e74358acc1483f168">findJumpTables</a>.</p>

</div>
</div>

### caseClusterRank() {#a350ee9bc2296e756148f478ba9e850e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SwitchCG::SwitchLowering::caseClusterRank (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">CaseCluster</a> &amp; CC, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#afb58db00e426c2a6c09111c7cea5a743">CaseClusterIt</a> First, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#afb58db00e426c2a6c09111c7cea5a743">CaseClusterIt</a> Last)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the rank by weight of CC in [First,Last].</p>


<p>If CC has more weight than each cluster in the range, its rank is 0.</p>


<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ae23d9053e6c1acf31ff8244efba6e44b">computeSplitWorkItemInfo</a>.</p>

</div>
</div>

### computeSplitWorkItemInfo() {#ae23d9053e6c1acf31ff8244efba6e44b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchCG::SwitchLowering::SplitWorkItemInfo SwitchCG::SwitchLowering::computeSplitWorkItemInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/switchcg/switchworklistitem">SwitchWorkListItem</a> &amp; W)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute information to balance the tree based on branch probabilities to create a near-optimal (in terms of search time given key frequency) binary search tree.</p>


<p>See e.g. Kurt Mehlhorn "Nearly Optimal Binary Search Trees" (1975).</p>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a350ee9bc2296e756148f478ba9e850e0">caseClusterRank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### findBitTestClusters() {#ab5de88dc9568b784876478e316042ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwitchCG::SwitchLowering::findBitTestClusters (<a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a79baa30810b267c49d14b070a5a99110">CaseClusterVector</a> &amp; Clusters, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a225bed9cd6803933d859e79619abc590">buildBitTests</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa8618d970d3b70f103de8d0eab7e6a5eb">llvm::SwitchCG::CC_JumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa5e6475cb2937c0cc4aabbaa8c2aac459">llvm::SwitchCG::CC_Range</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a568ff706b8c5991bd299c8c00b803897">llvm::BitVector::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>

</div>
</div>

### findJumpTables() {#a41add37692675e7e74358acc1483f168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwitchCG::SwitchLowering::findJumpTables (<a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a79baa30810b267c49d14b070a5a99110">CaseClusterVector</a> &amp; Clusters, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &gt; SL, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DefaultMBB, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae706b72bcadad3acf12a239b257aabc6">buildJumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa5e6475cb2937c0cc4aabbaa8c2aac459">llvm::SwitchCG::CC_Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a588f02bacd83a10b0ed821aaccc5610f">llvm::SwitchCG::getJumpTableNumCases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#ab401f0019413b136ec7484fcb6236f68">llvm::SwitchCG::getJumpTableRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>

</div>
</div>

### init() {#ad2206b9896f6a294438739b86357af9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchCG::SwitchLowering::init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; tli, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; tm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; dl)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BitTestCases {#ad0b623b9a9376f177c19057bbe8452f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BitTestBlock&gt; llvm::SwitchCG::SwitchLowering::BitTestCases</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of <a href="/web-llvm/docs/api/structs/llvm/switchcg/bittestblock">BitTestBlock</a> structures used to communicate <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> code generation information.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a225bed9cd6803933d859e79619abc590">buildBitTests</a>.</p>

</div>
</div>

### JTCases {#af121412e6c04aaf607464f572a737a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;JumpTableBlock&gt; llvm::SwitchCG::SwitchLowering::JTCases</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of <a href="/web-llvm/docs/api/structs/llvm/switchcg/jumptable">JumpTable</a> structures used to communicate <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> code generation information.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#ae706b72bcadad3acf12a239b257aabc6">buildJumpTable</a>.</p>

</div>
</div>

### SwitchCases {#a286ec7b16992d5c9afbc8a634f264184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CaseBlock&gt; llvm::SwitchCG::SwitchLowering::SwitchCases</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">CaseBlock</a> structures used to communicate <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> code generation information.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#a653b0ef051399651c1d5f890f76e90b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* llvm::SwitchCG::SwitchLowering::DL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### FuncInfo {#aa5d2399671a0c517fb48adb7c0d4d403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionLoweringInfo&amp; llvm::SwitchCG::SwitchLowering::FuncInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### TLI {#ae1b4e7026ee414d2864f4f9bb80bebe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* llvm::SwitchCG::SwitchLowering::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### TM {#a6b0f1989ff38afeca0fbe6d3199a9fbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* llvm::SwitchCG::SwitchLowering::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/switchloweringutils-cpp">SwitchLoweringUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
