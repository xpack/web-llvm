---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irsymtab/storage/symbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Symbol` Struct Reference

<p>Contains the information needed by linkers for symbol resolution, as well as by the LTO implementation itself. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::irsymtab::storage::Symbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">llvm/Object/IRSymtab.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FlagBits { <a href="#af6aea5aadd80212d171ebddff0ae7044">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str">Str</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa126d0b6d1533f884c2b9978a35756">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The mangled symbol name. <a href="#a1fa126d0b6d1533f884c2b9978a35756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/str">Str</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e8eafa4ca28049374f061a4d17d37b">IRName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The unmangled symbol name, or the empty string if this is not an IR symbol. <a href="#a65e8eafa4ca28049374f061a4d17d37b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/storage/#ad2b23175625fe2187c025e9f539189a1">Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf3966d2746425299faab5e24315dd7">ComdatIndex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index into <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a15768088710b326e457bb867b234411a">Header::Comdats</a>, or -1 if not a comdat member. <a href="#a6cf3966d2746425299faab5e24315dd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsymtab/storage/#ad2b23175625fe2187c025e9f539189a1">Word</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8128467af78b7c88024035c4dc42b63">Flags</a></td>
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

<p>Contains the information needed by linkers for symbol resolution, as well as by the LTO implementation itself.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FlagBits {#af6aea5aadd80212d171ebddff0ae7044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::irsymtab::storage::Symbol::FlagBits </td>
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
<td class="doxyEnumItemName">FB_visibility<a id="af6aea5aadd80212d171ebddff0ae7044af436b974827038126ac1f7571fe7c782"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_has_uncommon<a id="af6aea5aadd80212d171ebddff0ae7044a818b95c61117ffdfb3514347da730b96"></a></td>
<td class="doxyEnumItemDescription"> (= FB_visibility + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_undefined<a id="af6aea5aadd80212d171ebddff0ae7044a3d9d39ed5d35e5b9c47a26e12e648a37"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_weak<a id="af6aea5aadd80212d171ebddff0ae7044aa9fc3498b248880573a354711d74931e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_common<a id="af6aea5aadd80212d171ebddff0ae7044a39c454028de579646252d421c11e9ff7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_indirect<a id="af6aea5aadd80212d171ebddff0ae7044ab719fc49b41ba3c560bed3b15f6812ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_used<a id="af6aea5aadd80212d171ebddff0ae7044a8579bc5377de3f38a2e81e5d65632bad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_tls<a id="af6aea5aadd80212d171ebddff0ae7044aa8b208ca059882d330626b67d527bf26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_may_omit<a id="af6aea5aadd80212d171ebddff0ae7044a0c7e3d2ade01c95c114a1c9765d92843"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_global<a id="af6aea5aadd80212d171ebddff0ae7044ac2089e2cc45b6d466d598e96d03905c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_format_specific<a id="af6aea5aadd80212d171ebddff0ae7044ac9b24a0d1a0b250d9e39e8ea32d25ca3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_unnamed_addr<a id="af6aea5aadd80212d171ebddff0ae7044a3dbb25ac19ece6e32c9cf553a455e6b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FB_executable<a id="af6aea5aadd80212d171ebddff0ae7044ae6a4c6f4fb710d3b1f182ff515ec0f12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ComdatIndex {#a6cf3966d2746425299faab5e24315dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Word llvm::irsymtab::storage::Symbol::ComdatIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index into <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/header/#a15768088710b326e457bb867b234411a">Header::Comdats</a>, or -1 if not a comdat member.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>.</p>

</div>
</div>

### Flags {#ae8128467af78b7c88024035c4dc42b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Word llvm::irsymtab::storage::Symbol::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>.</p>

</div>
</div>

### IRName {#a65e8eafa4ca28049374f061a4d17d37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Str llvm::irsymtab::storage::Symbol::IRName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The unmangled symbol name, or the empty string if this is not an IR symbol.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>.</p>

</div>
</div>

### Name {#a1fa126d0b6d1533f884c2b9978a35756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Str llvm::irsymtab::storage::Symbol::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The mangled symbol name.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
