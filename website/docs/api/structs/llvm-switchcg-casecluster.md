---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/switchcg/casecluster
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CaseCluster` Struct Reference

<p>A cluster of case labels. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SwitchCG::CaseCluster { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">llvm/CodeGen/SwitchLoweringUtils.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20da">CaseClusterKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f93f8291cccbfaac0af09c841026178">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9149913738ab8f2bda53815976574194">Low</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065919ff4d285a648cffb85cfad49421">High</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04d7316adcda065969204ba0dafcefc">MBB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8e59dbb4a6ee4250705f2d6d038198">JTCasesIndex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bca3d323709da65c039edabe72c218e">BTCasesIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">llvm::SwitchCG::CaseCluster</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f561c7f1cc22848fe5d3eed21a4381"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1512f7779598def512883389a485270c">Prob</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">CaseCluster</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd5cdff1df46742a7d1c12136f116fd">range</a> (const ConstantInt *Low, const ConstantInt *High, MachineBasicBlock *MBB, BranchProbability Prob)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">CaseCluster</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c12a1bbc0e27cc6e267de5a551aa4c9">jumpTable</a> (const ConstantInt *Low, const ConstantInt *High, unsigned JTCasesIndex, BranchProbability Prob)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/switchcg/casecluster">CaseCluster</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af136623e6876cb81bf58483924ba9695">bitTests</a> (const ConstantInt *Low, const ConstantInt *High, unsigned BTCasesIndex, BranchProbability Prob)</td>
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

<p>A cluster of case labels.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

###  {#a26f561c7f1cc22848fe5d3eed21a4381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SwitchCG::CaseCluster llvm::SwitchCG::CaseCluster</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### BTCasesIndex {#a7bca3d323709da65c039edabe72c218e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwitchCG::CaseCluster::BTCasesIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#af136623e6876cb81bf58483924ba9695">bitTests</a>.</p>

</div>
</div>

### High {#a065919ff4d285a648cffb85cfad49421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt * llvm::SwitchCG::CaseCluster::High</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#af136623e6876cb81bf58483924ba9695">bitTests</a>, <a href="#a7c12a1bbc0e27cc6e267de5a551aa4c9">jumpTable</a> and <a href="#a5cd5cdff1df46742a7d1c12136f116fd">range</a>.</p>

</div>
</div>

### JTCasesIndex {#adf8e59dbb4a6ee4250705f2d6d038198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwitchCG::CaseCluster::JTCasesIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a7c12a1bbc0e27cc6e267de5a551aa4c9">jumpTable</a>.</p>

</div>
</div>

### Kind {#a0f93f8291cccbfaac0af09c841026178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseClusterKind llvm::SwitchCG::CaseCluster::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### Low {#a9149913738ab8f2bda53815976574194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt* llvm::SwitchCG::CaseCluster::Low</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#af136623e6876cb81bf58483924ba9695">bitTests</a>, <a href="#a7c12a1bbc0e27cc6e267de5a551aa4c9">jumpTable</a>, <a href="#a5cd5cdff1df46742a7d1c12136f116fd">range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a770339f0c1b1f2c1328c48f1f4291dfa">llvm::SwitchCG::sortAndRangeify</a>.</p>

</div>
</div>

### MBB {#ad04d7316adcda065969204ba0dafcefc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SwitchCG::CaseCluster::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a5cd5cdff1df46742a7d1c12136f116fd">range</a>.</p>

</div>
</div>

### Prob {#a1512f7779598def512883389a485270c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::SwitchCG::CaseCluster::Prob</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#af136623e6876cb81bf58483924ba9695">bitTests</a>, <a href="#a7c12a1bbc0e27cc6e267de5a551aa4c9">jumpTable</a> and <a href="#a5cd5cdff1df46742a7d1c12136f116fd">range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### bitTests() {#af136623e6876cb81bf58483924ba9695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseCluster llvm::SwitchCG::CaseCluster::bitTests (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Low, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * High, unsigned BTCasesIndex, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="#a7bca3d323709da65c039edabe72c218e">BTCasesIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daab3398550375bca11fe3e11d0c454e382">llvm::SwitchCG::CC_BitTests</a>, <a href="#a065919ff4d285a648cffb85cfad49421">High</a>, <a href="#a9149913738ab8f2bda53815976574194">Low</a> and <a href="#a1512f7779598def512883389a485270c">Prob</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a225bed9cd6803933d859e79619abc590">llvm::SwitchCG::SwitchLowering::buildBitTests</a>.</p>

</div>
</div>

### jumpTable() {#a7c12a1bbc0e27cc6e267de5a551aa4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseCluster llvm::SwitchCG::CaseCluster::jumpTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Low, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * High, unsigned JTCasesIndex, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa8618d970d3b70f103de8d0eab7e6a5eb">llvm::SwitchCG::CC_JumpTable</a>, <a href="#a065919ff4d285a648cffb85cfad49421">High</a>, <a href="#adf8e59dbb4a6ee4250705f2d6d038198">JTCasesIndex</a>, <a href="#a9149913738ab8f2bda53815976574194">Low</a> and <a href="#a1512f7779598def512883389a485270c">Prob</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ae706b72bcadad3acf12a239b257aabc6">llvm::SwitchCG::SwitchLowering::buildJumpTable</a>.</p>

</div>
</div>

### range() {#a5cd5cdff1df46742a7d1c12136f116fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseCluster llvm::SwitchCG::CaseCluster::range (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Low, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * High, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#af4eb499895466e3a26f105b4c11d20daa5e6475cb2937c0cc4aabbaa8c2aac459">llvm::SwitchCG::CC_Range</a>, <a href="#a065919ff4d285a648cffb85cfad49421">High</a>, <a href="#a9149913738ab8f2bda53815976574194">Low</a>, <a href="#ad04d7316adcda065969204ba0dafcefc">MBB</a> and <a href="#a1512f7779598def512883389a485270c">Prob</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
