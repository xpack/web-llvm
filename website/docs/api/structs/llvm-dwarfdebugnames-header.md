---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfdebugnames/header
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Header` Struct Reference

<p>DWARF v5 Name Index header. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFDebugNames::Header { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">llvm/DebugInfo/DWARF/DWARFAcceleratorTable.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7831179949c0d3906a51516d928473de">extract</a> (const DWARFDataExtractor &amp;AS, uint64_t *Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b00a739957ebe2f63499174150d91b">dump</a> (ScopedPrinter &amp;W) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386eb1945f5a97d33779c62430859eec">UnitLength</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e876e7ff3c0e13b5b8bad2637bf062">Format</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecee57b22b4c5cf604b69dae140c5846">Version</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c9b621f1bafd2cb39d7f9f902a96f8">CompUnitCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919e99ef44b98508faea84481fdf37f3">LocalTypeUnitCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a0405d96e35fd505605cba8faeb585">ForeignTypeUnitCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacbec570b3b4530d169cde8df7f288e6">BucketCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a229ddf67d87a7ec6f463c8a89d52d5">NameCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ab9c2df56f402ec1476235e9d14c8a">AbbrevTableSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bf7135ab6458a0dedcafab50b25ad7">AugmentationStringSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a836562dbfe39b7bef38e7885981021db">AugmentationString</a></td>
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

<p>DWARF v5 Name Index header.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#ae5b00a739957ebe2f63499174150d91b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugNames::Header::dump (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="#a99ab9c2df56f402ec1476235e9d14c8a">AbbrevTableSize</a>, <a href="#a836562dbfe39b7bef38e7885981021db">AugmentationString</a>, <a href="#aacbec570b3b4530d169cde8df7f288e6">BucketCount</a>, <a href="#a36c9b621f1bafd2cb39d7f9f902a96f8">CompUnitCount</a>, <a href="#af1a0405d96e35fd505605cba8faeb585">ForeignTypeUnitCount</a>, <a href="#a18e876e7ff3c0e13b5b8bad2637bf062">Format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaad973adc80fce80cd7fb76d263240436">llvm::dwarf::FormatString</a>, <a href="#a919e99ef44b98508faea84481fdf37f3">LocalTypeUnitCount</a>, <a href="#a4a229ddf67d87a7ec6f463c8a89d52d5">NameCount</a>, <a href="#a386eb1945f5a97d33779c62430859eec">UnitLength</a> and <a href="#aecee57b22b4c5cf604b69dae140c5846">Version</a>.</p>

</div>
</div>

### extract() {#a7831179949c0d3906a51516d928473de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFDebugNames::Header::extract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; AS, uint64_t * Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>References <a href="#a99ab9c2df56f402ec1476235e9d14c8a">AbbrevTableSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#a836562dbfe39b7bef38e7885981021db">AugmentationString</a>, <a href="#a94bf7135ab6458a0dedcafab50b25ad7">AugmentationStringSize</a>, <a href="#aacbec570b3b4530d169cde8df7f288e6">BucketCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="#a36c9b621f1bafd2cb39d7f9f902a96f8">CompUnitCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#af1a0405d96e35fd505605cba8faeb585">ForeignTypeUnitCount</a>, <a href="#a18e876e7ff3c0e13b5b8bad2637bf062">Format</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a10e13073556511543a885ea96b61ff6c">llvm::DWARFDataExtractor::getInitialLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a0eb55ea3f585f9c8a2619fe7250e56f4">llvm::DataExtractor::getU32</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a45ee696c4102751e0194a0210c07dac0">llvm::DataExtractor::getU8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba53a9e57a679708b2d8ff0ccd8ec96b18">llvm::illegal_byte_sequence</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad7e3a2f9134fa59a38cc0a86acaaf351">llvm::DataExtractor::isValidOffsetForDataOfSize</a>, <a href="#a919e99ef44b98508faea84481fdf37f3">LocalTypeUnitCount</a>, <a href="#a4a229ddf67d87a7ec6f463c8a89d52d5">NameCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#aa4c4043f99a1a5b283741ef4c7cf2464">llvm::DataExtractor::skip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="#a386eb1945f5a97d33779c62430859eec">UnitLength</a> and <a href="#aecee57b22b4c5cf604b69dae140c5846">Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AbbrevTableSize {#a99ab9c2df56f402ec1476235e9d14c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::AbbrevTableSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### AugmentationString {#a836562dbfe39b7bef38e7885981021db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;8&gt; llvm::DWARFDebugNames::Header::AugmentationString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a> and <a href="#a7831179949c0d3906a51516d928473de">extract</a>.</p>

</div>
</div>

### AugmentationStringSize {#a94bf7135ab6458a0dedcafab50b25ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::AugmentationStringSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#a7831179949c0d3906a51516d928473de">extract</a>.</p>

</div>
</div>

### BucketCount {#aacbec570b3b4530d169cde8df7f288e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::BucketCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### CompUnitCount {#a36c9b621f1bafd2cb39d7f9f902a96f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::CompUnitCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### ForeignTypeUnitCount {#af1a0405d96e35fd505605cba8faeb585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::ForeignTypeUnitCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### Format {#a18e876e7ff3c0e13b5b8bad2637bf062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFDebugNames::Header::Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### LocalTypeUnitCount {#a919e99ef44b98508faea84481fdf37f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::LocalTypeUnitCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### NameCount {#a4a229ddf67d87a7ec6f463c8a89d52d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFDebugNames::Header::NameCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a>, <a href="#a7831179949c0d3906a51516d928473de">extract</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a27b19effa141f65cb45374ca33923da4">llvm::dwarf::findDebugNamesOffsets</a>.</p>

</div>
</div>

### UnitLength {#a386eb1945f5a97d33779c62430859eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDebugNames::Header::UnitLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a> and <a href="#a7831179949c0d3906a51516d928473de">extract</a>.</p>

</div>
</div>

### Version {#aecee57b22b4c5cf604b69dae140c5846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DWARFDebugNames::Header::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a>.</p>


<p>Referenced by <a href="#ae5b00a739957ebe2f63499174150d91b">dump</a> and <a href="#a7831179949c0d3906a51516d928473de">extract</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">DWARFAcceleratorTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
