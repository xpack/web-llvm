---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/wholeprogramdevirtresolution/byarg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ByArg` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::WholeProgramDevirtResolution::ByArg { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#a73c235c3b51fc129ec890391feccd47e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a73c235c3b51fc129ec890391feccd47e">llvm::WholeProgramDevirtResolution::ByArg::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf13a890a40972d903f329d37c5ad98a">TheKind</a> = <a href="#a73c235c3b51fc129ec890391feccd47ea8c8876be61a5890671404484313a21e5">Indir</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e46342d3d79c56fb3b498722a66f18">Info</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional information for the resolution: <a href="#ac1e46342d3d79c56fb3b498722a66f18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc8593fe943d570b5a3fe549132fdff">Byte</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a555cfcbd8d83cdbf785f01b88be68">Bit</a> = 0</td>
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


<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#a73c235c3b51fc129ec890391feccd47e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WholeProgramDevirtResolution::ByArg::Kind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Indir<a id="a73c235c3b51fc129ec890391feccd47ea8c8876be61a5890671404484313a21e5"></a></td>
<td class="doxyEnumItemDescription">Just do a regular virtual call</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UniformRetVal<a id="a73c235c3b51fc129ec890391feccd47ea635d252c06de8cd5c96ebcf3d8989ccf"></a></td>
<td class="doxyEnumItemDescription">Uniform return value optimization</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UniqueRetVal<a id="a73c235c3b51fc129ec890391feccd47ea8bf72562c0a17a25f9e07863e68543b3"></a></td>
<td class="doxyEnumItemDescription">Unique return value optimization</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VirtualConstProp<a id="a73c235c3b51fc129ec890391feccd47ea7382e969306ae2118ae88db2a241e833"></a></td>
<td class="doxyEnumItemDescription">Virtual constant propagation</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Bit {#a74a555cfcbd8d83cdbf785f01b88be68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::WholeProgramDevirtResolution::ByArg::Bit = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7ad99ec350487a043ea3bd282a0833a8/#a0f306d3f2c21090ca669a66d649cd2e9">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution::ByArg &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a85892c8cb2a8b36248f88a963d8a09ca">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryVirtualConstProp</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a>.</p>

</div>
</div>

### Byte {#afcc8593fe943d570b5a3fe549132fdff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::WholeProgramDevirtResolution::ByArg::Byte = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7ad99ec350487a043ea3bd282a0833a8/#a0f306d3f2c21090ca669a66d649cd2e9">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution::ByArg &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a85892c8cb2a8b36248f88a963d8a09ca">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryVirtualConstProp</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a>.</p>

</div>
</div>

### Info {#ac1e46342d3d79c56fb3b498722a66f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::WholeProgramDevirtResolution::ByArg::Info = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Additional information for the resolution:</p>


<ul class="doxyList ">
<li>UniformRetVal: the uniform return value.</li>
<li>UniqueRetVal: the return value associated with the unique vtable (0 or 1).</li>
</ul>

<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7ad99ec350487a043ea3bd282a0833a8/#a0f306d3f2c21090ca669a66d649cd2e9">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution::ByArg &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae1cb89e56d053bfe29124d830ef0ac94">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryUniformRetValOpt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a4dc69b6c381a3b54539a9eff3e7d1d3f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryUniqueRetValOpt</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a>.</p>

</div>
</div>

### TheKind {#acf13a890a40972d903f329d37c5ad98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WholeProgramDevirtResolution::ByArg::Kind llvm::WholeProgramDevirtResolution::ByArg::TheKind = <a href="#a73c235c3b51fc129ec890391feccd47ea8c8876be61a5890671404484313a21e5">Indir</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7ad99ec350487a043ea3bd282a0833a8/#a0f306d3f2c21090ca669a66d649cd2e9">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution::ByArg &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae1cb89e56d053bfe29124d830ef0ac94">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryUniformRetValOpt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a4dc69b6c381a3b54539a9eff3e7d1d3f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryUniqueRetValOpt</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a85892c8cb2a8b36248f88a963d8a09ca">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryVirtualConstProp</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
