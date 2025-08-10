---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SyntheticTypeNameBuilder.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">llvm/DebugInfo/DWARF/DWARFAcceleratorTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebuginfoentry-h">llvm/DebugInfo/DWARF/DWARFDebugInfoEntry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a> (UnitEntryPairTy UnitEntryPair)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f43087fac32b05f47dcd3c89fc7bbd">TypeAttr</a>[] = {dwarf::DW_AT_type}</td>
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

### getTypeDeduplicationCandidate() {#a123fab946df8deba32a875505ddef3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; UnitEntryPairTy &gt; getTypeDeduplicationCandidate (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> UnitEntryPair)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#ad961b9c792517de751570e73618293ba">llvm::dwarf_linker::parallel::UnitEntryPairTy::getNamespaceOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#ac0f5b717fb77c6c02c668e29b9764c9e">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addDIETypeName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a1ead8e73f45a8c9a08f8ae11d89cfecb">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addParentName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### TypeAttr {#a83f43087fac32b05f47dcd3c89fc7bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Attribute TypeAttr[] = {dwarf::DW_AT_type}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a461535e36ca5b8a26e8fb2901a23941d">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addParamNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a086f090ebea74999eafa96dc69047a67">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTemplateParamNames</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#ab2bf71aa33f172d69cb90abfeb10695f">llvm::DWARFTypePrinter&lt; DieType &gt;::appendTemplateParameters</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
