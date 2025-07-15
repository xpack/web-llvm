---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-nvptxtargetmachine-cpp-/nvptxpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NVPTXPassConfig` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d75054c5690d0da7b1a78c567af1de">NVPTXPassConfig</a> (NVPTXTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine">NVPTXTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee7479abb2de25ebc1a1040af93bb8e1">getNVPTXTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579752615e6d1eb6de1d78a9c96f984e">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a579752615e6d1eb6de1d78a9c96f984e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617186c1e6c66d3b4c0a48e2556e8258">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a617186c1e6c66d3b4c0a48e2556e8258">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace69c6b28a567c328871972e705ba463">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#ace69c6b28a567c328871972e705ba463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad641a0ff7475cca256e481fc93c80ff2">addPostRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#ad641a0ff7475cca256e481fc93c80ff2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16bce7eed5d85bb0eb481754956b2d58">addMachineSSAOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form. <a href="#a16bce7eed5d85bb0eb481754956b2d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563131d2198d70f6410d25a3e67dda5f">createTargetRegisterAllocator</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level. <a href="#a563131d2198d70f6410d25a3e67dda5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcad7628fd41e4776ceea3f215ae07e">addFastRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation. <a href="#a9fcad7628fd41e4776ceea3f215ae07e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe63419e9074e68df213589ed9870742">addOptimizedRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addOptimizedRegAlloc - Add passes related to register allocation. <a href="#abe63419e9074e68df213589ed9870742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1a1113a686baa239548051a6647fa5">addRegAssignAndRewriteFast</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add core register allocator passes which do the actual register assignment and rewriting. <a href="#a6c1a1113a686baa239548051a6647fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb200e7a41751e7adf899ccfeb4556e">addRegAssignAndRewriteOptimized</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33acd24879703b251f45cdf7f0324ec">addEarlyCSEOrGVNPass</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ebdf4a52b59625f51a356139e29bf5">addAddressSpaceInferencePasses</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35997780674e381f3dd70a16ea67fe2d">addStraightLineScalarOptimizationPasses</a> ()</td>
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


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NVPTXPassConfig() {#a03d75054c5690d0da7b1a78c567af1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::NVPTXPassConfig (<a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine">NVPTXTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFastRegAlloc() {#a9fcad7628fd41e4776ceea3f215ae07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addFastRegAlloc ()</td>
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


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae50f7215c4832bcfb5ffb377f964e061">llvm::PHIEliminationID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adcdd39e0229ebb0b23f143d644d2d1f7">llvm::TwoAddressInstructionPassID</a>.</p>

</div>
</div>

### addInstSelector() {#a617186c1e6c66d3b4c0a48e2556e8258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXPassConfig::addInstSelector ()</td>
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

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a879c53d18034a667939cc5a8e2519eac">llvm::createAllocaHoisting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9cf53eee6fd909bcd611b68ed4da847a">llvm::createLowerAggrCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5398f77eb4b83f420c9f6faafa47983a">llvm::createNVPTXISelDag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a131aca3be29e66eacf25dd9a2a7baf91">llvm::createNVPTXReplaceImageHandlesPass</a>, <a href="#aee7479abb2de25ebc1a1040af93bb8e1">getNVPTXTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addIRPasses() {#a579752615e6d1eb6de1d78a9c96f984e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addIRPasses ()</td>
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

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae4fcea773b8fc3af6c3c579ebcc7c692">llvm::AAResults::addAAResult</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1895f13235512e51a7619de25cda6f4f">llvm::createExpandVariadicsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0000e11ad5a4d13f48c4498fbd9d18a">llvm::createExternalAAWrapperPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2437c2069622767cd806b96828ad2149">llvm::createGenericToNVVMLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17a97a755982d8fe4e03d09755f11af4">llvm::createLoadStoreVectorizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4c32b3fd4a883892e21a8a7d2622ef3">llvm::createNVPTXAAWrapperPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0bfe448556131e46d6b2e8aab586de9e">llvm::createNVPTXAssignValidGlobalNamesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aafb586a7c2ebc9a3f986906f1b479cc3">llvm::createNVPTXCtorDtorLoweringLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6fea52ac1a4fd9bd076eced7c7ca31cb">llvm::createNVPTXImageOptimizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66c992a3f0ee669428ba2d19c474c47b">llvm::createNVPTXLowerArgsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1447a0322c38b993d7c84570397a7b68">llvm::createNVPTXLowerUnreachablePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2846ea3beb3d5b3234de823a7765676d">llvm::createNVVMReflectPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7e42c560dd36ec85086cc1c43b61f56">llvm::createSROAPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp/#a384d0b5684175e21fc0c5c625f5998bb">DisableLoadStoreVectorizer</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85d339220c3769c26cc027fe4cc4dfee">llvm::FuncletLayoutID</a>, <a href="#aee7479abb2de25ebc1a1040af93bb8e1">getNVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a0fec1667ac50cd92d5de25da9c53f704">llvm::GCNTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a29d4416121b20dd5ccd9ffca40c05524">llvm::Lowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5dc78ed1fd5966782d85bf389333790">llvm::MachineCopyPropagationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d504656f6cc4feb09837a202a4bac92">llvm::MachineLateInstrsCleanupID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ddae16561e646c4cbadec7e4fb5308b">llvm::PatchableFunctionID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d5462b10402ee83291fda8b0b74f437">llvm::PostRAMachineSinkingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5fd09bcdb3ea958016747ab1e9f4f7">llvm::PostRASchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54f54c42fcbebfb3d7e6bc1b5807e47c">llvm::PrologEpilogCodeInserterID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40e93d6a1c6ab9b6b1b7ba3a391336cf">llvm::RemoveLoadsIntoFakeUsesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6bfbf70fac2ed039c8bd6b3b0d168117">llvm::ShrinkWrapID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a805432189f97152d1899d08945204faa">llvm::StackMapLivenessID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a35f37733d6182da960aeaa10f5df2e16">llvm::TailDuplicateLegacyID</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a16bce7eed5d85bb0eb481754956b2d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addMachineSSAOptimization ()</td>
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


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3c584af6befa438063622f975dc8386a">llvm::TargetPassConfig::addILPOpts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af84508d5d676c86da43af3573b6297ea">llvm::DeadMachineInstructionElimID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08efde8583f615980c38b4e29760fae8">llvm::EarlyMachineLICMID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab82e9cd8759ab1db940ed0389c68d920">llvm::EarlyTailDuplicateLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adfe6b8951666ab7bb35ee3ca5a078937">llvm::LocalStackSlotAllocationID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab243cd86bbcb539fad948485fad842fc">llvm::MachineCSELegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a307065c6152b458d2b8ceaea1823d7">llvm::MachineSinkingID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dd8f9c0f0e4e56dfa9c1038235e35eb">llvm::OptimizePHIsLegacyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5233e3ce01bdfffee235d5d772b014dd">llvm::PeepholeOptimizerLegacyID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a1f3df08c5aaa70199bcbe47963f77ac6">llvm::TargetPassConfig::printAndVerify</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac0e496ce1c3c373c5737a6d9d2c84237">llvm::StackColoringLegacyID</a>.</p>

</div>
</div>

### addOptimizedRegAlloc() {#abe63419e9074e68df213589ed9870742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addOptimizedRegAlloc ()</td>
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


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab80163ae002e9cec63a9e279d5b1c2d7">llvm::LiveVariablesID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60b90e9a630631cf67aaef4679ffbf62">llvm::MachineLoopInfoID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f3ce4ffd1eecf7a4fef2cce86560b1a">llvm::MachineSchedulerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae50f7215c4832bcfb5ffb377f964e061">llvm::PHIEliminationID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a1f3df08c5aaa70199bcbe47963f77ac6">llvm::TargetPassConfig::printAndVerify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa38acb33ffcc1e45797c032c78e27b4b">llvm::ProcessImplicitDefsID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a97dc750eaae6c6c05a7f2ab03cdffc">llvm::RegisterCoalescerID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947df27369e5b0e5d44b3109f1cc592d">llvm::StackSlotColoringID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adcdd39e0229ebb0b23f143d644d2d1f7">llvm::TwoAddressInstructionPassID</a>.</p>

</div>
</div>

### addPostRegAlloc() {#ad641a0ff7475cca256e481fc93c80ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addPostRegAlloc ()</td>
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

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a46266862acc8a036ab51fe2fb7fedc63">llvm::createNVPTXPeephole</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2dd51a8b32ff8a1aafcbd53d6f0292a6">llvm::createNVPTXPrologEpilogPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addPreRegAlloc() {#ace69c6b28a567c328871972e705ba463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addPreRegAlloc ()</td>
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

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a31bac69c7a1c780033e527d2b8c7df62">llvm::createNVPTXProxyRegErasurePass</a>.</p>

</div>
</div>

### addRegAssignAndRewriteFast() {#a6c1a1113a686baa239548051a6647fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::addRegAssignAndRewriteFast ()</td>
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


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### addRegAssignAndRewriteOptimized() {#acdb200e7a41751e7adf899ccfeb4556e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::addRegAssignAndRewriteOptimized ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### createTargetRegisterAllocator() {#a563131d2198d70f6410d25a3e67dda5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * NVPTXPassConfig::createTargetRegisterAllocator (bool Optimized)</td>
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


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>

</div>
</div>

### getNVPTXTargetMachine() {#aee7479abb2de25ebc1a1040af93bb8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NVPTXTargetMachine &amp; anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::getNVPTXTargetMachine ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#a617186c1e6c66d3b4c0a48e2556e8258">addInstSelector</a> and <a href="#a579752615e6d1eb6de1d78a9c96f984e">addIRPasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addAddressSpaceInferencePasses() {#a15ebdf4a52b59625f51a356139e29bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addAddressSpaceInferencePasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>

</div>
</div>

### addEarlyCSEOrGVNPass() {#ab33acd24879703b251f45cdf7f0324ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addEarlyCSEOrGVNPass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>

</div>
</div>

### addStraightLineScalarOptimizationPasses() {#a35997780674e381f3dd70a16ea67fe2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXPassConfig::addStraightLineScalarOptimizationPasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp">NVPTXTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
