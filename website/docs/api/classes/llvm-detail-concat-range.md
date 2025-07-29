---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/concat-range
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `concat_range` Class Template

<p>Helper to store a sequence of ranges being concatenated and access them. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ValueT, typename... RangeTs&gt;
class llvm::detail::concat_range&lt;ValueT, RangeTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/concat-iterator">concat_iterator</a>&lt; ValueT, decltype(std::begin(std::declval&lt; RangeTs &amp; &gt;()))... &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a195c303a3f38e1d297390e03ec174e58">concat_range</a> (RangeTs &amp;&amp;... Ranges)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d2d88e51316dc0ab99eabcd667e4de5">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac33b2ffeb41e3c3b835a166a6dd81ef5">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a48561ad734baff0a4a228352de7f9eed">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abeba4ea61a595a85487e7c2099667ebb">end</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adde52c091e3226d0b32e2f891cf6bef4">begin_impl</a> (std::index_sequence&lt; Ns... &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51938b1c8c69c1b59f4998c58d5019e0">begin_impl</a> (std::index_sequence&lt; Ns... &gt;) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6331033c2b589b785f2ed40371aaa49">end_impl</a> (std::index_sequence&lt; Ns... &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t... Ns&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aaae5b56812620e26f543cce5f0e16765">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f4fb93a5fc2e17bd6647ef3878173dc">end_impl</a> (std::index_sequence&lt; Ns... &gt;) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT, typename... RangeTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::tuple&lt; RangeTs... &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb1370762b88cd1a1837fb350134c957">Ranges</a></td>
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

<p>Helper to store a sequence of ranges being concatenated and access them.</p>


<p>This is designed to facilitate providing actual storage when temporaries are passed into the constructor such that we can use it as part of range based for loops.</p>


<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#aaae5b56812620e26f543cce5f0e16765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::iterator = 
      concat_iterator&lt;ValueT,
                      decltype(std::begin(std::declval&lt;RangeTs &amp;&gt;()))...&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### concat\_range() {#a195c303a3f38e1d297390e03ec174e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::concat_range (RangeTs &amp;&amp;... Ranges)</td>
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



<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a7d2d88e51316dc0ab99eabcd667e4de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::begin ()</td>
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



<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### begin() {#ac33b2ffeb41e3c3b835a166a6dd81ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::begin ()</td>
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



<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### end() {#a48561ad734baff0a4a228352de7f9eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::end ()</td>
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



<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### end() {#abeba4ea61a595a85487e7c2099667ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::end ()</td>
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



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### begin\_impl() {#adde52c091e3226d0b32e2f891cf6bef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::begin_impl (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 1150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### begin\_impl() {#a51938b1c8c69c1b59f4998c58d5019e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::begin_impl (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### end\_impl() {#af6331033c2b589b785f2ed40371aaa49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::end_impl (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

### end\_impl() {#a2f4fb93a5fc2e17bd6647ef3878173dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t... Ns&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::end_impl (std::index_sequence&lt; Ns... &gt;)</td>
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



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ranges {#abb1370762b88cd1a1837fb350134c957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT, typename... RangeTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt;RangeTs...&gt; llvm::detail::concat_range&lt; ValueT, RangeTs &gt;::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
