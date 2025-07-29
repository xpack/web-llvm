---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/filewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FileWriter` Class

<p>A simplified binary data writer class that doesn't require targets, target definitions, architectures, or require any other optional compile time libraries to be enabled via the build process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::gsym::FileWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">llvm/DebugInfo/GSYM/FileWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b386e2d944089795e87b32182ed9dc">FileWriter</a> (llvm::raw_pwrite_stream &amp;S, llvm::endianness B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4ab35e164da639bfc5195aa0d00597">FileWriter</a> (const FileWriter &amp;rhs)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5490307dcaf9237f4c1b8b8df433e03">~FileWriter</a> ()</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2650dd36112ef09ead6a40ba1c158e3">operator=</a> (const FileWriter &amp;rhs)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e4989cbade2289d6496aa80c97a748">writeU8</a> (uint8_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a single uint8_t value into the stream at the current file position. <a href="#a45e4989cbade2289d6496aa80c97a748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dcdc350144ba397db6ac8d0f0d871d0">writeU16</a> (uint16_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a single uint16_t value into the stream at the current file position. <a href="#a1dcdc350144ba397db6ac8d0f0d871d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766e343d0ff12c414ffa59f35c1f562d">writeU32</a> (uint32_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a single uint32_t value into the stream at the current file position. <a href="#a766e343d0ff12c414ffa59f35c1f562d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6da8c6b7db557d8f5e8fae0462d89b8">writeU64</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a single uint64_t value into the stream at the current file position. <a href="#ae6da8c6b7db557d8f5e8fae0462d89b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4ccfc2f70d9b024d7489a9e943389e">writeSLEB</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the value into the stream encoded using signed LEB128 at the current file position. <a href="#a3d4ccfc2f70d9b024d7489a9e943389e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155ed5ec938a9850383cdd2db34cbd32">writeULEB</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the value into the stream encoded using unsigned LEB128 at the current file position. <a href="#a155ed5ec938a9850383cdd2db34cbd32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2098b5e04292cab5f72108ed12e1bd">writeData</a> (llvm::ArrayRef&lt; uint8_t &gt; Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an array of uint8_t values into the stream at the current file position. <a href="#abf2098b5e04292cab5f72108ed12e1bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe1d7578ceb2fd20d24412def14805d">writeNullTerminated</a> (llvm::StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a NULL terminated C string into the stream at the current file position. <a href="#acbe1d7578ceb2fd20d24412def14805d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23334fee66fedcc03e7c74ed4295611c">fixup32</a> (uint32_t Value, uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fixup a uint32_t value at the specified offset in the stream. <a href="#a23334fee66fedcc03e7c74ed4295611c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1707b6e1ef8dd2cad56c0ec486e205">alignTo</a> (size_t Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pad with zeroes at the current file position until the current file position matches the specified alignment. <a href="#a4c1707b6e1ef8dd2cad56c0ec486e205">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1462db57acbef343fec398bfbf85391a">tell</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current offset within the file. <a href="#a1462db57acbef343fec398bfbf85391a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">llvm::raw_pwrite_stream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06839dfde8dde87851fb49485410cd97">get_stream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded943536fd3590c1c6b3ccb1dc7bbe2">getByteOrder</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">llvm::raw_pwrite_stream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b7059b8a52490bac8e2430dc27acb1">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73db8646d954a56e3d9d0cb437507b9a">ByteOrder</a></td>
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

<p>A simplified binary data writer class that doesn't require targets, target definitions, architectures, or require any other optional compile time libraries to be enabled via the build process.</p>


<p>This class needs the ability to seek to different spots in the binary stream that is produces to fixup offsets and sizes.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FileWriter() {#a63b386e2d944089795e87b32182ed9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::FileWriter::FileWriter (<a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">llvm::raw_pwrite_stream</a> &amp; S, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> B)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### FileWriter() {#a6f4ab35e164da639bfc5195aa0d00597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::FileWriter::FileWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; rhs)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FileWriter() {#ae5490307dcaf9237f4c1b8b8df433e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileWriter::~FileWriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#ad2650dd36112ef09ead6a40ba1c158e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::FileWriter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; rhs)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### alignTo() {#a4c1707b6e1ef8dd2cad56c0ec486e205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::alignTo (size_t Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pad with zeroes at the current file position until the current file position matches the specified alignment.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/structs/llvm/align"&gt;Align&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>An integer speciying the desired alignment. This does not need to be a power of two.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#ab6deec968e0067bd7e7cd91892043097">llvm::gsym::FunctionInfo::encode</a>.</p>

</div>
</div>

### fixup32() {#a23334fee66fedcc03e7c74ed4295611c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::fixup32 (uint32_t Value, uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fixup a uint32_t value at the specified offset in the stream.</p>


<p>This function will save the current file position, seek to the specified offset, overwrite the data using <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, and then restore the file position to the previous file position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The offset at which to write the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> within the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#ab6deec968e0067bd7e7cd91892043097">llvm::gsym::FunctionInfo::encode</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#acf6e5aa620d3dbd266db4b6d03388ed7">llvm::gsym::MergedFunctionsInfo::encode</a>.</p>

</div>
</div>

### get\_stream() {#a06839dfde8dde87851fb49485410cd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_pwrite_stream &amp; llvm::gsym::FileWriter::get_stream ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>

</div>
</div>

### getByteOrder() {#aded943536fd3590c1c6b3ccb1dc7bbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::gsym::FileWriter::getByteOrder ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#ab6deec968e0067bd7e7cd91892043097">llvm::gsym::FunctionInfo::encode</a>.</p>

</div>
</div>

### tell() {#a1462db57acbef343fec398bfbf85391a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t FileWriter::tell ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the current offset within the file.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The unsigned offset from the start of the file of the current file position.</p></dd>
</dl>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#ab6deec968e0067bd7e7cd91892043097">llvm::gsym::FunctionInfo::encode</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#acf6e5aa620d3dbd266db4b6d03388ed7">llvm::gsym::MergedFunctionsInfo::encode</a>.</p>

</div>
</div>

### writeData() {#abf2098b5e04292cab5f72108ed12e1bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeData (<a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write an array of uint8_t values into the stream at the current file position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>An array of values to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#ab6deec968e0067bd7e7cd91892043097">llvm::gsym::FunctionInfo::encode</a>.</p>

</div>
</div>

### writeNullTerminated() {#acbe1d7578ceb2fd20d24412def14805d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeNullTerminated (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a NULL terminated C string into the stream at the current file position.</p>


<p>The entire contents of Str will be written into the steam at the current file position and then an extra NULL termation byte will be written. It is up to the user to ensure that Str doesn't contain any NULL characters unless the additional NULL characters are desired.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Str</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>

</div>
</div>

### writeSLEB() {#a3d4ccfc2f70d9b024d7489a9e943389e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeSLEB (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the value into the stream encoded using signed LEB128 at the current file position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>.</p>

</div>
</div>

### writeU16() {#a1dcdc350144ba397db6ac8d0f0d871d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeU16 (uint16_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a single uint16_t value into the stream at the current file position.</p>


<p>The value will be byte swapped if needed to match the byte order specified during construction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>.</p>

</div>
</div>

### writeU32() {#a766e343d0ff12c414ffa59f35c1f562d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeU32 (uint32_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a single uint32_t value into the stream at the current file position.</p>


<p>The value will be byte swapped if needed to match the byte order specified during construction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#ab6deec968e0067bd7e7cd91892043097">llvm::gsym::FunctionInfo::encode</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#acf6e5aa620d3dbd266db4b6d03388ed7">llvm::gsym::MergedFunctionsInfo::encode</a>.</p>

</div>
</div>

### writeU64() {#ae6da8c6b7db557d8f5e8fae0462d89b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeU64 (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a single uint64_t value into the stream at the current file position.</p>


<p>The value will be byte swapped if needed to match the byte order specified during construction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>.</p>

</div>
</div>

### writeU8() {#a45e4989cbade2289d6496aa80c97a748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeU8 (uint8_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a single uint8_t value into the stream at the current file position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>.</p>

</div>
</div>

### writeULEB() {#a155ed5ec938a9850383cdd2db34cbd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileWriter::writeULEB (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the value into the stream encoded using unsigned LEB128 at the current file position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The value to write into the stream.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ByteOrder {#a73db8646d954a56e3d9d0cb437507b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::gsym::FileWriter::ByteOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>

</div>
</div>

### OS {#ad7b7059b8a52490bac8e2430dc27acb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_pwrite_stream&amp; llvm::gsym::FileWriter::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">FileWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/filewriter-cpp">FileWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
