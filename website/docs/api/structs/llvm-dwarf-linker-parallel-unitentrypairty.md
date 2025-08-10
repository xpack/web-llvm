---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/unitentrypairty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `UnitEntryPairTy` Struct

<p>This is a helper structure which keeps a debug info entry with it's containing compilation unit. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::UnitEntryPairTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinker/Parallel/DWARFLinkerCompileUnit.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f49d46393124150ae0758363739301">UnitEntryPairTy</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00ccfaa561fd47b12f5e0c46991e08e">UnitEntryPairTy</a> (CompileUnit *CU, const DWARFDebugInfoEntry *DieEntry)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad961b9c792517de751570e73618293ba">getNamespaceOrigin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55cd7dad28a1cbc0330d57e9613f8fc">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b782888847c9ffd3c67ff187783af0">CU</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c2b2cb0d8ba2bd1233b6482d15f36d">DieEntry</a> = nullptr</td>
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

<p>This is a helper structure which keeps a debug info entry with it's containing compilation unit.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnitEntryPairTy() {#a55f49d46393124150ae0758363739301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::UnitEntryPairTy::UnitEntryPairTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#ad961b9c792517de751570e73618293ba">getNamespaceOrigin</a> and <a href="#ab55cd7dad28a1cbc0330d57e9613f8fc">getParent</a>.</p>

</div>
</div>

### UnitEntryPairTy() {#aa00ccfaa561fd47b12f5e0c46991e08e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::UnitEntryPairTy::UnitEntryPairTy (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> * CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="#af5c2b2cb0d8ba2bd1233b6482d15f36d">DieEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNamespaceOrigin() {#ad961b9c792517de751570e73618293ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnitEntryPairTy UnitEntryPairTy::getNamespaceOrigin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="#a52b782888847c9ffd3c67ff187783af0">CU</a>, <a href="#af5c2b2cb0d8ba2bd1233b6482d15f36d">DieEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp/#a7bc7aa181f977cf03466ea878c066a84">MAX_REFERENCIES_DEPTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479fad28670925b341cc0d43e6a0535646d38">llvm::dwarf_linker::parallel::Resolve</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a> and <a href="#a55f49d46393124150ae0758363739301">UnitEntryPairTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a>.</p>

</div>
</div>

### getParent() {#ab55cd7dad28a1cbc0330d57e9613f8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; UnitEntryPairTy &gt; UnitEntryPairTy::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 1792 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="#af5c2b2cb0d8ba2bd1233b6482d15f36d">DieEntry</a> and <a href="#a55f49d46393124150ae0758363739301">UnitEntryPairTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a1ead8e73f45a8c9a08f8ae11d89cfecb">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addParentName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CU {#a52b782888847c9ffd3c67ff187783af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit* llvm::dwarf_linker::parallel::UnitEntryPairTy::CU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aea3108f6ef726c8e9b0d244f51230050">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addArrayDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a53c9ecdd82532a2231dca73e685f4ae3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDieNameFromDeclFileAndDeclLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac0f5b717fb77c6c02c668e29b9764c9e">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDIETypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a0186dfd0c814155d8e6a9cab1969afdd">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addReferencedODRDies</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ae03fdc522b86805416485b83c76a27a3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aeee2046e220e7591b37234b1e818f2d6">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addValueName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac007678ea81a8e5ab91596fb0825513c">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::assignName</a>, <a href="#ad961b9c792517de751570e73618293ba">getNamespaceOrigin</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#af28b850047c908b6602c0783a0c4688f">llvm::dwarf_linker::parallel::DependencyTracker::updateDependenciesCompleteness</a>.</p>

</div>
</div>

### DieEntry {#af5c2b2cb0d8ba2bd1233b6482d15f36d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aea3108f6ef726c8e9b0d244f51230050">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addArrayDimension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a53c9ecdd82532a2231dca73e685f4ae3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDieNameFromDeclFileAndDeclLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac0f5b717fb77c6c02c668e29b9764c9e">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDIETypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a0186dfd0c814155d8e6a9cab1969afdd">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addReferencedODRDies</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ae03fdc522b86805416485b83c76a27a3">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#aeee2046e220e7591b37234b1e818f2d6">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addValueName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac007678ea81a8e5ab91596fb0825513c">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::assignName</a>, <a href="#ad961b9c792517de751570e73618293ba">getNamespaceOrigin</a>, <a href="#ab55cd7dad28a1cbc0330d57e9613f8fc">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a>, <a href="#aa00ccfaa561fd47b12f5e0c46991e08e">UnitEntryPairTy</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#af28b850047c908b6602c0783a0c4688f">llvm::dwarf_linker::parallel::DependencyTracker::updateDependenciesCompleteness</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
