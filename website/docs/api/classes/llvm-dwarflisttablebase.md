---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarflisttablebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFListTableBase` Class Template

<p>A class representing a table of lists as specified in the DWARF v5 standard for location lists and range lists. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DWARFListType&gt;
class llvm::DWARFListTableBase&lt;DWARFListType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">llvm/DebugInfo/DWARF/DWARFListTable.h</a>"
</div>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af0bda9379098fea3e0212217a0b3f6a1">DWARFListTableBase</a> (StringRef SectionName, StringRef HeaderString, StringRef ListTypeString)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a80db363bd273155d8f8b64f0d96b651a">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad9fdda0d62b2d02110b2e21276c80e93">extractHeaderAndOffsets</a> (DWARFDataExtractor Data, uint64_t *OffsetPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the table header and the array of offsets. <a href="#ad9fdda0d62b2d02110b2e21276c80e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae4e640d58b73a1ecf5b3c4a73a476806">extract</a> (DWARFDataExtractor Data, uint64_t *OffsetPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract an entire table, including all list entries. <a href="#ae4e640d58b73a1ecf5b3c4a73a476806">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f56b95c6429c26fbddd56ac096c50ec">findList</a> (DWARFDataExtractor Data, uint64_t Offset) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype">DWARFListType</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up a list based on a given offset. <a href="#a9f56b95c6429c26fbddd56ac096c50ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b55fcbc9c6b60d4b2495fca760e6597">getHeaderOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5cfdb0db959f3a21463fa51baf32f906">getAddrSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5199ed0da07fa39770658d0148c81537">getOffsetEntryCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca6133baf413da74b0e1348b6511a135">getFormat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7bbad7169bd16810cafb23afee1d472">dump</a> (DWARFDataExtractor Data, raw_ostream &amp;OS, llvm::function_ref&lt; std::optional&lt; object::SectionedAddress &gt;(uint32_t)&gt; LookupPooledAddress, DIDumpOptions DumpOpts={}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45916b0462cf81dce88aa936d9949d2a">getOffsetEntry</a> (DataExtractor Data, uint32_t Index) const -&gt; std::optional&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the contents of the offset entry designated by a given index. <a href="#a45916b0462cf81dce88aa936d9949d2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ead43c971432ac7c3cdae12c722fea8">getHeaderSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the table header including the length but not including the offsets. <a href="#a3ead43c971432ac7c3cdae12c722fea8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a65280b7a15281cc167faa570f6dd0b01">length</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader">DWARFListTableHeader</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae2d40d23727e1ad8c86bd7872f6535a">Header</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::map&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype">DWARFListType</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c4455a1a0dd9bb575892b719a8561c7">ListMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping between file offsets and lists. <a href="#a3c4455a1a0dd9bb575892b719a8561c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DWARFListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88b8e0400468c5b3b3939b6076b42eeb">HeaderString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This string is displayed as a heading before the list is dumped (e.g. <a href="#a88b8e0400468c5b3b3939b6076b42eeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class representing a table of lists as specified in the DWARF v5 standard for location lists and range lists.</p>


<p>The table consists of a header followed by an array of offsets into a DWARF section, followed by zero or more list entries. The list entries are kept in a map where the keys are the lists' section offsets.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### DWARFListTableBase() {#af0bda9379098fea3e0212217a0b3f6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFListTableBase&lt; DWARFListType &gt;::DWARFListTableBase (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HeaderString, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ListTypeString)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a80db363bd273155d8f8b64f0d96b651a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFListTableBase&lt; DWARFListType &gt;::clear ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Referenced by <a href="#ae4e640d58b73a1ecf5b3c4a73a476806">llvm::DWARFListTableBase&lt; DWARFListType &gt;::extract</a>.</p>

</div>
</div>

### dump() {#ae7bbad7169bd16810cafb23afee1d472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFListTableBase&lt; DWARFListType &gt;::dump (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;(uint32_t)&gt; LookupPooledAddress, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a5cfdb0db959f3a21463fa51baf32f906">llvm::DWARFListTableBase&lt; DWARFListType &gt;::getAddrSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga01f206798c5c6fc8bf8ee1c8e83e37e4">llvm::dwarf::RangeListEncodingString</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a20d3f5071a5e2993982abaea21820301">dumpRnglistsSection</a>.</p>

</div>
</div>

### extract() {#ae4e640d58b73a1ecf5b3c4a73a476806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DWARFListTableBase&lt; DWARFListType &gt;::extract (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, uint64_t * OffsetPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract an entire table, including all list entries.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a80db363bd273155d8f8b64f0d96b651a">llvm::DWARFListTableBase&lt; DWARFListType &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttype/#a5ce06b7e3524ccb5cde055c3cf596b10">llvm::DWARFListType&lt; ListEntryType &gt;::extract</a>, <a href="#ad9fdda0d62b2d02110b2e21276c80e93">llvm::DWARFListTableBase&lt; DWARFListType &gt;::extractHeaderAndOffsets</a>, <a href="#a5b55fcbc9c6b60d4b2495fca760e6597">llvm::DWARFListTableBase&lt; DWARFListType &gt;::getHeaderOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a20d3f5071a5e2993982abaea21820301">dumpRnglistsSection</a>.</p>

</div>
</div>

### extractHeaderAndOffsets() {#ad9fdda0d62b2d02110b2e21276c80e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DWARFListTableBase&lt; DWARFListType &gt;::extractHeaderAndOffsets (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, uint64_t * OffsetPtr)</td>
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

<p>Extract the table header and the array of offsets.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#ae4e640d58b73a1ecf5b3c4a73a476806">llvm::DWARFListTableBase&lt; DWARFListType &gt;::extract</a>.</p>

</div>
</div>

### findList() {#a9f56b95c6429c26fbddd56ac096c50ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFListType &gt; llvm::DWARFListTableBase&lt; DWARFListType &gt;::findList (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> Data, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up a list based on a given offset.</p>


<p>Extract it and enter it into the list map if necessary.</p>


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a5b55fcbc9c6b60d4b2495fca760e6597">llvm::DWARFListTableBase&lt; DWARFListType &gt;::getHeaderOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aac462c25594ad9731410df38ff635fb7">llvm::DWARFUnit::findRnglistFromOffset</a>.</p>

</div>
</div>

### getAddrSize() {#a5cfdb0db959f3a21463fa51baf32f906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFListTableBase&lt; DWARFListType &gt;::getAddrSize ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Referenced by <a href="#ae7bbad7169bd16810cafb23afee1d472">llvm::DWARFListTableBase&lt; DWARFListType &gt;::dump</a>.</p>

</div>
</div>

### getFormat() {#aca6133baf413da74b0e1348b6511a135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFListTableBase&lt; DWARFListType &gt;::getFormat ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Referenced by <a href="#a3ead43c971432ac7c3cdae12c722fea8">llvm::DWARFListTableBase&lt; DWARFListType &gt;::getHeaderSize</a>.</p>

</div>
</div>

### getHeaderOffset() {#a5b55fcbc9c6b60d4b2495fca760e6597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFListTableBase&lt; DWARFListType &gt;::getHeaderOffset ()</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Referenced by <a href="#ae4e640d58b73a1ecf5b3c4a73a476806">llvm::DWARFListTableBase&lt; DWARFListType &gt;::extract</a> and <a href="#a9f56b95c6429c26fbddd56ac096c50ec">llvm::DWARFListTableBase&lt; DWARFListType &gt;::findList</a>.</p>

</div>
</div>

### getHeaderSize() {#a3ead43c971432ac7c3cdae12c722fea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFListTableBase&lt; DWARFListType &gt;::getHeaderSize ()</td>
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

<p>Return the size of the table header including the length but not including the offsets.</p>


<p>This is dependent on the table format, which is unambiguously derived from parsing the table.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>References <a href="#aca6133baf413da74b0e1348b6511a135">llvm::DWARFListTableBase&lt; DWARFListType &gt;::getFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a1374388723b168fd14a77c5188d4a7db">llvm::DWARFListTableHeader::getHeaderSize</a>.</p>

</div>
</div>

### getOffsetEntry() {#a45916b0462cf81dce88aa936d9949d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFListTableBase&lt; DWARFListType &gt;::getOffsetEntry (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> Data, uint32_t Index)</td>
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

<p>Return the contents of the offset entry designated by a given index.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>

</div>
</div>

### getOffsetEntryCount() {#a5199ed0da07fa39770658d0148c81537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFListTableBase&lt; DWARFListType &gt;::getOffsetEntryCount ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### length() {#a65280b7a15281cc167faa570f6dd0b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFListTableBase&lt; DWARFListType &gt;::length ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a20d3f5071a5e2993982abaea21820301">dumpRnglistsSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Header {#aae2d40d23727e1ad8c86bd7872f6535a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFListTableHeader llvm::DWARFListTableBase&lt; DWARFListType &gt;::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### HeaderString {#a88b8e0400468c5b3b3939b6076b42eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFListTableBase&lt; DWARFListType &gt;::HeaderString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This string is displayed as a heading before the list is dumped (e.g.</p>


<p>"ranges:").</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

### ListMap {#a3c4455a1a0dd9bb575892b719a8561c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DWARFListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, DWARFListType&gt; llvm::DWARFListTableBase&lt; DWARFListType &gt;::ListMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping between file offsets and lists.</p>


<p>It is used to find a particular list based on an offset (obtained from DW_AT_ranges, for example).</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarflisttable-h">DWARFListTable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
