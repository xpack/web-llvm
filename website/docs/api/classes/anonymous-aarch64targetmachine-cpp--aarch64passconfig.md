---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64PassConfig` Class Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28524895802517d8f53e5fe7ce3bdf3">AArch64PassConfig</a> (AArch64TargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine">AArch64TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade45842956ab309874aa98e6b65932ff">getAArch64TargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cd4388c6010537824ebe8992c09d5f">createMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level. <a href="#a32cd4388c6010537824ebe8992c09d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ae8bc7ea67b8b545120b6e9d5832d1">createPostMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to createMachineScheduler but used when postRA machine scheduling is enabled. <a href="#ae8ae8bc7ea67b8b545120b6e9d5832d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a893766a6f5979c280a6d937a4d51bb75">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a893766a6f5979c280a6d937a4d51bb75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40314d5e1634192397b4d4e4d78b73c0">addPreISel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#a40314d5e1634192397b4d4e4d78b73c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888822aa114d172197937929d130c2ab">addCodeGenPrepare</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add pass to prepare the LLVM IR for code generation. <a href="#a888822aa114d172197937929d130c2ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd8cde558668250369ff9b23cbbbbb51">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#abd8cde558668250369ff9b23cbbbbb51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7dbbe6ffe8583ca18ae4590e8e0fd4">addIRTranslator</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes. <a href="#a2e7dbbe6ffe8583ca18ae4590e8e0fd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66645743ba2e3e7179aa52fba667927f">addPreLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before legalization. <a href="#a66645743ba2e3e7179aa52fba667927f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c1a8916e9e40b1054a62f9ff6e1614">addLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target. <a href="#a99c1a8916e9e40b1054a62f9ff6e1614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71cee5c16c8e10d2eb03f6bcbeaff9a9">addPreRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before the register bank selection. <a href="#a71cee5c16c8e10d2eb03f6bcbeaff9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01a114d2fc0bff7af5c74a2d388827e">addRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks. <a href="#af01a114d2fc0bff7af5c74a2d388827e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae307ea7e42798b0754978764fab85f00">addGlobalInstructionSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes. <a href="#ae307ea7e42798b0754978764fab85f00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30443d291730c6d57a500f7c7fdaa92f">addMachineSSAOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form. <a href="#a30443d291730c6d57a500f7c7fdaa92f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93142e0240a03a005fa2f52ff28e706">addILPOpts</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes that optimize instruction level parallelism for out-of-order targets. <a href="#ae93142e0240a03a005fa2f52ff28e706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac305cefffb34482da2d19c54e347caa6">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#ac305cefffb34482da2d19c54e347caa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12ca69c1858fb1e0df616b9243ac96c">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#af12ca69c1858fb1e0df616b9243ac96c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e02ef6d484e1b3d856b0ad1416ff810">addPreSched2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#a1e02ef6d484e1b3d856b0ad1416ff810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133b56fc6ec387a6ddad9bd9f23eb4d1">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#a133b56fc6ec387a6ddad9bd9f23eb4d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d91382d623d77443845dde96202b91">addPostBBSections</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately after basic block sections are assigned. <a href="#ad0d91382d623d77443845dde96202b91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04c4188df691a4a71bf7b4997a8100e">addPreEmitPass2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may add passes immediately before machine code is emitted in this callback. <a href="#ab04c4188df691a4a71bf7b4997a8100e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2e229cd96c686316ed262eee2f6fcc">addRegAssignAndRewriteOptimized</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa012680bff81e5c64468237fa738fe">getCSEConfig</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the CSEConfig object to use for the current optimization level. <a href="#affa012680bff81e5c64468237fa738fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64PassConfig() {#ab28524895802517d8f53e5fe7ce3bdf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::AArch64PassConfig (<a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine">AArch64TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a2e23d3db2edb9b94dd6df4f78d8a4166">EnableSinkFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51a34bf4ca8119bdeb89ffc48c5d4783">llvm::PostMachineSchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a7f80b6261618502ecc2ece029f3a7371">llvm::TargetPassConfig::setEnableSinkAndFold</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e22488ba2ab98ca21d3d1377e4ba26a">llvm::TargetPassConfig::substitutePass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGenPrepare() {#a888822aa114d172197937929d130c2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addCodeGenPrepare ()</td>
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


<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3082a93fec84f7658664ce7b4840b15c">llvm::TargetPassConfig::addCodeGenPrepare</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d1fac35a424195b35f9986e09c767e0">llvm::createTypePromotionLegacyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addGlobalInstructionSelect() {#ae307ea7e42798b0754978764fab85f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addGlobalInstructionSelect ()</td>
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

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0dd134d15826a3abcfed9c42bdcc3155">llvm::createAArch64PostSelectOptimize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addILPOpts() {#ae93142e0240a03a005fa2f52ff28e706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addILPOpts ()</td>
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


<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4daf628a3a429b19b836a9d109c16363">llvm::createAArch64CondBrTuning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a63d56b5981bfe70febc2adc7e3672e">llvm::createAArch64ConditionalCompares</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7fd5479a0be55587235e5d6992cc1f02">llvm::createAArch64ConditionOptimizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d5499e1f8ca95f2c88ceeb2b045a9c4">llvm::createAArch64SIMDInstrOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c268b78bb60779c59f41a9212d21c6c">llvm::createAArch64StackTaggingPreRAPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f692c1eeb49235c3f82a2b3b0e75769">llvm::createAArch64StorePairSuppressPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57e66365c51f9fe42173246196dc25f1">llvm::EarlyIfConverterLegacyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#afc92736eaec941441cda197e6ddb5fb1">EnableCCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a1e23687830431b9783ae2a8ba5c67322">EnableCondBrTuning</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a98cb91602aae6c876e7fa15a2550ae4b">EnableCondOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ad406e3834655b047b66b1ff9cb4b43c8">EnableEarlyIfConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a54b725f539bbd34f207d899bb5430785">EnableMCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a71dbfc9c44945a2693da355515d834d2">EnableStPairSuppress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62834da6fd24fb8766861fafa8c4049e">llvm::MachineCombinerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addInstSelector() {#abd8cde558668250369ff9b23cbbbbb51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addInstSelector ()</td>
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

<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae06bef0a024f9e90bce34b007a41b9df">llvm::createAArch64CleanupLocalDynamicTLSPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3c5796c201eb5ca4e24947f3d7bc0aa">llvm::createAArch64ISelDag</a>, <a href="#ade45842956ab309874aa98e6b65932ff">getAArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addIRPasses() {#a893766a6f5979c280a6d937a4d51bb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addIRPasses ()</td>
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

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6b86c713155bca69e937aa91d47ee">llvm::createAArch64Arm64ECCallLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad94ed5b51bc3f2d5e49b0f98654d1740">llvm::createAArch64StackTaggingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b0db116677d9d685f7a07e73a914af">llvm::createCFGSimplificationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac36be5551fad7b07b40a2e47c65df7b8">llvm::createCFGuardCheckPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78a1999200fd47f262b2115ebfbe4f8f">llvm::createComplexDeinterleavingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae28159c054fa79ac71652e2bb0972082">llvm::createEarlyCSEPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35002e316fe760ae40476e3627201a5b">llvm::createFalkorMarkStridedAccessesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb1bd00fb1d7e33e5f85634b1691e22">llvm::createInterleavedAccessPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2dc1e8e7ebe4514d8f79da9e3f39505">llvm::createInterleavedLoadCombinePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ff6249a4edaaa88c875acff3e8a44ff">llvm::createJMCInstrumenterPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52fe42f45635485443c10aa9de4e7825">llvm::createLICMPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c077d5ecfb6be89f42babfdce5a71d3">llvm::createLoopDataPrefetchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cedf757f360f8a9b439d7ff9dcdd981">llvm::createSelectOptimizePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c0b23603da5cadac0b7602fae0dddc5">llvm::createSeparateConstOffsetFromGEPPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a095cbe5fe3e24d225ec696a5f2a429c4">llvm::createSMEABIPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a810c7404f2aaf68fd0e6c242878e66f6">llvm::createSVEIntrinsicOptsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ab74b3e25dc3e12d9f164d1200fcf9495">EnableAtomicTidy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#adf9c215835e347a83d9b24375b69fa13">EnableFalkorHWPFFix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a36e0a4ad7a6d508dea693b02deacd874">EnableGEPOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ac4c62565f35006824b9f25fe3ae028cc">EnableLoopDataPrefetch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a402d70cf47b586196e979c940a3bda75">EnableSelectOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a0e313458d44866783dc37c637ad4136b">EnableSVEIntrinsicOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addIRTranslator() {#a2e7dbbe6ffe8583ca18ae4590e8e0fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addIRTranslator ()</td>
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

<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addLegalizeMachineIR() {#a99c1a8916e9e40b1054a62f9ff6e1614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addLegalizeMachineIR ()</td>
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

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a30443d291730c6d57a500f7c7fdaa92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addMachineSSAOptimization ()</td>
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


<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e1dc65c445136e2e59dbee92ccd5f7d">llvm::TargetPassConfig::addMachineSSAOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a201f90b906734804b7a0b6fac4deee3e">llvm::createAArch64MIPeepholeOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a75022ff3b0cc973ca2b8d7d655247a">llvm::createSMEPeepholeOptPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ac9e5a0bbb4a5167b2b8aa561bce8da32">EnableSMEPeepholeOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPostBBSections() {#ad0d91382d623d77443845dde96202b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPostBBSections ()</td>
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

<p>This pass may be implemented by targets that want to run passes immediately after basic block sections are assigned.</p>

<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a17e189295e53ef7252e5955f320334a2">BranchRelaxation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6efaf90f46371b2a436e3d95530491fe">llvm::BranchRelaxationPassID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab01d3e609a4cec5297c3beca022d4e2f">llvm::createAArch64BranchTargetsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a666813574d51144033d16798a35e25e5">llvm::createAArch64CompressJumpTablesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a382a6a11f75cb1c6644360394893d9e6">llvm::createAArch64PointerAuthPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaecbd2f3b063158048f985b41f36c596">llvm::createAArch64SLSHardeningPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a05e181915ab2df5b003c5a3eeb15219f">EnableBranchTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#af4f34f6c3dc48f1f758719cfc44b8a71">EnableCompressJumpTables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPostRegAlloc() {#af12ca69c1858fb1e0df616b9243ac96c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a49d2a45144c850e22e7ce4db79d3be2a">llvm::createAArch64A57FPLoadBalancing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ab49a9165d403fa47ca2dd750dbb0f4">llvm::createAArch64RedundantCopyEliminationPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ab116eea21c829ed214f066676ba08711">EnableRedundantCopyElimination</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a02a18e7b86433276cfda5efe4c95fdf5">llvm::TargetPassConfig::usingDefaultRegAlloc</a>.</p>

</div>
</div>

### addPreEmitPass() {#a133b56fc6ec387a6ddad9bd9f23eb4d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPreEmitPass ()</td>
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

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc96b1cef8c62f3d398869b0332f81b3">llvm::createAArch64A53Fix835769</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a874c38e0060d3be903d57f16945b95ef">llvm::createAArch64CollectLOHPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fac7522195671ed678db745338eb462">llvm::createAArch64LoadStoreOptimizationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aacf1ad1887ce35e59410fb29054780">llvm::createCFGuardLongjmpPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae0ddc4f9737f32e48735c72aa4f04fe1">llvm::createEHContGuardCatchretPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae3d36829312751f45f383b1c4f95a52e">llvm::createMachineCopyPropagationPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a1785b93df5b7ad6aa41c89303c038918">EnableAArch64CopyPropagation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#aad2f133fbd8a49b8bc1553955955cf23">EnableCollectLOH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a442e4d0e3c6d6fc78ce6995d35fcda6e">EnableLoadStoreOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreEmitPass2() {#ab04c4188df691a4a71bf7b4997a8100e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPreEmitPass2 ()</td>
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


<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab628faa2ee8b55120fb6b1545a346bfd">llvm::createUnpackMachineBundles</a>.</p>

</div>
</div>

### addPreISel() {#a40314d5e1634192397b4d4e4d78b73c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addPreISel ()</td>
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


<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1dee0e28b161d52ffd8a6921ad83e2b">llvm::createAArch64PromoteConstantPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ef9505eeb810d439c7239e86eca8716">llvm::createGlobalMergePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmerge-cpp/#ac8d706cc05787b7897af799445df6ab4">EnableGlobalMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a1e1ae0d5f3a12d751e70b178cd6ad69a">EnablePromoteConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreLegalizeMachineIR() {#a66645743ba2e3e7179aa52fba667927f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPreLegalizeMachineIR ()</td>
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

<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41c07c1e0df10d82b23058bf582a7f75">llvm::createAArch64O0PreLegalizerCombiner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a043956c11fb4512a688ec039e4849a28">llvm::createAArch64PreLegalizerCombiner</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#aadafc8d88628f006a01a7b5227c49c81">EnableGISelLoadStoreOptPreLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreRegAlloc() {#ac305cefffb34482da2d19c54e347caa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPreRegAlloc ()</td>
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

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6212838afb4bda7fa9152af22be8438">llvm::createAArch64AdvSIMDScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56aa8327f36e85423bee38771ecc9e6d">llvm::createAArch64DeadRegisterDefinitions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ab9bf0b1ed5b4680b9a2ed8ec1b4d8c7a">EnableAdvSIMDScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a310081f3bb70c1ad1fe5dc36b69f7e36">EnableDeadRegisterElimination</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#adf236a077b71d539a7e12cbf9df34313">EnableMachinePipeliner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9a507e59c5cebcb4277894157ceebb3">llvm::MachinePipelinerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5233e3ce01bdfffee235d5d772b014dd">llvm::PeepholeOptimizerLegacyID</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreRegBankSelect() {#a71cee5c16c8e10d2eb03f6bcbeaff9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPreRegBankSelect ()</td>
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

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ab63e0cce91a72a2d20d8d93e96deb1">llvm::createAArch64PostLegalizerCombiner</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5cf2d86ae5ed2a3207d2a752871a3373">llvm::createAArch64PostLegalizerLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a47f483f26103bcd9249e0c8319217f46">EnableGISelLoadStoreOptPostLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreSched2() {#a1e02ef6d484e1b3d856b0ad1416ff810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64PassConfig::addPreSched2 ()</td>
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

<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74f77662b6a8f73ec5eb3b17ea3bbd50">llvm::createAArch64ExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fac7522195671ed678db745338eb462">llvm::createAArch64LoadStoreOptimizationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6069f2e1fffd84f93afc22a89caaa22">llvm::createAArch64LowerHomogeneousPrologEpilogPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebdc9b7f7c564450425e2b68a703197b">llvm::createAArch64SpeculationHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38d27219c667afc0854dddd85e51fbf7">llvm::createFalkorHWPFFixPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7647f86ce7db39f6024e16d41a1650ed">llvm::createKCFIPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#adf9c215835e347a83d9b24375b69fa13">EnableFalkorHWPFFix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8fd7d7acb6ac34c5c712c79eda432848">EnableHomogeneousPrologEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a442e4d0e3c6d6fc78ce6995d35fcda6e">EnableLoadStoreOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addRegAssignAndRewriteOptimized() {#a7f2e229cd96c686316ed262eee2f6fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addRegAssignAndRewriteOptimized ()</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a94d238c15b46f46b3e99ec226fa26402">llvm::TargetPassConfig::addRegAssignAndRewriteOptimized</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3155f956ec0a110e5a21e3e165fd9008">llvm::createAArch64PostCoalescerPass</a>.</p>

</div>
</div>

### addRegBankSelect() {#af01a114d2fc0bff7af5c74a2d388827e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64PassConfig::addRegBankSelect ()</td>
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

<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### createMachineScheduler() {#a32cd4388c6010537824ebe8992c09d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::createMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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


<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76a32cac419f39ba98266ca4f5d24edf">llvm::createAArch64MacroFusionDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36ef7fb029dbd7ed2314db341b9f854">llvm::createLoadClusterDAGMutation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7bc2ad470d8a41e9423748814b0e3596">llvm::createStoreClusterDAGMutation</a>.</p>

</div>
</div>

### createPostMachineScheduler() {#ae8ae8bc7ea67b8b545120b6e9d5832d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::createPostMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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

<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a76a32cac419f39ba98266ca4f5d24edf">llvm::createAArch64MacroFusionDAGMutation</a>.</p>

</div>
</div>

### getAArch64TargetMachine() {#ade45842956ab309874aa98e6b65932ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64TargetMachine &amp; anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::getAArch64TargetMachine ()</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#abd8cde558668250369ff9b23cbbbbb51">addInstSelector</a>.</p>

</div>
</div>

### getCSEConfig() {#affa012680bff81e5c64468237fa738fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSEConfigBase &gt; AArch64PassConfig::getCSEConfig ()</td>
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

<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4df597e75df6566e28b92bc525a093fb">llvm::getStandardCSEConfigForOpt</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
