---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-spirvtargetmachine-cpp-/spirvpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPIRVPassConfig` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a6d4efcc12c90a148ffd4b37471090">SPIRVPassConfig</a> (SPIRVTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine">SPIRVTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24fa7714b59e37b0d9d98490bf917c3c">getSPIRVTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b35c5bae001f6e5ba644a2317e74c3">addMachineSSAOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form. <a href="#a80b35c5bae001f6e5ba644a2317e74c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6198d33b54a1512672754cd2214ee0">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a1d6198d33b54a1512672754cd2214ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaaf192d50648477defb32dde09a979c">addISelPrepare</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common passes that perform LLVM IR to IR transforms in preparation for instruction selection. <a href="#aaaaf192d50648477defb32dde09a979c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0196e62e22fe0f806ad60d0da201d8b9">addIRTranslator</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes. <a href="#a0196e62e22fe0f806ad60d0da201d8b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402f652315d3b4ba6fd330ff1aa6a713">addPreLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before legalization. <a href="#a402f652315d3b4ba6fd330ff1aa6a713">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f29ba2ae48751cd60b71d48789d4a5d">addLegalizeMachineIR</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target. <a href="#a2f29ba2ae48751cd60b71d48789d4a5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59de015d004a5f101e06162d9699076a">addRegBankSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks. <a href="#a59de015d004a5f101e06162d9699076a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d0918db4ac4c5f349656dd07c0f12d">addGlobalInstructionSelect</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes. <a href="#ad9d0918db4ac4c5f349656dd07c0f12d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9eb07321f4c47ecc902f60c6a03ac8">createTargetRegisterAllocator</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level. <a href="#a6e9eb07321f4c47ecc902f60c6a03ac8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e079080aef432fecd2d4b4038976c0">addFastRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation. <a href="#a35e079080aef432fecd2d4b4038976c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000734ed3e175c4264c656853dd7116f">addOptimizedRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addOptimizedRegAlloc - Add passes related to register allocation. <a href="#a000734ed3e175c4264c656853dd7116f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5b49a4c790fa16cf668d00e0ff7923">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#adf5b49a4c790fa16cf668d00e0ff7923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6613bd083d0f038d36a9b65ac3dfd1">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#a2d6613bd083d0f038d36a9b65ac3dfd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine">SPIRVTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cff4f944d0d10f17a33e06c9491f69b">TM</a></td>
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


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVPassConfig() {#af4a6d4efcc12c90a148ffd4b37471090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::SPIRVPassConfig (<a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine">SPIRVTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFastRegAlloc() {#a35e079080aef432fecd2d4b4038976c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::addFastRegAlloc ()</td>
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

<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation.</p>


<p>Add the minimum set of target-independent passes that are required for register allocation.</p>


<p>No coalescing or scheduling.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>

</div>
</div>

### addGlobalInstructionSelect() {#ad9d0918db4ac4c5f349656dd07c0f12d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVPassConfig::addGlobalInstructionSelect ()</td>
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

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>.</p>

</div>
</div>

### addIRPasses() {#a1d6198d33b54a1512672754cd2214ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVPassConfig::addIRPasses ()</td>
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

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb7682c55116e253e95fcd05564a3c3b">llvm::createLoopSimplifyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18287429a6a702fe387ac86d66d3ad26">llvm::createPromoteMemoryToRegisterPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a298985cd6a2cff3108156659a3d8e4e4">llvm::createRegToMemWrapperPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac29a69003e698e7dff3cb8681bdc8191">llvm::createSPIRVMergeRegionExitTargetsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae75cbc1aead155ebf910eca19f09eb6c">llvm::createSPIRVPrepareFunctionsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa3f2b16fb78301d854c2c4cb401302a">llvm::createSPIRVRegularizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a457096c6a025a652e595e648f8ee5a27">llvm::createSPIRVStripConvergenceIntrinsicsPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a089700341b0cfa4edf89dae2cc1eaa5e">llvm::createSPIRVStructurizerPass</a>.</p>

</div>
</div>

### addIRTranslator() {#a0196e62e22fe0f806ad60d0da201d8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVPassConfig::addIRTranslator ()</td>
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

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addISelPrepare() {#aaaaf192d50648477defb32dde09a979c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVPassConfig::addISelPrepare ()</td>
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

<p>Add common passes that perform LLVM IR to IR transforms in preparation for instruction selection.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#acd370e6335630ad711de582b8bb2fd72">llvm::TargetPassConfig::addISelPrepare</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a211487b8a6087e50068d9dd2bff09c16">llvm::createSPIRVEmitIntrinsicsPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aca23623f476d3929484bdad4a5ce54d8">llvm::TargetPassConfig::getTM</a>.</p>

</div>
</div>

### addLegalizeMachineIR() {#a2f29ba2ae48751cd60b71d48789d4a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVPassConfig::addLegalizeMachineIR ()</td>
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

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a63bb6ecc6ba09650573ace82aac0e368">llvm::createSPIRVPostLegalizerPass</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a80b35c5bae001f6e5ba644a2317e74c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVPassConfig::addMachineSSAOptimization ()</td>
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


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a8e1dc65c445136e2e59dbee92ccd5f7d">llvm::TargetPassConfig::addMachineSSAOptimization</a>.</p>

</div>
</div>

### addOptimizedRegAlloc() {#a000734ed3e175c4264c656853dd7116f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::addOptimizedRegAlloc ()</td>
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

<p>addOptimizedRegAlloc - Add passes related to register allocation.</p>


<p>Add standard target-independent passes that are tightly coupled with optimized register allocation, including coalescing, machine instruction scheduling, and register allocation itself.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a> provides standard regalloc passes for most targets.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>

</div>
</div>

### addPostRegAlloc() {#adf5b49a4c790fa16cf668d00e0ff7923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVPassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a40a9d9de0a8ca42af17c54cf1272fd11">llvm::TargetPassConfig::addPostRegAlloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae39ec6579da91ce8fa292f0a7205d98d">llvm::BranchFolderPassID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85d339220c3769c26cc027fe4cc4dfee">llvm::FuncletLayoutID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a532b041efe66edbeceeb4d90628974d2">llvm::LiveDebugValuesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc14e69cab3ee0a21fdfdd40632b7ee1">llvm::MachineBlockPlacementID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5dc78ed1fd5966782d85bf389333790">llvm::MachineCopyPropagationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d504656f6cc4feb09837a202a4bac92">llvm::MachineLateInstrsCleanupID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ddae16561e646c4cbadec7e4fb5308b">llvm::PatchableFunctionID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d5462b10402ee83291fda8b0b74f437">llvm::PostRAMachineSinkingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40e93d6a1c6ab9b6b1b7ba3a391336cf">llvm::RemoveLoadsIntoFakeUsesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6bfbf70fac2ed039c8bd6b3b0d168117">llvm::ShrinkWrapID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a805432189f97152d1899d08945204faa">llvm::StackMapLivenessID</a>.</p>

</div>
</div>

### addPreEmitPass() {#a2d6613bd083d0f038d36a9b65ac3dfd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVPassConfig::addPreEmitPass ()</td>
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

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20238ed2289069a3916113ff344ff392">llvm::createSPIRVEmitNonSemanticDIPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aca23623f476d3929484bdad4a5ce54d8">llvm::TargetPassConfig::getTM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp/#ac77e1ee06f61d312b16f5250e6f6c17e">SPVEnableNonSemanticDI</a>.</p>

</div>
</div>

### addPreLegalizeMachineIR() {#a402f652315d3b4ba6fd330ff1aa6a713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVPassConfig::addPreLegalizeMachineIR ()</td>
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

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55cd39a23a4267bbd42c2a487fcbd374">llvm::createSPIRVPreLegalizerCombiner</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2f84f3d91e9d25b661853c26312e7380">llvm::createSPIRVPreLegalizerPass</a>.</p>

</div>
</div>

### addRegBankSelect() {#a59de015d004a5f101e06162d9699076a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVPassConfig::addRegBankSelect ()</td>
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

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a> and <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a18a280ae37dbd3b58a04012da318b687">llvm::RegBankSelect::ID</a>.</p>

</div>
</div>

### createTargetRegisterAllocator() {#a6e9eb07321f4c47ecc902f60c6a03ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * SPIRVPassConfig::createTargetRegisterAllocator (bool Optimized)</td>
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

<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level.</p>


<p>Instantiate the default register allocator pass for this target for either the optimized or unoptimized allocation path.</p>


<p>This will be added to the pass manager by addFastRegAlloc in the unoptimized case or addOptimizedRegAlloc in the optimized case.</p>


<p>A target that uses the standard regalloc pass order for fast or optimized allocation may still override this for per-target regalloc selection. But -regalloc=... always takes precedence.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>

</div>
</div>

### getSPIRVTargetMachine() {#a24fa7714b59e37b0d9d98490bf917c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVTargetMachine &amp; anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::getSPIRVTargetMachine ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TM {#a0cff4f944d0d10f17a33e06c9491f69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SPIRVTargetMachine&amp; anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
