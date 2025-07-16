---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdebugnames/entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Entry` Class Reference

<p>DWARF v5-specific implementation of an Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDebugNames::Entry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">llvm/DebugInfo/DWARF/DWARFAcceleratorTable.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/entry">Entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract class representing a single entry in the accelerator tables. <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/entry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dbcbae88ed13238bd675419bf51cad">NameIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af664ab3dc7e92649c0dc7631344894d8">ValueIterator</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4ce25f9f7e27cc6e7589bd30ce8b9d">Entry</a> (const NameIndex &amp;NameIdx, const Abbrev &amp;Abbr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">NameIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e58bb460a5ae0a687b1414928c4859">getNameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a2f93ef6b921fa2841f711434b5f30">getCUOffset</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Offset of the Compilation Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the Compilation Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#a68a2f93ef6b921fa2841f711434b5f30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7e4becda80f2307c86bfb95213dece">getLocalTUOffset</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Offset of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#abc7e4becda80f2307c86bfb95213dece">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c934f51543fe7a9c47772b43ab2f0a">getForeignTUTypeSignature</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type signature of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#a09c934f51543fe7a9c47772b43ab2f0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae423031d453f1608b8de2615f501a961">getTag</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Tag of the Debug Info <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the Tag is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#ae423031d453f1608b8de2615f501a961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed42ffc88b53a8a18018e56d64014aa">getRelatedCUOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168c086b440ac3edbfc53840cae70183">getCUIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Index into the Compilation Unit list of the owning Name Index or std::nullopt if this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> does not have an associated Compilation Unit. <a href="#a168c086b440ac3edbfc53840cae70183">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135d424639be046fd6d58dbaaa831f82">getRelatedCUIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar functionality to <a href="#a168c086b440ac3edbfc53840cae70183">getCUIndex()</a> but without the DW_IDX_type_unit restriction. <a href="#a135d424639be046fd6d58dbaaa831f82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabddaaf3a1568deb8177b99810ee0054">getTUIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit of the owning Name Index or std::nullopt if this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> does not have an associated <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit. <a href="#aabddaaf3a1568deb8177b99810ee0054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6719d23b30167cc8521b886be4f028">tag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>.debug_names-specific getter, which always succeeds (DWARF v5 index entries always have a tag). <a href="#a9f6719d23b30167cc8521b886be4f028">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d9def68ebcbb770eb26c987b5e0548">getDIEUnitOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Offset of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> within the containing <a href="/web-llvm/docs/api/namespaces/cu">CU</a> or TU. <a href="#a68d9def68ebcbb770eb26c987b5e0548">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa52b75e81f83faaff001fdf8f6433144">hasParentInformation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> has information about its parent <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (i.e. <a href="#aa52b75e81f83faaff001fdf8f6433144">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">DWARFDebugNames::Entry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bdb3e65ba30c7b30437f48960cc9dc6">getParentDIEEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> corresponding to the parent of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represented by <span class="doxyComputerOutput">this</span> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#a7bdb3e65ba30c7b30437f48960cc9dc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev">Abbrev</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361c7d20a2d5883c4207f8e5e4c2d8f8">getAbbrev</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the Abbreviation that can be used to interpret the raw values of this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>. <a href="#a361c7d20a2d5883c4207f8e5e4c2d8f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf26e5048ffe1347a66cf21a0b4b6591">lookup</a> (dwarf::Index Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the Index <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>, if the <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> contains such <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#aaf26e5048ffe1347a66cf21a0b4b6591">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4da819ae2b9c63d1a75e1aabb6be89">dump</a> (ScopedPrinter &amp;W) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb639b3c403a927db9dd576cd989339d">dumpParentIdx</a> (ScopedPrinter &amp;W, const DWARFFormValue &amp;FormValue) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">NameIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8cbeea9f16e12adf8466ae1e977625">NameIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev">Abbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587da5d40df77e411cfc547805d4b131">Abbr</a></td>
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

<p>DWARF v5-specific implementation of an Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>

<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<div class="doxySectionDef">

## Friends

### NameIndex {#a06dbcbae88ed13238bd675419bf51cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">NameIndex</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="#a06dbcbae88ed13238bd675419bf51cad">NameIndex</a>.</p>


<p>Referenced by <a href="#a64e58bb460a5ae0a687b1414928c4859">getNameIndex</a> and <a href="#a06dbcbae88ed13238bd675419bf51cad">NameIndex</a>.</p>

</div>
</div>

### ValueIterator {#af664ab3dc7e92649c0dc7631344894d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/valueiterator">ValueIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="#af664ab3dc7e92649c0dc7631344894d8">ValueIterator</a>.</p>


<p>Referenced by <a href="#af664ab3dc7e92649c0dc7631344894d8">ValueIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Entry() {#ace4ce25f9f7e27cc6e7589bd30ce8b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDebugNames::Entry::Entry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">NameIndex</a> &amp; NameIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev">Abbrev</a> &amp; Abbr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#afa4da819ae2b9c63d1a75e1aabb6be89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugNames::Entry::dump (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeb639b3c403a927db9dd576cd989339d">dumpParentIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/entry/#a5e5e275d47e2269dcb745f6fc3a82bb6">llvm::DWARFAcceleratorTable::Entry::Values</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a740d35e0d3e2f7601f845b641fe58971">llvm::zip_first</a>.</p>

</div>
</div>

### dumpParentIdx() {#aeb639b3c403a927db9dd576cd989339d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugNames::Entry::dumpParentIdx (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FormValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#a7bdb3e65ba30c7b30437f48960cc9dc6">getParentDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#aff41df6db83444b2f49193bc1f362fae">llvm::DWARFFormValue::getRawUValue</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#afa4da819ae2b9c63d1a75e1aabb6be89">dump</a>.</p>

</div>
</div>

### getAbbrev() {#a361c7d20a2d5883c4207f8e5e4c2d8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Abbrev &amp; llvm::DWARFDebugNames::Entry::getAbbrev ()</td>
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

<p>Return the Abbreviation that can be used to interpret the raw values of this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### getCUIndex() {#a168c086b440ac3edbfc53840cae70183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getCUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Index into the Compilation Unit list of the owning Name Index or std::nullopt if this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> does not have an associated Compilation Unit.</p>


<p>It is up to the user to verify that the returned Index is valid in the owning <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">NameIndex</a> (or use <a href="#a68a2f93ef6b921fa2841f711434b5f30">getCUOffset()</a>, which will handle that check itself). Note that entries in NameIndexes which index just a single Compilation Unit are implicitly associated with that unit, so this function will return 0 even without an explicit DW_IDX_compile_unit attribute, unless there is a DW_IDX_type_unit attribute.</p>


<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="#a135d424639be046fd6d58dbaaa831f82">getRelatedCUIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>


<p>Referenced by <a href="#a68a2f93ef6b921fa2841f711434b5f30">getCUOffset</a>.</p>

</div>
</div>

### getCUOffset() {#a68a2f93ef6b921fa2841f711434b5f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getCUOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Offset of the Compilation Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the Compilation Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>

<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="#a168c086b440ac3edbfc53840cae70183">getCUIndex</a>.</p>

</div>
</div>

### getDIEUnitOffset() {#a68d9def68ebcbb770eb26c987b5e0548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getDIEUnitOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Offset of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> within the containing <a href="/web-llvm/docs/api/namespaces/cu">CU</a> or TU.</p>

<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### getForeignTUTypeSignature() {#a09c934f51543fe7a9c47772b43ab2f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getForeignTUTypeSignature ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type signature of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="#aabddaaf3a1568deb8177b99810ee0054">getTUIndex</a>.</p>

</div>
</div>

### getLocalTUOffset() {#abc7e4becda80f2307c86bfb95213dece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getLocalTUOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Offset of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="#aabddaaf3a1568deb8177b99810ee0054">getTUIndex</a>.</p>

</div>
</div>

### getNameIndex() {#a64e58bb460a5ae0a687b1414928c4859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NameIndex * llvm::DWARFDebugNames::Entry::getNameIndex ()</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="#a06dbcbae88ed13238bd675419bf51cad">NameIndex</a>.</p>

</div>
</div>

### getParentDIEEntry() {#a7bdb3e65ba30c7b30437f48960cc9dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; DWARFDebugNames::Entry &gt; &gt; DWARFDebugNames::Entry::getParentDIEEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> corresponding to the parent of the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represented by <span class="doxyComputerOutput">this</span> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>


<p>If the parent is not in the table, nullopt is returned. Precondition: <a href="#aa52b75e81f83faaff001fdf8f6433144">hasParentInformation()</a> == true. An error is returned for ill-formed tables.</p>


<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>


<p>Referenced by <a href="#aeb639b3c403a927db9dd576cd989339d">dumpParentIdx</a>.</p>

</div>
</div>

### getRelatedCUIndex() {#a135d424639be046fd6d58dbaaa831f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getRelatedCUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar functionality to <a href="#a168c086b440ac3edbfc53840cae70183">getCUIndex()</a> but without the DW_IDX_type_unit restriction.</p>


<p>This allows us to get the associated a compilation unit index for an entry that is a type unit.</p>


<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>


<p>Referenced by <a href="#a168c086b440ac3edbfc53840cae70183">getCUIndex</a> and <a href="#a1ed42ffc88b53a8a18018e56d64014aa">getRelatedCUOffset</a>.</p>

</div>
</div>

### getRelatedCUOffset() {#a1ed42ffc88b53a8a18018e56d64014aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getRelatedCUOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="#a135d424639be046fd6d58dbaaa831f82">getRelatedCUIndex</a>.</p>

</div>
</div>

### getTag() {#ae423031d453f1608b8de2615f501a961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; dwarf::Tag &gt; llvm::DWARFDebugNames::Entry::getTag ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Tag of the Debug Info <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> or std::nullopt if the Tag is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>.</p>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="#a9f6719d23b30167cc8521b886be4f028">tag</a>.</p>

</div>
</div>

### getTUIndex() {#aabddaaf3a1568deb8177b99810ee0054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDebugNames::Entry::getTUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit of the owning Name Index or std::nullopt if this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> does not have an associated <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit.</p>


<p>It is up to the user to verify that the returned Index is a valid index in the owning <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex">NameIndex</a> (or use <a href="#abc7e4becda80f2307c86bfb95213dece">getLocalTUOffset()</a>, which will handle that check itself).</p>


<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>


<p>Referenced by <a href="#a09c934f51543fe7a9c47772b43ab2f0a">getForeignTUTypeSignature</a> and <a href="#abc7e4becda80f2307c86bfb95213dece">getLocalTUOffset</a>.</p>

</div>
</div>

### hasParentInformation() {#aa52b75e81f83faaff001fdf8f6433144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugNames::Entry::hasParentInformation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> has information about its parent <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (i.e.</p>


<p>if it has an IDX_parent attribute)</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### lookup() {#aaf26e5048ffe1347a66cf21a0b4b6591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; DWARFDebugNames::Entry::lookup (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a5d3c920b66ea797d6adb243862fdf47a">dwarf::Index</a> Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the value of the Index <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a>, if the <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry">Entry</a> contains such <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/entry/#a5e5e275d47e2269dcb745f6fc3a82bb6">llvm::DWARFAcceleratorTable::Entry::Values</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a740d35e0d3e2f7601f845b641fe58971">llvm::zip_first</a>.</p>

</div>
</div>

### tag() {#a9f6719d23b30167cc8521b886be4f028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DWARFDebugNames::Entry::tag ()</td>
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

<p>.debug_names-specific getter, which always succeeds (DWARF v5 index entries always have a tag).</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae423031d453f1608b8de2615f501a961">getTag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Abbr {#a587da5d40df77e411cfc547805d4b131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Abbrev* llvm::DWARFDebugNames::Entry::Abbr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

### NameIdx {#a5d8cbeea9f16e12adf8466ae1e977625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NameIndex* llvm::DWARFDebugNames::Entry::NameIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
