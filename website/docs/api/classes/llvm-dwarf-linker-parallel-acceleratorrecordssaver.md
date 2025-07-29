---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AcceleratorRecordsSaver` Class

<p>This class helps to store information for accelerator entries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::AcceleratorRecordsSaver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">DWARFLinker/Parallel/AcceleratorRecordsSaver.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a> (LinkingGlobalData &amp;GlobalData, CompileUnit &amp;InUnit, CompileUnit *OutUnit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cca92649cf7f496eca2ec162448e403">AcceleratorRecordsSaver</a> (LinkingGlobalData &amp;GlobalData, CompileUnit &amp;InUnit, TypeUnit *OutUnit)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f6165bbc416cec4b36472ffba7c1c81">AcceleratorRecordsSaver</a> (LinkingGlobalData &amp;GlobalData, CompileUnit &amp;InUnit, CompileUnit::OutputUnitVariantPtr OutUnit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a> (const DWARFDebugInfoEntry *InputDieEntry, DIE *OutDIE, AttributesInfo &amp;AttrInfo, TypeEntry *TypeEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save accelerator info for the specified <span class="doxyComputerOutput">OutDIE</span> inside OutUnit. <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37addefa67ac345264fef8f6f477eef8">saveObjC</a> (const DWARFDebugInfoEntry *InputDieEntry, DIE *OutDIE, AttributesInfo &amp;AttrInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae49a5ef1608e2df3b53c880ef1543616">saveNameRecord</a> (StringEntry *Name, DIE *OutDIE, dwarf::Tag Tag, bool AvoidForPubSections)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fdaa3ade4765ff2fc5c85c753c7a41b">saveNamespaceRecord</a> (StringEntry *Name, DIE *OutDIE, dwarf::Tag Tag, TypeEntry *TypeEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb4f618e8ceb12af873c37a5d9c554b">saveObjCNameRecord</a> (StringEntry *Name, DIE *OutDIE, dwarf::Tag Tag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09878fd3b26b9ee9ab928cd3c1922bfe">saveTypeRecord</a> (StringEntry *Name, DIE *OutDIE, dwarf::Tag Tag, uint32_t QualifiedNameHash, bool ObjcClassImplementation, TypeEntry *TypeEntry)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9966b203ddae1beafd7cc1e178eee8dd">GlobalData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global linking data. <a href="#a9966b203ddae1beafd7cc1e178eee8dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b9f313e11ee86970787c0c6c22c057">InUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comiple unit corresponding to input DWARF. <a href="#a07b9f313e11ee86970787c0c6c22c057">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr">CompileUnit::OutputUnitVariantPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compile unit or Artificial type unit corresponding to the output DWARF. <a href="#a6823914b22f163f7589ace91f0e43bd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class helps to store information for accelerator entries.</p>


<p>It prepares accelerator info for the certain <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and store it inside OutUnit.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AcceleratorRecordsSaver() {#a7d5a66c6045eca3d80d4e5f4729a4764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::AcceleratorRecordsSaver (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; InUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> * OutUnit)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<p>References <a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a>, <a href="#a9966b203ddae1beafd7cc1e178eee8dd">GlobalData</a>, <a href="#a07b9f313e11ee86970787c0c6c22c057">InUnit</a> and <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>.</p>


<p>Referenced by <a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a> and <a href="#a8cca92649cf7f496eca2ec162448e403">AcceleratorRecordsSaver</a>.</p>

</div>
</div>

### AcceleratorRecordsSaver() {#a8cca92649cf7f496eca2ec162448e403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::AcceleratorRecordsSaver (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; InUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a> * OutUnit)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<p>References <a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a>, <a href="#a9966b203ddae1beafd7cc1e178eee8dd">GlobalData</a>, <a href="#a07b9f313e11ee86970787c0c6c22c057">InUnit</a> and <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### AcceleratorRecordsSaver() {#a0f6165bbc416cec4b36472ffba7c1c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::AcceleratorRecordsSaver (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> &amp; InUnit, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr">CompileUnit::OutputUnitVariantPtr</a> OutUnit)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<p>References <a href="#a9966b203ddae1beafd7cc1e178eee8dd">GlobalData</a>, <a href="#a07b9f313e11ee86970787c0c6c22c057">InUnit</a> and <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### save() {#aca2d3ebfb1896c7f85f76bcb6dea8b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AcceleratorRecordsSaver::save (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo">AttributesInfo</a> &amp; AttrInfo, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * TypeEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save accelerator info for the specified <span class="doxyComputerOutput">OutDIE</span> inside OutUnit.</p>


<p>Side effects: set attributes in <span class="doxyComputerOutput">AttrInfo</span>.</p>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a6201b76e51e8eecfbb57c77fba8367b8">llvm::StringMapEntry&lt; ValueTy &gt;::getKey</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac0e347575bcc3e0fd9caa27e1edfadef">llvm::DWARFDie::getLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a183b9a712f7e4beb9b21671ce343c960">llvm::DWARFDie::getShortName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a>, <a href="#a9966b203ddae1beafd7cc1e178eee8dd">GlobalData</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp/#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo/#a4daca957e18f277a09ab600d2a6bd4a6">llvm::dwarf_linker::parallel::AttributesInfo::HasLiveAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo/#a272567b11a32fd231a9aae03777b4c22">llvm::dwarf_linker::parallel::AttributesInfo::HasRanges</a>, <a href="#a07b9f313e11ee86970787c0c6c22c057">InUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo/#a12dbe5605f6cd75c38b8bb027f069991">llvm::dwarf_linker::parallel::AttributesInfo::IsDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo/#a81d67be7f49ae415ffdb05ca79ff2f81">llvm::dwarf_linker::parallel::AttributesInfo::MangledName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo/#aa19ec6f95131e2df7b42173aacfb3b61">llvm::dwarf_linker::parallel::AttributesInfo::Name</a>, <a href="#ae49a5ef1608e2df3b53c880ef1543616">saveNameRecord</a>, <a href="#a3fdaa3ade4765ff2fc5c85c753c7a41b">saveNamespaceRecord</a>, <a href="#a37addefa67ac345264fef8f6f477eef8">saveObjC</a>, <a href="#a09878fd3b26b9ee9ab928cd3c1922bfe">saveTypeRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870ad26b007baa81cc3cd38d8d6c93e6df42">llvm::ShortName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89b32c8b0576fa5fcba34f7f8df660b9">llvm::StripTemplateParameters</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### saveNameRecord() {#ae49a5ef1608e2df3b53c880ef1543616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AcceleratorRecordsSaver::saveNameRecord (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag, bool AvoidForPubSections)</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo/#a7c75d487b09af4c72db473d5ef471d97">llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::Type</a>.</p>


<p>Referenced by <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a> and <a href="#a37addefa67ac345264fef8f6f477eef8">saveObjC</a>.</p>

</div>
</div>

### saveNamespaceRecord() {#a3fdaa3ade4765ff2fc5c85c753c7a41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AcceleratorRecordsSaver::saveNamespaceRecord (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * TypeEntry)</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491ab3ba0fe968ce39dcfc6fe8cc0f1b02da">llvm::dwarf_linker::parallel::DwarfUnit::Namespace</a>, <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo/#a7c75d487b09af4c72db473d5ef471d97">llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::Type</a>.</p>


<p>Referenced by <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a>.</p>

</div>
</div>

### saveObjC() {#a37addefa67ac345264fef8f6f477eef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AcceleratorRecordsSaver::saveObjC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * InputDieEntry, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo">AttributesInfo</a> &amp; AttrInfo)</td>
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



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmapentry/#a6201b76e51e8eecfbb57c77fba8367b8">llvm::StringMapEntry&lt; ValueTy &gt;::getKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a53e2261d44de5b8447cfa73b482c647f">llvm::DWARFDebugInfoEntry::getTag</a>, <a href="#a9966b203ddae1beafd7cc1e178eee8dd">GlobalData</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/attributesinfo/#aa19ec6f95131e2df7b42173aacfb3b61">llvm::dwarf_linker::parallel::AttributesInfo::Name</a>, <a href="#ae49a5ef1608e2df3b53c880ef1543616">saveNameRecord</a> and <a href="#a4cb4f618e8ceb12af873c37a5d9c554b">saveObjCNameRecord</a>.</p>


<p>Referenced by <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a>.</p>

</div>
</div>

### saveObjCNameRecord() {#a4cb4f618e8ceb12af873c37a5d9c554b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AcceleratorRecordsSaver::saveObjCNameRecord (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491adebd6b4842117b405ba901644458b32c">llvm::dwarf_linker::parallel::DwarfUnit::ObjC</a>, <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo/#a7c75d487b09af4c72db473d5ef471d97">llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::Type</a>.</p>


<p>Referenced by <a href="#a37addefa67ac345264fef8f6f477eef8">saveObjC</a>.</p>

</div>
</div>

### saveTypeRecord() {#a09878fd3b26b9ee9ab928cd3c1922bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AcceleratorRecordsSaver::saveTypeRecord (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * OutDIE, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag, uint32_t QualifiedNameHash, bool ObjcClassImplementation, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#ae00955922b792a539fb6b19062e0a1af">TypeEntry</a> * TypeEntry)</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="#a6823914b22f163f7589ace91f0e43bd7">OutUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo/#a7c75d487b09af4c72db473d5ef471d97">llvm::dwarf_linker::parallel::DwarfUnit::AccelInfo::Type</a> and <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491aa1fa27779242b4902f7ae3bdd5c6d508">llvm::dwarf_linker::parallel::DwarfUnit::Type</a>.</p>


<p>Referenced by <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### GlobalData {#a9966b203ddae1beafd7cc1e178eee8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingGlobalData&amp; llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::GlobalData</td>
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

<p>Global linking data.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<p>Referenced by <a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a>, <a href="#a0f6165bbc416cec4b36472ffba7c1c81">AcceleratorRecordsSaver</a>, <a href="#a8cca92649cf7f496eca2ec162448e403">AcceleratorRecordsSaver</a>, <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a> and <a href="#a37addefa67ac345264fef8f6f477eef8">saveObjC</a>.</p>

</div>
</div>

### InUnit {#a07b9f313e11ee86970787c0c6c22c057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit&amp; llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::InUnit</td>
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

<p>Comiple unit corresponding to input DWARF.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<p>Referenced by <a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a>, <a href="#a0f6165bbc416cec4b36472ffba7c1c81">AcceleratorRecordsSaver</a>, <a href="#a8cca92649cf7f496eca2ec162448e403">AcceleratorRecordsSaver</a> and <a href="#aca2d3ebfb1896c7f85f76bcb6dea8b81">save</a>.</p>

</div>
</div>

### OutUnit {#a6823914b22f163f7589ace91f0e43bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileUnit::OutputUnitVariantPtr llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::OutUnit</td>
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

<p>Compile unit or Artificial type unit corresponding to the output DWARF.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a>.</p>


<p>Referenced by <a href="#a7d5a66c6045eca3d80d4e5f4729a4764">AcceleratorRecordsSaver</a>, <a href="#a0f6165bbc416cec4b36472ffba7c1c81">AcceleratorRecordsSaver</a>, <a href="#a8cca92649cf7f496eca2ec162448e403">AcceleratorRecordsSaver</a>, <a href="#ae49a5ef1608e2df3b53c880ef1543616">saveNameRecord</a>, <a href="#a3fdaa3ade4765ff2fc5c85c753c7a41b">saveNamespaceRecord</a>, <a href="#a4cb4f618e8ceb12af873c37a5d9c554b">saveObjCNameRecord</a> and <a href="#a09878fd3b26b9ee9ab928cd3c1922bfe">saveTypeRecord</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp">AcceleratorRecordsSaver.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-h">AcceleratorRecordsSaver.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
