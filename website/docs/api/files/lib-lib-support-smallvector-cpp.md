---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/smallvector-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SmallVector.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memalloc-h">llvm/Support/MemAlloc.h</a>"
#include &lt;cstdint&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-smallvector-cpp-">anonymous{SmallVector.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-smallvector-cpp-/struct16b">Struct16B</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-smallvector-cpp-/struct32b">Struct32B</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16781b016f45fba1aa015dc59ba7e653">report_size_overflow</a> (size_t MinSize, size_t MaxSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report that MinSize doesn't fit into this vector's size type. <a href="#a16781b016f45fba1aa015dc59ba7e653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba83d1439bd004981452b39ad73c3c0">report_at_maximum_capacity</a> (size_t MaxSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report that this vector is already at maximum capacity. <a href="#aaba83d1439bd004981452b39ad73c3c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Size_T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaacda3d173fc2125198e9fc756841767">getNewCapacity</a> (size_t MinSize, size_t TSize, size_t OldCapacity)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af529edaff902b7a5f2370f71ed88db1e">replaceAllocation</a> (void *NewElts, size_t TSize, size_t NewCapacity, size_t VSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If vector was first created with capacity 0, getFirstEl() points to the memory right after, an area unallocated. <a href="#af529edaff902b7a5f2370f71ed88db1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getNewCapacity() {#aaacda3d173fc2125198e9fc756841767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Size_T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t getNewCapacity (size_t MinSize, size_t TSize, size_t OldCapacity)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/smallvector-cpp">SmallVector.cpp</a>.</p>


<p>References <a href="#aaba83d1439bd004981452b39ad73c3c0">report_at_maximum_capacity</a> and <a href="#a16781b016f45fba1aa015dc59ba7e653">report_size_overflow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a0fef5db8f0b473292cb9770075050da5">llvm::SmallVectorBase&lt; Size_T &gt;::grow_pod</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a2c068750374c249c3498144297eda93c">llvm::SmallVectorBase&lt; Size_T &gt;::mallocForGrow</a>.</p>

</div>
</div>

### replaceAllocation() {#af529edaff902b7a5f2370f71ed88db1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * replaceAllocation (void * NewElts, size_t TSize, size_t NewCapacity, size_t VSize=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If vector was first created with capacity 0, getFirstEl() points to the memory right after, an area unallocated.</p>


<p>If a subsequent allocation, that grows the vector, happens to return the same pointer as getFirstEl(), get a new allocation, otherwise isSmall() will falsely return that no allocation was done (true) and the memory will not be freed in the destructor. If a VSize is given (vector size), also copy that many elements to the new allocation - used if realloca fails to increase space, and happens to allocate precisely at BeginX. This is unlikely to be called often, but resolves a memory leak when the situation does occur.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/smallvector-cpp">SmallVector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8bb931812d78f470d4ca775ac8b88e61">llvm::safe_malloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a0fef5db8f0b473292cb9770075050da5">llvm::SmallVectorBase&lt; Size_T &gt;::grow_pod</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a2c068750374c249c3498144297eda93c">llvm::SmallVectorBase&lt; Size_T &gt;::mallocForGrow</a>.</p>

</div>
</div>

### report\_at\_maximum\_capacity() {#aaba83d1439bd004981452b39ad73c3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void report_at_maximum_capacity (size_t MaxSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report that this vector is already at maximum capacity.</p>


<p>Throws std::length_error or calls report_fatal_error.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/smallvector-cpp">SmallVector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#aaacda3d173fc2125198e9fc756841767">getNewCapacity</a>.</p>

</div>
</div>

### report\_size\_overflow() {#a16781b016f45fba1aa015dc59ba7e653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void report_size_overflow (size_t MinSize, size_t MaxSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report that MinSize doesn't fit into this vector's size type.</p>


<p>Throws std::length_error or calls report_fatal_error.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/smallvector-cpp">SmallVector.cpp</a>.</p>


<p>Referenced by <a href="#aaacda3d173fc2125198e9fc756841767">getNewCapacity</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
