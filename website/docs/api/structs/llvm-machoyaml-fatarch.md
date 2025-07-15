---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/machoyaml/fatarch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FatArch` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachOYAML::FatArch { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">llvm/ObjectYAML/MachOYAML.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex32</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd47e94d530e3e98d4ea694b2b1760e">cputype</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababfbb5092ec6615e8670ad32eea8fb7">cpusubtype</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex64</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c19c878c03ae8f131c81ea4df8958f6">offset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d8430cd21c1d9eede148721d0d3a404">size</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af3d107e8c53996156ea3b8bc9390b7">align</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8597b1f87407c555bad3655b0f46bf9">reserved</a></td>
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


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### align {#a6af3d107e8c53996156ea3b8bc9390b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachOYAML::FatArch::align</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aa33d56236bd375c3b794773f4a9bb2f1">anonymous{MachOEmitter.cpp}::constructFatArch</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>.</p>

</div>
</div>

### cpusubtype {#ababfbb5092ec6615e8670ad32eea8fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FatArch::cpusubtype</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aa33d56236bd375c3b794773f4a9bb2f1">anonymous{MachOEmitter.cpp}::constructFatArch</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>.</p>

</div>
</div>

### cputype {#a1bd47e94d530e3e98d4ea694b2b1760e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FatArch::cputype</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aa33d56236bd375c3b794773f4a9bb2f1">anonymous{MachOEmitter.cpp}::constructFatArch</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>.</p>

</div>
</div>

### offset {#a0c19c878c03ae8f131c81ea4df8958f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex64 llvm::MachOYAML::FatArch::offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aa33d56236bd375c3b794773f4a9bb2f1">anonymous{MachOEmitter.cpp}::constructFatArch</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>.</p>

</div>
</div>

### reserved {#ad8597b1f87407c555bad3655b0f46bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex32 llvm::MachOYAML::FatArch::reserved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a04e7b80e5a81e549928ca2e08054efa8">anonymous{MachOEmitter.cpp}::writeFatArch&lt; MachO::fat_arch_64 &gt;</a>.</p>

</div>
</div>

### size {#a2d8430cd21c1d9eede148721d0d3a404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachOYAML::FatArch::size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#aa33d56236bd375c3b794773f4a9bb2f1">anonymous{MachOEmitter.cpp}::constructFatArch</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>.</p>

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
