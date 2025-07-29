---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/minidumpfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MinidumpFile` Class

<p>A class providing access to the contents of a minidump file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::MinidumpFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">llvm/Object/Minidump.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9a91d5283c180a6e0a4f30540194fe">FallibleMemory64Iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/fallible-iterator">llvm::fallible_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memory64iterator">Memory64Iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0fea94893e4efd724c1aef5689ec874">MinidumpFile</a> (MemoryBufferRef Source, const minidump::Header &amp;Header, ArrayRef&lt; minidump::Directory &gt; Streams, DenseMap&lt; minidump::StreamType, std::size_t &gt; StreamMap, std::vector&lt; minidump::Directory &gt; ExceptionStreams)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/header">minidump::Header</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c5b98eceac8b14b095c9c694532fe4f">header</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the contents of the minidump header. <a href="#a6c5b98eceac8b14b095c9c694532fe4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6a28bdbe9f2cd8a6ecccf7e5c25ff4">streams</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of streams (stream directory entries) in this file. <a href="#aca6a28bdbe9f2cd8a6ecccf7e5c25ff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a544c2983fe03425d0dfe7b5ff0b59d9e">getRawStream</a> (const minidump::Directory &amp;Stream) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the raw contents of the stream given by the directory entry. <a href="#a544c2983fe03425d0dfe7b5ff0b59d9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0ea3a2b3ccf8f1d4b82ecf8c6924cf">getRawStream</a> (minidump::StreamType Type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the raw contents of the stream of the given type, or std::nullopt if the file does not contain a stream of this type. <a href="#a8b0ea3a2b3ccf8f1d4b82ecf8c6924cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbbd8e0dfd101eb09f1c39cdd0f29a1">getRawData</a> (minidump::LocationDescriptor Desc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the raw contents of an object given by the LocationDescriptor. <a href="#a8cbbd8e0dfd101eb09f1c39cdd0f29a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7de35b1ad345a06e1d7c38dc51d94fb">getString</a> (size_t Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minidump string at the given offset. <a href="#aa7de35b1ad345a06e1d7c38dc51d94fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/systeminfo">minidump::SystemInfo</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7450bd48a110b6b5048d13e3661f50b2">getSystemInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the contents of the SystemInfo stream, cast to the appropriate type. <a href="#a7450bd48a110b6b5048d13e3661f50b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/module">minidump::Module</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0dde9957b6ab8f9e75a60791590846c">getModuleList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the module list embedded in the ModuleList stream. <a href="#ac0dde9957b6ab8f9e75a60791590846c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/thread">minidump::Thread</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e2bc96f3263580c61d7d418a6fb1c9">getThreadList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the thread list embedded in the ThreadList stream. <a href="#ac5e2bc96f3263580c61d7d418a6fb1c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/exceptionstream">minidump::ExceptionStream</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2d260d8171013121787f6fa0c985f3">getExceptionStream</a> (minidump::Directory Directory) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the contents of the Exception stream. <a href="#a2f2d260d8171013121787f6fa0c985f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/exceptionstream">minidump::ExceptionStream</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aedfe998a29953de6b95350183cbdf5">getExceptionStream</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the first exception stream in the file. <a href="#a6aedfe998a29953de6b95350183cbdf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/memorydescriptor">minidump::MemoryDescriptor</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0afb22f7ce895a7c0478a96fb72abf">getMemoryList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of descriptors embedded in the MemoryList stream. <a href="#abb0afb22f7ce895a7c0478a96fb72abf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/memory64listheader">minidump::Memory64ListHeader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391de1fcfed6e45ae43857dc2d75efda">getMemoryList64Header</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the header to the memory 64 list stream. <a href="#a391de1fcfed6e45ae43857dc2d75efda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/exceptionstreamsiterator">ExceptionStreamsIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c26205368ee8bf686e666dc15a3837">getExceptionStreams</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator that reads each exception stream independently. <a href="#a94c26205368ee8bf686e666dc15a3837">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#abf9a91d5283c180a6e0a4f30540194fe">FallibleMemory64Iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79b94d312ad221c9d2b49357633a223">getMemory64List</a> (Error &amp;Err) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator that pairs each descriptor with it's respective content from the Memory64List stream. <a href="#ad79b94d312ad221c9d2b49357633a223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memoryinfoiterator">MemoryInfoIterator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0999878cf807ab0c674f1d3eadcc3ecb">getMemoryInfoList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of descriptors embedded in the MemoryInfoList stream. <a href="#a0999878cf807ab0c674f1d3eadcc3ecb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9546d124adf2d611fb8ba51f4ed6fcc2">getData</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2e2b3077032b436f9b0650ad654227f">getStreamFromDirectory</a> (minidump::Directory Directory) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the stream of the given type, cast to the appropriate type. <a href="#ac2e2b3077032b436f9b0650ad654227f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9003dcce9fced7327f0dbe0ddd22cd25">getStream</a> (minidump::StreamType Stream) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the stream of the given type, cast to the appropriate type. <a href="#a9003dcce9fced7327f0dbe0ddd22cd25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06c1df97029a04d0157f2d09282fd427">getListStream</a> (minidump::StreamType Stream) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the contents of a stream which contains a list of fixed-size items, prefixed by the list size. <a href="#a06c1df97029a04d0157f2d09282fd427">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/header">minidump::Header</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfd11a3d7d47ca1d1daa81a572ba650">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ec18048e229e727d3fa1bed36b8453">Streams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a>, std::size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc73574b8ffdea69c2eadfd85b98e283">StreamMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff50eea87995a9db3a8cdc5d71c45b39">ExceptionStreams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile">MinidumpFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d4bfb09d6c352cfd4373d1e71ff8c8">create</a> (MemoryBufferRef Source)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a new <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile">MinidumpFile</a> object from the given memory buffer. <a href="#af4d4bfb09d6c352cfd4373d1e71ff8c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba774a0bf438aa89966d734fe263292">classof</a> (const Binary *B)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9743f4a51f6fcb0e5d84e203e86eed3">createError</a> (StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae3af51ede3deb1d8b2f302a25cf456">createEOFError</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e25f090dbca68ae276bad654edeeb24">getDataSlice</a> (ArrayRef&lt; uint8_t &gt; Data, uint64_t Offset, uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a slice of the given data array, with bounds checking. <a href="#a3e25f090dbca68ae276bad654edeeb24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa94951b800909bf5bd4b8aa8baf1573c">getDataSliceAs</a> (ArrayRef&lt; uint8_t &gt; Data, uint64_t Offset, uint64_t Count) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the slice of the given data array as an array of objects of the given type. <a href="#aa94951b800909bf5bd4b8aa8baf1573c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class providing access to the contents of a minidump file.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FallibleMemory64Iterator {#abf9a91d5283c180a6e0a4f30540194fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::MinidumpFile::FallibleMemory64Iterator =  llvm::fallible_iterator&lt;Memory64Iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MinidumpFile() {#ae0fea94893e4efd724c1aef5689ec874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::MinidumpFile::MinidumpFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/header">minidump::Header</a> &amp; Header, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> &gt; Streams, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a>, std::size_t &gt; StreamMap, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> &gt; ExceptionStreams)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExceptionStream() {#a2f2d260d8171013121787f6fa0c985f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const minidump::ExceptionStream &amp; &gt; llvm::object::MinidumpFile::getExceptionStream (<a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> Directory)</td>
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

<p>Returns the contents of the Exception stream.</p>


<p>An error is returned if the associated stream is smaller than the size of the ExceptionStream structure. Or the directory supplied is not of kind exception stream.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/minidump/directory/#a13a26a23295f6783a46d9dcd6e2e27c0">llvm::minidump::Directory::Type</a>.</p>

</div>
</div>

### getExceptionStream() {#a6aedfe998a29953de6b95350183cbdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const minidump::ExceptionStream &amp; &gt; llvm::object::MinidumpFile::getExceptionStream ()</td>
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

<p>Returns the first exception stream in the file.</p>


<p>An error is returned if the associated stream is smaller than the size of the ExceptionStream structure. Or the directory supplied is not of kind exception stream.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<p>Reference <a href="#a94c26205368ee8bf686e666dc15a3837">getExceptionStreams</a>.</p>

</div>
</div>

### getExceptionStreams() {#a94c26205368ee8bf686e666dc15a3837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; llvm::object::MinidumpFile::ExceptionStreamsIterator &gt; MinidumpFile::getExceptionStreams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator that reads each exception stream independently.</p>


<p>The contents of the exception strema are not validated before being read, an error will be returned if the stream is not large enough to contain an exception stream, or if the stream points beyond the end of the file.</p>


<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a6aedfe998a29953de6b95350183cbdf5">getExceptionStream</a>.</p>

</div>
</div>

### getMemory64List() {#ad79b94d312ad221c9d2b49357633a223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MinidumpFile::FallibleMemory64Iterator &gt; MinidumpFile::getMemory64List (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator that pairs each descriptor with it's respective content from the Memory64List stream.</p>


<p>An error is returned if the file does not contain a Memory64List stream, or if the descriptor data is unreadable.</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memory64iterator/#a60a07d51aefd93427f81d8129f292ce2">llvm::object::MinidumpFile::Memory64Iterator::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/fallible-iterator/#a1885ab71cce9418d89aa8ca952021241">llvm::fallible_iterator&lt; Memory64Iterator &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memory64iterator/#adb63fbdcb123b88737c5dd8703782c91">llvm::object::MinidumpFile::Memory64Iterator::end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="#a391de1fcfed6e45ae43857dc2d75efda">getMemoryList64Header</a>, <a href="#a544c2983fe03425d0dfe7b5ff0b59d9e">getRawStream</a>, <a href="/web-llvm/docs/api/classes/llvm/fallible-iterator/#a5e324def628fb970ffc152836f145972">llvm::fallible_iterator&lt; Memory64Iterator &gt;::itr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getMemoryInfoList() {#a0999878cf807ab0c674f1d3eadcc3ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; iterator_range&lt; MinidumpFile::MemoryInfoIterator &gt; &gt; MinidumpFile::getMemoryInfoList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the list of descriptors embedded in the MemoryInfoList stream.</p>


<p>The descriptors provide properties (e.g. permissions) of interesting regions of memory at the time the minidump was taken. An error is returned if the file does not contain this stream, or if the stream is not large enough to contain the number of memory descriptors declared in the stream header. The consistency of the MemoryInfoList entries themselves is not checked in any way.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#a544c2983fe03425d0dfe7b5ff0b59d9e">getRawStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### getMemoryList() {#abb0afb22f7ce895a7c0478a96fb72abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; minidump::MemoryDescriptor &gt; &gt; llvm::object::MinidumpFile::getMemoryList ()</td>
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

<p>Returns the list of descriptors embedded in the MemoryList stream.</p>


<p>The descriptors provide the content of interesting regions of memory at the time the minidump was taken. An error is returned if the file does not contain this stream, or if the stream is not large enough to contain the number of memory descriptors declared in the stream header. The consistency of the MemoryDescriptor entries themselves is not checked in any way.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getMemoryList64Header() {#a391de1fcfed6e45ae43857dc2d75efda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; minidump::Memory64ListHeader &gt; llvm::object::MinidumpFile::getMemoryList64Header ()</td>
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

<p>Returns the header to the memory 64 list stream.</p>


<p>An error is returned if the file does not contain this stream.</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<p>Referenced by <a href="#ad79b94d312ad221c9d2b49357633a223">getMemory64List</a>.</p>

</div>
</div>

### getModuleList() {#ac0dde9957b6ab8f9e75a60791590846c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; minidump::Module &gt; &gt; llvm::object::MinidumpFile::getModuleList ()</td>
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

<p>Returns the module list embedded in the ModuleList stream.</p>


<p>An error is returned if the file does not contain this stream, or if the stream is not large enough to contain the number of modules declared in the stream header. The consistency of the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> entries themselves is not checked in any way.</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getRawData() {#a8cbbd8e0dfd101eb09f1c39cdd0f29a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; llvm::object::MinidumpFile::getRawData (<a href="/web-llvm/docs/api/structs/llvm/minidump/locationdescriptor">minidump::LocationDescriptor</a> Desc)</td>
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

<p>Returns the raw contents of an object given by the LocationDescriptor.</p>


<p>An error is returned if the descriptor points outside of the minidump file.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>.</p>

</div>
</div>

### getRawStream() {#a544c2983fe03425d0dfe7b5ff0b59d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; llvm::object::MinidumpFile::getRawStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> &amp; Stream)</td>
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

<p>Returns the raw contents of the stream given by the directory entry.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidump/locationdescriptor/#a99d42fe42cfc2e5e42f43958589a7106">llvm::minidump::LocationDescriptor::DataSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/directory/#a0274e66af4b8081e718c87e75bd9be9b">llvm::minidump::Directory::Location</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/locationdescriptor/#a1ce0eaa19e2c9171a00949407780f9c5">llvm::minidump::LocationDescriptor::RVA</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>.</p>


<p>Referenced by <a href="#ad79b94d312ad221c9d2b49357633a223">getMemory64List</a>, <a href="#a0999878cf807ab0c674f1d3eadcc3ecb">getMemoryInfoList</a> and <a href="#a8b0ea3a2b3ccf8f1d4b82ecf8c6924cf">getRawStream</a>.</p>

</div>
</div>

### getRawStream() {#a8b0ea3a2b3ccf8f1d4b82ecf8c6924cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ArrayRef&lt; uint8_t &gt; &gt; MinidumpFile::getRawStream (<a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the raw contents of the stream of the given type, or std::nullopt if the file does not contain a stream of this type.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>


<p>Reference <a href="#a544c2983fe03425d0dfe7b5ff0b59d9e">getRawStream</a>.</p>

</div>
</div>

### getString() {#aa7de35b1ad345a06e1d7c38dc51d94fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; MinidumpFile::getString (size_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minidump string at the given offset.</p>


<p>An error is returned if we fail to parse the string, or the string is invalid <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a>.</p>


<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getSystemInfo() {#a7450bd48a110b6b5048d13e3661f50b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const minidump::SystemInfo &amp; &gt; llvm::object::MinidumpFile::getSystemInfo ()</td>
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

<p>Returns the contents of the SystemInfo stream, cast to the appropriate type.</p>


<p>An error is returned if the file does not contain this stream, or the stream is smaller than the size of the SystemInfo structure. The internal consistency of the stream is not checked in any way.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getThreadList() {#ac5e2bc96f3263580c61d7d418a6fb1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; minidump::Thread &gt; &gt; llvm::object::MinidumpFile::getThreadList ()</td>
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

<p>Returns the thread list embedded in the ThreadList stream.</p>


<p>An error is returned if the file does not contain this stream, or if the stream is not large enough to contain the number of threads declared in the stream header. The consistency of the Thread entries themselves is not checked in any way.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### header() {#a6c5b98eceac8b14b095c9c694532fe4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const minidump::Header &amp; llvm::object::MinidumpFile::header ()</td>
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

<p>Returns the contents of the minidump header.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### streams() {#aca6a28bdbe9f2cd8a6ecccf7e5c25ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; minidump::Directory &gt; llvm::object::MinidumpFile::streams ()</td>
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

<p>Returns the list of streams (stream directory entries) in this file.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getData() {#a9546d124adf2d611fb8ba51f4ed6fcc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; llvm::object::MinidumpFile::getData ()</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getListStream() {#a06c1df97029a04d0157f2d09282fd427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; T &gt; &gt; llvm::object::MinidumpFile::getListStream (<a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a> Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the contents of a stream which contains a list of fixed-size items, prefixed by the list size.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getStream() {#a9003dcce9fced7327f0dbe0ddd22cd25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const T &amp; &gt; llvm::object::MinidumpFile::getStream (<a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280">minidump::StreamType</a> Stream)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the stream of the given type, cast to the appropriate type.</p>


<p>Checks that the stream is large enough to hold an object of this type.</p>


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getStreamFromDirectory() {#ac2e2b3077032b436f9b0650ad654227f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const T &amp; &gt; llvm::object::MinidumpFile::getStreamFromDirectory (<a href="/web-llvm/docs/api/structs/llvm/minidump/directory">minidump::Directory</a> Directory)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the stream of the given type, cast to the appropriate type.</p>


<p>Checks that the stream is large enough to hold an object of this type.</p>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ExceptionStreams {#aff50eea87995a9db3a8cdc5d71c45b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;minidump::Directory&gt; llvm::object::MinidumpFile::ExceptionStreams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### Header {#accfd11a3d7d47ca1d1daa81a572ba650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const minidump::Header&amp; llvm::object::MinidumpFile::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### StreamMap {#abc73574b8ffdea69c2eadfd85b98e283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;minidump::StreamType, std::size_t&gt; llvm::object::MinidumpFile::StreamMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### Streams {#a16ec18048e229e727d3fa1bed36b8453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;minidump::Directory&gt; llvm::object::MinidumpFile::Streams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a9ba774a0bf438aa89966d734fe263292}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::MinidumpFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * B)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>.</p>

</div>
</div>

### create() {#af4d4bfb09d6c352cfd4373d1e71ff8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MinidumpFile &gt; &gt; MinidumpFile::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source)</td>
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

<p>Construct a new <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile">MinidumpFile</a> object from the given memory buffer.</p>


<p>Returns an error if this file cannot be identified as a minidump file, or if its contents are badly corrupted (i.e. we cannot read the stream directory).</p>


<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#a5fda203d4efac195c9e470dd41d95969">llvm::minidump::Header::MagicSignature</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#a8f79f27fcbb8c6ebd5e56cecdf99137b">llvm::minidump::Header::MagicVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#a255d6e4cb11c68599f007278b07bdf86">llvm::minidump::Header::NumberOfStreams</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#aa70f2fc85ea3ca571c7d56f9ad418018">llvm::minidump::Header::Signature</a>, <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#af2999a3d5f4d70afeb7974c9c26396f8">llvm::minidump::Header::StreamDirectoryRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>, <a href="/web-llvm/docs/api/namespaces/llvm/minidump/#aa8cbdda4c517e8f73a3f150077295280a92e592d90b9548016776a6fb68dccded">llvm::minidump::Unused</a> and <a href="/web-llvm/docs/api/structs/llvm/minidump/header/#a41eac288e7f9f851e330d13f5c333b07">llvm::minidump::Header::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createEOFError() {#a5ae3af51ede3deb1d8b2f302a25cf456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::MinidumpFile::createEOFError ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### createError() {#af9743f4a51f6fcb0e5d84e203e86eed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::MinidumpFile::createError (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

### getDataSlice() {#a3e25f090dbca68ae276bad654edeeb24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; MinidumpFile::getDataSlice (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint64_t Offset, uint64_t Size)</td>
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

<p>Return a slice of the given data array, with bounds checking.</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a>.</p>

</div>
</div>

### getDataSliceAs() {#aa94951b800909bf5bd4b8aa8baf1573c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; T &gt; &gt; llvm::object::MinidumpFile::getDataSliceAs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint64_t Offset, uint64_t Count)</td>
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

<p>Return the slice of the given data array as an array of objects of the given type.</p>


<p>The function checks that the input array is large enough to contain the correct number of objects of the given type.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/minidump-h">Minidump.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/minidump-cpp">Minidump.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
