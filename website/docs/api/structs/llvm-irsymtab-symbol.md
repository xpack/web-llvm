---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irsymtab/symbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Symbol` Struct Reference

<p>This represents a symbol that has been read from a <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol">storage::Symbol</a> and possibly a <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/uncommon">storage::Uncommon</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::irsymtab::Symbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">llvm/Object/IRSymtab.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/symbolref">SymbolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ephemeral symbols produced by <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/#a583e69face84cad10651476ced420ebd">Reader::symbols()</a> and <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/#a04409736e8ac494863b8d99d527923e1">Reader::module_symbols()</a>. <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/symbolref/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/inputfile/symbol">Symbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The purpose of this struct is to only expose the symbol information that an <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> client should need in order to do symbol resolution. <a href="/web-llvm/docs/api/structs/llvm/lto/inputfile/symbol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf930621dd3dd37428f7b9acea068026">S</a> = <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol">storage::Symbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0488e0ae187e220414c6d661f86dd153">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mangled symbol name. <a href="#a0488e0ae187e220414c6d661f86dd153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5f86797118279c69b62e476f033a43">getIRName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the unmangled symbol name, or the empty string if this is not an IR symbol. <a href="#aee5f86797118279c69b62e476f033a43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f365e21de926757362dcb743903f3e">getComdatIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index into the comdat table (see <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/#a87437598fc43eb1826414fcf27437c4e">Reader::getComdatTable()</a>), or -1 if not a comdat member. <a href="#ac9f365e21de926757362dcb743903f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195">GlobalValue::VisibilityTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addb627f9f45719fbabaf711aa463b89a">getVisibility</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec23c2eab4271bd09a1947ee550aff2">isUndefined</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597749a65478ff8c18f9c0e2a62ecb3e">isWeak</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9fc5bd7094cc29df1c7eeedf435267">isCommon</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63cd5e6db4978253c05f9975614054a7">isIndirect</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a1174be536faf58a36e68890e249c9">isUsed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53200b8f146dcb7f01b7d4357ea02732">isTLS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e95458c286cdf95be5aecd99537422">canBeOmittedFromSymbolTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9b9b2f3a4ac8a01c37983561e7d6f3">isGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dce176e85a4b418f6ac2092f27d9e4">isFormatSpecific</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e7a448edb150d1341ed648c01040ed">isUnnamedAddr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf862cc382d391a92fd2d335776c91cd">isExecutable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab687f8a8fcca54212ce1f40c9ad206fc">getCommonSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a37e5a7ef03af4b9917bcf9a92d12a">getCommonAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80e7369e850d761a976f6c37a8ebd76">getCOFFWeakExternalFallback</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>COFF-specific: for weak externals, returns the name of the symbol that is used as a fallback if the weak external remains undefined. <a href="#af80e7369e850d761a976f6c37a8ebd76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435dbc8ed915e18dddaea03a4e2ad1e9">getSectionName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269e722995aae4ceba7ed9ef4f577294">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842acdf5182b4bc353088be65fb800cc">IRName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb1d81966df21452806e152842056a1">ComdatIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39956b88f14e14a089b554094b2117d3">CommonSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50d4658766825f2852fdf021c7f895f">CommonAlign</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b958acbb28ed053a8df76c62093271">COFFWeakExternFallbackName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb661217f251c7e0f1e6db2996a0fae">SectionName</a></td>
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

<p>This represents a symbol that has been read from a <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol">storage::Symbol</a> and possibly a <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/uncommon">storage::Uncommon</a>.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### S {#abf930621dd3dd37428f7b9acea068026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::irsymtab::Symbol::S =  storage::Symbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canBeOmittedFromSymbolTable() {#a16e95458c286cdf95be5aecd99537422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::canBeOmittedFromSymbolTable ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a0c7e3d2ade01c95c114a1c9765d92843">llvm::irsymtab::storage::Symbol::FB_may_omit</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### getCOFFWeakExternalFallback() {#af80e7369e850d761a976f6c37a8ebd76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::getCOFFWeakExternalFallback ()</td>
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

<p>COFF-specific: for weak externals, returns the name of the symbol that is used as a fallback if the weak external remains undefined.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a63b958acbb28ed053a8df76c62093271">COFFWeakExternFallbackName</a>, <a href="#a63cd5e6db4978253c05f9975614054a7">isIndirect</a> and <a href="#a597749a65478ff8c18f9c0e2a62ecb3e">isWeak</a>.</p>

</div>
</div>

### getComdatIndex() {#ac9f365e21de926757362dcb743903f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::irsymtab::Symbol::getComdatIndex ()</td>
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

<p>Returns the index into the comdat table (see <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/#a87437598fc43eb1826414fcf27437c4e">Reader::getComdatTable()</a>), or -1 if not a comdat member.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Reference <a href="#a9eb1d81966df21452806e152842056a1">ComdatIndex</a>.</p>

</div>
</div>

### getCommonAlignment() {#a78a37e5a7ef03af4b9917bcf9a92d12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::irsymtab::Symbol::getCommonAlignment ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae50d4658766825f2852fdf021c7f895f">CommonAlign</a> and <a href="#a6c9fc5bd7094cc29df1c7eeedf435267">isCommon</a>.</p>

</div>
</div>

### getCommonSize() {#ab687f8a8fcca54212ce1f40c9ad206fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::irsymtab::Symbol::getCommonSize ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39956b88f14e14a089b554094b2117d3">CommonSize</a> and <a href="#a6c9fc5bd7094cc29df1c7eeedf435267">isCommon</a>.</p>

</div>
</div>

### getIRName() {#aee5f86797118279c69b62e476f033a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::getIRName ()</td>
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

<p>Returns the unmangled symbol name, or the empty string if this is not an IR symbol.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Reference <a href="#a842acdf5182b4bc353088be65fb800cc">IRName</a>.</p>

</div>
</div>

### getName() {#a0488e0ae187e220414c6d661f86dd153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::getName ()</td>
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

<p>Returns the mangled symbol name.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Reference <a href="#a269e722995aae4ceba7ed9ef4f577294">Name</a>.</p>

</div>
</div>

### getSectionName() {#a435dbc8ed915e18dddaea03a4e2ad1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::getSectionName ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Reference <a href="#a0eb661217f251c7e0f1e6db2996a0fae">SectionName</a>.</p>

</div>
</div>

### getVisibility() {#addb627f9f45719fbabaf711aa463b89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::VisibilityTypes llvm::irsymtab::Symbol::getVisibility ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044af436b974827038126ac1f7571fe7c782">llvm::irsymtab::storage::Symbol::FB_visibility</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isCommon() {#a6c9fc5bd7094cc29df1c7eeedf435267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isCommon ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a39c454028de579646252d421c11e9ff7">llvm::irsymtab::storage::Symbol::FB_common</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>


<p>Referenced by <a href="#a78a37e5a7ef03af4b9917bcf9a92d12a">getCommonAlignment</a> and <a href="#ab687f8a8fcca54212ce1f40c9ad206fc">getCommonSize</a>.</p>

</div>
</div>

### isExecutable() {#aaf862cc382d391a92fd2d335776c91cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isExecutable ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ae6a4c6f4fb710d3b1f182ff515ec0f12">llvm::irsymtab::storage::Symbol::FB_executable</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isFormatSpecific() {#aa1dce176e85a4b418f6ac2092f27d9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isFormatSpecific ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ac9b24a0d1a0b250d9e39e8ea32d25ca3">llvm::irsymtab::storage::Symbol::FB_format_specific</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isGlobal() {#a3b9b9b2f3a4ac8a01c37983561e7d6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isGlobal ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ac2089e2cc45b6d466d598e96d03905c9">llvm::irsymtab::storage::Symbol::FB_global</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isIndirect() {#a63cd5e6db4978253c05f9975614054a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isIndirect ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044ab719fc49b41ba3c560bed3b15f6812ec">llvm::irsymtab::storage::Symbol::FB_indirect</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>


<p>Referenced by <a href="#af80e7369e850d761a976f6c37a8ebd76">getCOFFWeakExternalFallback</a>.</p>

</div>
</div>

### isTLS() {#a53200b8f146dcb7f01b7d4357ea02732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isTLS ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044aa8b208ca059882d330626b67d527bf26">llvm::irsymtab::storage::Symbol::FB_tls</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isUndefined() {#adec23c2eab4271bd09a1947ee550aff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isUndefined ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a3d9d39ed5d35e5b9c47a26e12e648a37">llvm::irsymtab::storage::Symbol::FB_undefined</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isUnnamedAddr() {#a57e7a448edb150d1341ed648c01040ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isUnnamedAddr ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a3dbb25ac19ece6e32c9cf553a455e6b5">llvm::irsymtab::storage::Symbol::FB_unnamed_addr</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isUsed() {#a42a1174be536faf58a36e68890e249c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isUsed ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044a8579bc5377de3f38a2e81e5d65632bad">llvm::irsymtab::storage::Symbol::FB_used</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>

</div>
</div>

### isWeak() {#a597749a65478ff8c18f9c0e2a62ecb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::irsymtab::Symbol::isWeak ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/irsymtab/storage/symbol/#af6aea5aadd80212d171ebddff0ae7044aa9fc3498b248880573a354711d74931e">llvm::irsymtab::storage::Symbol::FB_weak</a> and <a href="#a3b2f202d72c50ec877e1290c50bfab28">Flags</a>.</p>


<p>Referenced by <a href="#af80e7369e850d761a976f6c37a8ebd76">getCOFFWeakExternalFallback</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### COFFWeakExternFallbackName {#a63b958acbb28ed053a8df76c62093271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::COFFWeakExternFallbackName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#af80e7369e850d761a976f6c37a8ebd76">getCOFFWeakExternalFallback</a>.</p>

</div>
</div>

### ComdatIndex {#a9eb1d81966df21452806e152842056a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::irsymtab::Symbol::ComdatIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#ac9f365e21de926757362dcb743903f3e">getComdatIndex</a>.</p>

</div>
</div>

### CommonAlign {#ae50d4658766825f2852fdf021c7f895f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::irsymtab::Symbol::CommonAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#a78a37e5a7ef03af4b9917bcf9a92d12a">getCommonAlignment</a>.</p>

</div>
</div>

### CommonSize {#a39956b88f14e14a089b554094b2117d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::irsymtab::Symbol::CommonSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#ab687f8a8fcca54212ce1f40c9ad206fc">getCommonSize</a>.</p>

</div>
</div>

### Flags {#a3b2f202d72c50ec877e1290c50bfab28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::irsymtab::Symbol::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#a16e95458c286cdf95be5aecd99537422">canBeOmittedFromSymbolTable</a>, <a href="#addb627f9f45719fbabaf711aa463b89a">getVisibility</a>, <a href="#a6c9fc5bd7094cc29df1c7eeedf435267">isCommon</a>, <a href="#aaf862cc382d391a92fd2d335776c91cd">isExecutable</a>, <a href="#aa1dce176e85a4b418f6ac2092f27d9e4">isFormatSpecific</a>, <a href="#a3b9b9b2f3a4ac8a01c37983561e7d6f3">isGlobal</a>, <a href="#a63cd5e6db4978253c05f9975614054a7">isIndirect</a>, <a href="#a53200b8f146dcb7f01b7d4357ea02732">isTLS</a>, <a href="#adec23c2eab4271bd09a1947ee550aff2">isUndefined</a>, <a href="#a57e7a448edb150d1341ed648c01040ed">isUnnamedAddr</a>, <a href="#a42a1174be536faf58a36e68890e249c9">isUsed</a>, <a href="#a597749a65478ff8c18f9c0e2a62ecb3e">isWeak</a> and <a href="/web-llvm/docs/api/classes/llvm/irsymtab/reader/symbolref/#ab9c5de9d18da48567a5085c76b47911e">llvm::irsymtab::Reader::SymbolRef::moveNext</a>.</p>

</div>
</div>

### IRName {#a842acdf5182b4bc353088be65fb800cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::IRName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#aee5f86797118279c69b62e476f033a43">getIRName</a>.</p>

</div>
</div>

### Name {#a269e722995aae4ceba7ed9ef4f577294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::Name</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#a0488e0ae187e220414c6d661f86dd153">getName</a>.</p>

</div>
</div>

### SectionName {#a0eb661217f251c7e0f1e6db2996a0fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::irsymtab::Symbol::SectionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">IRSymtab.h</a>.</p>


<p>Referenced by <a href="#a435dbc8ed915e18dddaea03a4e2ad1e9">getSectionName</a>.</p>

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
