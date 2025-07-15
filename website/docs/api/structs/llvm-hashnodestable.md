---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hashnodestable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `HashNodeStable` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/hashnodestable">HashNodeStable</a> is the serialized, stable, and compact representation of a <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::HashNodeStable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">llvm/CGData/OutlinedHashTreeRecord.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex64</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8ed2c92340bd47d8da01a8d483f5ae">Hash</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4768333b0fd61daef285d1104a911ec9">Terminals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9044678a73d0f8eb1869896267366952">SuccessorIds</a></td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/hashnodestable">HashNodeStable</a> is the serialized, stable, and compact representation of a <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a>.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Hash {#a1a8ed2c92340bd47d8da01a8d483f5ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex64 llvm::HashNodeStable::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a2c9fcdfa14dafa4bf635b6bdd88e0c77">llvm::OutlinedHashTreeRecord::deserialize</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24588379b8be1521d75b9125ce41c383/#a2590440f6997b9501f9816f8ef59d02e">llvm::yaml::MappingTraits&lt; HashNodeStable &gt;::mapping</a>.</p>

</div>
</div>

### SuccessorIds {#a9044678a73d0f8eb1869896267366952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::HashNodeStable::SuccessorIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a2c9fcdfa14dafa4bf635b6bdd88e0c77">llvm::OutlinedHashTreeRecord::deserialize</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24588379b8be1521d75b9125ce41c383/#a2590440f6997b9501f9816f8ef59d02e">llvm::yaml::MappingTraits&lt; HashNodeStable &gt;::mapping</a>.</p>

</div>
</div>

### Terminals {#a4768333b0fd61daef285d1104a911ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HashNodeStable::Terminals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a2c9fcdfa14dafa4bf635b6bdd88e0c77">llvm::OutlinedHashTreeRecord::deserialize</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24588379b8be1521d75b9125ce41c383/#a2590440f6997b9501f9816f8ef59d02e">llvm::yaml::MappingTraits&lt; HashNodeStable &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtreerecord-h">OutlinedHashTreeRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
