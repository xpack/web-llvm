---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarflocationtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFLocationTable` Class Reference

<p>An abstract base class for various kinds of location tables (.debug_loc, .debug_loclists, and their dwo variants). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFLocationTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">llvm/DebugInfo/DWARF/DWARFDebugLoc.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc">DWARFDebugLoc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists">DWARFDebugLoclists</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9780871a76560efb258150301d9a7549">DWARFLocationTable</a> (DWARFDataExtractor Data)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af436723635d312a1fb9e9f7b718af357">~DWARFLocationTable</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23c0a6b21464e995ec595578c63ffcb">visitLocationList</a> (uint64_t *Offset, function_ref&lt; bool(const DWARFLocationEntry &amp;)&gt; Callback) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call the user-provided callback for each entry (including the end-of-list entry) in the location list starting at <span class="doxyComputerOutput">Offset</span>. <a href="#ab23c0a6b21464e995ec595578c63ffcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9a11e9a2e87414bb67f6aaa342a570">dumpLocationList</a> (uint64_t *Offset, raw_ostream &amp;OS, std::optional&lt; object::SectionedAddress &gt; BaseAddr, const DWARFObject &amp;Obj, DWARFUnit *U, DIDumpOptions DumpOpts, unsigned Indent) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the location list at the given <span class="doxyComputerOutput">Offset</span>. <a href="#aec9a11e9a2e87414bb67f6aaa342a570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc05bf27e333c6e86262cbe80d95914f">visitAbsoluteLocationList</a> (uint64_t Offset, std::optional&lt; object::SectionedAddress &gt; BaseAddr, std::function&lt; std::optional&lt; object::SectionedAddress &gt;(uint32_t)&gt; LookupAddr, function_ref&lt; bool(Expected&lt; DWARFLocationExpression &gt;)&gt; Callback) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37b7a2374eed912ceb4a6788f177dc4">getData</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab79aa595ca0798d15a9a143a7f342f">dumpRawEntry</a> (const DWARFLocationEntry &amp;Entry, raw_ostream &amp;OS, unsigned Indent, DIDumpOptions DumpOpts, const DWARFObject &amp;Obj) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ade406c1a304117d5a9ee408cff71f">Data</a></td>
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

<p>An abstract base class for various kinds of location tables (.debug_loc, .debug_loclists, and their dwo variants).</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFLocationTable() {#a9780871a76560efb258150301d9a7549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFLocationTable::DWARFLocationTable (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>


<p>References <a href="#aa4ade406c1a304117d5a9ee408cff71f">Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#ae58153e86839c2ede37ca6ce18918a11">llvm::DWARFDebugLoc::DWARFDebugLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#a4193dd44d06918bb67662d352bfaa4b2">llvm::DWARFDebugLoclists::DWARFDebugLoclists</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DWARFLocationTable() {#af436723635d312a1fb9e9f7b718af357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::DWARFLocationTable::~DWARFLocationTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpLocationList() {#aec9a11e9a2e87414bb67f6aaa342a570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFLocationTable::dumpLocationList (uint64_t * Offset, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt; BaseAddr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, unsigned Indent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the location list at the given <span class="doxyComputerOutput">Offset</span>.</p>


<p>The function returns true iff it has successfully reched the end of the list. This means that one can attempt to parse another list after the current one (<span class="doxyComputerOutput">Offset</span> will be updated to point past the end of the current list).</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugloc-cpp">DWARFDebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#aa4ade406c1a304117d5a9ee408cff71f">Data</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#af989f60200414119fe05ca13a394ca61">llvm::DIDumpOptions::DisplayRawContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugloc-cpp/#ad9ab58d9df7ebf68297048b5c82143de">dumpExpression</a>, <a href="#a2ab79aa595ca0798d15a9a143a7f342f">dumpRawEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a37d04f96a64f8d44fb59b8ca1ab8935b">llvm::DIDumpOptions::RecoverableErrorHandler</a> and <a href="#ab23c0a6b21464e995ec595578c63ffcb">visitLocationList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#aaefcf5fb948c6d0eaba576c6919871b9">llvm::DWARFDebugLoc::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#a2717a5a96c54f051a1fe6ec28dd7aad7">llvm::DWARFDebugLoclists::dumpRange</a>.</p>

</div>
</div>

### getData() {#af37b7a2374eed912ceb4a6788f177dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDataExtractor &amp; llvm::DWARFLocationTable::getData ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>


<p>Reference <a href="#aa4ade406c1a304117d5a9ee408cff71f">Data</a>.</p>

</div>
</div>

### visitAbsoluteLocationList() {#acc05bf27e333c6e86262cbe80d95914f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLocationTable::visitAbsoluteLocationList (uint64_t Offset, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt; BaseAddr, std::function&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;(uint32_t)&gt; LookupAddr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarflocationexpression">DWARFLocationExpression</a> &gt;)&gt; Callback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugloc-cpp">DWARFDebugLoc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#ab23c0a6b21464e995ec595578c63ffcb">visitLocationList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab8397ea715fe1132418fcad480386db">llvm::DWARFUnit::findLoclistFromOffset</a>.</p>

</div>
</div>

### visitLocationList() {#ab23c0a6b21464e995ec595578c63ffcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::DWARFLocationTable::visitLocationList (uint64_t * Offset, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarflocationentry">DWARFLocationEntry</a> &amp;)&gt; Callback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call the user-provided callback for each entry (including the end-of-list entry) in the location list starting at <span class="doxyComputerOutput">Offset</span>.</p>


<p>The callback can return false to terminate the iteration early. Returns an error if it was unable to parse the entire location list correctly. Upon successful termination <span class="doxyComputerOutput">Offset</span> will be updated point past the end of the list.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#aec9a11e9a2e87414bb67f6aaa342a570">dumpLocationList</a> and <a href="#acc05bf27e333c6e86262cbe80d95914f">visitAbsoluteLocationList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### dumpRawEntry() {#a2ab79aa595ca0798d15a9a143a7f342f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DWARFLocationTable::dumpRawEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarflocationentry">DWARFLocationEntry</a> &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Indent, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &amp; Obj)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>


<p>Referenced by <a href="#aec9a11e9a2e87414bb67f6aaa342a570">dumpLocationList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Data {#aa4ade406c1a304117d5a9ee408cff71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDataExtractor llvm::DWARFLocationTable::Data</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#aaefcf5fb948c6d0eaba576c6919871b9">llvm::DWARFDebugLoc::dump</a>, <a href="#aec9a11e9a2e87414bb67f6aaa342a570">dumpLocationList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#a2717a5a96c54f051a1fe6ec28dd7aad7">llvm::DWARFDebugLoclists::dumpRange</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#a11cbb190f63755889353aaef746ba05a">llvm::DWARFDebugLoc::dumpRawEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#aaa38af193e8749bb5d9b945b405e933e">llvm::DWARFDebugLoclists::dumpRawEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#ae58153e86839c2ede37ca6ce18918a11">llvm::DWARFDebugLoc::DWARFDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#a4193dd44d06918bb67662d352bfaa4b2">llvm::DWARFDebugLoclists::DWARFDebugLoclists</a>, <a href="#a9780871a76560efb258150301d9a7549">DWARFLocationTable</a>, <a href="#af37b7a2374eed912ceb4a6788f177dc4">getData</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#ae386da186965d9d9ce64e0cc1450814d">llvm::DWARFDebugLoc::visitLocationList</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#a58e073f89252bbc940a641902a910eb6">llvm::DWARFDebugLoclists::visitLocationList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugloc-h">DWARFDebugLoc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugloc-cpp">DWARFDebugLoc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
