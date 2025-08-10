---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stringtablebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StringTableBuilder` Class

<p>Utility for building string tables with deduplicated suffixes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StringTableBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">llvm/MC/StringTableBuilder.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstringtablebuilder">ELFStringTableBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#a58c8b5f09afd8827aed05c9a1804e73a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37419537c597404e7659cc4e2096f39">StringTableBuilder</a> (Kind K, Align Alignment=Align(1))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cafb774782fffec29167921f23e9f6c">~StringTableBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ba484ec18769c20a3c576c02f0b2a7">add</a> (CachedHashStringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a string to the builder. <a href="#ae6ba484ec18769c20a3c576c02f0b2a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1201babaeb013dfde6d83086e2f35224">add</a> (StringRef S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae745bcacfe97669686a4f7c2941d9e0a">finalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the strings and build the final table. <a href="#ae745bcacfe97669686a4f7c2941d9e0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ff7a5198a84bc90537e2f1007af9fd">finalizeInOrder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the string table without reording it. <a href="#a12ff7a5198a84bc90537e2f1007af9fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13bc9289af7e5d306d3951a0ab8f0b11">getOffset</a> (CachedHashStringRef S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offest of a string in the string table. <a href="#a13bc9289af7e5d306d3951a0ab8f0b11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeeab600cd769753b6de8f7e513e6ec0">getOffset</a> (StringRef S) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81311e6775d39743b9b5819b283dbbea">contains</a> (StringRef S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a string is contained in the string table. <a href="#a81311e6775d39743b9b5819b283dbbea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb59783e1d9df70acab52a1f31a4f12a">contains</a> (CachedHashStringRef S) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48cff00887e58910f0074f00165b784">getSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088f3eaf2c7f561d4e021ce000d753c9">clear</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2469d919349b52e2d98dd09fed5d623">write</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c04d3fd68e4c5a63750703a90b54b25">write</a> (uint8_t *Buf) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad377faec4ee6f12fcdfe1547101de791">isFinalized</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fb429fdc25a4ad94214db69e565e52">finalizeStringTable</a> (bool Optimize)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80098f1e4738886dee4e2bc3650fa442">initSize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref">CachedHashStringRef</a>, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110e63f85f366c8d6fffd60f427509a4">StringIndexMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d9661ea2f09c6eda18e83d6fa9d23b">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a58c8b5f09afd8827aed05c9a1804e73a">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98cd17914572c1764ff46de523553df">K</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d4d1e43355d478cda973cbce050407a">Alignment</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7b11f4781b0af6beee0d22ac98f923">Finalized</a> = false</td>
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

<p>Utility for building string tables with deduplicated suffixes.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#a58c8b5f09afd8827aed05c9a1804e73a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::StringTableBuilder::Kind </td>
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
<td class="doxyEnumItemName">ELF<a id="a58c8b5f09afd8827aed05c9a1804e73aadb97a5bc1bb9ee2bc8b2dbb9065755f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WinCOFF<a id="a58c8b5f09afd8827aed05c9a1804e73aa3b433aad0b57e92f9970815c495fad4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachO<a id="a58c8b5f09afd8827aed05c9a1804e73aad9c26952cc8eda5313843bab92a4b47c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachO64<a id="a58c8b5f09afd8827aed05c9a1804e73aad1181b7fcf315dfde97a58d1a158b2e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOLinked<a id="a58c8b5f09afd8827aed05c9a1804e73aa9ab9fedf71c77844b4a749845cd82e06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachO64Linked<a id="a58c8b5f09afd8827aed05c9a1804e73aa24f103126892bfe4a4889575005e5837"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RAW<a id="a58c8b5f09afd8827aed05c9a1804e73aa7276fc7b95014e9041e70e8d0bfcdc3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DWARF<a id="a58c8b5f09afd8827aed05c9a1804e73aafa19fdcc19d034fbc975465426a59188"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XCOFF<a id="a58c8b5f09afd8827aed05c9a1804e73aa4577a254fb772e7f6c92648b602657f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXContainer<a id="a58c8b5f09afd8827aed05c9a1804e73aa195bde7c1cb7c6635198f26a25801ab6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StringTableBuilder() {#af37419537c597404e7659cc4e2096f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder::StringTableBuilder (<a href="#a58c8b5f09afd8827aed05c9a1804e73a">Kind</a> K, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ifs/anonymous-elfobjhandler-cpp-/elfstringtablebuilder/#a57409cff53cfe4000979c1d356c062e2">llvm::ifs::anonymous{ELFObjHandler.cpp}::ELFStringTableBuilder::ELFStringTableBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~StringTableBuilder() {#a6cafb774782fffec29167921f23e9f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder::~StringTableBuilder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ae6ba484ec18769c20a3c576c02f0b2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringTableBuilder::add (<a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref">CachedHashStringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a string to the builder.</p>


<p>Returns the position of S in the table. The position will be changed if finalize is used. Can only be used before the table is finalized.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad377faec4ee6f12fcdfe1547101de791">isFinalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a58c8b5f09afd8827aed05c9a1804e73aa7276fc7b95014e9041e70e8d0bfcdc3d">RAW</a>, <a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref/#a2dafe674df66999f933e57705ea1a037">llvm::CachedHashStringRef::size</a> and <a href="#a58c8b5f09afd8827aed05c9a1804e73aa3b433aad0b57e92f9970815c495fad4d">WinCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp/#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a0fcb5b0c8740137c1ba7ea67bc4e1986">writeTypeIdCompatibleVtableSummaryRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ac5a65c8b873ba60af3d6927d70551cc4">writeTypeIdSummaryRecord</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>.</p>

</div>
</div>

### add() {#a1201babaeb013dfde6d83086e2f35224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringTableBuilder::add (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>


<p>Reference <a href="#a1201babaeb013dfde6d83086e2f35224">add</a>.</p>


<p>Referenced by <a href="#a1201babaeb013dfde6d83086e2f35224">add</a>.</p>

</div>
</div>

### clear() {#a088f3eaf2c7f561d4e021ce000d753c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>

</div>
</div>

### contains() {#a81311e6775d39743b9b5819b283dbbea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringTableBuilder::contains (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a string is contained in the string table.</p>


<p>Since this class doesn't store the string values, this function can be used to check if storage needs to be done prior to adding the string.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>


<p>Reference <a href="#a81311e6775d39743b9b5819b283dbbea">contains</a>.</p>


<p>Referenced by <a href="#a81311e6775d39743b9b5819b283dbbea">contains</a>.</p>

</div>
</div>

### contains() {#abb59783e1d9df70acab52a1f31a4f12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringTableBuilder::contains (<a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref">CachedHashStringRef</a> S)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

### finalize() {#ae745bcacfe97669686a4f7c2941d9e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::finalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the strings and build the final table.</p>


<p>No more strings can be added after this point.</p>


<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a58c8b5f09afd8827aed05c9a1804e73aafa19fdcc19d034fbc975465426a59188">DWARF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

### finalizeInOrder() {#a12ff7a5198a84bc90537e2f1007af9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::finalizeInOrder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the string table without reording it.</p>


<p>In this mode, offsets returned by add will still be valid.</p>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>.</p>

</div>
</div>

### getOffset() {#a13bc9289af7e5d306d3951a0ab8f0b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t StringTableBuilder::getOffset (<a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref">CachedHashStringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the offest of a string in the string table.</p>


<p>Can only be used after the table is finalized.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ad377faec4ee6f12fcdfe1547101de791">isFinalized</a>.</p>


<p>Referenced by <a href="#abeeab600cd769753b6de8f7e513e6ec0">getOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>.</p>

</div>
</div>

### getOffset() {#abeeab600cd769753b6de8f7e513e6ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringTableBuilder::getOffset (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>


<p>Reference <a href="#a13bc9289af7e5d306d3951a0ab8f0b11">getOffset</a>.</p>

</div>
</div>

### getSize() {#af48cff00887e58910f0074f00165b784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringTableBuilder::getSize ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriter/#ae2b4d52449259cb44c2e6a0b558ec9ee">llvm::objcopy::elf::IHexSectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriterbase/#a4eacf10ebf949f25c6f0e1f1a0df6954">llvm::objcopy::elf::IHexSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriter/#a2c0bdb8c0a5dc11c8f200df17eb17df3">llvm::objcopy::elf::SRECSectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriterbase/#a725e0954ae2fcf7988f1baa0ef982313">llvm::objcopy::elf::SRECSectionWriterBase::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a> and <a href="#ae2469d919349b52e2d98dd09fed5d623">write</a>.</p>

</div>
</div>

### isFinalized() {#ad377faec4ee6f12fcdfe1547101de791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringTableBuilder::isFinalized ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>


<p>Referenced by <a href="#ae6ba484ec18769c20a3c576c02f0b2a7">add</a>, <a href="#a13bc9289af7e5d306d3951a0ab8f0b11">getOffset</a>, <a href="#ae2469d919349b52e2d98dd09fed5d623">write</a> and <a href="#a4c04d3fd68e4c5a63750703a90b54b25">write</a>.</p>

</div>
</div>

### write() {#ae2469d919349b52e2d98dd09fed5d623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#af48cff00887e58910f0074f00165b784">getSize</a>, <a href="#ad377faec4ee6f12fcdfe1547101de791">isFinalized</a> and <a href="#ae2469d919349b52e2d98dd09fed5d623">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#acfa5e41a619b2f37966fdc043ca96c09">upgrade</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriter/#ae2b4d52449259cb44c2e6a0b558ec9ee">llvm::objcopy::elf::IHexSectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionwriter/#a76b5551d20e099e66e929c74f32469fe">llvm::objcopy::elf::SectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/srecsectionwriter/#a2c0bdb8c0a5dc11c8f200df17eb17df3">llvm::objcopy::elf::SRECSectionWriter::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a> and <a href="#ae2469d919349b52e2d98dd09fed5d623">write</a>.</p>

</div>
</div>

### write() {#a4c04d3fd68e4c5a63750703a90b54b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::write (uint8_t * Buf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#ad377faec4ee6f12fcdfe1547101de791">isFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a58c8b5f09afd8827aed05c9a1804e73aa3b433aad0b57e92f9970815c495fad4d">WinCOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a71eb44a745361d5437d4a53f9f30dd3d">llvm::support::endian::write32be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a> and <a href="#a58c8b5f09afd8827aed05c9a1804e73aa4577a254fb772e7f6c92648b602657f1">XCOFF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### finalizeStringTable() {#aa9fb429fdc25a4ad94214db69e565e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::finalizeStringTable (bool Optimize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>

</div>
</div>

### initSize() {#a80098f1e4738886dee4e2bc3650fa442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StringTableBuilder::initSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alignment {#a4d4d1e43355d478cda973cbce050407a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::StringTableBuilder::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

### Finalized {#a2b7b11f4781b0af6beee0d22ac98f923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StringTableBuilder::Finalized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

### K {#af98cd17914572c1764ff46de523553df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::StringTableBuilder::K</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

### Size {#a56d9661ea2f09c6eda18e83d6fa9d23b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::StringTableBuilder::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

### StringIndexMap {#a110e63f85f366c8d6fffd60f427509a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;CachedHashStringRef, size_t&gt; llvm::StringTableBuilder::StringIndexMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">StringTableBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/stringtablebuilder-cpp">StringTableBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
