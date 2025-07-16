---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/globalvaluesummary/gvflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GVFlags` Struct Reference

<p>Group flags (Linkage, NotEligibleToImport, etc.) as a bitfield. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::GlobalValueSummary::GVFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> (GlobalValue::LinkageTypes Linkage, GlobalValue::VisibilityTypes Visibility, bool NotEligibleToImport, bool Live, bool IsLocal, bool CanAutoHide, ImportKind ImportType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience Constructors. <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3e4711ebf79a15a08499843071da146">Linkage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The linkage type of the associated global value. <a href="#ab3e4711ebf79a15a08499843071da146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7914ffd4eb71a53515d73ea6abc74a7">Visibility</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates the visibility. <a href="#ac7914ffd4eb71a53515d73ea6abc74a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7df9cb43125220f4198f90440164ba2">NotEligibleToImport</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate if the global value cannot be imported (e.g. <a href="#aa7df9cb43125220f4198f90440164ba2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf60e51668a91b9a24f41451806eb7e8">Live</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In per-module summary, indicate that the global value must be considered a live root for index-based liveness analysis. <a href="#adf60e51668a91b9a24f41451806eb7e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb8213497b192925ad7a95078631469">DSOLocal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates that the linker resolved the symbol to a definition from within the same linkage unit. <a href="#a3bb8213497b192925ad7a95078631469">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68afba1d01d2c8a930fae79199d8e280">CanAutoHide</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the per-module summary, indicates that the global value is linkonce_odr and global unnamed addr (so eligible for auto-hiding via hidden visibility). <a href="#a68afba1d01d2c8a930fae79199d8e280">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999b0f705022f5577410741705b51399">ImportType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field is written by the ThinLTO indexing step to postlink combined summary. <a href="#a999b0f705022f5577410741705b51399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Group flags (Linkage, NotEligibleToImport, etc.) as a bitfield.</p>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GVFlags() {#a25e81b69a07c7a87cdeaf6e732eca2c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalValueSummary::GVFlags::GVFlags (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195">GlobalValue::VisibilityTypes</a> Visibility, bool NotEligibleToImport, bool Live, bool IsLocal, bool CanAutoHide, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737">ImportKind</a> ImportType)</td>
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

<p>Convenience Constructors.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>References <a href="#a68afba1d01d2c8a930fae79199d8e280">CanAutoHide</a>, <a href="#a3bb8213497b192925ad7a95078631469">DSOLocal</a>, <a href="#a999b0f705022f5577410741705b51399">ImportType</a>, <a href="#ab3e4711ebf79a15a08499843071da146">Linkage</a>, <a href="#adf60e51668a91b9a24f41451806eb7e8">Live</a>, <a href="#aa7df9cb43125220f4198f90440164ba2">NotEligibleToImport</a> and <a href="#ac7914ffd4eb71a53515d73ea6abc74a7">Visibility</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CanAutoHide {#a68afba1d01d2c8a930fae79199d8e280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::CanAutoHide</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In the per-module summary, indicates that the global value is linkonce_odr and global unnamed addr (so eligible for auto-hiding via hidden visibility).</p>


<p>In the combined summary, indicates that the prevailing linkonce_odr copy can be auto-hidden via hidden visibility when it is upgraded to weak_odr in the backend. This is legal when all copies are eligible for auto-hiding (i.e. all copies were linkonce_odr global unnamed addr. If any copy is not (e.g. it was originally weak_odr, we cannot auto-hide the prevailing copy as it means the symbol was externally visible.</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### DSOLocal {#a3bb8213497b192925ad7a95078631469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::DSOLocal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates that the linker resolved the symbol to a definition from within the same linkage unit.</p>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### ImportType {#a999b0f705022f5577410741705b51399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::ImportType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This field is written by the ThinLTO indexing step to postlink combined summary.</p>


<p>The value is interpreted as '<a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737">ImportKind</a>' enum defined above.</p>


<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### Linkage {#ab3e4711ebf79a15a08499843071da146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::Linkage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The linkage type of the associated global value.</p>


<p>One use is to flag values that have local linkage types and need to have module identifier appended before placing into the combined index, to disambiguate from other values with the same name. In the future this will be used to update and optimize linkage types based on global summary-based analysis.</p>


<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### Live {#adf60e51668a91b9a24f41451806eb7e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::Live</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In per-module summary, indicate that the global value must be considered a live root for index-based liveness analysis.</p>


<p>Used for special LLVM values such as llvm.global_ctors that the linker does not know about.</p>


<p>In combined summary, indicate that the global value is live.</p>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### NotEligibleToImport {#aa7df9cb43125220f4198f90440164ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::NotEligibleToImport</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate if the global value cannot be imported (e.g.</p>


<p>it cannot be renamed or references something that can't be renamed).</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### Visibility {#ac7914ffd4eb71a53515d73ea6abc74a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GlobalValueSummary::GVFlags::Visibility</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates the visibility.</p>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="#a25e81b69a07c7a87cdeaf6e732eca2c5">GVFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

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
