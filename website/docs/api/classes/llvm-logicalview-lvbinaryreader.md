---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvbinaryreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVBinaryReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVBinaryReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">llvm/DebugInfo/LogicalView/Readers/LVBinaryReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader">LVReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The logical reader owns of all the logical elements created during the debug information parsing. <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader">LVCodeViewReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader">LVDWARFReader</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979df302b996cc5a296ff1aed95a6951">LVInlineeLine</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> &gt; &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506dce7ea66fac27d5edb7bc58e967fc">LVSectionAddresses</a> = std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2a45ae8cbed921aa56c77c0f6d3779">LVSectionRanges</a> = std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange">LVRange</a> &gt; &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be587a3cc7bd09981cf491af62cf291">LVSections</a> = std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d562b41fb3c6d478f38b73cfa44ab3">LVBinaryReader</a> ()=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90487a134bc2d94772898fa50e09896">LVBinaryReader</a> (StringRef Filename, StringRef FileFormatName, ScopedPrinter &amp;W, LVBinaryType BinaryType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1189b7bf00d12e735f6634427e5caf">LVBinaryReader</a> (const LVBinaryReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e80e1062d9ac983e1e5ecc558aee97c">~LVBinaryReader</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader">LVBinaryReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f87113ad0fdf1bb0e84377519cfa327">operator=</a> (const LVBinaryReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a6a2cd9de149501903770466ab75b4">addInlineeLines</a> (LVScope *Scope, LVLines &amp;Lines)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad68ac39542686af057c65d315c24ba">linearAddress</a> (uint16_t Segment, uint32_t Offset, LVAddress Addendum=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f98cb63bfe0a4c10282bbe286bde33a">addToSymbolTable</a> (StringRef Name, LVScope *Function, LVSectionIndex SectionIndex=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33636e75d54396bb47b2a88360ea14a3">addToSymbolTable</a> (StringRef Name, LVAddress Address, LVSectionIndex SectionIndex, bool IsComdat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0735018d9f77fda1d3ac1ef26d5d55c2">updateSymbolTable</a> (LVScope *Function)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/logicalview/lvsymboltableentry">LVSymbolTableEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a037e91a15a304677121ba36b89f75827">getSymbolTableEntry</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fafc62a64832e5a445da37a06fb7be">getSymbolTableAddress</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb05d655c3b4abdb2c2ef3b7b553e1b">getSymbolTableIndex</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6d1cd3aa62f8b56e0e2b976a47e399">getSymbolTableIsComdat</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23627e0b6a1a860f08078cffc221b4b6">getSectionIndex</a> (LVScope *Scope) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a740f19b6aaa166ffb6c29565ad8fc0ba">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff110c6f5553986884d9b984319d0d6">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a> (StringRef TheTriple, StringRef TheFeatures)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822b011606e4750a28584ab46d14462e">mapRangeAddress</a> (const object::ObjectFile &amp;Obj)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfa7e2ea8284709b02dad428cc3efb1">mapRangeAddress</a> (const object::ObjectFile &amp;Obj, const object::SectionRef &amp;Section, bool IsComdat)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f648767e6fee704685f85355aa7fa64">mapVirtualAddress</a> (const object::ObjectFile &amp;Obj)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b4341d651ea41cb74546557170ebaa">mapVirtualAddress</a> (const object::COFFObjectFile &amp;COFFObj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1ac3b9ee5a622c81ce24639725d83a">getSection</a> (LVScope *Scope, LVAddress Address, LVSectionIndex SectionIndex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95ed9d1449a665ba1c71c5251e34ab7">addSectionRange</a> (LVSectionIndex SectionIndex, LVScope *Scope)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529ceb2a8c2325e195bd8a1819891889">addSectionRange</a> (LVSectionIndex SectionIndex, LVScope *Scope, LVAddress LowerAddress, LVAddress UpperAddress)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange">LVRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb616341561b2b08f925cccf1c7481ee">getSectionRanges</a> (LVSectionIndex SectionIndex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f647a3f5093cbe2bc5ff3e9e295289d">includeInlineeLines</a> (LVSectionIndex SectionIndex, LVScope *Function)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2a6238adfb3ada928de5340d5298b6">createInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac378e86f9979cde149105568f10ee404">createInstructions</a> (LVScope *Function, LVSectionIndex SectionIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3f70a5f3d1222550716fb9db632c6a">createInstructions</a> (LVScope *Function, LVSectionIndex SectionIndex, const LVNameInfo &amp;NameInfo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873cd38481c3ed6a7e21bc016ec10ae2">processLines</a> (LVLines *DebugLines, LVSectionIndex SectionIndex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65eee5509cce98dcc69693ea13bb9220">processLines</a> (LVLines *DebugLines, LVSectionIndex SectionIndex, LVScope *Function)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08a39adcb7f8e92d9c79ca3de6bc4e8">addSectionAddress</a> (const object::SectionRef &amp;Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f70da07f056e7436d80fcddcc760164">CULines</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2018d81dede6424ed445ad0c80083d2">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5bd27217843e17f7dc34493ee2a7c3">MAI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ab8004d321f3e4d61b5b128b571285">STI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34358eaff90c8c985f8da3089bbd1d95">MII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92d4edd35a110d7f835e5ab051db5d0">MD</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269427268a7c733324ef40f3c6f8a974">MC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61933462a970b04a39d29b0391eae0b">MIP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec94a149e209340a7464f9b9c1788e1b">WasmCodeSectionOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymboltable">LVSymbolTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65012694b1741b991d0986dc6adeab11">SymbolTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVInlineeLine</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847bfa009f88a21d94ed4b76a572c0e3">CUInlineeLines</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdoublemap">LVDoubleMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035fc5ec3ddbe7933856c50c4963d517">ScopeInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdoublemap">LVDoubleMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb84b3854b407be41ad4a202a0080ff7">AssemblerMappings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVSectionAddresses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e22b2e2d22a8cdb34271496bc5cddfe">SectionAddresses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVSectionRanges</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c9d6826c7e46b75f41e1b056b4a291">SectionRanges</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad710bbbe1d544149b49162237d6dbd0">ImageBaseAddress</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c30902c6256036a010dfef71245fe8d">VirtualAddress</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVSections</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0e31501157d9ebd8923bcaf30dae02">Sections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5355e61468c8a3e23fcdc8ba51683fa">DiscoveredLines</a></td>
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


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LVInlineeLine {#a979df302b996cc5a296ff1aed95a6951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVBinaryReader::LVInlineeLine =  std::map&lt;LVScope *, std::unique_ptr&lt;LVLines&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### LVSectionAddresses {#a506dce7ea66fac27d5edb7bc58e967fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVBinaryReader::LVSectionAddresses =  std::map&lt;LVSectionIndex, object::SectionRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### LVSectionRanges {#aca2a45ae8cbed921aa56c77c0f6d3779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVBinaryReader::LVSectionRanges =  std::map&lt;LVSectionIndex, std::unique_ptr&lt;LVRange&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### LVSections {#a2be587a3cc7bd09981cf491af62cf291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVBinaryReader::LVSections =  std::map&lt;LVSectionIndex, object::SectionRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVBinaryReader() {#a77d562b41fb3c6d478f38b73cfa44ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVBinaryReader::LVBinaryReader ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#a4c1189b7bf00d12e735f6634427e5caf">LVBinaryReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a5a1bd6b089058360736e027da1171157">llvm::logicalview::LVCodeViewReader::LVCodeViewReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#aca7919065cf881851a0edff7ae9fbeb1">llvm::logicalview::LVCodeViewReader::LVCodeViewReader</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#aa5c941357b1a4565c7001065a68fb538">llvm::logicalview::LVDWARFReader::LVDWARFReader</a> and <a href="#a9f87113ad0fdf1bb0e84377519cfa327">operator=</a>.</p>

</div>
</div>

### LVBinaryReader() {#ab90487a134bc2d94772898fa50e09896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVBinaryReader::LVBinaryReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileFormatName, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833c">LVBinaryType</a> BinaryType)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a30c36ab397c2a31a605e88a0a476ee9c">llvm::logicalview::LVReader::FileFormatName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a3e8126edb83953e3574e3219f2699441">llvm::logicalview::LVReader::LVReader</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a05c1edcb51769b9ed74087532906b12e">llvm::logicalview::LVReader::W</a>.</p>

</div>
</div>

### LVBinaryReader() {#a4c1189b7bf00d12e735f6634427e5caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVBinaryReader::LVBinaryReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader">LVBinaryReader</a> &amp;)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Reference <a href="#a77d562b41fb3c6d478f38b73cfa44ab3">LVBinaryReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVBinaryReader() {#a2e80e1062d9ac983e1e5ecc558aee97c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::logicalview::LVBinaryReader::~LVBinaryReader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9f87113ad0fdf1bb0e84377519cfa327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVBinaryReader &amp; llvm::logicalview::LVBinaryReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader">LVBinaryReader</a> &amp;)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Reference <a href="#a77d562b41fb3c6d478f38b73cfa44ab3">LVBinaryReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInlineeLines() {#a43a6a2cd9de149501903770466ab75b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVBinaryReader::addInlineeLines (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> &amp; Lines)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### addToSymbolTable() {#a7f98cb63bfe0a4c10282bbe286bde33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::addToSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>


<p>Referenced by <a href="#a2f647a3f5093cbe2bc5ff3e9e295289d">includeInlineeLines</a>.</p>

</div>
</div>

### addToSymbolTable() {#a33636e75d54396bb47b2a88360ea14a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::addToSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Address, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, bool IsComdat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### dump() {#a6ff110c6f5553986884d9b984319d0d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVBinaryReader::dump ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a740f19b6aaa166ffb6c29565ad8fc0ba">print</a>.</p>

</div>
</div>

### getSectionIndex() {#a23627e0b6a1a860f08078cffc221b4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex llvm::logicalview::LVBinaryReader::getSectionIndex (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ac33e886406f67bcea7a9e84d0e648bf3">llvm::logicalview::LVReader::DotTextSectionIndex</a> and <a href="#a9eb05d655c3b4abdb2c2ef3b7b553e1b">getSymbolTableIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>.</p>

</div>
</div>

### getSymbolTableAddress() {#a67fafc62a64832e5a445da37a06fb7be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress LVBinaryReader::getSymbolTableAddress (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### getSymbolTableEntry() {#a037e91a15a304677121ba36b89f75827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVSymbolTableEntry &amp; LVBinaryReader::getSymbolTableEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### getSymbolTableIndex() {#a9eb05d655c3b4abdb2c2ef3b7b553e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex LVBinaryReader::getSymbolTableIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>


<p>Referenced by <a href="#adf2a6238adfb3ada928de5340d5298b6">createInstructions</a> and <a href="#a23627e0b6a1a860f08078cffc221b4b6">getSectionIndex</a>.</p>

</div>
</div>

### getSymbolTableIsComdat() {#aad6d1cd3aa62f8b56e0e2b976a47e399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LVBinaryReader::getSymbolTableIsComdat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### linearAddress() {#a7ad68ac39542686af057c65d315c24ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVBinaryReader::linearAddress (uint16_t Segment, uint32_t Offset, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Addendum=0)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>.</p>

</div>
</div>

### print() {#a740f19b6aaa166ffb6c29565ad8fc0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ae3b66787d42fd33ae1c2fe2c5fd7225c">llvm::logicalview::LVReader::OS</a>.</p>


<p>Referenced by <a href="#a6ff110c6f5553986884d9b984319d0d6">dump</a>.</p>

</div>
</div>

### updateSymbolTable() {#a0735018d9f77fda1d3ac1ef26d5d55c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex LVBinaryReader::updateSymbolTable (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addSectionRange() {#ad95ed9d1449a665ba1c71c5251e34ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::addSectionRange (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#adce7ef8a5f0e0e954cadfb779f665859">llvm::logicalview::LVRange::addEntry</a> and <a href="#abb616341561b2b08f925cccf1c7481ee">getSectionRanges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>.</p>

</div>
</div>

### addSectionRange() {#a529ceb2a8c2325e195bd8a1819891889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::addSectionRange (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> LowerAddress, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> UpperAddress)</td>
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



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#adce7ef8a5f0e0e954cadfb779f665859">llvm::logicalview::LVRange::addEntry</a> and <a href="#abb616341561b2b08f925cccf1c7481ee">getSectionRanges</a>.</p>

</div>
</div>

### createInstructions() {#adf2a6238adfb3ada928de5340d5298b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVBinaryReader::createInstructions ()</td>
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



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aabd8bf25dbcb16ca9fa57ef73d062006">llvm::logicalview::LVReader::CompileUnit</a>, <a href="#adf2a6238adfb3ada928de5340d5298b6">createInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="#a9eb05d655c3b4abdb2c2ef3b7b553e1b">getSymbolTableIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#adf2a6238adfb3ada928de5340d5298b6">createInstructions</a>, <a href="#ac378e86f9979cde149105568f10ee404">createInstructions</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>.</p>

</div>
</div>

### createInstructions() {#ac378e86f9979cde149105568f10ee404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVBinaryReader::createInstructions (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex)</td>
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



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aabd8bf25dbcb16ca9fa57ef73d062006">llvm::logicalview::LVReader::CompileUnit</a>, <a href="#adf2a6238adfb3ada928de5340d5298b6">createInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>

</div>
</div>

### createInstructions() {#a6e3f70a5f3d1222550716fb9db632c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVBinaryReader::createInstructions (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a17921983fe8c6609f9a818b13772efbb">LVNameInfo</a> &amp; NameInfo)</td>
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



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac071e70044138f6b9a2568a4bac82352">llvm::fmt_align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af06dfa98846bc5821b3f84c4014c7686">llvm::format_bytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a0c1ac3b9ee5a622c81ce24639725d83a">getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a8d87e69e124542d3338b631934cdbea9a49cc8e6220245b65cd7d20fc6ccc74f5">llvm::logicalview::Instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a945d5e233cf7d6240f6b783b36a374ff">llvm::Left</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ab92d4edd35a110d7f835e5ab051db5d0">MD</a>, <a href="#ae61933462a970b04a39d29b0391eae0b">MIP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa9d693b8e530a7fa3457dece6f8951e6c">llvm::MCDisassembler::SoftFail</a>, <a href="#a79ab8004d321f3e4d61b5b128b571285">STI</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#ab9990397f97b40d5d8564e000d00174a">llvm::StringRef::trim</a>.</p>

</div>
</div>

### getSection() {#a0c1ac3b9ee5a622c81ce24639725d83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::pair&lt; uint64_t, object::SectionRef &gt; &gt; LVBinaryReader::getSection (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Address, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex)</td>
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



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>.</p>


<p>Referenced by <a href="#a6e3f70a5f3d1222550716fb9db632c6a">createInstructions</a>.</p>

</div>
</div>

### getSectionRanges() {#abb616341561b2b08f925cccf1c7481ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVRange * LVBinaryReader::getSectionRanges (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex)</td>
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



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa87ba2ecc8b6915e8bd6f5089918229fd">llvm::logicalview::Range</a>.</p>


<p>Referenced by <a href="#ad95ed9d1449a665ba1c71c5251e34ab7">addSectionRange</a>, <a href="#a529ceb2a8c2325e195bd8a1819891889">addSectionRange</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a> and <a href="#a65eee5509cce98dcc69693ea13bb9220">processLines</a>.</p>

</div>
</div>

### includeInlineeLines() {#a2f647a3f5093cbe2bc5ff3e9e295289d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::includeInlineeLines (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function)</td>
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



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="#a7f98cb63bfe0a4c10282bbe286bde33a">addToSymbolTable</a>, <a href="#a7f70da07f056e7436d80fcddcc760164">CULines</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a37fc81a3671c77ca160274dfa7a6d9fb">llvm::logicalview::LVScope::getScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a04eb43a6dc736c2d6ed8dcc6d636a2afa55754bcb413b06333e15211f66f05353">llvm::codeview::InlineeLines</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### loadGenericTargetInfo() {#ad1c77f840dadc1ffb03432c9e688e4c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVBinaryReader::loadGenericTargetInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TheTriple, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TheFeatures)</td>
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



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/target/#a9a65dcb8a1d47b55360f95a575dedb62">llvm::Target::createMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9453c999bd3483858dec967aa3b8fca2">llvm::Target::createMCDisassembler</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9aecbb4df7336a0a60255508e24e93d3">llvm::Target::createMCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#afbeb195717f888bfc2ba9f54e9623bae">llvm::Target::createMCInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7291082412f4df3356f434aac4685911">llvm::Target::createMCRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a3b11020c76ae0245d4aee684528e8a73">llvm::Target::createMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a403352e1bd073ad5ea775fa48b598d60">llvm::MCAsmInfo::getAssemblerDialect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="#a9c5bd27217843e17f7dc34493ee2a7c3">MAI</a>, <a href="#a269427268a7c733324ef40f3c6f8a974">MC</a>, <a href="#ab92d4edd35a110d7f835e5ab051db5d0">MD</a>, <a href="#a34358eaff90c8c985f8da3089bbd1d95">MII</a>, <a href="#ae61933462a970b04a39d29b0391eae0b">MIP</a>, <a href="#ab2018d81dede6424ed445ad0c80083d2">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a5315ee213d2bb70bfb0d581369c8bd47">llvm::MCInstPrinter::setPrintImmHex</a>, <a href="#a79ab8004d321f3e4d61b5b128b571285">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### mapRangeAddress() {#a822b011606e4750a28584ab46d14462e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::logicalview::LVBinaryReader::mapRangeAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#a50b4341d651ea41cb74546557170ebaa">mapVirtualAddress</a> and <a href="#a8f648767e6fee704685f85355aa7fa64">mapVirtualAddress</a>.</p>

</div>
</div>

### mapRangeAddress() {#aabfa7e2ea8284709b02dad428cc3efb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::logicalview::LVBinaryReader::mapRangeAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &amp; Section, bool IsComdat)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### mapVirtualAddress() {#a8f648767e6fee704685f85355aa7fa64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::mapVirtualAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ac33e886406f67bcea7a9e84d0e648bf3">llvm::logicalview::LVReader::DotTextSectionIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a1d0de81caf9ed94cc291ff18c2ea802a">llvm::object::Binary::isWasm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a822b011606e4750a28584ab46d14462e">mapRangeAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#aec94a149e209340a7464f9b9c1788e1b">WasmCodeSectionOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>.</p>

</div>
</div>

### mapVirtualAddress() {#a50b4341d651ea41cb74546557170ebaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::mapVirtualAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile">object::COFFObjectFile</a> &amp; COFFObj)</td>
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



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a5d5c6f0e1d23df171e3bdd1c027a06e1">llvm::object::coff_section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb">llvm::ErrorOr&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ab5c5fe9889d863b8a8fbe02cbf68f662">llvm::object::COFFObjectFile::getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#ab0ecb019a3168e2f3d4cdeaabd3d9b10">llvm::object::COFFObjectFile::getImageBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa2b3dbe611464bb08a83985d56d7bc67b">llvm::COFF::IMAGE_SCN_CNT_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa86b861e119d7e8b4bf5d9664671667ca">llvm::COFF::IMAGE_SCN_LNK_COMDAT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a822b011606e4750a28584ab46d14462e">mapRangeAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a030e8ad39c3fe9a41a2f1927c5255701">llvm::object::coff_section::PointerToRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>, <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#a8882aa2bfacd40fbbd4bac3f492269c6">llvm::object::coff_section::SizeOfRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/structs/llvm/object/coff-section/#aa784468f9faf20b0d54bbe644a0b94f0">llvm::object::coff_section::VirtualAddress</a>.</p>

</div>
</div>

### processLines() {#a873cd38481c3ed6a7e21bc016ec10ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::processLines (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> * DebugLines, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex)</td>
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



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aabd8bf25dbcb16ca9fa57ef73d062006">llvm::logicalview::LVReader::CompileUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a873cd38481c3ed6a7e21bc016ec10ae2">processLines</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a> and <a href="#a873cd38481c3ed6a7e21bc016ec10ae2">processLines</a>.</p>

</div>
</div>

### processLines() {#a65eee5509cce98dcc69693ea13bb9220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVBinaryReader::processLines (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad04c501dd7f0cb888ae3e44b71be05e0">LVLines</a> * DebugLines, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function)</td>
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



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a08415ad3aca5fdf4f53418cea4a06ff4">llvm::logicalview::LVScope::addElement</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aabd8bf25dbcb16ca9fa57ef73d062006">llvm::logicalview::LVReader::CompileUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#affc4358004896c62821024b67f8dae5d">llvm::logicalview::LVRange::endSearch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#a0409fa6b52c2d7e04d9c1d0e63c72479">llvm::logicalview::LVRange::getEntry</a>, <a href="#abb616341561b2b08f925cccf1c7481ee">getSectionRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a49e9684d6b3ce0b3b3744a864c3212e6">llvm::logicalview::patterns</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvpatterns/#a1a615f01902ab8f50c01b56bc6f2a8ff">llvm::logicalview::LVPatterns::resolvePatternMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#a85238d38a2e02ae1b9f155e95bb8c5d5">llvm::logicalview::LVRange::startSearch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSectionAddress() {#ad08a39adcb7f8e92d9c79ca3de6bc4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVBinaryReader::addSectionAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">object::SectionRef</a> &amp; Section)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CULines {#a7f70da07f056e7436d80fcddcc760164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVLines llvm::logicalview::LVBinaryReader::CULines</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a> and <a href="#a2f647a3f5093cbe2bc5ff3e9e295289d">includeInlineeLines</a>.</p>

</div>
</div>

### MAI {#a9c5bd27217843e17f7dc34493ee2a7c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCAsmInfo&gt; llvm::logicalview::LVBinaryReader::MAI</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### MC {#a269427268a7c733324ef40f3c6f8a974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCContext&gt; llvm::logicalview::LVBinaryReader::MC</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### MD {#ab92d4edd35a110d7f835e5ab051db5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCDisassembler&gt; llvm::logicalview::LVBinaryReader::MD</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#a6e3f70a5f3d1222550716fb9db632c6a">createInstructions</a> and <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### MII {#a34358eaff90c8c985f8da3089bbd1d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCInstrInfo&gt; llvm::logicalview::LVBinaryReader::MII</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### MIP {#ae61933462a970b04a39d29b0391eae0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCInstPrinter&gt; llvm::logicalview::LVBinaryReader::MIP</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#a6e3f70a5f3d1222550716fb9db632c6a">createInstructions</a> and <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### MRI {#ab2018d81dede6424ed445ad0c80083d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCRegisterInfo&gt; llvm::logicalview::LVBinaryReader::MRI</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a6e3d7579887f71bf2b4cf7def5a3d77b">llvm::logicalview::LVDWARFReader::getRegisterName</a> and <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### STI {#a79ab8004d321f3e4d61b5b128b571285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const MCSubtargetInfo&gt; llvm::logicalview::LVBinaryReader::STI</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#a6e3f70a5f3d1222550716fb9db632c6a">createInstructions</a> and <a href="#ad1c77f840dadc1ffb03432c9e688e4c6">loadGenericTargetInfo</a>.</p>

</div>
</div>

### WasmCodeSectionOffset {#aec94a149e209340a7464f9b9c1788e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVBinaryReader::WasmCodeSectionOffset = 0</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>Referenced by <a href="#a8f648767e6fee704685f85355aa7fa64">mapVirtualAddress</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AssemblerMappings {#abb84b3854b407be41ad4a202a0080ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVDoubleMap&lt;LVSectionIndex, LVAddress, LVScope *&gt; llvm::logicalview::LVBinaryReader::AssemblerMappings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### CUInlineeLines {#a847bfa009f88a21d94ed4b76a572c0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVInlineeLine llvm::logicalview::LVBinaryReader::CUInlineeLines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### DiscoveredLines {#ad5355e61468c8a3e23fcdc8ba51683fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;LVLines&gt; &gt; llvm::logicalview::LVBinaryReader::DiscoveredLines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### ImageBaseAddress {#aad710bbbe1d544149b49162237d6dbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::logicalview::LVBinaryReader::ImageBaseAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### ScopeInstructions {#a035fc5ec3ddbe7933856c50c4963d517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVDoubleMap&lt;LVSectionIndex, LVScope *, LVLines *&gt; llvm::logicalview::LVBinaryReader::ScopeInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### SectionAddresses {#a2e22b2e2d22a8cdb34271496bc5cddfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionAddresses llvm::logicalview::LVBinaryReader::SectionAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### SectionRanges {#a66c9d6826c7e46b75f41e1b056b4a291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionRanges llvm::logicalview::LVBinaryReader::SectionRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### Sections {#abe0e31501157d9ebd8923bcaf30dae02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSections llvm::logicalview::LVBinaryReader::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### SymbolTable {#a65012694b1741b991d0986dc6adeab11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbolTable llvm::logicalview::LVBinaryReader::SymbolTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

### VirtualAddress {#a2c30902c6256036a010dfef71245fe8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::logicalview::LVBinaryReader::VirtualAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
