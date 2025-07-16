---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcovbuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCOVBuffer` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/gcovbuffer">GCOVBuffer</a> - A wrapper around <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> to provide <a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> specific read operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCOVBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">llvm/ProfileData/GCOV.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47c0b9404b9090968015a6836239394d">GCOVBuffer</a> (MemoryBuffer *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba30e0387e5148f1c866246e35a237d">~GCOVBuffer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1db2af6d2bd3952490d0ecc76aab3b1">readGCNOFormat</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>readGCNOFormat - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> GCNO signature is valid at the beginning of buffer. <a href="#ad1db2af6d2bd3952490d0ecc76aab3b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb37a1905e7f29be59a6d5406da52a32">readGCDAFormat</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>readGCDAFormat - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> GCDA signature is valid at the beginning of buffer. <a href="#afb37a1905e7f29be59a6d5406da52a32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6deeee5c731229c55b313c6452c3b8a2">readGCOVVersion</a> (GCOV::GCOVVersion &amp;version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>readGCOVVersion - Read <a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> version. <a href="#a6deeee5c731229c55b313c6452c3b8a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab936bbd10280d7a6c58bf9595f61dbc3">getWord</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0580e9799d5afe5272949dc8a95978">getString</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c24305d1aa0d278822f0ae9693e600">readInt</a> (uint32_t &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20182b16fc75ceb2edabd413f5e5247a">readInt64</a> (uint64_t &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ab176059f9da274f454d5b4c10a7c3">readString</a> (StringRef &amp;str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a> {<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;{}, false, 0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">DataExtractor::Cursor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a> {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91518fa4dd620494d90a651650e1ea29">Buffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08">GCOV::GCOVVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace14827219c77958bea408f04fe5baf9">version</a> {}</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/gcovbuffer">GCOVBuffer</a> - A wrapper around <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> to provide <a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> specific read operations.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCOVBuffer() {#a47c0b9404b9090968015a6836239394d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCOVBuffer::GCOVBuffer (<a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * B)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GCOVBuffer() {#a3ba30e0387e5148f1c866246e35a237d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCOVBuffer::~GCOVBuffer ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a> and <a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getString() {#adc0580e9799d5afe5272949dc8a95978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GCOVBuffer::getString ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a>, <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a> and <a href="#a09c24305d1aa0d278822f0ae9693e600">readInt</a>.</p>

</div>
</div>

### getWord() {#ab936bbd10280d7a6c58bf9595f61dbc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVBuffer::getWord ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a> and <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### readGCDAFormat() {#afb37a1905e7f29be59a6d5406da52a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVBuffer::readGCDAFormat ()</td>
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

<p>readGCDAFormat - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> GCDA signature is valid at the beginning of buffer.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>.</p>

</div>
</div>

### readGCNOFormat() {#ad1db2af6d2bd3952490d0ecc76aab3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVBuffer::readGCNOFormat ()</td>
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

<p>readGCNOFormat - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> GCNO signature is valid at the beginning of buffer.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### readGCOVVersion() {#a6deeee5c731229c55b313c6452c3b8a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVBuffer::readGCOVVersion (<a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08">GCOV::GCOVVersion</a> &amp; version)</td>
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

<p>readGCOVVersion - Read <a href="/web-llvm/docs/api/namespaces/llvm/gcov">GCOV</a> version.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a>, <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08ab1e658d09f62b1e53e0cb99a37df31e3">llvm::GCOV::V1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08adc96e487f3fa2bd49eee766c414dac00">llvm::GCOV::V304</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a28fc20af08dacec19f1191703628427b">llvm::GCOV::V407</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a607cdde36f2294fa72393d08056f261e">llvm::GCOV::V408</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a44a2004dc53121e992331b77372bba6d">llvm::GCOV::V800</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a6fde43e4bd261973caa55253c97501ba">llvm::GCOV::V900</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### readInt() {#a09c24305d1aa0d278822f0ae9693e600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVBuffer::readInt (uint32_t &amp; Val)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a>, <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="#adc0580e9799d5afe5272949dc8a95978">getString</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>, <a href="#a20182b16fc75ceb2edabd413f5e5247a">readInt64</a> and <a href="#a79ab176059f9da274f454d5b4c10a7c3">readString</a>.</p>

</div>
</div>

### readInt64() {#a20182b16fc75ceb2edabd413f5e5247a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVBuffer::readInt64 (uint64_t &amp; Val)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="#a09c24305d1aa0d278822f0ae9693e600">readInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>.</p>

</div>
</div>

### readString() {#a79ab176059f9da274f454d5b4c10a7c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVBuffer::readString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; str)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#a1533ae57f14fba1a9f835ea9f7d521d2">cursor</a>, <a href="#aa7bac54592a4de07ee31603aa6af6b03">de</a>, <a href="#a09c24305d1aa0d278822f0ae9693e600">readInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08ab1e658d09f62b1e53e0cb99a37df31e3">llvm::GCOV::V1200</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### cursor {#a1533ae57f14fba1a9f835ea9f7d521d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor::Cursor llvm::GCOVBuffer::cursor {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#adc0580e9799d5afe5272949dc8a95978">getString</a>, <a href="#ab936bbd10280d7a6c58bf9595f61dbc3">getWord</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>, <a href="#a6deeee5c731229c55b313c6452c3b8a2">readGCOVVersion</a>, <a href="#a09c24305d1aa0d278822f0ae9693e600">readInt</a>, <a href="#a79ab176059f9da274f454d5b4c10a7c3">readString</a> and <a href="#a3ba30e0387e5148f1c866246e35a237d">~GCOVBuffer</a>.</p>

</div>
</div>

### de {#aa7bac54592a4de07ee31603aa6af6b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor llvm::GCOVBuffer::de {<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;{}, false, 0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#adc0580e9799d5afe5272949dc8a95978">getString</a>, <a href="#ab936bbd10280d7a6c58bf9595f61dbc3">getWord</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>, <a href="#afb37a1905e7f29be59a6d5406da52a32">readGCDAFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>, <a href="#ad1db2af6d2bd3952490d0ecc76aab3b1">readGCNOFormat</a>, <a href="#a6deeee5c731229c55b313c6452c3b8a2">readGCOVVersion</a>, <a href="#a09c24305d1aa0d278822f0ae9693e600">readInt</a> and <a href="#a79ab176059f9da274f454d5b4c10a7c3">readString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#a91518fa4dd620494d90a651650e1ea29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBuffer* llvm::GCOVBuffer::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

### version {#ace14827219c77958bea408f04fe5baf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOV::GCOVVersion llvm::GCOVBuffer::version {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
