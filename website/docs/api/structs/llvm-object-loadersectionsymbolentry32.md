---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/loadersectionsymbolentry32
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoaderSectionSymbolEntry32` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::object::LoaderSectionSymbolEntry32 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">llvm/Object/XCOFFObjectFile.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b20e4a707c0bce1f7c19520f50bb90d">getSymbolName</a> (const LoaderSectionHeader32 *LoaderSecHeader) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29b779868ad66e9b7cc4ad8ff1216e0">SymbolName</a>[XCOFF::NameSize]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a9351dc9ad74cfe9ab63829d6926db48c">support::ubig32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe35a1e54cb044a4ccee1656d4316fdf">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a74c65fd6a4129b28e58e2f52dd021f8b">support::big16_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe568e91c7b0dae2b63704e180e1ff29">SectionNumber</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d68f96c83a63d099eeeb08997c22f6">SymbolType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5cfe4b7c59c4f650132d6d0186af5b">StorageClass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a9351dc9ad74cfe9ab63829d6926db48c">support::ubig32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25ab8b80da04385c1fdb76d2ff734b7">ImportFileID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a9351dc9ad74cfe9ab63829d6926db48c">support::ubig32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11c860bd775384d59e0f1125e2def74">ParameterTypeCheck</a></td>
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


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getSymbolName() {#a1b20e4a707c0bce1f7c19520f50bb90d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::LoaderSectionSymbolEntry32::getSymbolName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionheader32">LoaderSectionHeader32</a> * LoaderSecHeader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#abf04cdbb3bd4b5dc04636289e70ad71f">llvm::object::generateXCOFFFixedNameStringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a328dcddbae94eecadd48eb5d7986e2cb">llvm::object::getLoaderSecSymNameInStrTbl</a>, <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionsymbolentry32/nameoffsetinstrtbl/#a4c1ab195938bba396aaa8967970f0a1b">llvm::object::LoaderSectionSymbolEntry32::NameOffsetInStrTbl::IsNameInStrTbl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#ade25d600bbb69175395c080937b26432af61f2d9adb48d75296456e11766f3d5f">llvm::object::XCOFFSymbolRef::NAME_IN_STR_TBL_MAGIC</a>, <a href="/web-llvm/docs/api/structs/llvm/object/loadersectionsymbolentry32/nameoffsetinstrtbl/#a30be403ef9717f56aa4eb999559d52a5">llvm::object::LoaderSectionSymbolEntry32::NameOffsetInStrTbl::Offset</a> and <a href="#ad29b779868ad66e9b7cc4ad8ff1216e0">SymbolName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ImportFileID {#ae25ab8b80da04385c1fdb76d2ff734b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ubig32_t llvm::object::LoaderSectionSymbolEntry32::ImportFileID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### ParameterTypeCheck {#ae11c860bd775384d59e0f1125e2def74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ubig32_t llvm::object::LoaderSectionSymbolEntry32::ParameterTypeCheck</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### SectionNumber {#abe568e91c7b0dae2b63704e180e1ff29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::big16_t llvm::object::LoaderSectionSymbolEntry32::SectionNumber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### StorageClass {#a7c5cfe4b7c59c4f650132d6d0186af5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::StorageClass llvm::object::LoaderSectionSymbolEntry32::StorageClass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### SymbolName {#ad29b779868ad66e9b7cc4ad8ff1216e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::object::LoaderSectionSymbolEntry32::SymbolName[XCOFF::NameSize]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Referenced by <a href="#a1b20e4a707c0bce1f7c19520f50bb90d">getSymbolName</a>.</p>

</div>
</div>

### SymbolType {#ae2d68f96c83a63d099eeeb08997c22f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::LoaderSectionSymbolEntry32::SymbolType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

### Value {#abe35a1e54cb044a4ccee1656d4316fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ubig32_t llvm::object::LoaderSectionSymbolEntry32::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
