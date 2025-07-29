---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/openmpirbuilder/targetdatartargs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TargetDataRTArgs` Struct

<p>Container for the arguments used to pass data to the runtime library. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OpenMPIRBuilder::TargetDataRTArgs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456264f5524ecbab63a41b61a2eb9ee7">TargetDataRTArgs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a> (Value *BasePointersArray, Value *PointersArray, Value *SizesArray, Value *MapTypesArray, Value *MapTypesArrayEnd, Value *MappersArray, Value *MapNamesArray)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa998b8b179dd186fe4b5a1f6b6e25327">BasePointersArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of base pointer passed to the runtime library. <a href="#aa998b8b179dd186fe4b5a1f6b6e25327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44027c71c6a6a9a4111594eeb16da30e">PointersArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of section pointers passed to the runtime library. <a href="#a44027c71c6a6a9a4111594eeb16da30e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00635325d57af0b95f0b797f63ee6df6">SizesArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of sizes passed to the runtime library. <a href="#a00635325d57af0b95f0b797f63ee6df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc59185affff631915c34412a350c8c">MapTypesArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of map types passed to the runtime library for the beginning of the region or for the entire region if there are no separate map types for the region end. <a href="#abfc59185affff631915c34412a350c8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa67b508fb4ba886c018192e5a8d21e">MapTypesArrayEnd</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of map types passed to the runtime library for the end of the region, or nullptr if there are no separate map types for the region end. <a href="#a4fa67b508fb4ba886c018192e5a8d21e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b54534e64cdf22a09f26ddacebe69ac">MappersArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of user-defined mappers passed to the runtime library. <a href="#a4b54534e64cdf22a09f26ddacebe69ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8f3378279256a13c9938a109ef38fe">MapNamesArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The array of original declaration names of mapped pointers sent to the runtime library for debugging. <a href="#aff8f3378279256a13c9938a109ef38fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Container for the arguments used to pass data to the runtime library.</p>

<p>Definition at line 2202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetDataRTArgs() {#a456264f5524ecbab63a41b61a2eb9ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::TargetDataRTArgs::TargetDataRTArgs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### TargetDataRTArgs() {#a1fd0da634ba0e9b861b5028332970245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::TargetDataRTArgs::TargetDataRTArgs (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BasePointersArray, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PointersArray, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * SizesArray, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MapTypesArray, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MapTypesArrayEnd, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MappersArray, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MapNamesArray)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#aa998b8b179dd186fe4b5a1f6b6e25327">BasePointersArray</a>, <a href="#aff8f3378279256a13c9938a109ef38fe">MapNamesArray</a>, <a href="#a4b54534e64cdf22a09f26ddacebe69ac">MappersArray</a>, <a href="#abfc59185affff631915c34412a350c8c">MapTypesArray</a>, <a href="#a4fa67b508fb4ba886c018192e5a8d21e">MapTypesArrayEnd</a>, <a href="#a44027c71c6a6a9a4111594eeb16da30e">PointersArray</a> and <a href="#a00635325d57af0b95f0b797f63ee6df6">SizesArray</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BasePointersArray {#aa998b8b179dd186fe4b5a1f6b6e25327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::BasePointersArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of base pointer passed to the runtime library.</p>

<p>Definition at line 2204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

</div>
</div>

### MapNamesArray {#aff8f3378279256a13c9938a109ef38fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::MapNamesArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of original declaration names of mapped pointers sent to the runtime library for debugging.</p>

<p>Definition at line 2221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

</div>
</div>

### MappersArray {#a4b54534e64cdf22a09f26ddacebe69ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::MappersArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of user-defined mappers passed to the runtime library.</p>

<p>Definition at line 2218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

</div>
</div>

### MapTypesArray {#abfc59185affff631915c34412a350c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::MapTypesArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of map types passed to the runtime library for the beginning of the region or for the entire region if there are no separate map types for the region end.</p>

<p>Definition at line 2212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

</div>
</div>

### MapTypesArrayEnd {#a4fa67b508fb4ba886c018192e5a8d21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::MapTypesArrayEnd = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of map types passed to the runtime library for the end of the region, or nullptr if there are no separate map types for the region end.</p>

<p>Definition at line 2216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

</div>
</div>

### PointersArray {#a44027c71c6a6a9a4111594eeb16da30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::PointersArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of section pointers passed to the runtime library.</p>

<p>Definition at line 2206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

</div>
</div>

### SizesArray {#a00635325d57af0b95f0b797f63ee6df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::OpenMPIRBuilder::TargetDataRTArgs::SizesArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The array of sizes passed to the runtime library.</p>

<p>Definition at line 2208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a> and <a href="#a1fd0da634ba0e9b861b5028332970245">TargetDataRTArgs</a>.</p>

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
