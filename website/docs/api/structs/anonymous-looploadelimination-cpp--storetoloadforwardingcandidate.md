---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StoreToLoadForwardingCandidate` Struct Reference

<p>Represent a store-to-forwarding candidate. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f11ba76fd5bf10519e057da7c9a84b2">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d74f296d05ed42f72ab4205687c9b7">StoreToLoadForwardingCandidate</a> (LoadInst *Load, StoreInst *Store)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b88a2a7449e4edc75721e2ab686d9e">isDependenceDistanceOfOne</a> (PredicatedScalarEvolution &amp;PSE, Loop *L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the dependence from the store to the load has an absolute distance of one. <a href="#af7b88a2a7449e4edc75721e2ab686d9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1168d3b782579c020df450f3aba5af9">getLoadPtr</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2caa7a270983aba3db7f156957c6adc">Load</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54830aebaed98b40bb2157388e08e36">Store</a></td>
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

<p>Represent a store-to-forwarding candidate.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a5f11ba76fd5bf10519e057da7c9a84b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate">StoreToLoadForwardingCandidate</a> &amp; Cand</td>
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


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#ac2caa7a270983aba3db7f156957c6adc">Load</a>, <a href="#af54830aebaed98b40bb2157388e08e36">Store</a> and <a href="#ab6d74f296d05ed42f72ab4205687c9b7">StoreToLoadForwardingCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StoreToLoadForwardingCandidate() {#ab6d74f296d05ed42f72ab4205687c9b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::StoreToLoadForwardingCandidate (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * Store)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="#ac2caa7a270983aba3db7f156957c6adc">Load</a> and <a href="#af54830aebaed98b40bb2157388e08e36">Store</a>.</p>


<p>Referenced by <a href="#a5f11ba76fd5bf10519e057da7c9a84b2">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getLoadPtr() {#af1168d3b782579c020df450f3aba5af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::getLoadPtr ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>Reference <a href="#ac2caa7a270983aba3db7f156957c6adc">Load</a>.</p>

</div>
</div>

### isDependenceDistanceOfOne() {#af7b88a2a7449e4edc75721e2ab686d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne (<a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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

<p>Return true if the dependence from the store to the load has an absolute distance of one.</p>


<p>E.g. A[i+1] = A[i] (or A[i-1] = A[i] for descending loop)</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8bcb86d8d126d95b0dc05f09e8f3df96">llvm::ScalarEvolution::getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#ae0994d8207b94ad22ecebc1a6bc580f1">llvm::PredicatedScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a10ca5eacc61b5669880de2f8b0cff33c">llvm::PredicatedScalarEvolution::getSE</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#ac2caa7a270983aba3db7f156957c6adc">Load</a> and <a href="#af54830aebaed98b40bb2157388e08e36">Store</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a0600a51b42956b4e041baa101a3c047a">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::removeDependencesFromMultipleStores</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Load {#ac2caa7a270983aba3db7f156957c6adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst* anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::Load</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>Referenced by <a href="#af1168d3b782579c020df450f3aba5af9">getLoadPtr</a>, <a href="#af7b88a2a7449e4edc75721e2ab686d9e">isDependenceDistanceOfOne</a>, <a href="#a5f11ba76fd5bf10519e057da7c9a84b2">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a0600a51b42956b4e041baa101a3c047a">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::removeDependencesFromMultipleStores</a> and <a href="#ab6d74f296d05ed42f72ab4205687c9b7">StoreToLoadForwardingCandidate</a>.</p>

</div>
</div>

### Store {#af54830aebaed98b40bb2157388e08e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StoreInst* anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::Store</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a>.</p>


<p>Referenced by <a href="#af7b88a2a7449e4edc75721e2ab686d9e">isDependenceDistanceOfOne</a>, <a href="#a5f11ba76fd5bf10519e057da7c9a84b2">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a0600a51b42956b4e041baa101a3c047a">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::removeDependencesFromMultipleStores</a> and <a href="#ab6d74f296d05ed42f72ab4205687c9b7">StoreToLoadForwardingCandidate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp">LoopLoadElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
