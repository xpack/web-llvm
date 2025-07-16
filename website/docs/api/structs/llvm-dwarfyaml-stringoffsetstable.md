---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfyaml/stringoffsetstable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StringOffsetsTable` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFYAML::StringOffsetsTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">llvm/ObjectYAML/DWARFYAML.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b1012d9fe8944be2b7c6a5b7ef1a5a">Format</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35172720f26435d0b858112ea936d33a">Length</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">yaml::Hex16</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2cdb00e608fb987de1902a685f34dea">Version</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">yaml::Hex16</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1326215bb95a82375854039df4027cc0">Padding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2027cdc84e16d045288ba55b37361b">Offsets</a></td>
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


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Format {#ab4b1012d9fe8944be2b7c6a5b7ef1a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFYAML::StringOffsetsTable::Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>.</p>

</div>
</div>

### Length {#a35172720f26435d0b858112ea936d33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;yaml::Hex64&gt; llvm::DWARFYAML::StringOffsetsTable::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>.</p>

</div>
</div>

### Offsets {#a8f2027cdc84e16d045288ba55b37361b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;yaml::Hex64&gt; llvm::DWARFYAML::StringOffsetsTable::Offsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>.</p>

</div>
</div>

### Padding {#a1326215bb95a82375854039df4027cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::Hex16 llvm::DWARFYAML::StringOffsetsTable::Padding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>.</p>

</div>
</div>

### Version {#ad2cdb00e608fb987de1902a685f34dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::Hex16 llvm::DWARFYAML::StringOffsetsTable::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
