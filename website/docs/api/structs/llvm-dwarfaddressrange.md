---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfaddressrange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DWARFAddressRange` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFAddressRange { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">llvm/DebugInfo/DWARF/DWARFAddressRange.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca05bf4a1e0333334ed845c207eedbb">DWARFAddressRange</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ac3fccbdc0aa51833b044bda302a16">DWARFAddressRange</a> (uint64_t LowPC, uint64_t HighPC, uint64_t SectionIndex=object::SectionedAddress::UndefSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for unit testing. <a href="#ab1ac3fccbdc0aa51833b044bda302a16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e198398f670d31c3ff449b7d71ae281">valid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if LowPC is smaller or equal to HighPC. <a href="#a0e198398f670d31c3ff449b7d71ae281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a> (const DWARFAddressRange &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if [LowPC, HighPC) intersects with [RHS.LowPC, RHS.HighPC). <a href="#a46c7fe36682b4711fa50373a2d1bbee5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771573ea5cd6f54eccf26c50dac5e049">merge</a> (const DWARFAddressRange &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Union two address ranges if they intersect. <a href="#a771573ea5cd6f54eccf26c50dac5e049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81b0ebe03203f548bf8244b75c5a65a">dump</a> (raw_ostream &amp;OS, uint32_t AddressSize, DIDumpOptions DumpOpts={}, const DWARFObject *Obj=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dac28e965794b70aafbf7caa1cb2210">LowPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5b2a58f73b8e5d74eb0605f659e314d">HighPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbe8b253c903452a8058597f1260242">SectionIndex</a></td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFAddressRange() {#a9ca05bf4a1e0333334ed845c207eedbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFAddressRange::DWARFAddressRange ()</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>Referenced by <a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a> and <a href="#a771573ea5cd6f54eccf26c50dac5e049">merge</a>.</p>

</div>
</div>

### DWARFAddressRange() {#ab1ac3fccbdc0aa51833b044bda302a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFAddressRange::DWARFAddressRange (uint64_t LowPC, uint64_t HighPC, uint64_t SectionIndex=<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">object::SectionedAddress::UndefSection</a>)</td>
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

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>References <a href="#aa5b2a58f73b8e5d74eb0605f659e314d">HighPC</a>, <a href="#a1dac28e965794b70aafbf7caa1cb2210">LowPC</a>, <a href="#a6fbe8b253c903452a8058597f1260242">SectionIndex</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#af81b0ebe03203f548bf8244b75c5a65a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFAddressRange::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint32_t AddressSize, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> * Obj=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfaddressrange-cpp">DWARFAddressRange.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#af989f60200414119fe05ca13a394ca61">llvm::DIDumpOptions::DisplayRawContents</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a0373b5360a46d14a991fea39390d7240">llvm::DWARFFormValue::dumpAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a0bdd3a234a4ad4d695aea54ddb2b92bf">llvm::DWARFFormValue::dumpAddressSection</a>, <a href="#aa5b2a58f73b8e5d74eb0605f659e314d">HighPC</a>, <a href="#a1dac28e965794b70aafbf7caa1cb2210">LowPC</a> and <a href="#a6fbe8b253c903452a8058597f1260242">SectionIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rangelistentry/#a9490d0b5d168b24193e600de304103e1">llvm::RangeListEntry::dump</a>.</p>

</div>
</div>

### intersects() {#a46c7fe36682b4711fa50373a2d1bbee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAddressRange::intersects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange">DWARFAddressRange</a> &amp; RHS)</td>
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

<p>Returns true if [LowPC, HighPC) intersects with [RHS.LowPC, RHS.HighPC).</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9ca05bf4a1e0333334ed845c207eedbb">DWARFAddressRange</a>, <a href="#aa5b2a58f73b8e5d74eb0605f659e314d">HighPC</a>, <a href="#a1dac28e965794b70aafbf7caa1cb2210">LowPC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a6fbe8b253c903452a8058597f1260242">SectionIndex</a> and <a href="#a0e198398f670d31c3ff449b7d71ae281">valid</a>.</p>


<p>Referenced by <a href="#a771573ea5cd6f54eccf26c50dac5e049">merge</a>.</p>

</div>
</div>

### merge() {#a771573ea5cd6f54eccf26c50dac5e049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAddressRange::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfaddressrange">DWARFAddressRange</a> &amp; RHS)</td>
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

<p>Union two address ranges if they intersect.</p>


<p>This function will union two address ranges if they intersect by modifying this range to be the union of both ranges. If the two ranges don't intersect this range will be left alone.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RHS</td>
<td class="doxyParamItemDescription"><p>Another address range to combine with.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if the ranges don't intersect, true if they do and the ranges were combined.</p></dd>
</dl>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>References <a href="#a9ca05bf4a1e0333334ed845c207eedbb">DWARFAddressRange</a>, <a href="#aa5b2a58f73b8e5d74eb0605f659e314d">HighPC</a>, <a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a>, <a href="#a1dac28e965794b70aafbf7caa1cb2210">LowPC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### valid() {#a0e198398f670d31c3ff449b7d71ae281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAddressRange::valid ()</td>
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

<p>Returns true if LowPC is smaller or equal to HighPC.</p>


<p>This accounts for dead-stripped ranges.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>References <a href="#aa5b2a58f73b8e5d74eb0605f659e314d">HighPC</a> and <a href="#a1dac28e965794b70aafbf7caa1cb2210">LowPC</a>.</p>


<p>Referenced by <a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### HighPC {#aa5b2a58f73b8e5d74eb0605f659e314d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFAddressRange::HighPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>Referenced by <a href="#af81b0ebe03203f548bf8244b75c5a65a">dump</a>, <a href="#ab1ac3fccbdc0aa51833b044bda302a16">DWARFAddressRange</a>, <a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a>, <a href="#a771573ea5cd6f54eccf26c50dac5e049">merge</a> and <a href="#a0e198398f670d31c3ff449b7d71ae281">valid</a>.</p>

</div>
</div>

### LowPC {#a1dac28e965794b70aafbf7caa1cb2210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFAddressRange::LowPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>Referenced by <a href="#af81b0ebe03203f548bf8244b75c5a65a">dump</a>, <a href="#ab1ac3fccbdc0aa51833b044bda302a16">DWARFAddressRange</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a988c616ede2f0e4cf1c8c4f5faa554c8">llvm::DWARFDebugRangeList::getAbsoluteRanges</a>, <a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a>, <a href="#a771573ea5cd6f54eccf26c50dac5e049">merge</a> and <a href="#a0e198398f670d31c3ff449b7d71ae281">valid</a>.</p>

</div>
</div>

### SectionIndex {#a6fbe8b253c903452a8058597f1260242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFAddressRange::SectionIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a>.</p>


<p>Referenced by <a href="#af81b0ebe03203f548bf8244b75c5a65a">dump</a>, <a href="#ab1ac3fccbdc0aa51833b044bda302a16">DWARFAddressRange</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrnglist/#a08ab890d3a702ced75f774fa2bad2bbc">llvm::DWARFDebugRnglist::getAbsoluteRanges</a> and <a href="#a46c7fe36682b4711fa50373a2d1bbee5">intersects</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfaddressrange-h">DWARFAddressRange.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfaddressrange-cpp">DWARFAddressRange.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
