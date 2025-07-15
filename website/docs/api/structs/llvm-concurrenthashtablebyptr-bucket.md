---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/concurrenthashtablebyptr/bucket
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Bucket` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ConcurrentHashTableByPtr::Bucket { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">llvm/ADT/ConcurrentHashtable.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8107febc4faf098487d11c466678ab2">Bucket</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa615b1ffd20a1385b4fa159a306d2b5e">Size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b0b6cb8e9ed68ff3a3ab5e5ed90548">NumberOfEntries</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#a76ae32da073683b2d4d166533619df7b">HashesPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b75e8b63cf9b1849f0310f3d82acb28">Hashes</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#a6aad12071c0bf07633da45ddffaacdb8">DataPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49298c812045349a99ae5d9c1f66f887">Entries</a> = nullptr</td>
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


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Bucket() {#aa8107febc4faf098487d11c466678ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Bucket ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Entries {#a49298c812045349a99ae5d9c1f66f887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataPtr llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Entries = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a>.</p>

</div>
</div>

### Hashes {#a7b75e8b63cf9b1849f0310f3d82acb28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashesPtr llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Hashes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a>.</p>

</div>
</div>

### NumberOfEntries {#ab2b0b6cb8e9ed68ff3a3ab5e5ed90548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::NumberOfEntries = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#ac62bbcb37f3fbd47a66763f0125e9829">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::printStatistic</a> and <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a>.</p>

</div>
</div>

### Size {#aa615b1ffd20a1385b4fa159a306d2b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::Bucket::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#a05f04083a96d1718f46e8f875425e636">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#ac62bbcb37f3fbd47a66763f0125e9829">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::printStatistic</a> and <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#ade6907f5a5422e625635b35e22dfe10a">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::RehashBucket</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/concurrenthashtable-h">ConcurrentHashtable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
