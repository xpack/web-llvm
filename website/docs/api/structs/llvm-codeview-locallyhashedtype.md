---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeview/locallyhashedtype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LocallyHashedType` Struct Reference

<p>A locally hashed type represents a straightforward hash code of a serialized record. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::codeview::LocallyHashedType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">llvm/DebugInfo/CodeView/TypeHashing.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85cd82d5bbaa083c57837d4c8b3f8578">Hash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b806a28c3c7d7ea24c0d3c0d265949">RecordData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/codeview/locallyhashedtype">LocallyHashedType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b9c5b9df74bf984d5d5ad171f7c7fc">hashType</a> (ArrayRef&lt; uint8_t &gt; RecordData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a type, compute its local hash. <a href="#a95b9c5b9df74bf984d5d5ad171f7c7fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Range&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb25ac1007b36d17e21eae83b855f01f">hashTypes</a> (Range &amp;&amp;Records) -&gt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/locallyhashedtype">LocallyHashedType</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a sequence of types, compute all of the local hashes. <a href="#aeb25ac1007b36d17e21eae83b855f01f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/locallyhashedtype">LocallyHashedType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9d240204f798f816a5c00574041a86">hashTypeCollection</a> (TypeCollection &amp;Types)</td>
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

<p>A locally hashed type represents a straightforward hash code of a serialized record.</p>


<p>The record is simply serialized, and then the bytes are hashed by a standard algorithm. This is sufficient for the case of de-duplicating records within a single sequence of types, because if two records both have a back-reference to the same type in the same stream, they will both have the same numeric value for the <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> of the back reference.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Hash {#a85cd82d5bbaa083c57837d4c8b3f8578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::codeview::LocallyHashedType::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d4c6dcfa77293e610b110598fc7b9f83/#ab3e42a7f27620f45b59e80024c56ed93">llvm::DenseMapInfo&lt; codeview::LocallyHashedType &gt;::getHashValue</a>.</p>

</div>
</div>

### RecordData {#aa9b806a28c3c7d7ea24c0d3c0d265949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::codeview::LocallyHashedType::RecordData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Referenced by <a href="#a95b9c5b9df74bf984d5d5ad171f7c7fc">hashType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hashType() {#a95b9c5b9df74bf984d5d5ad171f7c7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocallyHashedType LocallyHashedType::hashType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; RecordData)</td>
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

<p>Given a type, compute its local hash.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a> and <a href="#aa9b806a28c3c7d7ea24c0d3c0d265949">RecordData</a>.</p>


<p>Referenced by <a href="#a4d9d240204f798f816a5c00574041a86">hashTypeCollection</a> and <a href="#aeb25ac1007b36d17e21eae83b855f01f">hashTypes</a>.</p>

</div>
</div>

### hashTypeCollection() {#a4d9d240204f798f816a5c00574041a86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; LocallyHashedType &gt; llvm::codeview::LocallyHashedType::hashTypeCollection (<a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection">TypeCollection</a> &amp; Types)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>Reference <a href="#a95b9c5b9df74bf984d5d5ad171f7c7fc">hashType</a>.</p>

</div>
</div>

### hashTypes() {#aeb25ac1007b36d17e21eae83b855f01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Range&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; LocallyHashedType &gt; llvm::codeview::LocallyHashedType::hashTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> &amp;&amp; Records)</td>
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

<p>Given a sequence of types, compute all of the local hashes.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a>.</p>


<p>References <a href="#a95b9c5b9df74bf984d5d5ad171f7c7fc">hashType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typehashing-h">TypeHashing.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp">TypeHashing.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
