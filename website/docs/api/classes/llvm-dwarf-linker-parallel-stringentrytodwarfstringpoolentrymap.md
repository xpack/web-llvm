---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/stringentrytodwarfstringpoolentrymap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StringEntryToDwarfStringPoolEntryMap` Class Reference

<p>This class creates a <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> for the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">DWARFLinker/Parallel/StringEntryToDwarfStringPoolEntryMap.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e20963c6a7a8f2a01a83f7e884e7956">DwarfStringPoolEntriesTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ea039dc101f11aeb6e526103ba60d4">StringEntryToDwarfStringPoolEntryMap</a> (LinkingGlobalData &amp;GlobalData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d6976902936376f330ad73b9cbeb09">~StringEntryToDwarfStringPoolEntryMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80767cd1b949a276d944c352d451e98">add</a> (const StringEntry *String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> for specified <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> if necessary. <a href="#ad80767cd1b949a276d944c352d451e98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eae8f19c57158a5be2206d9852037e1">getExistingEntry</a> (const StringEntry *String) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns already existed <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> for the specified <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a>. <a href="#a9eae8f19c57158a5be2206d9852037e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e3d39ed97f8993b0a5ce214b19fb2e">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase contents of StringsForEmission. <a href="#a73e3d39ed97f8993b0a5ce214b19fb2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0e20963c6a7a8f2a01a83f7e884e7956">DwarfStringPoolEntriesTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f6296b02d899f3d572cbc972c848d9">DwarfStringPoolEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cc531a36c3440023472a58fde477ae">GlobalData</a></td>
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

## Description {#details}

<p>This class creates a <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> for the corresponding <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a>.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### DwarfStringPoolEntriesTy {#a0e20963c6a7a8f2a01a83f7e884e7956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::DwarfStringPoolEntriesTy = 
      DenseMap&lt;const StringEntry *, DwarfStringPoolEntryWithExtString *&gt;</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StringEntryToDwarfStringPoolEntryMap() {#ae2ea039dc101f11aeb6e526103ba60d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::StringEntryToDwarfStringPoolEntryMap (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<p>Reference <a href="#a12cc531a36c3440023472a58fde477ae">GlobalData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~StringEntryToDwarfStringPoolEntryMap() {#a14d6976902936376f330ad73b9cbeb09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::~StringEntryToDwarfStringPoolEntryMap ()</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ad80767cd1b949a276d944c352d451e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfStringPoolEntryWithExtString * llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * String)</td>
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

<p>Create <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> for specified <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> if necessary.</p>


<p>Initialize <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> with initial values.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af4f6296b02d899f3d572cbc972c848d9">DwarfStringPoolEntries</a>, <a href="#a12cc531a36c3440023472a58fde477ae">GlobalData</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#a5ec8790ec7c63fb9e58de82b2774fac9">llvm::DwarfStringPoolEntry::Index</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#a7a1b7fb50f627423becd2123526ff26b">llvm::DwarfStringPoolEntry::NotIndexed</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#aa406c884c8fb2d9b2fee2aa3865d832d">llvm::DwarfStringPoolEntry::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring/#ad9753ce2d5673ac4b4acd65ed68daa88">llvm::DwarfStringPoolEntryWithExtString::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#acefe965e3ed0ea37d9578f82dc01cb7a">llvm::DwarfStringPoolEntry::Symbol</a>.</p>

</div>
</div>

### clear() {#a73e3d39ed97f8993b0a5ce214b19fb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::clear ()</td>
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

<p>Erase contents of StringsForEmission.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<p>Reference <a href="#af4f6296b02d899f3d572cbc972c848d9">DwarfStringPoolEntries</a>.</p>

</div>
</div>

### getExistingEntry() {#a9eae8f19c57158a5be2206d9852037e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfStringPoolEntryWithExtString * llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::getExistingEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * String)</td>
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

<p>Returns already existed <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> for the specified <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a>.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af4f6296b02d899f3d572cbc972c848d9">DwarfStringPoolEntries</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a09b5d1027676907c7bc194a865ffe0df">llvm::dwarf_linker::parallel::OutputSections::applyPatches</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DwarfStringPoolEntries {#af4f6296b02d899f3d572cbc972c848d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfStringPoolEntriesTy llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::DwarfStringPoolEntries</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<p>Referenced by <a href="#ad80767cd1b949a276d944c352d451e98">add</a>, <a href="#a73e3d39ed97f8993b0a5ce214b19fb2e">clear</a> and <a href="#a9eae8f19c57158a5be2206d9852037e1">getExistingEntry</a>.</p>

</div>
</div>

### GlobalData {#a12cc531a36c3440023472a58fde477ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingGlobalData&amp; llvm::dwarf_linker::parallel::StringEntryToDwarfStringPoolEntryMap::GlobalData</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a>.</p>


<p>Referenced by <a href="#ad80767cd1b949a276d944c352d451e98">add</a> and <a href="#ae2ea039dc101f11aeb6e526103ba60d4">StringEntryToDwarfStringPoolEntryMap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/stringentrytodwarfstringpoolentrymap-h">StringEntryToDwarfStringPoolEntryMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
