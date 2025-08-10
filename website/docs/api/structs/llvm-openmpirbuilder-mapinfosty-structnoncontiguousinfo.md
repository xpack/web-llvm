---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/openmpirbuilder/mapinfosty/structnoncontiguousinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `StructNonContiguousInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f192a9701952d6ffe90fd19beb0a71">IsNonContiguous</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a44f261ea64dfab54a32fedf028c7c33f">MapDimArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455750a6772d7b4dbf49c6e2a6892bee">Dims</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a708e1a451b8b9f851317bbd2ab0d9118">MapNonContiguousArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279b64a58a905fae32a957b2e0036b6a">Offsets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a708e1a451b8b9f851317bbd2ab0d9118">MapNonContiguousArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a7ec15dbfee1518848d8c415e8ec1b">Counts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a708e1a451b8b9f851317bbd2ab0d9118">MapNonContiguousArrayTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4726949bede9ff73a4defca2a4e00d7">Strides</a></td>
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


<p>Definition at line 2365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Counts {#a91a7ec15dbfee1518848d8c415e8ec1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapNonContiguousArrayTy llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Counts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a635fd9f6c5f2092419d60086cb1e0b87">llvm::OpenMPIRBuilder::MapInfosTy::append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a>.</p>

</div>
</div>

### Dims {#a455750a6772d7b4dbf49c6e2a6892bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapDimArrayTy llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Dims</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a635fd9f6c5f2092419d60086cb1e0b87">llvm::OpenMPIRBuilder::MapInfosTy::append</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### IsNonContiguous {#a63f192a9701952d6ffe90fd19beb0a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::IsNonContiguous = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### Offsets {#a279b64a58a905fae32a957b2e0036b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapNonContiguousArrayTy llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Offsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a635fd9f6c5f2092419d60086cb1e0b87">llvm::OpenMPIRBuilder::MapInfosTy::append</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>.</p>

</div>
</div>

### Strides {#ae4726949bede9ff73a4defca2a4e00d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapNonContiguousArrayTy llvm::OpenMPIRBuilder::MapInfosTy::StructNonContiguousInfo::Strides</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a635fd9f6c5f2092419d60086cb1e0b87">llvm::OpenMPIRBuilder::MapInfosTy::append</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
