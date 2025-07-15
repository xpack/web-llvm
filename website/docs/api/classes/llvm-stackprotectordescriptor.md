---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stackprotectordescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StackProtectorDescriptor` Class Reference

<p>Encapsulates all of the information needed to generate a stack protector check, and signals to isel when initialized that one needs to be generated. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StackProtectorDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">llvm/CodeGen/CodeGenCommonISel.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fb7a049f0def99d06f6d19ef0e5ded">StackProtectorDescriptor</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7bb247910a6a75a3b45832033893a9">shouldEmitStackProtector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all fields of the stack protector descriptor are initialized implying that we should/are ready to emit a stack protector. <a href="#a9f7bb247910a6a75a3b45832033893a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02aa9780b3650004c5a6dd172020ca4">shouldEmitFunctionBasedCheckStackProtector</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275ec5215a2578ade2b508eaccf0ddc9">initialize</a> (const BasicBlock *BB, MachineBasicBlock *MBB, bool FunctionBasedInstrumentation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the stack protector descriptor structure for a new basic block. <a href="#a275ec5215a2578ade2b508eaccf0ddc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c52761f81703c84723223cb3e21277e">resetPerBBState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset state that changes when we handle different basic blocks. <a href="#a2c52761f81703c84723223cb3e21277e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33dac72fe3581c561d8a3922bbf94681">resetPerFunctionState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset state that only changes when we switch functions. <a href="#a33dac72fe3581c561d8a3922bbf94681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad101291a071ef005af5b5653a9c516">getParentMBB</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa77282a145eb011d595a554810d367">getSuccessMBB</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dca6975019bcf560ab04e7756cbe3a2">getFailureMBB</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6e81d14098ef1916072a82010e6f16">addSuccessorMBB</a> (const BasicBlock *BB, MachineBasicBlock *ParentMBB, bool IsLikely, MachineBasicBlock *SuccMBB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a successor machine basic block to ParentMBB. <a href="#a9a6e81d14098ef1916072a82010e6f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca5c22988a25ef69aab08d05609249a">ParentMBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The basic block for which we are generating the stack protector. <a href="#aeca5c22988a25ef69aab08d05609249a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3367d87b62a5cf89a0d14264ab1150">SuccessMBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A basic block visited on stack protector check success that contains the terminators of ParentMBB. <a href="#a6b3367d87b62a5cf89a0d14264ab1150">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc0037fd7f3971198d114d8e6a3ccd6">FailureMBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This basic block visited on stack protector check failure that will contain a call to __stack_chk_fail(). <a href="#aabc0037fd7f3971198d114d8e6a3ccd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Encapsulates all of the information needed to generate a stack protector check, and signals to isel when initialized that one needs to be generated.</p>


<p><em>NOTE</em> The following is a high level documentation of <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> Stack Protector Generation. This is now also ported be shared with GlobalISel, but without any significant changes.</p>


<p>High Level Overview of ISel Stack Protector Generation:</p>


<p>Previously, the "stack protector" IR pass handled stack protector generation. This necessitated splitting basic blocks at the IR level to create the success/failure basic blocks in the tail of the basic block in question. As a result of this, calls that would have qualified for the sibling call optimization were no longer eligible for optimization since said calls were no longer right in the "tail position" (i.e. the immediate predecessor of a <a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> instruction).</p>


<p>Since the sibling call optimization causes the callee to reuse the caller's stack, if we could delay the generation of the stack protector check until later in CodeGen after the sibling call decision was made, we get both the tail call optimization and the stack protector check!</p>


<p>A few goals in solving this problem were:</p>


<ol class="doxyList" type="1">
<li>Preserve the architecture independence of stack protector generation.</li>
<li>Preserve the normal IR level stack protector check for platforms like OpenBSD for which we support platform-specific stack protector generation.</li>
</ol>

<p>The main problem that guided the present solution is that one can not solve this problem in an architecture independent manner at the IR level only. This is because:</p>


<ol class="doxyList" type="1">
<li>The decision on whether or not to perform a sibling call on certain platforms (for instance i386) requires lower level information related to available registers that can not be known at the IR level.</li>
<li>Even if the previous point were not true, the decision on whether to perform a tail call is done in LowerCallTo in <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> (or <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> in GlobalISel) which occurs after the Stack Protector <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>. As a result, one would need to put the relevant callinst into the stack protector check success basic block (where the return inst is placed) and then move it back later at ISel/MI time before the stack protector check if the tail call optimization failed. The MI level option was nixed immediately since it would require platform-specific pattern matching. The ISel level option was nixed because <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> only processes one IR level basic block at a time implying one could not create a DAG Combine to move the callinst.</li>
</ol>

<p>To get around this problem:</p>


<ol class="doxyList" type="1">
<li><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> can only process one block at a time, we can generate multiple machine basic blocks for one IR level basic block. This is how we handle bit tests and switches.</li>
<li>At the MI level, tail calls are represented via a special return MIInst called "tcreturn". Thus if we know the basic block in which we wish to insert the stack protector check, we get the correct behavior by always inserting the stack protector check right before the return statement. This is a "magical transformation" since no matter where the stack protector check intrinsic is, we always insert the stack protector check code at the end of the BB.</li>
</ol>

<p>Given the aforementioned constraints, the following solution was devised:</p>


<ol class="doxyList" type="1">
<li>On platforms that do not support ISel stack protector check generation, allow for the normal IR level stack protector check generation to continue.</li>
<li>On platforms that do support ISel stack protector check generation:

a. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the IR level stack protector pass to decide if a stack protector is required/which BB we insert the stack protector check in by reusing the logic already therein.

b. After we finish selecting the basic block, we produce the validation code with one of these techniques: 1) with a call to a guard check function 2) with inlined instrumentation

1) We insert a call to the check function before the terminator.

2) We first find a splice point in the parent basic block before the terminator and then splice the terminator of said basic block into the success basic block. Then we code-gen a new tail for the parent basic block consisting of the two loads, the comparison, and finally two branches to the success/failure basic blocks. We conclude by code-gening the failure basic block if we have not code-gened it already (all stack protector checks we generate in the same function, use the same failure basic block).</li>
</ol>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StackProtectorDescriptor() {#ad5fb7a049f0def99d06f6d19ef0e5ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StackProtectorDescriptor::StackProtectorDescriptor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFailureMBB() {#a6dca6975019bcf560ab04e7756cbe3a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::StackProtectorDescriptor::getFailureMBB ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### getParentMBB() {#a8ad101291a071ef005af5b5653a9c516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::StackProtectorDescriptor::getParentMBB ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

### getSuccessMBB() {#a2aa77282a145eb011d595a554810d367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::StackProtectorDescriptor::getSuccessMBB ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### initialize() {#a275ec5215a2578ade2b508eaccf0ddc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StackProtectorDescriptor::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, bool FunctionBasedInstrumentation)</td>
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

<p>Initialize the stack protector descriptor structure for a new basic block.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a9f7bb247910a6a75a3b45832033893a9">shouldEmitStackProtector</a>.</p>

</div>
</div>

### resetPerBBState() {#a2c52761f81703c84723223cb3e21277e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StackProtectorDescriptor::resetPerBBState ()</td>
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

<p>Reset state that changes when we handle different basic blocks.</p>


<p>This currently includes:</p>


<ol class="doxyList" type="1">
<li>The specific basic block we are generating a stack protector for (ParentMBB).</li>
<li>The successor machine basic block that will contain the tail of parent mbb after we create the stack protector check (SuccessMBB). This BB is visited only on stack protector check success.</li>
</ol>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

### resetPerFunctionState() {#a33dac72fe3581c561d8a3922bbf94681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StackProtectorDescriptor::resetPerFunctionState ()</td>
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

<p>Reset state that only changes when we switch functions.</p>


<p>This currently includes:</p>


<ol class="doxyList" type="1">
<li>FailureMBB since we reuse the failure code path for all stack protector checks created in an individual function.</li>
</ol>

<p>2.The guard variable since the guard variable we are checking against is always the same.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

### shouldEmitFunctionBasedCheckStackProtector() {#ab02aa9780b3650004c5a6dd172020ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StackProtectorDescriptor::shouldEmitFunctionBasedCheckStackProtector ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

### shouldEmitStackProtector() {#a9f7bb247910a6a75a3b45832033893a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StackProtectorDescriptor::shouldEmitStackProtector ()</td>
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

<p>Returns true if all fields of the stack protector descriptor are initialized implying that we should/are ready to emit a stack protector.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>


<p>Referenced by <a href="#a275ec5215a2578ade2b508eaccf0ddc9">initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSuccessorMBB() {#a9a6e81d14098ef1916072a82010e6f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * StackProtectorDescriptor::addSuccessorMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * ParentMBB, bool IsLikely, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccMBB=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a successor machine basic block to ParentMBB.</p>


<p>Add a successor MBB to ParentMBB&lt; creating a new MachineBB for BB if SuccMBB is 0.</p>


<p>If the successor mbb has not been created yet (i.e. if SuccMBB = 0), then the machine basic block will be created. Assign a large weight if IsLikely is true.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp">CodeGenCommonISel.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FailureMBB {#aabc0037fd7f3971198d114d8e6a3ccd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::StackProtectorDescriptor::FailureMBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This basic block visited on stack protector check failure that will contain a call to __stack_chk_fail().</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

### ParentMBB {#aeca5c22988a25ef69aab08d05609249a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::StackProtectorDescriptor::ParentMBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The basic block for which we are generating the stack protector.</p>


<p>As a result of stack protector generation, we will splice the terminators of this basic block into the successor mbb SuccessMBB and replace it with a compare/branch to the successor mbbs SuccessMBB/FailureMBB depending on whether or not the stack protector was violated.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

### SuccessMBB {#a6b3367d87b62a5cf89a0d14264ab1150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::StackProtectorDescriptor::SuccessMBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A basic block visited on stack protector check success that contains the terminators of ParentMBB.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegencommonisel-h">CodeGenCommonISel.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp">CodeGenCommonISel.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
