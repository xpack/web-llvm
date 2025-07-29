---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-varlocbasedimpl-cpp-/locindex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LocIndex` Struct

<p>A type-checked pair of {<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Location (or 0), Index}, used to index into a VarLocMap. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{VarLocBasedImpl.cpp}::LocIndex { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a> = uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a205da6b22835211e90e5d272b5828f7e">u32_index_t</a> = uint32_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f32cae2afc1a537be042b64456144ba">LocIndex</a> (u32_location_t Location, u32_index_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4dd6277cae0ce1b90eb92909b32dab">getAsRawInteger</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6201c0d946bf02470a62e8261a45c6e">Location</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a205da6b22835211e90e5d272b5828f7e">u32_index_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174f5ca13ad248fcb86b088b86220982">Index</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/locindex">LocIndex</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb8b425a0d6b74df7d199a3f05531f31">fromRawInteger</a> (IntT ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80b59059707bdae1d97681e54fd15a3">rawIndexForReg</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the start of the interval reserved for VarLocs of kind RegisterKind which reside in <span class="doxyComputerOutput">Reg</span>. <a href="#ad80b59059707bdae1d97681e54fd15a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a1f9850308b06b4b75f13c4aa73e1e">indexRangeForLocation</a> (const VarLocSet &amp;Set, u32_location_t Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a range covering all set indices in the interval reserved for <span class="doxyComputerOutput">Location</span> in <span class="doxyComputerOutput">Set</span>. <a href="#aa9a1f9850308b06b4b75f13c4aa73e1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452ecdd12ada38942f5d7f8f78be68ea">kUniversalLocation</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The location that has an entry for every VarLoc in the map. <a href="#a452ecdd12ada38942f5d7f8f78be68ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315ef69152182bdf0bcbf482bc88c134">kFirstRegLocation</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The first location that is reserved for VarLocs with locations of kind RegisterKind. <a href="#a315ef69152182bdf0bcbf482bc88c134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70984ef80fa789ace4137d857bde4b01">kFirstInvalidRegLocation</a> = 1 &lt;&lt; 30</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The first location greater than 0 that is not reserved for VarLocs with locations of kind RegisterKind. <a href="#a70984ef80fa789ace4137d857bde4b01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d00fe4fdb4f31792051c7823ee9e69d">kSpillLocation</a> = <a href="#a70984ef80fa789ace4137d857bde4b01">kFirstInvalidRegLocation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special location reserved for VarLocs with locations of kind SpillLocKind. <a href="#a6d00fe4fdb4f31792051c7823ee9e69d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedbb2c50993de0e3acf3719ed18e0699">kEntryValueBackupLocation</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special location reserved for VarLocs of kind EntryValueBackupKind and EntryValueCopyBackupKind. <a href="#aedbb2c50993de0e3acf3719ed18e0699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47551c00d230f60aebf052f501304245">kWasmLocation</a> = <a href="#a70984ef80fa789ace4137d857bde4b01">kFirstInvalidRegLocation</a> + 2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special location reserved for VarLocs with locations of kind WasmLocKind. <a href="#a47551c00d230f60aebf052f501304245">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f934c82fdf4c5ea741db19506827895">kFirstVirtualRegLocation</a> = 1 &lt;&lt; 31</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The first location that is reserved for VarLocs with locations of kind VirtualRegisterKind. <a href="#a6f934c82fdf4c5ea741db19506827895">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A type-checked pair of {<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Location (or 0), Index}, used to index into a VarLocMap.</p>


<p>This can be efficiently converted to a 64-bit int for insertion into a <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a>, and efficiently converted back. The type-checker helps ensure that the conversions aren't lossy.</p>


<p>Why encode a location /into/ the VarLocMap index? This makes it possible to find the open VarLocs killed by a register def very quickly. This is a performance-critical operation for <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### u32\_index\_t {#a205da6b22835211e90e5d272b5828f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::LocIndex::u32_index_t =  uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### u32\_location\_t {#a626afd7de7fed611fa6307b8d3f40f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VarLocBasedImpl.cpp}::LocIndex::u32_location_t =  uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LocIndex() {#a8f32cae2afc1a537be042b64456144ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VarLocBasedImpl.cpp}::LocIndex::LocIndex (<a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a> Location, <a href="#a205da6b22835211e90e5d272b5828f7e">u32_index_t</a> Index)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>References <a href="#a174f5ca13ad248fcb86b088b86220982">Index</a> and <a href="#ac6201c0d946bf02470a62e8261a45c6e">Location</a>.</p>


<p>Referenced by <a href="#afb8b425a0d6b74df7d199a3f05531f31">fromRawInteger</a>, <a href="#aa9a1f9850308b06b4b75f13c4aa73e1e">indexRangeForLocation</a> and <a href="#ad80b59059707bdae1d97681e54fd15a3">rawIndexForReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsRawInteger() {#aca4dd6277cae0ce1b90eb92909b32dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{VarLocBasedImpl.cpp}::LocIndex::getAsRawInteger ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>References <a href="#a174f5ca13ad248fcb86b088b86220982">Index</a> and <a href="#ac6201c0d946bf02470a62e8261a45c6e">Location</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Index {#a174f5ca13ad248fcb86b088b86220982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_index_t anonymous{VarLocBasedImpl.cpp}::LocIndex::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aca4dd6277cae0ce1b90eb92909b32dab">getAsRawInteger</a> and <a href="#a8f32cae2afc1a537be042b64456144ba">LocIndex</a>.</p>

</div>
</div>

### Location {#ac6201c0d946bf02470a62e8261a45c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::Location</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aca4dd6277cae0ce1b90eb92909b32dab">getAsRawInteger</a>, <a href="#aa9a1f9850308b06b4b75f13c4aa73e1e">indexRangeForLocation</a> and <a href="#a8f32cae2afc1a537be042b64456144ba">LocIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromRawInteger() {#afb8b425a0d6b74df7d199a3f05531f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIndex anonymous{VarLocBasedImpl.cpp}::LocIndex::fromRawInteger (IntT ID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a8f32cae2afc1a537be042b64456144ba">LocIndex</a>.</p>

</div>
</div>

### indexRangeForLocation() {#aa9a1f9850308b06b4b75f13c4aa73e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{VarLocBasedImpl.cpp}::LocIndex::indexRangeForLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-varlocbasedimpl-cpp-/#a0fcac79d5789c3482f72fdb2eb8d0a32">VarLocSet</a> &amp; Set, <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a> Location)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a range covering all set indices in the interval reserved for <span class="doxyComputerOutput">Location</span> in <span class="doxyComputerOutput">Set</span>.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>References <a href="#ac6201c0d946bf02470a62e8261a45c6e">Location</a> and <a href="#a8f32cae2afc1a537be042b64456144ba">LocIndex</a>.</p>

</div>
</div>

### rawIndexForReg() {#ad80b59059707bdae1d97681e54fd15a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{VarLocBasedImpl.cpp}::LocIndex::rawIndexForReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the start of the interval reserved for VarLocs of kind RegisterKind which reside in <span class="doxyComputerOutput">Reg</span>.</p>


<p>The end is at rawIndexForReg(Reg+1)-1.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<p>Reference <a href="#a8f32cae2afc1a537be042b64456144ba">LocIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### kEntryValueBackupLocation {#aedbb2c50993de0e3acf3719ed18e0699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kEntryValueBackupLocation</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A special location reserved for VarLocs of kind EntryValueBackupKind and EntryValueCopyBackupKind.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="#a70984ef80fa789ace4137d857bde4b01">kFirstInvalidRegLocation</a> + 1
</div>
</dd>
</dl>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### kFirstInvalidRegLocation {#a70984ef80fa789ace4137d857bde4b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kFirstInvalidRegLocation = 1 &lt;&lt; 30</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The first location greater than 0 that is not reserved for VarLocs with locations of kind RegisterKind.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### kFirstRegLocation {#a315ef69152182bdf0bcbf482bc88c134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kFirstRegLocation = 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The first location that is reserved for VarLocs with locations of kind RegisterKind.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### kFirstVirtualRegLocation {#a6f934c82fdf4c5ea741db19506827895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kFirstVirtualRegLocation = 1 &lt;&lt; 31</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The first location that is reserved for VarLocs with locations of kind VirtualRegisterKind.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### kSpillLocation {#a6d00fe4fdb4f31792051c7823ee9e69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kSpillLocation = <a href="#a70984ef80fa789ace4137d857bde4b01">kFirstInvalidRegLocation</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A special location reserved for VarLocs with locations of kind SpillLocKind.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### kUniversalLocation {#a452ecdd12ada38942f5d7f8f78be68ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kUniversalLocation = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The location that has an entry for every VarLoc in the map.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### kWasmLocation {#a47551c00d230f60aebf052f501304245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">u32_location_t anonymous{VarLocBasedImpl.cpp}::LocIndex::kWasmLocation = <a href="#a70984ef80fa789ace4137d857bde4b01">kFirstInvalidRegLocation</a> + 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A special location reserved for VarLocs with locations of kind WasmLocKind.</p>


<p>TODO Placing all Wasm target index locations in this single kWasmLocation may cause slowdown in compilation time in very large functions. Consider giving a each target index/offset pair its own <a href="#a626afd7de7fed611fa6307b8d3f40f6f">u32_location_t</a> if this becomes a problem.</p>


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
