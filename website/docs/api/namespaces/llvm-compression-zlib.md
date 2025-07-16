---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/compression/zlib
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `zlib` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::compression::zlib { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369da242fd5c0d70a31ffcd3374a0909">isAvailable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cde98f89d9b23b493dc0c7c0f054eb5">compress</a> (ArrayRef&lt; uint8_t &gt; Input, SmallVectorImpl&lt; uint8_t &gt; &amp;CompressedBuffer, int Level=DefaultCompression)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f2be1038afa2414d1df3da720de0c55">decompress</a> (ArrayRef&lt; uint8_t &gt; Input, uint8_t *Output, size_t &amp;UncompressedSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e173a2b36628a36ca5de692f6c773d">decompress</a> (ArrayRef&lt; uint8_t &gt; Input, SmallVectorImpl&lt; uint8_t &gt; &amp;Output, size_t UncompressedSize)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f069c45f3ede1898e07c3dcfb894a91">NoCompression</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76c95a902eec05086940cf67c6047de">BestSpeedCompression</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ab2b657ee11cf4e2cab101623b94df">DefaultCompression</a> = 6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca36e81333c6bff75084ce9df5c1baaf">BestSizeCompression</a> = 9</td>
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

## Functions

### compress() {#a0cde98f89d9b23b493dc0c7c0f054eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::compression::zlib::compress (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; CompressedBuffer, int Level=<a href="#ad3ab2b657ee11cf4e2cab101623b94df">DefaultCompression</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/#afa6436cae5aba19d74d91f619ac7a635">llvm::compression::compress</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragefilenamessectionwriter/#a244a9bcfc38a346ac3c76bde7edbfca2">llvm::coverage::CoverageFilenamesSectionWriter::write</a>.</p>

</div>
</div>

### decompress() {#a1f2be1038afa2414d1df3da720de0c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::compression::zlib::decompress (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, uint8_t * Output, size_t &amp; UncompressedSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/compression/#a4d8e395f255894e9332618a800ca175b">llvm::compression::decompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/#af0ec62d7b9545309bcd1880f10cdec3d">llvm::compression::decompress</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#ab1e2363d08ff779aade90747e730bfd9">llvm::coverage::RawCoverageFilenamesReader::read</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>.</p>

</div>
</div>

### decompress() {#a58e173a2b36628a36ca5de692f6c773d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::compression::zlib::decompress (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Input, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; Output, size_t UncompressedSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isAvailable() {#a369da242fd5c0d70a31ffcd3374a0909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::compression::zlib::isAvailable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/compression-cpp">Compression.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7225c5646513edfb422f6b6518984b52">llvm::collectPGOFuncNameStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad3f8fff250d2097627615cd46a3abd0">llvm::collectVTableStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/#a3d9cefba87d0911ecaa4ae38e7f3d5e8">llvm::compression::getReasonIfUnsupported</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragefilenamesreader/#ab1e2363d08ff779aade90747e730bfd9">llvm::coverage::RawCoverageFilenamesReader::read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragefilenamessectionwriter/#a244a9bcfc38a346ac3c76bde7edbfca2">llvm::coverage::CoverageFilenamesSectionWriter::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BestSizeCompression {#aca36e81333c6bff75084ce9df5c1baaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::compression::zlib::BestSizeCompression = 9</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a> and <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragefilenamessectionwriter/#a244a9bcfc38a346ac3c76bde7edbfca2">llvm::coverage::CoverageFilenamesSectionWriter::write</a>.</p>

</div>
</div>

### BestSpeedCompression {#af76c95a902eec05086940cf67c6047de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::compression::zlib::BestSpeedCompression = 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>.</p>

</div>
</div>

### DefaultCompression {#ad3ab2b657ee11cf4e2cab101623b94df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::compression::zlib::DefaultCompression = 6</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>.</p>

</div>
</div>

### NoCompression {#a3f069c45f3ede1898e07c3dcfb894a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::compression::zlib::NoCompression = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compression-h">Compression.h</a>.</p>

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
