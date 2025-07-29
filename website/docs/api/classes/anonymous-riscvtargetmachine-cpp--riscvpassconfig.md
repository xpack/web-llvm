---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVPassConfig` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff91c4562be0d3d5fbf198128208b7b3">RISCVPassConfig</a> (RISCVTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine">RISCVTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27a64323276bc614dfbad7ccaea6969">getRISCVTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407041e55fa1f623a4ffa56436b5606b">createMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level. <a href="#a407041e55fa1f623a4ffa56436b5606b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981486e15f588bdbce922588c8efc899">createPostMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled. <a href="#a981486e15f588bdbce922588c8efc899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e61fde0e7b339c7d80bffc620cae9e">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a84e61fde0e7b339c7d80bffc620cae9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5102e947fb4b8eb6df44076550b0932">addPreISel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#aa5102e947fb4b8eb6df44076550b0932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ccde565a879c650a351c241c3ded38">addCodeGenPrepare</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add pass to prepare the LLVM IR for code generation. <a href="#a26ccde565a879c650a351c241c3ded38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d67a66099fbd2539b2f08ee40e89fa">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a19d67a66099fbd2539b2f08ee40e89fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea27c90fe3715a3fdff57ebdc05961b">addIRTranslator</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes. <a href="#a3ea27c90fe3715a3fdff57ebdc05961b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b548a250605b613b063b914759d97d">addPreLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before legalization. <a href="#aa4b548a250605b613b063b914759d97d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffe1247c2ed65cfe28f9b8559fc6b60">addLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target. <a href="#acffe1247c2ed65cfe28f9b8559fc6b60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d63b05994602cb8ed4c5bb2b7a58104">addPreRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before the register bank selection. <a href="#a0d63b05994602cb8ed4c5bb2b7a58104">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3ea38945bedb20f172040147b21de5">addRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks. <a href="#afa3ea38945bedb20f172040147b21de5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75364ce3d7cd5de0849be66d54daf40">addGlobalInstructionSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes. <a href="#ac75364ce3d7cd5de0849be66d54daf40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6595c29823c270fc695147623a1179">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#acd6595c29823c270fc695147623a1179">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a373d9e90c782cb9d8d84cbe4282f10d6">addPreEmitPass2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may add passes immediately before machine code is emitted in this callback. <a href="#a373d9e90c782cb9d8d84cbe4282f10d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1099002b991ffc332e4dfe16dbe62b4">addPreSched2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#ab1099002b991ffc332e4dfe16dbe62b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79163aeadc46557eb643d6be5dcd37a1">addMachineSSAOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form. <a href="#a79163aeadc46557eb643d6be5dcd37a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133a13b65f016ae40049bb567e6c1850">createRVVRegAllocPass</a> (bool Optimized)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a13906a1e82f11750c90da5c8b002c">addRegAssignAndRewriteFast</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add core register allocator passes which do the actual register assignment and rewriting. <a href="#ad6a13906a1e82f11750c90da5c8b002c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02591d59a880da83ce4de3f78d24e721">addRegAssignAndRewriteOptimized</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb50f4d9f449524cc16b192b03979e1">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#acdb50f4d9f449524cc16b192b03979e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd7a622a58a666a25265fae614784ca8">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#acd7a622a58a666a25265fae614784ca8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c144d09717f47854e750b54d18c8ba">addFastRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation. <a href="#af1c144d09717f47854e750b54d18c8ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/cseconfigbase">CSEConfigBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf4fe24e87983a4a2e5bebdb0a1c822">getCSEConfig</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the CSEConfig object to use for the current optimization level. <a href="#a5bf4fe24e87983a4a2e5bebdb0a1c822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVPassConfig() {#aff91c4562be0d3d5fbf198128208b7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::RISCVPassConfig (<a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine">RISCVTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a1d12f56505e14b7444bf5fcf8409af7d">llvm::TargetPassConfig::EnableLoopTermFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a2e23d3db2edb9b94dd6df4f78d8a4166">EnableSinkFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51a34bf4ca8119bdeb89ffc48c5d4783">llvm::PostMachineSchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a7f80b6261618502ecc2ece029f3a7371">llvm::TargetPassConfig::setEnableSinkAndFold</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e22488ba2ab98ca21d3d1377e4ba26a">llvm::TargetPassConfig::substitutePass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGenPrepare() {#a26ccde565a879c650a351c241c3ded38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addCodeGenPrepare ()</td>
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

<p>Add pass to prepare the LLVM IR for code generation.</p>


<p>This should be done before exception handling preparation passes.</p>


<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3082a93fec84f7658664ce7b4840b15c">llvm::TargetPassConfig::addCodeGenPrepare</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d1fac35a424195b35f9986e09c767e0">llvm::createTypePromotionLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addFastRegAlloc() {#af1c144d09717f47854e750b54d18c8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addFastRegAlloc ()</td>
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


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8473cd921ce0dee1a2b3b0ab484708cc">llvm::TargetPassConfig::addFastRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a19f0d598a96bac224de3572f125e1e1b">llvm::InitUndefID</a>.</p>

</div>
</div>

### addGlobalInstructionSelect() {#ac75364ce3d7cd5de0849be66d54daf40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addGlobalInstructionSelect ()</td>
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

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addInstSelector() {#a19d67a66099fbd2539b2f08ee40e89fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addInstSelector ()</td>
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

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acbf879eebbdb64865b6b2d07053f5ab1">llvm::createRISCVISelDag</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="#ac27a64323276bc614dfbad7ccaea6969">getRISCVTargetMachine</a>.</p>

</div>
</div>

### addIRPasses() {#a84e61fde0e7b339c7d80bffc620cae9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addIRPasses ()</td>
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

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb1bd00fb1d7e33e5f85634b1691e22">llvm::createInterleavedAccessPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c077d5ecfb6be89f42babfdce5a71d3">llvm::createLoopDataPrefetchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5a7a65c5eafc9441e7bf3d55b127afb">llvm::createRISCVCodeGenPreparePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a4396fd1c4e96b735f38972d967abbb">llvm::createRISCVGatherScatterLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6818edd05d260eb24501133aa7d85b6">llvm::createRISCVZacasABIFixPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ac4c62565f35006824b9f25fe3ae028cc">EnableLoopDataPrefetch</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addIRTranslator() {#a3ea27c90fe3715a3fdff57ebdc05961b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addIRTranslator ()</td>
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

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addLegalizeMachineIR() {#acffe1247c2ed65cfe28f9b8559fc6b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addLegalizeMachineIR ()</td>
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

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a79163aeadc46557eb643d6be5dcd37a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addMachineSSAOptimization ()</td>
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


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e1dc65c445136e2e59dbee92ccd5f7d">llvm::TargetPassConfig::addMachineSSAOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9caa87fec78d097d9c193f174f45f903">llvm::createRISCVOptWInstrsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc06baa2270331888dd4e68abbd4441c">llvm::createRISCVVectorPeepholePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#af61e3b73d9d43568caa834ee55305ec1">EnableMachineCombiner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62834da6fd24fb8766861fafa8c4049e">llvm::MachineCombinerID</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPostRegAlloc() {#acd7a622a58a666a25265fae614784ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76150f5c071558a6335ef1a6d698fc15">llvm::createRISCVRedundantCopyEliminationPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ab116eea21c829ed214f066676ba08711">EnableRedundantCopyElimination</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreEmitPass() {#acd6595c29823c270fc695147623a1179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPreEmitPass ()</td>
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

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6efaf90f46371b2a436e3d95530491fe">llvm::BranchRelaxationPassID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae3d36829312751f45f383b1c4f95a52e">llvm::createMachineCopyPropagationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cb2ba499a28130da348235c347a571">llvm::createRISCVMakeCompressibleOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#aab219e28b61b68315474ef1e16d4aeb0">EnableRISCVCopyPropagation</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreEmitPass2() {#a373d9e90c782cb9d8d84cbe4282f10d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPreEmitPass2 ()</td>
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


<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bb2ebbd4120567cb1062b5cce764fe2">llvm::createRISCVExpandAtomicPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad41cab08dc876253930a3cac6afde84a">llvm::createRISCVExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9880948b76c573cb65b779dc99df264e">llvm::createRISCVIndirectBranchTrackingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1351236443b144a9ad67fce1f7dea838">llvm::createRISCVMoveMergePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a741bd04b6b04abb102a6c13e31c04a5d">llvm::createRISCVPushPopOptimizationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab628faa2ee8b55120fb6b1545a346bfd">llvm::createUnpackMachineBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#afe43fb9222955bdceb316e851056f516">llvm::Module::getModuleFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreISel() {#aa5102e947fb4b8eb6df44076550b0932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addPreISel ()</td>
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


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa0546121ccb6a6f3638d0d692dbb5f8">llvm::createBarrierNoopPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ef9505eeb810d439c7239e86eca8716">llvm::createGlobalMergePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp/#ac8d706cc05787b7897af799445df6ab4">EnableGlobalMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreLegalizeMachineIR() {#aa4b548a250605b613b063b914759d97d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPreLegalizeMachineIR ()</td>
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

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70c0714a95f6f75bc3eeac8702ac5f40">llvm::createRISCVO0PreLegalizerCombiner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e3e9d476979a52caff15499714a7f3d">llvm::createRISCVPreLegalizerCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreRegAlloc() {#acdb50f4d9f449524cc16b192b03979e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPreRegAlloc ()</td>
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

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31613c591f6cc634214309bb9792843c">llvm::createRISCVInsertReadWriteCSRPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae2b1f300c5180be6e27b6f08da1a3d3a">llvm::createRISCVInsertWriteVXRMPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a022532c07c2d87c2e2b2c1600d639371">llvm::createRISCVLandingPadSetupPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a549303bf280815782bf81577d58776">llvm::createRISCVMergeBaseOffsetOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adaa029f7ed7de899e47b6ae7a6120f56">llvm::createRISCVPreRAExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3952590814ba27de1aad2ac4c5ff442e">llvm::createRISCVVLOptimizerPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#adf236a077b71d539a7e12cbf9df34313">EnableMachinePipeliner</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#a45b29e0cb8c32c24393f453c7e2c7c4a">EnableVLOptimizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9a507e59c5cebcb4277894157ceebb3">llvm::MachinePipelinerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreRegBankSelect() {#a0d63b05994602cb8ed4c5bb2b7a58104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPreRegBankSelect ()</td>
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

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07eae818550c1a5d5f6d471e949339c7">llvm::createRISCVPostLegalizerCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreSched2() {#ab1099002b991ffc332e4dfe16dbe62b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVPassConfig::addPreSched2 ()</td>
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

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7647f86ce7db39f6024e16d41a1650ed">llvm::createKCFIPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2c8bc915c574473cf5c362d32e7ff9f7">llvm::createRISCVPostRAExpandPseudoPass</a>.</p>

</div>
</div>

### addRegAssignAndRewriteFast() {#ad6a13906a1e82f11750c90da5c8b002c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addRegAssignAndRewriteFast ()</td>
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


<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a662881e8843762cf5faebe3885d8f482">llvm::TargetPassConfig::addRegAssignAndRewriteFast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502b0ddd7fb7e5927d923ce924e872e3">llvm::createRISCVDeadRegisterDefinitionsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8db2e8ba2cd1e93d428ad49f96a1e18e">llvm::createRISCVInsertVSETVLIPass</a>, <a href="#a133a13b65f016ae40049bb567e6c1850">createRVVRegAllocPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#adcedc755a8272f96059255799a2b5e21">EnableRISCVDeadRegisterElimination</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addRegAssignAndRewriteOptimized() {#a02591d59a880da83ce4de3f78d24e721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addRegAssignAndRewriteOptimized ()</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a94d238c15b46f46b3e99ec226fa26402">llvm::TargetPassConfig::addRegAssignAndRewriteOptimized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502b0ddd7fb7e5927d923ce924e872e3">llvm::createRISCVDeadRegisterDefinitionsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8db2e8ba2cd1e93d428ad49f96a1e18e">llvm::createRISCVInsertVSETVLIPass</a>, <a href="#a133a13b65f016ae40049bb567e6c1850">createRVVRegAllocPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd97ebfb34e1008455408c6c7e795089">llvm::createVirtRegRewriter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#adcedc755a8272f96059255799a2b5e21">EnableRISCVDeadRegisterElimination</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addRegBankSelect() {#afa3ea38945bedb20f172040147b21de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVPassConfig::addRegBankSelect ()</td>
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

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### createMachineScheduler() {#a407041e55fa1f623a4ffa56436b5606b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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


<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2002164aea6fabe20598e0526746b1fa">llvm::ScheduleDAGMI::addMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36ef7fb029dbd7ed2314db341b9f854">llvm::createLoadClusterDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ff60d96d753c683224740c17f57a2f2">llvm::createRISCVVectorMaskDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bc2ad470d8a41e9423748814b0e3596">llvm::createStoreClusterDAGMutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#ac8ed505d7d56ce5cc5cfa5cab9392c87">DisableVectorMaskMutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#ae6cbe650dda9aa5650fd2ad40786360a">EnableMISchedLoadStoreClustering</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

### createPostMachineScheduler() {#a981486e15f588bdbce922588c8efc899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createPostMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2002164aea6fabe20598e0526746b1fa">llvm::ScheduleDAGMI::addMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2f0c2f2a077d67dc0bcb24bc31e3b05">llvm::createGenericSchedPostRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36ef7fb029dbd7ed2314db341b9f854">llvm::createLoadClusterDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bc2ad470d8a41e9423748814b0e3596">llvm::createStoreClusterDAGMutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#a423c2ea361febbba28d4a403c5c65e1b">EnablePostMISchedLoadStoreClustering</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

### createRVVRegAllocPass() {#a133a13b65f016ae40049bb567e6c1850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * RISCVPassConfig::createRVVRegAllocPass (bool Optimized)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-/#a0d212434da967befff1b11fd1def2fda">anonymous{RISCVTargetMachine.cpp}::createFastRVVRegisterAllocator</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-/#a50a284982f3dc9458a0008856a9489c0">anonymous{RISCVTargetMachine.cpp}::createGreedyRVVRegisterAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; RVVRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-/#a6bd7d079caa9a4a3fd925c6e3fa00b27">anonymous{RISCVTargetMachine.cpp}::InitializeDefaultRVVRegisterAllocatorFlag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-/#a4ef90e3afb7602d713d746833d7270d4">anonymous{RISCVTargetMachine.cpp}::initializeDefaultRVVRegisterAllocatorOnce</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-/#abb98ca139ad9dfc38c2db160ef607d4f">anonymous{RISCVTargetMachine.cpp}::useDefaultRegisterAllocator</a>.</p>


<p>Referenced by <a href="#ad6a13906a1e82f11750c90da5c8b002c">addRegAssignAndRewriteFast</a> and <a href="#a02591d59a880da83ce4de3f78d24e721">addRegAssignAndRewriteOptimized</a>.</p>

</div>
</div>

### getCSEConfig() {#a5bf4fe24e87983a4a2e5bebdb0a1c822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSEConfigBase &gt; RISCVPassConfig::getCSEConfig ()</td>
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

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4df597e75df6566e28b92bc525a093fb">llvm::getStandardCSEConfigForOpt</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### getRISCVTargetMachine() {#ac27a64323276bc614dfbad7ccaea6969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVTargetMachine &amp; anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::getRISCVTargetMachine ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#a19d67a66099fbd2539b2f08ee40e89fa">addInstSelector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
