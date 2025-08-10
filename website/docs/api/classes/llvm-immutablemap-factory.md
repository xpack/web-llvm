---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutablemap/factory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Factory` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ImmutableMap::Factory { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">llvm/ADT/ImmutableMap.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5dc805a5a5a12aadb981af671569e6">Factory</a> (bool canonicalize=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36cb223fcc9d348dfed2c84e9c1d401">Factory</a> (BumpPtrAllocator &amp;Alloc, bool canonicalize=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadcea4bd83d893bb00d8f939ad4c65e0">Factory</a> (const Factory &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemap/factory">Factory</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae150f9613d78da77b46246a87ca0ffab">operator=</a> (const Factory &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ffcd1d42b4fcf9ca72090bb9008c9b">getEmptyMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c6a5e25d93d30df1b02d5715042b36">add</a> (ImmutableMap Old, key_type_ref K, data_type_ref D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee499a52810d4c69d661f410501d037e">remove</a> (ImmutableMap Old, key_type_ref K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a744e5bd7d0965b1bb1cbc5daa85263d7">TreeTy::Factory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9738360dc9377296e852fe5f45f80b64">getTreeFactory</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a744e5bd7d0965b1bb1cbc5daa85263d7">TreeTy::Factory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97aab26509b5cdfc13bd6e584aa508b4">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b0fae2a1cc012cfeebcb5e04eeafd5d">Canonicalize</a></td>
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


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Factory() {#a8b5dc805a5a5a12aadb981af671569e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Factory (bool canonicalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Referenced by <a href="#aadcea4bd83d893bb00d8f939ad4c65e0">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Factory</a> and <a href="#ae150f9613d78da77b46246a87ca0ffab">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::operator=</a>.</p>

</div>
</div>

### Factory() {#ab36cb223fcc9d348dfed2c84e9c1d401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Factory (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, bool canonicalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>.</p>

</div>
</div>

### Factory() {#aadcea4bd83d893bb00d8f939ad4c65e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Factory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablemap/factory">Factory</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a8b5dc805a5a5a12aadb981af671569e6">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Factory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae150f9613d78da77b46246a87ca0ffab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Factory &amp; llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablemap/factory">Factory</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a8b5dc805a5a5a12aadb981af671569e6">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Factory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a30c6a5e25d93d30df1b02d5715042b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMap llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::add (<a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a> Old, <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a98a4f44b8b25e741934379d81e11a512">key_type_ref</a> K, <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#ab8fe9c07b69f7da7df498d0550d054d8">data_type_ref</a> D)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a3da5e071a65c311ca6e250265ff337bf">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::ImmutableMap</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a4897a76a245b7b17eb0be5476543bd9d">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Root</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getEmptyMap() {#a16ffcd1d42b4fcf9ca72090bb9008c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMap llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::getEmptyMap ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a3da5e071a65c311ca6e250265ff337bf">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::ImmutableMap</a>.</p>

</div>
</div>

### getTreeFactory() {#a9738360dc9377296e852fe5f45f80b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy::Factory * llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::getTreeFactory ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### remove() {#aee499a52810d4c69d661f410501d037e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMap llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::remove (<a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a> Old, <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a98a4f44b8b25e741934379d81e11a512">key_type_ref</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a3da5e071a65c311ca6e250265ff337bf">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::ImmutableMap</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablemap/#a4897a76a245b7b17eb0be5476543bd9d">llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Root</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Canonicalize {#a4b0fae2a1cc012cfeebcb5e04eeafd5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::Canonicalize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### F {#a97aab26509b5cdfc13bd6e584aa508b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy::Factory llvm::ImmutableMap&lt; KeyT, ValT, ValInfo &gt;::Factory::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
