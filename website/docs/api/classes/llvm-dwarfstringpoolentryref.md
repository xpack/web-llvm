---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfstringpoolentryref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfStringPoolEntryRef` Class

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a>: Dwarf string pool entry reference. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DwarfStringPoolEntryRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">llvm/CodeGen/DwarfStringPoolEntry.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a7b4f7aa69407049141bb91ed299a9">ByValStringEntryPtr</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer type for "By value" string entry. <a href="#a97a7b4f7aa69407049141bb91ed299a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711f027e6410991c771ad61e420ec220">ExtStringEntryPtr</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a> *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer type for external string entry. <a href="#a711f027e6410991c771ad61e420ec220">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747c3f0eda29a4b8cea30091c7e975cd">DwarfStringPoolEntryRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">ByValStringEntryPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">ExtStringEntryPtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe6c7bf1a876d28273f16121fc8fc56">MapEntry</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the dwarf string pool Entry. <a href="#abfe6c7bf1a876d28273f16121fc8fc56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a>: Dwarf string pool entry reference.</p>


<p>Dwarf string pool entry keeps string value and its data. There are two variants how data are represented:</p>


<ol class="doxyList" type="1">
<li>String data in pool - <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry&lt;DwarfStringPoolEntry&gt;</a>.</li>
<li>External string data - <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a>.</li>
</ol>

<p>The external data variant allows reducing memory usage for the case when string pool entry does not have data: string entry does not keep any data and so no need to waste space for the full <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a>. It is recommended to use external variant if not all entries of dwarf string pool have corresponding <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a>.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ByValStringEntryPtr {#a97a7b4f7aa69407049141bb91ed299a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfStringPoolEntryRef::ByValStringEntryPtr =  const StringMapEntry&lt;DwarfStringPoolEntry&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer type for "By value" string entry.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

### ExtStringEntryPtr {#a711f027e6410991c771ad61e420ec220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfStringPoolEntryRef::ExtStringEntryPtr =  const DwarfStringPoolEntryWithExtString *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer type for external string entry.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfStringPoolEntryRef() {#a747c3f0eda29a4b8cea30091c7e975cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfStringPoolEntryRef::DwarfStringPoolEntryRef ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MapEntry {#abfe6c7bf1a876d28273f16121fc8fc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerUnion&lt;ByValStringEntryPtr, ExtStringEntryPtr&gt; llvm::DwarfStringPoolEntryRef::MapEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the dwarf string pool Entry.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
