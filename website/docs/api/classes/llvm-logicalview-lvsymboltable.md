---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvsymboltable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LVSymbolTable` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVSymbolTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">llvm/DebugInfo/LogicalView/Readers/LVBinaryReader.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77879c3dfa6bce7b54cb06afcc25ef7">LVSymbolNames</a> = std::map&lt; std::string, <a href="/web-llvm/docs/api/structs/llvm/logicalview/lvsymboltableentry">LVSymbolTableEntry</a>, std::less&lt;&gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36337bf248e03e331c20d360ddfd023d">LVSymbolTable</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a5a0127b16ad855144f8cf685f0ee7">add</a> (StringRef Name, LVScope *Function, LVSectionIndex SectionIndex=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05ccbee52e66f5a21978b5c59a081ba">add</a> (StringRef Name, LVAddress Address, LVSectionIndex SectionIndex, bool IsComdat)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e5b75c69a12213b1af7ba626ce0773">update</a> (LVScope *Function)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd42021a3ce3803cf25cf07b54a0d67">getEntry</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d0402f7d0c9f7b177fb57958be389c">getAddress</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c79bada6f31803a5aba019bcb7cf0e">getIndex</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b884fc64cfec301aee5c0cb79aa58d">getIsComdat</a> (StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d894fd30a637d764b08da87b733e92f">print</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LVSymbolNames</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f7f9e1db839ea3bcad132e8a256d11">SymbolNames</a></td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LVSymbolNames {#ad77879c3dfa6bce7b54cb06afcc25ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::LVSymbolTable::LVSymbolNames =  std::map&lt;std::string, LVSymbolTableEntry, std::less&lt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVSymbolTable() {#a36337bf248e03e331c20d360ddfd023d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVSymbolTable::LVSymbolTable ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ab8a5a0127b16ad855144f8cf685f0ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVSymbolTable::add (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a> and <a href="#a5d894fd30a637d764b08da87b733e92f">print</a>.</p>

</div>
</div>

### add() {#aa05ccbee52e66f5a21978b5c59a081ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVSymbolTable::add (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#ad3a6cc0dd7aa2e5bf8b5d0ee648e6850">LVAddress</a> Address, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#abe7d68250d295e9000cdcb3eef735051">LVSectionIndex</a> SectionIndex, bool IsComdat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a> and <a href="#a5d894fd30a637d764b08da87b733e92f">print</a>.</p>

</div>
</div>

### getAddress() {#ab0d0402f7d0c9f7b177fb57958be389c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVAddress LVSymbolTable::getAddress (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### getEntry() {#adbd42021a3ce3803cf25cf07b54a0d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LVSymbolTableEntry &amp; LVSymbolTable::getEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### getIndex() {#a14c79bada6f31803a5aba019bcb7cf0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex LVSymbolTable::getIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a79e79d328c2a1364382c050f1edc3b9f">llvm::logicalview::LVReader::getDotTextSectionIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### getIsComdat() {#a20b884fc64cfec301aee5c0cb79aa58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LVSymbolTable::getIsComdat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>.</p>

</div>
</div>

### print() {#a5d894fd30a637d764b08da87b733e92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVSymbolTable::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a9696bc411b0a7022c2cc78bff5173cefadfd0a82c4bf37b1e90b690a22a20692e">llvm::logicalview::Offset</a>.</p>


<p>Referenced by <a href="#aa05ccbee52e66f5a21978b5c59a081ba">add</a>, <a href="#ab8a5a0127b16ad855144f8cf685f0ee7">add</a> and <a href="#ac8e5b75c69a12213b1af7ba626ce0773">update</a>.</p>

</div>
</div>

### update() {#ac8e5b75c69a12213b1af7ba626ce0773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSectionIndex LVSymbolTable::update (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Function)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvbinaryreader-cpp">LVBinaryReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#adfebd8c4ae29ccd84c600c1e65d6b807a86408593c34af77fdd90df932f8b5261">llvm::codeview::Function</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a79e79d328c2a1364382c050f1edc3b9f">llvm::logicalview::LVReader::getDotTextSectionIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a1c10e59416d98e95d2bc433fdb8273ab">llvm::logicalview::getReader</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a>, <a href="#a5d894fd30a637d764b08da87b733e92f">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a51919633e20f013bde3389c6db7fca2a">llvm::logicalview::UndefinedSectionIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SymbolNames {#ab5f7f9e1db839ea3bcad132e8a256d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVSymbolNames llvm::logicalview::LVSymbolTable::SymbolNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/readers/lvbinaryreader-h">LVBinaryReader.h</a>.</p>

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
