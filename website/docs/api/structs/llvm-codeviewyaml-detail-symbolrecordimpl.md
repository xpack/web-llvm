---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/detail/symbolrecordimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SymbolRecordImpl` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::CodeViewYAML::detail::SymbolRecordImpl&lt;T&gt; { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase">SymbolRecordBase</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aadbb3d901f554d3ee2facf47df6789ed">SymbolRecordImpl</a> (codeview::SymbolKind K)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48f079beaca7d1b5b8a441d9b9fb3d13">map</a> (yaml::IO &amp;io) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">codeview::CVSymbol</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3eb44747128a9792d002a70ce17a1239">toCodeViewSymbol</a> (BumpPtrAllocator &amp;Allocator, CodeViewContainer Container) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a946f92a0c1edf978ef6731937ec00109">fromCodeViewSymbol</a> (codeview::CVSymbol CVS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a036a1eb4571aff99392e6ea3da236b5c">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba52465c1cff9a9455fb23f909ea5e7c">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa3b106942d2ada347227ea86712a9e8">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd71e8c1afbf744aca57c0006b6cd530">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add38b1fdadc2fe3f83368c6e547fffe0">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a55733181db004e7a5b15ca03bc3c2b74">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11724097bf3be24b922ed78b9f10e8ea">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a870def1898696e670fed70c42b23e5ab">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb0a518a2f3cbbcfdef755d7290410a8">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acf5eac154cfe3da526156a9362c57c89">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af114d88ab09cdf7cd9a6d504e955165c">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acadb3ba1ba4582c5ccb4358e9aca9d66">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa569faa73e17f6603300f4cdc1dbefd1">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b60aaa55b7e046781c4dbb110b5677a">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a907e2a6fb390b22f11d0fdfef16eec76">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89735492cd40fdd33dfa15e923184967">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6aada6094a05a52acc58a14d0dfc09ca">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9462368d0e542a10197f5a5a12a1805b">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa596eab5707f276631f5b991e0ebda98">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a436ebbf0d4fb45c3b40473a54f443025">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29b23cb7aa66c43f5a53a090df804209">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4368e69409c16e8bb9fa028bb50e2f6c">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac95e6dd7188807a2f54d0c62889d12cc">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a583d139784a6b169ca0824049a250f82">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7bc5004dbd95938aa4742e06e3f3bba4">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8f3171f4e2b1ba6585871904e6a3dc5c">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59c3f96fc3a3d55c1f6196bd4225e778">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e5086e2aa8ebd9540f029cae59dc691">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6f43e9ee79ced60e828cdefd0218060">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9e5be9f3ba50dfdc21ebb89340d2200">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a460c8b1c7a3f80d4c6dd15b760db6438">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d7ee249190d5597f120ba414739578e">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba2354da172b09118ed769ffaf906713">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a235f06661d49b57941ab539fb4cd70f4">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf075dfdc439ca4d8b1c927facd8eb03">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a34d7587db1c8ae2b56817966ebbd2749">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1103e534909edc78113e13cb65d0011a">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad3886bb5c4354a5451a0ae77f6ba4779">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6afe8268be2e3a61d8044a237b1b5b20">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a120be8f78b26739a364c7a9f6dc3409d">map</a> (IO &amp;IO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab69482b5b3592d6c038a49ef284dc0b0">map</a> (IO &amp;IO)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad189ed7be4ec21107c2c31af563801b7">Symbol</a></td>
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


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolRecordImpl() {#aadbb3d901f554d3ee2facf47df6789ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::SymbolRecordImpl (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase/#a072bf2ce5285b17d28580f5e2b6b626f">llvm::CodeViewYAML::detail::SymbolRecordBase::SymbolRecordBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fromCodeViewSymbol() {#a946f92a0c1edf978ef6731937ec00109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::fromCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">codeview::CVSymbol</a> CVS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/symboldeserializer/#a4f31719a3302d53ef0f8ab28e7afc76e">llvm::codeview::SymbolDeserializer::deserializeAs</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a48f079beaca7d1b5b8a441d9b9fb3d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; io)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>

</div>
</div>

### map() {#a036a1eb4571aff99392e6ea3da236b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ScopeEndSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>

</div>
</div>

### map() {#aba52465c1cff9a9455fb23f909ea5e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; Thunk32Sym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aaa3b106942d2ada347227ea86712a9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; TrampolineSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#abd71e8c1afbf744aca57c0006b6cd530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; SectionSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#add38b1fdadc2fe3f83368c6e547fffe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; CoffGroupSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a55733181db004e7a5b15ca03bc3c2b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ExportSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a11724097bf3be24b922ed78b9f10e8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ProcSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a870def1898696e670fed70c42b23e5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; RegisterSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aeb0a518a2f3cbbcfdef755d7290410a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; PublicSym32 &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#acf5eac154cfe3da526156a9362c57c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ProcRefSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#af114d88ab09cdf7cd9a6d504e955165c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; EnvBlockSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#acadb3ba1ba4582c5ccb4358e9aca9d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; InlineSiteSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aa569faa73e17f6603300f4cdc1dbefd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; LocalSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a4b60aaa55b7e046781c4dbb110b5677a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a907e2a6fb390b22f11d0fdfef16eec76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeSubfieldSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a89735492cd40fdd33dfa15e923184967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeRegisterSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a6aada6094a05a52acc58a14d0dfc09ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeFramePointerRelSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a9462368d0e542a10197f5a5a12a1805b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeSubfieldRegisterSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aa596eab5707f276631f5b991e0ebda98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeFramePointerRelFullScopeSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a436ebbf0d4fb45c3b40473a54f443025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DefRangeRegisterRelSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a29b23cb7aa66c43f5a53a090df804209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; BlockSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a4368e69409c16e8bb9fa028bb50e2f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; LabelSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#ac95e6dd7188807a2f54d0c62889d12cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ObjNameSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a583d139784a6b169ca0824049a250f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; Compile2Sym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a7bc5004dbd95938aa4742e06e3f3bba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; Compile3Sym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a8f3171f4e2b1ba6585871904e6a3dc5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; FrameProcSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a59c3f96fc3a3d55c1f6196bd4225e778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; CallSiteInfoSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a6e5086e2aa8ebd9540f029cae59dc691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; FileStaticSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aa6f43e9ee79ced60e828cdefd0218060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; HeapAllocationSiteSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#ab9e5be9f3ba50dfdc21ebb89340d2200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; FrameCookieSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a460c8b1c7a3f80d4c6dd15b760db6438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; CallerSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a4d7ee249190d5597f120ba414739578e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; UDTSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aba2354da172b09118ed769ffaf906713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; BuildInfoSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a235f06661d49b57941ab539fb4cd70f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; BPRelativeSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#aaf075dfdc439ca4d8b1c927facd8eb03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; RegRelativeSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a34d7587db1c8ae2b56817966ebbd2749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ConstantSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a1103e534909edc78113e13cb65d0011a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; DataSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#ad3886bb5c4354a5451a0ae77f6ba4779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; ThreadLocalDataSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a6afe8268be2e3a61d8044a237b1b5b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; UsingNamespaceSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#a120be8f78b26739a364c7a9f6dc3409d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; AnnotationSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### map() {#ab69482b5b3592d6c038a49ef284dc0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; JumpTableSym &gt;::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a>.</p>

</div>
</div>

### toCodeViewSymbol() {#a3eb44747128a9792d002a70ce17a1239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::CVSymbol llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::toCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a> Container)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="#ad189ed7be4ec21107c2c31af563801b7">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolserializer/#a676fab3398dbcf60c457a2f9c4b906ca">llvm::codeview::SymbolSerializer::writeOneSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Symbol {#ad189ed7be4ec21107c2c31af563801b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::Symbol</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>Referenced by <a href="#a946f92a0c1edf978ef6731937ec00109">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::fromCodeViewSymbol</a>, <a href="#aba52465c1cff9a9455fb23f909ea5e7c">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::map</a>, <a href="#aadbb3d901f554d3ee2facf47df6789ed">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::SymbolRecordImpl</a> and <a href="#a3eb44747128a9792d002a70ce17a1239">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::toCodeViewSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
