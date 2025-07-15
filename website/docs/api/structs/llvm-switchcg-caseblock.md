---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/switchcg/caseblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CaseBlock` Struct Reference

<p>This structure is used to communicate between <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> and SDISel for the code generation of additional basic blocks needed by multi-case switch statements. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SwitchCG::CaseBlock { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">llvm/CodeGen/SwitchLoweringUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> (ISD::CondCode cc, const Value *cmplhs, const Value *cmprhs, const Value *cmpmiddle, MachineBasicBlock *truebb, MachineBasicBlock *falsebb, MachineBasicBlock *me, SDLoc dl, BranchProbability trueprob=BranchProbability::getUnknown(), BranchProbability falseprob=BranchProbability::getUnknown(), bool isunpredictable=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1a861a3ca73c38d41341e5630d7206">CaseBlock</a> (CmpInst::Predicate pred, bool nocmp, const Value *cmplhs, const Value *cmprhs, const Value *cmpmiddle, MachineBasicBlock *truebb, MachineBasicBlock *falsebb, MachineBasicBlock *me, DebugLoc dl, BranchProbability trueprob=BranchProbability::getUnknown(), BranchProbability falseprob=BranchProbability::getUnknown(), bool isunpredictable=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed88926c7c267de324ad1fb3849711da">CC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c8ff2b32d5ab7b3cb32056920ad63b">PredInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">llvm::SwitchCG::CaseBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a7553fb60ebc5c8dc84bd3658555b8"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c69b42db9fbec24257dd3f4991dcc45">CmpLHS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac82e73a81c735151477cce79e665ded">CmpMHS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cbab750fe1c9367b0b60d1fc5b93b3">CmpRHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85dee301aa78d53f5a80ec7f8739bb00">TrueBB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3b98f6c3852ce830744ceed0aafd63">FalseBB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f6788e0412c4fe16273d2dd1a03cef">ThisBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa78f50d45ebf96fcdafc6566a3d4951">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug location of the instruction this <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">CaseBlock</a> was produced from. <a href="#afa78f50d45ebf96fcdafc6566a3d4951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ee1d434a22e2c482a561f00386ba41">DbgLoc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ec00a8f98caffafaae61f79580d2ec">TrueProb</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cab00e92ff09b90369ee038ef5149cf">FalseProb</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e0d0a0add71615292568516d513794">IsUnpredictable</a></td>
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

<p>This structure is used to communicate between <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> and SDISel for the code generation of additional basic blocks needed by multi-case switch statements.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CaseBlock() {#a6ab842e01d79a0e6b95068c03625ae61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchCG::CaseBlock::CaseBlock (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> cc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cmplhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cmprhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cmpmiddle, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * truebb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * falsebb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * me, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> dl, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> trueprob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>(), <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> falseprob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>(), bool isunpredictable=false)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="#aed88926c7c267de324ad1fb3849711da">CC</a>, <a href="#a8c69b42db9fbec24257dd3f4991dcc45">CmpLHS</a>, <a href="#aac82e73a81c735151477cce79e665ded">CmpMHS</a>, <a href="#a38cbab750fe1c9367b0b60d1fc5b93b3">CmpRHS</a>, <a href="#afa78f50d45ebf96fcdafc6566a3d4951">DL</a>, <a href="#a8b3b98f6c3852ce830744ceed0aafd63">FalseBB</a>, <a href="#a3cab00e92ff09b90369ee038ef5149cf">FalseProb</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">llvm::BranchProbability::getUnknown</a>, <a href="#aa7e0d0a0add71615292568516d513794">IsUnpredictable</a>, <a href="#a17f6788e0412c4fe16273d2dd1a03cef">ThisBB</a>, <a href="#a85dee301aa78d53f5a80ec7f8739bb00">TrueBB</a> and <a href="#a11ec00a8f98caffafaae61f79580d2ec">TrueProb</a>.</p>

</div>
</div>

### CaseBlock() {#afb1a861a3ca73c38d41341e5630d7206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchCG::CaseBlock::CaseBlock (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> pred, bool nocmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cmplhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cmprhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cmpmiddle, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * truebb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * falsebb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * me, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> dl, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> trueprob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>(), <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> falseprob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>(), bool isunpredictable=false)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">llvm::BranchProbability::getUnknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a> and <a href="#a33c8ff2b32d5ab7b3cb32056920ad63b">PredInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a12a7553fb60ebc5c8dc84bd3658555b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::SwitchCG::CaseBlock llvm::SwitchCG::CaseBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### CC {#aed88926c7c267de324ad1fb3849711da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::CondCode llvm::SwitchCG::CaseBlock::CC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### CmpLHS {#a8c69b42db9fbec24257dd3f4991dcc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::SwitchCG::CaseBlock::CmpLHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### CmpMHS {#aac82e73a81c735151477cce79e665ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::SwitchCG::CaseBlock::CmpMHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### CmpRHS {#a38cbab750fe1c9367b0b60d1fc5b93b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::SwitchCG::CaseBlock::CmpRHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### DbgLoc {#a42ee1d434a22e2c482a561f00386ba41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::SwitchCG::CaseBlock::DbgLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>

</div>
</div>

### DL {#afa78f50d45ebf96fcdafc6566a3d4951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDLoc llvm::SwitchCG::CaseBlock::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug location of the instruction this <a href="/web-llvm/docs/api/structs/llvm/switchcg/caseblock">CaseBlock</a> was produced from.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### FalseBB {#a8b3b98f6c3852ce830744ceed0aafd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::SwitchCG::CaseBlock::FalseBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### FalseProb {#a3cab00e92ff09b90369ee038ef5149cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::SwitchCG::CaseBlock::FalseProb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### IsUnpredictable {#aa7e0d0a0add71615292568516d513794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwitchCG::CaseBlock::IsUnpredictable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### PredInfo {#a33c8ff2b32d5ab7b3cb32056920ad63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct PredInfoPair llvm::SwitchCG::CaseBlock::PredInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#afb1a861a3ca73c38d41341e5630d7206">CaseBlock</a>.</p>

</div>
</div>

### ThisBB {#a17f6788e0412c4fe16273d2dd1a03cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SwitchCG::CaseBlock::ThisBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a>.</p>

</div>
</div>

### TrueBB {#a85dee301aa78d53f5a80ec7f8739bb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::SwitchCG::CaseBlock::TrueBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### TrueProb {#a11ec00a8f98caffafaae61f79580d2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability llvm::SwitchCG::CaseBlock::TrueProb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a>.</p>


<p>Referenced by <a href="#a6ab842e01d79a0e6b95068c03625ae61">CaseBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/switchloweringutils-h">SwitchLoweringUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
