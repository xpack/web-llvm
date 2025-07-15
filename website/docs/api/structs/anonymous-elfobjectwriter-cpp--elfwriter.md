---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-elfobjectwriter-cpp-/elfwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ELFWriter` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ELFObjectWriter.cpp}::ELFWriter { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b12bf6dc53ccb60d3278d8840adec0e">RevGroupMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DwoMode { <a href="#a42c738c6458b934218c327bf6be7b60d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7691ac6af7315dde5707342149b9eb">ELFWriter</a> (ELFObjectWriter &amp;OWriter, raw_pwrite_stream &amp;OS, bool IsLittleEndian, DwoMode Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40656d9663103c44945a8c495157f0c">addToSectionTable</a> (MCSectionELF *Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a63598e07e4b28ae0c650f52d1e15c4">align</a> (Align Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af699e5a47a59c1c3b1044c30f999df43">maybeWriteCompression</a> (uint32_t ChType, uint64_t Size, SmallVectorImpl&lt; uint8_t &gt; &amp;CompressedContents, Align Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb9a99f53363b940f4690f42f1c2978e">writeWord</a> (uint64_t Word)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7632fee8767231267f8ed73c5a6aa9c4">write</a> (T Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a> (const MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9090caa8ccfc6c4298f8d31ffbc73ca4">writeSymbol</a> (const MCAssembler &amp;Asm, SymbolTableWriter &amp;Writer, uint32_t StringIndex, ELFSymbolData &amp;MSD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a> (MCAssembler &amp;Asm, const RevGroupMapTy &amp;RevGroupMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the symbol table data. <a href="#a701e935a2d02fd488218cf26b8eedb67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7dd59a6310763d432506ca4b036a9a">writeAddrsigSection</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e8d5b5fce0c5c0440880ba3af1e2ca">createRelocationSection</a> (MCContext &amp;Ctx, const MCSectionELF &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b52974bd5074929c1a84c3ad64967a">writeSectionHeaders</a> (const MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1d0c4d37d55950252509e0b0c84501">writeSectionData</a> (const MCAssembler &amp;Asm, MCSection &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad64fa2a6fc581ccd15fff7608d56103">writeSectionHeaderEntry</a> (uint32_t Name, uint32_t Type, uint64_t Flags, uint64_t Address, uint64_t Offset, uint64_t Size, uint32_t Link, uint32_t Info, MaybeAlign Alignment, uint64_t EntrySize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa07832cc5201fc524e000dcc171a70e7">writeRelocations</a> (const MCAssembler &amp;Asm, const MCSectionELF &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a> (uint32_t GroupSymbolIndex, uint64_t Offset, uint64_t Size, const MCSectionELF &amp;Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter">ELFObjectWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{ELFObjectWriter.cpp}<a href="#a42c738c6458b934218c327bf6be7b60d">::ELFWriter::DwoMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2946926354401ab92fb40a35c42958a9">Mode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b4914936f38fc7648e44b4cd02b4c3">LastLocalSymbolIndex</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621a2a2221e5a836f8c49a7bf851366c">StringTableIndex</a> = ~0u</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c4ff8786e9b2bb6fffe2023376fd6a">SymbolTableIndex</a> = ~0u</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6436d785057270262de783c833b271a6">SectionTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58befb331c0a20300b519e2d96ad7efb">symbolValue</a> (const MCAssembler &amp;Asm, const MCSymbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2318eea8f5de4d05db1b3e876649ca2">isInSymtab</a> (const MCAssembler &amp;Asm, const MCSymbolELF &amp;Symbol, bool Used, bool Renamed)</td>
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

## Symbol Table Data Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857f9867463a5a1821ddb7d9f20d45b7">StrTabBuilder</a> {StringTableBuilder::ELF}</td>
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


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RevGroupMapTy {#a6b12bf6dc53ccb60d3278d8840adec0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ELFObjectWriter.cpp}::ELFWriter::RevGroupMapTy =  DenseMap&lt;const MCSymbol *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DwoMode {#a42c738c6458b934218c327bf6be7b60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{ELFObjectWriter.cpp}::ELFWriter::DwoMode </td>
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
<td class="doxyEnumItemName">AllSections<a id="a42c738c6458b934218c327bf6be7b60dac7a0514ed65ec7e07a8516a4502882e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonDwoOnly<a id="a42c738c6458b934218c327bf6be7b60da6fa36e4733e59cacece4264d2e291dc5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DwoOnly<a id="a42c738c6458b934218c327bf6be7b60da2f5553c6916ebe158aa60fe17820139d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFWriter() {#aec7691ac6af7315dde5707342149b9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFWriter (<a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter">ELFObjectWriter</a> &amp; OWriter, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, bool IsLittleEndian, <a href="#a42c738c6458b934218c327bf6be7b60d">DwoMode</a> Mode)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#a2946926354401ab92fb40a35c42958a9">Mode</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a> and <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToSectionTable() {#ab40656d9663103c44945a8c495157f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ELFWriter::addToSectionTable (<a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> * Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="#a6436d785057270262de783c833b271a6">SectionTable</a> and <a href="#a857f9867463a5a1821ddb7d9f20d45b7">StrTabBuilder</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a> and <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### align() {#a5a63598e07e4b28ae0c650f52d1e15c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ELFWriter::align (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a> and <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### computeSymbolTable() {#a701e935a2d02fd488218cf26b8eedb67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::computeSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a6b12bf6dc53ccb60d3278d8840adec0e">RevGroupMapTy</a> &amp; RevGroupMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the symbol table data.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Asm</td>
<td class="doxyParamItemDescription"><p>- The assembler.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RevGroupMap</td>
<td class="doxyParamItemDescription"><p>- Maps a signature symbol to the group section.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#ab40656d9663103c44945a8c495157f0c">addToSectionTable</a>, <a href="#a5a63598e07e4b28ae0c650f52d1e15c4">align</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aae2bf8b46988a2fc0589e95903930c19">llvm::MutableArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a9d959094f4544749c129c46034cbed67">llvm::MutableArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a3908d151fa93bdc906cbf57d96060673">llvm::MCSection::getAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfobjectwriter-cpp-/symboltablewriter/#aabe506660c270bc079d9448f7ed411f8">anonymous{ELFObjectWriter.cpp}::SymbolTableWriter::getShndxIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfobjectwriter-cpp-/#a740acf4dce2922d79f8d78b15d1387bd">anonymous{ELFObjectWriter.cpp}::isDwoSection</a>, <a href="#ad2318eea8f5de4d05db1b3e876649ca2">isInSymtab</a>, <a href="#af3b4914936f38fc7648e44b4cd02b4c3">LastLocalSymbolIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="#a2946926354401ab92fb40a35c42958a9">Mode</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata/#a19416e07574c7ba52698f14cd9363aa2">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFSymbolData::Name</a>, <a href="#a42c738c6458b934218c327bf6be7b60da6fa36e4733e59cacece4264d2e291dc5">NonDwoOnly</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata/#a6b331ceb5d3c933eb803f17d9631bef9">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFSymbolData::Order</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata/#a64e8a48be2bf581ddbed9077518b579e">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFSymbolData::SectionIndex</a>, <a href="#a6436d785057270262de783c833b271a6">SectionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a3e2af52824552afc9a63a0489f9c7ed4">llvm::MCSectionELF::setOffsets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a319b64bc6b9c38e948eda8bfafff58b5">llvm::ELF::SHN_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a39083466eebf0993a765922244288d20">llvm::ELF::SHN_COMMON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5ae3fe714923fc008de6b4078f07accaba">llvm::ELF::SHN_LORESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca973f4a1893cca71a0ec69aa145189486">llvm::ELF::SHT_SYMTAB_SHNDX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a41d1d619e276ea6e4e6e98c4b929ba77a492b026d2205f6f178f7eb7863018e31">llvm::ELF::STB_LOCAL</a>, <a href="#a857f9867463a5a1821ddb7d9f20d45b7">StrTabBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a58921cad23ba8bdf0c8077b7a2923127">llvm::ELF::STT_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a78278359d67657d43c307d922ad9a1d5af3e7284f94dabe52ad31412ab70c15f4">llvm::ELF::STV_DEFAULT</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata/#a8734667f9e5bd9fe2dd43d3cf7964651">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFSymbolData::Symbol</a>, <a href="#a37c4ff8786e9b2bb6fffe2023376fd6a">SymbolTableIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac8e87cd16d53ffeb9af9fee1637039a6a1286e09fce124574524353839d2b1208">llvm::ELF::SYMENTRY_SIZE32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac8e87cd16d53ffeb9af9fee1637039a6a9495757a7e6c5b8d5a22d947daf63961">llvm::ELF::SYMENTRY_SIZE64</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>, <a href="#a7632fee8767231267f8ed73c5a6aa9c4">write</a>, <a href="#a9090caa8ccfc6c4298f8d31ffbc73ca4">writeSymbol</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfobjectwriter-cpp-/symboltablewriter/#a9b91d63de477829a841c50e79b34f52a">anonymous{ELFObjectWriter.cpp}::SymbolTableWriter::writeSymbol</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### createRelocationSection() {#a01e8d5b5fce0c5c0440880ba3af1e2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * ELFWriter::createRelocationSection (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a3c88d87144f11ed223126c42717b91c3">llvm::MCTargetOptions::Crel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a19048a597f3c3778eefb67f07d3d8bc9">llvm::MCSectionELF::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#aba2770972dc030b69d7c4f799eca7441">llvm::MCSectionELF::getGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4e2b2b87092f84d740d8e9f34e8b86ee">llvm::ELF::SHF_INFO_LINK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### is64Bit() {#a9a9c4ee9eececa95401fdf493b822c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFWriter::is64Bit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#a01e8d5b5fce0c5c0440880ba3af1e2ca">createRelocationSection</a>, <a href="#af699e5a47a59c1c3b1044c30f999df43">maybeWriteCompression</a>, <a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>, <a href="#aa07832cc5201fc524e000dcc171a70e7">writeRelocations</a> and <a href="#aaf1d0c4d37d55950252509e0b0c84501">writeSectionData</a>.</p>

</div>
</div>

### maybeWriteCompression() {#af699e5a47a59c1c3b1044c30f999df43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFWriter::maybeWriteCompression (uint32_t ChType, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; CompressedContents, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a> and <a href="#a7632fee8767231267f8ed73c5a6aa9c4">write</a>.</p>


<p>Referenced by <a href="#aaf1d0c4d37d55950252509e0b0c84501">writeSectionData</a>.</p>

</div>
</div>

### write() {#a7632fee8767231267f8ed73c5a6aa9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFObjectWriter.cpp}::ELFWriter::write (T Val)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#af699e5a47a59c1c3b1044c30f999df43">maybeWriteCompression</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a> and <a href="#aa07832cc5201fc524e000dcc171a70e7">writeRelocations</a>.</p>

</div>
</div>

### writeAddrsigSection() {#a3a7dd59a6310763d432506ca4b036a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeAddrsigSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a> and <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### writeHeader() {#a1a77a133bdf741f6950a92f7f0cf64a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4848e3ad29a6f6a8216e031204f636e9a9779724bd5764207594c7f8a5c0be718">llvm::ELF::EI_NIDENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4848e3ad29a6f6a8216e031204f636e9a793e236b3f65263bd0a7818298c7c183">llvm::ELF::EI_PAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5ac700ff9a9a24f46587997e131502702c">llvm::ELF::ELFCLASS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa87228a0d135b2b897952fa11ff023c5a54b4da97cdda07031363b240c26c9794">llvm::ELF::ELFCLASS64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2bafedc8af0121f7104ef49a576b30865de">llvm::ELF::ELFDATA2LSB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a868a39064cf90c55a5a8b267d8018c2ba133a1bcc89f1dca304102b741ecbf299">llvm::ELF::ELFDATA2MSB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a617f2c7a774356b3d2c32f189b8caf95">llvm::ELF::ElfMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4ab209c3746d919aa1b0e0c03ae2f1a38e">llvm::ELF::ELFOSABI_GNU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a71ceb704cd8260b471b28358df7bd0d4afc97566f2e931d4d0e88c4425e88b56b">llvm::ELF::ELFOSABI_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aadbc5ef54c920f724d4e267f41d2c00aaba0cdd056685bc8fe4fab01da806afdc">llvm::ELF::ET_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a0cdd5ed818007673314ddf36d90c4731afbed835612b6e8c447d0233b4311ab4c">llvm::ELF::EV_CURRENT</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5ae3fe714923fc008de6b4078f07accaba">llvm::ELF::SHN_LORESERVE</a>, <a href="#a621a2a2221e5a836f8c49a7bf851366c">StringTableIndex</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a> and <a href="#adb9a99f53363b940f4690f42f1c2978e">writeWord</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### writeObject() {#a27e478bd5208561e8eb16ec550509761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ELFWriter::writeObject (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#ab40656d9663103c44945a8c495157f0c">addToSectionTable</a>, <a href="#a5a63598e07e4b28ae0c650f52d1e15c4">align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#a01e8d5b5fce0c5c0440880ba3af1e2ca">createRelocationSection</a>, <a href="#a42c738c6458b934218c327bf6be7b60da2f5553c6916ebe158aa60fe17820139d">DwoOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a04990a85b6279a802df811663e2852f5">llvm::MCSection::getOrdinal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp/#ab138684de9096eb96683328900f78e48">Groups</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a6fce6a65c0d14e10427b3082f129db7fa85923f836a85bbea451954a76a79ed89">llvm::ELF::GRP_COMDAT</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfobjectwriter-cpp-/#a740acf4dce2922d79f8d78b15d1387bd">anonymous{ELFObjectWriter.cpp}::isDwoSection</a>, <a href="#a2946926354401ab92fb40a35c42958a9">Mode</a>, <a href="#a42c738c6458b934218c327bf6be7b60da6fa36e4733e59cacece4264d2e291dc5">NonDwoOnly</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#a9a004bff5f9c00b2ede3a52c93c665c2">llvm::raw_pwrite_stream::pwrite</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="#a6436d785057270262de783c833b271a6">SectionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a3e2af52824552afc9a63a0489f9c7ed4">llvm::MCSectionELF::setOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a87c843b7d5be00f8abfc1311db9522df">llvm::MCSection::setOrdinal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4ed5db5129e0b0fe70bf59b691698a72">llvm::ELF::SHF_EXCLUDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5ae3fe714923fc008de6b4078f07accaba">llvm::ELF::SHN_LORESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5a742dfa2d775f5b3b041d915133f9356b">llvm::ELF::SHN_UNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca9d2a9add5afe20c3d863e720a8864898">llvm::ELF::SHT_LLVM_ADDRSIG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca095782f71f1df92eff34130f8a6d15f5">llvm::ELF::SHT_STRTAB</a>, <a href="#a621a2a2221e5a836f8c49a7bf851366c">StringTableIndex</a>, <a href="#a857f9867463a5a1821ddb7d9f20d45b7">StrTabBuilder</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>, <a href="#a7632fee8767231267f8ed73c5a6aa9c4">write</a>, <a href="#a3a7dd59a6310763d432506ca4b036a9a">writeAddrsigSection</a>, <a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a>, <a href="#aa07832cc5201fc524e000dcc171a70e7">writeRelocations</a>, <a href="#aaf1d0c4d37d55950252509e0b0c84501">writeSectionData</a> and <a href="#a83b52974bd5074929c1a84c3ad64967a">writeSectionHeaders</a>.</p>

</div>
</div>

### writeRelocations() {#aa07832cc5201fc524e000dcc171a70e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeRelocations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions/#a3c88d87144f11ed223126c42717b91c3">llvm::MCTargetOptions::Crel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daaf29cd80fceba94e4f48b143fcf354c6">llvm::ELF::EM_MIPS</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp/#a53fddd8023ad4026f03d60903b0c6702">encodeCrel</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="#af943c786b03d08b35be07dd83fde0d07">OWriter</a>, <a href="/web-llvm/docs/api/structs/llvm/elf/elf32-rela/#a35fe5be6ddd3ff8a32cb48749f573bbe">llvm::ELF::Elf32_Rela::r_info</a>, <a href="/web-llvm/docs/api/structs/llvm/elf/elf64-rela/#a892ef7affa08869fb4a889c23577ec05">llvm::ELF::Elf64_Rela::r_info</a>, <a href="/web-llvm/docs/api/structs/llvm/elf/elf32-rela/#ada6e1f1789bb65d344b25f7c1eff1b94">llvm::ELF::Elf32_Rela::setSymbolAndType</a>, <a href="/web-llvm/docs/api/structs/llvm/elf/elf64-rela/#a4bfde51b35a2e85f27c34460a7bd9bcb">llvm::ELF::Elf64_Rela::setSymbolAndType</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a> and <a href="#a7632fee8767231267f8ed73c5a6aa9c4">write</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### writeSectionData() {#aaf1d0c4d37d55950252509e0b0c84501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeSectionData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/compression/#afa6436cae5aba19d74d91f619ac7a635">llvm::compression::compress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a681bb951252b254fd6af44d47474efbdaf5e9aabfafb8c5e3c4834642384d5773">llvm::ELF::ELFCOMPRESS_ZLIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a681bb951252b254fd6af44d47474efbda435e5766a889b67965653c7c50936573">llvm::ELF::ELFCOMPRESS_ZSTD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a3908d151fa93bdc906cbf57d96060673">llvm::MCSection::getAlign</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af699e5a47a59c1c3b1044c30f999df43">maybeWriteCompression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015abf799091c82aff654ed25824e734ffcc">llvm::ELF::SHF_COMPRESSED</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeeb5973ff74c4c4d279e275b34b7ef54">llvm::toStringRef</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00ad697a787afbc87e2117697b91ed26272">llvm::Zlib</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa100a124c9d33561b0950011928aae00a0c8468c9ff2f38e853335e1e40ade4c3">llvm::Zstd</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### writeSectionHeader() {#aeaa22f130bcc2796a4d90a2be0e2fe38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeSectionHeader (uint32_t GroupSymbolIndex, uint64_t Offset, uint64_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a04990a85b6279a802df811663e2852f5">llvm::MCSection::getOrdinal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>, <a href="#af3b4914936f38fc7648e44b4cd02b4c3">LastLocalSymbolIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca8c63cb324623b483b1b1b1fb1b575447">llvm::ELF::SHT_DYNAMIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1771b2365460420ea3aee1fa4c324c99">llvm::ELF::SHT_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca9d2a9add5afe20c3d863e720a8864898">llvm::ELF::SHT_LLVM_ADDRSIG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca3b34c61cc0e95c91405e13c12da52925">llvm::ELF::SHT_LLVM_CALL_GRAPH_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca973f4a1893cca71a0ec69aa145189486">llvm::ELF::SHT_SYMTAB_SHNDX</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a621a2a2221e5a836f8c49a7bf851366c">StringTableIndex</a>, <a href="#a857f9867463a5a1821ddb7d9f20d45b7">StrTabBuilder</a>, <a href="#a37c4ff8786e9b2bb6fffe2023376fd6a">SymbolTableIndex</a> and <a href="#aad64fa2a6fc581ccd15fff7608d56103">writeSectionHeaderEntry</a>.</p>


<p>Referenced by <a href="#a83b52974bd5074929c1a84c3ad64967a">writeSectionHeaders</a>.</p>

</div>
</div>

### writeSectionHeaderEntry() {#aad64fa2a6fc581ccd15fff7608d56103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeSectionHeaderEntry (uint32_t Name, uint32_t Type, uint64_t Flags, uint64_t Address, uint64_t Offset, uint64_t Size, uint32_t Link, uint32_t Info, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, uint64_t EntrySize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a> and <a href="#adb9a99f53363b940f4690f42f1c2978e">writeWord</a>.</p>


<p>Referenced by <a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a> and <a href="#a83b52974bd5074929c1a84c3ad64967a">writeSectionHeaders</a>.</p>

</div>
</div>

### writeSectionHeaders() {#a83b52974bd5074929c1a84c3ad64967a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeSectionHeaders (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="#a6436d785057270262de783c833b271a6">SectionTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aeec78f1526015355c4756622c5e64ed5ae3fe714923fc008de6b4078f07accaba">llvm::ELF::SHN_LORESERVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca81286d3a2a72a87d1bd189c76508b9dc">llvm::ELF::SHT_CREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcadb5044a1bd05d2a84193fb0eb9b9df12">llvm::ELF::SHT_DYNSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1771b2365460420ea3aee1fa4c324c99">llvm::ELF::SHT_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1fc220dae6e53d3aca8d431cd209e74e">llvm::ELF::SHT_REL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad32bebb3c18c53470e49d5ad192e1158">llvm::ELF::SHT_RELA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca095782f71f1df92eff34130f8a6d15f5">llvm::ELF::SHT_STRTAB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca4f0cd819b71791cb5a1945952dbc9166">llvm::ELF::SHT_SYMTAB</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>, <a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a> and <a href="#aad64fa2a6fc581ccd15fff7608d56103">writeSectionHeaderEntry</a>.</p>


<p>Referenced by <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### writeSymbol() {#a9090caa8ccfc6c4298f8d31ffbc73ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFWriter::writeSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/anonymous-elfobjectwriter-cpp-/symboltablewriter">SymbolTableWriter</a> &amp; Writer, uint32_t StringIndex, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata">ELFSymbolData</a> &amp; MSD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a9756a579fc66a3fbcc6d3e82866a289f">llvm::MCExpr::evaluateKnownAbsolute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf/#a83461ac06968f969da6b77b0e3e90527">llvm::MCSymbolELF::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp/#af36ade7f203b60e63b920bb1f086df7c">isIFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp/#a25936820f84b7fc98c3c892bc0ddbf5c">mergeTypeForSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata/#a64e8a48be2bf581ddbed9077518b579e">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFSymbolData::SectionIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a7269ceaea4bf3dbd15caa427598cbcb9">llvm::ELF::STT_GNU_IFUNC</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/elfsymboldata/#a8734667f9e5bd9fe2dd43d3cf7964651">anonymous{ELFObjectWriter.cpp}::ELFWriter::ELFSymbolData::Symbol</a>, <a href="#a58befb331c0a20300b519e2d96ad7efb">symbolValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfobjectwriter-cpp-/symboltablewriter/#a9b91d63de477829a841c50e79b34f52a">anonymous{ELFObjectWriter.cpp}::SymbolTableWriter::writeSymbol</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>.</p>

</div>
</div>

### writeWord() {#adb9a99f53363b940f4690f42f1c2978e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ELFObjectWriter.cpp}::ELFWriter::writeWord (uint64_t Word)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a> and <a href="#a619b2e3eb5744ddcc838d7128c63226c">W</a>.</p>


<p>Referenced by <a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a> and <a href="#aad64fa2a6fc581ccd15fff7608d56103">writeSectionHeaderEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LastLocalSymbolIndex {#af3b4914936f38fc7648e44b4cd02b4c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ELFObjectWriter.cpp}::ELFWriter::LastLocalSymbolIndex = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a> and <a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a>.</p>

</div>
</div>

### Mode {#a2946926354401ab92fb40a35c42958a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{ELFObjectWriter.cpp}::ELFWriter::DwoMode anonymous{ELFObjectWriter.cpp}::ELFWriter::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#aec7691ac6af7315dde5707342149b9eb">ELFWriter</a> and <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>.</p>

</div>
</div>

### OWriter {#af943c786b03d08b35be07dd83fde0d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFObjectWriter&amp; anonymous{ELFObjectWriter.cpp}::ELFWriter::OWriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#a01e8d5b5fce0c5c0440880ba3af1e2ca">createRelocationSection</a>, <a href="#aec7691ac6af7315dde5707342149b9eb">ELFWriter</a>, <a href="#a9a9c4ee9eececa95401fdf493b822c2b">is64Bit</a>, <a href="#a3a7dd59a6310763d432506ca4b036a9a">writeAddrsigSection</a>, <a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a> and <a href="#aa07832cc5201fc524e000dcc171a70e7">writeRelocations</a>.</p>

</div>
</div>

### SectionTable {#a6436d785057270262de783c833b271a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MCSectionELF *&gt; anonymous{ELFObjectWriter.cpp}::ELFWriter::SectionTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ab40656d9663103c44945a8c495157f0c">addToSectionTable</a>, <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a> and <a href="#a83b52974bd5074929c1a84c3ad64967a">writeSectionHeaders</a>.</p>

</div>
</div>

### StringTableIndex {#a621a2a2221e5a836f8c49a7bf851366c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ELFObjectWriter.cpp}::ELFWriter::StringTableIndex = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a> and <a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a>.</p>

</div>
</div>

### SymbolTableIndex {#a37c4ff8786e9b2bb6fffe2023376fd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ELFObjectWriter.cpp}::ELFWriter::SymbolTableIndex = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a> and <a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a>.</p>

</div>
</div>

### W {#a619b2e3eb5744ddcc838d7128c63226c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::endian::Writer anonymous{ELFObjectWriter.cpp}::ELFWriter::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a5a63598e07e4b28ae0c650f52d1e15c4">align</a>, <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#aec7691ac6af7315dde5707342149b9eb">ELFWriter</a>, <a href="#a7632fee8767231267f8ed73c5a6aa9c4">write</a>, <a href="#a3a7dd59a6310763d432506ca4b036a9a">writeAddrsigSection</a>, <a href="#a1a77a133bdf741f6950a92f7f0cf64a3">writeHeader</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a>, <a href="#aa07832cc5201fc524e000dcc171a70e7">writeRelocations</a>, <a href="#aaf1d0c4d37d55950252509e0b0c84501">writeSectionData</a>, <a href="#aad64fa2a6fc581ccd15fff7608d56103">writeSectionHeaderEntry</a>, <a href="#a83b52974bd5074929c1a84c3ad64967a">writeSectionHeaders</a> and <a href="#adb9a99f53363b940f4690f42f1c2978e">writeWord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isInSymtab() {#ad2318eea8f5de4d05db1b3e876649ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ELFWriter::isInSymtab (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> &amp; Symbol, bool Used, bool Renamed)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a579f54f07d96da2627125a17e0353b14">llvm::ELF::STT_SECTION</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4acec19f33bc45f90643617e00ce9a81">llvm::MCSymbolRefExpr::VK_WEAKREF</a>.</p>


<p>Referenced by <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>.</p>

</div>
</div>

### symbolValue() {#a58befb331c0a20300b519e2d96ad7efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ELFWriter::symbolValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a8212a1be8c83903d02e10af1cd534dc7">llvm::MCSymbol::getCommonAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a4e87f4e2c6164013059b777bc2b6cf2a">llvm::MCSymbol::isCommon</a>.</p>


<p>Referenced by <a href="#a9090caa8ccfc6c4298f8d31ffbc73ca4">writeSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Symbol Table Data

### StrTabBuilder {#a857f9867463a5a1821ddb7d9f20d45b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder anonymous{ELFObjectWriter.cpp}::ELFWriter::StrTabBuilder {StringTableBuilder::ELF}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ab40656d9663103c44945a8c495157f0c">addToSectionTable</a>, <a href="#a701e935a2d02fd488218cf26b8eedb67">computeSymbolTable</a>, <a href="#a27e478bd5208561e8eb16ec550509761">writeObject</a> and <a href="#aeaa22f130bcc2796a4d90a2be0e2fe38">writeSectionHeader</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/elfobjectwriter-cpp">ELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
