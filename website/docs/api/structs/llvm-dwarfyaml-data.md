---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfyaml/data
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Data` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFYAML::Data { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">llvm/ObjectYAML/DWARFYAML.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fe4e18f5a2278fdd0c3e9ba559947e">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/abbrevtableinfo">AbbrevTableInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ac21f4a38a14d4151a066ffc40005a">getAbbrevTableInfoByID</a> (uint64_t ID) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63440c1553c8b023f90126cc142e8724">getAbbrevTableContentByIndex</a> (uint64_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab127296bde91cefd87a394e58ab024f5">IsLittleEndian</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0acf5e51f9671f09657a10263eb5c6">Is64BitAddrSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/abbrevtable">AbbrevTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e38be107ad1f885b0ed61bc831d263">DebugAbbrev</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8df295a5a4dacf81ee28b321362899a">DebugStrings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/stringoffsetstable">StringOffsetsTable</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0abb4e9e112ffb6c92c7b0e3db7972e">DebugStrOffsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/arange">ARange</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b37ed1fe291f3d831af2db367c043ee">DebugAranges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/ranges">Ranges</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1745fd1a346312981f82f0294c02a711">DebugRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/addrtableentry">AddrTableEntry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7165f3746a536073c7a0f89496c887">DebugAddr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection">PubSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c5a21cd2603ebf7df4a6a3679b0b57">PubNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection">PubSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade37b161ce67428fd763763ec0b9cc46">PubTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection">PubSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53baa09681087ec466fed43e3da19c12">GNUPubNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection">PubSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720771e59be66482fdc2efc2ef1e0a8a">GNUPubTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/unit">Unit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a76c1f40d0f513f7857ac5bf4156117">Units</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/linetable">LineTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b4be343876460e80fcdb613214de9ec">DebugLines</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/listtable">ListTable</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/rnglistentry">RnglistEntry</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c4902f00e77bcce833b59ff7337e7a">DebugRnglists</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/listtable">ListTable</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/loclistentry">LoclistEntry</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26422808f838c118cce38277f6e6ce52">DebugLoclists</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnamessection">DebugNamesSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade09d4e1e1ded42dd16575861c0a0fa5">DebugNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; uint64_t, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/abbrevtableinfo">AbbrevTableInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7aa2dc769a97703a0bd746f7c249f2">AbbrevTableInfoMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; uint64_t, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03946bc8fe9a73a89dc05e57bf7e157c">AbbrevTableContents</a></td>
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


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getAbbrevTableContentByIndex() {#a63440c1553c8b023f90126cc142e8724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef DWARFYAML::Data::getAbbrevTableContentByIndex (uint64_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a36e38be107ad1f885b0ed61bc831d263">DebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a81600054c53c8bfe10547514c330a547">llvm::DWARFYAML::emitDebugAbbrev</a> and <a href="#a52ac21f4a38a14d4151a066ffc40005a">getAbbrevTableInfoByID</a>.</p>

</div>
</div>

### getAbbrevTableInfoByID() {#a52ac21f4a38a14d4151a066ffc40005a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFYAML::Data::AbbrevTableInfo &gt; llvm::DWARFYAML::Data::getAbbrevTableInfoByID (uint64_t ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfyaml-cpp">DWARFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a36e38be107ad1f885b0ed61bc831d263">DebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="#a63440c1553c8b023f90126cc142e8724">getAbbrevTableContentByIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/abbrevtable/#ac9f933bf79290747c9014acf2b36a1d8">llvm::DWARFYAML::AbbrevTable::ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>.</p>

</div>
</div>

### getNonEmptySectionNames() {#a887ba011291edccdab6965f72b24578e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt; StringRef &gt; llvm::DWARFYAML::Data::getNonEmptySectionNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfyaml-cpp">DWARFYAML.cpp</a>.</p>


<p>References <a href="#a36e38be107ad1f885b0ed61bc831d263">DebugAbbrev</a>, <a href="#a0d7165f3746a536073c7a0f89496c887">DebugAddr</a>, <a href="#a5b37ed1fe291f3d831af2db367c043ee">DebugAranges</a>, <a href="#a0b4be343876460e80fcdb613214de9ec">DebugLines</a>, <a href="#a26422808f838c118cce38277f6e6ce52">DebugLoclists</a>, <a href="#ade09d4e1e1ded42dd16575861c0a0fa5">DebugNames</a>, <a href="#a1745fd1a346312981f82f0294c02a711">DebugRanges</a>, <a href="#ac9c4902f00e77bcce833b59ff7337e7a">DebugRnglists</a>, <a href="#ab8df295a5a4dacf81ee28b321362899a">DebugStrings</a>, <a href="#aa0abb4e9e112ffb6c92c7b0e3db7972e">DebugStrOffsets</a>, <a href="#a53baa09681087ec466fed43e3da19c12">GNUPubNames</a>, <a href="#a720771e59be66482fdc2efc2ef1e0a8a">GNUPubTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="#ad0c5a21cd2603ebf7df4a6a3679b0b57">PubNames</a>, <a href="#ade37b161ce67428fd763763ec0b9cc46">PubTypes</a> and <a href="#a0a76c1f40d0f513f7857ac5bf4156117">Units</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a>, <a href="#af1fe4e18f5a2278fdd0c3e9ba559947e">isEmpty</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp/#ab26e08b9fdcb1680fe057c2fac9d09c1">shouldEmitDWARF</a>.</p>

</div>
</div>

### isEmpty() {#af1fe4e18f5a2278fdd0c3e9ba559947e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFYAML::Data::isEmpty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfyaml-cpp">DWARFYAML.cpp</a>.</p>


<p>Reference <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DebugAbbrev {#a36e38be107ad1f885b0ed61bc831d263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AbbrevTable&gt; llvm::DWARFYAML::Data::DebugAbbrev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a81600054c53c8bfe10547514c330a547">llvm::DWARFYAML::emitDebugAbbrev</a>, <a href="#a63440c1553c8b023f90126cc142e8724">getAbbrevTableContentByIndex</a>, <a href="#a52ac21f4a38a14d4151a066ffc40005a">getAbbrevTableInfoByID</a>, <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>.</p>

</div>
</div>

### DebugAddr {#a0d7165f3746a536073c7a0f89496c887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;AddrTableEntry&gt; &gt; llvm::DWARFYAML::Data::DebugAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugAranges {#a5b37ed1fe291f3d831af2db367c043ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;ARange&gt; &gt; llvm::DWARFYAML::Data::DebugAranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugLines {#a0b4be343876460e80fcdb613214de9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LineTable&gt; llvm::DWARFYAML::Data::DebugLines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugLoclists {#a26422808f838c118cce38277f6e6ce52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;ListTable&lt;LoclistEntry&gt; &gt; &gt; llvm::DWARFYAML::Data::DebugLoclists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a98a827d6dc5e0b9852b362a6303a4c04">llvm::DWARFYAML::emitDebugLoclists</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugNames {#ade09d4e1e1ded42dd16575861c0a0fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;DebugNamesSection&gt; llvm::DWARFYAML::Data::DebugNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad1f7f7a8ed653ac5d4c9cf22992767ea">llvm::DWARFYAML::emitDebugNames</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugRanges {#a1745fd1a346312981f82f0294c02a711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;Ranges&gt; &gt; llvm::DWARFYAML::Data::DebugRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugRnglists {#ac9c4902f00e77bcce833b59ff7337e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;ListTable&lt;RnglistEntry&gt; &gt; &gt; llvm::DWARFYAML::Data::DebugRnglists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a8427f4b409530028e8e344a02aef72a1">llvm::DWARFYAML::emitDebugRnglists</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugStrings {#ab8df295a5a4dacf81ee28b321362899a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;StringRef&gt; &gt; llvm::DWARFYAML::Data::DebugStrings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aac6c1a9a865304388a58f18a55a4a8f7">llvm::DWARFYAML::emitDebugStr</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### DebugStrOffsets {#aa0abb4e9e112ffb6c92c7b0e3db7972e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;StringOffsetsTable&gt; &gt; llvm::DWARFYAML::Data::DebugStrOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### GNUPubNames {#a53baa09681087ec466fed43e3da19c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PubSection&gt; llvm::DWARFYAML::Data::GNUPubNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a6fb5811ad2c492fe44774e9aeac6a6e4">llvm::DWARFYAML::emitDebugGNUPubnames</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### GNUPubTypes {#a720771e59be66482fdc2efc2ef1e0a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PubSection&gt; llvm::DWARFYAML::Data::GNUPubTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aa2deb4bf15d78c73e0e1f4f341379c74">llvm::DWARFYAML::emitDebugGNUPubtypes</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### Is64BitAddrSize {#abf0acf5e51f9671f09657a10263eb5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFYAML::Data::Is64BitAddrSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a98a827d6dc5e0b9852b362a6303a4c04">llvm::DWARFYAML::emitDebugLoclists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a8427f4b409530028e8e344a02aef72a1">llvm::DWARFYAML::emitDebugRnglists</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a>.</p>

</div>
</div>

### IsLittleEndian {#ab127296bde91cefd87a394e58ab024f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFYAML::Data::IsLittleEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a6fb5811ad2c492fe44774e9aeac6a6e4">llvm::DWARFYAML::emitDebugGNUPubnames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aa2deb4bf15d78c73e0e1f4f341379c74">llvm::DWARFYAML::emitDebugGNUPubtypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a98a827d6dc5e0b9852b362a6303a4c04">llvm::DWARFYAML::emitDebugLoclists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad1f7f7a8ed653ac5d4c9cf22992767ea">llvm::DWARFYAML::emitDebugNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aac8bbdfe4333871ee70d90676f5a304f">llvm::DWARFYAML::emitDebugPubnames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad5b39b3c318d6af879ffdc19bbcfe09e">llvm::DWARFYAML::emitDebugPubtypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a8427f4b409530028e8e344a02aef72a1">llvm::DWARFYAML::emitDebugRnglists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>.</p>

</div>
</div>

### PubNames {#ad0c5a21cd2603ebf7df4a6a3679b0b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PubSection&gt; llvm::DWARFYAML::Data::PubNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aac8bbdfe4333871ee70d90676f5a304f">llvm::DWARFYAML::emitDebugPubnames</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### PubTypes {#ade37b161ce67428fd763763ec0b9cc46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PubSection&gt; llvm::DWARFYAML::Data::PubTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad5b39b3c318d6af879ffdc19bbcfe09e">llvm::DWARFYAML::emitDebugPubtypes</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

### Units {#a0a76c1f40d0f513f7857ac5bf4156117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Unit&gt; llvm::DWARFYAML::Data::Units</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a> and <a href="#a887ba011291edccdab6965f72b24578e">getNonEmptySectionNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbbrevTableContents {#a03946bc8fe9a73a89dc05e57bf7e157c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;uint64_t, std::string&gt; llvm::DWARFYAML::Data::AbbrevTableContents</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>

</div>
</div>

### AbbrevTableInfoMap {#a5c7aa2dc769a97703a0bd746f7c249f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;uint64_t, AbbrevTableInfo&gt; llvm::DWARFYAML::Data::AbbrevTableInfoMap</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">DWARFYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfyaml-cpp">DWARFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
