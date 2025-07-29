---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/utils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Utils` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::Utils { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">llvm/SandboxIR/Utils.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ed4ff75262c5c7bf6107a1cb09d583">getExpectedType</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the expected type of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a></span> V. <a href="#a94ed4ff75262c5c7bf6107a1cb09d583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ce107d4b6f96c84c7fe574a320993f">getExpectedValue</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the expected <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> for this instruction. <a href="#af0ce107d4b6f96c84c7fe574a320993f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LoadOrStoreT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0185a31c3cb2e873b3cf08093d18537">getMemInstructionBase</a> (const LoadOrStoreT *LSI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the base <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> for load or store instruction <span class="doxyComputerOutput">LSI</span>. <a href="#ab0185a31c3cb2e873b3cf08093d18537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880037a6ce1e268642581425f4f44c5f">getNumBits</a> (Type *Ty, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of bits of <span class="doxyComputerOutput">Ty</span>. <a href="#a880037a6ce1e268642581425f4f44c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd0aabe6c4d3a12394213ccf7d03560">getNumBits</a> (Value *V, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of bits required to represent the operands or return value of <span class="doxyComputerOutput">V</span> in <span class="doxyComputerOutput">DL</span>. <a href="#a0cd0aabe6c4d3a12394213ccf7d03560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a974ca47a829812a9cc9a2cad4f32dc73">getNumBits</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the number of bits required to represent the operands or return value of <span class="doxyComputerOutput">I</span>. <a href="#a974ca47a829812a9cc9a2cad4f32dc73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">llvm::MemoryLocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f715b1ea015a15c8efb07a459c0156f">memoryLocationGetOrNone</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalent to MemoryLocation::getOrNone(I). <a href="#a9f715b1ea015a15c8efb07a459c0156f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LoadOrStoreT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52c21a2bc9e5238472dabfd4183158e5">getPointerDiffInBytes</a> (LoadOrStoreT *I0, LoadOrStoreT *I1, ScalarEvolution &amp;SE) -&gt; std::optional&lt; int &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the gap between the memory locations accessed by <span class="doxyComputerOutput">I0</span> and <span class="doxyComputerOutput">I1</span> in bytes. <a href="#a52c21a2bc9e5238472dabfd4183158e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LoadOrStoreT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a283da28f49cf79afe0661c5b84db7910">atLowerAddress</a> (LoadOrStoreT *I0, LoadOrStoreT *I1, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if <span class="doxyComputerOutput">I0</span> accesses a memory location lower than <span class="doxyComputerOutput">I1</span>. <a href="#a283da28f49cf79afe0661c5b84db7910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0193fe229d9129ff3f641345ea0066">aliasAnalysisGetModRefInfo</a> (BatchAAResults &amp;BatchAA, const Instruction *I, const std::optional&lt; MemoryLocation &gt; &amp;OptLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalent to BatchAA::getModRefInfo(). <a href="#a5c0193fe229d9129ff3f641345ea0066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6765221be207c523a7b58baa17d8abe">verifyFunction</a> (const Function *F, raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalent to <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction()</a>. <a href="#ab6765221be207c523a7b58baa17d8abe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### aliasAnalysisGetModRefInfo() {#a5c0193fe229d9129ff3f641345ea0066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::sandboxir::Utils::aliasAnalysisGetModRefInfo (<a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BatchAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &gt; &amp; OptLoc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Equivalent to BatchAA::getModRefInfo().</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults/#adfa0be41805b25d9577d6f15d148a0d7">llvm::BatchAAResults::getModRefInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### atLowerAddress() {#a283da28f49cf79afe0661c5b84db7910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LoadOrStoreT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Utils::atLowerAddress (LoadOrStoreT * I0, LoadOrStoreT * I1, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns true if <span class="doxyComputerOutput">I0</span> accesses a memory location lower than <span class="doxyComputerOutput">I1</span>.</p>


<p>Returns false if the difference cannot be determined, if the memory locations are equal, or if I1 accesses a memory location greater than I0.</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>Reference <a href="#a52c21a2bc9e5238472dabfd4183158e5">getPointerDiffInBytes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#af9bf47b55127bc4dab70c2a450ee1a27">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memseedbundle/#a5d9eeeed10260d334e4fa005d77f6637">llvm::sandboxir::MemSeedBundle&lt; sandboxir::StoreInst &gt;::MemSeedBundle</a>.</p>

</div>
</div>

### getExpectedType() {#a94ed4ff75262c5c7bf6107a1cb09d583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::sandboxir::Utils::getExpectedType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the expected type of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a></span> V.</p>


<p>For most Values this is equivalent to getType, but for stores returns the stored type, rather than void, and for ReturnInsts returns the returned type.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#af0ce107d4b6f96c84c7fe574a320993f">getExpectedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a5f93ad2195368bba2202c3cc75e7cc1d">llvm::sandboxir::Value::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#a1d1c2bc5710b2b6ca489fed0de8f8c54">llvm::sandboxir::VecUtils::getCommonScalarType</a>, <a href="#a974ca47a829812a9cc9a2cad4f32dc73">getNumBits</a>, <a href="#a0cd0aabe6c4d3a12394213ccf7d03560">getNumBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#ac168de25fddd4444562e933d48ad0691">llvm::sandboxir::VecUtils::getNumLanes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a3019002eb2b04987eae4158ac938245e">llvm::sandboxir::isValidMemSeed</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/bottomupvec/#af99e15876a8fdb279707835eb24b037b">llvm::sandboxir::BottomUpVec::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#a033de8f81a298858c0219b067c983618">llvm::sandboxir::VecUtils::tryGetCommonScalarType</a>.</p>

</div>
</div>

### getExpectedValue() {#af0ce107d4b6f96c84c7fe574a320993f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::Utils::getExpectedValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the expected <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> for this instruction.</p>


<p>For most instructions, this is the instruction itself, but for stores returns the stored operand, and for ReturnInstructions returns the returned value.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a94ed4ff75262c5c7bf6107a1cb09d583">getExpectedType</a>.</p>

</div>
</div>

### getMemInstructionBase() {#ab0185a31c3cb2e873b3cf08093d18537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LoadOrStoreT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::Utils::getMemInstructionBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LoadOrStoreT * LSI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the base <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> for load or store instruction <span class="doxyComputerOutput">LSI</span>.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#acfec3e7998ff90624e6f88e517464dd2">llvm::sandboxir::Context::getOrCreateValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>.</p>

</div>
</div>

### getNumBits() {#a880037a6ce1e268642581425f4f44c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Utils::getNumBits (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the number of bits of <span class="doxyComputerOutput">Ty</span>.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#a81ce5874362fbe3b93b0c31ea8a7b8f4">llvm::sandboxir::VecUtils::areConsecutive</a>, <a href="#a0cd0aabe6c4d3a12394213ccf7d03560">getNumBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle/#a75a54304c99ee264027c946c229d2ab6">llvm::sandboxir::SeedBundle::getSlice</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle/#a7d63423056e426e6f51b8a866a4021fa">llvm::sandboxir::SeedBundle::insertAt</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/bottomupvec/#af99e15876a8fdb279707835eb24b037b">llvm::sandboxir::BottomUpVec::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle/#aaca41cf5428be5168a21ead42cccc6cc">llvm::sandboxir::SeedBundle::SeedBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle/#a6b326cc642a333805cfa5aa71497e0c9">llvm::sandboxir::SeedBundle::setUsed</a>.</p>

</div>
</div>

### getNumBits() {#a0cd0aabe6c4d3a12394213ccf7d03560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Utils::getNumBits (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the number of bits required to represent the operands or return value of <span class="doxyComputerOutput">V</span> in <span class="doxyComputerOutput">DL</span>.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a94ed4ff75262c5c7bf6107a1cb09d583">getExpectedType</a> and <a href="#a880037a6ce1e268642581425f4f44c5f">getNumBits</a>.</p>

</div>
</div>

### getNumBits() {#a974ca47a829812a9cc9a2cad4f32dc73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::Utils::getNumBits (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the number of bits required to represent the operands or return value of <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="#a94ed4ff75262c5c7bf6107a1cb09d583">getExpectedType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getPointerDiffInBytes() {#a52c21a2bc9e5238472dabfd4183158e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LoadOrStoreT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; llvm::sandboxir::Utils::getPointerDiffInBytes (LoadOrStoreT * I0, LoadOrStoreT * I1, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\Returns the gap between the memory locations accessed by <span class="doxyComputerOutput">I0</span> and <span class="doxyComputerOutput">I1</span> in bytes.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff9e533399d91febd63fa4bfe82a42a7">llvm::ScalarEvolution::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vecutils/#a81ce5874362fbe3b93b0c31ea8a7b8f4">llvm::sandboxir::VecUtils::areConsecutive</a> and <a href="#a283da28f49cf79afe0661c5b84db7910">atLowerAddress</a>.</p>

</div>
</div>

### memoryLocationGetOrNone() {#a9f715b1ea015a15c8efb07a459c0156f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; llvm::MemoryLocation &gt; llvm::sandboxir::Utils::memoryLocationGetOrNone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Equivalent to MemoryLocation::getOrNone(I).</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af61b31a99c1e58b1760492d2a7a1ba9c">llvm::MemoryLocation::getOrNone</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### verifyFunction() {#ab6765221be207c523a7b58baa17d8abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::Utils::verifyFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Equivalent to <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction()</a>.</p>


<p>\Returns true if the IR is broken.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/utils-h">Utils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
