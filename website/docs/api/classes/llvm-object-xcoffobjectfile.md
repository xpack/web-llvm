---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/xcoffobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XCOFFObjectFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::XCOFFObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">llvm/Object/XCOFFObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for all object file types. <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b3a10b03e16984050ca82558844a95">xcoff_symbol_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/xcoff-symbol-iterator">xcoff_symbol_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027f9711f9c345de769b868de76c0e05">ObjectFile::createXCOFFObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab344ce30b163d18efac6a31c246c6715">XCOFFObjectFile</a> (unsigned Type, MemoryBufferRef Object)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc06f8608837a3bcad0809f49025d9d9">moveSymbolNext</a> (DataRefImpl &amp;Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26063993809b386ab934532d1af8b56c">getSymbolFlags</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2700f065d466d121516e7dbaa56348">symbol_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a5bf1bfacdebc64c1f70e3b2861ba76eb">basic_symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7d6556798e014fdfae78bc0b3d5235">symbol_end</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a63b3a10b03e16984050ca82558844a95">xcoff_symbol_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b2e47a9b79b850895513f344881db0">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5663d03689c83dfe78cf82f2710c6115">getSymbolName</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbca160cc61e2866976918c03e0135b6">getSymbolAddress</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b3dd58311eae0ca4186635d31c8655">getSymbolValueImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afba35271cc6fce891ce2bda4576c87d5">getSymbolAlignment</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c221e2f2dc591094cf0b0d92fd42d3">getCommonSymbolSizeImpl</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d12d4046ba19c552b1e86fbe25abe9">getSymbolSection</a> (DataRefImpl Symb) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebff746bf0b2e33d0521c544bbb2b6db">moveSectionNext</a> (DataRefImpl &amp;Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e555f784aeb3a459128d1d9a2928f36">getSectionName</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c03084606f192cd1032910070316a1">getSectionAddress</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ba86943fe55c4f5afa2bb90fda698e">getSectionIndex</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5524d5f35cbfb6846573bdf5e60e08c2">getSectionSize</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9800b5c811f6cb665c2c118d1ceccb54">getSectionContents</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1e44a6253c5cfd1ea8fbb479cea6a0">getSectionAlignment</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e56dd71da739369797eed90adcd1aa0">isSectionCompressed</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc70c96004b6684d1f5e67c621827cb2">isSectionText</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540165da4d0f8e7c070551b19dcbfea5">isSectionData</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4722e471ff1ee6061f7f4e265f173833">isSectionBSS</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d580a4e198fdfb59863606ed199162f">isDebugSection</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3071bf49d31a9daf8a9fae0d9573bfbf">isSectionVirtual</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabae0e0e8a8ba4541ffd3e85012dde9c">section_rel_begin</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d1ca2c06b80838d961631a71384907">section_rel_end</a> (DataRefImpl Sec) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dab119d37a8dd2a3b52ff464e939b2">moveRelocationNext</a> (DataRefImpl &amp;Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5429091cffadaa5d1ff0557b20aef3af">getRelocationOffset</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbol-iterator">symbol_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5608b1db31841e33e852d5e8e7362523">getRelocationSymbol</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca463bc4ee33dc722f5e86de9d45960a">getRelocationType</a> (DataRefImpl Rel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181019615fec687b5203ba7489f65613">getRelocationTypeName</a> (DataRefImpl Rel, SmallVectorImpl&lt; char &gt; &amp;Result) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065428320f2dc6545e5a6b8d6f85df1b">section_begin</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23bd63f7e9ab9c9da2bffd45a529a6e">section_end</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02bb9315b2af1d734736ec4e427e3504">getBytesInAddress</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes used to represent an address in this object file format. <a href="#a02bb9315b2af1d734736ec4e427e3504">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5bcc9e485a23061cdef3497a43f13a">getFileFormatName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac732436ad66c12e6a2387b56ad6bd2ab">getArch</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b6277ee4861daab6273ccb0330f650">getFeatures</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2070c5afcd8a8d3007661a9405939067">getStartAddress</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc07ce668f69931ef8f02942f71c8dca">mapDebugSectionName</a> (StringRef Name) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a debug section name to a standard DWARF section name. <a href="#abc07ce668f69931ef8f02942f71c8dca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2a3a5a47c2b59a6e76774c5f2d6bba">isRelocatableObject</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this is a relocatable object (.o/.obj). <a href="#aeb2a3a5a47c2b59a6e76774c5f2d6bba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd35d32e09260ea392203103e472465c">getRawData</a> (const char *Start, uint64_t Size, StringRef Name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffauxiliaryheader32">XCOFFAuxiliaryHeader32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b00595211ef1000d4a542193fb145c">auxiliaryHeader32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffauxiliaryheader64">XCOFFAuxiliaryHeader64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665a053ea13974dd63d7a9d4b352a968">auxiliaryHeader64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c4c87bba85f9c8594dda9ba9edea99">getPointerToSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90303baf9d185097198f817b998136a6">getSymbolSectionName</a> (XCOFFSymbolRef Ref) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d6474e0580f137735002afb39321c4">getSymbolSectionID</a> (SymbolRef Sym) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref">XCOFFSymbolRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a> (DataRefImpl Ref) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32">XCOFFFileHeader32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64">XCOFFFileHeader64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae468bb7b7f91eceb924829d6ab30c69">getMagic</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba98e29c6eb5c27012cca6628555cff">getTimeStamp</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2f44591afeb9844d2c707d0c3e627f">getSymbolTableOffset32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74bf9fdb3b2f056dcfc220a4b762851e">getSymbolTableOffset64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4e00e4e4af365bb00455c632fdd458">getRawNumberOfSymbolTableEntries32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b952b9a3a6f0f03c1b9845e865f8a0">getLogicalNumberOfSymbolTableEntries32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6183def919d99ddf97174e12ec154882">getNumberOfSymbolTableEntries64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e67cafd95aae0e63fb1bc2cc11f8884">getNumberOfSymbolTableEntries</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c80392232d40366a1870cfb8e71c2f">getSymbolIndex</a> (uintptr_t SymEntPtr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cf6760f283737b422b80253b8828d2">getSymbolSize</a> (DataRefImpl Symb) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95439c835232ebad9940e1ccaa72e79a">getSymbolByIndex</a> (uint32_t Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c320b3e81e7f30b610142e8103b91ea">getSymbolEntryAddressByIndex</a> (uint32_t SymbolTableIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7051daf7cb225b8eaaf0028fac5b6b25">getSymbolNameByIndex</a> (uint32_t SymbolTableIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3b971352558436572c0f3a6efc3f60">getCFileName</a> (const XCOFFFileAuxEnt *CFileEntPtr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698cd79926f41067466d4420db3b97c3">getOptionalHeaderSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2569b6fc611ce03c731b44d248e1d34">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader32">XCOFFSectionHeader32</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180352eb59cde1ec5c850d9f80affdf0">sections32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader64">XCOFFSectionHeader64</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc2b0967dae6ef3524da67639142067">sections64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561cf045928b46ca65b204ecbc5875c7">getSectionFlags</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bffc145ade7d36357a22aec0c22b4e">getSectionByNum</a> (int16_t Num) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uintptr_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68866f040b091698a4a3bf9c744e263e">getSectionFileOffsetToRawData</a> (XCOFF::SectionTypeFlags SectType) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafddeca2e7b57e958a25b8660f735cf8">checkSymbolEntryPointer</a> (uintptr_t SymbolEntPtr) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b8e8f5c674a66e5bcb4c9554864267d">getNumberOfRelocationEntries</a> (const XCOFFSectionHeader&lt; T &gt; &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Shdr, typename Reloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adeb534d315c9a390fc59cdef8e9f261a">relocations</a> (const Shdr &amp;Sec) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; Reloc &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ef70b0779ce0c0e0f41c320c1f355a">getImportFileTable</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ExceptEnt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2171b8599a07a37e7a4f18b12d7ff312">getExceptionEntries</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; ExceptEnt &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928be9f8ad2d5fda0dc77b3e55fa352d">getStringTableEntry</a> (uint32_t Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb293c42728a4376167b20a504dcc21">getStringTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a6d134aed42e1f7be67a8dc02c9bd401f">XCOFF::SymbolAuxType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac683182aca879fad4c1df1b6a9218c1e">getSymbolAuxType</a> (uintptr_t AuxEntryAddress) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acabcf83af1313630664523bb37c473f5">tryGetCPUName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader32">XCOFFSectionHeader32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a41f5c1c033252b29eff739805332e">sectionHeaderTable32</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader64">XCOFFSectionHeader64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de119306337ed05c6faf9ecf525c78d">sectionHeaderTable64</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b27708c53e9dcbb87802cf82ed9dd10">sectionHeaderTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26076bb887d165577101ce3f6a98cc23">getFileHeaderSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b1abc3ff0f3a294be97817474a9353">getSectionHeaderSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader32">XCOFFSectionHeader32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010639179ea08fc03d46929a3bda8e89">toSection32</a> (DataRefImpl Ref) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader64">XCOFFSectionHeader64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0d50c9f7c051f83f35e1182b700cc7">toSection64</a> (DataRefImpl Ref) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ba7a0e9d2b9ad23c65bcb316e56b18f">getSectionHeaderTableAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac850df4e27757dd0e58fedb0e93df6d8">getEndOfSymbolTableAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16ad233c040f4424ff10d3c68070eb2">getSectionByType</a> (XCOFF::SectionTypeFlags SectType) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b992a20be6fecf5e2c0713bb4305d3">getSectionFileOffsetToRawData</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd6fc025cecfba0c10106bce6dad8ab">getSectionNameInternal</a> (DataRefImpl Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63e0c9049ae15ced35e8016bb404483">checkSectionAddress</a> (uintptr_t Addr, uintptr_t TableAddr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e6780df3a2a12a9cf34c0d2209b9dc4">FileHeader</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff0c79df95344eb737da48722a5f464">AuxiliaryHeader</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64b87d6040467af7b23ba5ba1d3ddcde">SectionHeaderTable</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584acc1e18e9b4dd50378e072ceca649">SymbolTblPtr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/object/xcoffstringtable">XCOFFStringTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac562f918c837e001924c99edbc256cb2">StringTable</a> = {0, nullptr}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d87919540a6096c1a44308a603c50e">getAdvancedSymbolEntryAddress</a> (uintptr_t CurrentAddress, uint32_t Distance)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf58be8f379f16c99d5fd5495dfcd37">classof</a> (const Binary *B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a371754173b32502a6ed52f1519b5dad2">isReservedSectionNumber</a> (int16_t SectionNumber)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile">XCOFFObjectFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eacb85f74f8671df84f4dc0fcd6af8b">create</a> (unsigned Type, MemoryBufferRef MBR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/xcoffstringtable">XCOFFStringTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9f698a0f51cf13c7956ebf5999cb1f">parseStringTable</a> (const XCOFFObjectFile *Obj, uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93327876b6ec870ac115c49a5322cd8c">InvalidRelocOffset</a> = ...</td>
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


<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### xcoff\_symbol\_iterator\_range {#a63b3a10b03e16984050ca82558844a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::object::XCOFFObjectFile::xcoff_symbol_iterator_range =  iterator_range&lt;xcoff_symbol_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ObjectFile::createXCOFFObjectFile {#a027f9711f9c345de769b868de76c0e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> &gt; &gt; <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object, unsigned FileType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### XCOFFObjectFile() {#ab344ce30b163d18efac6a31c246c6715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::XCOFFObjectFile::XCOFFObjectFile (unsigned Type, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Object)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### auxiliaryHeader32() {#a14b00595211ef1000d4a542193fb145c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFAuxiliaryHeader32 * llvm::object::XCOFFObjectFile::auxiliaryHeader32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>, <a href="#a2070c5afcd8a8d3007661a9405939067">getStartAddress</a> and <a href="#a26063993809b386ab934532d1af8b56c">getSymbolFlags</a>.</p>

</div>
</div>

### auxiliaryHeader64() {#a665a053ea13974dd63d7a9d4b352a968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFAuxiliaryHeader64 * llvm::object::XCOFFObjectFile::auxiliaryHeader64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a> and <a href="#a2070c5afcd8a8d3007661a9405939067">getStartAddress</a>.</p>

</div>
</div>

### checkSymbolEntryPointer() {#aafddeca2e7b57e958a25b8660f735cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::XCOFFObjectFile::checkSymbolEntryPointer (uintptr_t SymbolEntPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a>.</p>


<p>Referenced by <a href="#adc06f8608837a3bcad0809f49025d9d9">moveSymbolNext</a>.</p>

</div>
</div>

### fileHeader32() {#a5b7e829b257d3ddebc7532bc2633c918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFFileHeader32 * llvm::object::XCOFFObjectFile::fileHeader32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#ad2569b6fc611ce03c731b44d248e1d34">getFlags</a>, <a href="#af7b952b9a3a6f0f03c1b9845e865f8a0">getLogicalNumberOfSymbolTableEntries32</a>, <a href="#aae468bb7b7f91eceb924829d6ab30c69">getMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>, <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a>, <a href="#a698cd79926f41067466d4420db3b97c3">getOptionalHeaderSize</a>, <a href="#a5f4e00e4e4af365bb00455c632fdd458">getRawNumberOfSymbolTableEntries32</a>, <a href="#a2d2f44591afeb9844d2c707d0c3e627f">getSymbolTableOffset32</a>, <a href="#adba98e29c6eb5c27012cca6628555cff">getTimeStamp</a> and <a href="#aeb2a3a5a47c2b59a6e76774c5f2d6bba">isRelocatableObject</a>.</p>

</div>
</div>

### fileHeader64() {#a19f13af7b6d6631c60f80c484f548c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFFileHeader64 * llvm::object::XCOFFObjectFile::fileHeader64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#ad2569b6fc611ce03c731b44d248e1d34">getFlags</a>, <a href="#aae468bb7b7f91eceb924829d6ab30c69">getMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>, <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a>, <a href="#a6183def919d99ddf97174e12ec154882">getNumberOfSymbolTableEntries64</a>, <a href="#a698cd79926f41067466d4420db3b97c3">getOptionalHeaderSize</a>, <a href="#a74bf9fdb3b2f056dcfc220a4b762851e">getSymbolTableOffset64</a>, <a href="#adba98e29c6eb5c27012cca6628555cff">getTimeStamp</a> and <a href="#aeb2a3a5a47c2b59a6e76774c5f2d6bba">isRelocatableObject</a>.</p>

</div>
</div>

### getArch() {#ac732436ad66c12e6a2387b56ad6bd2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType llvm::object::XCOFFObjectFile::getArch ()</td>
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



<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>.</p>

</div>
</div>

### getBytesInAddress() {#a02bb9315b2af1d734736ec4e427e3504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::XCOFFObjectFile::getBytesInAddress ()</td>
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

<p>The number of bytes used to represent an address in this object file format.</p>

<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getCFileName() {#a0a3b971352558436572c0f3a6efc3f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getCFileName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileauxent">XCOFFFileAuxEnt</a> * CFileEntPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#abf04cdbb3bd4b5dc04636289e70ad71f">llvm::object::generateXCOFFFixedNameStringRef</a>, <a href="#a928be9f8ad2d5fda0dc77b3e55fa352d">getStringTableEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileauxent/nameinstrtbltype/#a8ccd87d5f76fa488a667f3e706066d32">llvm::object::XCOFFFileAuxEnt::NameInStrTblType::Magic</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileauxent/#ae9769122b92d152c4c45fe71004dea60">llvm::object::XCOFFFileAuxEnt::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#ade25d600bbb69175395c080937b26432af61f2d9adb48d75296456e11766f3d5f">llvm::object::XCOFFSymbolRef::NAME_IN_STR_TBL_MAGIC</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileauxent/#a4ec230947afe853a8e39338d6b39683a">llvm::object::XCOFFFileAuxEnt::NameInStrTbl</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileauxent/nameinstrtbltype/#aaa8339b4331b4aa704adb9002e829238">llvm::object::XCOFFFileAuxEnt::NameInStrTblType::Offset</a>.</p>

</div>
</div>

### getCommonSymbolSizeImpl() {#a69c221e2f2dc591094cf0b0d92fd42d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getCommonSymbolSizeImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a6cc14b2dc032a8e267ab859663f09108">llvm::object::XCOFFCsectAuxRef::getSectionOrLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a4bb4dcacc2b9e1dadcd353b2a4245cd3">llvm::object::XCOFFCsectAuxRef::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a306cbb4386d868083a86447946e6ef6b">llvm::object::XCOFFSymbolRef::isCsectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fa533de1d99e6b391e90e30a38b9e3a954">llvm::XCOFF::XTY_CM</a>.</p>

</div>
</div>

### getExceptionEntries() {#a2171b8599a07a37e7a4f18b12d7ff312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ExceptEnt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template LLVM_EXPORT_TEMPLATE Expected&lt; ArrayRef&lt; ExceptionSectionEntry64 &gt; &gt; llvm::object::XCOFFObjectFile::getExceptionEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5524d5f35cbfb6846573bdf5e60e08c2">getSectionSize</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeabda15739c5c07c0ac38280faaa4a2306">llvm::XCOFF::STYP_EXCEPT</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getFeatures() {#aa7b6277ee4861daab6273ccb0330f650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SubtargetFeatures &gt; llvm::object::XCOFFObjectFile::getFeatures ()</td>
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



<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getFileFormatName() {#a8b5bcc9e485a23061cdef3497a43f13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::XCOFFObjectFile::getFileFormatName ()</td>
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



<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getFlags() {#ad2569b6fc611ce03c731b44d248e1d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::XCOFFObjectFile::getFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#ab5f398c8986b5951c9b4c7bf6d7207f9">llvm::object::XCOFFFileHeader32::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#a0d70ea4670b72cdb35067f51bb26df1c">llvm::object::XCOFFFileHeader64::Flags</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getImportFileTable() {#a81ef70b0779ce0c0e0f41c320c1f355a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getImportFileTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a008429291a0c1d14927d2b28302c7e85">llvm::object::getObject</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionheader32/#a0d3cc6d3d95ab329d85ef408107b3c19">llvm::object::LoaderSectionHeader32::LengthOfImpidStrTbl</a>, <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionheader64/#a1445584bd36b265dde0d4eb855aa989d">llvm::object::LoaderSectionHeader64::LengthOfImpidStrTbl</a>, <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionheader32/#ad4062868147ff89def184e4757da46f6">llvm::object::LoaderSectionHeader32::OffsetToImpid</a>, <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionheader64/#a9861b1f323b37cdbd8932c8572d7e12e">llvm::object::LoaderSectionHeader64::OffsetToImpid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea18317b81fd433739e8c447d1b1b93d32">llvm::XCOFF::STYP_LOADER</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>

</div>
</div>

### getLogicalNumberOfSymbolTableEntries32() {#af7b952b9a3a6f0f03c1b9845e865f8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFObjectFile::getLogicalNumberOfSymbolTableEntries32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>.</p>


<p>Referenced by <a href="#a4e67cafd95aae0e63fb1bc2cc11f8884">getNumberOfSymbolTableEntries</a> and <a href="#a5608b1db31841e33e852d5e8e7362523">getRelocationSymbol</a>.</p>

</div>
</div>

### getMagic() {#aae468bb7b7f91eceb924829d6ab30c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::XCOFFObjectFile::getMagic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#a1667ca69f5e230a3a57f7658cc5c10ae">llvm::object::XCOFFFileHeader32::Magic</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#afb0bb5a24d2fec7561ae6f0adf1cc0bf">llvm::object::XCOFFFileHeader64::Magic</a>.</p>

</div>
</div>

### getNumberOfRelocationEntries() {#a8b8e8f5c674a66e5bcb4c9554864267d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::object::XCOFFObjectFile::getNumberOfRelocationEntries (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader">XCOFFSectionHeader</a>&lt; T &gt; &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#aa4c2e75ac22d396f86f5ed6a29698bd0">llvm::XCOFF::RelocOverflow</a>, <a href="#a180352eb59cde1ec5c850d9f80affdf0">sections32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeac5d245ccdee6f92a2b232f49c0b4c41e">llvm::XCOFF::STYP_OVRFLO</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#adeb534d315c9a390fc59cdef8e9f261a">relocations</a>.</p>

</div>
</div>

### getNumberOfSections() {#a7bf43f77e02d30fdc343d9b1c9b69784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::XCOFFObjectFile::getNumberOfSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#a9b47ff19c1ba0961d2bbce18410b5b3c">llvm::object::XCOFFFileHeader32::NumberOfSections</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#ab916a2f972b11f0efd20fa66714d4a76">llvm::object::XCOFFFileHeader64::NumberOfSections</a>.</p>


<p>Referenced by <a href="#a5429091cffadaa5d1ff0557b20aef3af">getRelocationOffset</a>, <a href="#a01bffc145ade7d36357a22aec0c22b4e">getSectionByNum</a>, <a href="#af23bd63f7e9ab9c9da2bffd45a529a6e">section_end</a>, <a href="#a180352eb59cde1ec5c850d9f80affdf0">sections32</a> and <a href="#a1dc2b0967dae6ef3524da67639142067">sections64</a>.</p>

</div>
</div>

### getNumberOfSymbolTableEntries() {#a4e67cafd95aae0e63fb1bc2cc11f8884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFObjectFile::getNumberOfSymbolTableEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 890 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b952b9a3a6f0f03c1b9845e865f8a0">getLogicalNumberOfSymbolTableEntries32</a>, <a href="#a6183def919d99ddf97174e12ec154882">getNumberOfSymbolTableEntries64</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#a7051daf7cb225b8eaaf0028fac5b6b25">getSymbolNameByIndex</a> and <a href="#abc7d6556798e014fdfae78bc0b3d5235">symbol_end</a>.</p>

</div>
</div>

### getNumberOfSymbolTableEntries64() {#a6183def919d99ddf97174e12ec154882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFObjectFile::getNumberOfSymbolTableEntries64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#aa6799d6beed3e048cd3f3359654068a9">llvm::object::XCOFFFileHeader64::NumberOfSymTableEntries</a>.</p>


<p>Referenced by <a href="#a4e67cafd95aae0e63fb1bc2cc11f8884">getNumberOfSymbolTableEntries</a> and <a href="#a5608b1db31841e33e852d5e8e7362523">getRelocationSymbol</a>.</p>

</div>
</div>

### getOptionalHeaderSize() {#a698cd79926f41067466d4420db3b97c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::XCOFFObjectFile::getOptionalHeaderSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#a730b0169e99be44f0a295ec3d3642467">llvm::object::XCOFFFileHeader32::AuxHeaderSize</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#a0ec1f9c5cb12549ff9504c765a78f8ee">llvm::object::XCOFFFileHeader64::AuxHeaderSize</a>, <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getPointerToSymbolTable() {#a03c4c87bba85f9c8594dda9ba9edea99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * llvm::object::XCOFFObjectFile::getPointerToSymbolTable ()</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a0c320b3e81e7f30b610142e8103b91ea">getSymbolEntryAddressByIndex</a>.</p>

</div>
</div>

### getRawData() {#acd35d32e09260ea392203103e472465c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getRawData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Start, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#afc55f34d54c38dcea2d603b5dd7c902f">llvm::object::Binary::checkOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getRawNumberOfSymbolTableEntries32() {#a5f4e00e4e4af365bb00455c632fdd458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::XCOFFObjectFile::getRawNumberOfSymbolTableEntries32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#a1a6a80bb7fbff44ac4796148237d1195">llvm::object::XCOFFFileHeader32::NumberOfSymTableEntries</a>.</p>

</div>
</div>

### getRelocationOffset() {#a5429091cffadaa5d1ff0557b20aef3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getRelocationOffset (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the relocation offset with the base address of the containing section as zero, or InvalidRelocOffset on errors (such as a relocation that does not refer to an address in any section).</p></dd>
</dl>


<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a93327876b6ec870ac115c49a5322cd8c">InvalidRelocOffset</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader32/#a1ce3b6485685d5d29a878256f559f361">llvm::object::XCOFFSectionHeader32::SectionSize</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader64/#a3218c13f05d27d73620dd4e0c5042964">llvm::object::XCOFFSectionHeader64::SectionSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader32/#a87aeeaf45253005060b074fecb8692e1">llvm::object::XCOFFSectionHeader32::VirtualAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsectionheader64/#a0ac45f1cd5a0031446e8898db293d91f">llvm::object::XCOFFSectionHeader64::VirtualAddress</a>.</p>

</div>
</div>

### getRelocationSymbol() {#a5608b1db31841e33e852d5e8e7362523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_iterator llvm::object::XCOFFObjectFile::getRelocationSymbol (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Declaration at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#af7b952b9a3a6f0f03c1b9845e865f8a0">getLogicalNumberOfSymbolTableEntries32</a>, <a href="#a6183def919d99ddf97174e12ec154882">getNumberOfSymbolTableEntries64</a>, <a href="#a0c320b3e81e7f30b610142e8103b91ea">getSymbolEntryAddressByIndex</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="#abc7d6556798e014fdfae78bc0b3d5235">symbol_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>

</div>
</div>

### getRelocationType() {#aca463bc4ee33dc722f5e86de9d45960a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getRelocationType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel)</td>
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



<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>

</div>
</div>

### getRelocationTypeName() {#a181019615fec687b5203ba7489f65613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::XCOFFObjectFile::getRelocationTypeName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Rel, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Result)</td>
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



<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a45337c02ef6094e30bf7aa0e1dc8826c">llvm::XCOFF::getRelocationTypeString</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>

</div>
</div>

### getSectionAddress() {#a97c03084606f192cd1032910070316a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSectionAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getSectionAlignment() {#aaf1e44a6253c5cfd1ea8fbb479cea6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSectionAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getSectionByNum() {#a01bffc145ade7d36357a22aec0c22b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DataRefImpl &gt; llvm::object::XCOFFObjectFile::getSectionByNum (int16_t Num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0eb32107433e870b9384b4768c2ce11">llvm::object::getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20a0352e6404e8f88399d202d70b5bf34f9">llvm::object::invalid_section_index</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#af0d12d4046ba19c552b1e86fbe25abe9">getSymbolSection</a>, <a href="#a90303baf9d185097198f817b998136a6">getSymbolSectionName</a> and <a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a>.</p>

</div>
</div>

### getSectionContents() {#a9800b5c811f6cb665c2c118d1ceccb54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; uint8_t &gt; &gt; llvm::object::XCOFFObjectFile::getSectionContents (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#afc55f34d54c38dcea2d603b5dd7c902f">llvm::object::Binary::checkOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a5524d5f35cbfb6846573bdf5e60e08c2">getSectionSize</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="#a3071bf49d31a9daf8a9fae0d9573bfbf">isSectionVirtual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getSectionFileOffsetToRawData() {#a68866f040b091698a4a3bf9c744e263e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uintptr_t &gt; llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData (<a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389ae">XCOFF::SectionTypeFlags</a> SectType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aaa1c9b49781cf9386252a4cf41ab3abc">llvm::object::ObjectFile::base</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ade4b8410fbe0406fc61d1db65d1cfa12">llvm::SmallString&lt; InternalLen &gt;::c_str</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#afc55f34d54c38dcea2d603b5dd7c902f">llvm::object::Binary::checkOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp/#ad2987340f5bfdede1094a2719c29b1ed">ECASE</a>, <a href="#a5524d5f35cbfb6846573bdf5e60e08c2">getSectionSize</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeacb24e90dcfcba01d1c251bcf8b399ef2">llvm::XCOFF::STYP_BSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1e3f056d2214669889fba21e3d949ca3">llvm::XCOFF::STYP_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea91ad18218d1a31d6e08723d07b3df9ba">llvm::XCOFF::STYP_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1dddb836146cb79d721a0eb775a670ab">llvm::XCOFF::STYP_DWARF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeabda15739c5c07c0ac38280faaa4a2306">llvm::XCOFF::STYP_EXCEPT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1f498f3fbb898ea8e37f18e59cf23e39">llvm::XCOFF::STYP_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea18317b81fd433739e8c447d1b1b93d32">llvm::XCOFF::STYP_LOADER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeac5d245ccdee6f92a2b232f49c0b4c41e">llvm::XCOFF::STYP_OVRFLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeaad2dde9fb3e75239c7e4da9337eecd9d">llvm::XCOFF::STYP_PAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeadcf57b5531bdb50652a3604cf820b71d">llvm::XCOFF::STYP_TBSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea233a82ca0336e9be851e053af95ecb5d">llvm::XCOFF::STYP_TDATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea625db7b5bb9b798cf7c4eac884e7722b">llvm::XCOFF::STYP_TEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea096fc439e418e4b17ce41780ff4a9f8d">llvm::XCOFF::STYP_TYPCHK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getSectionFlags() {#a561cf045928b46ca65b204ecbc5875c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::XCOFFObjectFile::getSectionFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#a0d580a4e198fdfb59863606ed199162f">isDebugSection</a>, <a href="#a4722e471ff1ee6061f7f4e265f173833">isSectionBSS</a>, <a href="#a540165da4d0f8e7c070551b19dcbfea5">isSectionData</a> and <a href="#acc70c96004b6684d1f5e67c621827cb2">isSectionText</a>.</p>

</div>
</div>

### getSectionIndex() {#ae9ba86943fe55c4f5afa2bb90fda698e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSectionIndex (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getSectionName() {#a4e555f784aeb3a459128d1d9a2928f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getSectionName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/object/#abf04cdbb3bd4b5dc04636289e70ad71f">llvm::object::generateXCOFFFixedNameStringRef</a>.</p>

</div>
</div>

### getSectionSize() {#a5524d5f35cbfb6846573bdf5e60e08c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSectionSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#a2171b8599a07a37e7a4f18b12d7ff312">getExceptionEntries</a>, <a href="#a9800b5c811f6cb665c2c118d1ceccb54">getSectionContents</a> and <a href="#a68866f040b091698a4a3bf9c744e263e">getSectionFileOffsetToRawData</a>.</p>

</div>
</div>

### getStartAddress() {#a2070c5afcd8a8d3007661a9405939067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::XCOFFObjectFile::getStartAddress ()</td>
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



<p>Declaration at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a14b00595211ef1000d4a542193fb145c">auxiliaryHeader32</a>, <a href="#a665a053ea13974dd63d7a9d4b352a968">auxiliaryHeader64</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcoffauxiliaryheader/#a4d10d37577e4be8ddc2dfdb657d9db87">llvm::object::XCOFFAuxiliaryHeader&lt; T &gt;::getEntryPointAddr</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### getStringTable() {#afcb293c42728a4376167b20a504dcc21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::XCOFFObjectFile::getStringTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getStringTableEntry() {#a928be9f8ad2d5fda0dc77b3e55fa352d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getStringTableEntry (uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#a0a3b971352558436572c0f3a6efc3f60">getCFileName</a>.</p>

</div>
</div>

### getSymbolAddress() {#afbca160cc61e2866976918c03e0135b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::XCOFFObjectFile::getSymbolAddress (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#ab1e1cc599a5a829c5962a07153a9a8c1">llvm::object::XCOFFSymbolRef::getValue</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>

</div>
</div>

### getSymbolAlignment() {#afba35271cc6fce891ce2bda4576c87d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFObjectFile::getSymbolAlignment (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a306cbb4386d868083a86447946e6ef6b">llvm::object::XCOFFSymbolRef::isCsectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>

</div>
</div>

### getSymbolAuxType() {#ac683182aca879fad4c1df1b6a9218c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFF::SymbolAuxType * llvm::object::XCOFFObjectFile::getSymbolAuxType (uintptr_t AuxEntryAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0eb32107433e870b9384b4768c2ce11">llvm::object::getWithOffset</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a44ec76f6bf21a20a2dda440d3a43a2ba">llvm::object::SymbolAuxTypeOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>

</div>
</div>

### getSymbolByIndex() {#a95439c835232ebad9940e1ccaa72e79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::XCOFFObjectFile::getSymbolByIndex (uint32_t Idx)</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a>.</p>

</div>
</div>

### getSymbolEntryAddressByIndex() {#a0c320b3e81e7f30b610142e8103b91ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::XCOFFObjectFile::getSymbolEntryAddressByIndex (uint32_t SymbolTableIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#ac0d87919540a6096c1a44308a603c50e">getAdvancedSymbolEntryAddress</a> and <a href="#a03c4c87bba85f9c8594dda9ba9edea99">getPointerToSymbolTable</a>.</p>


<p>Referenced by <a href="#a5608b1db31841e33e852d5e8e7362523">getRelocationSymbol</a>, <a href="#a7051daf7cb225b8eaaf0028fac5b6b25">getSymbolNameByIndex</a> and <a href="#abc7d6556798e014fdfae78bc0b3d5235">symbol_end</a>.</p>

</div>
</div>

### getSymbolFlags() {#a26063993809b386ab934532d1af8b56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; llvm::object::XCOFFObjectFile::getSymbolFlags (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a14b00595211ef1000d4a542193fb145c">auxiliaryHeader32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a19f57c169e86a4332accccf291954261">llvm::XCOFF::C_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a8f5d26c17483f47bf923e263a4de4c2e">llvm::XCOFF::C_WEAKEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a26ad87605387868c03e36dddba0aff91">llvm::object::XCOFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#af60828c217c51c5f46cf6ecffb526a28">llvm::object::XCOFFSymbolRef::getStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a7033122210368081acb564a69e3ce350">llvm::object::XCOFFSymbolRef::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a306cbb4386d868083a86447946e6ef6b">llvm::object::XCOFFSymbolRef::isCsectSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ab57487d0a7c9b4f4003ba302b693df97af643a34fdae3d8c2e1440c1458f68745">llvm::XCOFF::N_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ab57487d0a7c9b4f4003ba302b693df97a9bda16ced9ef53550951a707d8fb10ef">llvm::XCOFF::N_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad05b784bd1fda8fa92e47f5968bfce29a1574d67d07664912e3e2f871590d7986">llvm::XCOFF::NEW_XCOFF_INTERPRET</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431acc6eb3e8d6f0fb38a6f3eb9ddef198af">llvm::object::BasicSymbolRef::SF_Absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402">llvm::object::BasicSymbolRef::SF_Hidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766">llvm::object::BasicSymbolRef::SF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ea6077f0f2b971e50bbacbc960260a8008">llvm::XCOFF::SYM_V_EXPORTED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a8a4cb520e5c6a7e39926cfe8dae0b73ea5f87b6d679c546ae79ee03411c54a15f">llvm::XCOFF::SYM_V_HIDDEN</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a2cdb7f94606325a22e75e209055edb0d">llvm::XCOFF::VISIBILITY_MASK</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fa533de1d99e6b391e90e30a38b9e3a954">llvm::XCOFF::XTY_CM</a>.</p>

</div>
</div>

### getSymbolIndex() {#a08c80392232d40366a1870cfb8e71c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFObjectFile::getSymbolIndex (uintptr_t SymEntPtr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a>.</p>

</div>
</div>

### getSymbolName() {#a5663d03689c83dfe78cf82f2710c6115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getSymbolName (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#abb68cddc1b5010571d488b639eb9d561">llvm::object::XCOFFSymbolRef::getName</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>


<p>Referenced by <a href="#a7051daf7cb225b8eaaf0028fac5b6b25">getSymbolNameByIndex</a>.</p>

</div>
</div>

### getSymbolNameByIndex() {#a7051daf7cb225b8eaaf0028fac5b6b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getSymbolNameByIndex (uint32_t SymbolTableIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="#a4e67cafd95aae0e63fb1bc2cc11f8884">getNumberOfSymbolTableEntries</a>, <a href="#a0c320b3e81e7f30b610142e8103b91ea">getSymbolEntryAddressByIndex</a>, <a href="#a5663d03689c83dfe78cf82f2710c6115">getSymbolName</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>

</div>
</div>

### getSymbolSection() {#af0d12d4046ba19c552b1e86fbe25abe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; llvm::object::XCOFFObjectFile::getSymbolSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a01bffc145ade7d36357a22aec0c22b4e">getSectionByNum</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a26ad87605387868c03e36dddba0aff91">llvm::object::XCOFFSymbolRef::getSectionNumber</a>, <a href="#af23bd63f7e9ab9c9da2bffd45a529a6e">section_end</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>

</div>
</div>

### getSymbolSectionID() {#a71d6474e0580f137735002afb39321c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::object::XCOFFObjectFile::getSymbolSectionID (<a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a26ad87605387868c03e36dddba0aff91">llvm::object::XCOFFSymbolRef::getSectionNumber</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>

</div>
</div>

### getSymbolSectionName() {#a90303baf9d185097198f817b998136a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFObjectFile::getSymbolSectionName (<a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref">XCOFFSymbolRef</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#abf04cdbb3bd4b5dc04636289e70ad71f">llvm::object::generateXCOFFFixedNameStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a01bffc145ade7d36357a22aec0c22b4e">getSectionByNum</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a26ad87605387868c03e36dddba0aff91">llvm::object::XCOFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ab57487d0a7c9b4f4003ba302b693df97af643a34fdae3d8c2e1440c1458f68745">llvm::XCOFF::N_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ab57487d0a7c9b4f4003ba302b693df97a2c209de094ab85d67d57b03f5976e12c">llvm::XCOFF::N_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ab57487d0a7c9b4f4003ba302b693df97a9bda16ced9ef53550951a707d8fb10ef">llvm::XCOFF::N_UNDEF</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getSymbolSize() {#ad6cf6760f283737b422b80253b8828d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSymbolSize (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a6cc14b2dc032a8e267ab859663f09108">llvm::object::XCOFFCsectAuxRef::getSectionOrLength</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a4bb4dcacc2b9e1dadcd353b2a4245cd3">llvm::object::XCOFFCsectAuxRef::getSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a306cbb4386d868083a86447946e6ef6b">llvm::object::XCOFFSymbolRef::isCsectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fa533de1d99e6b391e90e30a38b9e3a954">llvm::XCOFF::XTY_CM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>

</div>
</div>

### getSymbolTableOffset32() {#a2d2f44591afeb9844d2c707d0c3e627f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFObjectFile::getSymbolTableOffset32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#aebea28e17396a7dfdd5dea02026d5c37">llvm::object::XCOFFFileHeader32::SymbolTableOffset</a>.</p>

</div>
</div>

### getSymbolTableOffset64() {#a74bf9fdb3b2f056dcfc220a4b762851e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSymbolTableOffset64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#a904634c6a20c2f66ab4150a03f50c8fc">llvm::object::XCOFFFileHeader64::SymbolTableOffset</a>.</p>

</div>
</div>

### getSymbolType() {#a606ab46a34eecd59e09198799a982dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolRef::Type &gt; llvm::object::XCOFFObjectFile::getSymbolType (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ab3ab2990d9bd88d3ff52e29f0ad776bf">llvm::XCOFF::C_FILE</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#abb68cddc1b5010571d488b639eb9d561">llvm::object::XCOFFSymbolRef::getName</a>, <a href="#a01bffc145ade7d36357a22aec0c22b4e">getSectionByNum</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a26ad87605387868c03e36dddba0aff91">llvm::object::XCOFFSymbolRef::getSectionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#af60828c217c51c5f46cf6ecffb526a28">llvm::object::XCOFFSymbolRef::getStorageClass</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="#a0d580a4e198fdfb59863606ed199162f">isDebugSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a0b01026129dcc250501775442ac4b2e5">llvm::object::XCOFFSymbolRef::isFunction</a>, <a href="#a4722e471ff1ee6061f7f4e265f173833">isSectionBSS</a>, <a href="#a540165da4d0f8e7c070551b19dcbfea5">isSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049">llvm::object::SymbolRef::ST_Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a771f3523463fc179b4e89f60841a23b8">llvm::object::SymbolRef::ST_File</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f">llvm::object::SymbolRef::ST_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>

</div>
</div>

### getSymbolValueImpl() {#a78b3dd58311eae0ca4186635d31c8655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSymbolValueImpl (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Symb)</td>
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



<p>Declaration at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#ab1e1cc599a5a829c5962a07153a9a8c1">llvm::object::XCOFFSymbolRef::getValue</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>

</div>
</div>

### getTimeStamp() {#adba98e29c6eb5c27012cca6628555cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::object::XCOFFObjectFile::getTimeStamp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#a6432a124f5c990a0a07e09097f5476a1">llvm::object::XCOFFFileHeader32::TimeStamp</a> and <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#a0ab75c802bf4042d36eeba7748b941ab">llvm::object::XCOFFFileHeader64::TimeStamp</a>.</p>

</div>
</div>

### is64Bit() {#ac446bd686a2dd61629879727edb97f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::is64Bit ()</td>
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



<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a60b6c7df2a6f0927102c0e2a23dd0b2e">llvm::object::Binary::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/object/binary/#af4e569b1876c0dbd751c766d6a1b926aaf10c5cafe80d2255fee25e3fb79f4069">llvm::object::Binary::ID_XCOFF64</a>.</p>


<p>Referenced by <a href="#a14b00595211ef1000d4a542193fb145c">auxiliaryHeader32</a>, <a href="#a665a053ea13974dd63d7a9d4b352a968">auxiliaryHeader64</a>, <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a>, <a href="#ac732436ad66c12e6a2387b56ad6bd2ab">getArch</a>, <a href="#a02bb9315b2af1d734736ec4e427e3504">getBytesInAddress</a>, <a href="#a2171b8599a07a37e7a4f18b12d7ff312">getExceptionEntries</a>, <a href="#a8b5bcc9e485a23061cdef3497a43f13a">getFileFormatName</a>, <a href="#ad2569b6fc611ce03c731b44d248e1d34">getFlags</a>, <a href="#a81ef70b0779ce0c0e0f41c320c1f355a">getImportFileTable</a>, <a href="#aae468bb7b7f91eceb924829d6ab30c69">getMagic</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#ae8d3f159178a82a1a29163a8d80070d1">getMemberAlignment</a>, <a href="#a8b8e8f5c674a66e5bcb4c9554864267d">getNumberOfRelocationEntries</a>, <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a>, <a href="#a4e67cafd95aae0e63fb1bc2cc11f8884">getNumberOfSymbolTableEntries</a>, <a href="#a698cd79926f41067466d4420db3b97c3">getOptionalHeaderSize</a>, <a href="#a5429091cffadaa5d1ff0557b20aef3af">getRelocationOffset</a>, <a href="#a5608b1db31841e33e852d5e8e7362523">getRelocationSymbol</a>, <a href="#aca463bc4ee33dc722f5e86de9d45960a">getRelocationType</a>, <a href="#a181019615fec687b5203ba7489f65613">getRelocationTypeName</a>, <a href="#a97c03084606f192cd1032910070316a1">getSectionAddress</a>, <a href="#a9800b5c811f6cb665c2c118d1ceccb54">getSectionContents</a>, <a href="#a561cf045928b46ca65b204ecbc5875c7">getSectionFlags</a>, <a href="#ae9ba86943fe55c4f5afa2bb90fda698e">getSectionIndex</a>, <a href="#a5524d5f35cbfb6846573bdf5e60e08c2">getSectionSize</a>, <a href="#a2070c5afcd8a8d3007661a9405939067">getStartAddress</a>, <a href="#ac683182aca879fad4c1df1b6a9218c1e">getSymbolAuxType</a>, <a href="#a26063993809b386ab934532d1af8b56c">getSymbolFlags</a>, <a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a>, <a href="#adba98e29c6eb5c27012cca6628555cff">getTimeStamp</a>, <a href="#aeb2a3a5a47c2b59a6e76774c5f2d6bba">isRelocatableObject</a>, <a href="#a3071bf49d31a9daf8a9fae0d9573bfbf">isSectionVirtual</a>, <a href="#a80dab119d37a8dd2a3b52ff464e939b2">moveRelocationNext</a>, <a href="#a09d1ca2c06b80838d961631a71384907">section_rel_end</a>, <a href="#a180352eb59cde1ec5c850d9f80affdf0">sections32</a> and <a href="#a1dc2b0967dae6ef3524da67639142067">sections64</a>.</p>

</div>
</div>

### isDebugSection() {#a0d580a4e198fdfb59863606ed199162f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isDebugSection (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a561cf045928b46ca65b204ecbc5875c7">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea91ad18218d1a31d6e08723d07b3df9ba">llvm::XCOFF::STYP_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1dddb836146cb79d721a0eb775a670ab">llvm::XCOFF::STYP_DWARF</a>.</p>


<p>Referenced by <a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a>.</p>

</div>
</div>

### isRelocatableObject() {#aeb2a3a5a47c2b59a6e76774c5f2d6bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isRelocatableObject ()</td>
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

<p>True if this is a relocatable object (.o/.obj).</p>

<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a5b7e829b257d3ddebc7532bc2633c918">fileHeader32</a>, <a href="#a19f13af7b6d6631c60f80c484f548c56">fileHeader64</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader32/#ab5f398c8986b5951c9b4c7bf6d7207f9">llvm::object::XCOFFFileHeader32::Flags</a>, <a href="/web-llvm/docs/api/structs/llvm/object/xcofffileheader64/#a0d70ea4670b72cdb35067f51bb26df1c">llvm::object::XCOFFFileHeader64::Flags</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a5802ca21347dbdd286d7757ce56283b3">llvm::object::NoRelMask</a>.</p>

</div>
</div>

### isSectionBSS() {#a4722e471ff1ee6061f7f4e265f173833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isSectionBSS (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a561cf045928b46ca65b204ecbc5875c7">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeacb24e90dcfcba01d1c251bcf8b399ef2">llvm::XCOFF::STYP_BSS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeadcf57b5531bdb50652a3604cf820b71d">llvm::XCOFF::STYP_TBSS</a>.</p>


<p>Referenced by <a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a>.</p>

</div>
</div>

### isSectionCompressed() {#a8e56dd71da739369797eed90adcd1aa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isSectionCompressed (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### isSectionData() {#a540165da4d0f8e7c070551b19dcbfea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isSectionData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a561cf045928b46ca65b204ecbc5875c7">getSectionFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1e3f056d2214669889fba21e3d949ca3">llvm::XCOFF::STYP_DATA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea233a82ca0336e9be851e053af95ecb5d">llvm::XCOFF::STYP_TDATA</a>.</p>


<p>Referenced by <a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a>.</p>

</div>
</div>

### isSectionText() {#acc70c96004b6684d1f5e67c621827cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isSectionText (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a561cf045928b46ca65b204ecbc5875c7">getSectionFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea625db7b5bb9b798cf7c4eac884e7722b">llvm::XCOFF::STYP_TEXT</a>.</p>

</div>
</div>

### isSectionVirtual() {#a3071bf49d31a9daf8a9fae0d9573bfbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isSectionVirtual (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Reference <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#a9800b5c811f6cb665c2c118d1ceccb54">getSectionContents</a>.</p>

</div>
</div>

### mapDebugSectionName() {#abc07ce668f69931ef8f02942f71c8dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::XCOFFObjectFile::mapDebugSectionName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Maps a debug section name to a standard DWARF section name.</p>

<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a> and <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>

</div>
</div>

### moveRelocationNext() {#a80dab119d37a8dd2a3b52ff464e939b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::XCOFFObjectFile::moveRelocationNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Rel)</td>
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



<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>

</div>
</div>

### moveSectionNext() {#aebff746bf0b2e33d0521c544bbb2b6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::XCOFFObjectFile::moveSectionNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Sec)</td>
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



<p>Declaration at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### moveSymbolNext() {#adc06f8608837a3bcad0809f49025d9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::XCOFFObjectFile::moveSymbolNext (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> &amp; Symb)</td>
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



<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#aafddeca2e7b57e958a25b8660f735cf8">checkSymbolEntryPointer</a>, <a href="#ac0d87919540a6096c1a44308a603c50e">getAdvancedSymbolEntryAddress</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="#a6db838b9f4583e0721a8fb69665af778">toSymbolRef</a>.</p>

</div>
</div>

### relocations() {#adeb534d315c9a390fc59cdef8e9f261a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Shdr, typename Reloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ArrayRef&lt; Reloc &gt; &gt; llvm::object::XCOFFObjectFile::relocations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Shdr &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a2bbd5b7e8ed457b226f0e186ce4bb1c0">llvm::object::Binary::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a8b8e8f5c674a66e5bcb4c9554864267d">getNumberOfRelocationEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a008429291a0c1d14927d2b28302c7e85">llvm::object::getObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0eb32107433e870b9384b4768c2ce11">llvm::object::getWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a14f792635361c0fbd371a68ae0f171a3">llvm::XCOFF::RelocationSerializationSize32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a476cbe7f235a1f6f83c47ac0f27f98cb">llvm::XCOFF::RelocationSerializationSize64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/object/xcoffrelocation/#ac7628f9e0b10c3a71a88985030168481">llvm::object::XCOFFRelocation&lt; llvm::support::ubig32_t &gt;::getRelocatedLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#afaa36a54350700c193a7f2fa00285008">llvm::object::llvm::object::XCOFFObjectFile::relocations&lt; llvm::object::XCOFFSectionHeader32, llvm::object::XCOFFRelocation32 &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a3019d44af7758c50befaa11b48ead3b5">llvm::object::llvm::object::XCOFFObjectFile::relocations&lt; llvm::object::XCOFFSectionHeader64, llvm::object::XCOFFRelocation64 &gt;</a> and <a href="#a09d1ca2c06b80838d961631a71384907">section_rel_end</a>.</p>

</div>
</div>

### section\_begin() {#a065428320f2dc6545e5a6b8d6f85df1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator llvm::object::XCOFFObjectFile::section_begin ()</td>
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



<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>

</div>
</div>

### section\_end() {#af23bd63f7e9ab9c9da2bffd45a529a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_iterator llvm::object::XCOFFObjectFile::section_end ()</td>
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



<p>Declaration at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0eb32107433e870b9384b4768c2ce11">llvm::object::getWithOffset</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a84e7ca90f9c05219e1c82f602bad10fc">llvm::object::ObjectFile::SectionRef</a>.</p>


<p>Referenced by <a href="#af0d12d4046ba19c552b1e86fbe25abe9">getSymbolSection</a>.</p>

</div>
</div>

### section\_rel\_begin() {#aabae0e0e8a8ba4541ffd3e85012dde9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator llvm::object::XCOFFObjectFile::section_rel_begin (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### section\_rel\_end() {#a09d1ca2c06b80838d961631a71384907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator llvm::object::XCOFFObjectFile::section_rel_end (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
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



<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a198fe5e1de4053e999d41555cb796801">llvm::object::ObjectFile::RelocationRef</a> and <a href="#adeb534d315c9a390fc59cdef8e9f261a">relocations</a>.</p>

</div>
</div>

### sections32() {#a180352eb59cde1ec5c850d9f80affdf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; XCOFFSectionHeader32 &gt; llvm::object::XCOFFObjectFile::sections32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>


<p>Referenced by <a href="#a8b8e8f5c674a66e5bcb4c9554864267d">getNumberOfRelocationEntries</a>.</p>

</div>
</div>

### sections64() {#a1dc2b0967dae6ef3524da67639142067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; XCOFFSectionHeader64 &gt; llvm::object::XCOFFObjectFile::sections64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7bf43f77e02d30fdc343d9b1c9b69784">getNumberOfSections</a> and <a href="#ac446bd686a2dd61629879727edb97f3a">is64Bit</a>.</p>

</div>
</div>

### symbol\_begin() {#a6f2700f065d466d121516e7dbaa56348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator llvm::object::XCOFFObjectFile::symbol_begin ()</td>
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



<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>


<p>Referenced by <a href="#af8b2e47a9b79b850895513f344881db0">symbols</a>.</p>

</div>
</div>

### symbol\_end() {#abc7d6556798e014fdfae78bc0b3d5235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">basic_symbol_iterator llvm::object::XCOFFObjectFile::symbol_end ()</td>
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



<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a4e67cafd95aae0e63fb1bc2cc11f8884">getNumberOfSymbolTableEntries</a>, <a href="#a0c320b3e81e7f30b610142e8103b91ea">getSymbolEntryAddressByIndex</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a23fe52bbc164a30ba18e057d37bd2283">llvm::object::ObjectFile::SymbolRef</a>.</p>


<p>Referenced by <a href="#a5608b1db31841e33e852d5e8e7362523">getRelocationSymbol</a> and <a href="#af8b2e47a9b79b850895513f344881db0">symbols</a>.</p>

</div>
</div>

### symbols() {#af8b2e47a9b79b850895513f344881db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFFObjectFile::xcoff_symbol_iterator_range llvm::object::XCOFFObjectFile::symbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="#a6f2700f065d466d121516e7dbaa56348">symbol_begin</a> and <a href="#abc7d6556798e014fdfae78bc0b3d5235">symbol_end</a>.</p>

</div>
</div>

### toSymbolRef() {#a6db838b9f4583e0721a8fb69665af778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFFSymbolRef llvm::object::XCOFFObjectFile::toSymbolRef (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>Referenced by <a href="#a69c221e2f2dc591094cf0b0d92fd42d3">getCommonSymbolSizeImpl</a>, <a href="#afbca160cc61e2866976918c03e0135b6">getSymbolAddress</a>, <a href="#afba35271cc6fce891ce2bda4576c87d5">getSymbolAlignment</a>, <a href="#a26063993809b386ab934532d1af8b56c">getSymbolFlags</a>, <a href="#a5663d03689c83dfe78cf82f2710c6115">getSymbolName</a>, <a href="#af0d12d4046ba19c552b1e86fbe25abe9">getSymbolSection</a>, <a href="#ad6cf6760f283737b422b80253b8828d2">getSymbolSize</a>, <a href="#a606ab46a34eecd59e09198799a982dc4">getSymbolType</a>, <a href="#a78b3dd58311eae0ca4186635d31c8655">getSymbolValueImpl</a> and <a href="#adc06f8608837a3bcad0809f49025d9d9">moveSymbolNext</a>.</p>

</div>
</div>

### tryGetCPUName() {#acabcf83af1313630664523bb37c473f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::object::XCOFFObjectFile::tryGetCPUName ()</td>
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



<p>Declaration at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkSectionAddress() {#af63e0c9049ae15ced35e8016bb404483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::XCOFFObjectFile::checkSectionAddress (uintptr_t Addr, uintptr_t TableAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getEndOfSymbolTableAddress() {#ac850df4e27757dd0e58fedb0e93df6d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::XCOFFObjectFile::getEndOfSymbolTableAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getFileHeaderSize() {#a26076bb887d165577101ce3f6a98cc23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::object::XCOFFObjectFile::getFileHeaderSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionByType() {#ab16ad233c040f4424ff10d3c68070eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::XCOFFObjectFile::getSectionByType (<a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389ae">XCOFF::SectionTypeFlags</a> SectType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionFileOffsetToRawData() {#aa0b992a20be6fecf5e2c0713bb4305d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::getSectionFileOffsetToRawData (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionHeaderSize() {#af8b1abc3ff0f3a294be97817474a9353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::object::XCOFFObjectFile::getSectionHeaderSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionHeaderTableAddress() {#a8ba7a0e9d2b9ad23c65bcb316e56b18f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::XCOFFObjectFile::getSectionHeaderTableAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### getSectionNameInternal() {#a3fd6fc025cecfba0c10106bce6dad8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::object::XCOFFObjectFile::getSectionNameInternal (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### sectionHeaderTable() {#a0b27708c53e9dcbb87802cf82ed9dd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::object::XCOFFObjectFile::sectionHeaderTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### sectionHeaderTable32() {#ae0a41f5c1c033252b29eff739805332e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFSectionHeader32 * llvm::object::XCOFFObjectFile::sectionHeaderTable32 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### sectionHeaderTable64() {#a8de119306337ed05c6faf9ecf525c78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFSectionHeader64 * llvm::object::XCOFFObjectFile::sectionHeaderTable64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### toSection32() {#a010639179ea08fc03d46929a3bda8e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFSectionHeader32 * llvm::object::XCOFFObjectFile::toSection32 (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### toSection64() {#abe0d50c9f7c051f83f35e1182b700cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFSectionHeader64 * llvm::object::XCOFFObjectFile::toSection64 (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> Ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AuxiliaryHeader {#aeff0c79df95344eb737da48722a5f464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::object::XCOFFObjectFile::AuxiliaryHeader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### FileHeader {#a5e6780df3a2a12a9cf34c0d2209b9dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::object::XCOFFObjectFile::FileHeader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### SectionHeaderTable {#a64b87d6040467af7b23ba5ba1d3ddcde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::object::XCOFFObjectFile::SectionHeaderTable = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### StringTable {#ac562f918c837e001924c99edbc256cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFFStringTable llvm::object::XCOFFObjectFile::StringTable = {0, nullptr}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### SymbolTblPtr {#a584acc1e18e9b4dd50378e072ceca649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void* llvm::object::XCOFFObjectFile::SymbolTblPtr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a4bf58be8f379f16c99d5fd5495dfcd37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> * B)</td>
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



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### getAdvancedSymbolEntryAddress() {#ac0d87919540a6096c1a44308a603c50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::XCOFFObjectFile::getAdvancedSymbolEntryAddress (uintptr_t CurrentAddress, uint32_t Distance)</td>
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



<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#ab0eb32107433e870b9384b4768c2ce11">llvm::object::getWithOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ad0cbda82482585d346b65687e2f3a38a">llvm::XCOFF::SymbolTableEntrySize</a>.</p>


<p>Referenced by <a href="#a0c320b3e81e7f30b610142e8103b91ea">getSymbolEntryAddressByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a> and <a href="#adc06f8608837a3bcad0809f49025d9d9">moveSymbolNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### create() {#a5eacb85f74f8671df84f4dc0fcd6af8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; XCOFFObjectFile &gt; &gt; llvm::object::XCOFFObjectFile::create (unsigned Type, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> MBR)</td>
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



<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### isReservedSectionNumber() {#a371754173b32502a6ed52f1519b5dad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFObjectFile::isReservedSectionNumber (int16_t SectionNumber)</td>
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



<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

### parseStringTable() {#a5d9f698a0f51cf13c7956ebf5999cb1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; XCOFFStringTable &gt; llvm::object::XCOFFObjectFile::parseStringTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile">XCOFFObjectFile</a> * Obj, uint64_t Offset)</td>
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



<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### InvalidRelocOffset {#a93327876b6ec870ac115c49a5322cd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFObjectFile::InvalidRelocOffset</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      std::numeric_limits&lt;uint64_t&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()
</div>
</dd>
</dl>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a5429091cffadaa5d1ff0557b20aef3af">getRelocationOffset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
