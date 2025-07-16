---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdebugrnglist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFDebugRnglist` Class Reference

<p>A class representing a single rangelist. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDebugRnglist { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrnglists-h">llvm/DebugInfo/DWARF/DWARFDebugRnglists.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarflisttype">DWARFListType&lt;ListEntryType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for lists of entries that are extracted from a particular section, such as range lists or location lists. <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ab890d3a702ced75f774fa2bad2bbc">getAbsoluteRanges</a> (std::optional&lt; object::SectionedAddress &gt; BaseAddr, uint8_t AddressByteSize, function_ref&lt; std::optional&lt; object::SectionedAddress &gt;(uint32_t)&gt; LookupPooledAddress) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> from a rangelist. <a href="#a08ab890d3a702ced75f774fa2bad2bbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3236ed0add6ff11a6154c252f12f74">getAbsoluteRanges</a> (std::optional&lt; object::SectionedAddress &gt; BaseAddr, DWARFUnit &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> from a rangelist. <a href="#a1f3236ed0add6ff11a6154c252f12f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class representing a single rangelist.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrnglists-h">DWARFDebugRnglists.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getAbsoluteRanges() {#a08ab890d3a702ced75f774fa2bad2bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFAddressRangesVector DWARFDebugRnglist::getAbsoluteRanges (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt; BaseAddr, uint8_t AddressByteSize, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;(uint32_t)&gt; LookupPooledAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> from a rangelist.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrnglists-h">DWARFDebugRnglists.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugrnglists-cpp">DWARFDebugRnglists.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ad31a7a9cab8288e009f13cfabc5afc13">llvm::dwarf::computeTombstoneAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a58762abf82ba4b9f2f46d3b89070d6c1">DenseMapInfo&lt; LocallyHashedType &gt;::Tombstone</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype/#a041f83847fc54b70c309ed67355b1b40">llvm::DWARFListType&lt; RangeListEntry &gt;::Entries</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange/#a6fbe8b253c903452a8058597f1260242">llvm::DWARFAddressRange::SectionIndex</a>.</p>


<p>Referenced by <a href="#a1f3236ed0add6ff11a6154c252f12f74">getAbsoluteRanges</a>.</p>

</div>
</div>

### getAbsoluteRanges() {#a1f3236ed0add6ff11a6154c252f12f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFAddressRangesVector DWARFDebugRnglist::getAbsoluteRanges (std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt; BaseAddr, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> from a rangelist.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrnglists-h">DWARFDebugRnglists.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugrnglists-cpp">DWARFDebugRnglists.cpp</a>.</p>


<p>Reference <a href="#a08ab890d3a702ced75f774fa2bad2bbc">getAbsoluteRanges</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrnglists-h">DWARFDebugRnglists.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugrnglists-cpp">DWARFDebugRnglists.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
