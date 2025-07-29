---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/codegen/acceltable-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AccelTable.h` File

<p>This file contains support for writing accelerator tables. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlfunctionalextras-h">llvm/ADT/STLFunctionalExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">llvm/CodeGen/DIE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">llvm/CodeGen/DwarfStringPoolEntry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h">llvm/Support/Allocator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/djb-h">llvm/Support/DJB.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include &lt;cstdint&gt;
#include &lt;variant&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltabledata">AccelTableData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface which the different types of accelerator table data have to conform. <a href="/web-llvm/docs/api/classes/llvm/acceltabledata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltablebase">AccelTableBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class holding non-template-dependant functionality of the <a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a> class. <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata">HashData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a group of entries with identical name (and hence, hash value). <a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable&lt;DataT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class holds an abstract representation of an Accelerator Table, consisting of a sequence of buckets, each bucket containint a sequence of <a href="/web-llvm/docs/api/structs/llvm/acceltablebase/hashdata">HashData</a> entries. <a href="/web-llvm/docs/api/classes/llvm/acceltable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltabledata">AppleAccelTableData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for different implementations of Data classes for Apple Accelerator Tables. <a href="/web-llvm/docs/api/classes/llvm/appleacceltabledata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom">Atom</a> defines the form of the data in an Apple accelerator table. <a href="/web-llvm/docs/api/structs/llvm/appleacceltabledata/atom/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/offsetandunitid">OffsetAndUnitID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to identify an entry in <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a> based on their <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset and UnitID. <a href="/web-llvm/docs/api/structs/llvm/offsetandunitid/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cb238644ab8f81d85a6a699debefd09a">DenseMapInfo&lt;OffsetAndUnitID&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltabledata">DWARF5AccelTableData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Data class implementation for DWARF v5 accelerator table. <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltabledata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugnamesabbrev">DebugNamesAbbrev</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/debugnamesabbrev/attributeencoding">AttributeEncoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/typeunitmetainfo">TypeUnitMetaInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf5acceltable/unitindexandencoding">UnitIndexAndEncoding</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata">AppleAccelTableOffsetData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for simple Apple accelerator tables with just a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> reference. <a href="/web-llvm/docs/api/classes/llvm/appleacceltableoffsetdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltabletypedata">AppleAccelTableTypeData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for Apple type accelerator tables. <a href="/web-llvm/docs/api/classes/llvm/appleacceltabletypedata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for simple Apple accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer. <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata">AppleAccelTableStaticTypeData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accelerator table data implementation for type accelerator tables with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset but no actual <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> pointer. <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file contains support for writing accelerator tables.</p>


<p>The DWARF and Apple accelerator tables are an indirect hash table optimized for null lookup rather than access to known data.</p>


<p>The Apple accelerator tables are a precursor of the newer DWARF v5 accelerator tables. Both formats share common design ideas.</p>


<p>The Apple accelerator table are output into an on-disk format that looks like this:</p>


<p>.---------------—.</p>


<table class="doxyTable">
<tr>
<th>HEADER</th>
</tr>
<tr>
<td>BUCKETS</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>HASHES</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>OFFSETS</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>DATA</td>
</tr>
</table>

<p>‘------------------`</p>


<p>The header contains a magic number, version, type of hash function, the number of buckets, total number of hashes, and room for a special struct of data and the length of that struct.</p>


<p>The buckets contain an index (e.g. 6) into the hashes array. The hashes section contains all of the 32-bit hash values in contiguous memory, and the offsets contain the offset into the data area for the particular hash.</p>


<p>For a lookup example, we could hash a function name and take it modulo the number of buckets giving us our bucket. From there we take the bucket value as an index into the hashes table and look at each successive hash as long as the hash value is still the same modulo result (bucket value) as earlier. If we have a match we look at that same entry in the offsets table and grab the offset in the data for our final match.</p>


<p>The DWARF v5 accelerator table consists of zero or more name indices that are output into an on-disk format that looks like this:</p>


<p>.---------------—.</p>


<table class="doxyTable">
<tr>
<th>HEADER</th>
</tr>
<tr>
<td><a href="/web-llvm/docs/api/namespaces/cu">CU</a> LIST</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>LOCAL TU LIST</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>FOREIGN TU LIST</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>HASH TABLE</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>NAME TABLE</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>ABBREV TABLE</td>
</tr>
<tr>
<td>---------------—</td>
</tr>
<tr>
<td>ENTRY POOL</td>
</tr>
</table>

<p>‘------------------`</p>


<p>For the full documentation please refer to the DWARF 5 standard.</p>


<p>This file defines the class template AccelTable, which is represents an abstract view of an Accelerator table, without any notion of an on-disk layout. This class is parameterized by an entry type, which should derive from AccelTableData. This is the type of individual entries in the table, and it should store the data necessary to emit them. AppleAccelTableData is the base class for Apple Accelerator Table entries, which have a uniform structure based on a sequence of Atoms. There are different sub-classes derived from AppleAccelTable, which differ in the set of Atoms and how they obtain their values.</p>


<p>An Apple Accelerator Table can be serialized by calling emitAppleAccelTable function.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
