---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/directxpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DirectXPassConfig` Class



## Declaration

<div class="doxyDeclaration">
class DirectXPassConfig { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52efc438d0e939dd577b301bd0444baf">DirectXPassConfig</a> (DirectXTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/directxtargetmachine">DirectXTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23830a043e833c85ef2afc8331541b2">getDirectXTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3849035a953e35bd74b4033033100f15">createTargetRegisterAllocator</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level. <a href="#a3849035a953e35bd74b4033033100f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49845b47cd7ea53506680a7419f38f16">addCodeGenPrepare</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add pass to prepare the LLVM IR for code generation. <a href="#a49845b47cd7ea53506680a7419f38f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DirectXPassConfig() {#a52efc438d0e939dd577b301bd0444baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirectXPassConfig::DirectXPassConfig (<a href="/web-llvm/docs/api/classes/llvm/directxtargetmachine">DirectXTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGenPrepare() {#a49845b47cd7ea53506680a7419f38f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DirectXPassConfig::addCodeGenPrepare ()</td>
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

<p>Add pass to prepare the LLVM IR for code generation.</p>


<p>This should be done before exception handling preparation passes.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ade4bf5cdbca633355d8e0d865198c">llvm::createDXILDataScalarizationLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83f366d2c594038b61ec46091096db2f">llvm::createDXILFinalizeLinkageLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56cb6a8b8936dc041c15268afc236c7d">llvm::createDXILFlattenArraysLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a91f2593de99e308ce0a1cf26de84ae00">llvm::createDXILIntrinsicExpansionLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3a81f0859384a79cabe441c42fcf1df">llvm::createDXILOpLoweringLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a416c08661498c5206470e3fab7059d4b">llvm::createDXILPrepareModulePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6eb20d12edfdaca2e6ef77fdc82620fe">llvm::createDXILResourceAccessLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3208f86bcb31cd461a2d9087f03cccc3">llvm::createDXILTranslateMetadataLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab89a78d687ee0188640f6034e17a4064">llvm::createScalarizerPass</a> and <a href="/web-llvm/docs/api/structs/llvm/scalarizerpassoptions/#a2c426bfd7bd7c6fd835516dc4b3d5616">llvm::ScalarizerPassOptions::ScalarizeLoadStore</a>.</p>

</div>
</div>

### createTargetRegisterAllocator() {#a3849035a953e35bd74b4033033100f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * DirectXPassConfig::createTargetRegisterAllocator (bool Optimized)</td>
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

<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level.</p>


<p>Instantiate the default register allocator pass for this target for either the optimized or unoptimized allocation path.</p>


<p>This will be added to the pass manager by addFastRegAlloc in the unoptimized case or addOptimizedRegAlloc in the optimized case.</p>


<p>A target that uses the standard regalloc pass order for fast or optimized allocation may still override this for per-target regalloc selection. But -regalloc=... always takes precedence.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>

</div>
</div>

### getDirectXTargetMachine() {#ac23830a043e833c85ef2afc8331541b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirectXTargetMachine &amp; DirectXPassConfig::getDirectXTargetMachine ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aca23623f476d3929484bdad4a5ce54d8">llvm::TargetPassConfig::getTM</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
