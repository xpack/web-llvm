---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/domconditioncache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DomConditionCache` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DomConditionCache { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">llvm/Analysis/DomConditionCache.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3532f1fed678b633aaa54f94bb6336">AffectedValuesMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *, 1 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map of values about which a branch might be providing information. <a href="#a5c3532f1fed678b633aaa54f94bb6336">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac105333da6ce958e6a88367557e798ae">registerBranch</a> (BranchInst *BI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a branch condition to the cache. <a href="#ac105333da6ce958e6a88367557e798ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484d8fd01b56b3d8b33201afca63e65a">removeValue</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a value from the cache, e.g. because it will be erased. <a href="#a484d8fd01b56b3d8b33201afca63e65a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d9b8fb2a8e5a95ae752bcc3c1d0f66">conditionsFor</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access the list of branches which affect this value. <a href="#a22d9b8fb2a8e5a95ae752bcc3c1d0f66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AffectedValuesMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5be940c67dd38ac4e7e76ce363d41b">AffectedValues</a></td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AffectedValuesMap {#a5c3532f1fed678b633aaa54f94bb6336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomConditionCache::AffectedValuesMap =  DenseMap&lt;Value *, SmallVector&lt;BranchInst *, 1&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map of values about which a branch might be providing information.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### conditionsFor() {#a22d9b8fb2a8e5a95ae752bcc3c1d0f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BranchInst * &gt; llvm::DomConditionCache::conditionsFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Access the list of branches which affect this value.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>.</p>

</div>
</div>

### registerBranch() {#ac105333da6ce958e6a88367557e798ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DomConditionCache::registerBranch (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * BI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a branch condition to the cache.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domconditioncache-cpp">DomConditionCache.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>.</p>

</div>
</div>

### removeValue() {#a484d8fd01b56b3d8b33201afca63e65a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomConditionCache::removeValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Remove a value from the cache, e.g. because it will be erased.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AffectedValues {#a9f5be940c67dd38ac4e7e76ce363d41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AffectedValuesMap llvm::DomConditionCache::AffectedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domconditioncache-h">DomConditionCache.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/domconditioncache-cpp">DomConditionCache.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
