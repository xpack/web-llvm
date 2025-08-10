---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/archive-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Archive.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/binary-h">llvm/Object/Binary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/error-h">llvm/Object/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/chrono-h">llvm/Support/Chrono.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/globalsymtabinfo">GlobalSymtabInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8160a3004ff47f73b842d7030269ff3d">malformedError</a> (Twine Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a> (const AbstractArchiveMemberHeader *ArMemHeader, const char *RawHeaderPtr, uint64_t Size)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, std::size_t N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a> (const T(&amp;Field)[N])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a> (Twine FieldName, const StringRef RawField, const Archive *Parent, const AbstractArchiveMemberHeader *MemHeader)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad146f206f099fa725c05238ccdccc333">getArchiveMemberOctField</a> (Twine FieldName, const StringRef RawField, const Archive *Parent, const AbstractArchiveMemberHeader *MemHeader)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d59676cde66e2b3b227b524b35f891">getGlobalSymtabLocAndSize</a> (const MemoryBufferRef &amp;Data, uint64_t GlobalSymtabOffset, const char *&amp;GlobalSymtabLoc, uint64_t &amp;Size, const char *BitMessage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a90ba7dd76e41d07e6c1cb792e0db3">appendGlobalSymbolTableInfo</a> (SmallVector&lt; GlobalSymtabInfo &gt; &amp;SymtabInfos, const char *GlobalSymtabLoc, uint64_t Size)</td>
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

### appendGlobalSymbolTableInfo() {#a59a90ba7dd76e41d07e6c1cb792e0db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void appendGlobalSymbolTableInfo (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/globalsymtabinfo">GlobalSymtabInfo</a> &gt; &amp; SymtabInfos, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * GlobalSymtabLoc, uint64_t Size)</td>
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



<p>Definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4ec2abec8101a7b16ee520e882cc7d34">llvm::support::endian::read64be</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archive/#aa44b94c95310ecd69cb194904f795b5b">llvm::object::Archive::SymbolTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>.</p>

</div>
</div>

### createMemberHeaderParseError() {#af194271b77c030b86d1f22f523e7f048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error createMemberHeaderParseError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader">AbstractArchiveMemberHeader</a> * ArMemHeader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RawHeaderPtr, uint64_t Size)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5379c20deca096e73006138ba387f171">llvm::object::Binary::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#ae73dd2f342d8dbbf4a1145fc8c8798de">llvm::object::AbstractArchiveMemberHeader::getName</a>, <a href="#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#ae54b3190e013b4c17e9dd0e82fb8ec2e">llvm::object::BigArchiveMemberHeader::BigArchiveMemberHeader</a>.</p>

</div>
</div>

### getArchiveMemberDecField() {#af0b0d5a3c44e6c8bf449fcbd3cc1224b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; getArchiveMemberDecField (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> FieldName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RawField, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader">AbstractArchiveMemberHeader</a> * MemHeader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a8e3cae5601471f6b6ce12a153183ee8b">llvm::object::AbstractArchiveMemberHeader::getOffset</a>, <a href="#a8160a3004ff47f73b842d7030269ff3d">malformedError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a8601675aad561f5f3467eb4a49c95794">llvm::object::AbstractArchiveMemberHeader::getGID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#aa0994633a7dc598ab379d4dcfa99bb17">llvm::object::AbstractArchiveMemberHeader::getLastModified</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#adfe40bee08ac4f93c61808e0aa9e3308">llvm::object::BigArchiveMemberHeader::getNextOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#aa12e214fe9eef659a3935afbac7b05fb">llvm::object::BigArchiveMemberHeader::getRawNameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#ace1855f7759a2a9be5299cdecc51c477">llvm::object::ArchiveMemberHeader::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a19fbab288c38cba1ba49b9093ce87995">llvm::object::BigArchiveMemberHeader::getSize</a> and <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a366b06f6bd50440e9b1c85f537aec7ec">llvm::object::AbstractArchiveMemberHeader::getUID</a>.</p>

</div>
</div>

### getArchiveMemberOctField() {#ad146f206f099fa725c05238ccdccc333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; getArchiveMemberOctField (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> FieldName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RawField, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader">AbstractArchiveMemberHeader</a> * MemHeader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a8e3cae5601471f6b6ce12a153183ee8b">llvm::object::AbstractArchiveMemberHeader::getOffset</a>, <a href="#a8160a3004ff47f73b842d7030269ff3d">malformedError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a5b041d7f0753dfc105eec7d7a34d5bed">llvm::object::AbstractArchiveMemberHeader::getAccessMode</a>.</p>

</div>
</div>

### getFieldRawString() {#a896c0342b10ed46345456bd263e5a7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, std::size_t N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getFieldRawString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T(&amp;) Field=[N])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="#a73d59676cde66e2b3b227b524b35f891">getGlobalSymtabLocAndSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#adfe40bee08ac4f93c61808e0aa9e3308">llvm::object::BigArchiveMemberHeader::getNextOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#af5f1be3aead208648e9c3e7fcdc82bee">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::getRawAccessMode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a01dfe67672812fbb3930167c6b288d1e">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::getRawLastModified</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#aa12e214fe9eef659a3935afbac7b05fb">llvm::object::BigArchiveMemberHeader::getRawNameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a1e4072ec96d4b728f231d52d847b7c25">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::getRawUID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#ace1855f7759a2a9be5299cdecc51c477">llvm::object::ArchiveMemberHeader::getSize</a> and <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a19fbab288c38cba1ba49b9093ce87995">llvm::object::BigArchiveMemberHeader::getSize</a>.</p>

</div>
</div>

### getGlobalSymtabLocAndSize() {#a73d59676cde66e2b3b227b524b35f891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error getGlobalSymtabLocAndSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &amp; Data, uint64_t GlobalSymtabOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *&amp; GlobalSymtabLoc, uint64_t &amp; Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BitMessage)</td>
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



<p>Definition at line 1286 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a>, <a href="#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/object/bigarmemhdrtype/#aa832b8b6208cc89d7c19c206fcc6c2de">llvm::object::BigArMemHdrType::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>.</p>

</div>
</div>

### malformedError() {#a8160a3004ff47f73b842d7030269ff3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error malformedError (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Msg)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#ae54b3190e013b4c17e9dd0e82fb8ec2e">llvm::object::BigArchiveMemberHeader::BigArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a77b750f0deb484099d9f4f3539bda353">checkLinkerOptCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a58bd45157985a622dba76ecef6375f4d">llvm::object::MachOObjectFile::checkSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a9537162135cca043a3b82f0df2816ed7">llvm::object::Archive::Child::Child</a>, <a href="#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad53613e81c10091896d73287938ab8be">llvm::object::Archive::ec_symbols</a>, <a href="#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="#ad146f206f099fa725c05238ccdccc333">getArchiveMemberOctField</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ad107a2e9bf01094f9564019267eace1d">llvm::object::MachOObjectFile::getChainedFixupsHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a11261ec56e31921149aa022482d80e7e">llvm::object::MachOObjectFile::getDyldChainedFixupTargets</a>, <a href="#a73d59676cde66e2b3b227b524b35f891">getGlobalSymtabLocAndSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a137ad5829c3f2470a0da63800c59385e">llvm::object::Archive::Child::getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a990a2cc1b018140f8dde6e1a8ad42182">llvm::object::ArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a1a18707996459de69e40ab867eeee801">llvm::object::MachOObjectFile::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a79ff60972cb2fd27ac7280c9e5052d4a">llvm::object::MachOObjectFile::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a35b89b3d8775f01eeeb4e36769e2b435">llvm::object::MachOObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/#a66ced5c57cafe11823df6917a866b17f">llvm::object::MachOUniversalBinary::MachOUniversalBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/object/exportentry/#a0ec56e47067ae8d2239c5da9d6ae8418">llvm::object::ExportEntry::moveNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machobindentry/#a4a875fa809c0df5dff3223d539ae4c7c">llvm::object::MachOBindEntry::moveNext</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machorebaseentry/#aa36d5eb1318336e34265a7c2cc87b604">llvm::object::MachORebaseEntry::moveNext</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
