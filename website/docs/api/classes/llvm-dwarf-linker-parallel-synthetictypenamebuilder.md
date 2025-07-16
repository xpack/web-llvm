---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SyntheticTypeNameBuilder` Class Reference

<p>The helper class to build type name based on <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> properties. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">DWARFLinker/Parallel/SyntheticTypeNameBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ed13db9bc68f498cef6781d0c56f76">SyntheticTypeNameBuilder</a> (TypePool &amp;TypePoolRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac007678ea81a8e5ab91596fb0825513c">assignName</a> (UnitEntryPairTy InputUnitEntryPair, std::optional&lt; std::pair&lt; size_t, size_t &gt; &gt; ChildIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create synthetic name for the specified <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> <span class="doxyComputerOutput">InputUnitEntryPair</span> and assign created name to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> type info. <a href="#ac007678ea81a8e5ab91596fb0825513c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3108f6ef726c8e9b0d244f51230050">addArrayDimension</a> (UnitEntryPairTy InputUnitEntryPair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add array type dimension. <a href="#aea3108f6ef726c8e9b0d244f51230050">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa9676347c5ae75e905430f8e0897ea">addSignature</a> (UnitEntryPairTy InputUnitEntryPair, bool addTemplateParameters)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add signature( entry type plus type of parameters plus type of template parameters(if <span class="doxyComputerOutput">addTemplateParameters</span> is true). <a href="#a3fa9676347c5ae75e905430f8e0897ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461535e36ca5b8a26e8fb2901a23941d">addParamNames</a> (CompileUnit &amp;CU, SmallVector&lt; const DWARFDebugInfoEntry *, 20 &gt; &amp;FunctionParameters)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add specified <span class="doxyComputerOutput">FunctionParameters</span> to the built name. <a href="#a461535e36ca5b8a26e8fb2901a23941d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086f090ebea74999eafa96dc69047a67">addTemplateParamNames</a> (CompileUnit &amp;CU, SmallVector&lt; const DWARFDebugInfoEntry *, 10 &gt; &amp;TemplateParameters)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add specified <span class="doxyComputerOutput">TemplateParameters</span> to the built name. <a href="#a086f090ebea74999eafa96dc69047a67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bafd85c5f3303a3dfe173951bc6b9a">addOrderedName</a> (CompileUnit &amp;CU, const DWARFDebugInfoEntry *DieEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add ordered name to the built name. <a href="#a35bafd85c5f3303a3dfe173951bc6b9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a> (UnitEntryPairTy InputUnitEntryPair, bool AssignNameToTypeDescriptor, ArrayRef&lt; dwarf::Attribute &gt; ODRAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze <span class="doxyComputerOutput">InputUnitEntryPair's</span> ODR attributes and put names of the referenced type dies to the built name. <a href="#a0186dfd0c814155d8e6a9cab1969afdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ead8e73f45a8c9a08f8ae11d89cfecb">addParentName</a> (UnitEntryPairTy &amp;InputUnitEntryPair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add names of parent dies to the built name. <a href="#a1ead8e73f45a8c9a08f8ae11d89cfecb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c9ecdd82532a2231dca73e685f4ae3">addDieNameFromDeclFileAndDeclLine</a> (UnitEntryPairTy &amp;InputUnitEntryPair, bool &amp;HasDeclFileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e80bf7b79d77fda1c18134835ee26d">addTypePrefix</a> (const DWARFDebugInfoEntry *DieEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add type prefix to the built name. <a href="#ab4e80bf7b79d77fda1c18134835ee26d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a> (UnitEntryPairTy InputUnitEntryPair, bool AddParentNames)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add type name to the built name. <a href="#ae03fdc522b86805416485b83c76a27a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a> (UnitEntryPairTy InputUnitEntryPair, std::optional&lt; std::pair&lt; size_t, size_t &gt; &gt; ChildIndex, bool AssignNameToTypeDescriptor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze <span class="doxyComputerOutput">InputUnitEntryPair</span> for the type name and possibly assign built type name to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s type info. <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf0c84320ea66223b29c09fa3740e50">addOrderedName</a> (std::pair&lt; size_t, size_t &gt; ChildIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add ordered name to the built name. <a href="#abaf0c84320ea66223b29c09fa3740e50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee2046e220e7591b37234b1e818f2d6">addValueName</a> (UnitEntryPairTy InputUnitEntryPair, dwarf::Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add value name to the built name. <a href="#aeee2046e220e7591b37234b1e818f2d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 1000 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60e80384471b338195888b7933df892">SyntheticName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Buffer keeping bult name. <a href="#ab60e80384471b338195888b7933df892">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852cdc3d7fa3fb3e04248ee28c78d6cf">RecursionDepth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursion counter. <a href="#a852cdc3d7fa3fb3e04248ee28c78d6cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b89caefc9c557f7d6e6b89657a6e04">TypePoolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> pool. <a href="#a64b89caefc9c557f7d6e6b89657a6e04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The helper class to build type name based on <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> properties.</p>


<p>It builds synthetic name based on explicit attributes: DW_AT_name, DW_AT_linkage_name or based on implicit attributes(DW_AT_decl*). Names for specific DIEs(like subprograms, template classes...) include additional attributes: subprogram parameters, template parameters, array ranges. Examples of built name:</p>


<p>class A { } : {8}A</p>


<p>namspace llvm { class A { } } : {1}llvm{8}A</p>


<p>template &lt;int&gt; structure B { } : {F}B&lt;{0}int&gt;</p>


<p>void foo ( int p1, float p3 ) : {a}void foo({0}int, {0}int)</p>


<p>int *ptr; : {c}ptr {0}int</p>


<p>int var; : {d}var</p>


<p>These names is used to refer DIEs describing types.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SyntheticTypeNameBuilder() {#ae3ed13db9bc68f498cef6781d0c56f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::SyntheticTypeNameBuilder (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typepool">TypePool</a> &amp; TypePoolRef)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Reference <a href="#a64b89caefc9c557f7d6e6b89657a6e04">TypePoolRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignName() {#ac007678ea81a8e5ab91596fb0825513c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::assignName (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair, std::optional&lt; std::pair&lt; size_t, size_t &gt; &gt; ChildIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create synthetic name for the specified <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> <span class="doxyComputerOutput">InputUnitEntryPair</span> and assign created name to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> type info.</p>


<p><span class="doxyComputerOutput">ChildIndex</span> is used to create name for ordered DIEs(function arguments f.e.).</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/group/#ga3cc183d3d4b3e914db2998f157d22e8a">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga29be93ac65e487988de0407cc51f6317">llvm::dwarf_linker::parallel::CompileUnit::getDieTypeEntry</a>, <a href="#a852cdc3d7fa3fb3e04248ee28c78d6cf">RecursionDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addArrayDimension() {#aea3108f6ef726c8e9b0d244f51230050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SyntheticTypeNameBuilder::addArrayDimension (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add array type dimension.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#af1912d641eadda862e32bbb231a13e50">llvm::DWARFDebugInfoEntry::getAbbreviationDeclarationPtr</a>, <a href="/web-llvm/docs/api/groups/helper/#ga122417b360a01a5ac081c1c9b4aa971a">llvm::dwarf_linker::parallel::CompileUnit::getFirstChildEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#ga0b2870f844dabdc24d144e1cd4b95fe0">llvm::dwarf_linker::parallel::CompileUnit::getSiblingEntry</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>


<p>Referenced by <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>.</p>

</div>
</div>

### addDieNameFromDeclFileAndDeclLine() {#a53c9ecdd82532a2231dca73e685f4ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SyntheticTypeNameBuilder::addDieNameFromDeclFileAndDeclLine (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; InputUnitEntryPair, bool &amp; HasDeclFileName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>synthetic name of the specified <span class="doxyComputerOutput">DieEntry</span>. The name is constructed from the dwarf::DW_AT_decl_file and dwarf::DW_AT_decl_line attributes.</p></dd>
</dl>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#adc641b1f4e9cea792161329bdaab4078">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>, <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>


<p>Referenced by <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>.</p>

</div>
</div>

### addDIETypeName() {#ac0f5b717fb77c6c02c668e29b9764c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addDIETypeName (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair, std::optional&lt; std::pair&lt; size_t, size_t &gt; &gt; ChildIndex, bool AssignNameToTypeDescriptor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze <span class="doxyComputerOutput">InputUnitEntryPair</span> for the type name and possibly assign built type name to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s type info.</p>


<p>NOTE: while analyzing types we may create different kind of names for the same type depending on whether the type is part of another type. f.e. DW_TAG_formal_parameter would receive "{02}01" name when examined alone. Or "{0}int" name when it is a part of a function name: {a}void foo({0}int). The <span class="doxyComputerOutput">AssignNameToTypeDescriptor</span> tells whether the type name is part of another type name and then should not be assigned to <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> type descriptor.</p>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#a35bafd85c5f3303a3dfe173951bc6b9a">addOrderedName</a>, <a href="#a1ead8e73f45a8c9a08f8ae11d89cfecb">addParentName</a>, <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>, <a href="#ab4e80bf7b79d77fda1c18134835ee26d">addTypePrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/group/#ga29be93ac65e487988de0407cc51f6317">llvm::dwarf_linker::parallel::CompileUnit::getDieTypeEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a6201b76e51e8eecfbb57c77fba8367b8">llvm::StringMapEntry&lt; ValueTy &gt;::getKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a>, <a href="/web-llvm/docs/api/groups/group/#gab6d6048b9ba79d8a442e18b7ecc428a6">llvm::dwarf_linker::parallel::CompileUnit::setDieTypeEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a> and <a href="#a64b89caefc9c557f7d6e6b89657a6e04">TypePoolRef</a>.</p>


<p>Referenced by <a href="#a1ead8e73f45a8c9a08f8ae11d89cfecb">addParentName</a>, <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a> and <a href="#ac007678ea81a8e5ab91596fb0825513c">assignName</a>.</p>

</div>
</div>

### addOrderedName() {#a35bafd85c5f3303a3dfe173951bc6b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addOrderedName (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add ordered name to the built name.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>.</p>

</div>
</div>

### addOrderedName() {#abaf0c84320ea66223b29c09fa3740e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SyntheticTypeNameBuilder::addOrderedName (std::pair&lt; size_t, size_t &gt; ChildIdx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add ordered name to the built name.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1e29256284cbb6ab1c31bfcdf7770">llvm::format_hex_no_prefix</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>

</div>
</div>

### addParamNames() {#a461535e36ca5b8a26e8fb2901a23941d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addParamNames (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *, 20 &gt; &amp; FunctionParameters)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add specified <span class="doxyComputerOutput">FunctionParameters</span> to the built name.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a83f43087fac32b05f47dcd3c89fc7bbd">TypeAttr</a>.</p>


<p>Referenced by <a href="#a3fa9676347c5ae75e905430f8e0897ea">addSignature</a>.</p>

</div>
</div>

### addParentName() {#a1ead8e73f45a8c9a08f8ae11d89cfecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addParentName (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> &amp; InputUnitEntryPair)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add names of parent dies to the built name.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#ab55cd7dad28a1cbc0330d57e9613f8fc">llvm::dwarf_linker::parallel::UnitEntryPairTy::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a123fab946df8deba32a875505ddef3d0">getTypeDeduplicationCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>


<p>Referenced by <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>.</p>

</div>
</div>

### addReferencedODRDies() {#a0186dfd0c814155d8e6a9cab1969afdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addReferencedODRDies (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair, bool AssignNameToTypeDescriptor, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> &gt; ODRAttrs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze <span class="doxyComputerOutput">InputUnitEntryPair's</span> ODR attributes and put names of the referenced type dies to the built name.</p>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>, <a href="#a852cdc3d7fa3fb3e04248ee28c78d6cf">RecursionDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afcf78d2889ce6c20ba9de57049ac479fad28670925b341cc0d43e6a0535646d38">llvm::dwarf_linker::parallel::Resolve</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>


<p>Referenced by <a href="#a461535e36ca5b8a26e8fb2901a23941d">addParamNames</a>, <a href="#a3fa9676347c5ae75e905430f8e0897ea">addSignature</a>, <a href="#a086f090ebea74999eafa96dc69047a67">addTemplateParamNames</a> and <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>.</p>

</div>
</div>

### addSignature() {#a3fa9676347c5ae75e905430f8e0897ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addSignature (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair, bool addTemplateParameters)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add signature( entry type plus type of parameters plus type of template parameters(if <span class="doxyComputerOutput">addTemplateParameters</span> is true).</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#a461535e36ca5b8a26e8fb2901a23941d">addParamNames</a>, <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a>, <a href="#a086f090ebea74999eafa96dc69047a67">addTemplateParamNames</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#af1912d641eadda862e32bbb231a13e50">llvm::DWARFDebugInfoEntry::getAbbreviationDeclarationPtr</a>, <a href="/web-llvm/docs/api/groups/helper/#ga122417b360a01a5ac081c1c9b4aa971a">llvm::dwarf_linker::parallel::CompileUnit::getFirstChildEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#ga0b2870f844dabdc24d144e1cd4b95fe0">llvm::dwarf_linker::parallel::CompileUnit::getSiblingEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a83f43087fac32b05f47dcd3c89fc7bbd">TypeAttr</a>.</p>


<p>Referenced by <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>.</p>

</div>
</div>

### addTemplateParamNames() {#a086f090ebea74999eafa96dc69047a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addTemplateParamNames (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; CU, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *, 10 &gt; &amp; TemplateParameters)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add specified <span class="doxyComputerOutput">TemplateParameters</span> to the built name.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp/#a83f43087fac32b05f47dcd3c89fc7bbd">TypeAttr</a>.</p>


<p>Referenced by <a href="#a3fa9676347c5ae75e905430f8e0897ea">addSignature</a>.</p>

</div>
</div>

### addTypeName() {#ae03fdc522b86805416485b83c76a27a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error SyntheticTypeNameBuilder::addTypeName (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair, bool AddParentNames)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add type name to the built name.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="#aea3108f6ef726c8e9b0d244f51230050">addArrayDimension</a>, <a href="#a53c9ecdd82532a2231dca73e685f4ae3">addDieNameFromDeclFileAndDeclLine</a>, <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a>, <a href="#a3fa9676347c5ae75e905430f8e0897ea">addSignature</a>, <a href="#aeee2046e220e7591b37234b1e818f2d6">addValueName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#afbe6a2dc0336fa85db3656856747ce1e">llvm::dwarf_linker::parallel::getODRAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa10731e4d6c303386a70337b0e0668d0">llvm::dwarf::toStringRef</a>.</p>


<p>Referenced by <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>.</p>

</div>
</div>

### addTypePrefix() {#ab4e80bf7b79d77fda1c18134835ee26d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SyntheticTypeNameBuilder::addTypePrefix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * DieEntry)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add type prefix to the built name.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>


<p>Referenced by <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>.</p>

</div>
</div>

### addValueName() {#aeee2046e220e7591b37234b1e818f2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SyntheticTypeNameBuilder::addValueName (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty">UnitEntryPairTy</a> InputUnitEntryPair, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add value name to the built name.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#a52b782888847c9ffd3c67ff187783af0">llvm::dwarf_linker::parallel::UnitEntryPairTy::CU</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/unitentrypairty/#af5c2b2cb0d8ba2bd1233b6482d15f36d">llvm::dwarf_linker::parallel::UnitEntryPairTy::DieEntry</a>, <a href="/web-llvm/docs/api/groups/helper/#gaed7fe8d7d740751efb3cd56d309a63e9">llvm::dwarf_linker::parallel::CompileUnit::find</a> and <a href="#ab60e80384471b338195888b7933df892">SyntheticName</a>.</p>


<p>Referenced by <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### RecursionDepth {#a852cdc3d7fa3fb3e04248ee28c78d6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::RecursionDepth = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursion counter.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a> and <a href="#ac007678ea81a8e5ab91596fb0825513c">assignName</a>.</p>

</div>
</div>

### SyntheticName {#ab60e80384471b338195888b7933df892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;1000&gt; llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::SyntheticName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Buffer keeping bult name.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#aea3108f6ef726c8e9b0d244f51230050">addArrayDimension</a>, <a href="#a53c9ecdd82532a2231dca73e685f4ae3">addDieNameFromDeclFileAndDeclLine</a>, <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a>, <a href="#abaf0c84320ea66223b29c09fa3740e50">addOrderedName</a>, <a href="#a461535e36ca5b8a26e8fb2901a23941d">addParamNames</a>, <a href="#a1ead8e73f45a8c9a08f8ae11d89cfecb">addParentName</a>, <a href="#a0186dfd0c814155d8e6a9cab1969afdd">addReferencedODRDies</a>, <a href="#a3fa9676347c5ae75e905430f8e0897ea">addSignature</a>, <a href="#a086f090ebea74999eafa96dc69047a67">addTemplateParamNames</a>, <a href="#ae03fdc522b86805416485b83c76a27a3">addTypeName</a>, <a href="#ab4e80bf7b79d77fda1c18134835ee26d">addTypePrefix</a>, <a href="#aeee2046e220e7591b37234b1e818f2d6">addValueName</a> and <a href="#ac007678ea81a8e5ab91596fb0825513c">assignName</a>.</p>

</div>
</div>

### TypePoolRef {#a64b89caefc9c557f7d6e6b89657a6e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypePool&amp; llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::TypePoolRef</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> pool.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a>.</p>


<p>Referenced by <a href="#ac0f5b717fb77c6c02c668e29b9764c9e">addDIETypeName</a> and <a href="#ae3ed13db9bc68f498cef6781d0c56f76">SyntheticTypeNameBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-cpp">SyntheticTypeNameBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/synthetictypenamebuilder-h">SyntheticTypeNameBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
