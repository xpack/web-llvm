---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachObjectWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">llvm/MC/MCMachObjectWriter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines the object file and target independent interfaces used by the assembler backend to write native file format object files. <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd306a626b64ae7b48b9f9f06fb9b39">VersionInfoType</a> = struct { bool EmitBuildVersion; union { <a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">MachO::PlatformType</a> Platform; } TypeOrPlatform; unsigned Major; unsigned Minor; unsigned Update; <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion; }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4bf98bbfcb390f851732271db6c97c3">MachObjectWriter</a> (std::unique_ptr&lt; MCMachObjectTargetWriter &gt; MOTW, raw_pwrite_stream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7ffd07b20ace5663469673c7fdfc28">findAliasedSymbol</a> (const MCSymbol &amp;Sym) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe850866c34aae7e741e5a9cd530d8ea">writeHeader</a> (MachO::HeaderFileType Type, unsigned NumLoadCommands, unsigned LoadCommandsSize, bool SubsectionsViaSymbols)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f071c4c2aba88443b1ab2d2e8a8fcd">writeSegmentLoadCommand</a> (StringRef Name, unsigned NumSections, uint64_t VMAddr, uint64_t VMSize, uint64_t SectionDataStartOffset, uint64_t SectionDataSize, uint32_t MaxProt, uint32_t InitProt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write a segment load command. <a href="#ab2f071c4c2aba88443b1ab2d2e8a8fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0975e62123800512eca4d2ae67034c21">writeSection</a> (const MCAssembler &amp;Asm, const MCSection &amp;Sec, uint64_t VMAddr, uint64_t FileOffset, unsigned Flags, uint64_t RelocationsStart, unsigned NumRelocations)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee55193bd2b54948d8f7aa074e68445a">writeSymtabLoadCommand</a> (uint32_t SymbolOffset, uint32_t NumSymbols, uint32_t StringTableOffset, uint32_t StringTableSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac0b0e83713315a5458053f2949705e">writeDysymtabLoadCommand</a> (uint32_t FirstLocalSymbol, uint32_t NumLocalSymbols, uint32_t FirstExternalSymbol, uint32_t NumExternalSymbols, uint32_t FirstUndefinedSymbol, uint32_t NumUndefinedSymbols, uint32_t IndirectSymbolOffset, uint32_t NumIndirectSymbols)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eaa0b0e3cca86ba5b64bd8637297d14">writeNlist</a> (MachSymbolData &amp;MSD, const MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41145f17a62df13d96c490ca3ce9c40">writeLinkeditLoadCommand</a> (uint32_t Type, uint32_t DataOffset, uint32_t DataSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a673b20bc7c9d71d28a3c006b9c9418a1">writeLinkerOptionsLoadCommand</a> (const std::vector&lt; std::string &gt; &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b113871f6a7036554ee273f6c989fe">addRelocation</a> (const MCSymbol *RelSymbol, const MCSection *Sec, MachO::any_relocation_info &amp;MRE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbd1184c383c03fb43f26365d095b50">recordRelocation</a> (MCAssembler &amp;Asm, const MCFragment *Fragment, const MCFixup &amp;Fixup, MCValue Target, uint64_t &amp;FixedValue) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a relocation entry. <a href="#a6dbd1184c383c03fb43f26365d095b50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef266637bcd341b78e94c0ba47ce238">bindIndirectSymbols</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228730a8c564293f8f798c0600481e7c">computeSymbolTable</a> (MCAssembler &amp;Asm, std::vector&lt; MachSymbolData &gt; &amp;LocalSymbolData, std::vector&lt; MachSymbolData &gt; &amp;ExternalSymbolData, std::vector&lt; MachSymbolData &gt; &amp;UndefinedSymbolData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the symbol table data. <a href="#a228730a8c564293f8f798c0600481e7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c1c5abac9df89f0de66b7771b475d3">computeSectionAddresses</a> (const MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38158d8fb10faf842b94bfd73955a0b3">executePostLayoutBinding</a> (MCAssembler &amp;Asm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform any late binding of symbols (for example, to assign symbol indices for use when generating relocations). <a href="#a38158d8fb10faf842b94bfd73955a0b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854e63ee2f4ff3e684ba403e8342d88d">isSymbolRefDifferenceFullyResolvedImpl</a> (const MCAssembler &amp;Asm, const MCSymbol &amp;SymA, const MCFragment &amp;FB, bool InSet, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ae9aaf6cda4c28330c5915f8291d5e">populateAddrSigSection</a> (MCAssembler &amp;Asm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a> (MCAssembler &amp;Asm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the object file and returns the number of bytes written. <a href="#af452e21aa5eefd6666ed1d0b693f770c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MachSymbolData *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4cdceccf90077200f1fc22b21a5025">findSymbolData</a> (const MCSymbol &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ed307c3a3e428567f01965e6954dd8">writeWithPadding</a> (StringRef Str, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcmachobjecttargetwriter">MCMachObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c3b86492f70260d9be026f280ff8a3">TargetObjectWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The target specific Mach-O writer instance. <a href="#ac8c3b86492f70260d9be026f280ff8a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mclohcontainer">MCLOHContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab803fc4e4eebd03c6ac00cf59f7f6777">LOHContainer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afbd306a626b64ae7b48b9f9f06fb9b39">VersionInfoType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4193372f23afff7966bd4389d5d093d">VersionInfo</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afbd306a626b64ae7b48b9f9f06fb9b39">VersionInfoType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafaee2b7cea0bc74811baf66a3f902a">TargetVariantVersionInfo</a> {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; std::string &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620a1c8b9be0c12aa4fc03914b8ac295">LinkerOptions</a></td>
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

## Relocation Data Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, std::vector&lt; RelAndSymbol &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1d7aad9ae4203c9fa2a415dab071a7">Relocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; IndirectSymbolData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d8f26bd7dcdb110e5b3a3a9567075a">IndirectSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0b58abdee0b5ba73053508626f9ec3">IndirectSymBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machobjectwriter/dataregiondata">DataRegionData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7362e187fb2795677cadd020b526660">DataRegions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ac66fe51a73cdf1ab9f07ca6ead1652e7">SectionAddrMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5cfe16413ce9a3a81b0ccfdd0535a04">SectionAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50f6697e82fe914bcdd82b4d94fb13f">SectionOrder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e868e0ace7ed50c05205adfd292abf5">StringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; MachSymbolData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d792b45a658a02486383cb236533f0">LocalSymbolData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; MachSymbolData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5794c4e563b3a2944f6e9395381af8b">ExternalSymbolData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; MachSymbolData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42c30ffb2d430c9454789ab9099dbb23">UndefinedSymbolData</a></td>
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

## Lifetime management Methods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc4e9777889f1400f9439219769ab8b">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lifetime management <a href="#acdc4e9777889f1400f9439219769ab8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility Methods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f972d8aca0c842218ea5b0fd4559a8">isFixupKindPCRel</a> (const MCAssembler &amp;Asm, unsigned Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; IndirectSymbolData &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95a5423ec4f5177c9eaaaf2a60eb876d">getIndirectSymbols</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machobjectwriter/dataregiondata">DataRegionData</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422412075a762e5d8dc08ecd610ee2e0">getDataRegions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">llvm::SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b7dd22dc010bb70268a1ca05d90af5">getSectionOrder</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ac66fe51a73cdf1ab9f07ca6ead1652e7">SectionAddrMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2120fb70d13351919b19b2e84bc70483">getSectionAddressMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mclohcontainer">MCLOHContainer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f31f328a11e115e8956f98e02880c0d">getLOHContainer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1db2b8157f2659ddbb53b5515bf1f7">getSectionAddress</a> (const MCSection *Sec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c098d5087a761f4ff5d1862ae8dfcbe">getSymbolAddress</a> (const MCSymbol &amp;S, const MCAssembler &amp;Asm) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be2c8edb4b559c7d47cfa0ec881739f">getFragmentAddress</a> (const MCAssembler &amp;Asm, const MCFragment *Fragment) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0536664f5fb6bbdea8b29f944e01c0c7">getPaddingSize</a> (const MCAssembler &amp;Asm, const MCSection *SD) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3fd02f1d1b3eeeec275c2485ba8af0a">getAtom</a> (const MCSymbol &amp;S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4cfdd1099f849b68c5072d1d7fd017">doesSymbolRequireExternRelocation</a> (const MCSymbol &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13dd44b52d16a2aacf2d74fa529ac7a">setVersionMin</a> (MCVersionMinType Type, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion=VersionTuple())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mach-O deployment target version information. <a href="#af13dd44b52d16a2aacf2d74fa529ac7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3936ecdc3e1dad30506a50cbadb3ae9">setBuildVersion</a> (MachO::PlatformType Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion=VersionTuple())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b1cd34ac4caf308aac4476c51adb7a">setTargetVariantBuildVersion</a> (MachO::PlatformType Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; std::string &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7756b275710eb6ea0b5f9f0b501bef2">getLinkerOptions</a> ()</td>
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

## Target Writer Proxy Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcadd6665b8fc182fdedd7a9d9f41dc8">isX86_64</a> () const</td>
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


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VersionInfoType {#afbd306a626b64ae7b48b9f9f06fb9b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachObjectWriter::VersionInfoType =  struct {
    bool EmitBuildVersion;
    union {
      MCVersionMinType Type;        
      MachO::PlatformType Platform; 
    } TypeOrPlatform;
    unsigned Major;
    unsigned Minor;
    unsigned Update;
    
    VersionTuple SDKVersion;
  }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachObjectWriter() {#af4bf98bbfcb390f851732271db6c97c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachObjectWriter::MachObjectWriter (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcmachobjecttargetwriter">MCMachObjectTargetWriter</a> &gt; MOTW, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRelocation() {#a40b113871f6a7036554ee273f6c989fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachObjectWriter::addRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * RelSymbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Sec, <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a> &amp; MRE)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a49ae9aaf6cda4c28330c5915f8291d5e">populateAddrSigSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a> and <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### bindIndirectSymbols() {#aeef266637bcd341b78e94c0ba47ce238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::bindIndirectSymbols (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a4735e4e9043352fd4e19057bf95ea28a">llvm::MachO::S_LAZY_SYMBOL_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a93912b05b13268a5cbd717f4a5fab8c9">llvm::MachO::S_NON_LAZY_SYMBOL_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409ae03f48f1f4c31faadeac53f15460c2d6">llvm::MachO::S_SYMBOL_STUBS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a0b4240e38bf4066a8378e3a0450555ef">llvm::MachO::S_THREAD_LOCAL_VARIABLE_POINTERS</a>.</p>


<p>Referenced by <a href="#a38158d8fb10faf842b94bfd73955a0b3">executePostLayoutBinding</a>.</p>

</div>
</div>

### computeSectionAddresses() {#a08c1c5abac9df89f0de66b7771b475d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::computeSectionAddresses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a0536664f5fb6bbdea8b29f944e01c0c7">getPaddingSize</a>.</p>


<p>Referenced by <a href="#a38158d8fb10faf842b94bfd73955a0b3">executePostLayoutBinding</a>.</p>

</div>
</div>

### computeSymbolTable() {#a228730a8c564293f8f798c0600481e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::computeSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, std::vector&lt; MachSymbolData &gt; &amp; LocalSymbolData, std::vector&lt; MachSymbolData &gt; &amp; ExternalSymbolData, std::vector&lt; MachSymbolData &gt; &amp; UndefinedSymbolData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the symbol table data.</p>


<p>computeSymbolTable - Compute the symbol table data</p>


<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#adee15ddf2796a0e230bf8ec9465e9cdc">isSymbolLinkerVisible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### executePostLayoutBinding() {#a38158d8fb10faf842b94bfd73955a0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::executePostLayoutBinding (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Perform any late binding of symbols (for example, to assign symbol indices for use when generating relocations).</p>


<p>This routine is called by the assembler after layout and relaxation is complete.</p>


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="#aeef266637bcd341b78e94c0ba47ce238">bindIndirectSymbols</a> and <a href="#a08c1c5abac9df89f0de66b7771b475d3">computeSectionAddresses</a>.</p>

</div>
</div>

### findAliasedSymbol() {#a8b7ffd07b20ace5663469673c7fdfc28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol &amp; MachObjectWriter::findAliasedSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>


<p>Referenced by <a href="#a854e63ee2f4ff3e684ba403e8342d88d">isSymbolRefDifferenceFullyResolvedImpl</a> and <a href="#a7eaa0b0e3cca86ba5b64bd8637297d14">writeNlist</a>.</p>

</div>
</div>

### isSymbolRefDifferenceFullyResolvedImpl() {#a854e63ee2f4ff3e684ba403e8342d88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachObjectWriter::isSymbolRefDifferenceFullyResolvedImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; SymA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> &amp; FB, bool InSet, bool IsPCRel)</td>
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



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="#a8b7ffd07b20ace5663469673c7fdfc28">findAliasedSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a4e2fd6c6e6a95e8b339866567c8345d7">llvm::MCFragment::getAtom</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="#adcadd6665b8fc182fdedd7a9d9f41dc8">isX86_64</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a75b6a1a0b7892c9ee2d96388addd631c">llvm::MCObjectWriter::SubsectionsViaSymbols</a>.</p>

</div>
</div>

### populateAddrSigSection() {#a49ae9aaf6cda4c28330c5915f8291d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::populateAddrSigSection (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="#a40b113871f6a7036554ee273f6c989fe">addRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa73b7678d1078f7640dc5c2d3c7de0fe3">llvm::MachO::GENERIC_RELOC_VANILLA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a8e8e21bf8aec48266b68356d5d4cca94">llvm::MCObjectWriter::getAddrsigSyms</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### recordRelocation() {#a6dbd1184c383c03fb43f26365d095b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a relocation entry.</p>


<p>This routine is called by the assembler after layout and relaxation, and post layout binding. The implementation is responsible for storing information about the relocation so that it can be emitted during <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject()</a>.</p>


<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#a0903fa4546b8ea669d26cc0d1b5ae48d">isFixupTargetValid</a>.</p>

</div>
</div>

### writeDysymtabLoadCommand() {#a8ac0b0e83713315a5458053f2949705e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeDysymtabLoadCommand (uint32_t FirstLocalSymbol, uint32_t NumLocalSymbols, uint32_t FirstExternalSymbol, uint32_t NumExternalSymbols, uint32_t FirstUndefinedSymbol, uint32_t NumUndefinedSymbols, uint32_t IndirectSymbolOffset, uint32_t NumIndirectSymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeHeader() {#abe850866c34aae7e741e5a9cd530d8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeHeader (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19a">MachO::HeaderFileType</a> Type, unsigned NumLoadCommands, unsigned LoadCommandsSize, bool SubsectionsViaSymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac1c361fc17a664c6c8eb2deb666a495aa371e02a5be76919ad4f0176d3c81a223">llvm::MachO::CPU_SUBTYPE_ARM64E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad3a903396556679cce3aefb8e338c57e">llvm::MachO::CPU_SUBTYPE_ARM64E_WITH_PTRAUTH_VERSION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a33fddb0190d728c25e266a22d64bd7ad">llvm::MachO::CPU_TYPE_ARM64</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa109d22c6d71247dd24ee7ba5670b230a08eb469a4572cc8702c0c6acbb1fa808">llvm::MachO::MH_MAGIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aa109d22c6d71247dd24ee7ba5670b230ad58eeb9082b629126262656d574117e7">llvm::MachO::MH_MAGIC_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a56796c840e08337bb5693b43bf17360caf6603f58bda7e4bd0c905219ff2aa726">llvm::MachO::MH_SUBSECTIONS_VIA_SYMBOLS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a75b6a1a0b7892c9ee2d96388addd631c">llvm::MCObjectWriter::SubsectionsViaSymbols</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeLinkeditLoadCommand() {#ab41145f17a62df13d96c490ca3ce9c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeLinkeditLoadCommand (uint32_t Type, uint32_t DataOffset, uint32_t DataSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeLinkerOptionsLoadCommand() {#a673b20bc7c9d71d28a3c006b9c9418a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeLinkerOptionsLoadCommand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#a003ab8893ba4df3a28468f7dfea5745a">ComputeLinkerOptionsLoadCommandSize</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeNlist() {#a7eaa0b0e3cca86ba5b64bd8637297d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeNlist (MachSymbolData &amp; MSD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a8b7ffd07b20ace5663469673c7fdfc28">findAliasedSymbol</a>, <a href="#a9c098d5087a761f4ff5d1862ae8dfcbe">getSymbolAddress</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda77259a8efd8dc293c93df006d02b90c5">llvm::MachO::N_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11a8bc1bbfcee7206480576072973724a1a">llvm::MachO::N_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda906620a6f5df2e39717dac5f1473a77a">llvm::MachO::N_INDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad152fa3b2aff735d4a2e4b644dc93b11aa76667ab09bbf06002b68e0c1a015806">llvm::MachO::N_PEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda149563e67229adecb388a1b15854f767">llvm::MachO::N_SECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227edac444d073d7dfae9ee37913c3ebc18fa9">llvm::MachO::N_UNDF</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeObject() {#af452e21aa5eefd6666ed1d0b693f770c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachObjectWriter::writeObject (<a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
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

<p>Write the object file and returns the number of bytes written.</p>


<p>This routine is called by the assembler after layout and relaxation is complete, fixups have been evaluated and applied, and relocations generated.</p>


<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#add652e7ff42f6239bfb6aeef0e86c6f1">llvm::MCSection::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a2e6e1fd5b53c221af1ecccca793da758">llvm::MCObjectWriter::CGProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#a003ab8893ba4df3a28468f7dfea5745a">ComputeLinkerOptionsLoadCommandSize</a>, <a href="#a228730a8c564293f8f798c0600481e7c">computeSymbolTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#aa4096cda69872272e2399b02947cbd0c">getLCFromMCVM</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="#a0536664f5fb6bbdea8b29f944e01c0c7">getPaddingSize</a>, <a href="#a3d1db2b8157f2659ddbb53b5515bf1f7">getSectionAddress</a>, <a href="#a9c098d5087a761f4ff5d1862ae8dfcbe">getSymbolAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334adc92b92dbafb0b2e4f7dc9bba15411eb">llvm::MachO::INDIRECT_SYMBOL_ABS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334ae4ee9e11a80526990aa9eadf63be1103">llvm::MachO::INDIRECT_SYMBOL_LOCAL</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a4099e754341e36bdbc04624fa2f1e19aa0720b97729bd97889599a4dc76faf0dc">llvm::MachO::MH_OBJECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>, <a href="#a49ae9aaf6cda4c28330c5915f8291d5e">populateAddrSigSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a137626613cacccb0e1080d23f3489c8f">llvm::MachO::S_ATTR_SOME_INSTRUCTIONS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a93912b05b13268a5cbd717f4a5fab8c9">llvm::MachO::S_NON_LAZY_SYMBOL_POINTERS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a75b6a1a0b7892c9ee2d96388addd631c">llvm::MCObjectWriter::SubsectionsViaSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783a459028b54c6de464c939b7a148dee815">llvm::MachO::VM_PROT_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783a9dccfb77c950352acfcae05d2002d5d4">llvm::MachO::VM_PROT_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783acca2a1b89bc84f63aa45c62455c7fcae">llvm::MachO::VM_PROT_WRITE</a>, <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>, <a href="#a8ac0b0e83713315a5458053f2949705e">writeDysymtabLoadCommand</a>, <a href="#abe850866c34aae7e741e5a9cd530d8ea">writeHeader</a>, <a href="#ab41145f17a62df13d96c490ca3ce9c40">writeLinkeditLoadCommand</a>, <a href="#a673b20bc7c9d71d28a3c006b9c9418a1">writeLinkerOptionsLoadCommand</a>, <a href="#a7eaa0b0e3cca86ba5b64bd8637297d14">writeNlist</a>, <a href="#a0975e62123800512eca4d2ae67034c21">writeSection</a>, <a href="#ab2f071c4c2aba88443b1ab2d2e8a8fcd">writeSegmentLoadCommand</a> and <a href="#aee55193bd2b54948d8f7aa074e68445a">writeSymtabLoadCommand</a>.</p>

</div>
</div>

### writeSection() {#a0975e62123800512eca4d2ae67034c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec, uint64_t VMAddr, uint64_t FileOffset, unsigned Flags, uint64_t RelocationsStart, unsigned NumRelocations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeSegmentLoadCommand() {#ab2f071c4c2aba88443b1ab2d2e8a8fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeSegmentLoadCommand (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, unsigned NumSections, uint64_t VMAddr, uint64_t VMSize, uint64_t SectionDataStartOffset, uint64_t SectionDataSize, uint32_t MaxProt, uint32_t InitProt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write a segment load command.</p>


<p>writeSegmentLoadCommand - Write a segment load command.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumSections</td>
<td class="doxyParamItemDescription"><p>The number of sections in this segment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SectionDataSize</td>
<td class="doxyParamItemDescription"><p>The total size of the sections.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2280dba4a11db43bbecadf864b1f9a66">is64Bit</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### writeSymtabLoadCommand() {#aee55193bd2b54948d8f7aa074e68445a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeSymtabLoadCommand (uint32_t SymbolOffset, uint32_t NumSymbols, uint32_t StringTableOffset, uint32_t StringTableSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a57f7c781103b28d9511e2ddd5aa0eec6">W</a>.</p>


<p>Referenced by <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findSymbolData() {#afa4cdceccf90077200f1fc22b21a5025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachObjectWriter::MachSymbolData * MachObjectWriter::findSymbolData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>

</div>
</div>

### writeWithPadding() {#a26ed307c3a3e428567f01965e6954dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::writeWithPadding (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### W {#a57f7c781103b28d9511e2ddd5aa0eec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::endian::Writer llvm::MachObjectWriter::W</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a228730a8c564293f8f798c0600481e7c">computeSymbolTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mclohdirective/#a31c388d4454133dfd0f5b26b0299f99d">llvm::MCLOHDirective::emit</a>, <a href="#af4bf98bbfcb390f851732271db6c97c3">MachObjectWriter</a>, <a href="#a8ac0b0e83713315a5458053f2949705e">writeDysymtabLoadCommand</a>, <a href="#abe850866c34aae7e741e5a9cd530d8ea">writeHeader</a>, <a href="#ab41145f17a62df13d96c490ca3ce9c40">writeLinkeditLoadCommand</a>, <a href="#a673b20bc7c9d71d28a3c006b9c9418a1">writeLinkerOptionsLoadCommand</a>, <a href="#a7eaa0b0e3cca86ba5b64bd8637297d14">writeNlist</a>, <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>, <a href="#a0975e62123800512eca4d2ae67034c21">writeSection</a>, <a href="#ab2f071c4c2aba88443b1ab2d2e8a8fcd">writeSegmentLoadCommand</a> and <a href="#aee55193bd2b54948d8f7aa074e68445a">writeSymtabLoadCommand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LinkerOptions {#a620a1c8b9be0c12aa4fc03914b8ac295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;std::string&gt; &gt; llvm::MachObjectWriter::LinkerOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### LOHContainer {#ab803fc4e4eebd03c6ac00cf59f7f6777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCLOHContainer llvm::MachObjectWriter::LOHContainer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### TargetObjectWriter {#ac8c3b86492f70260d9be026f280ff8a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCMachObjectTargetWriter&gt; llvm::MachObjectWriter::TargetObjectWriter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The target specific Mach-O writer instance.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### TargetVariantVersionInfo {#adafaee2b7cea0bc74811baf66a3f902a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionInfoType llvm::MachObjectWriter::TargetVariantVersionInfo {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### VersionInfo {#ac4193372f23afff7966bd4389d5d093d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionInfoType llvm::MachObjectWriter::VersionInfo {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Relocation Data

### DataRegions {#af7362e187fb2795677cadd020b526660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DataRegionData&gt; llvm::MachObjectWriter::DataRegions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### IndirectSymBase {#a4e0b58abdee0b5ba73053508626f9ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSection *, unsigned&gt; llvm::MachObjectWriter::IndirectSymBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### IndirectSymbols {#a08d8f26bd7dcdb110e5b3a3a9567075a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;IndirectSymbolData&gt; llvm::MachObjectWriter::IndirectSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### Relocations {#a3a1d7aad9ae4203c9fa2a415dab071a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSection *, std::vector&lt;RelAndSymbol&gt; &gt; llvm::MachObjectWriter::Relocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### SectionAddress {#ad5cfe16413ce9a3a81b0ccfdd0535a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionAddrMap llvm::MachObjectWriter::SectionAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### SectionOrder {#ae50f6697e82fe914bcdd82b4d94fb13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCSection *, 0&gt; llvm::MachObjectWriter::SectionOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Symbol Table Data

### ExternalSymbolData {#af5794c4e563b3a2944f6e9395381af8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachSymbolData&gt; llvm::MachObjectWriter::ExternalSymbolData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### LocalSymbolData {#af6d792b45a658a02486383cb236533f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachSymbolData&gt; llvm::MachObjectWriter::LocalSymbolData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### StringTable {#a5e868e0ace7ed50c05205adfd292abf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::MachObjectWriter::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### UndefinedSymbolData {#a42c30ffb2d430c9454789ab9099dbb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachSymbolData&gt; llvm::MachObjectWriter::UndefinedSymbolData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Lifetime management Methods

### reset {#acdc4e9777889f1400f9439219769ab8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachObjectWriter::reset ()</td>
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

<p>lifetime management</p>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a9007366cbf9e6c4f72f284ceabb104ad">llvm::MCObjectWriter::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility Methods

### doesSymbolRequireExternRelocation {#a0d4cfdd1099f849b68c5072d1d7fd017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachObjectWriter::doesSymbolRequireExternRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aa462dae167e31cac32e97bb0c77ab071">llvm::MCSymbol::isUndefined</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### getAtom {#ab3fd02f1d1b3eeeec275c2485ba8af0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * MachObjectWriter::getAtom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a4e2fd6c6e6a95e8b339866567c8345d7">llvm::MCFragment::getAtom</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin/#ab4ef3ac1427687f11d30de588a790122">llvm::MCAsmInfoDarwin::isSectionAtomizableBySymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#adee15ddf2796a0e230bf8ec9465e9cdc">isSymbolLinkerVisible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### getDataRegions {#a422412075a762e5d8dc08ecd610ee2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; DataRegionData &gt; &amp; llvm::MachObjectWriter::getDataRegions ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### getFragmentAddress {#a2be2c8edb4b559c7d47cfa0ec881739f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachObjectWriter::getFragmentAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a> and <a href="#a3d1db2b8157f2659ddbb53b5515bf1f7">getSectionAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### getIndirectSymbols {#a95a5423ec4f5177c9eaaaf2a60eb876d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; IndirectSymbolData &gt; &amp; llvm::MachObjectWriter::getIndirectSymbols ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a798fb78a6525095a294fda8d027edeb6">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitSymbolAttribute</a>.</p>

</div>
</div>

### getLinkerOptions {#af7756b275710eb6ea0b5f9f0b501bef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::vector&lt; std::string &gt; &gt; &amp; llvm::MachObjectWriter::getLinkerOptions ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a20df437db4d5607918482b6758bd9ffa">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitLinkerOptions</a>.</p>

</div>
</div>

### getLOHContainer {#a1f31f328a11e115e8956f98e02880c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCLOHContainer &amp; llvm::MachObjectWriter::getLOHContainer ()</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### getPaddingSize {#a0536664f5fb6bbdea8b29f944e01c0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachObjectWriter::getPaddingSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * SD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a3908d151fa93bdc906cbf57d96060673">llvm::MCSection::getAlign</a>, <a href="#a3d1db2b8157f2659ddbb53b5515bf1f7">getSectionAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a915b90d97a0e500c99adefff0c22fec3">llvm::MCSection::isVirtualSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99cdcecbadc13087f087c61809bb44f1">llvm::offsetToAlignment</a>.</p>


<p>Referenced by <a href="#a08c1c5abac9df89f0de66b7771b475d3">computeSectionAddresses</a> and <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### getSectionAddress {#a3d1db2b8157f2659ddbb53b5515bf1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MachObjectWriter::getSectionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Sec)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="#a2be2c8edb4b559c7d47cfa0ec881739f">getFragmentAddress</a>, <a href="#a0536664f5fb6bbdea8b29f944e01c0c7">getPaddingSize</a>, <a href="#a9c098d5087a761f4ff5d1862ae8dfcbe">getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a> and <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### getSectionAddressMap {#a2120fb70d13351919b19b2e84bc70483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionAddrMap &amp; llvm::MachObjectWriter::getSectionAddressMap ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### getSectionOrder {#a40b7dd22dc010bb70268a1ca05d90af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const llvm::SmallVectorImpl&lt; MCSection * &gt; &amp; llvm::MachObjectWriter::getSectionOrder ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>

</div>
</div>

### getSymbolAddress {#a9c098d5087a761f4ff5d1862ae8dfcbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t MachObjectWriter::getSymbolAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#aa770f9e822312cc252ee01659e0bc7d4">llvm::MCExpr::evaluateAsRelocatable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a30cdafd656830b62aa8070242810c405">llvm::Target::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="#a3d1db2b8157f2659ddbb53b5515bf1f7">getSectionAddress</a>, <a href="#a9c098d5087a761f4ff5d1862ae8dfcbe">getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2192a3f25b0bc0505cc168a012038046">llvm::MCSymbol::getVariableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a620bf1ce8489b3da259faf0c55a862aa">llvm::MCSymbol::isVariable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a9c098d5087a761f4ff5d1862ae8dfcbe">getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="#a7eaa0b0e3cca86ba5b64bd8637297d14">writeNlist</a> and <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>.</p>

</div>
</div>

### isFixupKindPCRel {#a56f972d8aca0c842218ea5b0fd4559a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachObjectWriter::isFixupKindPCRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, unsigned Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#ae92461ded3785b1595f975afc7d42cb9">llvm::MCFixupKindInfo::Flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a> and <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### setBuildVersion {#af3936ecdc3e1dad30506a50cbadb3ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachObjectWriter::setBuildVersion (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">MachO::PlatformType</a> Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion=<a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a>())</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#aaefc9558efc4b58f37049b3e4656011f">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitBuildVersion</a>.</p>

</div>
</div>

### setTargetVariantBuildVersion {#a08b1cd34ac4caf308aac4476c51adb7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachObjectWriter::setTargetVariantBuildVersion (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3cdacd46a54ada4abe329c88c7a92504">MachO::PlatformType</a> Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a109ba15aa1760d974d280d73a7b632b9">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitDarwinTargetVariantBuildVersion</a>.</p>

</div>
</div>

### setVersionMin {#af13dd44b52d16a2aacf2d74fa529ac7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachObjectWriter::setVersionMin (<a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> Type, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion=<a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a>())</td>
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

<p>Mach-O deployment target version information.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a54b409598660523f6cc25d472089fc05">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitVersionMin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Target Writer Proxy Accessors

### is64Bit {#a2280dba4a11db43bbecadf864b1f9a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachObjectWriter::is64Bit ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Referenced by <a href="#af4bf98bbfcb390f851732271db6c97c3">MachObjectWriter</a>, <a href="#a49ae9aaf6cda4c28330c5915f8291d5e">populateAddrSigSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86machobjectwriter-cpp-/x86machobjectwriter/#ae86630c0128bf3d964ca61e862679cca">anonymous{X86MachObjectWriter.cpp}::X86MachObjectWriter::recordRelocation</a>, <a href="#abe850866c34aae7e741e5a9cd530d8ea">writeHeader</a>, <a href="#a673b20bc7c9d71d28a3c006b9c9418a1">writeLinkerOptionsLoadCommand</a>, <a href="#a7eaa0b0e3cca86ba5b64bd8637297d14">writeNlist</a>, <a href="#af452e21aa5eefd6666ed1d0b693f770c">writeObject</a>, <a href="#a0975e62123800512eca4d2ae67034c21">writeSection</a> and <a href="#ab2f071c4c2aba88443b1ab2d2e8a8fcd">writeSegmentLoadCommand</a>.</p>

</div>
</div>

### isX86\_64 {#adcadd6665b8fc182fdedd7a9d9f41dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachObjectWriter::isX86_64 ()</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#af2acbc063e449084ba33f738a700ce47a633855cb5719de40d81669897cc571c8">llvm::MachO::CPU_TYPE_X86_64</a>.</p>


<p>Referenced by <a href="#a854e63ee2f4ff3e684ba403e8342d88d">isSymbolRefDifferenceFullyResolvedImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcmachobjectwriter-h">MCMachObjectWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp">MachObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
