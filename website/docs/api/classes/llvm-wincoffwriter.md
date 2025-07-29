---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/wincoffwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WinCOFFWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WinCOFFWriter { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873cddead8cb24f63c3f760b64636f5a">symbols</a> = std::vector&lt; std::unique_ptr&lt; COFFSymbol &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b57e72a6aaf9071484114a4b5bf6e08">sections</a> = std::vector&lt; std::unique_ptr&lt; COFFSection &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d31551d47e74edbcb3995d349da2c27">symbol_map</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *, COFFSymbol * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005b9e4e4cea3cd3802cda04bb7f9910">section_map</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *, COFFSection * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab331e7bf0d8b74ebd740b8a0f342f00c">symbol_list</a> = <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; COFFSymbol * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DwoMode { <a href="#adb7920f406fa5aedf5f43f8e5ea74c6b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62cc3a814dc53171f32886aaa2ba8318">WinCOFFWriter</a> (WinCOFFObjectWriter &amp;OWriter, raw_pwrite_stream &amp;OS, DwoMode Mode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e77c3f43a0acf7bdad25ee6308d3812">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb14ab0bcb74e040f599ece0ea8de54">executePostLayoutBinding</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae083e4782d3a3ca6e98fbaacbb8d3f8f">recordRelocation</a> (MCAssembler &amp;Asm, const MCFragment *Fragment, const MCFixup &amp;Fixup, MCValue Target, uint64_t &amp;FixedValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204d14337c246adfd274aac0837c6045">writeObject</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae23544385415140fac111e6d513de04d">getSectionNumber</a> (const MCSection &amp;Section) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">COFFSymbol *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239a97f08170291a953b108aa733ac1d">createSymbol</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">COFFSymbol *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da1595bbf1dbb2d26fc4e3218a46e9c">GetOrCreateCOFFSymbol</a> (const MCSymbol *Symbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">COFFSection *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d99d1a1036350e8fbcb68bc440f6f70">createSection</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec85adf6e48706efa781021674c859f9">defineSection</a> (const MCAssembler &amp;Asm, MCSectionCOFF const &amp;Sec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function takes a section data object from the assembler and creates the associated <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section staging object. <a href="#aec85adf6e48706efa781021674c859f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">COFFSymbol *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c78efab4e4b7ece8f1a665f6f16489">getLinkedSymbol</a> (const MCSymbol &amp;Symbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f758971f2c678319b2789af1377ef11">defineSymbol</a> (const MCAssembler &amp;Asm, const MCSymbol &amp;Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function takes a symbol data object from the assembler and creates the associated <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol staging object. <a href="#a2f758971f2c678319b2789af1377ef11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2b43a1818c41d1587433ce5eea4f7b">SetSymbolName</a> (COFFSymbol &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd42824aabe6dfabad203313ddf4204">SetSectionName</a> (COFFSection &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef1fb6936522e20599aafd74a643791">IsPhysicalSection</a> (COFFSection *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ef1308f61c882e886d08000e7e3579">WriteFileHeader</a> (const COFF::header &amp;Header)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b5550413e4a4c84ba38a5076be3f0f">WriteSymbol</a> (const COFFSymbol &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9029633258d769dfd0ecdaa00161d92e">WriteAuxiliarySymbols</a> (const COFFSymbol::AuxiliarySymbols &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9988734d6386f6f5262ff66e514a096">writeSectionHeaders</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3c967272f5c81c0dd48d74cdfabb0c">WriteRelocation</a> (const COFF::relocation &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592cd4d86477a23144ca2061580e7947">writeSectionContents</a> (MCAssembler &amp;Asm, const MCSection &amp;MCSec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80717d4400917607319f2a2c74b5ab3">writeSection</a> (MCAssembler &amp;Asm, const COFFSection &amp;Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9523f3d5edc2316625926fd93681b8bf">createFileSymbols</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e96657cd4a6674dad71e86d977895c">setWeakDefaultNames</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9459491cef8ebb5ae049e8a4bf23ffc5">assignSectionNumbers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae5d99c89d00ab87fcb1045f9b30a55">assignFileOffsets</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#adb7920f406fa5aedf5f43f8e5ea74c6b">llvm::WinCOFFWriter::DwoMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661e3352259002a2c79043cf6cf8922c">Mode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter">WinCOFFObjectWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07020e5970f6cd969ef207f11670e1ef">OWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0513d06010ea2a3c937edb181b397f">W</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coff/header">COFF::header</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae09c1e1846ab4e62df390f43b7c62ce4">Header</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a331e246d12fa5ce9e7d1fea9063fc">Sections</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">symbols</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d166e80ed61324a2876d0409400169">Symbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b5d6454b7dc20ae1f84ce09502a140">Strings</a> {<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aa3b433aad0b57e92f9970815c495fad4d">StringTableBuilder::WinCOFF</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">section_map</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec5f6259fc377ae962d528ee15a1dd8">SectionMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">symbol_map</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4275e6adce6518b27507c502e10f66e">SymbolMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">symbol_list</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea528803c1580ce4e2434e320fd15ef4">WeakDefaults</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1664939e6fb3e3ecd124a27e743a73ca">UseBigObj</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9691b4ce40f1b624639dcab97745094f">UseOffsetLabels</a> = false</td>
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


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### section\_map {#a005b9e4e4cea3cd3802cda04bb7f9910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::WinCOFFWriter::section_map =  DenseMap&lt;MCSection const *, COFFSection *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### sections {#a7b57e72a6aaf9071484114a4b5bf6e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::WinCOFFWriter::sections =  std::vector&lt;std::unique_ptr&lt;COFFSection&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### symbol\_list {#ab331e7bf0d8b74ebd740b8a0f342f00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::WinCOFFWriter::symbol_list =  DenseSet&lt;COFFSymbol *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### symbol\_map {#a9d31551d47e74edbcb3995d349da2c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::WinCOFFWriter::symbol_map =  DenseMap&lt;MCSymbol const *, COFFSymbol *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### symbols {#a873cddead8cb24f63c3f760b64636f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::WinCOFFWriter::symbols =  std::vector&lt;std::unique_ptr&lt;COFFSymbol&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DwoMode {#adb7920f406fa5aedf5f43f8e5ea74c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WinCOFFWriter::DwoMode </td>
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
<td class="doxyEnumItemName">AllSections<a id="adb7920f406fa5aedf5f43f8e5ea74c6bad185352167b8d3ebb701cf3049a5fd33"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NonDwoOnly<a id="adb7920f406fa5aedf5f43f8e5ea74c6ba864d13ebc3fed2ac2558685d8f59a45d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DwoOnly<a id="adb7920f406fa5aedf5f43f8e5ea74c6ba4303c2b002aa619418165a36a6b7c5b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WinCOFFWriter() {#a62cc3a814dc53171f32886aaa2ba8318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinCOFFWriter::WinCOFFWriter (<a href="/web-llvm/docs/api/classes/llvm/wincoffobjectwriter">WinCOFFObjectWriter</a> &amp; OWriter, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, <a href="#adb7920f406fa5aedf5f43f8e5ea74c6b">DwoMode</a> Mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a4cdd8d73d6aba93a5790daaa2d767553">llvm::COFF::isAnyArm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="#a661e3352259002a2c79043cf6cf8922c">Mode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### executePostLayoutBinding() {#aeeb14ab0bcb74e040f599ece0ea8de54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::executePostLayoutBinding (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#adb7920f406fa5aedf5f43f8e5ea74c6ba4303c2b002aa619418165a36a6b7c5b5">DwoOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a906c310d62ec1ae55afe3295a4fc2115afc617a23fd5e4cce7f2adfc7c2966e1c">llvm::COFF::IMAGE_SYM_CLASS_STATIC</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a7ae7754aaf6513bc0ea0bd5f457fe7cc">isDwoSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad3097c5eaf4198579c34562fd89a240e">llvm::COFF::MaxNumberOfSections16</a>, <a href="#a661e3352259002a2c79043cf6cf8922c">Mode</a>, <a href="#adb7920f406fa5aedf5f43f8e5ea74c6ba864d13ebc3fed2ac2558685d8f59a45d">NonDwoOnly</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getSectionNumber() {#ae23544385415140fac111e6d513de04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WinCOFFWriter::getSectionNumber (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### recordRelocation() {#ae083e4782d3a3ca6e98fbaacbb8d3f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a57211898d4494ccede1f9e90b92ebad4">llvm::COFF::IMAGE_FILE_MACHINE_AMD64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8af90ffbdda9ed6facec414824d70f9de2">llvm::COFF::IMAGE_FILE_MACHINE_ARMNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ab9b603eafcb824ebeb03f246cff0b4d4">llvm::COFF::IMAGE_FILE_MACHINE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a8ead7683d6849408053cae7a90851c97">llvm::COFF::IMAGE_FILE_MACHINE_R4000</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125a1376dddaf4ade08fe5429571a06c6249">llvm::COFF::IMAGE_REL_AMD64_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a6712271e6979f7eb2d4922c87c520d4ea1dde8be4528eebd8bfb4962a11b91d36">llvm::COFF::IMAGE_REL_ARM64_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a905028c6320edfd212e3cffd365e6cf4">llvm::COFF::IMAGE_REL_ARM_ABSOLUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a746d514c28aa512d8ddd56dc058e8faf">llvm::COFF::IMAGE_REL_ARM_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a4674ff1d84292a919b54e9ebd3d5fd46">llvm::COFF::IMAGE_REL_ARM_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5ae23715c442b7fccbcc70e3490ec6a9f1">llvm::COFF::IMAGE_REL_ARM_BLX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a99ba87de124124cda61beaeeef90e547">llvm::COFF::IMAGE_REL_ARM_BLX23T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a55f505d72b7fc170f5f9328d90b30cae">llvm::COFF::IMAGE_REL_ARM_BLX24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a495a4c1060316f2d53806aaca9993bcc">llvm::COFF::IMAGE_REL_ARM_BRANCH11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a3ebd5ea614167c6fccba3b326dd215be">llvm::COFF::IMAGE_REL_ARM_BRANCH20T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a3fa5b356a43456262a6a3a100f20fa33">llvm::COFF::IMAGE_REL_ARM_BRANCH24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a8898d58c6174b9ced49e3092764a27b5">llvm::COFF::IMAGE_REL_ARM_BRANCH24T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a0715521bb7874a6e8d9964b5493f4b45">llvm::COFF::IMAGE_REL_ARM_MOV32A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a865cc9cadbef2c0b2034ed1f7d49a8d3">llvm::COFF::IMAGE_REL_ARM_MOV32T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5a966485b6e6aca96a28c699566244f1a5">llvm::COFF::IMAGE_REL_ARM_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa3675a902af589d1fe8239cb229e834c">llvm::COFF::IMAGE_REL_ARM_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5aa99263a4ddef9c6522025169308d6d80">llvm::COFF::IMAGE_REL_ARM_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acc90ecc867e5f7f9b59008a4f097ced5afdfb7f85dbcb8abb448c59c38cc76ee3">llvm::COFF::IMAGE_REL_ARM_TOKEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#adb84e9917e2d3804c02e45f01918cc2da32627d83f2285f6f55acdf638a21284d">llvm::COFF::IMAGE_REL_I386_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7ba23af8b37dbbc8a5ad5026bb6a217fe6d">llvm::COFF::IMAGE_REL_MIPS_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7ba4a1fb04b4071332202dbb31dec920001">llvm::COFF::IMAGE_REL_MIPS_REFHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a2a5fd940ffde686f89fd39f338cb8e7ba6a40fa1912993d06f8154528f27ff721">llvm::COFF::IMAGE_REL_MIPS_SECRELHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a4cdd8d73d6aba93a5790daaa2d767553">llvm::COFF::isAnyArm64</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### reset() {#a6e77c3f43a0acf7bdad25ee6308d3812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeObject() {#a204d14337c246adfd274aac0837c6045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t WinCOFFWriter::writeObject (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#adb7920f406fa5aedf5f43f8e5ea74c6ba4303c2b002aa619418165a36a6b7c5b5">DwoOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a7a79ac08bf9d69bf371f9048385a11e0">llvm::MCSectionCOFF::getCOMDATSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aab8c6e58e0fb2534a0b6289f30b1d25d">llvm::MCSymbol::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a84a5158eaadf6a13eba52886d751b6c5">getTime</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea85161daa9965cdbe86d035f42c2c65ed">llvm::COFF::IMAGE_COMDAT_SELECT_ASSOCIATIVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa24ac1300caa85825d3526b8baaec159f">llvm::COFF::IMAGE_SCN_LNK_REMOVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a7ae7754aaf6513bc0ea0bd5f457fe7cc">isDwoSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a9cc0bd5c7cfcb87bc65c90ec1423f958">llvm::MCSymbol::isRegistered</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="#a661e3352259002a2c79043cf6cf8922c">Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ae3f859e92e664e6b19ce1d65c3d4577e">llvm::COFF::section::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a>, <a href="#adb7920f406fa5aedf5f43f8e5ea74c6ba864d13ebc3fed2ac2558685d8f59a45d">NonDwoOnly</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignFileOffsets() {#aaae5d99c89d00ab87fcb1045f9b30a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::assignFileOffsets (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### assignSectionNumbers() {#a9459491cef8ebb5ae049e8a4bf23ffc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::assignSectionNumbers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### createFileSymbols() {#a9523f3d5edc2316625926fd93681b8bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::createFileSymbols (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### createSection() {#a8d99d1a1036350e8fbcb68bc440f6f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFSection * WinCOFFWriter::createSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### createSymbol() {#a239a97f08170291a953b108aa733ac1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFSymbol * WinCOFFWriter::createSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### defineSection() {#aec85adf6e48706efa781021674c859f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::defineSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function takes a section data object from the assembler and creates the associated <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> section staging object.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### defineSymbol() {#a2f758971f2c678319b2789af1377ef11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::defineSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function takes a symbol data object from the assembler and creates the associated <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> symbol staging object.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### getLinkedSymbol() {#aa5c78efab4e4b7ece8f1a665f6f16489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFSymbol * WinCOFFWriter::getLinkedSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### GetOrCreateCOFFSymbol() {#a5da1595bbf1dbb2d26fc4e3218a46e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFSymbol * WinCOFFWriter::GetOrCreateCOFFSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### IsPhysicalSection() {#a6ef1fb6936522e20599aafd74a643791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WinCOFFWriter::IsPhysicalSection (COFFSection * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SetSectionName() {#accd42824aabe6dfabad203313ddf4204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::SetSectionName (COFFSection &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SetSymbolName() {#a7f2b43a1818c41d1587433ce5eea4f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::SetSymbolName (COFFSymbol &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### setWeakDefaultNames() {#a77e96657cd4a6674dad71e86d977895c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::setWeakDefaultNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### WriteAuxiliarySymbols() {#a9029633258d769dfd0ecdaa00161d92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::WriteAuxiliarySymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-wincoffobjectwriter-cpp-/coffsymbol/#a0925eb82674816976ebf9e8d67708ea9">COFFSymbol::AuxiliarySymbols</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### WriteFileHeader() {#a85ef1308f61c882e886d08000e7e3579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::WriteFileHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coff/header">COFF::header</a> &amp; Header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### WriteRelocation() {#a9c3c967272f5c81c0dd48d74cdfabb0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::WriteRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coff/relocation">COFF::relocation</a> &amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSection() {#ab80717d4400917607319f2a2c74b5ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::writeSection (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> COFFSection &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionContents() {#a592cd4d86477a23144ca2061580e7947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t WinCOFFWriter::writeSectionContents (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; MCSec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### writeSectionHeaders() {#ae9988734d6386f6f5262ff66e514a096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::writeSectionHeaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### WriteSymbol() {#a41b5550413e4a4c84ba38a5076be3f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WinCOFFWriter::WriteSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> COFFSymbol &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Mode {#a661e3352259002a2c79043cf6cf8922c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::WinCOFFWriter::DwoMode llvm::WinCOFFWriter::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#aeeb14ab0bcb74e040f599ece0ea8de54">executePostLayoutBinding</a>, <a href="#a62cc3a814dc53171f32886aaa2ba8318">WinCOFFWriter</a> and <a href="#a204d14337c246adfd274aac0837c6045">writeObject</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Header {#ae09c1e1846ab4e62df390f43b7c62ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFF::header llvm::WinCOFFWriter::Header = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### OWriter {#a07020e5970f6cd969ef207f11670e1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WinCOFFObjectWriter&amp; llvm::WinCOFFWriter::OWriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SectionMap {#aeec5f6259fc377ae962d528ee15a1dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">section_map llvm::WinCOFFWriter::SectionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Sections {#a34a331e246d12fa5ce9e7d1fea9063fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sections llvm::WinCOFFWriter::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Strings {#a94b5d6454b7dc20ae1f84ce09502a140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::WinCOFFWriter::Strings {<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aa3b433aad0b57e92f9970815c495fad4d">StringTableBuilder::WinCOFF</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### SymbolMap {#ab4275e6adce6518b27507c502e10f66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_map llvm::WinCOFFWriter::SymbolMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### Symbols {#a27d166e80ed61324a2876d0409400169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbols llvm::WinCOFFWriter::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### UseBigObj {#a1664939e6fb3e3ecd124a27e743a73ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinCOFFWriter::UseBigObj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### UseOffsetLabels {#a9691b4ce40f1b624639dcab97745094f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WinCOFFWriter::UseOffsetLabels = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### W {#a0b0513d06010ea2a3c937edb181b397f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::endian::Writer llvm::WinCOFFWriter::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

### WeakDefaults {#aea528803c1580ce4e2434e320fd15ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">symbol_list llvm::WinCOFFWriter::WeakDefaults</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp">WinCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
