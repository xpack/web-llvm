---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/openmpirbuilder/mapinfosty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MapInfosTy` Struct

<p>This structure contains combined information generated for mappable clauses, including base pointers, pointers, sizes, map types, user-defined mappers, and non-contiguous information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OpenMPIRBuilder::MapInfosTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a> (MapInfosTy &amp;CurInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append arrays in <em>CurInfo</em>. <a href="#a635fd9f6c5f2092419d60086cb1e0b87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a83dc195f27cf9d455f808cd6d0d17e57">MapValuesArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0b33fc6977b91af2e3a595430af816">BasePointers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a83dc195f27cf9d455f808cd6d0d17e57">MapValuesArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fbb78e0f7d3e62a8dc557721b761c2">Pointers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a751d216ddce395dc7fa49fcf8e0a82c0">MapDeviceInfoArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a5c5757b7d47dac50e0cdd270e52ae">DevicePointers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a83dc195f27cf9d455f808cd6d0d17e57">MapValuesArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae351998f1a0107dc5b8f4ea32fe0c60">Sizes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a62976e7f4bbb16d15c3483044afe20e7">MapFlagsArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81575ee2bccba5b439ed4d436ffa53ed">Types</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4ab7cfa9fab97684d498b889987bcc74">MapNamesArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b3b8488a8b835c326ac389bed33f14">Names</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo">StructNonContiguousInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3dff2ccb3dbfbc0659e74acec6c421">NonContigInfo</a></td>
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

<p>This structure contains combined information generated for mappable clauses, including base pointers, pointers, sizes, map types, user-defined mappers, and non-contiguous information.</p>

<p>Definition at line 2364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### append() {#a635fd9f6c5f2092419d60086cb1e0b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::MapInfosTy::append (<a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty">MapInfosTy</a> &amp; CurInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append arrays in <em>CurInfo</em>.</p>

<p>Definition at line 2381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a7f0b33fc6977b91af2e3a595430af816">BasePointers</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a91a7ec15dbfee1518848d8c415e8ec1b">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Counts</a>, <a href="#a71a5c5757b7d47dac50e0cdd270e52ae">DevicePointers</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a455750a6772d7b4dbf49c6e2a6892bee">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Dims</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a87b3b8488a8b835c326ac389bed33f14">Names</a>, <a href="#add3dff2ccb3dbfbc0659e74acec6c421">NonContigInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#a279b64a58a905fae32a957b2e0036b6a">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Offsets</a>, <a href="#ac3fbb78e0f7d3e62a8dc557721b761c2">Pointers</a>, <a href="#aae351998f1a0107dc5b8f4ea32fe0c60">Sizes</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo/#ae4726949bede9ff73a4defca2a4e00d7">llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Strides</a> and <a href="#a81575ee2bccba5b439ed4d436ffa53ed">Types</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BasePointers {#a7f0b33fc6977b91af2e3a595430af816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapValuesArrayTy llvm::OpenMPIRBuilder::MapInfosTy::BasePointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### DevicePointers {#a71a5c5757b7d47dac50e0cdd270e52ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapDeviceInfoArrayTy llvm::OpenMPIRBuilder::MapInfosTy::DevicePointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### Names {#a87b3b8488a8b835c326ac389bed33f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapNamesArrayTy llvm::OpenMPIRBuilder::MapInfosTy::Names</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### NonContigInfo {#add3dff2ccb3dbfbc0659e74acec6c421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructNonContiguousInfo llvm::OpenMPIRBuilder::MapInfosTy::NonContigInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### Pointers {#ac3fbb78e0f7d3e62a8dc557721b761c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapValuesArrayTy llvm::OpenMPIRBuilder::MapInfosTy::Pointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### Sizes {#aae351998f1a0107dc5b8f4ea32fe0c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapValuesArrayTy llvm::OpenMPIRBuilder::MapInfosTy::Sizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### Types {#a81575ee2bccba5b439ed4d436ffa53ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapFlagsArrayTy llvm::OpenMPIRBuilder::MapInfosTy::Types</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a635fd9f6c5f2092419d60086cb1e0b87">append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
