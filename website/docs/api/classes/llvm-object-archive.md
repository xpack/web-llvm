---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/archive
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Archive` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::Archive { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/bigarchive">BigArchive</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24211ac7a10e413813ea69f258fb2658">child_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/fallible-iterator">fallible_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive/childfallibleiterator">ChildFallibleIterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#ab288378fa8bfa0678dd25e36b5198a87">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a> (MemoryBufferRef Source, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab288378fa8bfa0678dd25e36b5198a87">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba32220e0e4128ca33ebc90738780eb">kind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a831e9d8a13d29158e9607b50e46b9b">isThin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a24211ac7a10e413813ea69f258fb2658">child_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96c91af5a0b48ef31603a556830b5ee">child_begin</a> (Error &amp;Err, bool SkipInternal=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a24211ac7a10e413813ea69f258fb2658">child_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f42473697d3e7447ff595edc6cf2a4">child_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a24211ac7a10e413813ea69f258fb2658">child_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1e06f3450b7f027dfac3a136c3f547">children</a> (Error &amp;Err, bool SkipInternal=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d42da5dcfe3901a2328c98293495ad">symbol_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol-iterator">symbol_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a45b07febdd0826f59682635335111">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol-iterator">symbol_iterator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad53613e81c10091896d73287938ab8be">ec_symbols</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6942d34da0ae42a687cccd3e4b4a7f3">findSym</a> (StringRef name) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7627fa50310fa64ca42b24a175196892">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84bb2caca83d65db03695cf2e035f410">hasSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4977194f7b9fa1b8878243f1a63e60c6">getSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4c08500c50214f1c3fd995209568d0">getStringTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8893b8d88f459187356143661b34a3">getNumberOfSymbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263730f838496be7a6dcc8960c170dac">getNumberOfECSymbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082b3ce52569d06f1facd2e3ca528b75">getFirstChildOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f4d7553bec2820f98474d1d3fdc3fe">takeThinBuffers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader">AbstractArchiveMemberHeader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0319d34665366a03cae0c91e380323e8">createArchiveMemberHeader</a> (const char *RawHeaderPtr, uint64_t Size, Error *Err) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457900e5727399c3a3dc3aa7ee0f9a98">getArchiveMagicLen</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b49427424adcdd7558430012349bce0">setFirstRegular</a> (const Child &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982cb0d19b381e31cf384b0914de39bc">anchor</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa44b94c95310ecd69cb194904f795b5b">SymbolTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539063942b082a945fb8d6cae17dfa0b">ECSymbolTable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bc3592efbf7f42dae2970271e6c58a">StringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ccdca23bbc0a3039201e4f732464a6d">FirstRegularData</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d236a75d57ec220ba1bd6ba17112cb">FirstRegularStartOfFile</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e888e772c91c48899c1a850e4bd60a">Format</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee66c403fdce3e8949320ab40b59296">IsThin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1618f8ee2adcf4e994043f71816d16aa">ThinBuffers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff545dbbc7e3d85c4e6d914200747db">create</a> (MemoryBufferRef Source)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb4b14d68eff7cfdc9457db1603fea7">getDefaultKind</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37a8365d81258109c2093aac933e8a2">getDefaultKindForTriple</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8573022f865d22feb0cffae310a6b98e">classof</a> (Binary const *v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56b46642bec8e141cc7aff486aaaf2d">MaxMemberSize</a> = 9999999999</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size field is 10 decimal digits long. <a href="#ae56b46642bec8e141cc7aff486aaaf2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### child\_iterator {#a24211ac7a10e413813ea69f258fb2658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::Archive::child_iterator =  fallible_iterator&lt;ChildFallibleIterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Kind {#ab288378fa8bfa0678dd25e36b5198a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::object::Archive::Kind </td>
</tr>
</table>
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
<td class="doxyEnumItemName">K_GNU<a id="ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K_GNU64<a id="ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K_BSD<a id="ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K_DARWIN<a id="ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K_DARWIN64<a id="ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K_COFF<a id="ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">K_AIXBIG<a id="ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Archive() {#a8ad341cb471333b07af638089e1dc7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::Archive (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a22e8d3b532d837ea2b7136d4befc430a">llvm::object::ArchiveMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a7bf059b8b05e0acb1e02d9f833425477">llvm::object::BigArchiveMagic</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ad96c91af5a0b48ef31603a556830b5ee">child_begin</a>, <a href="#a77f42473697d3e7447ff595edc6cf2a4">child_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#a539063942b082a945fb8d6cae17dfa0b">ECSymbolTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aad293d52241823f347ddee418e1e3608a">llvm::object::Binary::ID_Archive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20ad5a8a27f4e310ea593b285615faaca35">llvm::object::invalid_file_type</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">K_AIXBIG</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">K_BSD</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">K_COFF</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">K_DARWIN64</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">K_GNU</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">K_GNU64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="#a2b49427424adcdd7558430012349bce0">setFirstRegular</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="#a87bc3592efbf7f42dae2970271e6c58a">StringTable</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#aa44b94c95310ecd69cb194904f795b5b">SymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a5581dd64bd991f857438cd71f12b711e">llvm::object::ThinArchiveMagic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#a6fd90d0abf2981b4a1db908db7a8082e">llvm::object::Archive::Symbol::Symbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### child\_begin() {#ad96c91af5a0b48ef31603a556830b5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::child_iterator Archive::child_begin (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err, bool SkipInternal=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a77f42473697d3e7447ff595edc6cf2a4">child_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="#a082b3ce52569d06f1facd2e3ca528b75">getFirstChildOffset</a>, <a href="#a7627fa50310fa64ca42b24a175196892">isEmpty</a> and <a href="/web-llvm/docs/api/classes/llvm/fallible-iterator/#a5e324def628fb970ffc152836f145972">llvm::fallible_iterator&lt; ChildFallibleIterator &gt;::itr</a>.</p>


<p>Referenced by <a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a> and <a href="#a6f1e06f3450b7f027dfac3a136c3f547">children</a>.</p>

</div>
</div>

### child\_end() {#a77f42473697d3e7447ff595edc6cf2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::child_iterator Archive::child_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fallible-iterator/#a1885ab71cce9418d89aa8ca952021241">llvm::fallible_iterator&lt; ChildFallibleIterator &gt;::end</a>.</p>


<p>Referenced by <a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="#ad96c91af5a0b48ef31603a556830b5ee">child_begin</a> and <a href="#a6f1e06f3450b7f027dfac3a136c3f547">children</a>.</p>

</div>
</div>

### children() {#a6f1e06f3450b7f027dfac3a136c3f547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; child_iterator &gt; llvm::object::Archive::children (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err, bool SkipInternal=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="#ad96c91af5a0b48ef31603a556830b5ee">child_begin</a>, <a href="#a77f42473697d3e7447ff595edc6cf2a4">child_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#ac22ea488f955382d30003c56202ef80d">appendFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#afb660c7a07ee04be6dac1b6ce20de6d6">llvm::objcopy::createNewArchiveMembers</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#aa2f8f902ed35880d4ccb900b4ddbe2c1">anonymous{OffloadBinary.cpp}::extractFromArchive</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ab09d28878031ffd0f73e46ea295c1e65">anonymous{DlltoolDriver.cpp}::forEachCoff</a>.</p>

</div>
</div>

### createArchiveMemberHeader() {#a0319d34665366a03cae0c91e380323e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AbstractArchiveMemberHeader &gt; Archive::createArchiveMemberHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RawHeaderPtr, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">K_AIXBIG</a>, <a href="#a8ba32220e0e4128ca33ebc90738780eb">kind</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### ec\_symbols() {#ad53613e81c10091896d73287938ab8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; iterator_range&lt; Archive::symbol_iterator &gt; &gt; Archive::ec_symbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a539063942b082a945fb8d6cae17dfa0b">ECSymbolTable</a>, <a href="#a1e8893b8d88f459187356143661b34a3">getNumberOfSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="#aa44b94c95310ecd69cb194904f795b5b">SymbolTable</a>.</p>

</div>
</div>

### findSym() {#ad6942d34da0ae42a687cccd3e4b4a7f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; Archive::Child &gt; &gt; Archive::findSym (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1263 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aa53f9de42b9d8eeaf9af259f59f4a1be">llvm::object::Archive::Symbol::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol/#aaccb27d091e3f4899c01d6ebc1100967">llvm::object::Archive::Symbol::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, <a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a> and <a href="#a60d42da5dcfe3901a2328c98293495ad">symbol_end</a>.</p>

</div>
</div>

### getFirstChildOffset() {#a082b3ce52569d06f1facd2e3ca528b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::Archive::getFirstChildOffset ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="#a457900e5727399c3a3dc3aa7ee0f9a98">getArchiveMagicLen</a>.</p>


<p>Referenced by <a href="#ad96c91af5a0b48ef31603a556830b5ee">child_begin</a>.</p>

</div>
</div>

### getNumberOfECSymbols() {#a263730f838496be7a6dcc8960c170dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t Archive::getNumberOfECSymbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#a539063942b082a945fb8d6cae17dfa0b">ECSymbolTable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>.</p>

</div>
</div>

### getNumberOfSymbols() {#a1e8893b8d88f459187356143661b34a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t Archive::getNumberOfSymbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="#a4977194f7b9fa1b8878243f1a63e60c6">getSymbolTable</a>, <a href="#a84bb2caca83d65db03695cf2e035f410">hasSymbolTable</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">K_AIXBIG</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">K_BSD</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">K_DARWIN64</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">K_GNU</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">K_GNU64</a>, <a href="#a8ba32220e0e4128ca33ebc90738780eb">kind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7a225814d4cc0d175373f7ffc59f66b4">llvm::support::endian::read32be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4ec2abec8101a7b16ee520e882cc7d34">llvm::support::endian::read64be</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>.</p>


<p>Referenced by <a href="#ad53613e81c10091896d73287938ab8be">ec_symbols</a> and <a href="#a60d42da5dcfe3901a2328c98293495ad">symbol_end</a>.</p>

</div>
</div>

### getStringTable() {#a1c4c08500c50214f1c3fd995209568d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::getStringTable ()</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="#a87bc3592efbf7f42dae2970271e6c58a">StringTable</a>.</p>


<p>Referenced by <a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a>.</p>

</div>
</div>

### getSymbolTable() {#a4977194f7b9fa1b8878243f1a63e60c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::getSymbolTable ()</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="#aa44b94c95310ecd69cb194904f795b5b">SymbolTable</a>.</p>


<p>Referenced by <a href="#a1e8893b8d88f459187356143661b34a3">getNumberOfSymbols</a> and <a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a>.</p>

</div>
</div>

### hasSymbolTable() {#a84bb2caca83d65db03695cf2e035f410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Archive::hasSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1284 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Reference <a href="#aa44b94c95310ecd69cb194904f795b5b">SymbolTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#af5cb5b86f3ef0aa8fee5da90f3635bad">llvm::objcopy::executeObjcopyOnArchive</a>, <a href="#a1e8893b8d88f459187356143661b34a3">getNumberOfSymbols</a> and <a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a>.</p>

</div>
</div>

### isEmpty() {#a7627fa50310fa64ca42b24a175196892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Archive::isEmpty ()</td>
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



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a> and <a href="#a457900e5727399c3a3dc3aa7ee0f9a98">getArchiveMagicLen</a>.</p>


<p>Referenced by <a href="#ad96c91af5a0b48ef31603a556830b5ee">child_begin</a>.</p>

</div>
</div>

### isThin() {#a0a831e9d8a13d29158e9607b50e46b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::Archive::isThin ()</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a9537162135cca043a3b82f0df2816ed7">llvm::object::Archive::Child::Child</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#af5cb5b86f3ef0aa8fee5da90f3635bad">llvm::objcopy::executeObjcopyOnArchive</a>, <a href="#a457900e5727399c3a3dc3aa7ee0f9a98">getArchiveMagicLen</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a03bfd76bddfe1a42326e93dc3c131c8c">llvm::object::Archive::Child::getBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a22ece0b78ccffb215a68d44b94b46e2f">llvm::object::Archive::Child::getFullName</a>.</p>

</div>
</div>

### kind() {#a8ba32220e0e4128ca33ebc90738780eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::object::Archive::kind ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a0319d34665366a03cae0c91e380323e8">createArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#af5cb5b86f3ef0aa8fee5da90f3635bad">llvm::objcopy::executeObjcopyOnArchive</a>, <a href="#a1e8893b8d88f459187356143661b34a3">getNumberOfSymbols</a> and <a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a>.</p>

</div>
</div>

### symbol\_begin() {#a03e47f68ebb90174f21f2ab9b95d3d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::symbol_iterator Archive::symbol_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="#a1c4c08500c50214f1c3fd995209568d0">getStringTable</a>, <a href="#a4977194f7b9fa1b8878243f1a63e60c6">getSymbolTable</a>, <a href="#a84bb2caca83d65db03695cf2e035f410">hasSymbolTable</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">K_AIXBIG</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">K_BSD</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">K_DARWIN64</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">K_GNU</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">K_GNU64</a>, <a href="#a8ba32220e0e4128ca33ebc90738780eb">kind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7a225814d4cc0d175373f7ffc59f66b4">llvm::support::endian::read32be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4ec2abec8101a7b16ee520e882cc7d34">llvm::support::endian::read64be</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>.</p>


<p>Referenced by <a href="#ad6942d34da0ae42a687cccd3e4b4a7f3">findSym</a> and <a href="#a04a45b07febdd0826f59682635335111">symbols</a>.</p>

</div>
</div>

### symbol\_end() {#a60d42da5dcfe3901a2328c98293495ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::symbol_iterator Archive::symbol_end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Reference <a href="#a1e8893b8d88f459187356143661b34a3">getNumberOfSymbols</a>.</p>


<p>Referenced by <a href="#ad6942d34da0ae42a687cccd3e4b4a7f3">findSym</a> and <a href="#a04a45b07febdd0826f59682635335111">symbols</a>.</p>

</div>
</div>

### symbols() {#a04a45b07febdd0826f59682635335111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; symbol_iterator &gt; llvm::object::Archive::symbols ()</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a03e47f68ebb90174f21f2ab9b95d3d28">symbol_begin</a> and <a href="#a60d42da5dcfe3901a2328c98293495ad">symbol_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a23cbef0272f92b38f3f6654ce8af1cfb">anonymous{DlltoolDriver.cpp}::doIdentify</a>.</p>

</div>
</div>

### takeThinBuffers() {#ae6f4d7553bec2820f98474d1d3fdc3fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; llvm::object::Archive::takeThinBuffers ()</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getArchiveMagicLen() {#a457900e5727399c3a3dc3aa7ee0f9a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Archive::getArchiveMagicLen ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a22e8d3b532d837ea2b7136d4befc430a">llvm::object::ArchiveMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a7bf059b8b05e0acb1e02d9f833425477">llvm::object::BigArchiveMagic</a>, <a href="#a0a831e9d8a13d29158e9607b50e46b9b">isThin</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">K_AIXBIG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a5581dd64bd991f857438cd71f12b711e">llvm::object::ThinArchiveMagic</a>.</p>


<p>Referenced by <a href="#a082b3ce52569d06f1facd2e3ca528b75">getFirstChildOffset</a> and <a href="#a7627fa50310fa64ca42b24a175196892">isEmpty</a>.</p>

</div>
</div>

### setFirstRegular() {#a2b49427424adcdd7558430012349bce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Archive::setFirstRegular (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a> and <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a982cb0d19b381e31cf384b0914de39bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Archive::anchor ()</td>
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



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ECSymbolTable {#a539063942b082a945fb8d6cae17dfa0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::ECSymbolTable</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a>, <a href="#ad53613e81c10091896d73287938ab8be">ec_symbols</a> and <a href="#a263730f838496be7a6dcc8960c170dac">getNumberOfECSymbols</a>.</p>

</div>
</div>

### StringTable {#a87bc3592efbf7f42dae2970271e6c58a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::StringTable</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a> and <a href="#a1c4c08500c50214f1c3fd995209568d0">getStringTable</a>.</p>

</div>
</div>

### SymbolTable {#aa44b94c95310ecd69cb194904f795b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::SymbolTable</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a59a90ba7dd76e41d07e6c1cb792e0db3">appendGlobalSymbolTableInfo</a>, <a href="#a8ad341cb471333b07af638089e1dc7c9">Archive</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="#ad53613e81c10091896d73287938ab8be">ec_symbols</a>, <a href="#a4977194f7b9fa1b8878243f1a63e60c6">getSymbolTable</a> and <a href="#a84bb2caca83d65db03695cf2e035f410">hasSymbolTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FirstRegularData {#a5ccdca23bbc0a3039201e4f732464a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::FirstRegularData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### FirstRegularStartOfFile {#a43d236a75d57ec220ba1bd6ba17112cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::Archive::FirstRegularStartOfFile = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### Format {#a49e888e772c91c48899c1a850e4bd60a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::object::Archive::Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### IsThin {#a7ee66c403fdce3e8949320ab40b59296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::object::Archive::IsThin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### ThinBuffers {#a1618f8ee2adcf4e994043f71816d16aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;MemoryBuffer&gt; &gt; llvm::object::Archive::ThinBuffers</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8573022f865d22feb0cffae310a6b98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::Archive::classof (<a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * v)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a5efaba206c0c82deb1e8898c4c3aad4b">llvm::object::Binary::Binary</a>.</p>

</div>
</div>

### create() {#afff545dbbc7e3d85c4e6d914200747db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Archive &gt; &gt; Archive::create (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Source)</td>
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



<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a7bf059b8b05e0acb1e02d9f833425477">llvm::object::BigArchiveMagic</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform/#a0ff140ec3eee8b9a860f3626b5640c04">llvm::orc::COFFPlatform::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#aab4f9dfc17222d93cc4942c9b84470c6">llvm::orc::StaticLibraryDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machouniversalbinary/objectforarch/#af15c33e98f6234064d5be2e0dcf7aa7d">llvm::object::MachOUniversalBinary::ObjectForArch::getAsArchive</a>.</p>

</div>
</div>

### getDefaultKind() {#a6eb4b14d68eff7cfdc9457db1603fea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object::Archive::Kind Archive::getDefaultKind ()</td>
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



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#aa37a8365d81258109c2093aac933e8a2">getDefaultKindForTriple</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ae329f3571e25025c5496be7a9746a94f">llvm::sys::getDefaultTargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#a5b9ae09da2b1f1939e37ba537fdf9eb1">llvm::NewArchiveMember::detectKindFromObject</a>.</p>

</div>
</div>

### getDefaultKindForTriple() {#aa37a8365d81258109c2093aac933e8a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object::Archive::Kind Archive::getDefaultKindForTriple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">K_AIXBIG</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">K_COFF</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8">K_DARWIN</a>, <a href="#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">K_GNU</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#a5b9ae09da2b1f1939e37ba537fdf9eb1">llvm::NewArchiveMember::detectKindFromObject</a> and <a href="#a6eb4b14d68eff7cfdc9457db1603fea7">getDefaultKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### MaxMemberSize {#ae56b46642bec8e141cc7aff486aaaf2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::object::Archive::MaxMemberSize = 9999999999</td>
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

<p>Size field is 10 decimal digits long.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
