---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/helper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The methods to access OrigUnit Reference



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFUnit &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4a7a4b7dd835a0d0791b13322e3b5679">getOrigUnit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns paired compile unit from input DWARF. <a href="#ga4a7a4b7dd835a0d0791b13322e3b5679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga122417b360a01a5ac081c1c9b4aa971a">getFirstChildEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0b2870f844dabdc24d144e1cd4b95fe0">getSiblingEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga64ac1b3c171031003b392861e7fd8b2d">getParent</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga28d62fd02c932ec4b1e956b615747906">getDIEAtIndex</a> (unsigned Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4793154b7cb56b07edd053ee0f2a34b9">getDebugInfoEntry</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga619b3ce46249265bdc72744dec7e953a">getUnitDIE</a> (bool ExtractUnitDIEOnly=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga344f9eb0eda77b2c26871e2e0b55186a">getDIE</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab537c76e7cadfb09365273a0fae0e896">getDIEIndex</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac74dc3072176bf9eb4fd1f2db6ea9d3d">getDIEIndex</a> (const DWARFDie &amp;Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; DWARFFormValue &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaed7fe8d7d740751efb3cd56d309a63e9">find</a> (uint32_t DieIdx, ArrayRef&lt; dwarf::Attribute &gt; Attrs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; DWARFFormValue &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga36cc8fce6194aa7a20ae36da44795e70">find</a> (const DWARFDebugInfoEntry *Die, ArrayRef&lt; dwarf::Attribute &gt; Attrs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga15d48891883ccbfff9602a3c00b2f326">getDIEIndexForOffset</a> (uint64_t Offset)</td>
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


<div class="doxySectionDef">

## Functions

### find() {#gaed7fe8d7d740751efb3cd56d309a63e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; llvm::dwarf_linker::parallel::CompileUnit::find (uint32_t DieIdx, ArrayRef&lt; dwarf::Attribute &gt; Attrs)</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aea3108f6ef726c8e9b0d244f51230050">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addArrayDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a53c9ecdd82532a2231dca73e685f4ae3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDieNameFromDeclFileAndDeclLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a0186dfd0c814155d8e6a9cab1969afdd">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addReferencedODRDies</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ae03fdc522b86805416485b83c76a27a3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aeee2046e220e7591b37234b1e818f2d6">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addValueName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae4cfe0d2715277bd9e110855ed46c66a">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### find() {#ga36cc8fce6194aa7a20ae36da44795e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; llvm::dwarf_linker::parallel::CompileUnit::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * Die, ArrayRef&lt; dwarf::Attribute &gt; Attrs)</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#af1912d641eadda862e32bbb231a13e50">llvm::DWARFDebugInfoEntry::getAbbreviationDeclarationPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a74338425061cc0d9df5fe5398d48d9f2">llvm::DWARFDebugInfoEntry::getOffset</a>.</p>

</div>
</div>

### getDebugInfoEntry() {#ga4793154b7cb56b07edd053ee0f2a34b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * llvm::dwarf_linker::parallel::CompileUnit::getDebugInfoEntry (unsigned Index)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a63c52ca4471973f37308391bf9f5979e">llvm::dwarf_linker::parallel::CompileUnit::analyzeDWARFStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2ce07f2980494b70fbc5b5c8b7eac63a">llvm::dwarf_linker::parallel::CompileUnit::assignTypeNames</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### getDIE() {#ga344f9eb0eda77b2c26871e2e0b55186a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::dwarf_linker::parallel::CompileUnit::getDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * Die)</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>.</p>

</div>
</div>

### getDIEAtIndex() {#ga28d62fd02c932ec4b1e956b615747906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::dwarf_linker::parallel::CompileUnit::getDIEAtIndex (unsigned Index)</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getDIEIndex() {#gab537c76e7cadfb09365273a0fae0e896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf_linker::parallel::CompileUnit::getDIEIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * Die)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>.</p>

</div>
</div>

### getDIEIndex() {#gac74dc3072176bf9eb4fd1f2db6ea9d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf_linker::parallel::CompileUnit::getDIEIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie &amp; Die)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getDIEIndexForOffset() {#ga15d48891883ccbfff9602a3c00b2f326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::dwarf_linker::parallel::CompileUnit::getDIEIndexForOffset (uint64_t Offset)</td>
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



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### getFirstChildEntry() {#ga122417b360a01a5ac081c1c9b4aa971a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * llvm::dwarf_linker::parallel::CompileUnit::getFirstChildEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * Die)</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aea3108f6ef726c8e9b0d244f51230050">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addArrayDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>.</p>

</div>
</div>

### getOrigUnit() {#ga4a7a4b7dd835a0d0791b13322e3b5679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit &amp; llvm::dwarf_linker::parallel::CompileUnit::getOrigUnit ()</td>
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

<p>Returns paired compile unit from input DWARF.</p>

<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2c8b9ba6422c57fd4edb9b5771b650d2">llvm::dwarf_linker::parallel::CompileUnit::cleanupDataAfterClonning</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b155dc5f7f9374eb06f7277da633577">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#aab5e3c8afd376c7fedfcd02a86d31540">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugMacro</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a67e7cb91f1de318011b4ad8f6453fa7a">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/groups/group/#ga67e10343676779815d39ecb9f3494161">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga46715474259d177dfee3f64cb84060b9">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#gaebaf347b4df991192eb43b3f5ec6982d">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga4d4950c415f9a38bf821dc4fac3d1fa3">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga24d254de081807f2007f1791d41dbcc2">llvm::dwarf_linker::parallel::CompileUnit::getDieOutOffset</a>, <a href="/web-llvm/docs/api/groups/group/#ga78fda22e9740aea1e9dad0b83f09b667">llvm::dwarf_linker::parallel::CompileUnit::getDieTypeEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#affd8bc2fe0d879ef4ad2538a617e7629">llvm::dwarf_linker::parallel::CompileUnit::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a91509cfc9da285731d483b1373c8584d">llvm::dwarf_linker::parallel::CompileUnit::loadInputDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#aee0400306419adf13952ab2f6734fc0a">llvm::dwarf_linker::parallel::CompileUnit::loadLineTable</a>, <a href="/web-llvm/docs/api/groups/group/#gaa4bca7959b19725916051fad326d8ddf">llvm::dwarf_linker::parallel::CompileUnit::setDieTypeEntry</a> and <a href="/web-llvm/docs/api/groups/methods/#gae294385bb587a12499b98215ae8e7745">llvm::dwarf_linker::parallel::CompileUnit::warn</a>.</p>

</div>
</div>

### getParent() {#ga64ac1b3c171031003b392861e7fd8b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::dwarf_linker::parallel::CompileUnit::getParent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * Die)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getSiblingEntry() {#ga0b2870f844dabdc24d144e1cd4b95fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * llvm::dwarf_linker::parallel::CompileUnit::getSiblingEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * Die)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aea3108f6ef726c8e9b0d244f51230050">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addArrayDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a1df1c26e0a60f062547d6ba537e0021a">llvm::dwarf_linker::parallel::CompileUnit::cloneDIE</a>.</p>

</div>
</div>

### getUnitDIE() {#ga619b3ce46249265bdc72744dec7e953a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::dwarf_linker::parallel::CompileUnit::getUnitDIE (bool ExtractUnitDIEOnly=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a63c52ca4471973f37308391bf9f5979e">llvm::dwarf_linker::parallel::CompileUnit::analyzeDWARFStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2ce07f2980494b70fbc5b5c8b7eac63a">llvm::dwarf_linker::parallel::CompileUnit::assignTypeNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a91509cfc9da285731d483b1373c8584d">llvm::dwarf_linker::parallel::CompileUnit::loadInputDIEs</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
