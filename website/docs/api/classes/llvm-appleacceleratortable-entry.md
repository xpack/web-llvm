---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/appleacceleratortable/entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Entry` Class

<p>Apple-specific implementation of an Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AppleAcceleratorTable::Entry { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6912dd22c08109a56b81e76544229535">AppleAcceleratorTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509409330a2f84b6c32b6bee39748238">Entry</a> (const AppleAcceleratorTable &amp;Table)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a86813500814b851f934a1298ef89c">getCUOffset</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Offset of the Compilation Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> or std::nullopt if the Compilation Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>. <a href="#ac1a86813500814b851f934a1298ef89c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c30b96f55985fda53f4448dcb82c59">getDIESectionOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Section Offset of the Debug Info <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> or std::nullopt if the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>. <a href="#a97c30b96f55985fda53f4448dcb82c59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72464ee65b0699a8517a57ad370928d">getTag</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Tag of the Debug Info <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> or std::nullopt if the Tag is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>. <a href="#ab72464ee65b0699a8517a57ad370928d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19075cf428ce749f15c26d3c4ba36f8b">lookup</a> (HeaderData::AtomType Atom) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the Atom in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>, if the <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> contains such Atom. <a href="#a19075cf428ce749f15c26d3c4ba36f8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd4809f48daffefca13b5892aab6a14">extract</a> (uint64_t *Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8bebad60d9f39788d6dba50e7de2353">Table</a></td>
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

<p>Apple-specific implementation of an Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<div class="doxySectionDef">

## Friends

### AppleAcceleratorTable {#a6912dd22c08109a56b81e76544229535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="#a6912dd22c08109a56b81e76544229535">AppleAcceleratorTable</a>.</p>


<p>Referenced by <a href="#a6912dd22c08109a56b81e76544229535">AppleAcceleratorTable</a>.</p>

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
<td class="doxyMemberName">friend class ValueIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Reference <a href="#af664ab3dc7e92649c0dc7631344894d8">ValueIterator</a>.</p>


<p>Referenced by <a href="#af664ab3dc7e92649c0dc7631344894d8">ValueIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Entry() {#a509409330a2f84b6c32b6bee39748238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AppleAcceleratorTable::Entry::Entry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCUOffset() {#ac1a86813500814b851f934a1298ef89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; AppleAcceleratorTable::Entry::getCUOffset ()</td>
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

<p>Returns the Offset of the Compilation Unit associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> or std::nullopt if the Compilation Unit offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>.</p>

<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5dab810df460ae6d1f23f02e1d520334f05">llvm::dwarf::DW_ATOM_cu_offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### getDIESectionOffset() {#a97c30b96f55985fda53f4448dcb82c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; AppleAcceleratorTable::Entry::getDIESectionOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Section Offset of the Debug Info <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> or std::nullopt if the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>.</p>


<p>The returned offset is relative to the start of the Section containing the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da729ef8a54240d5ae532c7261914cae96">llvm::dwarf::DW_ATOM_die_offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### getTag() {#ab72464ee65b0699a8517a57ad370928d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; dwarf::Tag &gt; AppleAcceleratorTable::Entry::getTag ()</td>
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

<p>Returns the Tag of the Debug Info <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> associated with this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> or std::nullopt if the Tag is not recorded in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da297d590afe629760c5523b1a3e907941">llvm::dwarf::DW_ATOM_die_tag</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### lookup() {#a19075cf428ce749f15c26d3c4ba36f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; AppleAcceleratorTable::Entry::lookup (HeaderData::AtomType Atom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the value of the Atom in this Accelerator <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a>, if the <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry">Entry</a> contains such Atom.</p>

<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfacceleratortable/entry/#a5e5e275d47e2269dcb745f6fc3a82bb6">llvm::DWARFAcceleratorTable::Entry::Values</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a19010bf2388f505d1262e23f9f87a813">llvm::zip_equal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### extract() {#a4bd4809f48daffefca13b5892aab6a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AppleAcceleratorTable::Entry::extract (uint64_t * Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Table {#aa8bebad60d9f39788d6dba50e7de2353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable&amp; llvm::AppleAcceleratorTable::Entry::Table</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
