---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/anonymous-lvcodeviewvisitor-cpp-/lvtyperecords
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LVTypeRecords` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2416429f5fdce13dbb48524f137a8787">RecordEntry</a> = std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6651321ab4d518b1eb179d22217588fc">RecordTable</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a>, RecordEntry &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a6fee2eb43b197b19ca009c0b2417c">NameTable</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa08605980fbb85408144311dcc39ea">LVTypeRecords</a> (LVShared *Shared)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf84d2b16e9b39cca528666c9b93a5e8">add</a> (uint32_t StreamIdx, TypeIndex TI, TypeLeafKind Kind, LVElement *Element=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9582cf72cacf16d0c72cdc7da4ceb83">add</a> (uint32_t StreamIdx, TypeIndex TI, StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeee49c1b4a888ec7c1f61325804b21c">find</a> (uint32_t StreamIdx, TypeIndex TI, bool Create=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f05cd10d036b2106900b9ff8fe1124">find</a> (uint32_t StreamIdx, StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/logicalview/lvshared">LVShared</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984b3d72de4ad3a3e7c16b5ce2357c1f">Shared</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RecordTable</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b4b30583e9fe406b65ee405a83d2eb">RecordFromTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">RecordTable</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd0061a87628f8aa1f9dd40f830f0a9">RecordFromIds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">NameTable</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511491ae9d1e4bf8b057df079de50762">NameFromTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">NameTable</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a7d61eaaf2fcfc1e1971f4613e3a76">NameFromIds</a></td>
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


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### NameTable {#a46a6fee2eb43b197b19ca009c0b2417c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::NameTable =  std::map&lt;StringRef, TypeIndex&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### RecordEntry {#a2416429f5fdce13dbb48524f137a8787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::RecordEntry =  std::pair&lt;TypeLeafKind, LVElement *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### RecordTable {#a6651321ab4d518b1eb179d22217588fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::RecordTable =  std::map&lt;TypeIndex, RecordEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVTypeRecords() {#a6aa08605980fbb85408144311dcc39ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::LVTypeRecords (<a href="/web-llvm/docs/api/structs/llvm/logicalview/lvshared">LVShared</a> * Shared)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#adf84d2b16e9b39cca528666c9b93a5e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVTypeRecords::add (uint32_t StreamIdx, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#adf84d2b16e9b39cca528666c9b93a5e8">add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ead626102cfc2416a570fc0dc582a9b771">llvm::logicalview::Kind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>


<p>Referenced by <a href="#ae9582cf72cacf16d0c72cdc7da4ceb83">add</a> and <a href="#adf84d2b16e9b39cca528666c9b93a5e8">add</a>.</p>

</div>
</div>

### add() {#ae9582cf72cacf16d0c72cdc7da4ceb83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVTypeRecords::add (uint32_t StreamIdx, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#adf84d2b16e9b39cca528666c9b93a5e8">add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>

</div>
</div>

### find() {#afeee49c1b4a888ec7c1f61325804b21c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVTypeRecords::find (uint32_t StreamIdx, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, bool Create=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#afeee49c1b4a888ec7c1f61325804b21c">find</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf33a9b90a30d17ecb3c53b2920cc5b1">llvm::codeview::TypeIndex::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#ac91b7c005927969946b469b676f10d97">llvm::logicalview::LVObject::setOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>


<p>Referenced by <a href="#a29f05cd10d036b2106900b9ff8fe1124">find</a> and <a href="#afeee49c1b4a888ec7c1f61325804b21c">find</a>.</p>

</div>
</div>

### find() {#a29f05cd10d036b2106900b9ff8fe1124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex LVTypeRecords::find (uint32_t StreamIdx, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#afeee49c1b4a888ec7c1f61325804b21c">find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a2d9a88c5d445b0e9d7299c3e4a7ca9a5">llvm::codeview::TypeIndex::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a330fc2ae3951b2cb65f9afe18148477caeb346ebd980b4497546a22f978bbdc19">llvm::pdb::StreamTPI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NameFromIds {#a39a7d61eaaf2fcfc1e1971f4613e3a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NameTable llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::NameFromIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### NameFromTypes {#a511491ae9d1e4bf8b057df079de50762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NameTable llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::NameFromTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### RecordFromIds {#abcd0061a87628f8aa1f9dd40f830f0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordTable llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::RecordFromIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### RecordFromTypes {#aa4b4b30583e9fe406b65ee405a83d2eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordTable llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::RecordFromTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### Shared {#a984b3d72de4ad3a3e7c16b5ce2357c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVShared* llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVTypeRecords::Shared = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
