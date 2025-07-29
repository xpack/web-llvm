---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/nativesession
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NativeSession` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::NativeSession { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">llvm/DebugInfo/PDB/Native/NativeSession.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">IPDBSession</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">IPDBSession</a> defines an interface used to provide a context for querying debug information from a debug data source (for example, a PDB). <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcff9b08352b2950db6c2d27b68c659c">IMap</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a>&lt; uint64_t, uint16_t, 8, <a href="/web-llvm/docs/api/structs/llvm/intervalmaphalfopeninfo">IntervalMapHalfOpenInfo</a>&lt; uint64_t &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from virtual address to module index. <a href="#adcff9b08352b2950db6c2d27b68c659c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abacb37bf0bac9b174d38283f91c406e2">NativeSession</a> (std::unique_ptr&lt; PDBFile &gt; PdbFile, std::unique_ptr&lt; BumpPtrAllocator &gt; Allocator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f33c7c9fda8d551a5bdfc70b9b05aec">~NativeSession</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad6024f1ff0a43f008c382eebe0e8bc">getLoadAddress</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f44423e4ee68c7ba3ebc14172446e64">setLoadAddress</a> (uint64_t Address) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolexe">PDBSymbolExe</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec0a067a0a5fb05e01dfd6350dc3308">getGlobalScope</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe49dc54ae0d2ef1e1484fa181d7104">getSymbolById</a> (SymIndexId SymbolId) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22602a2dcab20f24424225b3bedbcf3a">addressForVA</a> (uint64_t VA, uint32_t &amp;Section, uint32_t &amp;Offset) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277f859f380850343d58cdd740d822b4">addressForRVA</a> (uint32_t RVA, uint32_t &amp;Section, uint32_t &amp;Offset) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe7201ebf6970eebc5d2edddb57d404">findSymbolByAddress</a> (uint64_t Address, PDB_SymType Type) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b81f0ad477f2c844eaf8710d1b7900">findSymbolByRVA</a> (uint32_t RVA, PDB_SymType Type) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489ca1ad15b298eefea45fc445781b14">findSymbolBySectOffset</a> (uint32_t Sect, uint32_t Offset, PDB_SymType Type) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a217f1bfdff572ea30e762481e0049ebf">IPDBEnumLineNumbers</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd76a96f188964b0ad33acd219433d1">findLineNumbers</a> (const PDBSymbolCompiland &amp;Compiland, const IPDBSourceFile &amp;File) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a217f1bfdff572ea30e762481e0049ebf">IPDBEnumLineNumbers</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace21067119f8cff56f4720d9bd9e00d5">findLineNumbersByAddress</a> (uint64_t Address, uint32_t Length) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a217f1bfdff572ea30e762481e0049ebf">IPDBEnumLineNumbers</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3164daf5c652f03c1491fdc8e5b4913c">findLineNumbersByRVA</a> (uint32_t RVA, uint32_t Length) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a217f1bfdff572ea30e762481e0049ebf">IPDBEnumLineNumbers</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3532a5ed6f2849be0b297aa8db038e38">findLineNumbersBySectOffset</a> (uint32_t Section, uint32_t Offset, uint32_t Length) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae4335f7829654f053ddbeac3c2335c06">IPDBEnumSourceFiles</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b43eeb05042b2141ff01abe732ffc6">findSourceFiles</a> (const PDBSymbolCompiland *Compiland, llvm::StringRef Pattern, PDB_NameSearchFlags Flags) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsourcefile">IPDBSourceFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b06f3a0c563a2505f5517b42448cfe">findOneSourceFile</a> (const PDBSymbolCompiland *Compiland, llvm::StringRef Pattern, PDB_NameSearchFlags Flags) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbenumchildren">IPDBEnumChildren</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland">PDBSymbolCompiland</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb387336a2eb24bc5e851d74e0635330">findCompilandsForSourceFile</a> (llvm::StringRef Pattern, PDB_NameSearchFlags Flags) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland">PDBSymbolCompiland</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67db713dc0f700cef717cf4291a08fa0">findOneCompilandForSourceFile</a> (llvm::StringRef Pattern, PDB_NameSearchFlags Flags) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae4335f7829654f053ddbeac3c2335c06">IPDBEnumSourceFiles</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae179594daf80487a9abaafd43fa3b6a5">getAllSourceFiles</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae4335f7829654f053ddbeac3c2335c06">IPDBEnumSourceFiles</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0263a584478c49ef6d2bbda66067c861">getSourceFilesForCompiland</a> (const PDBSymbolCompiland &amp;Compiland) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsourcefile">IPDBSourceFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c8106f327fd126e6dbc46e22ad26fc">getSourceFileById</a> (uint32_t FileId) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a386e30dda9ef254a37d02069626268bc">IPDBEnumDataStreams</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb897ccf704446aeb32af9444568d008">getDebugStreams</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a9ddc8f3c09e74d959dfbd811fa8ecbc5">IPDBEnumTables</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88eab9058537f6403f6857f3d0201d30">getEnumTables</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a2fd2e966936f069ea186f74e8755f501">IPDBEnumInjectedSources</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d13b39808b1a7b9b9f8949d474cedd">getInjectedSources</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a46c31c9e96c219a0b92600c9397abbf8">IPDBEnumSectionContribs</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2333034ff47104b39e298fcd7f4359f">getSectionContribs</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#add28aee891a080423f5cf93cee05412d">IPDBEnumFrameData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021131c19cf7aa17aeaa06a61467d66e">getFrameData</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f8511bf1a5eff6c9d89e67e94e9af9">getPDBFile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17430b4cc81240bd91f3bcdbf5f8ac9">getPDBFile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/nativeexesymbol">NativeExeSymbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73eb9fb40d9b91380d0d4db1daeb747">getNativeGlobalScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache">SymbolCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02cfb0d8635ea2f431cd43398f6196b9">getSymbolCache</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache">SymbolCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538a02570eb69e88553d42c78c2dec64">getSymbolCache</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a24ad588b7d53407770f4db55d8a315">getRVAFromSectOffset</a> (uint32_t Section, uint32_t Offset) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33322d9be265c7bf0446cabdc13dea41">getVAFromSectOffset</a> (uint32_t Section, uint32_t Offset) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e9a303e556a771d0a900b4e4453f94">moduleIndexForVA</a> (uint64_t VA, uint16_t &amp;ModuleIndex) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c535be48e878b989dd9a4d06b873a8">moduleIndexForSectOffset</a> (uint32_t Sect, uint32_t Offset, uint16_t &amp;ModuleIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref">ModuleDebugStreamRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb854f12f4521ba6ff2f8c4789bd792f">getModuleDebugStream</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae03c0dfa26ed8dc026cda4c57d80a7ab">initializeExeSymbol</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9eb0d51d1061f11e75add07181b2e36">parseSectionContribs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae99e6b88bb6d32e2f8349e4ce02ed48e">Pdb</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6e5001c8db493b18502eddd9d02e63">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache">SymbolCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fb0686cc82d633b2b8301c204f1842">Cache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c63f64bc3abb8620c4ca5f67e928e8">ExeSymbol</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00e55228d5777360405f285bdec5a27">LoadAddress</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a6b645fcc5ae44b9a8e2fef275890ae4b">IMap::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61db435e4374ba8142009fb0dfc1962a">IMapAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">IMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29110951102f179d6767165323605b2e">AddrToModuleIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a2d747d45eb8ebf19defef962acdb6">createFromPdb</a> (std::unique_ptr&lt; MemoryBuffer &gt; MB, std::unique_ptr&lt; IPDBSession &gt; &amp;Session)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf765bc037aeb5a285300d19ecc0235">createFromPdbPath</a> (StringRef PdbPath, std::unique_ptr&lt; IPDBSession &gt; &amp;Session)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e7e990ed77bc137febf6f0127ea8d0">createFromExe</a> (StringRef Path, std::unique_ptr&lt; IPDBSession &gt; &amp;Session)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c66fa7ae2a9b589c8a2738661897ca">searchForPdb</a> (const PdbSearchOptions &amp;Opts)</td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### IMap {#adcff9b08352b2950db6c2d27b68c659c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::pdb::NativeSession::IMap = 
      IntervalMap&lt;uint64_t, uint16_t, 8, IntervalMapHalfOpenInfo&lt;uint64_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from virtual address to module index.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NativeSession() {#abacb37bf0bac9b174d38283f91c406e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeSession::NativeSession (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> &gt; PdbFile, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt; Allocator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeexesymbol-cpp/#a60028c7e119776d3c849f7782e59661d">getDbiStreamPtr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#ac73eb9fb40d9b91380d0d4db1daeb747">getNativeGlobalScope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~NativeSession() {#a6f33c7c9fda8d551a5bdfc70b9b05aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeSession::~NativeSession ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadd7bf230fde8d4836917806aff6a6b27">llvm::pdb::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba247232063f777fa3c2371e077db8b61b">llvm::pdb::Compiland</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23caac70412e939d72a9234cdebb1af5867b">llvm::pdb::Path</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addressForRVA() {#a277f859f380850343d58cdd740d822b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSession::addressForRVA (uint32_t RVA, uint32_t &amp; Section, uint32_t &amp; Offset)</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a22602a2dcab20f24424225b3bedbcf3a">addressForVA</a> and <a href="#af6b81f0ad477f2c844eaf8710d1b7900">findSymbolByRVA</a>.</p>

</div>
</div>

### addressForVA() {#a22602a2dcab20f24424225b3bedbcf3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSession::addressForVA (uint64_t VA, uint32_t &amp; Section, uint32_t &amp; Offset)</td>
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



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="#a277f859f380850343d58cdd740d822b4">addressForRVA</a>, <a href="#afad6024f1ff0a43f008c382eebe0e8bc">getLoadAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>


<p>Referenced by <a href="#acfe7201ebf6970eebc5d2edddb57d404">findSymbolByAddress</a>.</p>

</div>
</div>

### findCompilandsForSourceFile() {#acb387336a2eb24bc5e851d74e0635330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumChildren&lt; PDBSymbolCompiland &gt; &gt; NativeSession::findCompilandsForSourceFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Pattern, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1d1b2eadb80309d27efbb727411c54ec">PDB_NameSearchFlags</a> Flags)</td>
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



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### findLineNumbers() {#aebd76a96f188964b0ad33acd219433d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumLineNumbers &gt; NativeSession::findLineNumbers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland">PDBSymbolCompiland</a> &amp; Compiland, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsourcefile">IPDBSourceFile</a> &amp; File)</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba247232063f777fa3c2371e077db8b61b">llvm::pdb::Compiland</a>.</p>

</div>
</div>

### findLineNumbersByAddress() {#ace21067119f8cff56f4720d9bd9e00d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumLineNumbers &gt; NativeSession::findLineNumbersByAddress (uint64_t Address, uint32_t Length)</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadd7bf230fde8d4836917806aff6a6b27">llvm::pdb::Address</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

### findLineNumbersByRVA() {#a3164daf5c652f03c1491fdc8e5b4913c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumLineNumbers &gt; NativeSession::findLineNumbersByRVA (uint32_t RVA, uint32_t Length)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="#afad6024f1ff0a43f008c382eebe0e8bc">getLoadAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>

</div>
</div>

### findLineNumbersBySectOffset() {#a3532a5ed6f2849be0b297aa8db038e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumLineNumbers &gt; NativeSession::findLineNumbersBySectOffset (uint32_t Section, uint32_t Offset, uint32_t Length)</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="#a33322d9be265c7bf0446cabdc13dea41">getVAFromSectOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>

</div>
</div>

### findOneCompilandForSourceFile() {#a67db713dc0f700cef717cf4291a08fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbolCompiland &gt; NativeSession::findOneCompilandForSourceFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Pattern, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1d1b2eadb80309d27efbb727411c54ec">PDB_NameSearchFlags</a> Flags)</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### findOneSourceFile() {#af0b06f3a0c563a2505f5517b42448cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBSourceFile &gt; NativeSession::findOneSourceFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland">PDBSymbolCompiland</a> * Compiland, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Pattern, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1d1b2eadb80309d27efbb727411c54ec">PDB_NameSearchFlags</a> Flags)</td>
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



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba247232063f777fa3c2371e077db8b61b">llvm::pdb::Compiland</a>.</p>

</div>
</div>

### findSourceFiles() {#a25b43eeb05042b2141ff01abe732ffc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumSourceFiles &gt; NativeSession::findSourceFiles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland">PDBSymbolCompiland</a> * Compiland, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Pattern, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1d1b2eadb80309d27efbb727411c54ec">PDB_NameSearchFlags</a> Flags)</td>
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



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba247232063f777fa3c2371e077db8b61b">llvm::pdb::Compiland</a>.</p>

</div>
</div>

### findSymbolByAddress() {#acfe7201ebf6970eebc5d2edddb57d404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbol &gt; NativeSession::findSymbolByAddress (uint64_t Address, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30b">PDB_SymType</a> Type)</td>
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



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadd7bf230fde8d4836917806aff6a6b27">llvm::pdb::Address</a>, <a href="#a22602a2dcab20f24424225b3bedbcf3a">addressForVA</a>, <a href="#a489ca1ad15b298eefea45fc445781b14">findSymbolBySectOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

### findSymbolByRVA() {#af6b81f0ad477f2c844eaf8710d1b7900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbol &gt; NativeSession::findSymbolByRVA (uint32_t RVA, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30b">PDB_SymType</a> Type)</td>
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



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="#a277f859f380850343d58cdd740d822b4">addressForRVA</a>, <a href="#a489ca1ad15b298eefea45fc445781b14">findSymbolBySectOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

### findSymbolBySectOffset() {#a489ca1ad15b298eefea45fc445781b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbol &gt; NativeSession::findSymbolBySectOffset (uint32_t Sect, uint32_t Offset, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30b">PDB_SymType</a> Type)</td>
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



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>


<p>Referenced by <a href="#acfe7201ebf6970eebc5d2edddb57d404">findSymbolByAddress</a> and <a href="#af6b81f0ad477f2c844eaf8710d1b7900">findSymbolByRVA</a>.</p>

</div>
</div>

### getAllSourceFiles() {#ae179594daf80487a9abaafd43fa3b6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumSourceFiles &gt; NativeSession::getAllSourceFiles ()</td>
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



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getDebugStreams() {#aeb897ccf704446aeb32af9444568d008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumDataStreams &gt; NativeSession::getDebugStreams ()</td>
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



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getEnumTables() {#a88eab9058537f6403f6857f3d0201d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumTables &gt; NativeSession::getEnumTables ()</td>
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



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getFrameData() {#a021131c19cf7aa17aeaa06a61467d66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumFrameData &gt; NativeSession::getFrameData ()</td>
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



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getGlobalScope() {#a1ec0a067a0a5fb05e01dfd6350dc3308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbolExe &gt; NativeSession::getGlobalScope ()</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a1156974e21ae291dbf690aa300fa9d8b">llvm::pdb::PDBSymbol::createAs</a> and <a href="#ac73eb9fb40d9b91380d0d4db1daeb747">getNativeGlobalScope</a>.</p>

</div>
</div>

### getInjectedSources() {#a87d13b39808b1a7b9b9f8949d474cedd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumInjectedSources &gt; NativeSession::getInjectedSources ()</td>
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



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>.</p>

</div>
</div>

### getLoadAddress() {#afad6024f1ff0a43f008c382eebe0e8bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeSession::getLoadAddress ()</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Referenced by <a href="#a22602a2dcab20f24424225b3bedbcf3a">addressForVA</a> and <a href="#a3164daf5c652f03c1491fdc8e5b4913c">findLineNumbersByRVA</a>.</p>

</div>
</div>

### getModuleDebugStream() {#adb854f12f4521ba6ff2f8c4789bd792f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ModuleDebugStreamRef &gt; NativeSession::getModuleDebugStream (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeexesymbol-cpp/#a60028c7e119776d3c849f7782e59661d">getDbiStreamPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#a9c8a7829dd7c35a1d5da5f9fb7c4ac22">llvm::pdb::DbiModuleDescriptor::getModuleStreamIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0a7a9a9849fa2f1e5dec7a99ba9530da">llvm::pdb::kInvalidStreamIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/moduledebugstreamref/#a0384c62524bcae12ec581fe7872a091a">llvm::pdb::ModuleDebugStreamRef::reload</a>.</p>

</div>
</div>

### getNativeGlobalScope() {#ac73eb9fb40d9b91380d0d4db1daeb747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NativeExeSymbol &amp; NativeSession::getNativeGlobalScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="#abacb37bf0bac9b174d38283f91c406e2">NativeSession</a>.</p>


<p>Referenced by <a href="#a1ec0a067a0a5fb05e01dfd6350dc3308">getGlobalScope</a>.</p>

</div>
</div>

### getPDBFile() {#a84f8511bf1a5eff6c9d89e67e94e9af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDBFile &amp; llvm::pdb::NativeSession::getPDBFile ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeexesymbol-cpp/#a60028c7e119776d3c849f7782e59661d">getDbiStreamPtr</a>.</p>

</div>
</div>

### getPDBFile() {#ac17430b4cc81240bd91f3bcdbf5f8ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PDBFile &amp; llvm::pdb::NativeSession::getPDBFile ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### getRVAFromSectOffset() {#a6a24ad588b7d53407770f4db55d8a315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t NativeSession::getRVAFromSectOffset (uint32_t Section, uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativeexesymbol-cpp/#a60028c7e119776d3c849f7782e59661d">getDbiStreamPtr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>


<p>Referenced by <a href="#a33322d9be265c7bf0446cabdc13dea41">getVAFromSectOffset</a>.</p>

</div>
</div>

### getSectionContribs() {#ab2333034ff47104b39e298fcd7f4359f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumSectionContribs &gt; NativeSession::getSectionContribs ()</td>
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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getSourceFileById() {#a94c8106f327fd126e6dbc46e22ad26fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBSourceFile &gt; NativeSession::getSourceFileById (uint32_t FileId)</td>
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



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getSourceFilesForCompiland() {#a0263a584478c49ef6d2bbda66067c861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IPDBEnumSourceFiles &gt; NativeSession::getSourceFilesForCompiland (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland">PDBSymbolCompiland</a> &amp; Compiland)</td>
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



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a33e853ec74d48b1340d1d4bae772d30ba247232063f777fa3c2371e077db8b61b">llvm::pdb::Compiland</a>.</p>

</div>
</div>

### getSymbolById() {#aefe49dc54ae0d2ef1e1484fa181d7104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; PDBSymbol &gt; NativeSession::getSymbolById (<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0d95a0af7fff523a0a4bfb7f6b578d12">SymIndexId</a> SymbolId)</td>
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



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### getSymbolCache() {#a02cfb0d8635ea2f431cd43398f6196b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolCache &amp; llvm::pdb::NativeSession::getSymbolCache ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### getSymbolCache() {#a538a02570eb69e88553d42c78c2dec64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolCache &amp; llvm::pdb::NativeSession::getSymbolCache ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### getVAFromSectOffset() {#a33322d9be265c7bf0446cabdc13dea41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t NativeSession::getVAFromSectOffset (uint32_t Section, uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="#a6a24ad588b7d53407770f4db55d8a315">getRVAFromSectOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>


<p>Referenced by <a href="#a3532a5ed6f2849be0b297aa8db038e38">findLineNumbersBySectOffset</a> and <a href="#a31c535be48e878b989dd9a4d06b873a8">moduleIndexForSectOffset</a>.</p>

</div>
</div>

### moduleIndexForSectOffset() {#a31c535be48e878b989dd9a4d06b873a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSession::moduleIndexForSectOffset (uint32_t Sect, uint32_t Offset, uint16_t &amp; ModuleIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="#a33322d9be265c7bf0446cabdc13dea41">getVAFromSectOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadfd0a82c4bf37b1e90b690a22a20692e">llvm::pdb::Offset</a>.</p>

</div>
</div>

### moduleIndexForVA() {#ae4e9a303e556a771d0a900b4e4453f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSession::moduleIndexForVA (uint64_t VA, uint16_t &amp; ModuleIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### setLoadAddress() {#a8f44423e4ee68c7ba3ebc14172446e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NativeSession::setLoadAddress (uint64_t Address)</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23cadd7bf230fde8d4836917806aff6a6b27">llvm::pdb::Address</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### initializeExeSymbol() {#ae03c0dfa26ed8dc026cda4c57d80a7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeSession::initializeExeSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

### parseSectionContribs() {#af9eb0d51d1061f11e75add07181b2e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NativeSession::parseSectionContribs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrToModuleIndex {#a29110951102f179d6767165323605b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IMap llvm::pdb::NativeSession::AddrToModuleIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### Allocator {#aae6e5001c8db493b18502eddd9d02e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BumpPtrAllocator&gt; llvm::pdb::NativeSession::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### Cache {#ac6fb0686cc82d633b2b8301c204f1842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolCache llvm::pdb::NativeSession::Cache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### ExeSymbol {#ae4c63f64bc3abb8620c4ca5f67e928e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymIndexId llvm::pdb::NativeSession::ExeSymbol = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### IMapAllocator {#a61db435e4374ba8142009fb0dfc1962a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IMap::Allocator llvm::pdb::NativeSession::IMapAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### LoadAddress {#ae00e55228d5777360405f285bdec5a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::pdb::NativeSession::LoadAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

### Pdb {#ae99e6b88bb6d32e2f8349e4ce02ed48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;PDBFile&gt; llvm::pdb::NativeSession::Pdb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createFromExe() {#a41e7e990ed77bc137febf6f0127ea8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error NativeSession::createFromExe (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">IPDBSession</a> &gt; &amp; Session)</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#a6d532e2f19636873f69d5c0d7524dc38">getPdbPathFromExe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#ae1d1df29b280e901fe36cd22e7072f95">loadPdbFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msf/#afa98ccc224894a8f32ec9ed84776e709">llvm::msf::Magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa0d7b7082a37cb024864ce149d0b04f5f">llvm::file_magic::pdb</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### createFromPdb() {#a40a2d747d45eb8ebf19defef962acdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error NativeSession::createFromPdb (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; MB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">IPDBSession</a> &gt; &amp; Session)</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23caac70412e939d72a9234cdebb1af5867b">llvm::pdb::Path</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### createFromPdbPath() {#a8cf765bc037aeb5a285300d19ecc0235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error NativeSession::createFromPdbPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PdbPath, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsession">IPDBSession</a> &gt; &amp; Session)</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#ae1d1df29b280e901fe36cd22e7072f95">loadPdbFile</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1307fe9528cee604862ce0966931dc6b">llvm::pdb::loadDataForEXE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#af4c4166fc69a542bfee8013a10a63c7e">llvm::pdb::loadDataForPDB</a>.</p>

</div>
</div>

### searchForPdb() {#a10c66fa7ae2a9b589c8a2738661897ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; NativeSession::searchForPdb (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PdbSearchOptions &amp; Opts)</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#a6d532e2f19636873f69d5c0d7524dc38">getPdbPathFromExe</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#ae1d1df29b280e901fe36cd22e7072f95">loadPdbFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa950616e5405e4ef51a87d384180e7aa1">llvm::sys::path::posix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a03907c7df68a93c377bf90c5bdd78ca3">llvm::sys::path::remove_filename</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa0f4137ed1502b5045d6083aa258b5c42">llvm::sys::path::windows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1307fe9528cee604862ce0966931dc6b">llvm::pdb::loadDataForEXE</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lvreaderhandler-cpp/#af7b4a495780ab66e37af8b9881e7ad93">searchForExe</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/nativesession-h">NativeSession.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp">NativeSession.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
