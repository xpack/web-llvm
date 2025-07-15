---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machoyaml/fileheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FileHeader` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachOYAML::FileHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">llvm/ObjectYAML/MachOYAML.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0c9859e7f0f07adef63d315869c79d">magic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b441a6b84b5a5b0d03b3924cdb9abf4">cputype</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a630bbeba00ca46a7c5639c97bbb78b">cpusubtype</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e0cca5b417d9e9926713548b760ed8">filetype</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7902fefc22f88f420fb469c0b09f8a6c">ncmds</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b18ba2f7667e7a85a1bcf679c7aeed">sizeofcmds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6073cd2943b70d371493ba54d7f1409d">flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd320b92a0a66bfa0b32d0014df3e0c">reserved</a></td>
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


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### cpusubtype {#a5a630bbeba00ca46a7c5639c97bbb78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FileHeader::cpusubtype</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### cputype {#a5b441a6b84b5a5b0d03b3924cdb9abf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FileHeader::cputype</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### filetype {#a54e0cca5b417d9e9926713548b760ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FileHeader::filetype</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### flags {#a6073cd2943b70d371493ba54d7f1409d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FileHeader::flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### magic {#afd0c9859e7f0f07adef63d315869c79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FileHeader::magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### ncmds {#a7902fefc22f88f420fb469c0b09f8a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachOYAML::FileHeader::ncmds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### reserved {#acfd320b92a0a66bfa0b32d0014df3e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FileHeader::reserved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

### sizeofcmds {#ad7b18ba2f7667e7a85a1bcf679c7aeed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachOYAML::FileHeader::sizeofcmds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
