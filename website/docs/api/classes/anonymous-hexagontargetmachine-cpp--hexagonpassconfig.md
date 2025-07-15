---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonPassConfig` Class Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6477286c8a405aa7ec749d4e2a42e22">HexagonPassConfig</a> (HexagonTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine">HexagonTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ac6eaa6cd0f2a0007defff436c81e1">getHexagonTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ec343bc43cccbc53f1d2ea82ee5e2e">createMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of ScheduleDAGInstrs to be run within the standard MachineScheduler pass for this function and target at the current optimization level. <a href="#a58ec343bc43cccbc53f1d2ea82ee5e2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93af065c06aa9526f1e7271b510df04">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#ac93af065c06aa9526f1e7271b510df04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62fb646c12db92e5eb16b019f4a9364a">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a62fb646c12db92e5eb16b019f4a9364a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b527c478a68c3620d05e93db5ef254a">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#a6b527c478a68c3620d05e93db5ef254a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0763413dfa57a881314355bb075ba86">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#ab0763413dfa57a881314355bb075ba86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c44ce1d16724b00c765ae9cb864ef16">addPreSched2</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#a0c44ce1d16724b00c765ae9cb864ef16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383b8a8b877e49abe4c951d6df789d45">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#a383b8a8b877e49abe4c951d6df789d45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonPassConfig() {#aa6477286c8a405aa7ec749d4e2a42e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::HexagonPassConfig (<a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine">HexagonTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInstSelector() {#a62fb646c12db92e5eb16b019f4a9364a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPassConfig::addInstSelector ()</td>
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

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a410406a77809776562d3ee8932840a89">llvm::createHexagonBitSimplify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4bd6d6ca7244bf6d3743967ac75e3e97">llvm::createHexagonConstPropagationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77d881048d50cd387fc5dea2a02ff3b5">llvm::createHexagonEarlyIfConversion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90026ee326d941107b731d3ce9be1c57">llvm::createHexagonGenInsert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a86dd7375b4a67d413db18fa8e93e4d6a">llvm::createHexagonGenPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab0482afae85e7046f1adbfca29a66258">llvm::createHexagonISelDag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c9c8baa8635026abdfd9f56334dccba">llvm::createHexagonLoopRescheduling</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95ccc7d28203cf01d4d759aabf88ef07">llvm::createHexagonOptimizeSZextends</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a44659f67354441ba668258e8b68533ee">llvm::createHexagonPeephole</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc1c152e5494325e7cc150062f09cda0">llvm::createHexagonSplitDoubleRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a86803d67abf6004c18d7eadc6de6adcd">llvm::createHexagonVExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a55b4996648faae0cb0d4744fce912f84">DisableHCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#ab99b217b5d9729f04312e32fe8e7c5f1">DisableHSDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a5990e7fe7cd7d8096de45e14fa388c50">EnableBitSimplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#afe512f21fae028ea9c8f4e953ee39318">EnableEarlyIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#af5f3fab291c6d76110f406fdf0a45550">EnableGenInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a72a98d2b48a2fec0edba6b5022b7b218">EnableGenPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a97fecd006eca978f3ffb7a6e1f7a329f">EnableLoopResched</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a80e9b8b56922bfd06ca6835329a76324">EnableVExtractOpt</a>, <a href="#a22ac6eaa6cd0f2a0007defff436c81e1">getHexagonTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad810a1e96a20217be2b5ce15066af066">llvm::UnreachableMachineBlockElimID</a>.</p>

</div>
</div>

### addIRPasses() {#ac93af065c06aa9526f1e7271b510df04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPassConfig::addIRPasses ()</td>
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

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b0db116677d9d685f7a07e73a914af">llvm::createCFGSimplificationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b274400ee4dddce0e8c2e3056fcef20">llvm::createDeadCodeEliminationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab447a2b92653b244a2d185a5bc32cde">llvm::createHexagonCommonGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7028bf9350e913078cfa086fd925630f">llvm::createHexagonGenExtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0578c331fd8ee347288d62051762e967">llvm::createHexagonVectorCombineLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb65f938406d0b71e233fa1a0d343838">llvm::createInstSimplifyLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c077d5ecfb6be89f42babfdce5a71d3">llvm::createLoopDataPrefetchPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#af865f58a1daf96185c508856931924d5">EnableCommGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a209fddd75f363c5c0edbd0a8313cb6e9">EnableGenExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#ac7ec53b0fca6016afc5c61981aec2c9b">EnableInitialCFGCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a879cc3a727c9ca30b527d05d254a81fe">EnableInstSimplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aaf7b119415eac8f2fe46bb4d78d85f5f">EnableLoopPrefetch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a229a3086c94cd3ee59dd816141e13008">EnableVectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPostRegAlloc() {#ab0763413dfa57a881314355bb075ba86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a124602d73eee88f532e253bbed464352">llvm::createHexagonCFGOptimizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9b81c9d91e8e7f4c9b7912fe505e23f">llvm::createHexagonOptAddrMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb3de6d10c00bf56f276de6751c766ea">llvm::createHexagonRDFOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a34326d3a10edcef836a3aa95be00f412">DisableAModeOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a24853b47ad42af9de33e83f4a569abd3">DisableHexagonCFGOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a8d4d9fcf01479ecfef4f598a31e8cdd8">EnableRDFOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreEmitPass() {#a383b8a8b877e49abe4c951d6df789d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPassConfig::addPreEmitPass ()</td>
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

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3592a5586b246f3bcd673f428e2e8023">llvm::createHexagonBranchRelaxation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f0bdd2765561909895dc619e44a1af3">llvm::createHexagonCallFrameInformation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54fe85cb76f10d03146d17097679972c">llvm::createHexagonFixupHwLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e011678127468a6518acd1d96661944">llvm::createHexagonGenMux</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd6fdf82a4008c96b86e3de2b17299">llvm::createHexagonLoopAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33a91c3cb79103a40634f84756170c23">llvm::createHexagonNewValueJump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63380f1987abfc83e2dd45e71dba56c9">llvm::createHexagonPacketizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a040a120054aa3b161ff296587b54e9c2">llvm::createHexagonVectorPrint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a71a28353a86a87f2223210d101dce96d">DisableHardwareLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a22c9b3518495043b3779f49a6e34b82e">EnableGenMux</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a5f02946c2491d6fa95155b316c24ba65">EnableVectorPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreRegAlloc() {#a6b527c478a68c3620d05e93db5ef254a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPassConfig::addPreRegAlloc ()</td>
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

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a476f55f1fbfd79e76b2edda420c4fae7">llvm::createHexagonConstExtenders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac16a1486e18fab82ba119158beb1f612">llvm::createHexagonGenMemAbsolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad334ebc2f4abb942af36808d05a32fc1">llvm::createHexagonHardwareLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d4417f25287d084cc43156a16e0d5a8">llvm::createHexagonLoadWidening</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f87471061c64b41be2ae6ddd1ebe87">llvm::createHexagonStoreWidening</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a71a28353a86a87f2223210d101dce96d">DisableHardwareLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a903ebd851a50d128ca83e72ca0cc9956">DisableLoadWidening</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a5958ae17ca05a8a58c734199a9ce4446">DisableStoreWidening</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a9001675d305143163d204ed09cc01379">EnableCExtOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a12fc797c36adabd3e7775dc15f416933">EnableCopyHoist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a0d1799ff5c69c94724dd4b6477c260c5">EnableExpandCondsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a7eb61ae65db622827ad31066a501408c">EnableGenMemAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#ab29da7a224120fd6ae08f2569b0f5f45">EnableTfrCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeebc3fb028f2450c451fc27991fce7a0">llvm::HexagonCopyHoistingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab04f9b6c9c9df759be9730257d4e1ab0">llvm::HexagonExpandCondsetsID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1102ba0a14eea634be096c31e9bbb711">llvm::HexagonTfrCleanupID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a36adfc24480b78dfe7a51559b8264de7">llvm::TargetPassConfig::insertPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9a507e59c5cebcb4277894157ceebb3">llvm::MachinePipelinerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a97dc750eaae6c6c05a7f2ab03cdffc">llvm::RegisterCoalescerID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac497af2dd82f999474d8fd289077ab4f">llvm::VirtRegRewriterID</a>.</p>

</div>
</div>

### addPreSched2() {#a0c44ce1d16724b00c765ae9cb864ef16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPassConfig::addPreSched2 ()</td>
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

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa72168265a7515011a734173c9eea486">llvm::createHexagonCopyToCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ca275d2617df094853257ccd42558c2">llvm::createHexagonMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1b58675305d93281675e9b25b69eece">llvm::createHexagonSplitConst32AndConst64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#a944c3cce370690247cfec637332b0b8c">DisableHexagonMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6820b1346e9140b1b40af95c5ec190a">llvm::IfConverterID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### createMachineScheduler() {#a58ec343bc43cccbc53f1d2ea82ee5e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::createMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#aab77d912a7ea86c5c77bc6eacb9adca6">createVLIWMachineSched</a>.</p>

</div>
</div>

### getHexagonTargetMachine() {#a22ac6eaa6cd0f2a0007defff436c81e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonTargetMachine &amp; anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::getHexagonTargetMachine ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#a62fb646c12db92e5eb16b019f4a9364a">addInstSelector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
