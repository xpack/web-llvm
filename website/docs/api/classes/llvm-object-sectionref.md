---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/sectionref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SectionRef` Class

<p>This is a value type class that represents a single section in the list of sections in the object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::SectionRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref">ELFSectionRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac698cd44041380ea3da5dba04d7ac97f">SectionRef</a> (DataRefImpl SectionP, const ObjectFile *Owner)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a>. <a href="#ac698cd44041380ea3da5dba04d7ac97f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932e8d9b1256f3a090b93062615816ee">operator==</a> (const SectionRef &amp;Other) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4045791b00c5531863c82de7f3a68a35">operator!=</a> (const SectionRef &amp;Other) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198a7909aa98bbe4499702e504bc4c06">operator&lt;</a> (const SectionRef &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06c6a96a14a2e694b34b6156f0f00f98">moveNext</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a4b091742ad2565d54543f6179ae13">getName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a664da9a987e7bb5023e33705509df4">getAddress</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1683493667fa7e44083fe1258a1dcb10">getIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ef2bc8c86e345544b07f87c2ceb951">getSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6342a1426bb80b6b762d4ec5e58f1ce4">getContents</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0fb4ba2708c0e5ef78df12760f6645">getAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alignment of this section. <a href="#ada0fb4ba2708c0e5ef78df12760f6645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7b4ba2945063411c487aac073f9459">isCompressed</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab78cb663ac0805b3be2756a9148e1d76">isText</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section contains instructions. <a href="#ab78cb663ac0805b3be2756a9148e1d76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf5dc4878ff8425b046dc9b4d5ce95c">isData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section contains data, not instructions. <a href="#a5bf5dc4878ff8425b046dc9b4d5ce95c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b626cd5412e6c9739be877e575bbc7">isBSS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section contains BSS uninitialized data. <a href="#a85b626cd5412e6c9739be877e575bbc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5e50ed72d772afaf0850c84fa3cf6e">isVirtual</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a7e5d2536571b2342788eb262e7a5f">isBitcode</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e27d763922e9d5ac17c3423fdece32">isStripped</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9acc251112b12a0f3523aba93a27ca04">isBerkeleyText</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section will be placed in the text segment, according to the Berkeley size format. <a href="#a9acc251112b12a0f3523aba93a27ca04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11a73c8ca0835a464fae89951a172c6">isBerkeleyData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section will be placed in the data segment, according to the Berkeley size format. <a href="#ae11a73c8ca0835a464fae89951a172c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57539e8934c3c44b150bf8670697c783">isDebugSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section is a debug section. <a href="#a57539e8934c3c44b150bf8670697c783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9252daa21a3dd50c0c31a70c482a94a0">containsSymbol</a> (SymbolRef S) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad695796e392abbb8c4865a4fbb5eca08">relocation_begin</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6656235915ff38c21cfc15051ccded59">relocation_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">relocation_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5930a5019c6caa6b7252f187524318b0">relocations</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afefc9a6c50666179dc43c56745fd0785">getRelocatedSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the related section if this section contains relocations. <a href="#afefc9a6c50666179dc43c56745fd0785">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7697438cbf778f7d1b051e97204606">getRawDataRefImpl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af325f1df60eef3a8a8a47e22a1f43c5e">getObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e53187239d5a90013d822feadb546b">SectionPimpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15d267e5c3a6c5e57dbcdda89b6e3db">OwningObject</a> = nullptr</td>
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

<p>This is a value type class that represents a single section in the list of sections in the object file.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SymbolRef {#a23fe52bbc164a30ba18e057d37bd2283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a>.</p>


<p>Referenced by <a href="#a9252daa21a3dd50c0c31a70c482a94a0">containsSymbol</a>, <a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a> and <a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SectionRef() {#a92bedaaa222dbfcf63f2219d872291d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::SectionRef::SectionRef ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a> and <a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#ab4adc966e00d57fb68b91ea203d8c119">llvm::object::ELFSectionRef::ELFSectionRef</a>, <a href="#a4045791b00c5531863c82de7f3a68a35">operator!=</a>, <a href="#a198a7909aa98bbe4499702e504bc4c06">operator&lt;</a>, <a href="#a932e8d9b1256f3a090b93062615816ee">operator==</a> and <a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a>.</p>

</div>
</div>

### SectionRef() {#ac698cd44041380ea3da5dba04d7ac97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::SectionRef::SectionRef (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> SectionP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * Owner)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a>.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a4045791b00c5531863c82de7f3a68a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Other)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a>.</p>

</div>
</div>

### operator&lt;() {#a198a7909aa98bbe4499702e504bc4c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Other)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a>.</p>

</div>
</div>

### operator==() {#a932e8d9b1256f3a090b93062615816ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a> &amp; Other)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a92bedaaa222dbfcf63f2219d872291d3">SectionRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### containsSymbol() {#a9252daa21a3dd50c0c31a70c482a94a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SectionRef::containsSymbol (<a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#af8b31890b3cf3677a9c279325661e3af">llvm::object::SymbolRef::getSection</a>, <a href="#a23fe52bbc164a30ba18e057d37bd2283">SymbolRef</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getAddress() {#a9a664da9a987e7bb5023e33705509df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::SectionRef::getAddress ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a603eb2d37a31ea2c14318bedeecb8e3c">llvm::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab8281e64fb0c8b5bc71fdb5876df6c9d">llvm::RuntimeDyldMachO::makeValueAddendPCRel</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### getAlignment() {#ada0fb4ba2708c0e5ef78df12760f6645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::object::SectionRef::getAlignment ()</td>
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

<p>Get the alignment of this section.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>

</div>
</div>

### getContents() {#a6342a1426bb80b6b762d4ec5e58f1ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::SectionRef::getContents ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/btfparser/parsecontext/#a657868ac1ec31f283f359d005dcdf905">llvm::BTFParser::ParseContext::makeExtractor</a>.</p>

</div>
</div>

### getIndex() {#a1683493667fa7e44083fe1258a1dcb10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::SectionRef::getIndex ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a1408ab8cac30c08491c126a28e803a04">llvm::jitlink::COFFLinkGraphBuilder::forEachRelocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/symbolsize-cpp/#a51cdd69cc3c09d50beee2d36727c2e42">getSectionID</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a> and <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getName() {#af9a4b091742ad2565d54543f6179ae13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::SectionRef::getName ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/dwarfobjinmemory/#aa19f707b77c01709bba51c751b77f288">anonymous{DWARFContext.cpp}::DWARFObjInMemory::DWARFObjInMemory</a> and <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a>.</p>

</div>
</div>

### getObject() {#af325f1df60eef3a8a8a47e22a1f43c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ObjectFile * llvm::object::SectionRef::getObject ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#ab4adc966e00d57fb68b91ea203d8c119">llvm::object::ELFSectionRef::ELFSectionRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#ae71e8902775f8de0490455dc8c929d2f">llvm::RuntimeDyldCOFFThumb::getJITSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#a781194b172ea38248b42801f65e3f071">llvm::object::ELFSectionRef::getObject</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a358c1febb02bfec774608e4761b27495">handleCompressedSection</a>.</p>

</div>
</div>

### getRawDataRefImpl() {#a1f7697438cbf778f7d1b051e97204606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::SectionRef::getRawDataRefImpl ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#a93cfe4f193a8a7d9cb445841cde670db">llvm::object::ELFObjectFileBase::getCrelDecodeProblem</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#a65cfa3f4710cddbc95dc790ffe80a658">llvm::object::ELFSectionRef::getFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-b2573e63a6159981bb12a624c22a604a/#a0a98f99bc4b56c9f1352d966180243a8">llvm::DenseMapInfo&lt; object::SectionRef &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#a89effab364d0a163ab419a879c6bbe9e">llvm::object::ELFSectionRef::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a76ab692cb3d70a67aafcb0ab4c22041e">llvm::object::COFFObjectFile::getSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ae48752dc6271082d4f4cb2c9db80703d">llvm::object::MachOObjectFile::getSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a6219972bdae3e9ac0f4daf447f328d82">llvm::object::MachOObjectFile::getSectionType</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsectionref/#ab50a33a2b9a8bb4f0308ac8ae8e614d3">llvm::object::ELFSectionRef::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a> and <a href="/web-llvm/docs/api/classes/anonymous-runtimedyldelf-cpp-/dyldelfobject/#aaf9af47b48d2f4d53961dbba93fda6b6">anonymous{RuntimeDyldELF.cpp}::DyldELFObject&lt; ELFT &gt;::updateSectionAddress</a>.</p>

</div>
</div>

### getRelocatedSection() {#afefc9a6c50666179dc43c56745fd0785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; llvm::object::SectionRef::getRelocatedSection ()</td>
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

<p>Returns the related section if this section contains relocations.</p>


<p>The returned section may or may not have applied its relocations.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### getSize() {#a88ef2bc8c86e345544b07f87c2ceb951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::SectionRef::getSize ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a>.</p>

</div>
</div>

### isBerkeleyData() {#ae11a73c8ca0835a464fae89951a172c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isBerkeleyData ()</td>
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

<p>Whether this section will be placed in the data segment, according to the Berkeley size format.</p>


<p>This is true if the section is allocatable and contains data (e.g. PROGBITS), but is not text.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isBerkeleyText() {#a9acc251112b12a0f3523aba93a27ca04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isBerkeleyText ()</td>
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

<p>Whether this section will be placed in the text segment, according to the Berkeley size format.</p>


<p>This is true if the section is allocatable, and contains either code or readonly data.</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isBitcode() {#af3a7e5d2536571b2342788eb262e7a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isBitcode ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isBSS() {#a85b626cd5412e6c9739be877e575bbc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isBSS ()</td>
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

<p>Whether this section contains BSS uninitialized data.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abfea148e3e5693c88962ce5add39bf56">llvm::object::MachOObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isCompressed() {#a6a7b4ba2945063411c487aac073f9459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isCompressed ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isData() {#a5bf5dc4878ff8425b046dc9b4d5ce95c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isData ()</td>
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

<p>Whether this section contains data, not instructions.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#abfea148e3e5693c88962ce5add39bf56">llvm::object::MachOObjectFile::getSymbolType</a>.</p>

</div>
</div>

### isDebugSection() {#a57539e8934c3c44b150bf8670697c783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isDebugSection ()</td>
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

<p>Whether this section is a debug section.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#abd84145c9ebe80a3a256dea1ee944946">llvm::object::ObjectFile::hasDebugInfo</a>.</p>

</div>
</div>

### isStripped() {#a84e27d763922e9d5ac17c3423fdece32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isStripped ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### isText() {#ab78cb663ac0805b3be2756a9148e1d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isText ()</td>
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

<p>Whether this section contains instructions.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo/#a1b2e1cb1c6d2d1f8a038916a90f993a9">anonymous{IntelJITEventListener.cpp}::IntelIttnotifyInfo::fillSectionInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ac01d9cc5d2d4a3b6662c7096e54bf8ad">llvm::RuntimeDyldMachO::getRelocationValueRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afe85af578989c7f3e9627866e7fa4962">llvm::RuntimeDyldImpl::loadObjectImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffx86-64/#afcf3722d9ca669767870af1a84877924">llvm::RuntimeDyldCOFFX86_64::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldelf/#ad9cec5473cec6044442bceccc2fcee96">llvm::RuntimeDyldELF::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#acb7257d8eec274d18e7916a0d552a2d7">llvm::RuntimeDyldMachO::processScatteredVANILLA</a>.</p>

</div>
</div>

### isVirtual() {#a9c5e50ed72d772afaf0850c84fa3cf6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::SectionRef::isVirtual ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### moveNext() {#a06c6a96a14a2e694b34b6156f0f00f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::SectionRef::moveNext ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### relocation\_begin() {#ad695796e392abbb8c4865a4fbb5eca08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator llvm::object::SectionRef::relocation_begin ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#a5930a5019c6caa6b7252f187524318b0">relocations</a>.</p>

</div>
</div>

### relocation\_end() {#a6656235915ff38c21cfc15051ccded59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">relocation_iterator llvm::object::SectionRef::relocation_end ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="#a5930a5019c6caa6b7252f187524318b0">relocations</a>.</p>

</div>
</div>

### relocations() {#a5930a5019c6caa6b7252f187524318b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; relocation_iterator &gt; llvm::object::SectionRef::relocations ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ad695796e392abbb8c4865a4fbb5eca08">relocation_begin</a> and <a href="#a6656235915ff38c21cfc15051ccded59">relocation_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/cofflinkgraphbuilder/#a1408ab8cac30c08491c126a28e803a04">llvm::jitlink::COFFLinkGraphBuilder::forEachRelocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OwningObject {#af15d267e5c3a6c5e57dbcdda89b6e3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ObjectFile* llvm::object::SectionRef::OwningObject = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

### SectionPimpl {#a58e53187239d5a90013d822feadb546b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataRefImpl llvm::object::SectionRef::SectionPimpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/objectfile-cpp">ObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
