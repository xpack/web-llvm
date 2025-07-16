---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machoyaml/nlistentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NListEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachOYAML::NListEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">llvm/ObjectYAML/MachOYAML.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0985b9595f4899c5418ae84f174f033">n_strx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex8</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f85d549dd3a2e87eff124ab0dcd56a">n_type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e1d729a84d763f2c2cd71eaaf19b68a">n_sect</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909ca1f39d2b2087fcc28b6e663dd2c5">n_desc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc132fc7befac1cedb1d35345ff68e7">n_value</a></td>
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


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### n\_desc {#a909ca1f39d2b2087fcc28b6e663dd2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachOYAML::NListEntry::n_desc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0cbfe390439d3481c2aa8e64afdf2a46/#a8840ffc784b5ce7dfc7d8080d74c59a5">llvm::yaml::MappingTraits&lt; MachOYAML::NListEntry &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a46fc3f6bb1d9703770ef88e4b3d5d90b">anonymous{MachOEmitter.cpp}::writeNListEntry</a>.</p>

</div>
</div>

### n\_sect {#a0e1d729a84d763f2c2cd71eaaf19b68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachOYAML::NListEntry::n_sect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0cbfe390439d3481c2aa8e64afdf2a46/#a8840ffc784b5ce7dfc7d8080d74c59a5">llvm::yaml::MappingTraits&lt; MachOYAML::NListEntry &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a46fc3f6bb1d9703770ef88e4b3d5d90b">anonymous{MachOEmitter.cpp}::writeNListEntry</a>.</p>

</div>
</div>

### n\_strx {#ac0985b9595f4899c5418ae84f174f033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachOYAML::NListEntry::n_strx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0cbfe390439d3481c2aa8e64afdf2a46/#a8840ffc784b5ce7dfc7d8080d74c59a5">llvm::yaml::MappingTraits&lt; MachOYAML::NListEntry &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a46fc3f6bb1d9703770ef88e4b3d5d90b">anonymous{MachOEmitter.cpp}::writeNListEntry</a>.</p>

</div>
</div>

### n\_type {#a77f85d549dd3a2e87eff124ab0dcd56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex8 llvm::MachOYAML::NListEntry::n_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0cbfe390439d3481c2aa8e64afdf2a46/#a8840ffc784b5ce7dfc7d8080d74c59a5">llvm::yaml::MappingTraits&lt; MachOYAML::NListEntry &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a46fc3f6bb1d9703770ef88e4b3d5d90b">anonymous{MachOEmitter.cpp}::writeNListEntry</a>.</p>

</div>
</div>

### n\_value {#a7fc132fc7befac1cedb1d35345ff68e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachOYAML::NListEntry::n_value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0cbfe390439d3481c2aa8e64afdf2a46/#a8840ffc784b5ce7dfc7d8080d74c59a5">llvm::yaml::MappingTraits&lt; MachOYAML::NListEntry &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a46fc3f6bb1d9703770ef88e4b3d5d90b">anonymous{MachOEmitter.cpp}::writeNListEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
