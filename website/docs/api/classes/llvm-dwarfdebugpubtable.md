---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdebugpubtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFDebugPubTable` Class Reference

<p>Represents structure for holding and parsing .debug_pub* tables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDebugPubTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">llvm/DebugInfo/DWARF/DWARFDebugPubTable.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e3d6be981128bf8e0a6218e92dedb0e">DWARFDebugPubTable</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021fcf81d5e7d4534f0aaf4984381236">extract</a> (DWARFDataExtractor Data, bool GnuStyle, function_ref&lt; void(Error)&gt; RecoverableErrorHandler)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d35cbb8144f97cd0811de3487719084">dump</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set">Set</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad697ecc9f169abe819dae0b2b37c8000">getData</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set">Set</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833f3ff4a5a4714cad8003c110e2ce2a">Sets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70316098ed5dc2b6e0e9b92218038992">GnuStyle</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>gnu styled tables contains additional information. <a href="#a70316098ed5dc2b6e0e9b92218038992">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents structure for holding and parsing .debug_pub* tables.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFDebugPubTable() {#a2e3d6be981128bf8e0a6218e92dedb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDebugPubTable::DWARFDebugPubTable ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a2d35cbb8144f97cd0811de3487719084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugPubTable::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugpubtable-cpp">DWARFDebugPubTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaad973adc80fce80cd7fb76d263240436">llvm::dwarf::FormatString</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf0b82d0ae1946333eaca4330f170180e">llvm::dwarf::GDBIndexEntryKindString</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga2c199ced0c87466d7d8706a8e637c30e">llvm::dwarf::GDBIndexEntryLinkageString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a76facea967f558412cc173c8224fdd9a">dumpPubTableSection</a>.</p>

</div>
</div>

### extract() {#a021fcf81d5e7d4534f0aaf4984381236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugPubTable::extract (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, bool GnuStyle, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugpubtable-cpp">DWARFDebugPubTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set/#a7f839cd510bd2e16a32556f66fbf1036">llvm::DWARFDebugPubTable::Set::Entries</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set/#a6ee0ea66e66bfbc0aaa48ae4f408638b">llvm::DWARFDebugPubTable::Set::Format</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a3b587fe584a4e8b02c4ca0426be42918">llvm::DataExtractor::getCStrRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a814a7655e692e4f880b38eed143052fb">llvm::DWARFDataExtractor::getRelocatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a45ee696c4102751e0194a0210c07dac0">llvm::DataExtractor::getU8</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a091e3b172c8f532c021b21c90fd3d461">llvm::DataExtractor::getUnsigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set/#a279f88f406170cef2d80d6296a0cdbf8">llvm::DWARFDebugPubTable::Set::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set/#a3b8d425362d21bbb5e355624495ef2a1">llvm::DWARFDebugPubTable::Set::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set/#ad0e76ecb4b6207b979c7d2ecac9d06d5">llvm::DWARFDebugPubTable::Set::Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugpubtable/set/#aef73b42b6bfd81240536c89ec9d9172c">llvm::DWARFDebugPubTable::Set::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a76facea967f558412cc173c8224fdd9a">dumpPubTableSection</a>.</p>

</div>
</div>

### getData() {#ad697ecc9f169abe819dae0b2b37c8000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Set &gt; llvm::DWARFDebugPubTable::getData ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GnuStyle {#a70316098ed5dc2b6e0e9b92218038992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugPubTable::GnuStyle = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>gnu styled tables contains additional information.</p>


<p>This flag determines whether or not section we parse is debug_gnu* table.</p>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>.</p>

</div>
</div>

### Sets {#a833f3ff4a5a4714cad8003c110e2ce2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Set&gt; llvm::DWARFDebugPubTable::Sets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugpubtable-h">DWARFDebugPubTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugpubtable-cpp">DWARFDebugPubTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
