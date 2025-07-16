---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/offloadbinary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OffloadBinary` Class Reference

<p>A simple binary serialization of an offloading file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::OffloadBinary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">llvm/Object/OffloadBinary.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36e2f64378e956c5664208f3ca99377">string_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e42569bd879c66d21a0b9a1079cb2cb">string_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#af36e2f64378e956c5664208f3ca99377">string_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee33fd7fbe5c727164b8ece2b6bf1f4">OffloadBinary</a> (MemoryBufferRef Source, const Header *TheHeader, const Entry *TheEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fdfeb2f4c14b1203caba19b107e856b">OffloadBinary</a> (const OffloadBinary &amp;Other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#ae1135a376f397074fd6f8f79b7463e41">ImageKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaafd22b6e572b2b89fdbd3d009f82e66">getImageKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a92b4561998310fbcfbeaeb7c449bad6a">OffloadKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf27943a5c6799e1abc7d1f70155ce6">getOffloadKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43224469973bb92cca230ff166f9fa34">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673bfc1db0c11ff151707e1a884a7a52">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49156af323d266d1a66ae974964e29d">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937d9f6e28fec6d925f965131a19699b">getTriple</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8573abaa1e3de55e5ce0f59eb1adf5f">getArch</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c8458a40b5fe00255d0cc4c6f057e64">getImage</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1e42569bd879c66d21a0b9a1079cb2cb">string_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6d2cae1549be0f3c714991bc66f71d9">strings</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d206c13e41371a26bff1ece7c3b7ee">getString</a> (StringRef Key) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72101a47d1ea03d94f1a953a13e67b8a">StringData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from keys to offsets in the binary. <a href="#a72101a47d1ea03d94f1a953a13e67b8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d63d7cb0532e79d409ca0f12cb7b52d">Buffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Raw pointer to the <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> for convenience. <a href="#a9d63d7cb0532e79d409ca0f12cb7b52d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/header">Header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379ab1d33b1c25dc60a3ad9b3b2b0bb0">TheHeader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Location of the header within the binary. <a href="#a379ab1d33b1c25dc60a3ad9b3b2b0bb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/entry">Entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acbd5b5e3ebc928b80f8e29797cafa4">TheEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Location of the metadata entries within the binary. <a href="#a6acbd5b5e3ebc928b80f8e29797cafa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary">OffloadBinary</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f06bb87aef1053996ec05424135d82">create</a> (MemoryBufferRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to parse the offloading binary stored in <span class="doxyComputerOutput">Data</span>. <a href="#ab1f06bb87aef1053996ec05424135d82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f47c8dc5df749b09ecdabc977e01c7">write</a> (const OffloadingImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the contents of <span class="doxyComputerOutput">File</span> to a binary buffer to be read later. <a href="#a56f47c8dc5df749b09ecdabc977e01c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084b7cfd2acc52fcfd2121bad6608ba8">getAlignment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa0d85f9c51396eadb6294e019461a3">classof</a> (const Binary *V)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec63ebc11ae7c16a9c804f9e30e397b8">Version</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current version of the binary used for backwards compatibility. <a href="#aec63ebc11ae7c16a9c804f9e30e397b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A simple binary serialization of an offloading file.</p>


<p>We use this format to embed the offloading image into the host executable so it can be extracted and used by the linker.</p>


<p>Many of these could be stored in the same section by the time the linker sees it so we mark this information with a header. The version is used to detect ABI stability and the size is used to find other offloading entries that may exist in the same section. All offsets are given as absolute byte offsets from the beginning of the file.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### string\_iterator {#af36e2f64378e956c5664208f3ca99377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::OffloadBinary::string_iterator =  MapVector&lt;StringRef, StringRef&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### string\_iterator\_range {#a1e42569bd879c66d21a0b9a1079cb2cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::OffloadBinary::string_iterator_range =  iterator_range&lt;string_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OffloadBinary() {#aeee33fd7fbe5c727164b8ece2b6bf1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::OffloadBinary::OffloadBinary (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/header">Header</a> * TheHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/entry">Entry</a> * TheEntry)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### OffloadBinary() {#a6fdfeb2f4c14b1203caba19b107e856b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::OffloadBinary::OffloadBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary">OffloadBinary</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArch() {#ac8573abaa1e3de55e5ce0f59eb1adf5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::OffloadBinary::getArch ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Reference <a href="#a32d206c13e41371a26bff1ece7c3b7ee">getString</a>.</p>

</div>
</div>

### getFlags() {#a673bfc1db0c11ff151707e1a884a7a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::OffloadBinary::getFlags ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### getImage() {#a4c8458a40b5fe00255d0cc4c6f057e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::OffloadBinary::getImage ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### getImageKind() {#aaafd22b6e572b2b89fdbd3d009f82e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImageKind llvm::object::OffloadBinary::getImageKind ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### getOffloadKind() {#a0bf27943a5c6799e1abc7d1f70155ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffloadKind llvm::object::OffloadBinary::getOffloadKind ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### getSize() {#ad49156af323d266d1a66ae974964e29d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::OffloadBinary::getSize ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### getString() {#a32d206c13e41371a26bff1ece7c3b7ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::OffloadBinary::getString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>


<p>Referenced by <a href="#ac8573abaa1e3de55e5ce0f59eb1adf5f">getArch</a> and <a href="#a937d9f6e28fec6d925f965131a19699b">getTriple</a>.</p>

</div>
</div>

### getTriple() {#a937d9f6e28fec6d925f965131a19699b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::OffloadBinary::getTriple ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Reference <a href="#a32d206c13e41371a26bff1ece7c3b7ee">getString</a>.</p>

</div>
</div>

### getVersion() {#a43224469973bb92cca230ff166f9fa34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::OffloadBinary::getVersion ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### strings() {#ac6d2cae1549be0f3c714991bc66f71d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">string_iterator_range llvm::object::OffloadBinary::strings ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#a9d63d7cb0532e79d409ca0f12cb7b52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::object::OffloadBinary::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Raw pointer to the <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> for convenience.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### StringData {#a72101a47d1ea03d94f1a953a13e67b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;StringRef, StringRef&gt; llvm::object::OffloadBinary::StringData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from keys to offsets in the binary.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### TheEntry {#a6acbd5b5e3ebc928b80f8e29797cafa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Entry* llvm::object::OffloadBinary::TheEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Location of the metadata entries within the binary.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

### TheHeader {#a379ab1d33b1c25dc60a3ad9b3b2b0bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Header* llvm::object::OffloadBinary::TheHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Location of the header within the binary.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#abaa0d85f9c51396eadb6294e019461a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::OffloadBinary::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * V)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>.</p>

</div>
</div>

### create() {#ab1f06bb87aef1053996ec05424135d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; OffloadBinary &gt; &gt; OffloadBinary::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buf)</td>
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

<p>Attempt to parse the offloading binary stored in <span class="doxyComputerOutput">Data</span>.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#a084b7cfd2acc52fcfd2121bad6608ba8">getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9992f46ab43b45770fddfdefef7c237">llvm::isAddrAligned</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa91e1aaaa67b1f5232dbea39497ef9250">llvm::file_magic::offload_binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a1a5b101afc11147048312dd33b62e008">llvm::object::unexpected_eof</a> and <a href="#aec63ebc11ae7c16a9c804f9e30e397b8">Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadfile/#a9b4886b96406a196d56ea326687ba908">llvm::object::OffloadFile::copy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>.</p>

</div>
</div>

### getAlignment() {#a084b7cfd2acc52fcfd2121bad6608ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::OffloadBinary::getAlignment ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="#ab1f06bb87aef1053996ec05424135d82">create</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#aa2f8f902ed35880d4ccb900b4ddbe2c1">anonymous{OffloadBinary.cpp}::extractFromArchive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a> and <a href="#a56f47c8dc5df749b09ecdabc977e01c7">write</a>.</p>

</div>
</div>

### write() {#a56f47c8dc5df749b09ecdabc977e01c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 0 &gt; OffloadBinary::write (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/offloadingimage">OffloadingImage</a> &amp; OffloadingData)</td>
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

<p>Serialize the contents of <span class="doxyComputerOutput">File</span> to a binary buffer to be read later.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae6ba484ec18769c20a3c576c02f0b2a7">llvm::StringTableBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aadb97a5bc1bb9ee2bc8b2dbb9065755f5">llvm::StringTableBuilder::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae745bcacfe97669686a4f7c2941d9e0a">llvm::StringTableBuilder::finalize</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/offloadingimage/#a55e305331a4556a83d806c1d6d3091e8">llvm::object::OffloadBinary::OffloadingImage::Flags</a>, <a href="#a084b7cfd2acc52fcfd2121bad6608ba8">getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a13bc9289af7e5d306d3951a0ab8f0b11">llvm::StringTableBuilder::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#af48cff00887e58910f0074f00165b784">llvm::StringTableBuilder::getSize</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/offloadingimage/#a7e5028688bea4574b8f3af7947c33a50">llvm::object::OffloadBinary::OffloadingImage::Image</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/header/#ae363d7f95e4d5fd5edd44bb29df0a0d0">llvm::object::OffloadBinary::Header::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/offloadingimage/#ae20697624777c3f848573c5ca97bfc28">llvm::object::OffloadBinary::OffloadingImage::StringData</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/entry/#a4613ab6d54a9f3d5f4cbe0afa303613f">llvm::object::OffloadBinary::Entry::TheImageKind</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/offloadingimage/#a865ec496e0ae3a02e4778d6db2c05e4d">llvm::object::OffloadBinary::OffloadingImage::TheImageKind</a>, <a href="/web-llvm/docs/api/structs/llvm/object/offloadbinary/offloadingimage/#a39740c937ded0a868e287d8ea509c8a4">llvm::object::OffloadBinary::OffloadingImage::TheOffloadKind</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae2469d919349b52e2d98dd09fed5d623">llvm::StringTableBuilder::write</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a960217c66ca1fa6c96ec78eba269b580">llvm::yaml::yaml2offload</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Version {#aec63ebc11ae7c16a9c804f9e30e397b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::object::OffloadBinary::Version = 1</td>
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

<p>The current version of the binary used for backwards compatibility.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a>.</p>


<p>Referenced by <a href="#ab1f06bb87aef1053996ec05424135d82">create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/offloadbinary-h">OffloadBinary.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/offloadbinary-cpp">OffloadBinary.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
