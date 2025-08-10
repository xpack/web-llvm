---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/xcoffyaml/auxiliaryheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AuxiliaryHeader` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::XCOFFYAML::AuxiliaryHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">llvm/ObjectYAML/XCOFFYAML.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cae70fafed77150576b505c7c3380b">Magic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6e0947dff99e8803fbdef12397680f9">Version</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7c0a3d73b22f7133d8e3e76da67aef">TextStartAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7242d4a79ff84260dc91e8dc4b9d9f">DataStartAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ffc3f6c0877b0d3a942ac5b83f587d1">TOCAnchorAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388cdae94e8b17bfd2af8c486b38cc24">SecNumOfEntryPoint</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f98db2c84836067b746c086e45b8de6">SecNumOfText</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988559fbef434f11630c6332e4cc265f">SecNumOfData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29cc6c96dc30ddd9590c3afcb781dcb5">SecNumOfTOC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c20fe961b9b636c9e0d134c36ed2682">SecNumOfLoader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80f8250480e531c557c3fdff6d15392">SecNumOfBSS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7200e31b1bff0ede0d915b7e185d0499">MaxAlignOfText</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5d49b17967383b56980311083515f3">MaxAlignOfData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a5f28a16f7f0d1930450ed85bb6b66">ModuleType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada52a86c68c37f2c6e8acedeefafca58">CpuFlag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4affd4594ad07149824cc21664c32da3">CpuType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a363b4a61ad1afa43428c717851c56f76">TextPageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b1e3930136fb400ec7d8f434a10cdde">DataPageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b526cc6aa31ac80b30518449b30317f">StackPageSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d6b81d2fbc5000f25e83869c049aa3">FlagAndTDataAlignment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29595c4a284c496198d556f4e9793f70">TextSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa977f6ebddaa8b7a7dcaf70c2ee57178">InitDataSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092e89195569b9ec8fea3c4195bf9b6e">BssDataSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c245e4a66c1ac2840b11fe070dd4e8">EntryPointAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbfa17747f69138d33c939b6e6d46b84">MaxStackSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45691ac7bbebe26daa8dd21b2487c661">MaxDataSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4706f0987c326577fa42b6768e9de0a9">SecNumOfTData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cfa8a46e3e1ff9a016dd24d23f3613d">SecNumOfTBSS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ee5aaf775b37c2da3efe2730899fc8">Flag</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### BssDataSize {#a092e89195569b9ec8fea3c4195bf9b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::BssDataSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### CpuFlag {#ada52a86c68c37f2c6e8acedeefafca58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex8&gt; llvm::XCOFFYAML::AuxiliaryHeader::CpuFlag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### CpuType {#a4affd4594ad07149824cc21664c32da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex8&gt; llvm::XCOFFYAML::AuxiliaryHeader::CpuType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>

</div>
</div>

### DataPageSize {#a8b1e3930136fb400ec7d8f434a10cdde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex8&gt; llvm::XCOFFYAML::AuxiliaryHeader::DataPageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### DataStartAddr {#aed7242d4a79ff84260dc91e8dc4b9d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::DataStartAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### EntryPointAddr {#ad7c245e4a66c1ac2840b11fe070dd4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::EntryPointAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### Flag {#a85ee5aaf775b37c2da3efe2730899fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex16&gt; llvm::XCOFFYAML::AuxiliaryHeader::Flag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### FlagAndTDataAlignment {#ae3d6b81d2fbc5000f25e83869c049aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex8&gt; llvm::XCOFFYAML::AuxiliaryHeader::FlagAndTDataAlignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### InitDataSize {#aa977f6ebddaa8b7a7dcaf70c2ee57178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::InitDataSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### Magic {#a92cae70fafed77150576b505c7c3380b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex16&gt; llvm::XCOFFYAML::AuxiliaryHeader::Magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### MaxAlignOfData {#a5b5d49b17967383b56980311083515f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex16&gt; llvm::XCOFFYAML::AuxiliaryHeader::MaxAlignOfData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### MaxAlignOfText {#a7200e31b1bff0ede0d915b7e185d0499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex16&gt; llvm::XCOFFYAML::AuxiliaryHeader::MaxAlignOfText</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### MaxDataSize {#a45691ac7bbebe26daa8dd21b2487c661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::MaxDataSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### MaxStackSize {#abbfa17747f69138d33c939b6e6d46b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::MaxStackSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### ModuleType {#a06a5f28a16f7f0d1930450ed85bb6b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex16&gt; llvm::XCOFFYAML::AuxiliaryHeader::ModuleType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>

</div>
</div>

### SecNumOfBSS {#ae80f8250480e531c557c3fdff6d15392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfBSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfData {#a988559fbef434f11630c6332e4cc265f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfEntryPoint {#a388cdae94e8b17bfd2af8c486b38cc24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfEntryPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfLoader {#a7c20fe961b9b636c9e0d134c36ed2682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfLoader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfTBSS {#a5cfa8a46e3e1ff9a016dd24d23f3613d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfTBSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfTData {#a4706f0987c326577fa42b6768e9de0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfTData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfText {#a8f98db2c84836067b746c086e45b8de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfText</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### SecNumOfTOC {#a29cc6c96dc30ddd9590c3afcb781dcb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint16_t&gt; llvm::XCOFFYAML::AuxiliaryHeader::SecNumOfTOC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### StackPageSize {#a0b526cc6aa31ac80b30518449b30317f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex8&gt; llvm::XCOFFYAML::AuxiliaryHeader::StackPageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### TextPageSize {#a363b4a61ad1afa43428c717851c56f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex8&gt; llvm::XCOFFYAML::AuxiliaryHeader::TextPageSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### TextSize {#a29595c4a284c496198d556f4e9793f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::TextSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### TextStartAddr {#a3e7c0a3d73b22f7133d8e3e76da67aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::TextStartAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### TOCAnchorAddr {#a7ffc3f6c0877b0d3a942ac5b83f587d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::XCOFFYAML::AuxiliaryHeader::TOCAnchorAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

### Version {#ad6e0947dff99e8803fbdef12397680f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex16&gt; llvm::XCOFFYAML::AuxiliaryHeader::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
