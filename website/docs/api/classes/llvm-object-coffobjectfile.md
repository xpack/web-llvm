---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/coffobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `COFFObjectFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::COFFObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">llvm/Object/COFF.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for all object file types. <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f80cb5015c23c8e0c458c21c3f53529">ImportDirectoryEntryRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae318e52271fbb7eb18b6b1e60be13e07">ExportDirectoryEntryRef</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78741e743b354924b8d2347c4aff18ab">COFFObjectFile</a> (MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b6448833640ab0aa371a3a20f3c851">getSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f85cadd55a2d71ca8bef9ef5891d37">getMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace165741d7f0ad2f7c9bd7682801ccb0">getSizeOfOptionalHeader</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5975b4c98d94134e25d2059b966ccea">getCharacteristics</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb1e2fb97d154911ed0d649bf067cea">getTimeDateStamp</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930336b912bc8faffc491775ea12ed59">getNumberOfSections</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed81b2f12360dfbdcb59c7e66c5ec12">getPointerToSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe23745b0c5de82e1d86516675fa435">getRawNumberOfSymbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6613c0638d74614238d7181c14110c31">getNumberOfSymbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cef7696b2eb83e45eee85ef38418a17">getStringTableSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/export-directory-table-entry">export_directory_table_entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96c8d3f09abcb6b490d3bf7b16283ea">getExportTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-load-configuration32">coff_load_configuration32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22979a367744c6526ecc866594c8593">getLoadConfig32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-load-configuration64">coff_load_configuration64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ead2b00f51d95271f33f90c6b9c9c34">getLoadConfig64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/chpe-metadata">chpe_metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fdc9865494fe0112a039bbec5c7f28c">getCHPEMetadata</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-dynamic-reloc-table">coff_dynamic_reloc_table</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588449b8e24305353101a1de7ca428fd">getDynamicRelocTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5c90a6256f01a33102b39f5b5fe6c0">getRelocationTypeName</a> (uint16_t Type) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995b2c5fbe06dc317b26e03bd3012f22">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8669c4d5032cf05442f9f4373d5795a9">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69eb80f1d4302a2c29668cde1bb00797">section_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae5b3985996bc3c13fd150a47af0330">section_end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1dd634529a874407925bf5117fae7e">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c5fe9889d863b8a8fbe02cbf68f662">getCOFFSection</a> (const SectionRef &amp;Section) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a> (const DataRefImpl &amp;Ref) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208278a65c14652df9a01a2e82cddb9b">getCOFFSymbol</a> (const SymbolRef &amp;Symbol) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-relocation">coff_relocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f61c62b32627fa1844d8d08f28bab35">getCOFFRelocation</a> (const RelocationRef &amp;Reloc) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ab692cb3d70a67aafcb0ab4c22041e">getSectionID</a> (SectionRef Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeefe77eeb81c0dfee4bb876927e90c8">getSymbolSectionID</a> (SymbolRef Sym) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d321c061482817dc5cba6aaa79acb4">getBytesInAddress</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes used to represent an address in this object file format. <a href="#a24d321c061482817dc5cba6aaa79acb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affea093f757641dcfabf57ee00db34b0">getFileFormatName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cdc37ed0342f580539b29515d6e8005">getArch</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b4728027ea64872fcd19415df825d3">getStartAddress</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e039c21ff2ea7ccd59bc097ff227295">getFeatures</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138ae135dded82599e2cd8a1a80cdab4">getHybridObjectView</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a681e9f03a87ec9bfef5a1fdb158580c1">import_directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdb1f24cc3284437fc3a4a3d1eecb66">import_directory_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a681e9f03a87ec9bfef5a1fdb158580c1">import_directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad0f9dae62eb74fb35210f92e7d0ac5">import_directory_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#af5071b960b6588f71c873e80360d764d">delay_import_directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8113f5d826fde607a47452b79e42e9e1">delay_import_directory_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#af5071b960b6588f71c873e80360d764d">delay_import_directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d47a60ce762e8820f211fcf6d965fb">delay_import_directory_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a59556bc42f9f67beacf432996bff67b1">export_directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253fcf3e3e1b79897105bcc713250312">export_directory_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a59556bc42f9f67beacf432996bff67b1">export_directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707556b3672253ecb24bab6b9f3f4ed7">export_directory_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a1b1313b416bffc5cfe9d8302aa9b77e3">base_reloc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28261b2f8af17e7ec3376e883e94a18e">base_reloc_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a1b1313b416bffc5cfe9d8302aa9b77e3">base_reloc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1895827e1066a67fc8cc82bfe9755c">base_reloc_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#ad1a37017b471a53401c4103a2db4964e">dynamic_reloc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a3131d4df46cbc706d146a1602384f">dynamic_reloc_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#ad1a37017b471a53401c4103a2db4964e">dynamic_reloc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac483814504437eff507c6d0cfd746c0f">dynamic_reloc_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory">debug_directory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa303653ce7326595d04be57c65f9bcea">debug_directory_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory">debug_directory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4967678cc731e1604d156274cb798d48">debug_directory_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a681e9f03a87ec9bfef5a1fdb158580c1">import_directory_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fdb950f7cf8cba999dbfe38c0f3c419">import_directories</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#af5071b960b6588f71c873e80360d764d">delay_import_directory_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f7a534db61d7b51dacd6fbdbd4877bd">delay_import_directories</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a59556bc42f9f67beacf432996bff67b1">export_directory_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9014ad271b96309def3cf0728c3be6df">export_directories</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1b1313b416bffc5cfe9d8302aa9b77e3">base_reloc_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa040d8a74d64872779efa69391e9ac8">base_relocs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#ad1a37017b471a53401c4103a2db4964e">dynamic_reloc_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5cd6a2d900de6318b23f9bed4e4c82">dynamic_relocs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory">debug_directory</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f70a8b3656392e9b73b9752f742d5b">debug_directories</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a712e21bd2eee9a034542113dba80986d">coff_tls_directory32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2dc7cfaff8172a96f3a65e6c0943d0">getTLSDirectory32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1acf209f92c7072cb62fe15d4dcb1537">coff_tls_directory64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eff1a33398f7ad979b9b737ce4c3e9a">getTLSDirectory64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/dos-header">dos_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0008623098af6f1fd97b1ff14e46e301">getDOSHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-file-header">coff_file_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a583f0b1295946c138249d35f997f03">getCOFFHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-bigobj-file-header">coff_bigobj_file_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c42b8b5b4e17a6f14f80b5514b5844">getCOFFBigObjHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/pe32-header">pe32_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da56d9cd8f06cd7fc894a0c6960d11c">getPE32Header</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header">pe32plus_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac7f4519e1b18514ac2d9e4f308400d">getPE32PlusHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/data-directory">data_directory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad74ce31d0f3a8c393448ace355fee69">getDataDirectory</a> (uint32_t index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa320001cb948fd09beeb24178f2f8de7">getSection</a> (int32_t index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd95c0b6b6010ace0114e6669c54ab1">getSymbol</a> (uint32_t index) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73121eb9b654794ad353cb23f6f02100">getAuxSymbol</a> (uint32_t index, const T *&amp;Res) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a3431cb32a21b98211acb764b8b32a">getSymbolName</a> (COFFSymbolRef Symbol) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eaf716ba0834134709bc8f6a502384f">getSymbolName</a> (const coff_symbol_generic *Symbol) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d21e61fd2e024f451f6bd4a021523b">getSymbolAuxData</a> (COFFSymbolRef Symbol) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af066e35e9d6a5bfc74d42f9eed6cfd0b">getSymbolIndex</a> (COFFSymbolRef Symbol) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b727390111c3a217035dcb6993b6a6a">getSymbolTableEntrySize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/coff-relocation">coff_relocation</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac89ef015c6338da9a9c460c25b6f3576">getRelocations</a> (const coff_section *Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b450c11951eeed5ec4560ce599ee87">getSectionName</a> (const coff_section *Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f385ce6f800f27716d33de9bacc0729">getSectionSize</a> (const coff_section *Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae94132813b134e3bca64884e6b6b3cd5">getSectionContents</a> (const coff_section *Sec, ArrayRef&lt; uint8_t &gt; &amp;Res) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ecb019a3168e2f3d4cdeaabd3d9b10">getImageBase</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c7b7b61a3806f27ff3e8e77763ad74">getVaPtr</a> (uint64_t VA, uintptr_t &amp;Res) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35aa17b159b4fcc409db6230a7168a2">getRvaPtr</a> (uint32_t Rva, uintptr_t &amp;Res, const char *ErrorContext=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b53a54831e9ad9cb7fe4c06fef03c43">getRvaAndSizeAsBytes</a> (uint32_t RVA, uint32_t Size, ArrayRef&lt; uint8_t &gt; &amp;Contents, const char *ErrorContext=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an RVA base and size, returns a valid array of bytes or an error code if the RVA and size is not contained completely within a valid section. <a href="#a8b53a54831e9ad9cb7fe4c06fef03c43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72ab1cfa75f161aac0286a7fa3e217b6">getHintName</a> (uint32_t Rva, uint16_t &amp;Hint, StringRef &amp;Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae18b7d7be4354e3df59467ddf7d35c63">getDebugPDBInfo</a> (const debug_directory *DebugDir, const codeview::DebugInfo *&amp;Info, StringRef &amp;PDBFileName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get PDB information out of a codeview debug directory entry. <a href="#ae18b7d7be4354e3df59467ddf7d35c63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ddeb77657c64ca7b6fa88ee659e76f">getDebugPDBInfo</a> (const codeview::DebugInfo *&amp;Info, StringRef &amp;PDBFileName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get PDB information from an executable. <a href="#a97ddeb77657c64ca7b6fa88ee659e76f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6cc985503debc981c55ef84d10201b">isRelocatableObject</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a relocatable object (.o/.obj). <a href="#a9e6cc985503debc981c55ef84d10201b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6098994c087673e051050badf6f7c1a1">is64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2d41bd06b5c504e4b62f9f8a3bad25">mapDebugSectionName</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a debug section name to a standard DWARF section name. <a href="#aaf2d41bd06b5c504e4b62f9f8a3bad25">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3568c41169c52a6540fd0fee50e3e327">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5034d2039fd2762121a698d20df45bab">getSymbolName</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ace90d17446bf72452ac5df2d0cfbd">getSymbolAddress</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198eead1f3b968154aa768771921cff8">getSymbolAlignment</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd96a74473063785a1531e8571ed229a">getSymbolValueImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb2d4c0f51994ad276c2d71c80df945">getCommonSymbolSizeImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eca68d4f7435b8b5ddb0d20c10bc690">getSymbolFlags</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69eec3d86ee001dbdc76f0da1f84bb7a">getSymbolType</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2456423e9e3bb5ffdc0a75fa36dd16cf">getSymbolSection</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01901c8d248a3abd4e92835f69362b5">moveSectionNext</a> (DataRefImpl &amp;Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ed4613400d9ee7e1e98b35dabeb845">getSectionName</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a40ad1dec679e8c38a9a1705e63ed6">getSectionAddress</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b3746e61eebbf85376662cd40034c3d">getSectionIndex</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f00c58e0c7e5236121c4bd02fff5d5">getSectionSize</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac11a1d319562846f8aea159bcd6d300">getSectionContents</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec303725814db1282e05d6f1d775fb2">getSectionAlignment</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d91ce764c1bc214c3e20db726bb9f0a">isSectionCompressed</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3abf1f90c004e86372b780b11bca263">isSectionText</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab27e325389f1d03e34557b3a75f98c">isSectionData</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b21593703df58c8a59363f737f0d064">isSectionBSS</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a769fe4d369055ba0768429c0b671c734">isSectionVirtual</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529853b2fbf4b976d4a99b8fa8a2f144">isDebugSection</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a78994887ac9a82a012307b4f7baf27">section_rel_begin</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac105d56f284be37d59dbca7613dcbf88">section_rel_end</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2062e071ceff7f6624a336df1b58b6e8">moveRelocationNext</a> (DataRefImpl &amp;Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d156c093588a5df663502e9ed42032">getRelocationOffset</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd5952e2b3dc1062533d96df0762772">getRelocationSymbol</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c9f0e08ca12fdbe16d6455017b90c7">getRelocationType</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac842bb87a969bf50f9a262be16a40d5b">getRelocationTypeName</a> (DataRefImpl Rel, SmallVectorImpl&lt; char &gt; &amp;Result) const override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e46f51d541bdf28a45d052c7e46b3e">getString</a> (uint32_t offset) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename coff_symbol_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> coff_symbol_type *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a221b5adbb671380b3a4c06c2b7641e">toSymb</a> (DataRefImpl Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a165b1b56ff611d81f04c74e663e9b912">toSec</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-relocation">coff_relocation</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f660bcadbe44632c08c1bce46662e2">toRel</a> (DataRefImpl Rel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf32002a320164d6e9ae0ead4d768e2">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d9c08a75dd3d5a5206768d1494025d">initSymbolTablePtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b4b150f112c8907295022c3bd19684">initImportTablePtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9456a538b3fc68bf50888c10d9bd31">initDelayImportTablePtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2677228140246667b403401b8aeb9b9d">initExportTablePtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae034f885e9f221e7f32def499fe8c8b5">initBaseRelocPtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d230d9d800583620e612e77318ec0c6">initDebugDirectoryPtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c268acca52cc615b304d2b8f32e24d">initTLSDirectoryPtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0c4c49e291475d34ecc5951c32567c">initLoadConfigPtr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d46564d459461d2f1c1c650d15998df">initDynamicRelocPtr</a> (uint32_t SectionIndex, uint32_t SectionOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-file-header">coff_file_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f159f849e98c245c104d652fc0f9555">COFFHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-bigobj-file-header">coff_bigobj_file_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaacc094d1ac6feffc486f5bb1329e1ee">COFFBigObjHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/pe32-header">pe32_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e4b672198f40e1dff2092a7823dd56a">PE32Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/pe32plus-header">pe32plus_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2555ebcea214f204d3aa08cb2eeb071d">PE32PlusHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/data-directory">data_directory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff859342d5ffca6b4d3f426cdf040472">DataDirectory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f937ee38bac2043707e680519e16dd">SectionTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a918bb801731475346a494b06e8f805cb">coff_symbol16</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e089822eb0b6dbcaf41dad3fe35874c">SymbolTable16</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#ac44385f777f6fb07e4cccf738f832ded">coff_symbol32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f98a01f536b2af5223ff8738cab1977">SymbolTable32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f3faa32de158ea71faacad4ed513aa">StringTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181c2a9d2d9bf17509bac3800b256d68">StringTableSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-import-directory-table-entry">coff_import_directory_table_entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f7c77e3208d014135bd6d01655aeec">ImportDirectory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/delay-import-directory-table-entry">delay_import_directory_table_entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b5626efe5d2218f987d51222483fdb">DelayImportDirectory</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49a84274ff2ef2cdf45e8809c1a0358">NumberOfDelayImportDirectory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/export-directory-table-entry">export_directory_table_entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9e6383dc58fdb776c832dcbda767bb">ExportDirectory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-base-reloc-block-header">coff_base_reloc_block_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60537bcd67ffb4fa3cef819b373497de">BaseRelocHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-base-reloc-block-header">coff_base_reloc_block_header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e6e6aa920e09e729f95f3d5a0e2f2c">BaseRelocEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory">debug_directory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d296c4e2edc7c63db667d7369f367a">DebugDirectoryBegin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory">debug_directory</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65efc444b5657266460f7638413d9cd">DebugDirectoryEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a712e21bd2eee9a034542113dba80986d">coff_tls_directory32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73810635e6bb89ae62a8d2df4fdbf04b">TLSDirectory32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1acf209f92c7072cb62fe15d4dcb1537">coff_tls_directory64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6121dfd72d5f6be820b7d7588e59408e">TLSDirectory64</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ffbef823b35e489a2f76e69e3b709b">LoadConfig</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/chpe-metadata">chpe_metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5bf2f83ad900f78833ebf3a95d6fbe">CHPEMetadata</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-dynamic-reloc-table">coff_dynamic_reloc_table</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfc1ccdf4d0ee8651d219e5773e77ee">DynamicRelocTable</a> = nullptr</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">COFFObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ab5f6073614bedfd40289035d5fd2f">create</a> (MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b11f0424c9b665e419865e703d8c976">classof</a> (const Binary *v)</td>
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


<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ExportDirectoryEntryRef {#ae318e52271fbb7eb18b6b1e60be13e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/exportdirectoryentryref">ExportDirectoryEntryRef</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#ae318e52271fbb7eb18b6b1e60be13e07">ExportDirectoryEntryRef</a>.</p>


<p>Referenced by <a href="#a253fcf3e3e1b79897105bcc713250312">export_directory_begin</a>, <a href="#a707556b3672253ecb24bab6b9f3f4ed7">export_directory_end</a> and <a href="#ae318e52271fbb7eb18b6b1e60be13e07">ExportDirectoryEntryRef</a>.</p>

</div>
</div>

### ImportDirectoryEntryRef {#a6f80cb5015c23c8e0c458c21c3f53529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/importdirectoryentryref">ImportDirectoryEntryRef</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a6f80cb5015c23c8e0c458c21c3f53529">ImportDirectoryEntryRef</a>.</p>


<p>Referenced by <a href="#abfdb1f24cc3284437fc3a4a3d1eecb66">import_directory_begin</a>, <a href="#a4ad0f9dae62eb74fb35210f92e7d0ac5">import_directory_end</a> and <a href="#a6f80cb5015c23c8e0c458c21c3f53529">ImportDirectoryEntryRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### COFFObjectFile() {#a78741e743b354924b8d2347c4aff18ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFObjectFile::COFFObjectFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### base\_reloc\_begin() {#a28261b2f8af17e7ec3376e883e94a18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">base_reloc_iterator COFFObjectFile::base_reloc_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#afa040d8a74d64872779efa69391e9ac8">base_relocs</a>.</p>

</div>
</div>

### base\_reloc\_end() {#a5c1895827e1066a67fc8cc82bfe9755c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">base_reloc_iterator COFFObjectFile::base_reloc_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#afa040d8a74d64872779efa69391e9ac8">base_relocs</a>.</p>

</div>
</div>

### base\_relocs() {#afa040d8a74d64872779efa69391e9ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; base_reloc_iterator &gt; COFFObjectFile::base_relocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1168 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a28261b2f8af17e7ec3376e883e94a18e">base_reloc_begin</a>, <a href="#a5c1895827e1066a67fc8cc82bfe9755c">base_reloc_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### debug\_directories() {#a54f70a8b3656392e9b73b9752f742d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const debug_directory * &gt; llvm::object::COFFObjectFile::debug_directories ()</td>
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



<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="#aa303653ce7326595d04be57c65f9bcea">debug_directory_begin</a>, <a href="#a4967678cc731e1604d156274cb798d48">debug_directory_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a97ddeb77657c64ca7b6fa88ee659e76f">getDebugPDBInfo</a>.</p>

</div>
</div>

### debug\_directory\_begin() {#aa303653ce7326595d04be57c65f9bcea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const debug_directory * llvm::object::COFFObjectFile::debug_directory_begin ()</td>
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



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#a54f70a8b3656392e9b73b9752f742d5b">debug_directories</a>.</p>

</div>
</div>

### debug\_directory\_end() {#a4967678cc731e1604d156274cb798d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const debug_directory * llvm::object::COFFObjectFile::debug_directory_end ()</td>
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



<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#a54f70a8b3656392e9b73b9752f742d5b">debug_directories</a>.</p>

</div>
</div>

### delay\_import\_directories() {#a3f7a534db61d7b51dacd6fbdbd4877bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; delay_import_directory_iterator &gt; COFFObjectFile::delay_import_directories ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a8113f5d826fde607a47452b79e42e9e1">delay_import_directory_begin</a>, <a href="#a26d47a60ce762e8820f211fcf6d965fb">delay_import_directory_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### delay\_import\_directory\_begin() {#a8113f5d826fde607a47452b79e42e9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">delay_import_directory_iterator COFFObjectFile::delay_import_directory_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a3f7a534db61d7b51dacd6fbdbd4877bd">delay_import_directories</a>.</p>

</div>
</div>

### delay\_import\_directory\_end() {#a26d47a60ce762e8820f211fcf6d965fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">delay_import_directory_iterator COFFObjectFile::delay_import_directory_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a3f7a534db61d7b51dacd6fbdbd4877bd">delay_import_directories</a>.</p>

</div>
</div>

### dynamic\_reloc\_begin() {#a10a3131d4df46cbc706d146a1602384f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dynamic_reloc_iterator COFFObjectFile::dynamic_reloc_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#ada5cd6a2d900de6318b23f9bed4e4c82">dynamic_relocs</a>.</p>

</div>
</div>

### dynamic\_reloc\_end() {#ac483814504437eff507c6d0cfd746c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dynamic_reloc_iterator COFFObjectFile::dynamic_reloc_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#ada5cd6a2d900de6318b23f9bed4e4c82">dynamic_relocs</a>.</p>

</div>
</div>

### dynamic\_relocs() {#ada5cd6a2d900de6318b23f9bed4e4c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; dynamic_reloc_iterator &gt; COFFObjectFile::dynamic_relocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a10a3131d4df46cbc706d146a1602384f">dynamic_reloc_begin</a>, <a href="#ac483814504437eff507c6d0cfd746c0f">dynamic_reloc_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a138ae135dded82599e2cd8a1a80cdab4">getHybridObjectView</a>.</p>

</div>
</div>

### export\_directories() {#a9014ad271b96309def3cf0728c3be6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; export_directory_iterator &gt; COFFObjectFile::export_directories ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a253fcf3e3e1b79897105bcc713250312">export_directory_begin</a>, <a href="#a707556b3672253ecb24bab6b9f3f4ed7">export_directory_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### export\_directory\_begin() {#a253fcf3e3e1b79897105bcc713250312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">export_directory_iterator COFFObjectFile::export_directory_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1069 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ae318e52271fbb7eb18b6b1e60be13e07">ExportDirectoryEntryRef</a>.</p>


<p>Referenced by <a href="#a9014ad271b96309def3cf0728c3be6df">export_directories</a>.</p>

</div>
</div>

### export\_directory\_end() {#a707556b3672253ecb24bab6b9f3f4ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">export_directory_iterator COFFObjectFile::export_directory_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#ae318e52271fbb7eb18b6b1e60be13e07">ExportDirectoryEntryRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#a9014ad271b96309def3cf0728c3be6df">export_directories</a>.</p>

</div>
</div>

### getArch() {#a9cdc37ed0342f580539b29515d6e8005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType COFFObjectFile::getArch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af5f85cadd55a2d71ca8bef9ef5891d37">getMachine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af80df1b14ea4773659bb2d4c2de4b2">llvm::getMachineArchType</a>.</p>


<p>Referenced by <a href="#a24d321c061482817dc5cba6aaa79acb4">getBytesInAddress</a> and <a href="#a5a5c90a6256f01a33102b39f5b5fe6c0">getRelocationTypeName</a>.</p>

</div>
</div>

### getAuxSymbol() {#a73121eb9b654794ad353cb23f6f02100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::COFFObjectFile::getAuxSymbol (uint32_t index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *&amp; Res)</td>
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



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a2fd95c0b6b6010ace0114e6669c54ab1">getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getBytesInAddress() {#a24d321c061482817dc5cba6aaa79acb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t COFFObjectFile::getBytesInAddress ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes used to represent an address in this object file format.</p>

<p>Declaration at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="#a9cdc37ed0342f580539b29515d6e8005">getArch</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>

</div>
</div>

### getCharacteristics() {#ad5975b4c98d94134e25d2059b966ccea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::COFFObjectFile::getCharacteristics ()</td>
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



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getCHPEMetadata() {#a9fdc9865494fe0112a039bbec5c7f28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const chpe_metadata * llvm::object::COFFObjectFile::getCHPEMetadata ()</td>
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



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getCOFFBigObjHeader() {#a79c42b8b5b4e17a6f14f80b5514b5844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_bigobj_file_header * llvm::object::COFFObjectFile::getCOFFBigObjHeader ()</td>
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



<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getCOFFHeader() {#a6a583f0b1295946c138249d35f997f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_file_header * llvm::object::COFFObjectFile::getCOFFHeader ()</td>
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



<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getCOFFRelocation() {#a4f61c62b32627fa1844d8d08f28bab35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_relocation * COFFObjectFile::getCOFFRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/relocationref">RelocationRef</a> &amp; Reloc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1086 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1367 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>

</div>
</div>

### getCOFFSection() {#ab5c5fe9889d863b8a8fbe02cbf68f662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_section * COFFObjectFile::getCOFFSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1350 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#ae71e8902775f8de0490455dc8c929d2f">llvm::RuntimeDyldCOFFThumb::getJITSymbolFlags</a>, <a href="#a8b53a54831e9ad9cb7fe4c06fef03c43">getRvaAndSizeAsBytes</a>, <a href="#ad35aa17b159b4fcc409db6230a7168a2">getRvaPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitordelegate/#a1a2fd79697f1d47d64f169fa74a24db8">llvm::logicalview::LVSymbolVisitorDelegate::LVSymbolVisitorDelegate</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>.</p>

</div>
</div>

### getCOFFSymbol() {#af7b03104f5d112e6566ae07122a124c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFSymbolRef COFFObjectFile::getCOFFSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="#a208278a65c14652df9a01a2e82cddb9b">getCOFFSymbol</a>, <a href="#a3eb2d4c0f51994ad276c2d71c80df945">getCommonSymbolSizeImpl</a>, <a href="#a62ace90d17446bf72452ac5df2d0cfbd">getSymbolAddress</a>, <a href="#a198eead1f3b968154aa768771921cff8">getSymbolAlignment</a>, <a href="#a9eca68d4f7435b8b5ddb0d20c10bc690">getSymbolFlags</a>, <a href="#a5034d2039fd2762121a698d20df45bab">getSymbolName</a>, <a href="#a2456423e9e3bb5ffdc0a75fa36dd16cf">getSymbolSection</a>, <a href="#adeefe77eeb81c0dfee4bb876927e90c8">getSymbolSectionID</a>, <a href="#a69eec3d86ee001dbdc76f0da1f84bb7a">getSymbolType</a> and <a href="#acd96a74473063785a1531e8571ed229a">getSymbolValueImpl</a>.</p>

</div>
</div>

### getCOFFSymbol() {#a208278a65c14652df9a01a2e82cddb9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFSymbolRef COFFObjectFile::getCOFFSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> &amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getDataDirectory() {#aad74ce31d0f3a8c393448ace355fee69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const data_directory * COFFObjectFile::getDataDirectory (uint32_t index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getDebugPDBInfo() {#ae18b7d7be4354e3df59467ddf7d35c63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getDebugPDBInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory">debug_directory</a> * DebugDir, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/unions/llvm/codeview/debuginfo">codeview::DebugInfo</a> *&amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; PDBFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get PDB information out of a codeview debug directory entry.</p>

<p>Declaration at line 1206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory/#a9a3b7aee32b8303527e5ae7bf00a37c0">llvm::object::debug_directory::AddressOfRawData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="#a8b53a54831e9ad9cb7fe4c06fef03c43">getRvaAndSizeAsBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/object/debug-directory/#a47b1b118e7c33f91f904caeaa7e9c18c">llvm::object::debug_directory::SizeOfData</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a97ddeb77657c64ca7b6fa88ee659e76f">getDebugPDBInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#a6d532e2f19636873f69d5c0d7524dc38">getPdbPathFromExe</a>.</p>

</div>
</div>

### getDebugPDBInfo() {#a97ddeb77657c64ca7b6fa88ee659e76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getDebugPDBInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/unions/llvm/codeview/debuginfo">codeview::DebugInfo</a> *&amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; PDBFileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get PDB information from an executable.</p>


<p>If the information is not present, Info will be set to nullptr and PDBFileName will be empty. An error is returned only on corrupt object files. Convenience accessor that can be used if the debug directory is not already handy.</p>


<p>Declaration at line 1214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a54f70a8b3656392e9b73b9752f742d5b">debug_directories</a>, <a href="#ae18b7d7be4354e3df59467ddf7d35c63">getDebugPDBInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a5630813d9121726fe56fa7120ed7ba85a6f32247c1ba00a49f72c290ca62467e1">llvm::COFF::IMAGE_DEBUG_TYPE_CODEVIEW</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getDOSHeader() {#a0008623098af6f1fd97b1ff14e46e301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const dos_header * llvm::object::COFFObjectFile::getDOSHeader ()</td>
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



<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>.</p>


<p>Referenced by <a href="#a5f385ce6f800f27716d33de9bacc0729">getSectionSize</a>.</p>

</div>
</div>

### getDynamicRelocTable() {#a588449b8e24305353101a1de7ca428fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_dynamic_reloc_table * llvm::object::COFFObjectFile::getDynamicRelocTable ()</td>
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



<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getExportTable() {#af96c8d3f09abcb6b490d3bf7b16283ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const export_directory_table_entry * llvm::object::COFFObjectFile::getExportTable ()</td>
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



<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getFeatures() {#a4e039c21ff2ea7ccd59bc097ff227295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SubtargetFeatures &gt; llvm::object::COFFObjectFile::getFeatures ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getFileFormatName() {#affea093f757641dcfabf57ee00db34b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef COFFObjectFile::getFileFormatName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1121 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af5f85cadd55a2d71ca8bef9ef5891d37">getMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a57211898d4494ccede1f9e90b92ebad4">llvm::COFF::IMAGE_FILE_MACHINE_AMD64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a0a3590d84a3fcf4c0f629a42e9384428">llvm::COFF::IMAGE_FILE_MACHINE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a597eb40b38096e04b0e038af42dfa5a0">llvm::COFF::IMAGE_FILE_MACHINE_ARM64EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ae41778f19526c71645364352b56e06d4">llvm::COFF::IMAGE_FILE_MACHINE_ARM64X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8af90ffbdda9ed6facec414824d70f9de2">llvm::COFF::IMAGE_FILE_MACHINE_ARMNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ab9b603eafcb824ebeb03f246cff0b4d4">llvm::COFF::IMAGE_FILE_MACHINE_I386</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a8ead7683d6849408053cae7a90851c97">llvm::COFF::IMAGE_FILE_MACHINE_R4000</a>.</p>

</div>
</div>

### getHintName() {#a72ab1cfa75f161aac0286a7fa3e217b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getHintName (uint32_t Rva, uint16_t &amp; Hint, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#ad35aa17b159b4fcc409db6230a7168a2">getRvaPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getHybridObjectView() {#a138ae135dded82599e2cd8a1a80cdab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; COFFObjectFile::getHybridObjectView ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1515 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#ada5cd6a2d900de6318b23f9bed4e4c82">dynamic_relocs</a>, <a href="#af5f85cadd55a2d71ca8bef9ef5891d37">getMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a>, <a href="#ad35aa17b159b4fcc409db6230a7168a2">getRvaPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a97f7a51724f930c3fac76ac2fe0f9a97abfb5a448fce0a6a4e553c4a497251f23">llvm::COFF::IMAGE_DVRT_ARM64X_FIXUP_TYPE_DELTA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a97f7a51724f930c3fac76ac2fe0f9a97a88e3d6c9a3a1f2e3a71325f2faf9f4e0">llvm::COFF::IMAGE_DVRT_ARM64X_FIXUP_TYPE_VALUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a97f7a51724f930c3fac76ac2fe0f9a97aecb05b2c90e0b8008c352e9058da97da">llvm::COFF::IMAGE_DVRT_ARM64X_FIXUP_TYPE_ZEROFILL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a345b3a1b6871f21b2ebc3a314cb7c5a5a29324aa9942197c3a4b8a44d6690e96f">llvm::COFF::IMAGE_DYNAMIC_RELOCATION_ARM64X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ae41778f19526c71645364352b56e06d4">llvm::COFF::IMAGE_FILE_MACHINE_ARM64X</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getImageBase() {#ab0ecb019a3168e2f3d4cdeaabd3d9b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getImageBase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a62a40ad1dec679e8c38a9a1705e63ed6">getSectionAddress</a>, <a href="#a62ace90d17446bf72452ac5df2d0cfbd">getSymbolAddress</a>, <a href="#a30c7b7b61a3806f27ff3e8e77763ad74">getVaPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a50b4341d651ea41cb74546557170ebaa">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>.</p>

</div>
</div>

### getLoadConfig32() {#ab22979a367744c6526ecc866594c8593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_load_configuration32 * llvm::object::COFFObjectFile::getLoadConfig32 ()</td>
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



<p>Definition at line 1024 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6098994c087673e051050badf6f7c1a1">is64</a>.</p>

</div>
</div>

### getLoadConfig64() {#a8ead2b00f51d95271f33f90c6b9c9c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_load_configuration64 * llvm::object::COFFObjectFile::getLoadConfig64 ()</td>
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



<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6098994c087673e051050badf6f7c1a1">is64</a>.</p>

</div>
</div>

### getMachine() {#af5f85cadd55a2d71ca8bef9ef5891d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::COFFObjectFile::getMachine ()</td>
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



<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a57211898d4494ccede1f9e90b92ebad4">llvm::COFF::IMAGE_FILE_MACHINE_AMD64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a0a3590d84a3fcf4c0f629a42e9384428">llvm::COFF::IMAGE_FILE_MACHINE_ARM64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a597eb40b38096e04b0e038af42dfa5a0">llvm::COFF::IMAGE_FILE_MACHINE_ARM64EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ae41778f19526c71645364352b56e06d4">llvm::COFF::IMAGE_FILE_MACHINE_ARM64X</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a9cdc37ed0342f580539b29515d6e8005">getArch</a>, <a href="#affea093f757641dcfabf57ee00db34b0">getFileFormatName</a> and <a href="#a138ae135dded82599e2cd8a1a80cdab4">getHybridObjectView</a>.</p>

</div>
</div>

### getNumberOfSections() {#a930336b912bc8faffc491775ea12ed59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::getNumberOfSections ()</td>
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



<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="#aa320001cb948fd09beeb24178f2f8de7">getSection</a> and <a href="#a2ae5b3985996bc3c13fd150a47af0330">section_end</a>.</p>

</div>
</div>

### getNumberOfSymbols() {#a6613c0638d74614238d7181c14110c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::getNumberOfSymbols ()</td>
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



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="#a0fe23745b0c5de82e1d86516675fa435">getRawNumberOfSymbols</a>.</p>


<p>Referenced by <a href="#aebd5952e2b3dc1062533d96df0762772">getRelocationSymbol</a>, <a href="#a2fd95c0b6b6010ace0114e6669c54ab1">getSymbol</a>, <a href="#ab0d21e61fd2e024f451f6bd4a021523b">getSymbolAuxData</a> and <a href="#af066e35e9d6a5bfc74d42f9eed6cfd0b">getSymbolIndex</a>.</p>

</div>
</div>

### getPE32Header() {#a2da56d9cd8f06cd7fc894a0c6960d11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const pe32_header * llvm::object::COFFObjectFile::getPE32Header ()</td>
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



<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getPE32PlusHeader() {#aeac7f4519e1b18514ac2d9e4f308400d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const pe32plus_header * llvm::object::COFFObjectFile::getPE32PlusHeader ()</td>
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



<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getPointerToSymbolTable() {#a4ed81b2f12360dfbdcb59c7e66c5ec12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::getPointerToSymbolTable ()</td>
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



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ab0d21e61fd2e024f451f6bd4a021523b">getSymbolAuxData</a>.</p>

</div>
</div>

### getRawNumberOfSymbols() {#a0fe23745b0c5de82e1d86516675fa435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::getRawNumberOfSymbols ()</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a6613c0638d74614238d7181c14110c31">getNumberOfSymbols</a>.</p>

</div>
</div>

### getRelocations() {#ac89ef015c6338da9a9c460c25b6f3576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; coff_relocation &gt; COFFObjectFile::getRelocations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1372 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a5a4d2bf09a4074476f11647f7ac20126">getFirstReloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a21926dd764fb7f7c891ec7c1ed725991">getNumberOfRelocations</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a5a5c90a6256f01a33102b39f5b5fe6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef COFFObjectFile::getRelocationTypeName (uint16_t Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="#a9cdc37ed0342f580539b29515d6e8005">getArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a3afe6ae6800fe6122bae64def61ea541">LLVM_COFF_SWITCH_RELOC_TYPE_NAME</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#ac842bb87a969bf50f9a262be16a40d5b">getRelocationTypeName</a>.</p>

</div>
</div>

### getRvaAndSizeAsBytes() {#a8b53a54831e9ad9cb7fe4c06fef03c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getRvaAndSizeAsBytes (uint32_t RVA, uint32_t Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Contents, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ErrorContext=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an RVA base and size, returns a valid array of bytes or an error code if the RVA and size is not contained completely within a valid section.</p>

<p>Declaration at line 1198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#ab5c5fe9889d863b8a8fbe02cbf68f662">getCOFFSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ae18b7d7be4354e3df59467ddf7d35c63">getDebugPDBInfo</a>.</p>

</div>
</div>

### getRvaPtr() {#ad35aa17b159b4fcc409db6230a7168a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getRvaPtr (uint32_t Rva, uintptr_t &amp; Res, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ErrorContext=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#ab5c5fe9889d863b8a8fbe02cbf68f662">getCOFFSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a72ab1cfa75f161aac0286a7fa3e217b6">getHintName</a>, <a href="#a138ae135dded82599e2cd8a1a80cdab4">getHybridObjectView</a> and <a href="#a30c7b7b61a3806f27ff3e8e77763ad74">getVaPtr</a>.</p>

</div>
</div>

### getSection() {#aa320001cb948fd09beeb24178f2f8de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const coff_section * &gt; COFFObjectFile::getSection (int32_t index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a930336b912bc8faffc491775ea12ed59">getNumberOfSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad9fb8ab8eb623e9967c0788fc42b150f">llvm::COFF::isReservedSectionNumber</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="#a62ace90d17446bf72452ac5df2d0cfbd">getSymbolAddress</a> and <a href="#a2456423e9e3bb5ffdc0a75fa36dd16cf">getSymbolSection</a>.</p>

</div>
</div>

### getSectionContents() {#ae94132813b134e3bca64884e6b6b3cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getSectionContents (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> * Sec, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#afc55f34d54c38dcea2d603b5dd7c902f">llvm::object::Binary::checkOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#a06f00c58e0c7e5236121c4bd02fff5d5">getSectionSize</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a030e8ad39c3fe9a41a2f1927c5255701">llvm::object::coff_section::PointerToRawData</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getSectionID() {#a76ab692cb3d70a67aafcb0ab4c22041e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned COFFObjectFile::getSectionID (<a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a1f7697438cbf778f7d1b051e97204606">llvm::object::SectionRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>

</div>
</div>

### getSectionName() {#a61b450c11951eeed5ec4560ce599ee87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; COFFObjectFile::getSectionName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#acdd038c2eb1f76887006bd132f57303a">decodeBase64StringEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a1cf355f3912e00f48f6a476ce4889eee">llvm::object::coff_section::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

### getSectionSize() {#a5f385ce6f800f27716d33de9bacc0729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getSectionSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">coff_section</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1282 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a0008623098af6f1fd97b1ff14e46e301">getDOSHeader</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a8882aa2bfacd40fbbd4bac3f492269c6">llvm::object::coff_section::SizeOfRawData</a> and <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a24835b5586d912858a9de0efbf6b8a15">llvm::object::coff_section::VirtualSize</a>.</p>

</div>
</div>

### getSizeOfOptionalHeader() {#ace165741d7f0ad2f7c9bd7682801ccb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::COFFObjectFile::getSizeOfOptionalHeader ()</td>
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



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getStartAddress() {#af9b4728027ea64872fcd19415df825d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; COFFObjectFile::getStartAddress ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### getStringTableSize() {#a9cef7696b2eb83e45eee85ef38418a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::getStringTableSize ()</td>
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



<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getSymbol() {#a2fd95c0b6b6010ace0114e6669c54ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; COFFSymbolRef &gt; llvm::object::COFFObjectFile::getSymbol (uint32_t index)</td>
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



<p>Definition at line 1149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#a6613c0638d74614238d7181c14110c31">getNumberOfSymbols</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>.</p>


<p>Referenced by <a href="#a73121eb9b654794ad353cb23f6f02100">getAuxSymbol</a>.</p>

</div>
</div>

### getSymbolAuxData() {#ab0d21e61fd2e024f451f6bd4a021523b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; COFFObjectFile::getSymbolAuxData (<a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a> Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1228 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="#a6613c0638d74614238d7181c14110c31">getNumberOfSymbols</a>, <a href="#a4ed81b2f12360dfbdcb59c7e66c5ec12">getPointerToSymbolTable</a>, <a href="#a6b727390111c3a217035dcb6993b6a6a">getSymbolTableEntrySize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getSymbolIndex() {#af066e35e9d6a5bfc74d42f9eed6cfd0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t COFFObjectFile::getSymbolIndex (<a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a> Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6613c0638d74614238d7181c14110c31">getNumberOfSymbols</a>, <a href="#a73b6448833640ab0aa371a3a20f3c851">getSymbolTable</a>, <a href="#a6b727390111c3a217035dcb6993b6a6a">getSymbolTableEntrySize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getSymbolName() {#af2a3431cb32a21b98211acb764b8b32a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; COFFObjectFile::getSymbolName (<a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref">COFFSymbolRef</a> Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#a5034d2039fd2762121a698d20df45bab">getSymbolName</a>.</p>

</div>
</div>

### getSymbolName() {#a9eaf716ba0834134709bc8f6a502384f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; COFFObjectFile::getSymbolName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol-generic">coff_symbol_generic</a> * Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a>.</p>

</div>
</div>

### getSymbolSectionID() {#adeefe77eeb81c0dfee4bb876927e90c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned COFFObjectFile::getSymbolSectionID (<a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#ad70cf7d54eb4ea803070fb903b70f44a">llvm::object::COFFSymbolRef::getSectionNumber</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getSymbolTable() {#a73b6448833640ab0aa371a3a20f3c851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::COFFObjectFile::getSymbolTable ()</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#af066e35e9d6a5bfc74d42f9eed6cfd0b">getSymbolIndex</a> and <a href="#a995b2c5fbe06dc317b26e03bd3012f22">symbol_begin</a>.</p>

</div>
</div>

### getSymbolTableEntrySize() {#a6b727390111c3a217035dcb6993b6a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::object::COFFObjectFile::getSymbolTableEntrySize ()</td>
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



<p>Definition at line 1175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ab0d21e61fd2e024f451f6bd4a021523b">getSymbolAuxData</a> and <a href="#af066e35e9d6a5bfc74d42f9eed6cfd0b">getSymbolIndex</a>.</p>

</div>
</div>

### getTimeDateStamp() {#a9bb1e2fb97d154911ed0d649bf067cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::getTimeDateStamp ()</td>
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



<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getTLSDirectory32() {#a4c2dc7cfaff8172a96f3a65e6c0943d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_tls_directory32 * llvm::object::COFFObjectFile::getTLSDirectory32 ()</td>
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



<p>Definition at line 1126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getTLSDirectory64() {#a1eff1a33398f7ad979b9b737ce4c3e9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_tls_directory64 * llvm::object::COFFObjectFile::getTLSDirectory64 ()</td>
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



<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### getVaPtr() {#a30c7b7b61a3806f27ff3e8e77763ad74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::getVaPtr (uint64_t VA, uintptr_t &amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab0ecb019a3168e2f3d4cdeaabd3d9b10">getImageBase</a> and <a href="#ad35aa17b159b4fcc409db6230a7168a2">getRvaPtr</a>.</p>

</div>
</div>

### import\_directories() {#a7fdb950f7cf8cba999dbfe38c0f3c419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; import_directory_iterator &gt; COFFObjectFile::import_directories ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#abfdb1f24cc3284437fc3a4a3d1eecb66">import_directory_begin</a>, <a href="#a4ad0f9dae62eb74fb35210f92e7d0ac5">import_directory_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### import\_directory\_begin() {#abfdb1f24cc3284437fc3a4a3d1eecb66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">import_directory_iterator COFFObjectFile::import_directory_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a4ad0f9dae62eb74fb35210f92e7d0ac5">import_directory_end</a> and <a href="#a6f80cb5015c23c8e0c458c21c3f53529">ImportDirectoryEntryRef</a>.</p>


<p>Referenced by <a href="#a7fdb950f7cf8cba999dbfe38c0f3c419">import_directories</a>.</p>

</div>
</div>

### import\_directory\_end() {#a4ad0f9dae62eb74fb35210f92e7d0ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">import_directory_iterator COFFObjectFile::import_directory_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#a6f80cb5015c23c8e0c458c21c3f53529">ImportDirectoryEntryRef</a>.</p>


<p>Referenced by <a href="#a7fdb950f7cf8cba999dbfe38c0f3c419">import_directories</a> and <a href="#abfdb1f24cc3284437fc3a4a3d1eecb66">import_directory_begin</a>.</p>

</div>
</div>

### is64() {#a6098994c087673e051050badf6f7c1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFObjectFile::is64 ()</td>
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



<p>Definition at line 1218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>


<p>Referenced by <a href="#ab22979a367744c6526ecc866594c8593">getLoadConfig32</a> and <a href="#a8ead2b00f51d95271f33f90c6b9c9c34">getLoadConfig64</a>.</p>

</div>
</div>

### is64Bit() {#aff1dd634529a874407925bf5117fae7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFObjectFile::is64Bit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### isRelocatableObject() {#a9e6cc985503debc981c55ef84d10201b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isRelocatableObject ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this is a relocatable object (.o/.obj).</p>

<p>Declaration at line 1217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### mapDebugSectionName() {#aaf2d41bd06b5c504e4b62f9f8a3bad25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef COFFObjectFile::mapDebugSectionName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a debug section name to a standard DWARF section name.</p>

<p>Declaration at line 1220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1509 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>

</div>
</div>

### section\_begin() {#a69eb80f1d4302a2c29668cde1bb00797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator COFFObjectFile::section_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1082 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>

</div>
</div>

### section\_end() {#a2ae5b3985996bc3c13fd150a47af0330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator COFFObjectFile::section_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a930336b912bc8faffc491775ea12ed59">getNumberOfSections</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#a2456423e9e3bb5ffdc0a75fa36dd16cf">getSymbolSection</a>.</p>

</div>
</div>

### symbol\_begin() {#a995b2c5fbe06dc317b26e03bd3012f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator COFFObjectFile::symbol_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1076 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a73b6448833640ab0aa371a3a20f3c851">getSymbolTable</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### symbol\_end() {#a8669c4d5032cf05442f9f4373d5795a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator COFFObjectFile::symbol_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>


<p>Referenced by <a href="#aebd5952e2b3dc1062533d96df0762772">getRelocationSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getCommonSymbolSizeImpl() {#a3eb2d4c0f51994ad276c2d71c80df945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getCommonSymbolSizeImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1047 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a9755c11be296a4d3996014d880d4c3dd">llvm::object::COFFSymbolRef::getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### getRelocationOffset() {#a98d156c093588a5df663502e9ed42032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getRelocationOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### getRelocationSymbol() {#aebd5952e2b3dc1062533d96df0762772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator COFFObjectFile::getRelocationSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a6613c0638d74614238d7181c14110c31">getNumberOfSymbols</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="#a8669c4d5032cf05442f9f4373d5795a9">symbol_end</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getRelocationType() {#a30c9f0e08ca12fdbe16d6455017b90c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getRelocationType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### getRelocationTypeName() {#ac842bb87a969bf50f9a262be16a40d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COFFObjectFile::getRelocationTypeName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1498 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a> and <a href="#a5a5c90a6256f01a33102b39f5b5fe6c0">getRelocationTypeName</a>.</p>

</div>
</div>

### getSectionAddress() {#a62a40ad1dec679e8c38a9a1705e63ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getSectionAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#ab0ecb019a3168e2f3d4cdeaabd3d9b10">getImageBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#aa784468f9faf20b0d54bbe644a0b94f0">llvm::object::coff_section::VirtualAddress</a>.</p>

</div>
</div>

### getSectionAlignment() {#aeec303725814db1282e05d6f1d775fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getSectionAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a55b4f91a2ce6aa1f508fcb111489e592">llvm::object::coff_section::getAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### getSectionContents() {#aac11a1d319562846f8aea159bcd6d300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; COFFObjectFile::getSectionContents (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1057 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#aac11a1d319562846f8aea159bcd6d300">getSectionContents</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#aac11a1d319562846f8aea159bcd6d300">getSectionContents</a>.</p>

</div>
</div>

### getSectionIndex() {#a0b3746e61eebbf85376662cd40034c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getSectionIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1054 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionName() {#a09ed4613400d9ee7e1e98b35dabeb845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; COFFObjectFile::getSectionName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1052 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a09ed4613400d9ee7e1e98b35dabeb845">getSectionName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#a09ed4613400d9ee7e1e98b35dabeb845">getSectionName</a> and <a href="#a529853b2fbf4b976d4a99b8fa8a2f144">isDebugSection</a>.</p>

</div>
</div>

### getSectionSize() {#a06f00c58e0c7e5236121c4bd02fff5d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getSectionSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#a06f00c58e0c7e5236121c4bd02fff5d5">getSectionSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#ae94132813b134e3bca64884e6b6b3cd5">getSectionContents</a> and <a href="#a06f00c58e0c7e5236121c4bd02fff5d5">getSectionSize</a>.</p>

</div>
</div>

### getSymbolAddress() {#a62ace90d17446bf72452ac5df2d0cfbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; COFFObjectFile::getSymbolAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="#ab0ecb019a3168e2f3d4cdeaabd3d9b10">getImageBase</a>, <a href="#aa320001cb948fd09beeb24178f2f8de7">getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#ad70cf7d54eb4ea803070fb903b70f44a">llvm::object::COFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa520e1a721f81e1befb66b422c6e4a60">llvm::object::ObjectFile::getSymbolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a4c74b387289140daf762aea822346deb">llvm::object::COFFSymbolRef::isAnyUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a2bf643940dab065e103dc6ef89b72e6c">llvm::object::COFFSymbolRef::isCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad9fb8ab8eb623e9967c0788fc42b150f">llvm::COFF::isReservedSectionNumber</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### getSymbolAlignment() {#a198eead1f3b968154aa768771921cff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t COFFObjectFile::getSymbolAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a9755c11be296a4d3996014d880d4c3dd">llvm::object::COFFSymbolRef::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### getSymbolFlags() {#a9eca68d4f7435b8b5ddb0d20c10bc690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; COFFObjectFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#ad70cf7d54eb4ea803070fb903b70f44a">llvm::object::COFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a5cb9fdbd29003eae3fc725811e1072ee">llvm::object::COFFSymbolRef::getWeakExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#af755df11820d1db4f001cafe15934336aa262b1c9c4e4e4411eb76fb8818264b5">llvm::COFF::IMAGE_SYM_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ac437dcd9750980233a278c48d2515271a24243cd03a81991e278a4817b463acdb">llvm::COFF::IMAGE_WEAK_EXTERN_SEARCH_ALIAS</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a2bf643940dab065e103dc6ef89b72e6c">llvm::object::COFFSymbolRef::isCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a88d5e578e07f26182eb80baa40b0fb6b">llvm::object::COFFSymbolRef::isExternal</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a5531a06cc2e1063806db2bfa1cb31dd3">llvm::object::COFFSymbolRef::isFileRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a67dd1972b87a5c8ccd3bf1fa4a9dd503">llvm::object::COFFSymbolRef::isSectionDefinition</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#aed332f322ba151963ef7b9a82dd8c3e1">llvm::object::COFFSymbolRef::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#ab3afda36f986ddb7d576aae27f4eaedf">llvm::object::COFFSymbolRef::isWeakExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431acc6eb3e8d6f0fb38a6f3eb9ddef198af">llvm::object::BasicSymbolRef::SF_Absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265">llvm::object::BasicSymbolRef::SF_FormatSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766">llvm::object::BasicSymbolRef::SF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>.</p>

</div>
</div>

### getSymbolName() {#a5034d2039fd2762121a698d20df45bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; COFFObjectFile::getSymbolName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="#a5034d2039fd2762121a698d20df45bab">getSymbolName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#af2a3431cb32a21b98211acb764b8b32a">getSymbolName</a> and <a href="#a5034d2039fd2762121a698d20df45bab">getSymbolName</a>.</p>

</div>
</div>

### getSymbolSection() {#a2456423e9e3bb5ffdc0a75fa36dd16cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; COFFObjectFile::getSymbolSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="#aa320001cb948fd09beeb24178f2f8de7">getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#ad70cf7d54eb4ea803070fb903b70f44a">llvm::object::COFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad9fb8ab8eb623e9967c0788fc42b150f">llvm::COFF::isReservedSectionNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="#a2ae5b3985996bc3c13fd150a47af0330">section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolType() {#a69eec3d86ee001dbdc76f0da1f84bb7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolRef::Type &gt; COFFObjectFile::getSymbolType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a6ec08367bd94557ab660f9cdc10c13d3">llvm::object::COFFSymbolRef::getComplexType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#ad70cf7d54eb4ea803070fb903b70f44a">llvm::object::COFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#af755df11820d1db4f001cafe15934336a41f6a8fb2e6e6e9e8ec19e8657290cd1">llvm::COFF::IMAGE_SYM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120aabbef750c1bc8143f79535ea20699385">llvm::COFF::IMAGE_SYM_DTYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a4c74b387289140daf762aea822346deb">llvm::object::COFFSymbolRef::isAnyUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a2bf643940dab065e103dc6ef89b72e6c">llvm::object::COFFSymbolRef::isCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a5531a06cc2e1063806db2bfa1cb31dd3">llvm::object::COFFSymbolRef::isFileRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad9fb8ab8eb623e9967c0788fc42b150f">llvm::COFF::isReservedSectionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a67dd1972b87a5c8ccd3bf1fa4a9dd503">llvm::object::COFFSymbolRef::isSectionDefinition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049">llvm::object::SymbolRef::ST_Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a771f3523463fc179b4e89f60841a23b8">llvm::object::SymbolRef::ST_File</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552">llvm::object::SymbolRef::ST_Unknown</a>.</p>

</div>
</div>

### getSymbolValueImpl() {#acd96a74473063785a1531e8571ed229a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t COFFObjectFile::getSymbolValueImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b03104f5d112e6566ae07122a124c4">getCOFFSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffsymbolref/#a9755c11be296a4d3996014d880d4c3dd">llvm::object::COFFSymbolRef::getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### isDebugSection() {#a529853b2fbf4b976d4a99b8fa8a2f144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isDebugSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a09ed4613400d9ee7e1e98b35dabeb845">getSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### isSectionBSS() {#a5b21593703df58c8a59363f737f0d064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isSectionBSS (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a5d5c6f0e1d23df171e3bdd1c027a06e1">llvm::object::coff_section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa4e1f40f2bdf9b194d4156c7707d047ba">llvm::COFF::IMAGE_SCN_CNT_UNINITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### isSectionCompressed() {#a1d91ce764c1bc214c3e20db726bb9f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isSectionCompressed (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionData() {#afab27e325389f1d03e34557b3a75f98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isSectionData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a5d5c6f0e1d23df171e3bdd1c027a06e1">llvm::object::coff_section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### isSectionText() {#aa3abf1f90c004e86372b780b11bca263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isSectionText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1060 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a5d5c6f0e1d23df171e3bdd1c027a06e1">llvm::object::coff_section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa2b3dbe611464bb08a83985d56d7bc67b">llvm::COFF::IMAGE_SCN_CNT_CODE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### isSectionVirtual() {#a769fe4d369055ba0768429c0b671c734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFObjectFile::isSectionVirtual (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a030e8ad39c3fe9a41a2f1927c5255701">llvm::object::coff_section::PointerToRawData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### moveRelocationNext() {#a2062e071ceff7f6624a336df1b58b6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COFFObjectFile::moveRelocationNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Rel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1068 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### moveSectionNext() {#ac01901c8d248a3abd4e92835f69362b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COFFObjectFile::moveSectionNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### moveSymbolNext() {#a3568c41169c52a6540fd0fee50e3e327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COFFObjectFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1042 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-symbol/#aaea00cd26e2aba599de33ddd92ce2705">llvm::object::coff_symbol&lt; SectionNumberType &gt;::NumberOfAuxSymbols</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### section\_rel\_begin() {#a7a78994887ac9a82a012307b4f7baf27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator COFFObjectFile::section_rel_begin (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a5a4d2bf09a4074476f11647f7ac20126">getFirstReloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#aa784468f9faf20b0d54bbe644a0b94f0">llvm::object::coff_section::VirtualAddress</a>.</p>

</div>
</div>

### section\_rel\_end() {#ac105d56f284be37d59dbca7613dcbf88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator COFFObjectFile::section_rel_end (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a5a4d2bf09a4074476f11647f7ac20126">getFirstReloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#a21926dd764fb7f7c891ec7c1ed725991">getNumberOfRelocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getString() {#a76e46f51d541bdf28a45d052c7e46b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; COFFObjectFile::getString (uint32_t offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initBaseRelocPtr() {#ae034f885e9f221e7f32def499fe8c8b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initBaseRelocPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initDebugDirectoryPtr() {#a5d230d9d800583620e612e77318ec0c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initDebugDirectoryPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initDelayImportTablePtr() {#aef9456a538b3fc68bf50888c10d9bd31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initDelayImportTablePtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initDynamicRelocPtr() {#a9d46564d459461d2f1c1c650d15998df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initDynamicRelocPtr (uint32_t SectionIndex, uint32_t SectionOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initExportTablePtr() {#a2677228140246667b403401b8aeb9b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initExportTablePtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initialize() {#abcf32002a320164d6e9ae0ead4d768e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initImportTablePtr() {#a71b4b150f112c8907295022c3bd19684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initImportTablePtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initLoadConfigPtr() {#a4c0c4c49e291475d34ecc5951c32567c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initLoadConfigPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initSymbolTablePtr() {#a05d9c08a75dd3d5a5206768d1494025d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initSymbolTablePtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### initTLSDirectoryPtr() {#a34c268acca52cc615b304d2b8f32e24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error COFFObjectFile::initTLSDirectoryPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### toRel() {#a10f660bcadbe44632c08c1bce46662e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_relocation * COFFObjectFile::toRel (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### toSec() {#a165b1b56ff611d81f04c74e663e9b912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_section * COFFObjectFile::toSec (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

### toSymb() {#a4a221b5adbb671380b3a4c06c2b7641e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename coff_symbol_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_symbol_type * COFFObjectFile::toSymb (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseRelocEnd {#a96e6e6aa920e09e729f95f3d5a0e2f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_base_reloc_block_header* llvm::object::COFFObjectFile::BaseRelocEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### BaseRelocHeader {#a60537bcd67ffb4fa3cef819b373497de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_base_reloc_block_header* llvm::object::COFFObjectFile::BaseRelocHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### CHPEMetadata {#afd5bf2f83ad900f78833ebf3a95d6fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const chpe_metadata* llvm::object::COFFObjectFile::CHPEMetadata = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### COFFBigObjHeader {#aaacc094d1ac6feffc486f5bb1329e1ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_bigobj_file_header* llvm::object::COFFObjectFile::COFFBigObjHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### COFFHeader {#a3f159f849e98c245c104d652fc0f9555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_file_header* llvm::object::COFFObjectFile::COFFHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### DataDirectory {#aff859342d5ffca6b4d3f426cdf040472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const data_directory* llvm::object::COFFObjectFile::DataDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### DebugDirectoryBegin {#ad2d296c4e2edc7c63db667d7369f367a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const debug_directory* llvm::object::COFFObjectFile::DebugDirectoryBegin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### DebugDirectoryEnd {#ab65efc444b5657266460f7638413d9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const debug_directory* llvm::object::COFFObjectFile::DebugDirectoryEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### DelayImportDirectory {#ad2b5626efe5d2218f987d51222483fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const delay_import_directory_table_entry* llvm::object::COFFObjectFile::DelayImportDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### DynamicRelocTable {#adbfc1ccdf4d0ee8651d219e5773e77ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_dynamic_reloc_table* llvm::object::COFFObjectFile::DynamicRelocTable = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### ExportDirectory {#aca9e6383dc58fdb776c832dcbda767bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const export_directory_table_entry* llvm::object::COFFObjectFile::ExportDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### ImportDirectory {#a22f7c77e3208d014135bd6d01655aeec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_import_directory_table_entry* llvm::object::COFFObjectFile::ImportDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### LoadConfig {#a00ffbef823b35e489a2f76e69e3b709b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::object::COFFObjectFile::LoadConfig = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### NumberOfDelayImportDirectory {#ac49a84274ff2ef2cdf45e8809c1a0358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::NumberOfDelayImportDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### PE32Header {#a0e4b672198f40e1dff2092a7823dd56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const pe32_header* llvm::object::COFFObjectFile::PE32Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### PE32PlusHeader {#a2555ebcea214f204d3aa08cb2eeb071d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const pe32plus_header* llvm::object::COFFObjectFile::PE32PlusHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### SectionTable {#a59f937ee38bac2043707e680519e16dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_section* llvm::object::COFFObjectFile::SectionTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### StringTable {#a71f3faa32de158ea71faacad4ed513aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::COFFObjectFile::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### StringTableSize {#a181c2a9d2d9bf17509bac3800b256d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::COFFObjectFile::StringTableSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### SymbolTable16 {#a9e089822eb0b6dbcaf41dad3fe35874c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_symbol16* llvm::object::COFFObjectFile::SymbolTable16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### SymbolTable32 {#a2f98a01f536b2af5223ff8738cab1977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_symbol32* llvm::object::COFFObjectFile::SymbolTable32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### TLSDirectory32 {#a73810635e6bb89ae62a8d2df4fdbf04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_tls_directory32* llvm::object::COFFObjectFile::TLSDirectory32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### TLSDirectory64 {#a6121dfd72d5f6be820b7d7588e59408e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const coff_tls_directory64* llvm::object::COFFObjectFile::TLSDirectory64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0b11f0424c9b665e419865e703d8c976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::COFFObjectFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * v)</td>
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



<p>Definition at line 1222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>.</p>

</div>
</div>

### create() {#a75ab5f6073614bedfd40289035d5fd2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; COFFObjectFile &gt; &gt; COFFObjectFile::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a>, definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3e3b4e38f2043b08c7a0df72bc8bd0f3">llvm::object::ObjectFile::createCOFFObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ab09d28878031ffd0f73e46ea295c1e65">anonymous{DlltoolDriver.cpp}::forEachCoff</a> and <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a2cbe923c28eb9aa4603a52f98777986a">getCOFFFileMachine</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">COFF.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp">COFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
