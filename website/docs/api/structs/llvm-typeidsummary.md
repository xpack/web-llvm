---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/typeidsummary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TypeIdSummary` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::TypeIdSummary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/typetestresolution">TypeTestResolution</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bc0b8f2041f3a3839f393f1a6aae33">TTRes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d5759cee861fcfca3b26ff5927e83c">WPDRes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from byte offset to whole-program devirt resolution for that (typeid, byte offset) pair. <a href="#a01d5759cee861fcfca3b26ff5927e83c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### TTRes {#a80bc0b8f2041f3a3839f393f1a6aae33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeTestResolution llvm::TypeIdSummary::TTRes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-6b7e56206de5417b61b501a03fcc04bd/#a9a6a7499bb609851662697044aa117a5">llvm::yaml::MappingTraits&lt; TypeIdSummary &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7ccea8ba8bd9770a7999071a79f9a1c2">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdSummary</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeTestUsers</a>.</p>

</div>
</div>

### WPDRes {#a01d5759cee861fcfca3b26ff5927e83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, WholeProgramDevirtResolution&gt; llvm::TypeIdSummary::WPDRes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from byte offset to whole-program devirt resolution for that (typeid, byte offset) pair.</p>

<p>Definition at line 1289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a2571433d1b220fb84bfcb7584002cb02">anonymous{WholeProgramDevirt.cpp}::DevirtModule::importResolution</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-6b7e56206de5417b61b501a03fcc04bd/#a9a6a7499bb609851662697044aa117a5">llvm::yaml::MappingTraits&lt; TypeIdSummary &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7ccea8ba8bd9770a7999071a79f9a1c2">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdSummary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
