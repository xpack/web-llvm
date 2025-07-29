---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvdwarfreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVDWARFReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVDWARFReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">llvm/DebugInfo/LogicalView/Readers/LVDWARFReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader">LVBinaryReader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae075f001bcf7871ad2e06adf432ed03c">LVElementSet</a> = std::unordered_set&lt; <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bf1445244febbbfef513fab898f347">LVElementReference</a> = std::unordered_map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a>, LVElementEntry &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eeccb0c42d994c7983021e929bc6e96">LVDWARFReader</a> ()=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c941357b1a4565c7001065a68fb538">LVDWARFReader</a> (StringRef Filename, StringRef FileFormatName, object::ObjectFile &amp;Obj, ScopedPrinter &amp;W)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194c5bdcd83c3806641808b42df41b42">LVDWARFReader</a> (const LVDWARFReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c90329b38a75958e5845601938dcbd">~LVDWARFReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader">LVDWARFReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a09d509675eff595e8028e1ec65024">operator=</a> (const LVDWARFReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96de4e6c3b42c520dea251ae6b319154">getCUBaseAddress</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9717d00700092350b8140dbf35d51a16">setCUBaseAddress</a> (LVAddress Address)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37cdc45da9773b10244ecfe6f208f8a">getCUHighAddress</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4396a18ffb10402dbc7d1b3a3dab3f82">setCUHighAddress</a> (LVAddress Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a86d76ed6f92c1d16716bd39fadc6de5d">LVSymbols</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20bd2faf4c331898263910653d54ae7">GetSymbolsWithLocations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3d7579887f71bf2b4cf7def5a3d77b">getRegisterName</a> (LVSmall Opcode, ArrayRef&lt; uint64_t &gt; Operands) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6085b16b5d9f99d6baafde6585f7ee89">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2654c1aa1162ecd859c2a9e301a33c">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf565023d8f6916f29adcd9ac264400e">createScopes</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920a403e93a285632b45dc6a4e91218c">sortScopes</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa931d02c8c129215334279dc0b43cb2">loadTargetInfo</a> (const object::ObjectFile &amp;Obj)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e30794db3ce743267061b832e054c84">mapRangeAddress</a> (const object::ObjectFile &amp;Obj) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa917880fcf72d87b9989604fc91351">createElement</a> (dwarf::Tag Tag)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a413a68b5168ded503c92eaf49d6fbe75">traverseDieAndChildren</a> (DWARFDie &amp;DIE, LVScope *Parent, DWARFDie &amp;SkeletonDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18649cbb30fab3fe558c8b3f1d06209f">processOneDie</a> (const DWARFDie &amp;InputDIE, LVScope *Parent, DWARFDie &amp;SkeletonDie)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096e290254d040e17fde777a6164a199">processOneAttribute</a> (const DWARFDie &amp;Die, LVOffset *OffsetPtr, const AttributeSpec &amp;AttrSpec)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72316b681ad4c4b2cac8d20903d78e9e">createLineAndFileRecords</a> (const DWARFDebugLine::LineTable *Lines)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fe0e2b5c50efb87d0562d531d9f817">processLocationGaps</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241c84880df8f719f2eaace041d4b14e">addGlobalOffset</a> (LVOffset Offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4367bda0e4c13a7d8b600c5e65b28c92">removeGlobalOffset</a> (LVOffset Offset)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46621bf981f3427563b6c80b2abc2b78">processLocationMember</a> (dwarf::Attribute Attr, const DWARFFormValue &amp;FormValue, const DWARFDie &amp;Die, uint64_t OffsetOnEntry)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7f17efdf50d4310ea927bc6f7c3ab0">processLocationList</a> (dwarf::Attribute Attr, const DWARFFormValue &amp;FormValue, const DWARFDie &amp;Die, uint64_t OffsetOnEntry, bool CallSiteLocation=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a4884ad12ec0cf64f127b2f0c45203">updateReference</a> (dwarf::Attribute Attr, const DWARFFormValue &amp;FormValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f2b304e3c0896cce1bf12e61df0f8c">getElementForOffset</a> (LVOffset offset, LVElement *Element, bool IsType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4354f519e5c954670323fd1078782050">Obj</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612113f087fc6b33ffec3c970db9e201">RangesDataAvailable</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f908d615d19ea5cea872e3fe0d1a9d4">CUBaseAddress</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc2c7eaf0a543fd20e256eda0df314d">CUHighAddress</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6290edf02483be4299a67a769eafe997">CurrentElement</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a01593b44c91ba44a7b64e21e83572">CurrentScope</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol">LVSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac622023d5ef74c038f582f42984c2194">CurrentSymbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf278291961f5516e228e709151ce15c">CurrentType</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac019a0c9cecba4eb4592e88b58c92293">CurrentOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33884c49860ff7cfcdf5a11dcec7a3d">CurrentEndOffset</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dac109845e14a79a964fbaf60a7e7fc">IncrementFileIndex</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a99ddaf1fd8ebfcd4d85a4fee93792b00">LVAddressRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a61300e772a9f29b26ba8616f448785">CurrentRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a86d76ed6f92c1d16716bd39fadc6de5d">LVSymbols</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb53c9f86b435cb740ecf3d7c142106">SymbolsWithLocations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1cce95edff2a5b59810cdf0f3b2567eb">LVOffsetElementMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e6f0ab2810432b2cd3e6374ce59ecf">GlobalOffsets</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3bf8e54e61216b257b1ccf0b51a7056">CurrentLowPC</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4456a11271e3e0df0522126d7f4f556">CurrentHighPC</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e60d1c04a9eeb106e7224e1f5f96428">FoundLowPC</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb391495c23894805fc726515bb233df">FoundHighPC</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LVElementReference</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02290e36e2105de138a640dbf407df3">ElementTable</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LVElementReference {#a05bf1445244febbbfef513fab898f347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVDWARFReader::LVElementReference =  std::unordered_map&lt;LVOffset, LVElementEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### LVElementSet {#ae075f001bcf7871ad2e06adf432ed03c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVDWARFReader::LVElementSet =  std::unordered_set&lt;LVElement *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVDWARFReader() {#a4eeccb0c42d994c7983021e929bc6e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVDWARFReader::LVDWARFReader ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>Referenced by <a href="#a194c5bdcd83c3806641808b42df41b42">LVDWARFReader</a> and <a href="#a61a09d509675eff595e8028e1ec65024">operator=</a>.</p>

</div>
</div>

### LVDWARFReader() {#aa5c941357b1a4565c7001065a68fb538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVDWARFReader::LVDWARFReader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileFormatName, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> &amp; W)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a68bf3a0b21ddaa5e5dd4700790af833cab61b2d6c6fa62903b882aaa53452c111">llvm::logicalview::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a30c36ab397c2a31a605e88a0a476ee9c">llvm::logicalview::LVReader::FileFormatName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefa1351017ac6423911223bc19a8cb7c653">llvm::logicalview::Filename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a77d562b41fb3c6d478f38b73cfa44ab3">llvm::logicalview::LVBinaryReader::LVBinaryReader</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a05c1edcb51769b9ed74087532906b12e">llvm::logicalview::LVReader::W</a>.</p>

</div>
</div>

### LVDWARFReader() {#a194c5bdcd83c3806641808b42df41b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVDWARFReader::LVDWARFReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader">LVDWARFReader</a> &amp;)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>Reference <a href="#a4eeccb0c42d994c7983021e929bc6e96">LVDWARFReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVDWARFReader() {#ae1c90329b38a75958e5845601938dcbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVDWARFReader::~LVDWARFReader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a61a09d509675eff595e8028e1ec65024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVDWARFReader &amp; llvm::logicalview::LVDWARFReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader">LVDWARFReader</a> &amp;)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>Reference <a href="#a4eeccb0c42d994c7983021e929bc6e96">LVDWARFReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#afc2654c1aa1162ecd859c2a9e301a33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVDWARFReader::dump ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a6085b16b5d9f99d6baafde6585f7ee89">print</a>.</p>

</div>
</div>

### getCUBaseAddress() {#a96de4e6c3b42c520dea251ae6b319154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVDWARFReader::getCUBaseAddress ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### getCUHighAddress() {#aa37cdc45da9773b10244ecfe6f208f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVDWARFReader::getCUHighAddress ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### getRegisterName() {#a6e3d7579887f71bf2b4cf7def5a3d77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LVDWARFReader::getRegisterName (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ab9502425858a198bcbe9227a823f8aea">LVSmall</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Operands)</td>
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



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#abcc02a97a7033bc1db45cd841ed4fc4e">llvm::DIDumpOptions::GetNameForDWARFReg</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ab2018d81dede6424ed445ad0c80083d2">llvm::logicalview::LVBinaryReader::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aeb9094ce3f495cf3f81c2c7aa6a975f5">llvm::DWARFExpression::prettyPrintRegisterOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>

</div>
</div>

### GetSymbolsWithLocations() {#af20bd2faf4c331898263910653d54ae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVSymbols &amp; llvm::logicalview::LVDWARFReader::GetSymbolsWithLocations ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### print() {#a6085b16b5d9f99d6baafde6585f7ee89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ae3b66787d42fd33ae1c2fe2c5fd7225c">llvm::logicalview::LVReader::OS</a>.</p>


<p>Referenced by <a href="#afc2654c1aa1162ecd859c2a9e301a33c">dump</a>.</p>

</div>
</div>

### setCUBaseAddress() {#a9717d00700092350b8140dbf35d51a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVDWARFReader::setCUBaseAddress (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Address)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>.</p>

</div>
</div>

### setCUHighAddress() {#a4396a18ffb10402dbc7d1b3a3dab3f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVDWARFReader::setCUHighAddress (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Address)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createScopes() {#abf565023d8f6916f29adcd9ac264400e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVDWARFReader::createScopes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 810 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad95ed9d1449a665ba1c71c5251e34ab7">llvm::logicalview::LVBinaryReader::addSectionRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#a44733b38b12755c4ab176ab0642fc5fd">llvm::logicalview::LVRange::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aabd8bf25dbcb16ca9fa57ef73d062006">llvm::logicalview::LVReader::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ad6f9fa82bb8b6a5dae98b9d9d346d913">llvm::DWARFContext::create</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a53b8fdf818581607c61a5b0bdd3bf5ed">llvm::logicalview::LVReader::createAlternativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#adf2a6238adfb3ada928de5340d5298b6">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#af75cb2856d2563990ed489c38b63a5c3">llvm::logicalview::LVReader::createScopes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a7f70da07f056e7436d80fcddcc760164">llvm::logicalview::LVBinaryReader::CULines</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#ac0c5fbd2279527ccfc0c0ef76c19ddce">llvm::DWARFDebugLine::FileNameEntry::DirIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a30c36ab397c2a31a605e88a0a476ee9c">llvm::logicalview::LVReader::FileFormatName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4030d97efbcfaf77b80c112cd27c4214">llvm::DWARFDie::getDwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a9cfe13a99c14005ccbf4e6b653713f0e">llvm::logicalview::LVReader::getFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a23627e0b6a1a860f08078cffc221b4b6">llvm::logicalview::LVBinaryReader::getSectionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#abb616341561b2b08f925cccf1c7481ee">llvm::logicalview::LVBinaryReader::getSectionRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afd5def6886f14df2575567385872bd04">llvm::DWARFUnit::isDWOUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ae970d60ab52d996448bb030b4a0b67bc">llvm::DWARFDie::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a8f648767e6fee704685f85355aa7fa64">llvm::logicalview::LVBinaryReader::mapVirtualAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa6adf97f83acf6453d4a6a4b1070f3754">llvm::codeview::None</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a873cd38481c3ed6a7e21bc016ec10ae2">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a420b00d155d9b18204d9a7afd76dabb5">llvm::DILineInfoSpecifier::RawValue</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aca8db53bfaede35c8940fceb72b495aa">llvm::logicalview::LVReader::Root</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvrange/#aa3cc825b5d1adfdd7029668cab4ad9a3">llvm::logicalview::LVRange::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a05c1edcb51769b9ed74087532906b12e">llvm::logicalview::LVReader::W</a>.</p>

</div>
</div>

### sortScopes() {#a920a403e93a285632b45dc6a4e91218c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::sortScopes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#aca8db53bfaede35c8940fceb72b495aa">llvm::logicalview::LVReader::Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addGlobalOffset() {#a241c84880df8f719f2eaace041d4b14e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVDWARFReader::addGlobalOffset (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a> Offset)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### createElement() {#aeaa917880fcf72d87b9989604fc91351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVDWARFReader::createElement (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### createLineAndFileRecords() {#a72316b681ad4c4b2cac8d20903d78e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::createLineAndFileRecords (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> * Lines)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### getElementForOffset() {#ac4f2b304e3c0896cce1bf12e61df0f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVDWARFReader::getElementForOffset (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a> offset, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element, bool IsType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### loadTargetInfo() {#aaa931d02c8c129215334279dc0b43cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error LVDWARFReader::loadTargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### mapRangeAddress() {#a6e30794db3ce743267061b832e054c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::mapRangeAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj)</td>
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



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### processLocationGaps() {#a04fe0e2b5c50efb87d0562d531d9f817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::processLocationGaps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### processLocationList() {#a6a7f17efdf50d4310ea927bc6f7c3ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::processLocationList (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FormValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, uint64_t OffsetOnEntry, bool CallSiteLocation=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### processLocationMember() {#a46621bf981f3427563b6c80b2abc2b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::processLocationMember (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FormValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, uint64_t OffsetOnEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### processOneAttribute() {#a096e290254d040e17fde777a6164a199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::processOneAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a> * OffsetPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ac187988134954b96f055f1a2c9be0aee">AttributeSpec</a> &amp; AttrSpec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### processOneDie() {#a18649cbb30fab3fe558c8b3f1d06209f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope * LVDWARFReader::processOneDie (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; InputDIE, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; SkeletonDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### removeGlobalOffset() {#a4367bda0e4c13a7d8b600c5e65b28c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVDWARFReader::removeGlobalOffset (<a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1ca9dca8309d4665c7172a966c3223c3">LVOffset</a> Offset)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### traverseDieAndChildren() {#a413a68b5168ded503c92eaf49d6fbe75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::traverseDieAndChildren (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; DIE, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; SkeletonDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

### updateReference() {#a30a4884ad12ec0cf64f127b2f0c45203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVDWARFReader::updateReference (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; FormValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>, definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CUBaseAddress {#a3f908d615d19ea5cea872e3fe0d1a9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVDWARFReader::CUBaseAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CUHighAddress {#a8fc2c7eaf0a543fd20e256eda0df314d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVDWARFReader::CUHighAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentElement {#a6290edf02483be4299a67a769eafe997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement* llvm::logicalview::LVDWARFReader::CurrentElement = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentEndOffset {#ab33884c49860ff7cfcdf5a11dcec7a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVOffset llvm::logicalview::LVDWARFReader::CurrentEndOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentHighPC {#ae4456a11271e3e0df0522126d7f4f556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVDWARFReader::CurrentHighPC = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentLowPC {#ac3bf8e54e61216b257b1ccf0b51a7056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress llvm::logicalview::LVDWARFReader::CurrentLowPC = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentOffset {#ac019a0c9cecba4eb4592e88b58c92293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVOffset llvm::logicalview::LVDWARFReader::CurrentOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentRanges {#a2a61300e772a9f29b26ba8616f448785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LVAddressRange&gt; llvm::logicalview::LVDWARFReader::CurrentRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentScope {#a12a01593b44c91ba44a7b64e21e83572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScope* llvm::logicalview::LVDWARFReader::CurrentScope = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentSymbol {#ac622023d5ef74c038f582f42984c2194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbol* llvm::logicalview::LVDWARFReader::CurrentSymbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### CurrentType {#acf278291961f5516e228e709151ce15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVType* llvm::logicalview::LVDWARFReader::CurrentType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### ElementTable {#ab02290e36e2105de138a640dbf407df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElementReference llvm::logicalview::LVDWARFReader::ElementTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### FoundHighPC {#afb391495c23894805fc726515bb233df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVDWARFReader::FoundHighPC = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### FoundLowPC {#a4e60d1c04a9eeb106e7224e1f5f96428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVDWARFReader::FoundLowPC = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### GlobalOffsets {#ae4e6f0ab2810432b2cd3e6374ce59ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVOffsetElementMap llvm::logicalview::LVDWARFReader::GlobalOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### IncrementFileIndex {#a0dac109845e14a79a964fbaf60a7e7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVDWARFReader::IncrementFileIndex = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### Obj {#a4354f519e5c954670323fd1078782050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object::ObjectFile&amp; llvm::logicalview::LVDWARFReader::Obj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### RangesDataAvailable {#a612113f087fc6b33ffec3c970db9e201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::logicalview::LVDWARFReader::RangesDataAvailable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

### SymbolsWithLocations {#a4eb53c9f86b435cb740ecf3d7c142106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbols llvm::logicalview::LVDWARFReader::SymbolsWithLocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvdwarfreader-h">LVDWARFReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvdwarfreader-cpp">LVDWARFReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
