---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/leafrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LeafRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::CodeViewYAML::LeafRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypes-h">llvm/ObjectYAML/CodeViewYAMLTypes.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">codeview::CVType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab84ebd8bdf9c439e34ae3de04a85155">toCodeViewRecord</a> (codeview::AppendingTypeTableBuilder &amp;Serializer) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordbase">detail::LeafRecordBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4baa8b40ad6e666aacb2e246bf16e8f1">Leaf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/leafrecord">LeafRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5a716dec96f4ddc8639d374c7104e3">fromCodeViewRecord</a> (codeview::CVType Type)</td>
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


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypes-h">CodeViewYAMLTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### toCodeViewRecord() {#aab84ebd8bdf9c439e34ae3de04a85155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVType LeafRecord::toCodeViewRecord (<a href="/web-llvm/docs/api/classes/llvm/codeview/appendingtypetablebuilder">codeview::AppendingTypeTableBuilder</a> &amp; Serializer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypes-h">CodeViewYAMLTypes.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>


<p>Reference <a href="#a4baa8b40ad6e666aacb2e246bf16e8f1">Leaf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Leaf {#a4baa8b40ad6e666aacb2e246bf16e8f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;detail::LeafRecordBase&gt; llvm::CodeViewYAML::LeafRecord::Leaf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypes-h">CodeViewYAMLTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp/#a02f0c453e9a72b7bb391a936c4eba8a8">mapLeafRecordImpl</a> and <a href="#aab84ebd8bdf9c439e34ae3de04a85155">toCodeViewRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromCodeViewRecord() {#a7a5a716dec96f4ddc8639d374c7104e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; LeafRecord &gt; LeafRecord::fromCodeViewRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">codeview::CVType</a> Type)</td>
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



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypes-h">CodeViewYAMLTypes.h</a>, definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0e494c491fad71e29cc10efce7c59f6ca7e4105e7f11aef8db54945155c4b3907">llvm::codeview::corrupt_record</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#abeca1104e840a7079510842fcb583505">llvm::CodeViewYAML::fromDebugT</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamltypes-h">CodeViewYAMLTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp">CodeViewYAMLTypes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
