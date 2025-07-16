---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNPassConfig` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig">AMDGPUPassConfig</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e14f7e670cd323bc7683448c522dc7">GCNPassConfig</a> (TargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine">GCNTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2231566b709be60b56bf00c6b29a4b8">getGCNTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee7911947922a80fe782ead0742972e">createMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level. <a href="#abee7911947922a80fe782ead0742972e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc91f335d0788469b44e409f15109585">createPostMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled. <a href="#abc91f335d0788469b44e409f15109585">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5e5cbdd263a4e0801b6dbf7c4e8ecd">addPreISel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#a5f5e5cbdd263a4e0801b6dbf7c4e8ecd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27c6922c2bb7ff1be0935f45a9e51aa">addMachineSSAOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form. <a href="#ac27c6922c2bb7ff1be0935f45a9e51aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d63513d35cc11cffba6cc0e1aedd6c">addILPOpts</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes that optimize instruction level parallelism for out-of-order targets. <a href="#a57d63513d35cc11cffba6cc0e1aedd6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f9db49e1cea1b37060681a0eedaf90c">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a6f9db49e1cea1b37060681a0eedaf90c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803bdcce5d97942f25d205c0cd6ae8c4">addIRTranslator</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes. <a href="#a803bdcce5d97942f25d205c0cd6ae8c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2667c7295afc96b23b54411646ba4171">addPreLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before legalization. <a href="#a2667c7295afc96b23b54411646ba4171">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7caa390ceeba55f7ab65e753c4c50e36">addLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target. <a href="#a7caa390ceeba55f7ab65e753c4c50e36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708125794ff496369f448c57990dc8ca">addPreRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before the register bank selection. <a href="#a708125794ff496369f448c57990dc8ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce176d2bddc4a3f88632b6848ad925e">addRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks. <a href="#a1ce176d2bddc4a3f88632b6848ad925e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979e73953046b0147c98748acca751bd">addPreGlobalInstructionSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before the (global) instruction selection. <a href="#a979e73953046b0147c98748acca751bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d8c81496f515a0baa31ca868ba92bf">addGlobalInstructionSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes. <a href="#a52d8c81496f515a0baa31ca868ba92bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b7b0423393d29b768dbbac91591004">addFastRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation. <a href="#a48b7b0423393d29b768dbbac91591004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b46039eaf0e1d0d70654fb984590de2">addOptimizedRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addOptimizedRegAlloc - Add passes related to register allocation. <a href="#a9b46039eaf0e1d0d70654fb984590de2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22399dbddf111b9bda1744d4c273a593">createSGPRAllocPass</a> (bool Optimized)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378df4e13ead88fb4268b93ec354f169">createVGPRAllocPass</a> (bool Optimized)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d9cc889332d421bfb591e473db3601">createWWMRegAllocPass</a> (bool Optimized)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d247e02f920febb3186ff26c27d88ed">createRegAllocPass</a> (bool Optimized) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachinePasses helper to create the target-selected or overriden regalloc pass. <a href="#a4d247e02f920febb3186ff26c27d88ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c5c73df865e6fa5a9fd1eb2b026168">addRegAssignAndRewriteFast</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add core register allocator passes which do the actual register assignment and rewriting. <a href="#ab8c5c73df865e6fa5a9fd1eb2b026168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598bda274297556dcbff4950a9d76444">addRegAssignAndRewriteOptimized</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b4ef77d4c6d7c070e0e92f1ed03b04">addPreRewrite</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addPreRewrite - Add passes to the optimized register allocation pipeline after register allocation is complete, but before virtual registers are rewritten to physical registers. <a href="#a27b4ef77d4c6d7c070e0e92f1ed03b04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19eac7701308b52068b7ec681c790fa">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#ab19eac7701308b52068b7ec681c790fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1487ad90c2cd99ed9a54aa02cd5fd43">addPreSched2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#ae1487ad90c2cd99ed9a54aa02cd5fd43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb47f242712c201352b881147ea41e90">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#aeb47f242712c201352b881147ea41e90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNPassConfig() {#a61e14f7e670cd323bc7683448c522dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::GCNPassConfig (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a79305ba9935a6139ad667945f665d6ea">llvm::AMDGPUPassConfig::AMDGPUPassConfig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51a34bf4ca8119bdeb89ffc48c5d4783">llvm::PostMachineSchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a809a59c560dc200a93667852f2dc68ca">llvm::TargetPassConfig::setRequiresCodeGenSCCOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e22488ba2ab98ca21d3d1377e4ba26a">llvm::TargetPassConfig::substitutePass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFastRegAlloc() {#a48b7b0423393d29b768dbbac91591004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addFastRegAlloc ()</td>
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

<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation.</p>


<p>Add the minimum set of target-independent passes that are required for register allocation.</p>


<p>No coalescing or scheduling.</p>


<p>Definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8473cd921ce0dee1a2b3b0ab484708cc">llvm::TargetPassConfig::addFastRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a36adfc24480b78dfe7a51559b8264de7">llvm::TargetPassConfig::insertPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae50f7215c4832bcfb5ffb377f964e061">llvm::PHIEliminationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa12848161f52fbf282860ae599a2da1b">llvm::SILowerControlFlowLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2cbe7e171e9c35ed81b4adffd23c80f">llvm::SIWholeQuadModeID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adcdd39e0229ebb0b23f143d644d2d1f7">llvm::TwoAddressInstructionPassID</a>.</p>

</div>
</div>

### addGlobalInstructionSelect() {#a52d8c81496f515a0baa31ca868ba92bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addGlobalInstructionSelect ()</td>
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

<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes.</p>

<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addILPOpts() {#a57d63513d35cc11cffba6cc0e1aedd6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addILPOpts ()</td>
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

<p>Add passes that optimize instruction level parallelism for out-of-order targets.</p>


<p>These passes are run while the machine code is still in SSA form, so they can use MachineTraceMetrics to control their heuristics.</p>


<p>All passes added here should preserve the MachineDominatorTree, MachineLoopInfo, and MachineTraceMetrics analyses.</p>


<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3c584af6befa438063622f975dc8386a">llvm::TargetPassConfig::addILPOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57e66365c51f9fe42173246196dc25f1">llvm::EarlyIfConverterLegacyID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ad406e3834655b047b66b1ff9cb4b43c8">EnableEarlyIfConversion</a>.</p>

</div>
</div>

### addInstSelector() {#a6f9db49e1cea1b37060681a0eedaf90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addInstSelector ()</td>
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

<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions.</p>

<p>Definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a3dfda91b1766a907bad7895b0c02c3ee">llvm::AMDGPUPassConfig::addInstSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb4b78ee0928a1acee5457337da279d">llvm::createSILowerI1CopiesLegacyPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac0c5201ad7ca8f35d08a7ec76d8c7d58">llvm::SIFixSGPRCopiesLegacyID</a>.</p>

</div>
</div>

### addIRTranslator() {#a803bdcce5d97942f25d205c0cd6ae8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addIRTranslator ()</td>
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

<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes.</p>

<p>Definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addLegalizeMachineIR() {#a7caa390ceeba55f7ab65e753c4c50e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addLegalizeMachineIR ()</td>
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

<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target.</p>

<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#ac27c6922c2bb7ff1be0935f45a9e51aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addMachineSSAOptimization ()</td>
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

<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form.</p>


<p>Add passes that optimize machine instructions in SSA form.</p>


<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e1dc65c445136e2e59dbee92ccd5f7d">llvm::TargetPassConfig::addMachineSSAOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7d649fe773cb6be857027a0a9ac5958">llvm::createSIShrinkInstructionsLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84508d5d676c86da43af3573b6297ea">llvm::DeadMachineInstructionElimID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08efde8583f615980c38b4e29760fae8">llvm::EarlyMachineLICMID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a6ac4f65ba5b4b6a993c6971af337d862">EnableDPPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a382dac520bb7468263680ea0013387aa">EnableSDWAPeephole</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7697cfe00b7d2c22fb70dee58438c937">llvm::GCNDPPCombineLegacyID</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a16f2b92989c6760a2447933b3c78a755">llvm::AMDGPUPassConfig::isPassEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab243cd86bbcb539fad948485fad842fc">llvm::MachineCSELegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac59c9ad543a3a758479d2462aab83b56">llvm::SIFoldOperandsLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad0bd0d80dde6ae49eb90068e96bbd5">llvm::SILoadStoreOptimizerLegacyID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac495b3ce88b033cfc607ea4dccf4d317">llvm::SIPeepholeSDWALegacyID</a>.</p>

</div>
</div>

### addOptimizedRegAlloc() {#a9b46039eaf0e1d0d70654fb984590de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addOptimizedRegAlloc ()</td>
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

<p>addOptimizedRegAlloc - Add passes related to register allocation.</p>


<p>Add standard target-independent passes that are tightly coupled with optimized register allocation, including coalescing, machine instruction scheduling, and register allocation itself.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a> provides standard regalloc passes for most targets.</p>


<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6481662c2fc1eb7d95b5a32939e24b94">llvm::TargetPassConfig::addOptimizedRegAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84508d5d676c86da43af3573b6297ea">llvm::DeadMachineInstructionElimID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b041ac21b02783220e6d32e943e1c8d">llvm::DetectDeadLanesID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a03570e80d49eb751eb2f8fb8189605e9">EnableDCEInRA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#add861b5daf3944b7f5a57d923d29c455">EnablePreRAOptimizations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a86164ffb69d2edf0439d0f9fb63194a9">EnableRewritePartialRegUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1460fad97eb294d613a093a3d5960dea">llvm::GCNPreRAOptimizationsID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27cfdb055746e64b50146a045437cd8e">llvm::GCNRewritePartialRegUsesID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a36adfc24480b78dfe7a51559b8264de7">llvm::TargetPassConfig::insertPass</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a16f2b92989c6760a2447933b3c78a755">llvm::AMDGPUPassConfig::isPassEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab80163ae002e9cec63a9e279d5b1c2d7">llvm::LiveVariablesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f3ce4ffd1eecf7a4fef2cce86560b1a">llvm::MachineSchedulerID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7cc77bd335790d51a417512803eb8761">OptExecMaskPreRA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ac8e22e97a2bbf3b43e765c4233d1203a">OptVGPRLiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae50f7215c4832bcfb5ffb377f964e061">llvm::PHIEliminationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec21ef731065e5fd86dcb1a64d077918">llvm::RenameIndependentSubregsID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5475adefdba77dc9bbecf952a9bd4cf3">llvm::SIFormMemoryClausesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa12848161f52fbf282860ae599a2da1b">llvm::SILowerControlFlowLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84164748e75fe82b6f96c1014586f279">llvm::SIOptimizeExecMaskingPreRAID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61bc27bebda7aee457afef9c6ed2679a">llvm::SIOptimizeVGPRLiveRangeLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2cbe7e171e9c35ed81b4adffd23c80f">llvm::SIWholeQuadModeID</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPostRegAlloc() {#ab19eac7701308b52068b7ec681c790fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addPostRegAlloc ()</td>
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

<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion.</p>

<p>Definition at line 1108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a40a9d9de0a8ca42af17c54cf1272fd11">llvm::TargetPassConfig::addPostRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac58019aba9b5294d4e0508a6298c5fdd">llvm::SIFixVGPRCopiesID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3e45e5619819d510f385416f375c67e4">llvm::SIOptimizeExecMaskingLegacyID</a>.</p>

</div>
</div>

### addPreEmitPass() {#aeb47f242712c201352b881147ea41e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addPreEmitPass ()</td>
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

<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted.</p>

<p>Definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e53ed92016d3e9fa2146428d7d6df0b">llvm::AMDGPUInsertDelayAluID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6efaf90f46371b2a436e3d95530491fe">llvm::BranchRelaxationPassID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a608059ed9b82ffc6c74899681a2ce2bc">llvm::createAMDGPUPreloadKernArgPrologLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b1328b2b52775fc6c78def1d06f39c6">llvm::createAMDGPUSetWavePriorityPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1f1b566607514b37834c2667e016954">llvm::createSIInsertWaitcntsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3e07c57f1f7331ea2dce6becb604ca4">llvm::createSIMemoryLegalizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ce45e5b72435b4b7423275d41cd2b63">llvm::createSIModeRegisterPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aa391f8f999cd00ac262961537b12d965">EnableInsertDelayAlu</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a6b94632cb8634b2674528b1dafda27df">EnableSetWavePriority</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ae1ff9bdd782ffd05efaf3465280c3521">EnableVOPD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac283495777f684b9f3676fe579a9cf88">llvm::GCNCreateVOPDID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a16f2b92989c6760a2447933b3c78a755">llvm::AMDGPUPassConfig::isPassEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a8b2bf85c8335aebd5f41c86485d89e">llvm::PostRAHazardRecognizerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abeb21a7da3bb15241e48979f2e90c2a6">llvm::SIInsertHardClausesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b9dcc40acd9e13e16072b0e255e284d">llvm::SILateBranchLoweringPassID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9d857774f36dd21a0bb4e846e8bcbaa9">llvm::SIPreEmitPeepholeID</a>.</p>

</div>
</div>

### addPreGlobalInstructionSelect() {#a979e73953046b0147c98748acca751bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addPreGlobalInstructionSelect ()</td>
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

<p>This method may be implemented by targets that want to run passes immediately before the (global) instruction selection.</p>

<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13a58eb47ea96193d204195ef8b2226">llvm::createAMDGPURegBankCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreISel() {#a5f5e5cbdd263a4e0801b6dbf7c4e8ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addPreISel ()</td>
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

<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes.</p>


<p>Methods with out-of-line standard implementations are major CodeGen stages called by addMachinePasses. Some targets may override major stages when inserting passes is insufficient, but maintaining overriden stages is more work. addPreISelPasses - This method should add any "last minute" LLVM-&gt;LLVM passes (which are run just before instruction selector).</p>


<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a32809e50f5ee8ee63d2ea8e20c0db9aa">llvm::AMDGPUPassConfig::addPreISel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa36db976dfcb92c21a9546fc2ca7dd4">llvm::AMDGPUPerfHintAnalysisLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ec9dae3cfe6007a5d87b711ff962577">llvm::AMDGPUUnifyDivergentExitNodesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1f957bcf6ab32cc9243c5cb8ed42842">llvm::createAMDGPUAnnotateUniformValuesLegacy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adea1c1543223e84df11f56c59e360d99">llvm::createAMDGPULateCodeGenPrepareLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba402224ba99d4f1ac926aa355600494">llvm::createAMDGPURewriteUndefForPHILegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a851f3205d9753afe31c59e28645a1084">llvm::createFixIrreduciblePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e50ae453760e391510b61c73a9c9a59">llvm::createLCSSAPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1cdab57d2321d56fe58536dc7374747d">llvm::createSIAnnotateControlFlowLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a701a74c44c000aec789c8e6e7fe064d6">llvm::createSinkingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb815c8f9920e07c3ab6bfc0e144658">llvm::createStructurizeCFGPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83ea9f7cadfcfd7fd47bdc2e60496211">llvm::createUnifyLoopExitsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreLegalizeMachineIR() {#a2667c7295afc96b23b54411646ba4171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addPreLegalizeMachineIR ()</td>
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

<p>This method may be implemented by targets that want to run passes immediately before legalization.</p>

<p>Definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2751fd672b46e454f128aadd3380d6b1">llvm::createAMDGPUPreLegalizeCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreRegBankSelect() {#a708125794ff496369f448c57990dc8ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addPreRegBankSelect ()</td>
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

<p>This method may be implemented by targets that want to run passes immediately before the register bank selection.</p>

<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3bcde00c3e835d7c0828043a93e9963">llvm::createAMDGPUGlobalISelDivergenceLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a592e260df29e4f6db1440436ddc907">llvm::createAMDGPUPostLegalizeCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreRewrite() {#a27b4ef77d4c6d7c070e0e92f1ed03b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addPreRewrite ()</td>
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

<p>addPreRewrite - Add passes to the optimized register allocation pipeline after register allocation is complete, but before virtual registers are rewritten to physical registers.</p>


<p>These passes must preserve VirtRegMap and LiveIntervals, and when running after RABasic or RAGreedy, they should take advantage of LiveRegMatrix. When these passes run, VirtRegMap contains legal physreg assignments for all virtual registers.</p>


<p>Note if the target overloads addRegAssignAndRewriteOptimized, this may not be honored. This is also not generally used for the fast variant, where the allocation and rewriting are done in one pass.</p>


<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ac533bca93325dcdddabf9031ab1210e9">EnableRegReassign</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a630ed80e9a19d7f0dd6638acc880ef7a">llvm::GCNNSAReassignID</a>.</p>


<p>Referenced by <a href="#a598bda274297556dcbff4950a9d76444">addRegAssignAndRewriteOptimized</a>.</p>

</div>
</div>

### addPreSched2() {#ae1487ad90c2cd99ed9a54aa02cd5fd43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNPassConfig::addPreSched2 ()</td>
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

<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass.</p>

<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7d649fe773cb6be857027a0a9ac5958">llvm::createSIShrinkInstructionsLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ba6d45ab25351a8c0d552a8114e0ec3">llvm::SIPostRABundlerID</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addRegAssignAndRewriteFast() {#ab8c5c73df865e6fa5a9fd1eb2b026168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addRegAssignAndRewriteFast ()</td>
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

<p>Add core register allocator passes which do the actual register assignment and rewriting.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any passes were added.</p></dd>
</dl>


<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ab17529dbc8213c26c4ecc1453b01c1">llvm::AMDGPUReserveWWMRegsID</a>, <a href="#a22399dbddf111b9bda1744d4c273a593">createSGPRAllocPass</a>, <a href="#a378df4e13ead88fb4268b93ec354f169">createVGPRAllocPass</a>, <a href="#a20d9cc889332d421bfb591e473db3601">createWWMRegAllocPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afca294f99feddadf494d8c8eb1b27c79">llvm::GCNPreRALongBranchRegID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#afc34b50470e3500e917ae44533e29350">RegAllocOptNotSupportedMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f8876435c197abef541d1c969ea0b63">llvm::SILowerSGPRSpillsLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82ecd626d44669bdd70394f8f411355b">llvm::SILowerWWMCopiesLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a997785f46d9c6dcbf883ffd6ff99713a">llvm::SIPreAllocateWWMRegsLegacyID</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a02a18e7b86433276cfda5efe4c95fdf5">llvm::TargetPassConfig::usingDefaultRegAlloc</a>.</p>

</div>
</div>

### addRegAssignAndRewriteOptimized() {#a598bda274297556dcbff4950a9d76444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addRegAssignAndRewriteOptimized ()</td>
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



<p>Definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="#a27b4ef77d4c6d7c070e0e92f1ed03b04">addPreRewrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae9d2d804eca92a446833b1a9923c52d5">llvm::AMDGPUMarkLastScratchLoadID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ab17529dbc8213c26c4ecc1453b01c1">llvm::AMDGPUReserveWWMRegsID</a>, <a href="#a22399dbddf111b9bda1744d4c273a593">createSGPRAllocPass</a>, <a href="#a378df4e13ead88fb4268b93ec354f169">createVGPRAllocPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd97ebfb34e1008455408c6c7e795089">llvm::createVirtRegRewriter</a>, <a href="#a20d9cc889332d421bfb591e473db3601">createWWMRegAllocPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afca294f99feddadf494d8c8eb1b27c79">llvm::GCNPreRALongBranchRegID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#afc34b50470e3500e917ae44533e29350">RegAllocOptNotSupportedMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f8876435c197abef541d1c969ea0b63">llvm::SILowerSGPRSpillsLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82ecd626d44669bdd70394f8f411355b">llvm::SILowerWWMCopiesLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a997785f46d9c6dcbf883ffd6ff99713a">llvm::SIPreAllocateWWMRegsLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947df27369e5b0e5d44b3109f1cc592d">llvm::StackSlotColoringID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a02a18e7b86433276cfda5efe4c95fdf5">llvm::TargetPassConfig::usingDefaultRegAlloc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac497af2dd82f999474d8fd289077ab4f">llvm::VirtRegRewriterID</a>.</p>

</div>
</div>

### addRegBankSelect() {#a1ce176d2bddc4a3f88632b6848ad925e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNPassConfig::addRegBankSelect ()</td>
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

<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks.</p>

<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1a0112c290ab4df9241168028ecf8b1">llvm::createAMDGPURegBankLegalizePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae7972cccd75a29d29cee9224ee08383">llvm::createAMDGPURegBankSelectPass</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ab8a9d06e86ce7ad2b051b65bd7e8cde4">NewRegBankSelect</a>.</p>

</div>
</div>

### createMachineScheduler() {#abee7911947922a80fe782ead0742972e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * GCNPassConfig::createMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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

<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level.</p>


<p>This can also be used to plug a new MachineSchedStrategy into an instance of the standard ScheduleDAGMI: return new ScheduleDAGMI(C, std::make_unique&lt;MyStrategy&gt;(C), /*RemoveKillFlags=*‍/false)</p>


<p>Return NULL to select the default (generic) machine scheduler.</p>


<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a6639ea61d6d969e494a0e730c2e540b5">AMDGPUSchedStrategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a2f08c3354af71da1c6f857e74e7a32a0">createGCNMaxILPMachineScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a4ae929254e7bc59ee3bfab916429b5ad">createGCNMaxMemoryClauseMachineScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ae61f15457e585b0e1c5564c8d971f1fd">createGCNMaxOccupancyMachineScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ad6a198cbac6862bdcb6f31447e5e0519">createSIMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>

</div>
</div>

### createPostMachineScheduler() {#abc91f335d0788469b44e409f15109585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createPostMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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

<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled.</p>

<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2002164aea6fabe20598e0526746b1fa">llvm::ScheduleDAGMI::addMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38eb48765c2d3082354340365c747dd7">llvm::createIGroupLPDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36ef7fb029dbd7ed2314db341b9f854">llvm::createLoadClusterDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bc2ad470d8a41e9423748814b0e3596">llvm::createStoreClusterDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4400835607d9a305af0952607e48b2d0">llvm::createVOPDPairingMutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ae1ff9bdd782ffd05efaf3465280c3521">EnableVOPD</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupassconfig/#a16f2b92989c6760a2447933b3c78a755">llvm::AMDGPUPassConfig::isPassEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a352cc1831da7694e67bfa9c7fdfa3e7f">llvm::AMDGPU::PostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

### createRegAllocPass() {#a4d247e02f920febb3186ff26c27d88ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * GCNPassConfig::createRegAllocPass (bool Optimized)</td>
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

<p>addMachinePasses helper to create the target-selected or overriden regalloc pass.</p>


<p>Find and instantiate the register allocation pass requested by this target at the current optimization level.</p>


<p>Different register allocators are defined as separate passes because they may require different analysis.</p>


<p>This helper ensures that the regalloc= option is always available, even for targets that override the default allocator.</p>


<p>FIXME: When <a href="/web-llvm/docs/api/classes/llvm/machinepassregistry">MachinePassRegistry</a> register pass IDs instead of function ptrs, this can be folded into addPass.</p>


<p>Definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### createSGPRAllocPass() {#a22399dbddf111b9bda1744d4c273a593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * GCNPassConfig::createSGPRAllocPass (bool Optimized)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a073a6b54ae729a7dc321b342e8c89a84">llvm::createFastRegisterAllocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e408e746db9cae453eb2799eedc64ce">llvm::createGreedyRegisterAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; SGPRRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a726fd49de2283496d73033e546e3572d">anonymous{AMDGPUTargetMachine.cpp}::InitializeDefaultSGPRRegisterAllocatorFlag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a66feaf05deb0d9a39e9bc9fce7881e07">anonymous{AMDGPUTargetMachine.cpp}::initializeDefaultSGPRRegisterAllocatorOnce</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a6d828a500b726dc52f7addecd99e841b">anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateSGPRs</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a592fac5463691d70118200da24479ba0">anonymous{AMDGPUTargetMachine.cpp}::useDefaultRegisterAllocator</a>.</p>


<p>Referenced by <a href="#ab8c5c73df865e6fa5a9fd1eb2b026168">addRegAssignAndRewriteFast</a> and <a href="#a598bda274297556dcbff4950a9d76444">addRegAssignAndRewriteOptimized</a>.</p>

</div>
</div>

### createVGPRAllocPass() {#a378df4e13ead88fb4268b93ec354f169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * GCNPassConfig::createVGPRAllocPass (bool Optimized)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#aa140cd1314a0e3966248ac0e224fe575">anonymous{AMDGPUTargetMachine.cpp}::createFastVGPRRegisterAllocator</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a0fd5bce724ce98bb3e36e87b5dd6b671">anonymous{AMDGPUTargetMachine.cpp}::createGreedyVGPRRegisterAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; VGPRRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#adb72577d3d0924420158c7937e626f27">anonymous{AMDGPUTargetMachine.cpp}::InitializeDefaultVGPRRegisterAllocatorFlag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a96dfb7cdef3ae777878e041a33fa7f89">anonymous{AMDGPUTargetMachine.cpp}::initializeDefaultVGPRRegisterAllocatorOnce</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a592fac5463691d70118200da24479ba0">anonymous{AMDGPUTargetMachine.cpp}::useDefaultRegisterAllocator</a>.</p>


<p>Referenced by <a href="#ab8c5c73df865e6fa5a9fd1eb2b026168">addRegAssignAndRewriteFast</a> and <a href="#a598bda274297556dcbff4950a9d76444">addRegAssignAndRewriteOptimized</a>.</p>

</div>
</div>

### createWWMRegAllocPass() {#a20d9cc889332d421bfb591e473db3601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * GCNPassConfig::createWWMRegAllocPass (bool Optimized)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a0b8ffd597d374a6cbce4df9d9e89bdbb">anonymous{AMDGPUTargetMachine.cpp}::createFastWWMRegisterAllocator</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#ad69455adeb51c0fcaec0882663c9b7f2">anonymous{AMDGPUTargetMachine.cpp}::createGreedyWWMRegisterAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; WWMRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a0846d1ad8d8c0ed0713e96fffbe926b0">anonymous{AMDGPUTargetMachine.cpp}::InitializeDefaultWWMRegisterAllocatorFlag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a1091d237d4f9dae078a6692ceab27de8">anonymous{AMDGPUTargetMachine.cpp}::initializeDefaultWWMRegisterAllocatorOnce</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a592fac5463691d70118200da24479ba0">anonymous{AMDGPUTargetMachine.cpp}::useDefaultRegisterAllocator</a>.</p>


<p>Referenced by <a href="#ab8c5c73df865e6fa5a9fd1eb2b026168">addRegAssignAndRewriteFast</a> and <a href="#a598bda274297556dcbff4950a9d76444">addRegAssignAndRewriteOptimized</a>.</p>

</div>
</div>

### getGCNTargetMachine() {#ac2231566b709be60b56bf00c6b29a4b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNTargetMachine &amp; anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::getGCNTargetMachine ()</td>
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



<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
