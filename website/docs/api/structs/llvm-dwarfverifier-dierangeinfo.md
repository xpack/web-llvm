---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfverifier/dierangeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DieRangeInfo` Struct

<p>A class that keeps the address range information for a single <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFVerifier::DieRangeInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">llvm/DebugInfo/DWARF/DWARFVerifier.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfverifier/dierangeinfo">DieRangeInfo</a> &gt;::const_iterator <a href="#a5b96b5528a961c4bdecf19e7e8b1fa29">die_range_info_iterator</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4990e5baeff6d046d7234725258b2f9">DieRangeInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec0bd30140348cbf4f52eb691ac06d5">DieRangeInfo</a> (DWARFDie Die)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c77d39ecd7214fdc50e381d560e1ed">DieRangeInfo</a> (std::vector&lt; DWARFAddressRange &gt; Ranges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for unit testing. <a href="#a97c77d39ecd7214fdc50e381d560e1ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange">DWARFAddressRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02fcde8a02b1b7a549f029f6c845863">insert</a> (const DWARFAddressRange &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts the address range. <a href="#ae02fcde8a02b1b7a549f029f6c845863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5b96b5528a961c4bdecf19e7e8b1fa29">die_range_info_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b02158aa529c25804ce469f24cc8a67">insert</a> (const DieRangeInfo &amp;RI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts the address range info. <a href="#a0b02158aa529c25804ce469f24cc8a67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37112a788bfd9dc3d5877cb34ab14c99">contains</a> (const DieRangeInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if ranges in this object contains all ranges within RHS. <a href="#a37112a788bfd9dc3d5877cb34ab14c99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d87dc2633ddd5ad9d65a824c13807c1">intersects</a> (const DieRangeInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any range in this object intersects with any range in RHS. <a href="#a8d87dc2633ddd5ad9d65a824c13807c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7eb61f0bd13d309602dd7dc7089f298">Die</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange">DWARFAddressRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2adddcfecd26e81efdae3fa8f944cc05">Ranges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sorted DWARFAddressRanges. <a href="#a2adddcfecd26e81efdae3fa8f944cc05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfverifier/dierangeinfo">DieRangeInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7eec92d940f8c6d01b9e775dce59ec7">Children</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sorted DWARFAddressRangeInfo. <a href="#aa7eec92d940f8c6d01b9e775dce59ec7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class that keeps the address range information for a single <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### die\_range\_info\_iterator {#a5b96b5528a961c4bdecf19e7e8b1fa29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::set&lt;DieRangeInfo&gt;::const_iterator llvm::DWARFVerifier::DieRangeInfo::die_range_info_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DieRangeInfo() {#ae4990e5baeff6d046d7234725258b2f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFVerifier::DieRangeInfo::DieRangeInfo ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<p>Referenced by <a href="#a37112a788bfd9dc3d5877cb34ab14c99">contains</a>, <a href="#a0b02158aa529c25804ce469f24cc8a67">insert</a> and <a href="#a8d87dc2633ddd5ad9d65a824c13807c1">intersects</a>.</p>

</div>
</div>

### DieRangeInfo() {#a0ec0bd30140348cbf4f52eb691ac06d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFVerifier::DieRangeInfo::DieRangeInfo (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<p>Reference <a href="#ac7eb61f0bd13d309602dd7dc7089f298">Die</a>.</p>

</div>
</div>

### DieRangeInfo() {#a97c77d39ecd7214fdc50e381d560e1ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFVerifier::DieRangeInfo::DieRangeInfo (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange">DWARFAddressRange</a> &gt; Ranges)</td>
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

<p>Used for unit testing.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a2adddcfecd26e81efdae3fa8f944cc05">Ranges</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#a37112a788bfd9dc3d5877cb34ab14c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::DieRangeInfo::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfverifier/dierangeinfo">DieRangeInfo</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if ranges in this object contains all ranges within RHS.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="#ae4990e5baeff6d046d7234725258b2f9">DieRangeInfo</a> and <a href="#a2adddcfecd26e81efdae3fa8f944cc05">Ranges</a>.</p>

</div>
</div>

### insert() {#ae02fcde8a02b1b7a549f029f6c845863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFAddressRange &gt; DWARFVerifier::DieRangeInfo::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange">DWARFAddressRange</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts the address range.</p>


<p>If the range overlaps with an existing range, the range that it overlaps with will be returned and the two address ranges will be unioned together in "Ranges". If a duplicate entry is attempted to be added, the duplicate range will not actually be added and the returned iterator will point to end().</p>


<p>This is used for finding overlapping ranges in the DW_AT_ranges attribute of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. It is also used as a set of address ranges that children address ranges must all be contained in.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a2adddcfecd26e81efdae3fa8f944cc05">Ranges</a>.</p>

</div>
</div>

### insert() {#a0b02158aa529c25804ce469f24cc8a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFVerifier::DieRangeInfo::die_range_info_iterator DWARFVerifier::DieRangeInfo::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfverifier/dierangeinfo">DieRangeInfo</a> &amp; RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts the address range info.</p>


<p>If any of its ranges overlaps with a range in an existing range info, the range info is <em>not</em> added and an iterator to the overlapping range info. If a duplicate entry is attempted to be added, the duplicate range will not actually be added and the returned iterator will point to end().</p>


<p>This is used for finding overlapping children of the same <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="#aa7eec92d940f8c6d01b9e775dce59ec7">Children</a>, <a href="#ae4990e5baeff6d046d7234725258b2f9">DieRangeInfo</a> and <a href="#a2adddcfecd26e81efdae3fa8f944cc05">Ranges</a>.</p>

</div>
</div>

### intersects() {#a8d87dc2633ddd5ad9d65a824c13807c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFVerifier::DieRangeInfo::intersects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfverifier/dierangeinfo">DieRangeInfo</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if any range in this object intersects with any range in RHS.</p>


<p>Identical ranges are not considered to be intersecting.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a>.</p>


<p>References <a href="#ae4990e5baeff6d046d7234725258b2f9">DieRangeInfo</a> and <a href="#a2adddcfecd26e81efdae3fa8f944cc05">Ranges</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Children {#aa7eec92d940f8c6d01b9e775dce59ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;DieRangeInfo&gt; llvm::DWARFVerifier::DieRangeInfo::Children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sorted DWARFAddressRangeInfo.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<p>Referenced by <a href="#a0b02158aa529c25804ce469f24cc8a67">insert</a>.</p>

</div>
</div>

### Die {#ac7eb61f0bd13d309602dd7dc7089f298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::DWARFVerifier::DieRangeInfo::Die</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<p>Referenced by <a href="#a0ec0bd30140348cbf4f52eb691ac06d5">DieRangeInfo</a>.</p>

</div>
</div>

### Ranges {#a2adddcfecd26e81efdae3fa8f944cc05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DWARFAddressRange&gt; llvm::DWARFVerifier::DieRangeInfo::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sorted DWARFAddressRanges.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a>.</p>


<p>Referenced by <a href="#a37112a788bfd9dc3d5877cb34ab14c99">contains</a>, <a href="#a97c77d39ecd7214fdc50e381d560e1ed">DieRangeInfo</a>, <a href="#a0b02158aa529c25804ce469f24cc8a67">insert</a>, <a href="#ae02fcde8a02b1b7a549f029f6c845863">insert</a> and <a href="#a8d87dc2633ddd5ad9d65a824c13807c1">intersects</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfverifier-h">DWARFVerifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp">DWARFVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
