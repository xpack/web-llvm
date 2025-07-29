---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfdebugrangelist/rangelistentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RangeListEntry` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFDebugRangeList::RangeListEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">llvm/DebugInfo/DWARF/DWARFDebugRangeList.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf64b9703afd2054b90bc97aa123d1a">isEndOfListEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end of any given range list is marked by an end of list entry, which consists of a 0 for the beginning address offset and a 0 for the ending address offset. <a href="#a8cf64b9703afd2054b90bc97aa123d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab974969801970ba1a8b9b3a0c69f5f5">isBaseAddressSelectionEntry</a> (uint8_t AddressSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base address selection entry consists of: <a href="#aab974969801970ba1a8b9b3a0c69f5f5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa95d135ac835ee0ca83041eccee588e">StartAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A beginning address offset. <a href="#afa95d135ac835ee0ca83041eccee588e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fe00f34df9ba6fbd7f315f74d8cce9">EndAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ending address offset. <a href="#af6fe00f34df9ba6fbd7f315f74d8cce9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f92efb881f3cb191e3cd53720a136a">SectionIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A section index this range belongs to. <a href="#a39f92efb881f3cb191e3cd53720a136a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### isBaseAddressSelectionEntry() {#aab974969801970ba1a8b9b3a0c69f5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugRangeList::RangeListEntry::isBaseAddressSelectionEntry (uint8_t AddressSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A base address selection entry consists of:</p>


<ol class="doxyList" type="1">
<li>The value of the largest representable address offset (for example, 0xffffffff when the size of an address is 32 bits).</li>
<li>An address, which defines the appropriate base address for use in interpreting the beginning and ending address offsets of subsequent entries of the location list.</li>
</ol>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugrangelist-cpp">DWARFDebugRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ad31a7a9cab8288e009f13cfabc5afc13">llvm::dwarf::computeTombstoneAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ae44667c99ac42386fb7f60170a90b011">llvm::DWARFContext::isAddressSizeSupported</a> and <a href="#afa95d135ac835ee0ca83041eccee588e">StartAddress</a>.</p>

</div>
</div>

### isEndOfListEntry() {#a8cf64b9703afd2054b90bc97aa123d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugRangeList::RangeListEntry::isEndOfListEntry ()</td>
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

<p>The end of any given range list is marked by an end of list entry, which consists of a 0 for the beginning address offset and a 0 for the ending address offset.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a>.</p>


<p>References <a href="#af6fe00f34df9ba6fbd7f315f74d8cce9">EndAddress</a> and <a href="#afa95d135ac835ee0ca83041eccee588e">StartAddress</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EndAddress {#af6fe00f34df9ba6fbd7f315f74d8cce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugRangeList::RangeListEntry::EndAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An ending address offset.</p>


<p>This address offset again has the size of an address and is relative to the applicable base address of the compilation unit referencing this range list. It marks the first address past the end of the address range. The ending address must be greater than or equal to the beginning address.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a>.</p>


<p>Referenced by <a href="#a8cf64b9703afd2054b90bc97aa123d1a">isEndOfListEntry</a>.</p>

</div>
</div>

### SectionIndex {#a39f92efb881f3cb191e3cd53720a136a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugRangeList::RangeListEntry::SectionIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A section index this range belongs to.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a>.</p>

</div>
</div>

### StartAddress {#afa95d135ac835ee0ca83041eccee588e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugRangeList::RangeListEntry::StartAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A beginning address offset.</p>


<p>This address offset has the size of an address and is relative to the applicable base address of the compilation unit referencing this range list. It marks the beginning of an address range.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a>.</p>


<p>Referenced by <a href="#aab974969801970ba1a8b9b3a0c69f5f5">isBaseAddressSelectionEntry</a> and <a href="#a8cf64b9703afd2054b90bc97aa123d1a">isEndOfListEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugrangelist-h">DWARFDebugRangeList.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugrangelist-cpp">DWARFDebugRangeList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
