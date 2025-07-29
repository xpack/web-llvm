---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WebAssemblyPassConfig` Class

<p><a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac785ca646202e2d20beed2eeb06351">WebAssemblyPassConfig</a> (WebAssemblyTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine">WebAssemblyTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d67bca5947563e8d8a263a99f4222d">getWebAssemblyTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb82e354d23248e7a99cecc1fb98e55">createTargetRegisterAllocator</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level. <a href="#a9eb82e354d23248e7a99cecc1fb98e55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb170544eb9997045ad3d9084cccccc0">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#aeb170544eb9997045ad3d9084cccccc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92398eff530e8269aeaa926aa01b7fb5">addISelPrepare</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common passes that perform LLVM IR to IR transforms in preparation for instruction selection. <a href="#a92398eff530e8269aeaa926aa01b7fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cdafbe47c009568275c8908a24275e3">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a9cdafbe47c009568275c8908a24275e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6b6d0dd0f7cd87c0f0942670254d75">addOptimizedRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addOptimizedRegAlloc - Add passes related to register allocation. <a href="#a9f6b6d0dd0f7cd87c0f0942670254d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78f5786247e095df8dd18dbd7325b56d">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#a78f5786247e095df8dd18dbd7325b56d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec2f7b926c14185ae68634f64675d50">addGCPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addGCPasses - Add late codegen passes that analyze code for garbage collection. <a href="#a0ec2f7b926c14185ae68634f64675d50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4beb7113336e36d1a81ae2ca8ca6d52">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#ab4beb7113336e36d1a81ae2ca8ca6d52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f9c04ecca87ed6772df9d6bb27c836b">addPreISel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#a8f9c04ecca87ed6772df9d6bb27c836b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7db547424baa0e88ca233c404a6a1b">addRegAssignAndRewriteFast</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add core register allocator passes which do the actual register assignment and rewriting. <a href="#a6c7db547424baa0e88ca233c404a6a1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04f0d553e3e7b77d295673ff1e44691b">addRegAssignAndRewriteOptimized</a> () override</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyPassConfig() {#a0ac785ca646202e2d20beed2eeb06351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::WebAssemblyPassConfig (<a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine">WebAssemblyTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGCPasses() {#a0ec2f7b926c14185ae68634f64675d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::addGCPasses ()</td>
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

<p>addGCPasses - Add late codegen passes that analyze code for garbage collection.</p>


<p>Add standard GC passes.</p>


<p>This should return true if GC info should be printed after these passes.</p>


<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

### addInstSelector() {#a9cdafbe47c009568275c8908a24275e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyPassConfig::addInstSelector ()</td>
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

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a45c2bcfa7777e420dc7c979b639afaf9">llvm::TargetPassConfig::addInstSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa4921d475e5ec77dd27b415732f9332f">llvm::createWebAssemblyArgumentMove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96d74c1aa5860b8366cbce34d25a2b1e">llvm::createWebAssemblyCleanCodeAfterTrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d48c5e621cd205d741f520816391b27">llvm::createWebAssemblyFixBrTableDefaults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a856e61e272d0f1021fe331fe12bf9e87">llvm::createWebAssemblyISelDag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5102a65a75df00b435532bc0f5f7e1">llvm::createWebAssemblySetP2AlignOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="#ab4d67bca5947563e8d8a263a99f4222d">getWebAssemblyTargetMachine</a>.</p>

</div>
</div>

### addIRPasses() {#aeb170544eb9997045ad3d9084cccccc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyPassConfig::addIRPasses ()</td>
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

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp/#a563cec1174cd4374050fc2c3007b26a9">basicCheckForEHAndSjLj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a052f90e5e4af6a011adf970b4a504aa1">llvm::createIndirectBrExpandPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72bec3f3cf93a5fed57e2de639a2c58e">llvm::createLowerGlobalDtorsLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73866a00fb633fea123b83d0dec2c073">llvm::createLowerInvokePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12d11d4d4e6bb3d883283ad219cfe6d7">llvm::createUnreachableBlockEliminationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158a1a60588742d800b39d3ce0429e89">llvm::createWebAssemblyAddMissingPrototypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac190cf7a0c3d21937ee46d261fdbeee4">llvm::createWebAssemblyFixFunctionBitcasts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9df37103568a509baca10e4fc7357a5e">llvm::createWebAssemblyLowerEmscriptenEHSjLj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ee885d3546e34b315b9c7730779188a">llvm::createWebAssemblyOptimizeReturned</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addISelPrepare() {#a92398eff530e8269aeaa926aa01b7fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyPassConfig::addISelPrepare ()</td>
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

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#acd370e6335630ad711de582b8bb2fd72">llvm::TargetPassConfig::addISelPrepare</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94f8bfbe825939e6e82f45e2d7095426">llvm::createWebAssemblyRefTypeMem2Local</a> and <a href="#ab4d67bca5947563e8d8a263a99f4222d">getWebAssemblyTargetMachine</a>.</p>

</div>
</div>

### addOptimizedRegAlloc() {#a9f6b6d0dd0f7cd87c0f0942670254d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyPassConfig::addOptimizedRegAlloc ()</td>
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


<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a6481662c2fc1eb7d95b5a32939e24b94">llvm::TargetPassConfig::addOptimizedRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a97dc750eaae6c6c05a7f2ab03cdffc">llvm::RegisterCoalescerID</a>.</p>

</div>
</div>

### addPostRegAlloc() {#a78f5786247e095df8dd18dbd7325b56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyPassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a40a9d9de0a8ca42af17c54cf1272fd11">llvm::TargetPassConfig::addPostRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85d339220c3769c26cc027fe4cc4dfee">llvm::FuncletLayoutID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc14e69cab3ee0a21fdfdd40632b7ee1">llvm::MachineBlockPlacementID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5dc78ed1fd5966782d85bf389333790">llvm::MachineCopyPropagationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d504656f6cc4feb09837a202a4bac92">llvm::MachineLateInstrsCleanupID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ddae16561e646c4cbadec7e4fb5308b">llvm::PatchableFunctionID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d5462b10402ee83291fda8b0b74f437">llvm::PostRAMachineSinkingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40e93d6a1c6ab9b6b1b7ba3a391336cf">llvm::RemoveLoadsIntoFakeUsesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6bfbf70fac2ed039c8bd6b3b0d168117">llvm::ShrinkWrapID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a805432189f97152d1899d08945204faa">llvm::StackMapLivenessID</a>.</p>

</div>
</div>

### addPreEmitPass() {#ab4beb7113336e36d1a81ae2ca8ca6d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyPassConfig::addPreEmitPass ()</td>
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

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a665aaee703109520c639696e02283bb8">llvm::TargetPassConfig::addPreEmitPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf9103686d41f4a217562f0bf8eddd9f">llvm::createWebAssemblyCFGSort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8acc0cde2aca7b9cb00194eb3dc0434d">llvm::createWebAssemblyCFGStackify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70893708760a1240a62799b05f9c056e">llvm::createWebAssemblyDebugFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa818251d10a37ed7bf44d481a91e84d2">llvm::createWebAssemblyExplicitLocals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4082580a16cdd0171d1c17c3d03535f">llvm::createWebAssemblyFixIrreducibleControlFlow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b34b4bdfacbc367ce389cbd3fb22abf">llvm::createWebAssemblyLateEHPrepare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac426e330c55fa7ddb80983694dbf8d74">llvm::createWebAssemblyLowerBrUnless</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4fce2f188b884af3d5825755e000e4e">llvm::createWebAssemblyMCLowerPrePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a68b9826bc2af8da490dc149adea748b0">llvm::createWebAssemblyMemIntrinsicResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee08bf9374b83dcbcaa5ecbca0ab0e8b">llvm::createWebAssemblyNullifyDebugValueLists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8be5057891baee5adc419b8eb8f00761">llvm::createWebAssemblyOptimizeLiveIntervals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdda771c29c731ed97c8f8c9ca72afe5">llvm::createWebAssemblyPeephole</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd0fc1dbfadc0283e0538c9504d4c121">llvm::createWebAssemblyRegColoring</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fc3701c4bf3de3a7654a55456282f4f">llvm::createWebAssemblyRegNumbering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf7b86fff2d721a15fa770725b1aed20">llvm::createWebAssemblyRegStackify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53fb2b9c991b9bb819e83e832ab08fbc">llvm::createWebAssemblyReplacePhysRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84af93da81fd23e2eeaf8de29b04bb2399f">llvm::Wasm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp/#ac16f99939d8bae4daf4d01bda3e30382">WasmDisableExplicitLocals</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp/#af9ca35b245dba6c3ae892b4bb4d79ea4">WasmDisableFixIrreducibleControlFlowPass</a>.</p>

</div>
</div>

### addPreISel() {#a8f9c04ecca87ed6772df9d6bb27c836b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyPassConfig::addPreISel ()</td>
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


<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c4939ec0b463c69e5776eb3f336a964">llvm::TargetPassConfig::addPreISel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ddc2e50b58934940fdd548c9b8655">llvm::createWebAssemblyLowerRefTypesIntPtrConv</a>.</p>

</div>
</div>

### addRegAssignAndRewriteFast() {#a6c7db547424baa0e88ca233c404a6a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::addRegAssignAndRewriteFast ()</td>
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

<p>Add core register allocator passes which do the actual register assignment and rewriting.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any passes were added.</p></dd>
</dl>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

### addRegAssignAndRewriteOptimized() {#a04f0d553e3e7b77d295673ff1e44691b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::addRegAssignAndRewriteOptimized ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

### createTargetRegisterAllocator() {#a9eb82e354d23248e7a99cecc1fb98e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * WebAssemblyPassConfig::createTargetRegisterAllocator (bool Optimized)</td>
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


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

### getWebAssemblyTargetMachine() {#ab4d67bca5947563e8d8a263a99f4222d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyTargetMachine &amp; anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::getWebAssemblyTargetMachine ()</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#a9cdafbe47c009568275c8908a24275e3">addInstSelector</a> and <a href="#a92398eff530e8269aeaa926aa01b7fb5">addISelPrepare</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
