---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/pointersumtypehelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PointerSumTypeHelper` Struct Template Reference

<p>A helper template for implementing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pointersumtype">PointerSumType</a></span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename TagT, typename... MemberTs&gt;
struct llvm::detail::PointerSumTypeHelper&lt;TagT, MemberTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">llvm/ADT/PointerSumType.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemberTs...</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TagT, typename... MemberTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#a78a6088ac065fefc180e7594f25c6552">...</a> }</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TagT, typename... MemberTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> : uint64_t { <a href="#a0e0483d5325b9266682ff5e1dcd706fa">...</a> }</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;TagT N, typename PointerT, typename TraitsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac6790710c23f2e09fbbd366c5b365214">LookupOverload</a> (PointerSumTypeMember&lt; N, PointerT, TraitsT &gt; *) -&gt; <a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, PointerT, <a href="/web-llvm/docs/api/classes/traitst">TraitsT</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;TagT N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a133877d447fe8c73d27941db1ee1623d">LookupOverload</a> (...)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TagT, typename... MemberTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr TagT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4092e609a5f36c3dc8a0b548c5b901db">MinTag</a> = ...</td>
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

<p>A helper template for implementing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pointersumtype">PointerSumType</a></span>.</p>


<p>It provides fast compile-time lookup of the member from a particular tag value, along with useful constants and compile time checking infrastructure..</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a78a6088ac065fefc180e7594f25c6552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">NumTagBits<a id="a78a6088ac065fefc180e7594f25c6552a89ff096aead3839255013f1e6c785902"></a></td>
<td class="doxyEnumItemDescription"> (= Min&lt;MemberTs::TraitsT::NumLowBitsAvailable...&gt;::value)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a>.</p>

</div>
</div>

### anonymous enum  {#a0e0483d5325b9266682ff5e1dcd706fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint64_t</td>
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
<td class="doxyEnumItemName">PointerMask<a id="a0e0483d5325b9266682ff5e1dcd706faa9a36102b39902f39ba2d7c86e851a285"></a></td>
<td class="doxyEnumItemDescription"> (= static_cast&lt;uint64_t&gt;(-1) &lt;&lt; NumTagBits)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TagMask<a id="a0e0483d5325b9266682ff5e1dcd706faac8ea40f18be819ba919f824292a6fbb6"></a></td>
<td class="doxyEnumItemDescription"> (= ~PointerMask)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### LookupOverload() {#ac6790710c23f2e09fbbd366c5b365214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;TagT N, typename PointerT, typename TraitsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerSumTypeMember&lt; N, PointerT, TraitsT &gt; llvm::detail::PointerSumTypeHelper&lt; TagT, MemberTs &gt;::LookupOverload (<a href="/web-llvm/docs/api/structs/llvm/pointersumtypemember">PointerSumTypeMember</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, PointerT, <a href="/web-llvm/docs/api/classes/traitst">TraitsT</a> &gt; *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a>.</p>

</div>
</div>

### LookupOverload() {#a133877d447fe8c73d27941db1ee1623d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;TagT N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::detail::PointerSumTypeHelper&lt; TagT, MemberTs &gt;::LookupOverload (...)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### MinTag {#a4092e609a5f36c3dc8a0b548c5b901db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TagT, typename... MemberTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagT llvm::detail::PointerSumTypeHelper&lt; TagT, MemberTs &gt;::MinTag</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      static_cast&lt;TagT&gt;(<a href="/web-llvm/docs/api/structs/llvm/detail/pointersumtypehelper/min">Min</a>&lt;MemberTs::Tag...&gt;<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">::value</a>)
</div>
</dd>
</dl>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointersumtype-h">PointerSumType.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
