---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-lowertypetests-cpp-/icallbranchfunnel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ICallBranchFunnel` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LowerTypeTests.cpp}::ICallBranchFunnel { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects&lt;BaseTy, TrailingTys&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See the file comment for details on the usage of the <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> type. <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabde8c221edd563338706bd7e75247d2">targets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f41609d4f06bc9b2ac027467a0dbb0">CI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a681b85ff61a1b164a453f3705d73b">UniqueId</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416d191841dab6432f4c9af8884b9f35">NTargets</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/icallbranchfunnel">ICallBranchFunnel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb948e4663bb2cccc693ebccc240113a">create</a> (BumpPtrAllocator &amp;Alloc, CallInst *CI, ArrayRef&lt; GlobalTypeMember * &gt; Targets, unsigned UniqueId)</td>
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


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### targets() {#aabde8c221edd563338706bd7e75247d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; GlobalTypeMember * &gt; anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::targets ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a> and <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#ab5f3828c41150c05c9b8142e98c35218">llvm::TrailingObjects&lt; ICallBranchFunnel, GlobalTypeMember * &gt;::getTrailingObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CI {#ac5f41609d4f06bc9b2ac027467a0dbb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst* anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::CI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>Referenced by <a href="#acb948e4663bb2cccc693ebccc240113a">create</a>.</p>

</div>
</div>

### UniqueId {#a28a681b85ff61a1b164a453f3705d73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::UniqueId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>Referenced by <a href="#acb948e4663bb2cccc693ebccc240113a">create</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NTargets {#a416d191841dab6432f4c9af8884b9f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::NTargets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#acb948e4663bb2cccc693ebccc240113a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICallBranchFunnel * anonymous{LowerTypeTests.cpp}::ICallBranchFunnel::create (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> * &gt; Targets, unsigned UniqueId)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="#ac5f41609d4f06bc9b2ac027467a0dbb0">CI</a>, <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#a5b733cf2a7d7206c2d2601cc5b024488">llvm::TrailingObjects&lt; ICallBranchFunnel, GlobalTypeMember * &gt;::totalSizeToAlloc</a> and <a href="#a28a681b85ff61a1b164a453f3705d73b">UniqueId</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
