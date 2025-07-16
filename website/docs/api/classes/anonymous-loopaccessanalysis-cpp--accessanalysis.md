---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AccessAnalysis` Class Reference

<p>Analyses memory accesses in a loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 1, bool &gt; <a href="#a0c684eecabc9183add9e1028170460ca">MemAccessInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read or write access location. <a href="#a0c684eecabc9183add9e1028170460ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a0c684eecabc9183add9e1028170460ca">MemAccessInfo</a>, 8 &gt; <a href="#a79a7da3e8eefd9f47c85b9d7cb066564">MemAccessInfoList</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="#a0c684eecabc9183add9e1028170460ca">MemAccessInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 1 &gt; &gt; <a href="#a3047ad965334acfab6ab47a104ab4fdd">PtrAccessMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d79938e1667fe7a4b2379ae49fc72ed">AccessAnalysis</a> (const Loop *TheLoop, AAResults *AA, const LoopInfo *LI, MemoryDepChecker::DepCandidates &amp;DA, PredicatedScalarEvolution &amp;PSE, SmallPtrSetImpl&lt; MDNode * &gt; &amp;LoopAliasScopes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc16f6d9880f38fe33aff8604b9309f1">addLoad</a> (const MemoryLocation &amp;Loc, Type *AccessTy, bool IsReadOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a load and whether it is only read from. <a href="#acc16f6d9880f38fe33aff8604b9309f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14cf09d76363d8ac97f0ae92969dae4">addStore</a> (const MemoryLocation &amp;Loc, Type *AccessTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a store. <a href="#ae14cf09d76363d8ac97f0ae92969dae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add290ed56a35aadf648ebccf66491f0f">createCheckForAccess</a> (RuntimePointerChecking &amp;RtCheck, MemAccessInfo Access, Type *AccessTy, const DenseMap&lt; Value *, const SCEV * &gt; &amp;Strides, DenseMap&lt; Value *, unsigned &gt; &amp;DepSetId, Loop *TheLoop, unsigned &amp;RunningDepId, unsigned ASId, bool ShouldCheckStride, bool Assume)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if we can emit a run-time no-alias check for <span class="doxyComputerOutput">Access</span>. <a href="#add290ed56a35aadf648ebccf66491f0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60735e0d022845d03d123916bb48e1e8">canCheckPtrAtRT</a> (RuntimePointerChecking &amp;RtCheck, ScalarEvolution *SE, Loop *TheLoop, const DenseMap&lt; Value *, const SCEV * &gt; &amp;Strides, Value *&amp;UncomputablePtr, bool ShouldCheckWrap=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether we can check the pointers at runtime for non-intersection. <a href="#a60735e0d022845d03d123916bb48e1e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eedd5084356d73040d85c4e1b2fcad2">buildDependenceSets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Goes over all memory accesses, checks whether a RT check is needed and builds sets of dependent accesses. <a href="#a8eedd5084356d73040d85c4e1b2fcad2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77116c2c948f7f69de875c120e505c59">isDependencyCheckNeeded</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initial processing of memory accesses determined that we need to perform dependency checking. <a href="#a77116c2c948f7f69de875c120e505c59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d62e07caf887e918be3dd7929db6ef">resetDepChecks</a> (MemoryDepChecker &amp;DepChecker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We decided that no dependence analysis would be used. Reset the state. <a href="#ad8d62e07caf887e918be3dd7929db6ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a79a7da3e8eefd9f47c85b9d7cb066564">MemAccessInfoList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a908a42280d530ccce4ab703173d9d836">getDependenciesToCheck</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8feeb29eb933c6fd5e39ae09b0a572">adjustLoc</a> (MemoryLocation Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adjust the <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> so that it represents accesses to this location across all iterations, rather than a single one. <a href="#a7d8feeb29eb933c6fd5e39ae09b0a572">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c238e3c71fc1d5a42d0b3816cc4c40f">adjustAliasScopeList</a> (MDNode *ScopeList) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop alias scopes that are only valid within a single loop iteration. <a href="#a2c238e3c71fc1d5a42d0b3816cc4c40f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec3be29e554fc2fec1f2dca9675d4e0">processMemAccesses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go over all memory access and check whether runtime pointer checks are needed and build sets of dependency check candidates. <a href="#a5ec3be29e554fc2fec1f2dca9675d4e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">PtrAccessMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f550c4ff7a98f132bf0f70fbf113848">Accesses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of all accesses. <a href="#a1f550c4ff7a98f132bf0f70fbf113848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57989b3bb569d1236bdb3c99e4d02993">TheLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop being checked. <a href="#a57989b3bb569d1236bdb3c99e4d02993">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a79a7da3e8eefd9f47c85b9d7cb066564">MemAccessInfoList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77222216a0734dcb4469b3be9819badc">CheckDeps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of accesses that need a further dependence check. <a href="#a77222216a0734dcb4469b3be9819badc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf67019d837be4975c2a7f1ff83c7fc0">ReadOnlyPtr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of pointers that are read only. <a href="#acf67019d837be4975c2a7f1ff83c7fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49df4df39b4e25657f96575f5c59a00c">BAA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Batched alias analysis results. <a href="#a49df4df39b4e25657f96575f5c59a00c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliassettracker">AliasSetTracker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f289ae9a4a874d3f3207a2838f9d9c9">AST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An alias set tracker to partition the access set by underlying object and. <a href="#a1f289ae9a4a874d3f3207a2838f9d9c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70fffc536770be1a7479be8cdb3cac05">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> of the loop being checked. <a href="#a70fffc536770be1a7479be8cdb3cac05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a4eb0c14b923c59b75a82bc41e03c2575">MemoryDepChecker::DepCandidates</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff8e0124059556125fb9f5e990a1932">DepCands</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets of potentially dependent accesses - members of one set share an underlying pointer. <a href="#a9ff8e0124059556125fb9f5e990a1932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475f0854510e3ff5d75bee0790263a83">IsRTCheckAnalysisNeeded</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initial processing of memory accesses determined that we may need to add memchecks. <a href="#a475f0854510e3ff5d75bee0790263a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d6436e7c9483271c162281cbb69883">PSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate containing all the SCEV-related assumptions. <a href="#a34d6436e7c9483271c162281cbb69883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83605b59d4c132a9a43bcbf43639ba14">UnderlyingObjects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e9f8dfcba69cf6b5b24d52cbbbce1d">LoopAliasScopes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Alias scopes that are declared inside the loop, and as such not valid across iterations. <a href="#a49e9f8dfcba69cf6b5b24d52cbbbce1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Analyses memory accesses in a loop.</p>


<p>Checks whether run time pointer checks are needed and builds sets for data dependence checking.</p>


<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MemAccessInfo {#a0c684eecabc9183add9e1028170460ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef PointerIntPair&lt;Value *, 1, bool&gt; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::MemAccessInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read or write access location.</p>

<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### MemAccessInfoList {#a79a7da3e8eefd9f47c85b9d7cb066564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;MemAccessInfo, 8&gt; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::MemAccessInfoList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### PtrAccessMap {#a3047ad965334acfab6ab47a104ab4fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef MapVector&lt;MemAccessInfo, SmallSetVector&lt;Type *, 1&gt; &gt; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::PtrAccessMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AccessAnalysis() {#a9d79938e1667fe7a4b2379ae49fc72ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::AccessAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a4eb0c14b923c59b75a82bc41e03c2575">MemoryDepChecker::DepCandidates</a> &amp; DA, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; LoopAliasScopes)</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLoad() {#acc16f6d9880f38fe33aff8604b9309f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::addLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, bool IsReadOnly)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a load and whether it is only read from.</p>

<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### addStore() {#ae14cf09d76363d8ac97f0ae92969dae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::addStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a store.</p>

<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### buildDependenceSets() {#a8eedd5084356d73040d85c4e1b2fcad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::buildDependenceSets ()</td>
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

<p>Goes over all memory accesses, checks whether a RT check is needed and builds sets of dependent accesses.</p>

<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### canCheckPtrAtRT() {#a60735e0d022845d03d123916bb48e1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AccessAnalysis::canCheckPtrAtRT (<a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> &amp; RtCheck, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Strides, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; UncomputablePtr, bool ShouldCheckWrap=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether we can check the pointers at runtime for non-intersection.</p>


<p>Returns true if we need no check or if we do and we can generate them (i.e. the pointers have computable bounds).</p>


<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#add290ed56a35aadf648ebccf66491f0f">createCheckForAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a799b2020cc896db04085849aed060f20">llvm::RuntimePointerChecking::generateChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a24e5c89884a8b7b92a1d27da4e94e230">llvm::RuntimePointerChecking::getNumberOfChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a77116c2c948f7f69de875c120e505c59">isDependencyCheckNeeded</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a177df4fcdf758fb57ca59102c15d30c3">llvm::RuntimePointerChecking::Need</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#aa6ad96a1c2591e0a61c92e0be5776978">llvm::RuntimePointerChecking::Pointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a1b570db2adb62a2c7ffca1869987682b">llvm::RuntimePointerChecking::reset</a>.</p>

</div>
</div>

### createCheckForAccess() {#add290ed56a35aadf648ebccf66491f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AccessAnalysis::createCheckForAccess (<a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> &amp; RtCheck, <a href="#a0c684eecabc9183add9e1028170460ca">MemAccessInfo</a> Access, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Strides, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt; &amp; DepSetId, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, unsigned &amp; RunningDepId, unsigned ASId, bool ShouldCheckStride, bool Assume)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if we can emit a run-time no-alias check for <span class="doxyComputerOutput">Access</span>.</p>


<p>Returns true if we can emit a run-time no alias check for <span class="doxyComputerOutput">Access</span>. If we can check this access, this also adds it to a dependence set and adds a run-time to check for it to <span class="doxyComputerOutput">RtCheck</span>. If <span class="doxyComputerOutput">Assume</span> is true, we will attempt to use additional run-time checks in order to get the bounds of the pointer.</p>


<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#afe024d2bcdcaa9644b7270f84edd74a5">findForkedPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a2d58e737d5b362a238d1b9cfbd961532">hasComputableBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#abe6c75313479a0d0d8dd63b870faeeac">llvm::RuntimePointerChecking::insert</a>, <a href="#a77116c2c948f7f69de875c120e505c59">isDependencyCheckNeeded</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a7f4bd2b45f0af65f9dd7ac1b949b528e">isNoWrap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a60735e0d022845d03d123916bb48e1e8">canCheckPtrAtRT</a>.</p>

</div>
</div>

### getDependenciesToCheck() {#a908a42280d530ccce4ab703173d9d836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemAccessInfoList &amp; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::getDependenciesToCheck ()</td>
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



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### isDependencyCheckNeeded() {#a77116c2c948f7f69de875c120e505c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::isDependencyCheckNeeded ()</td>
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

<p>Initial processing of memory accesses determined that we need to perform dependency checking.</p>


<p>Note that this can later be cleared if we retry memcheck analysis without dependency checking (i.e. FoundNonConstantDistanceDependence).</p>


<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a60735e0d022845d03d123916bb48e1e8">canCheckPtrAtRT</a> and <a href="#add290ed56a35aadf648ebccf66491f0f">createCheckForAccess</a>.</p>

</div>
</div>

### resetDepChecks() {#ad8d62e07caf887e918be3dd7929db6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::resetDepChecks (<a href="/web-llvm/docs/api/classes/llvm/memorydepchecker">MemoryDepChecker</a> &amp; DepChecker)</td>
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

<p>We decided that no dependence analysis would be used. Reset the state.</p>

<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#a67819b448429b42f3558c9b2e4ae4b45">llvm::MemoryDepChecker::clearDependences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### adjustAliasScopeList() {#a2c238e3c71fc1d5a42d0b3816cc4c40f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::adjustAliasScopeList (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * ScopeList)</td>
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

<p>Drop alias scopes that are only valid within a single loop iteration.</p>

<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### adjustLoc() {#a7d8feeb29eb933c6fd5e39ae09b0a572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::adjustLoc (<a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> Loc)</td>
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

<p>Adjust the <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> so that it represents accesses to this location across all iterations, rather than a single one.</p>

<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### processMemAccesses() {#a5ec3be29e554fc2fec1f2dca9675d4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AccessAnalysis::processMemAccesses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go over all memory access and check whether runtime pointer checks are needed and build sets of dependency check candidates.</p>

<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Accesses {#a1f550c4ff7a98f132bf0f70fbf113848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PtrAccessMap anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::Accesses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of all accesses.</p>


<p>Values are the types used to access memory pointed to by the pointer.</p>


<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### AST {#a1f289ae9a4a874d3f3207a2838f9d9c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasSetTracker anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::AST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An alias set tracker to partition the access set by underlying object and.</p>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### BAA {#a49df4df39b4e25657f96575f5c59a00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::BAA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Batched alias analysis results.</p>

<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### CheckDeps {#a77222216a0734dcb4469b3be9819badc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemAccessInfoList anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::CheckDeps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of accesses that need a further dependence check.</p>

<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### DepCands {#a9ff8e0124059556125fb9f5e990a1932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryDepChecker::DepCandidates&amp; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::DepCands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets of potentially dependent accesses - members of one set share an underlying pointer.</p>


<p>The set "CheckDeps" identfies which sets really need a dependence check.</p>


<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### IsRTCheckAnalysisNeeded {#a475f0854510e3ff5d75bee0790263a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::IsRTCheckAnalysisNeeded = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initial processing of memory accesses determined that we may need to add memchecks.</p>


<p>Perform the analysis to determine the necessary checks.</p>


<p>Note that, this is different from isDependencyCheckNeeded. When we retry memcheck analysis without dependency checking (i.e. FoundNonConstantDistanceDependence), isDependencyCheckNeeded is cleared while this remains set if we have potentially dependent accesses.</p>


<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### LI {#a70fffc536770be1a7479be8cdb3cac05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopInfo* anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> of the loop being checked.</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### LoopAliasScopes {#a49e9f8dfcba69cf6b5b24d52cbbbce1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSetImpl&lt;MDNode *&gt;&amp; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::LoopAliasScopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Alias scopes that are declared inside the loop, and as such not valid across iterations.</p>

<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### PSE {#a34d6436e7c9483271c162281cbb69883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate containing all the SCEV-related assumptions.</p>

<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### ReadOnlyPtr {#acf67019d837be4975c2a7f1ff83c7fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Value*, 16&gt; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::ReadOnlyPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of pointers that are read only.</p>

<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### TheLoop {#a57989b3bb569d1236bdb3c99e4d02993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop* anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop being checked.</p>

<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### UnderlyingObjects {#a83605b59d4c132a9a43bcbf43639ba14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, SmallVector&lt;const Value *, 16&gt; &gt; anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::UnderlyingObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
