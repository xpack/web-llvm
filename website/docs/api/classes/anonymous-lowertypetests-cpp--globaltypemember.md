---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lowertypetests-cpp-/globaltypemember
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalTypeMember` Class Reference

<p>A POD-like structure that we use to store a global reference together with its metadata types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LowerTypeTests.cpp}::GlobalTypeMember { ... }
</div>

## Base class

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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8fe5e3abecbabb3a7e1f5e1393630d">getGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341c182db9a71595e858ecb35c228896">isJumpTableCanonical</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a312caf4455aed24c06dbe5944089feb6">isExported</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc75bd9511e5001780af7e021a8936e0">types</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2114e4caf24de486adecfca44e896249">numTrailingObjects</a> (OverloadToken&lt; MDNode * &gt;) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83394caaa5147de75de07742b763dbda">TrailingObjects</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3569681ea17bdf844f697a099cec145">GO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9c0d4f16561ed22d6302e239f690cd">NTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6fee402a7f942fb69d38ec98279021">IsJumpTableCanonical</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9920cc0545c4184af26acb4e331d267">IsExported</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/globaltypemember">GlobalTypeMember</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d998bbf42b3e7b41db5f23ca7b37ba2">create</a> (BumpPtrAllocator &amp;Alloc, GlobalObject *GO, bool IsJumpTableCanonical, bool IsExported, ArrayRef&lt; MDNode * &gt; Types)</td>
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

<p>A POD-like structure that we use to store a global reference together with its metadata types.</p>


<p>In this pass we frequently need to query the set of metadata types referenced by a global, which at the IR level is an expensive operation involving a map lookup; this data structure helps to reduce the number of times we need to do this lookup.</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getGlobal() {#afd8fe5e3abecbabb3a7e1f5e1393630d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalObject * anonymous{LowerTypeTests.cpp}::GlobalTypeMember::getGlobal ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### isExported() {#a312caf4455aed24c06dbe5944089feb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::GlobalTypeMember::isExported ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### isJumpTableCanonical() {#a341c182db9a71595e858ecb35c228896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::GlobalTypeMember::isJumpTableCanonical ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### types() {#acc75bd9511e5001780af7e021a8936e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MDNode * &gt; anonymous{LowerTypeTests.cpp}::GlobalTypeMember::types ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a> and <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#ab5f3828c41150c05c9b8142e98c35218">llvm::TrailingObjects&lt; GlobalTypeMember, MDNode * &gt;::getTrailingObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### numTrailingObjects() {#a2114e4caf24de486adecfca44e896249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{LowerTypeTests.cpp}::GlobalTypeMember::numTrailingObjects (OverloadToken&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GO {#af3569681ea17bdf844f697a099cec145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalObject* anonymous{LowerTypeTests.cpp}::GlobalTypeMember::GO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### IsExported {#ae9920cc0545c4184af26acb4e331d267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::GlobalTypeMember::IsExported</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### IsJumpTableCanonical {#a8a6fee402a7f942fb69d38ec98279021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LowerTypeTests.cpp}::GlobalTypeMember::IsJumpTableCanonical</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### NTypes {#a1c9c0d4f16561ed22d6302e239f690cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{LowerTypeTests.cpp}::GlobalTypeMember::NTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

### TrailingObjects {#a83394caaa5147de75de07742b763dbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend anonymous{LowerTypeTests.cpp}::GlobalTypeMember::TrailingObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a7d998bbf42b3e7b41db5f23ca7b37ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalTypeMember * anonymous{LowerTypeTests.cpp}::GlobalTypeMember::create (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, bool IsJumpTableCanonical, bool IsExported, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; Types)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#a5b733cf2a7d7206c2d2601cc5b024488">llvm::TrailingObjects&lt; GlobalTypeMember, MDNode * &gt;::totalSizeToAlloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
