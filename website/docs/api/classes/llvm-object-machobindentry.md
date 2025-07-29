---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/machobindentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachOBindEntry` Class

<p><a href="/web-llvm/docs/api/classes/llvm/object/machobindentry">MachOBindEntry</a> encapsulates the current state in the decompression of binding opcodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::MachOBindEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#af6efd0f55e33298ac3bb484e6fd285b9">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7a652c1046385908bf8934960d6c45">MachOObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f570c7e9eb2d4585ab39f3f77a2f96d">MachOBindEntry</a> (Error *Err, const MachOObjectFile *O, ArrayRef&lt; uint8_t &gt; Opcodes, bool is64Bit, MachOBindEntry::Kind)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434b2cb6506b340ee35b63e5c545982f">operator==</a> (const MachOBindEntry &amp;) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca1e133ec69ac5f0cb3efc107d37881">segmentIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853b8ca72cc35d9968b12a1a6ac0b335">segmentOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc3aca00aaeb9ca53fc43c562588d13">typeName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2821d73d9c3c9222490a5e01135a5c">symbolName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b8c57c886810c6cfdee1b23f1b834d">flags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa47a06379dde66271aaf1877a22cc6e2">addend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67547bfbd618120801c7e10f7d16f939">ordinal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a5702fa01755ffb1d65733d114a58a">segmentName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71600cc1df077823aaa697a5ab6cd2f2">sectionName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa707137401fa160300bd60f29af02025">address</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a875fa809c0df5dff3223d539ae4c7c">moveNext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1211b2428242fd5c7382d417421cc3a2">moveToFirst</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dff8ed86835765b505cc006b60f4627">moveToEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e8e9c037cf061814d1b721f88a18b9">readULEB128</a> (const char **error)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601e607526b1ed562b9ff7b795ed9a26">readSLEB128</a> (const char **error)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6103273d85365af1bacc1e37b95b57c">E</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf3b580581ff62cbf24629a518423d8">O</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389f83cdff2ceb5e7af66d21ced69e6a">Opcodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf6c8b20f39c40c612d40c086471adb">Ptr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e391576e606123df00ec5b8a7e50b1e">SegmentOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb68c7f13e9f127328745d5d65ec9ee">SegmentIndex</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af055e79236e461c03f3a6c669af99c8b">SymbolName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97032ca574175667e6a9c96f0a0edbbb">LibraryOrdinalSet</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f2b7a1a3ce6429c78c04cf68ad3dd9">Ordinal</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3fc8503332dc61edb22a6c3f7a682b8">Flags</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848d6564d4a2bb2356ba8615f3830307">Addend</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68779738c916b2175992beb80331f08b">RemainingLoopCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74afdb871c6197ed9a699e566abd145b">AdvanceAmount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7fb1e0093ecc896c709ec45865fdd29">BindType</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6814b3031a67e35848490007e241a180">PointerSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af6efd0f55e33298ac3bb484e6fd285b9">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff2e7be2563b6340c1f59db59108505">TableKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4ba5e62e81509a6a95acf36ea3efce">Done</a> = false</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/object/machobindentry">MachOBindEntry</a> encapsulates the current state in the decompression of binding opcodes.</p>


<p>This allows you to iterate through the compressed table of bindings using: <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err = <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a>; for (const <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry">llvm::object::MachOBindEntry</a> &amp;Entry : Obj-&gt;bindTable(&amp;Err)) { } if (Err) { report error ...</p>


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#af6efd0f55e33298ac3bb484e6fd285b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::object::MachOBindEntry::Kind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Regular<a id="af6efd0f55e33298ac3bb484e6fd285b9ad2203cb1237cb6460cbad94564e39345"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lazy<a id="af6efd0f55e33298ac3bb484e6fd285b9a46a9ebdb80117bfa1f0cdea65438290a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="af6efd0f55e33298ac3bb484e6fd285b9a7324e3727807d95037eb19d304fd91ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MachOObjectFile {#abd7a652c1046385908bf8934960d6c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="#abd7a652c1046385908bf8934960d6c45">MachOObjectFile</a>.</p>


<p>Referenced by <a href="#a7f570c7e9eb2d4585ab39f3f77a2f96d">MachOBindEntry</a> and <a href="#abd7a652c1046385908bf8934960d6c45">MachOObjectFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachOBindEntry() {#a7f570c7e9eb2d4585ab39f3f77a2f96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOBindEntry::MachOBindEntry (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * O, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Opcodes, bool is64Bit, <a href="#af6efd0f55e33298ac3bb484e6fd285b9">MachOBindEntry::Kind</a> BK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3818 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a> and <a href="#abd7a652c1046385908bf8934960d6c45">MachOObjectFile</a>.</p>


<p>Referenced by <a href="#a434b2cb6506b340ee35b63e5c545982f">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a434b2cb6506b340ee35b63e5c545982f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachOBindEntry::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry">MachOBindEntry</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4343 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f570c7e9eb2d4585ab39f3f77a2f96d">MachOBindEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addend() {#aa47a06379dde66271aaf1877a22cc6e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MachOBindEntry::addend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4319 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### address() {#aa707137401fa160300bd60f29af02025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOBindEntry::address ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4339 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### flags() {#a38b8c57c886810c6cfdee1b23f1b834d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t MachOBindEntry::flags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4321 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### moveNext() {#a4a875fa809c0df5dff3223d539ae4c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOBindEntry::moveNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3834 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a842301af3a51cf544c9b80ccb1eac620aee927ceb1905da5a2d4409352dd231ad">llvm::MachO::BIND_IMMEDIATE_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a8e4926db8e267967f2ab9e0aa34afd8c">llvm::MachO::BIND_OPCODE_ADD_ADDR_ULEB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a97d232b1bfabb3ee3ca5b9dbba2fcb0f">llvm::MachO::BIND_OPCODE_DO_BIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a9106a073897b69bd55b72e11b3859ef6">llvm::MachO::BIND_OPCODE_DO_BIND_ADD_ADDR_IMM_SCALED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a3eb3521c78fa4acbbbd6887ccc95937f">llvm::MachO::BIND_OPCODE_DO_BIND_ADD_ADDR_ULEB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a0cf7a060db1baed294f7d33f19a0a25f">llvm::MachO::BIND_OPCODE_DO_BIND_ULEB_TIMES_SKIPPING_ULEB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a320eb56353bbe0f940ec9da2058d4295">llvm::MachO::BIND_OPCODE_DONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a842301af3a51cf544c9b80ccb1eac620a8915c95730c3845f72deafae695b03ea">llvm::MachO::BIND_OPCODE_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a47f5488b8f462ad11e53fcd0f5181c08">llvm::MachO::BIND_OPCODE_SET_ADDEND_SLEB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128aab95c0873b89b45668679d1871184d9e">llvm::MachO::BIND_OPCODE_SET_DYLIB_ORDINAL_IMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a6d9d15122d7c005a9b81e27e4097baf2">llvm::MachO::BIND_OPCODE_SET_DYLIB_ORDINAL_ULEB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a94eccc7eb063ecbb9fde7c545b759198">llvm::MachO::BIND_OPCODE_SET_DYLIB_SPECIAL_IMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128afff117ddfa29c4453e495ff4bade784d">llvm::MachO::BIND_OPCODE_SET_SEGMENT_AND_OFFSET_ULEB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128a83afb6cd049d83588201241f9aca21c8">llvm::MachO::BIND_OPCODE_SET_SYMBOL_TRAILING_FLAGS_IMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9203e99e8a95bc43ed5ce4f40e497128aa510e40b3108b04e8f1320c9659132b7">llvm::MachO::BIND_OPCODE_SET_TYPE_IMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48ca294d164bd72c67e18da73f2677b4ac92d317359f68971056be15d73a5af1f">llvm::MachO::BIND_SPECIAL_DYLIB_FLAT_LOOKUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a842301af3a51cf544c9b80ccb1eac620a8200b750ffa4ed886512bf12dea00236">llvm::MachO::BIND_SYMBOL_FLAGS_NON_WEAK_DEFINITION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a1b9d71bee45294e6bcf80334d3b65075a8bf50b5097db2b5c0d33ff114cd587e4">llvm::MachO::BIND_TYPE_TEXT_PCREL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#af6efd0f55e33298ac3bb484e6fd285b9a46a9ebdb80117bfa1f0cdea65438290a">Lazy</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a> and <a href="#af6efd0f55e33298ac3bb484e6fd285b9a7324e3727807d95037eb19d304fd91ec">Weak</a>.</p>

</div>
</div>

### ordinal() {#a67547bfbd618120801c7e10f7d16f939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MachOBindEntry::ordinal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4323 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### sectionName() {#a71600cc1df077823aaa697a5ab6cd2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOBindEntry::sectionName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4333 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### segmentIndex() {#acca1e133ec69ac5f0cb3efc107d37881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t MachOBindEntry::segmentIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4301 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### segmentName() {#a82a5702fa01755ffb1d65733d114a58a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOBindEntry::segmentName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4327 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### segmentOffset() {#a853b8ca72cc35d9968b12a1a6ac0b335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOBindEntry::segmentOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4303 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### symbolName() {#a5a2821d73d9c3c9222490a5e01135a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOBindEntry::symbolName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4317 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### typeName() {#adcc3aca00aaeb9ca53fc43c562588d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachOBindEntry::typeName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4305 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a1b9d71bee45294e6bcf80334d3b65075aac04a7bae61ef333fcaecd3426c6aa9e">llvm::MachO::BIND_TYPE_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a1b9d71bee45294e6bcf80334d3b65075aed9cf03378a77116d387557cb2d17583">llvm::MachO::BIND_TYPE_TEXT_ABSOLUTE32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a1b9d71bee45294e6bcf80334d3b65075a8bf50b5097db2b5c0d33ff114cd587e4">llvm::MachO::BIND_TYPE_TEXT_PCREL32</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### moveToEnd() {#a7dff8ed86835765b505cc006b60f4627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOBindEntry::moveToEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3828 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### moveToFirst() {#a1211b2428242fd5c7382d417421cc3a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachOBindEntry::moveToFirst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 3823 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### readSLEB128() {#a601e607526b1ed562b9ff7b795ed9a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t MachOBindEntry::readSLEB128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** error)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4292 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

### readULEB128() {#a38e8e9c037cf061814d1b721f88a18b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachOBindEntry::readULEB128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** error)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>, definition at line 4283 of file <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Addend {#a848d6564d4a2bb2356ba8615f3830307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::object::MachOBindEntry::Addend = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### AdvanceAmount {#a74afdb871c6197ed9a699e566abd145b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOBindEntry::AdvanceAmount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### BindType {#ad7fb1e0093ecc896c709ec45865fdd29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::MachOBindEntry::BindType = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Done {#a3f4ba5e62e81509a6a95acf36ea3efce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOBindEntry::Done = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### E {#aa6103273d85365af1bacc1e37b95b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error* llvm::object::MachOBindEntry::E</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Flags {#ad3fc8503332dc61edb22a6c3f7a682b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::MachOBindEntry::Flags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### LibraryOrdinalSet {#a97032ca574175667e6a9c96f0a0edbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MachOBindEntry::LibraryOrdinalSet = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### O {#adaf3b580581ff62cbf24629a518423d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachOObjectFile* llvm::object::MachOBindEntry::O</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Opcodes {#a389f83cdff2ceb5e7af66d21ced69e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::object::MachOBindEntry::Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Ordinal {#af5f2b7a1a3ce6429c78c04cf68ad3dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::object::MachOBindEntry::Ordinal = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### PointerSize {#a6814b3031a67e35848490007e241a180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::MachOBindEntry::PointerSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### Ptr {#a0bf6c8b20f39c40c612d40c086471adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t* llvm::object::MachOBindEntry::Ptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### RemainingLoopCount {#a68779738c916b2175992beb80331f08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOBindEntry::RemainingLoopCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### SegmentIndex {#abfb68c7f13e9f127328745d5d65ec9ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::MachOBindEntry::SegmentIndex = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### SegmentOffset {#a6e391576e606123df00ec5b8a7e50b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::MachOBindEntry::SegmentOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### SymbolName {#af055e79236e461c03f3a6c669af99c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::MachOBindEntry::SymbolName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

### TableKind {#abff2e7be2563b6340c1f59db59108505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::object::MachOBindEntry::TableKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp">MachOObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
