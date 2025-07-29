---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86targetmachine-cpp-/x86passconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86PassConfig` Class

<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86TargetMachine.cpp}::X86PassConfig { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-Independent Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb42cc47267e3ff970a3293013e32780">X86PassConfig</a> (X86TargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4818c762893e8d487fb10381f455aa23">getX86TargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc00aa28a4021e0ef7b45384a0e160bb">createMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level. <a href="#acc00aa28a4021e0ef7b45384a0e160bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9c01f8c6c6a81d28dee4e1d973c839">createPostMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled. <a href="#abc9c01f8c6c6a81d28dee4e1d973c839">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c4807821db20fbcf4babd1fc659f7">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a4a1c4807821db20fbcf4babd1fc659f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa53c38f16c31726617ebce8159b0b0e7">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#aa53c38f16c31726617ebce8159b0b0e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b89b777d297254f24196814c284a9bb">addIRTranslator</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes. <a href="#a1b89b777d297254f24196814c284a9bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921c03222a62b7ef446b045727669e22">addLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target. <a href="#a921c03222a62b7ef446b045727669e22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea268c0edfeb6c101065097f119b4a3">addRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks. <a href="#a1ea268c0edfeb6c101065097f119b4a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a974e00a88681009dbb16bab0b7090cd5">addGlobalInstructionSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes. <a href="#a974e00a88681009dbb16bab0b7090cd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409414cb392d30184c0ca8f919871338">addILPOpts</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes that optimize instruction level parallelism for out-of-order targets. <a href="#a409414cb392d30184c0ca8f919871338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af071ce1c6309fb92f11ae42dab34f4ed">addPreISel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#af071ce1c6309fb92f11ae42dab34f4ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d65456551b2fd62e896d8d1331c705a">addMachineSSAOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form. <a href="#a6d65456551b2fd62e896d8d1331c705a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5319393f1878214b8e24021a94424353">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#a5319393f1878214b8e24021a94424353">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04d110e1d671815a3730a88dd798953a">addPostFastRegAllocRewrite</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addPostFastRegAllocRewrite - Add passes to the optimized register allocation pipeline after fast register allocation is complete. <a href="#a04d110e1d671815a3730a88dd798953a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f3edd99fcc73e684fc3b1b4bcc4b1c">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#a08f3edd99fcc73e684fc3b1b4bcc4b1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324af9c253f0762dc05cfbf661ea06a3">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#a324af9c253f0762dc05cfbf661ea06a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace28f980685bf5095e675011d49b97b5">addPreEmitPass2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may add passes immediately before machine code is emitted in this callback. <a href="#ace28f980685bf5095e675011d49b97b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf047765574e0bbd2bbf1742bc06164">addPreSched2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#a2bf047765574e0bbd2bbf1742bc06164">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad1829e004248efafe7f4ac66dbfa48">addRegAssignAndRewriteOptimized</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/cseconfigbase">CSEConfigBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d8d7e822f489f3a3cc30ff7efc7718">getCSEConfig</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the CSEConfig object to use for the current optimization level. <a href="#a77d8d7e822f489f3a3cc30ff7efc7718">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86PassConfig() {#aeb42cc47267e3ff970a3293013e32780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86TargetMachine.cpp}::X86PassConfig::X86PassConfig (<a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGlobalInstructionSelect() {#a974e00a88681009dbb16bab0b7090cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addGlobalInstructionSelect ()</td>
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

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35a47431e5850ecfcf62abce80184d10">llvm::createX86GlobalBaseRegPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a666c13c65a48d84e24fd2216d6ffb299">llvm::TargetPassConfig::isGlobalISelAbortEnabled</a>.</p>

</div>
</div>

### addILPOpts() {#a409414cb392d30184c0ca8f919871338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addILPOpts ()</td>
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


<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a018a4b20713641e238f70225c15a51">llvm::createX86CmovConverterPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57e66365c51f9fe42173246196dc25f1">llvm::EarlyIfConverterLegacyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-cpp/#a0c4b282869e4cacc995ab58c138cc283">EnableMachineCombinerPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a62834da6fd24fb8766861fafa8c4049e">llvm::MachineCombinerID</a>.</p>

</div>
</div>

### addInstSelector() {#aa53c38f16c31726617ebce8159b0b0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addInstSelector ()</td>
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

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a473ee30de68dbcd22e515a82f31cf656">llvm::createCleanupLocalDynamicTLSPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54e328d153daae610ba4d9f57243299a">llvm::createX86ArgumentStackSlotPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35a47431e5850ecfcf62abce80184d10">llvm::createX86GlobalBaseRegPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84fdd2784484546a44b2d739234bbc5f">llvm::createX86ISelDag</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="#a4818c762893e8d487fb10381f455aa23">getX86TargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addIRPasses() {#a4a1c4807821db20fbcf4babd1fc659f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addIRPasses ()</td>
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

<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac36be5551fad7b07b40a2e47c65df7b8">llvm::createCFGuardCheckPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4c365f460495219c9152017a295c6d93">llvm::createCFGuardDispatchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a052f90e5e4af6a011adf970b4a504aa1">llvm::createIndirectBrExpandPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb1bd00fb1d7e33e5f85634b1691e22">llvm::createInterleavedAccessPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ff6249a4edaaa88c875acff3e8a44ff">llvm::createJMCInstrumenterPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35567442b23cff33e6089946f2565171">llvm::createX86LowerAMXIntrinsicsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad16e92f5dfb41058c8bd8041eab47eb8">llvm::createX86LowerAMXTypePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf4bf59218581e35ff9ed052d6cdaad">llvm::createX86PartialReductionPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### addIRTranslator() {#a1b89b777d297254f24196814c284a9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addIRTranslator ()</td>
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

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addLegalizeMachineIR() {#a921c03222a62b7ef446b045727669e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addLegalizeMachineIR ()</td>
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

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a6d65456551b2fd62e896d8d1331c705a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addMachineSSAOptimization ()</td>
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


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e1dc65c445136e2e59dbee92ccd5f7d">llvm::TargetPassConfig::addMachineSSAOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1951327a75cef2ae084ce8f8d59dbe">llvm::createX86DomainReassignmentPass</a>.</p>

</div>
</div>

### addPostFastRegAllocRewrite() {#a04d110e1d671815a3730a88dd798953a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addPostFastRegAllocRewrite ()</td>
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

<p>addPostFastRegAllocRewrite - Add passes to the optimized register allocation pipeline after fast register allocation is complete.</p>

<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99bd7b5447d842f7b5c0ab48c000eb62">llvm::createX86FastTileConfigPass</a>.</p>

</div>
</div>

### addPostRegAlloc() {#a08f3edd99fcc73e684fc3b1b4bcc4b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01053b0e973137b89d97ae9a39ad5c55">llvm::createX86FloatingPointStackifierPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b1664886d672057bf64af88ed165c14">llvm::createX86LoadValueInjectionLoadHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a626043415dcbf36addd46cbe04319ef7">llvm::createX86LowerTileCopyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreEmitPass() {#a324af9c253f0762dc05cfbf661ea06a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addPreEmitPass ()</td>
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

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa90b598062541e048f08b37ba0b5c09a">llvm::createBreakFalseDeps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f1934f3819c352d9066427fdf5e6a40">llvm::createX86CompressEVEXPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5981309b619a66f6281991a064e98df">llvm::createX86DiscriminateMemOpsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35a6bc20dd68076af458d8277d7147f2">llvm::createX86FixupBWInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a803f118b423c70ddf21b8d792188caec">llvm::createX86FixupInstTuning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e7f3d9c4768af8cdf6dddb6ef7ddeda">llvm::createX86FixupLEAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f10fdfdbba0f27bc6abedab4254ca6">llvm::createX86FixupVectorConstants</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66d6a1b0a1fa474139da02d820d618fe">llvm::createX86IndirectBranchTrackingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23e0568f4e49c661d4d025388c5cf075">llvm::createX86InsertPrefetchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6729482051bfb225fd6918bd7ff32f3c">llvm::createX86InsertX87waitPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c191a02e30ab550dac7f4b1be4afa36">llvm::createX86IssueVZeroUpperPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b9ffeb492d751fa2ad75e712b83b64e">llvm::createX86PadShortFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreEmitPass2() {#ace28f980685bf5095e675011d49b97b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addPreEmitPass2 ()</td>
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

<p>Targets may add passes immediately before machine code is emitted in this callback.</p>


<p>This is called even later than <span class="doxyComputerOutput">addPreEmitPass</span>.</p>


<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aacf1ad1887ce35e59410fb29054780">llvm::createCFGuardLongjmpPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2b327c7c629fcfc7c9cc56aec362cd5">llvm::createCFIInstrInserter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae0ddc4f9737f32e48735c72aa4f04fe1">llvm::createEHContGuardCatchretPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30ffad3307c3359586e50f708c7f184e">llvm::createPseudoProbeInserter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab628faa2ee8b55120fb6b1545a346bfd">llvm::createUnpackMachineBundles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc8bc3eb27d86f7c1a4ecf14235e5a56">llvm::createX86AvoidTrailingCallPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add7bb08aab671455134f62c9329ec073">llvm::createX86IndirectThunksPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3fb23437da92cbb296d08b79fd6a470d">llvm::createX86LoadValueInjectionRetHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee08a075888dec5d3dee12b6fc33696d">llvm::createX86ReturnThunksPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45a1a5aa25daa5c2d49d6a71ec88125d">llvm::createX86SpeculativeExecutionSideEffectSuppression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ab4fe87e4046ecd1f9f3d96bbf63822b3">llvm::DwarfCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af2741cb32381997a1e0f074f63d977ae">llvm::MCAsmInfo::getExceptionHandlingType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### addPreISel() {#af071ce1c6309fb92f11ae42dab34f4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addPreISel ()</td>
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


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0641056a8623d0cbbc16d705395bc75a">llvm::createX86WinEHStatePass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>.</p>

</div>
</div>

### addPreRegAlloc() {#a5319393f1878214b8e24021a94424353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addPreRegAlloc ()</td>
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

<p>This method may be implemented by targets that want to run passes immediately before register allocation.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af00fc33962f66e4006d5c0c179408cd8">llvm::createX86AvoidStoreForwardingBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab041955f65fc5bc376466c4fc85abde">llvm::createX86CallFrameOptimization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdfd60cb27d9acb066df1fd71f42105b">llvm::createX86DynAllocaExpander</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f99bca3b24146d28947ca4cc988161a">llvm::createX86FastPreTileConfigPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66b247ef7806abcc6e0b9ab6a2f2f2b6">llvm::createX86FixupSetCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a489a6a86cb21ef5841fc79541adadc89">llvm::createX86FlagsCopyLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6092a0417647a36e59c3c58c7b94367">llvm::createX86OptimizeLEAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aea807b244e780c9de5547997a5522088">llvm::createX86PreTileConfigPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65f5a5f0179a8e1cbb425fe8bf33069d">llvm::createX86SpeculativeLoadHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc40d274956b3912088a148d6e0e809d">llvm::createX86WinFixupBufferSecurityCheckPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78f393d2f578a374d322edd33c27ec37">llvm::LiveRangeShrinkID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreSched2() {#a2bf047765574e0bbd2bbf1742bc06164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86PassConfig::addPreSched2 ()</td>
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

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7647f86ce7db39f6024e16d41a1650ed">llvm::createKCFIPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a797824a83cee5c3514b8e88ae0ec8c11">llvm::createX86ExpandPseudoPass</a>.</p>

</div>
</div>

### addRegAssignAndRewriteOptimized() {#acad1829e004248efafe7f4ac66dbfa48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addRegAssignAndRewriteOptimized ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a94d238c15b46f46b3e99ec226fa26402">llvm::TargetPassConfig::addRegAssignAndRewriteOptimized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e408e746db9cae453eb2799eedc64ce">llvm::createGreedyRegisterAllocator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a6b901a0350b91449ac133807999289">llvm::createX86TileConfigPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#a40308b830aa32a1b90441cbf6a31dc5e">EnableTileRAPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6f81ebaba440d56ca78c806f562c9a1b">llvm::TargetPassConfig::isCustomizedRegAlloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#a9c40319b4934622623e10864866f6ecf">onlyAllocateTileRegisters</a>.</p>

</div>
</div>

### addRegBankSelect() {#a1ea268c0edfeb6c101065097f119b4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86PassConfig::addRegBankSelect ()</td>
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

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### createMachineScheduler() {#acc00aa28a4021e0ef7b45384a0e160bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{X86TargetMachine.cpp}::X86PassConfig::createMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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

<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level.</p>


<p>This can also be used to plug a new MachineSchedStrategy into an instance of the standard ScheduleDAGMI: return new ScheduleDAGMI(C, std::make_unique&lt;MyStrategy&gt;(C), /*RemoveKillFlags=*‍/false)</p>


<p>Return NULL to select the default (generic) machine scheduler.</p>


<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2002164aea6fabe20598e0526746b1fa">llvm::ScheduleDAGMI::addMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6080c6e434453b82694b4ef349fa8b79">llvm::createX86MacroFusionDAGMutation</a>.</p>

</div>
</div>

### createPostMachineScheduler() {#abc9c01f8c6c6a81d28dee4e1d973c839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{X86TargetMachine.cpp}::X86PassConfig::createPostMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2002164aea6fabe20598e0526746b1fa">llvm::ScheduleDAGMI::addMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2f0c2f2a077d67dc0bcb24bc31e3b05">llvm::createGenericSchedPostRA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6080c6e434453b82694b4ef349fa8b79">llvm::createX86MacroFusionDAGMutation</a>.</p>

</div>
</div>

### getCSEConfig() {#a77d8d7e822f489f3a3cc30ff7efc7718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSEConfigBase &gt; X86PassConfig::getCSEConfig ()</td>
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

<p>Returns the CSEConfig object to use for the current optimization level.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4df597e75df6566e28b92bc525a093fb">llvm::getStandardCSEConfigForOpt</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### getX86TargetMachine() {#a4818c762893e8d487fb10381f455aa23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86TargetMachine &amp; anonymous{X86TargetMachine.cpp}::X86PassConfig::getX86TargetMachine ()</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#aa53c38f16c31726617ebce8159b0b0e7">addInstSelector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp">X86TargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
