---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/archivewriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ArchiveWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">llvm/Object/ArchiveWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/magic-h">llvm/BinaryFormat/Magic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coff-h">llvm/Object/COFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/coffimportfile-h">llvm/Object/COFFImportFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/error-h">llvm/Object/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">llvm/Object/IRObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">llvm/Object/XCOFFObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">llvm/Support/SmallVectorMemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cerrno&gt;
#include &lt;map&gt;
#include &lt;unistd.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-archivewriter-cpp-">anonymous{ArchiveWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/symmap">SymMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-archivewriter-cpp-/memberdata">MemberData</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a> (raw_ostream &amp;OS, T Data, unsigned Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1006d6edecba6ccd85680339884fd276">isDarwin</a> (object::Archive::Kind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865ced7028dc9ae9e8118586cf8901cc">isAIXBigArchive</a> (object::Archive::Kind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9268243880dea3ade98f24e7bd531038">isCOFFArchive</a> (object::Archive::Kind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ba542da3cf5a91c1df4fd029b061cb">isBSDLike</a> (object::Archive::Kind Kind)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa9f638c7ae7fdd206a6c60e26bef9751">print</a> (raw_ostream &amp;Out, object::Archive::Kind Kind, T Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf4c0b08270ecda12b4b183b52b7a2ea">printLE</a> (raw_ostream &amp;Out, T Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a48633636bbcf3d359e1c02b6aba4a5">printRestOfMemberHeader</a> (raw_ostream &amp;Out, const sys::TimePoint&lt; std::chrono::seconds &gt; &amp;ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaeb6f00c0c03b98ec4a12da525e74b0">printGNUSmallMemberHeader</a> (raw_ostream &amp;Out, StringRef Name, const sys::TimePoint&lt; std::chrono::seconds &gt; &amp;ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52904074f52a694e289a93b1634553c3">printBSDMemberHeader</a> (raw_ostream &amp;Out, uint64_t Pos, StringRef Name, const sys::TimePoint&lt; std::chrono::seconds &gt; &amp;ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea934139e960daaca81f19ee42fefb9a">printBigArchiveMemberHeader</a> (raw_ostream &amp;Out, StringRef Name, const sys::TimePoint&lt; std::chrono::seconds &gt; &amp;ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size, uint64_t PrevOffset, uint64_t NextOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72ef2b9a4e9866b2d57f5e5270f57fb">useStringTable</a> (bool Thin, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2edaf906058e05bac72b0cffa0ac88">is64BitKind</a> (object::Archive::Kind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a> (raw_ostream &amp;Out, uint64_t Pos, raw_ostream &amp;StringTable, StringMap&lt; uint64_t &gt; &amp;MemberNames, object::Archive::Kind Kind, bool Thin, const NewArchiveMember &amp;M, sys::TimePoint&lt; std::chrono::seconds &gt; ModTime, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static MemberData</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be3fea922116aa226fc27bde3419182">computeStringTable</a> (StringRef Names)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0edd35207e47a9fb4d484238d3172e82">now</a> (bool Deterministic)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903f7954a46ba31474ad9e0c7ccfbed3">isArchiveSymbol</a> (const object::BasicSymbolRef &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0781a0e5a09042c7bf27104d1f86793a">printNBits</a> (raw_ostream &amp;Out, object::Archive::Kind Kind, uint64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d245de2307b5540582f87e3efa63a3c">computeSymbolTableSize</a> (object::Archive::Kind Kind, uint64_t NumSyms, uint64_t OffsetSize, uint64_t StringTableSize, uint32_t *Padding=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3cab2e73302be816886e9c0ba73746">computeSymbolMapSize</a> (uint64_t NumObj, SymMap &amp;SymMap, uint32_t *Padding=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146d10ed8f323a076ba12323de86902f">computeECSymbolsSize</a> (SymMap &amp;SymMap, uint32_t *Padding=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a> (raw_ostream &amp;Out, object::Archive::Kind Kind, bool Deterministic, uint64_t Size, uint64_t PrevMemberOffset=0, uint64_t NextMemberOffset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a> (object::Archive::Kind Kind, uint64_t NumMembers, uint64_t StringMemberSize, uint64_t NumSyms, uint64_t SymNamesSize, SymMap *SymMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838e4f1a36cc927704247e621bcf0204">getSymbolicFile</a> (MemoryBufferRef Buf, LLVMContext &amp;Context, object::Archive::Kind Kind, function_ref&lt; void(Error)&gt; Warn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a389fcf3a6cc81cb007bfcf9f253c5">is64BitSymbolicFile</a> (const SymbolicFile *SymObj)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AuxiliaryHeader&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a605d26c625db977423d136525feecb89">getAuxMaxAlignment</a> (uint16_t AuxHeaderSize, AuxiliaryHeader *AuxHeader, uint16_t Log2OfMaxAlign)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a> (SymbolicFile *SymObj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a> (raw_ostream &amp;Out, object::Archive::Kind Kind, bool Deterministic, ArrayRef&lt; MemberData &gt; Members, StringRef StringTable, uint64_t MembersOffset, unsigned NumSyms, uint64_t PrevMemberOffset=0, uint64_t NextMemberOffset=0, bool Is64Bit=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a> (raw_ostream &amp;Out, object::Archive::Kind Kind, bool Deterministic, ArrayRef&lt; MemberData &gt; Members, SymMap &amp;SymMap, uint64_t MembersOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a> (raw_ostream &amp;Out, object::Archive::Kind Kind, bool Deterministic, ArrayRef&lt; MemberData &gt; Members, SymMap &amp;SymMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832ff21f008f041dd1708c083417eb74">isECObject</a> (object::SymbolicFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb13b41609de563860e9b86fe296cd84">isAnyArm64COFF</a> (object::SymbolicFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6655075d2bf4bb40a6a0930c1a0cda">isImportDescriptor</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a> (SymbolicFile *Obj, uint16_t Index, raw_ostream &amp;SymNames, SymMap *SymMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; MemberData &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a> (raw_ostream &amp;StringTable, raw_ostream &amp;SymNames, object::Archive::Kind Kind, bool Thin, bool Deterministic, SymtabWritingMode NeedSymbols, SymMap *SymMap, LLVMContext &amp;Context, ArrayRef&lt; NewArchiveMember &gt; NewMembers, std::optional&lt; bool &gt; IsEC, function_ref&lt; void(Error)&gt; Warn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708c1755c910c2420229a493dfd3b20b">Log2OfAIXPageSize</a> = 12</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d9478fb7e03754c8beb1f0bb2e0843">MinBigArchiveMemDataAlign</a> = 2</td>
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

### computeECSymbolsSize() {#a146d10ed8f323a076ba12323de86902f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t computeECSymbolsSize (<a href="/web-llvm/docs/api/structs/symmap">SymMap</a> &amp; SymMap, uint32_t * Padding=nullptr)</td>
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



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/symmap/#a1da8b4bf1fb5b60a5aa6054455c846a0">SymMap::ECMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a> and <a href="#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a>.</p>

</div>
</div>

### computeHeadersSize() {#a356355a0c98d7b39551d7473665510f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t computeHeadersSize (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, uint64_t NumMembers, uint64_t StringMemberSize, uint64_t NumSyms, uint64_t SymNamesSize, <a href="/web-llvm/docs/api/structs/symmap">SymMap</a> * SymMap)</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#a146d10ed8f323a076ba12323de86902f">computeECSymbolsSize</a>, <a href="#aaf3cab2e73302be816886e9c0ba73746">computeSymbolMapSize</a>, <a href="#a8d245de2307b5540582f87e3efa63a3c">computeSymbolTableSize</a>, <a href="/web-llvm/docs/api/structs/symmap/#a1da8b4bf1fb5b60a5aa6054455c846a0">SymMap::ECMap</a>, <a href="#acd2edaf906058e05bac72b0cffa0ac88">is64BitKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### computeMemberData() {#a98ad0137a31b38aa7b278f7cc52c4f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; MemberData &gt; &gt; computeMemberData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; StringTable, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; SymNames, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, bool Thin, bool Deterministic, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc600b4b175aae20e7ad49f58a97e">SymtabWritingMode</a> NeedSymbols, <a href="/web-llvm/docs/api/structs/symmap">SymMap</a> * SymMap, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a> &gt; NewMembers, std::optional&lt; bool &gt; IsEC, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
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



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f24ae5aca75f26072ec2665cd5f24d3">llvm::alignToPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>, <a href="#a838e4f1a36cc927704247e621bcf0204">getSymbolicFile</a>, <a href="#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>, <a href="#a865ced7028dc9ae9e8118586cf8901cc">isAIXBigArchive</a>, <a href="#afb13b41609de563860e9b86fe296cd84">isAnyArm64COFF</a>, <a href="#a9268243880dea3ade98f24e7bd531038">isCOFFArchive</a>, <a href="#a1006d6edecba6ccd85680339884fd276">isDarwin</a>, <a href="#a832ff21f008f041dd1708c083417eb74">isECObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ae56b46642bec8e141cc7aff486aaaf2d">llvm::object::Archive::MaxMemberSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc600b4b175aae20e7ad49f58a97eaefec6932c057109f69458cec4657d4c5">llvm::NoSymtab</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="#aea934139e960daaca81f19ee42fefb9a">printBigArchiveMemberHeader</a>, <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7e0c6b3661b9c9f048aaef620463f1bc">llvm::sys::toTimePoint</a> and <a href="/web-llvm/docs/api/structs/symmap/#a754a8232906949e759f7f2d231f93595">SymMap::UseECMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### computeStringTable() {#a5be3fea922116aa226fc27bde3419182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberData computeStringTable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Names)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### computeSymbolMapSize() {#aaf3cab2e73302be816886e9c0ba73746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t computeSymbolMapSize (uint64_t NumObj, <a href="/web-llvm/docs/api/structs/symmap">SymMap</a> &amp; SymMap, uint32_t * Padding=nullptr)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/symmap/#ac3e5452193f29d245056cc8e4a63aaf8">SymMap::Map</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a> and <a href="#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a>.</p>

</div>
</div>

### computeSymbolTableSize() {#a8d245de2307b5540582f87e3efa63a3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t computeSymbolTableSize (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, uint64_t NumSyms, uint64_t OffsetSize, uint64_t StringTableSize, uint32_t * Padding=nullptr)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a865ced7028dc9ae9e8118586cf8901cc">isAIXBigArchive</a>, <a href="#a44ba542da3cf5a91c1df4fd029b061cb">isBSDLike</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a> and <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>.</p>

</div>
</div>

### getAuxMaxAlignment() {#a605d26c625db977423d136525feecb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AuxiliaryHeader&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t getAuxMaxAlignment (uint16_t AuxHeaderSize, AuxiliaryHeader * AuxHeader, uint16_t Log2OfMaxAlign)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#a708c1755c910c2420229a493dfd3b20b">Log2OfAIXPageSize</a>, <a href="#a59d9478fb7e03754c8beb1f0bb2e0843">MinBigArchiveMemDataAlign</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>.</p>


<p>Referenced by <a href="#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>.</p>

</div>
</div>

### getMemberAlignment() {#ae8d3f159178a82a1a29163a8d80070d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getMemberAlignment (<a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> * SymObj)</td>
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



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#a730b0169e99be44f0a295ec3d3642467">llvm::object::XCOFFFileHeader32::AuxHeaderSize</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#a0ec1f9c5cb12549ff9504c765a78f8ee">llvm::object::XCOFFFileHeader64::AuxHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a14b00595211ef1000d4a542193fb145c">llvm::object::XCOFFObjectFile::auxiliaryHeader32</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a665a053ea13974dd63d7a9d4b352a968">llvm::object::XCOFFObjectFile::auxiliaryHeader64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a5b7e829b257d3ddebc7532bc2633c918">llvm::object::XCOFFObjectFile::fileHeader32</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a19f13af7b6d6631c60f80c484f548c56">llvm::object::XCOFFObjectFile::fileHeader64</a>, <a href="#a605d26c625db977423d136525feecb89">getAuxMaxAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ac446bd686a2dd61629879727edb97f3a">llvm::object::XCOFFObjectFile::is64Bit</a>, <a href="#a708c1755c910c2420229a493dfd3b20b">Log2OfAIXPageSize</a> and <a href="#a59d9478fb7e03754c8beb1f0bb2e0843">MinBigArchiveMemDataAlign</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>.</p>

</div>
</div>

### getSymbolicFile() {#a838e4f1a36cc927704247e621bcf0204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; SymbolicFile &gt; &gt; getSymbolicFile (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buf, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; Warn)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50">llvm::file_magic::bitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#abfda2a40879c19a80434914b8a55ce42">llvm::object::SymbolicFile::isSymbolicFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">llvm::object::Archive::K_BSD</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">llvm::object::Archive::K_COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8">llvm::object::Archive::K_DARWIN</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">llvm::object::Archive::K_DARWIN64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">llvm::object::Archive::K_GNU</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">llvm::object::Archive::K_GNU64</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>.</p>

</div>
</div>

### getSymbols() {#a1f4394e4fc8872fa8f2a5baca5b3cc4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; unsigned &gt; &gt; getSymbols (<a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> * Obj, uint16_t Index, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; SymNames, <a href="/web-llvm/docs/api/structs/symmap">SymMap</a> * SymMap)</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/symmap/#a1da8b4bf1fb5b60a5aa6054455c846a0">SymMap::ECMap</a>, <a href="#a903f7954a46ba31474ad9e0c7ccfbed3">isArchiveSymbol</a>, <a href="#a832ff21f008f041dd1708c083417eb74">isECObject</a>, <a href="#a0e6655075d2bf4bb40a6a0930c1a0cda">isImportDescriptor</a>, <a href="/web-llvm/docs/api/structs/symmap/#ac3e5452193f29d245056cc8e4a63aaf8">SymMap::Map</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#aa224a43fb4348654b3a36b5309630905">llvm::object::SymbolicFile::symbols</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a> and <a href="/web-llvm/docs/api/structs/symmap/#a754a8232906949e759f7f2d231f93595">SymMap::UseECMap</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### is64BitKind() {#acd2edaf906058e05bac72b0cffa0ac88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool is64BitKind (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">llvm::object::Archive::K_BSD</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">llvm::object::Archive::K_COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8">llvm::object::Archive::K_DARWIN</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">llvm::object::Archive::K_DARWIN64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">llvm::object::Archive::K_GNU</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">llvm::object::Archive::K_GNU64</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a>, <a href="#a0781a0e5a09042c7bf27104d1f86793a">printNBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### is64BitSymbolicFile() {#a26a389fcf3a6cc81cb007bfcf9f253c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool is64BitSymbolicFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">SymbolicFile</a> * SymObj)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a635a922ee4f32bce5b1f3ae39e065c31">llvm::object::SymbolicFile::is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a> and <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>.</p>

</div>
</div>

### isAIXBigArchive() {#a865ced7028dc9ae9e8118586cf8901cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAIXBigArchive (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="#a8d245de2307b5540582f87e3efa63a3c">computeSymbolTableSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### isAnyArm64COFF() {#afb13b41609de563860e9b86fe296cd84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAnyArm64COFF (<a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">object::SymbolicFile</a> &amp; Obj)</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36ecc78d5979c7c250c9284a5211041d">llvm::getBitcodeTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac0322f1809be8f6f88af125c1956c9a1">llvm::object::Binary::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a4cdd8d73d6aba93a5790daaa2d767553">llvm::COFF::isAnyArm64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac391f637f5960964588dfac009094396">llvm::object::Binary::isCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5d4359ac837c2394894cd79492713d46">llvm::object::Binary::isCOFFImportFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2e1b01646abde97d55a7225f7ed9ffbf">llvm::object::Binary::isIR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>.</p>

</div>
</div>

### isArchiveSymbol() {#a903f7954a46ba31474ad9e0c7ccfbed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isArchiveSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref">object::BasicSymbolRef</a> &amp; S)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a28b7c599b5884de1b379b53365685778">llvm::object::BasicSymbolRef::getFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265">llvm::object::BasicSymbolRef::SF_FormatSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>.</p>

</div>
</div>

### isBSDLike() {#a44ba542da3cf5a91c1df4fd029b061cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isBSDLike (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">llvm::object::Archive::K_BSD</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">llvm::object::Archive::K_COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8">llvm::object::Archive::K_DARWIN</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">llvm::object::Archive::K_DARWIN64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">llvm::object::Archive::K_GNU</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">llvm::object::Archive::K_GNU64</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8d245de2307b5540582f87e3efa63a3c">computeSymbolTableSize</a>, <a href="#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>, <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### isCOFFArchive() {#a9268243880dea3ade98f24e7bd531038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCOFFArchive (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">llvm::object::Archive::K_COFF</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a> and <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>.</p>

</div>
</div>

### isDarwin() {#a1006d6edecba6ccd85680339884fd276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDarwin (<a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8">llvm::object::Archive::K_DARWIN</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">llvm::object::Archive::K_DARWIN64</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a> and <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>.</p>

</div>
</div>

### isECObject() {#a832ff21f008f041dd1708c083417eb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isECObject (<a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile">object::SymbolicFile</a> &amp; Obj)</td>
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



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36ecc78d5979c7c250c9284a5211041d">llvm::getBitcodeTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac0322f1809be8f6f88af125c1956c9a1">llvm::object::Binary::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a0a3590d84a3fcf4c0f629a42e9384428">llvm::COFF::IMAGE_FILE_MACHINE_ARM64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac391f637f5960964588dfac009094396">llvm::object::Binary::isCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5d4359ac837c2394894cd79492713d46">llvm::object::Binary::isCOFFImportFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2e1b01646abde97d55a7225f7ed9ffbf">llvm::object::Binary::isIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a> and <a href="#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>.</p>

</div>
</div>

### isImportDescriptor() {#a0e6655075d2bf4bb40a6a0930c1a0cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isImportDescriptor (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#af433dfa7afd9b346f99c32aadd484114">llvm::object::ImportDescriptorPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a102830d484cf8e6029c7103410e702b1">llvm::object::NullImportDescriptorSymbolName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a76efa8f8a29e582d7baeccbf548a3058">llvm::object::NullThunkDataPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#abae8f3e6131a78a842714f24404ccbaf">llvm::object::NullThunkDataSuffix</a>.</p>


<p>Referenced by <a href="#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>.</p>

</div>
</div>

### now() {#a0edd35207e47a9fb4d484238d3172e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::TimePoint&lt; std::chrono::seconds &gt; now (bool Deterministic)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/exponentialbackoff/#ac3a72825a12a5f0edde2b4483124b190">llvm::ExponentialBackoff::ExponentialBackoff</a>, <a href="/web-llvm/docs/api/classes/llvm/timerecord/#a867cbf168949d9b11c9dcb23ffb6989b">llvm::TimeRecord::getCurrentTime</a>, <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler/#a9ed90bedc720105e3872bfe12245e89d">llvm::TimeTraceProfiler::TimeTraceProfiler</a>, <a href="#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### print() {#aa9f638c7ae7fdd206a6c60e26bef9751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, T Val)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="#a44ba542da3cf5a91c1df4fd029b061cb">isBSDLike</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/gen-inline-oz-test-model/#afb44681dbd4e39a83fa89d34a03c042a">gen-inline-oz-test-model.build_mock_model</a>, <a href="/web-llvm/docs/api/namespaces/gen-regalloc-eviction-test-model/#aebc0794619dce658c82bf5f6b020a2ab">gen-regalloc-eviction-test-model.build_mock_model</a>, <a href="/web-llvm/docs/api/namespaces/gen-regalloc-priority-test-model/#a897c3b991053cb02691cf49f5b7b1cc3">gen-regalloc-priority-test-model.build_mock_model</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#a00a3fa6f9ae730c7b424fb26a2c0f20f">anonymous{AccelTable.cpp}::AppleAccelTableWriter::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/variablegepindex/#a488bff1f7c16c479309a8e7f76590c95">anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a74c4682962d0f4e7322c6a703adaa7ee">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a5747f9b95c42d8956f1894de1bef02dc">anonymous{LoopDistribute.cpp}::InstPartitionContainer::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula/#a376acc2ec7fd1a216d5ec9fb9f04c99a">anonymous{LoopStrengthReduce.cpp}::Formula::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewritestatepointsforgc-cpp-/bdvstate/#aa66e66ad0f2390a6481abb4feba60c2d">anonymous{RewriteStatepointsForGC.cpp}::BDVState::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields/#a423c378f7cfc3637d0a97b19ef757fac">anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a238a21f94d9186543c9d7656c55837fb">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/vxrminfo/#a1927229203dc3a9d85b07d75ac99e3d4">anonymous{RISCVInsertWriteVXRM.cpp}::VXRMInfo::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a045ad30ab1419840103a28ce5c6d5eb2">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwaoperand/#ad50842dfcd63fda000fc40bfe666e2ca">anonymous{SIPeepholeSDWA.cpp}::SDWAOperand::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-wasmobjectwriter-cpp-/wasmrelocationentry/#aaf06e15f842e20ddb2a9bde2df06ec7b">anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#a843229cfda9f61491b29bbf045507f4d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#a91e83c8a019bcde0518af21a79396a42">llvm::Comdat::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a2660a4c17b0c7f6c294a670ecc6812d7">llvm::DbgMarker::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3cb121a66942e3da75a21e28a09a47e9">llvm::DbgRecord::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a729103ecdea80ee058ef426cb4e0bf5a">llvm::Metadata::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9b4c67a0936fe59c9511ff591b97f260">llvm::Module::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#aaa82cedf82d927d77f03dbf0db19c2f0">llvm::ModuleSummaryIndex::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a367bddd00ba4d448572f39f59da07a14">llvm::NamedMDNode::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a90c89709fd5e5e1d96455aec8b0c3916">llvm::Type::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#af7dca9a9e816ef69fd9e9467f64f72b4">llvm::Value::dump</a>, <a href="/web-llvm/docs/api/namespaces/gen-inline-oz-test-model/#a217f2ab6000d72ad475b25276d3e1ac9">gen-inline-oz-test-model.main</a>, <a href="/web-llvm/docs/api/namespaces/log-reader/#a00a10719af7fe8bd112870799e9472d1">log_reader.main</a>, <a href="/web-llvm/docs/api/namespaces/log-reader/#a14b90855a54de6f662b45732cb262314">log_reader.pretty_print_tensor_value</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniumdemangle-cpp-/dumpvisitor/#ad493cd30055fca3c8953054af0bbac6c">anonymous{ItaniumDemangle.cpp}::DumpVisitor::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#a546804db12f646346b125a2d6e8a4bf9">llvm::DbgLabelRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a5a91755a39059240dcc0a2cdaa8b03ec">llvm::DbgMarker::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a3172de1fbc8c02b9b2cef0b24e3b558f">llvm::DbgVariableRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniumdemangle-cpp-/dumpvisitor/#adb58919e1518cf971d39119d95ce6ea6">anonymous{ItaniumDemangle.cpp}::DumpVisitor::printWithPendingNewline</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/namespaces/interactive-host/#a0eded48c2eef46879e2f4d0fd284238b">interactive_host.run_interactive</a> and <a href="/web-llvm/docs/api/structs/anonymous-debugcounter-cpp-/debugcounterowner/#acd9a1f60cb5cc2cbcb22d4bb89e677d6">anonymous{DebugCounter.cpp}::DebugCounterOwner::~DebugCounterOwner</a>.</p>

</div>
</div>

### printBigArchiveMemberHeader() {#aea934139e960daaca81f19ee42fefb9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printBigArchiveMemberHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt; &amp; ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size, uint64_t PrevOffset, uint64_t NextOffset)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#afb85ab84f25274ce79df485ddeadffdd">llvm::sys::toTimeT</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### printBSDMemberHeader() {#a52904074f52a694e289a93b1634553c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printBSDMemberHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, uint64_t Pos, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt; &amp; ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="#a8a48633636bbcf3d359e1c02b6aba4a5">printRestOfMemberHeader</a>, <a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### printGNUSmallMemberHeader() {#abaeb6f00c0c03b98ec4a12da525e74b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printGNUSmallMemberHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt; &amp; ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#a8a48633636bbcf3d359e1c02b6aba4a5">printRestOfMemberHeader</a>, <a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>, <a href="#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>

</div>
</div>

### printLE() {#aaf4c0b08270ecda12b4b183b52b7a2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printLE (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, T Val)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a> and <a href="#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a>.</p>

</div>
</div>

### printMemberHeader() {#a9f13720384c813c9f47a087657600363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printMemberHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, uint64_t Pos, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; StringTable, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint64_t &gt; &amp; MemberNames, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, bool Thin, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt; ModTime, uint64_t Size)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmap/#afea367cbdd62e85c20d3ebe044253ce7">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::insert</a>, <a href="#a44ba542da3cf5a91c1df4fd029b061cb">isBSDLike</a>, <a href="#a9268243880dea3ade98f24e7bd531038">isCOFFArchive</a>, <a href="#a52904074f52a694e289a93b1634553c3">printBSDMemberHeader</a>, <a href="#abaeb6f00c0c03b98ec4a12da525e74b0">printGNUSmallMemberHeader</a>, <a href="#a8a48633636bbcf3d359e1c02b6aba4a5">printRestOfMemberHeader</a>, <a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ac72ef2b9a4e9866b2d57f5e5270f57fb">useStringTable</a>.</p>


<p>Referenced by <a href="#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>.</p>

</div>
</div>

### printNBits() {#a0781a0e5a09042c7bf27104d1f86793a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printNBits (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, uint64_t Val)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#acd2edaf906058e05bac72b0cffa0ac88">is64BitKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>


<p>Referenced by <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>.</p>

</div>
</div>

### printRestOfMemberHeader() {#a8a48633636bbcf3d359e1c02b6aba4a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printRestOfMemberHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt; &amp; ModTime, unsigned UID, unsigned GID, unsigned Perms, uint64_t Size)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#afb85ab84f25274ce79df485ddeadffdd">llvm::sys::toTimeT</a>.</p>


<p>Referenced by <a href="#a52904074f52a694e289a93b1634553c3">printBSDMemberHeader</a>, <a href="#abaeb6f00c0c03b98ec4a12da525e74b0">printGNUSmallMemberHeader</a> and <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>.</p>

</div>
</div>

### printWithSpacePadding() {#af7cc3cea867e3070fd25ab0d14abb814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printWithSpacePadding (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, T Data, unsigned Size)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="#a5be3fea922116aa226fc27bde3419182">computeStringTable</a>, <a href="#aea934139e960daaca81f19ee42fefb9a">printBigArchiveMemberHeader</a>, <a href="#a52904074f52a694e289a93b1634553c3">printBSDMemberHeader</a>, <a href="#abaeb6f00c0c03b98ec4a12da525e74b0">printGNUSmallMemberHeader</a>, <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>, <a href="#a8a48633636bbcf3d359e1c02b6aba4a5">printRestOfMemberHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### useStringTable() {#ac72ef2b9a4e9866b2d57f5e5270f57fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool useStringTable (bool Thin, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="#a9f13720384c813c9f47a087657600363">printMemberHeader</a>.</p>

</div>
</div>

### writeECSymbols() {#a9ffd2185084f74a9992ea31cc78c4ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeECSymbols (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, bool Deterministic, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; MemberData &gt; Members, <a href="/web-llvm/docs/api/structs/symmap">SymMap</a> &amp; SymMap)</td>
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



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#a146d10ed8f323a076ba12323de86902f">computeECSymbolsSize</a>, <a href="/web-llvm/docs/api/structs/symmap/#a1da8b4bf1fb5b60a5aa6054455c846a0">SymMap::ECMap</a>, <a href="#a0edd35207e47a9fb4d484238d3172e82">now</a>, <a href="#abaeb6f00c0c03b98ec4a12da525e74b0">printGNUSmallMemberHeader</a>, <a href="#aaf4c0b08270ecda12b4b183b52b7a2ea">printLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### writeSymbolMap() {#a5b06dd328e277cc107d21a8ee4266e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeSymbolMap (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, bool Deterministic, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; MemberData &gt; Members, <a href="/web-llvm/docs/api/structs/symmap">SymMap</a> &amp; SymMap, uint64_t MembersOffset)</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#aaf3cab2e73302be816886e9c0ba73746">computeSymbolMapSize</a>, <a href="/web-llvm/docs/api/structs/symmap/#ac3e5452193f29d245056cc8e4a63aaf8">SymMap::Map</a>, <a href="#aaf4c0b08270ecda12b4b183b52b7a2ea">printLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### writeSymbolTable() {#a59c3a1cc637af30e381ff9222aa75c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, bool Deterministic, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; MemberData &gt; Members, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StringTable, uint64_t MembersOffset, unsigned NumSyms, uint64_t PrevMemberOffset=0, uint64_t NextMemberOffset=0, bool Is64Bit=false)</td>
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



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#a8d245de2307b5540582f87e3efa63a3c">computeSymbolTableSize</a>, <a href="#acd2edaf906058e05bac72b0cffa0ac88">is64BitKind</a>, <a href="#a26a389fcf3a6cc81cb007bfcf9f253c5">is64BitSymbolicFile</a>, <a href="#a865ced7028dc9ae9e8118586cf8901cc">isAIXBigArchive</a>, <a href="#a44ba542da3cf5a91c1df4fd029b061cb">isBSDLike</a>, <a href="#a9268243880dea3ade98f24e7bd531038">isCOFFArchive</a>, <a href="#a1006d6edecba6ccd85680339884fd276">isDarwin</a>, <a href="#a0781a0e5a09042c7bf27104d1f86793a">printNBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtable/#a1c25d62b8c2016835a39cd4b64151802">llvm::StringTable::size</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>.</p>

</div>
</div>

### writeSymbolTableHeader() {#a8980c8408e5daa10c78c4a577ebaa527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeSymbolTableHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a> Kind, bool Deterministic, uint64_t Size, uint64_t PrevMemberOffset=0, uint64_t NextMemberOffset=0)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#acd2edaf906058e05bac72b0cffa0ac88">is64BitKind</a>, <a href="#a865ced7028dc9ae9e8118586cf8901cc">isAIXBigArchive</a>, <a href="#a44ba542da3cf5a91c1df4fd029b061cb">isBSDLike</a>, <a href="#a0edd35207e47a9fb4d484238d3172e82">now</a>, <a href="#aea934139e960daaca81f19ee42fefb9a">printBigArchiveMemberHeader</a>, <a href="#a52904074f52a694e289a93b1634553c3">printBSDMemberHeader</a>, <a href="#abaeb6f00c0c03b98ec4a12da525e74b0">printGNUSmallMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a>, <a href="#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a> and <a href="#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Log2OfAIXPageSize {#a708c1755c910c2420229a493dfd3b20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t Log2OfAIXPageSize = 12</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="#a605d26c625db977423d136525feecb89">getAuxMaxAlignment</a> and <a href="#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>.</p>

</div>
</div>

### MinBigArchiveMemDataAlign {#a59d9478fb7e03754c8beb1f0bb2e0843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t MinBigArchiveMemDataAlign = 2</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>Referenced by <a href="#a605d26c625db977423d136525feecb89">getAuxMaxAlignment</a> and <a href="#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
