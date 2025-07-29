---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/compression
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `compression` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::compression { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib">zlib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/compression/zstd">zstd</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/compression/params">Params</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Format { <a href="#a959b9bf86b359a97448539383fb1b5f3">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a959b9bf86b359a97448539383fb1b5f3">Format</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bbde31a8b729ac4f8022306356a6f5">formatFor</a> (DebugCompressionType Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9cefba87d0911ecaa4ae38e7f3d5e8">getReasonIfUnsupported</a> (Format F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6436cae5aba19d74d91f619ac7a635">compress</a> (Params P, ArrayRef&lt; uint8_t &gt; Input, SmallVectorImpl&lt; uint8_t &gt; &amp;Output)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8e395f255894e9332618a800ca175b">decompress</a> (DebugCompressionType T, ArrayRef&lt; uint8_t &gt; Input, uint8_t *Output, size_t UncompressedSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ec62d7b9545309bcd1880f10cdec3d">decompress</a> (Format F, ArrayRef&lt; uint8_t &gt; Input, SmallVectorImpl&lt; uint8_t &gt; &amp;Output, size_t UncompressedSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4845ca8e22286ebb42866bcd08dea1">decompress</a> (DebugCompressionType T, ArrayRef&lt; uint8_t &gt; Input, SmallVectorImpl&lt; uint8_t &gt; &amp;Output, size_t UncompressedSize)</td>
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


<div class="doxySectionDef">

## Enumerations

### Format {#a959b9bf86b359a97448539383fb1b5f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::compression::Format </td>
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
<td class="doxyEnumItemName">Zlib<a id="a959b9bf86b359a97448539383fb1b5f3ad697a787afbc87e2117697b91ed26272"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Zstd<a id="a959b9bf86b359a97448539383fb1b5f3a0c8468c9ff2f38e853335e1e40ade4c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### compress() {#afa6436cae5aba19d74d91f619ac7a635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::compression::compress (<a href="/web-llvm/docs/api/structs/llvm/compression/params">Params</a> P, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib/#a0cde98f89d9b23b493dc0c7c0f054eb5">llvm::compression::zlib::compress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zstd/#a6e5017312495e404a75be3aafeeb08c5">llvm::compression::zstd::compress</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a959b9bf86b359a97448539383fb1b5f3ad697a787afbc87e2117697b91ed26272">Zlib</a> and <a href="#a959b9bf86b359a97448539383fb1b5f3a0c8468c9ff2f38e853335e1e40ade4c3">Zstd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/compressedsection/#a91ca209a030c16d2b41474b97f96d783">llvm::objcopy::elf::CompressedSection::CompressedSection</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aaf1d0c4d37d55950252509e0b0c84501">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionData</a>.</p>

</div>
</div>

### decompress() {#a4d8e395f255894e9332618a800ca175b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::compression::decompress (<a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00">DebugCompressionType</a> T, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, uint8_t * Output, size_t UncompressedSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib/#a1f2be1038afa2414d1df3da720de0c55">llvm::compression::zlib::decompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zstd/#a383d40dba37b3eecd97fbeeacda6477c">llvm::compression::zstd::decompress</a>, <a href="#ad1bbde31a8b729ac4f8022306356a6f5">formatFor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a959b9bf86b359a97448539383fb1b5f3ad697a787afbc87e2117697b91ed26272">Zlib</a> and <a href="#a959b9bf86b359a97448539383fb1b5f3a0c8468c9ff2f38e853335e1e40ade4c3">Zstd</a>.</p>


<p>Referenced by <a href="#aba4845ca8e22286ebb42866bcd08dea1">decompress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/decompressor/#aeff1a966d66b995e39f35c393a437a10">llvm::object::Decompressor::decompress</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>.</p>

</div>
</div>

### decompress() {#af0ec62d7b9545309bcd1880f10cdec3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::compression::decompress (<a href="#a959b9bf86b359a97448539383fb1b5f3">Format</a> F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Output, size_t UncompressedSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib/#a1f2be1038afa2414d1df3da720de0c55">llvm::compression::zlib::decompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zstd/#a383d40dba37b3eecd97fbeeacda6477c">llvm::compression::zstd::decompress</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a959b9bf86b359a97448539383fb1b5f3ad697a787afbc87e2117697b91ed26272">Zlib</a> and <a href="#a959b9bf86b359a97448539383fb1b5f3a0c8468c9ff2f38e853335e1e40ade4c3">Zstd</a>.</p>

</div>
</div>

### decompress() {#aba4845ca8e22286ebb42866bcd08dea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::compression::decompress (<a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00">DebugCompressionType</a> T, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Output, size_t UncompressedSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>References <a href="#a4d8e395f255894e9332618a800ca175b">decompress</a>, <a href="#ad1bbde31a8b729ac4f8022306356a6f5">formatFor</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### formatFor() {#ad1bbde31a8b729ac4f8022306356a6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Format llvm::compression::formatFor (<a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00">DebugCompressionType</a> Type)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a959b9bf86b359a97448539383fb1b5f3ad697a787afbc87e2117697b91ed26272">Zlib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00ad697a787afbc87e2117697b91ed26272">llvm::Zlib</a>, <a href="#a959b9bf86b359a97448539383fb1b5f3a0c8468c9ff2f38e853335e1e40ade4c3">Zstd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00a0c8468c9ff2f38e853335e1e40ade4c3">llvm::Zstd</a>.</p>


<p>Referenced by <a href="#aba4845ca8e22286ebb42866bcd08dea1">decompress</a>, <a href="#a4d8e395f255894e9332618a800ca175b">decompress</a>, <a href="/web-llvm/docs/api/structs/llvm/compression/params/#a094a364edadfccda93cb01dc23e341dd">llvm::compression::Params::Params</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>.</p>

</div>
</div>

### getReasonIfUnsupported() {#a3d9cefba87d0911ecaa4ae38e7f3d5e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::compression::getReasonIfUnsupported (<a href="#a959b9bf86b359a97448539383fb1b5f3">Format</a> F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zlib/#a369da242fd5c0d70a31ffcd3374a0909">llvm::compression::zlib::isAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/zstd/#a663a259708521e3e0dd26b77ba4f49e8">llvm::compression::zstd::isAvailable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a959b9bf86b359a97448539383fb1b5f3ad697a787afbc87e2117697b91ed26272">Zlib</a> and <a href="#a959b9bf86b359a97448539383fb1b5f3a0c8468c9ff2f38e853335e1e40ade4c3">Zstd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
