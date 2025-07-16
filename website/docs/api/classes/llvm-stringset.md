---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stringset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StringSet` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a> - A wrapper for <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> that provides set-like functionality. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class AllocatorTy = MallocAllocator&gt;
class llvm::StringSet&lt;AllocatorTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">llvm/ADT/StringSet.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap&lt;ValueTy, AllocatorTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> - This is an unconventional map that is specialized for handling keys that are "strings", which are basically ranges of bytes. <a href="/web-llvm/docs/api/classes/llvm/stringmap/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AllocatorTy = MallocAllocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a961eab0f4487835f14fc5521a66715fe">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::nullopt_t, AllocatorTy &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AllocatorTy = MallocAllocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2125a51c45392c230eb011c436dbb214">StringSet</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AllocatorTy = MallocAllocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7f5441ef4f59d61cc78711c7a6d1e2ad">StringSet</a> (std::initializer_list&lt; StringRef &gt; initializer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Container&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4b4a9ff9f09487478efef25a3be1c55c">StringSet</a> (Container &amp;&amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AllocatorTy = MallocAllocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4536cd7fac442b9f4bf5d3c74f325ada">StringSet</a> (AllocatorTy a)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AllocatorTy = MallocAllocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add93efa62e06c599f1734f3b206232a0">insert</a> (StringRef key) -&gt; std::pair&lt; typename <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a84ddb88b13b4bc68478bed9ea1fcf20e">Base::iterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename InputIt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a60a47d0f2f3f1612f630d1c7cd8d2f1d">insert</a> (InputIt begin, InputIt end)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ca1272e3b56a501307fcd090709a358">insert</a> (const StringMapEntry&lt; ValueTy &gt; &amp;mapEntry) -&gt; std::pair&lt; typename <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a84ddb88b13b4bc68478bed9ea1fcf20e">Base::iterator</a>, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class AllocatorTy = MallocAllocator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3137f5ea0c0700166fbd5281d11396e">contains</a> (StringRef key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the set contains the given <span class="doxyComputerOutput">key</span>. <a href="#aa3137f5ea0c0700166fbd5281d11396e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a> - A wrapper for <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> that provides set-like functionality.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a961eab0f4487835f14fc5521a66715fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AllocatorTy = MallocAllocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StringSet&lt; AllocatorTy &gt;::Base =  StringMap&lt;std::nullopt_t, AllocatorTy&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StringSet() {#a2125a51c45392c230eb011c436dbb214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AllocatorTy = MallocAllocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSet&lt; AllocatorTy &gt;::StringSet ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>

</div>
</div>

### StringSet() {#a7f5441ef4f59d61cc78711c7a6d1e2ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AllocatorTy = MallocAllocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSet&lt; AllocatorTy &gt;::StringSet (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; initializer)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<p>Reference <a href="#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>.</p>

</div>
</div>

### StringSet() {#a4b4a9ff9f09487478efef25a3be1c55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Container&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSet&lt; AllocatorTy &gt;::StringSet (Container &amp;&amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>.</p>

</div>
</div>

### StringSet() {#a4536cd7fac442b9f4bf5d3c74f325ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AllocatorTy = MallocAllocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSet&lt; AllocatorTy &gt;::StringSet (AllocatorTy a)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#aa3137f5ea0c0700166fbd5281d11396e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AllocatorTy = MallocAllocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringSet&lt; AllocatorTy &gt;::contains (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> key)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the set contains the given <span class="doxyComputerOutput">key</span>.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#ae2360079f1c7c77f7295ce2f296bd7c9">llvm::StringMapImpl::FindKey</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-dxilprepare-cpp-/#a75bc124efcc80e995bd054f75dc5452a">anonymous{DXILPrepare.cpp}::collectDeadStringAttrs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>.</p>

</div>
</div>

### insert() {#add93efa62e06c599f1734f3b206232a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class AllocatorTy = MallocAllocator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; typename Base::iterator, bool &gt; llvm::StringSet&lt; AllocatorTy &gt;::insert (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> key)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringmap/#acef94957604524790af3fbcb3cebc050">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::try_emplace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a033ed3ccb4d48ca276a60b87127b344d">llvm::AArch64Subtarget::AArch64Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragefilenamessectionwriter/#ad9bbe1edc123c9f45a4ab86c193ecfe1">llvm::coverage::CoverageFilenamesSectionWriter::CoverageFilenamesSectionWriter</a>, <a href="#a5ca1272e3b56a501307fcd090709a358">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>, <a href="#a60a47d0f2f3f1612f630d1c7cd8d2f1d">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#adcd261211472362965c5b1bc5a3efebe">populateDependencyMatrix</a>, <a href="#a4b4a9ff9f09487478efef25a3be1c55c">llvm::StringSet&lt; AllocatorTy &gt;::StringSet</a>, <a href="#a7f5441ef4f59d61cc78711c7a6d1e2ad">llvm::StringSet&lt; AllocatorTy &gt;::StringSet</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheck/#adf5e24a0f2fd2cbea147c73975624359">llvm::FileCheck::ValidateCheckPrefixes</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ae1863db0091c416836ecbf151ea73c90">ValidatePrefixes</a>.</p>

</div>
</div>

### insert() {#a60a47d0f2f3f1612f630d1c7cd8d2f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename InputIt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StringSet&lt; AllocatorTy &gt;::insert (InputIt begin, InputIt end)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a2d71dc9a645a91493dd60a723be28720">llvm::StringMap&lt; std::nullopt_t, MallocAllocator &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; std::nullopt_t, MallocAllocator &gt;::end</a> and <a href="#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>.</p>

</div>
</div>

### insert() {#a5ca1272e3b56a501307fcd090709a358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; typename Base::iterator, bool &gt; llvm::StringSet&lt; AllocatorTy &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; ValueTy &gt; &amp; mapEntry)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a6201b76e51e8eecfbb57c77fba8367b8">llvm::StringMapEntry&lt; ValueTy &gt;::getKey</a> and <a href="#add93efa62e06c599f1734f3b206232a0">llvm::StringSet&lt; AllocatorTy &gt;::insert</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringset-h">StringSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
