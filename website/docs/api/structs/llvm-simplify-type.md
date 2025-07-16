---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/simplify-type
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `simplify_type` Struct Template Reference

<p>Define a template that can be specialized by smart pointers to reflect the fact that they are automatically dereferenced, and are not involved with the template selection process... the default implementation is a noop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename From&gt;
struct llvm::simplify_type&lt;From&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename From&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f12135ed9ee0ba54bd08387bc1e8f10">SimpleType</a> = From</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename From&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#a6f12135ed9ee0ba54bd08387bc1e8f10">SimpleType</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b88874a389afad6e628d5708dcdb4f9">getSimplifiedValue</a> (From &amp;Val)</td>
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

<p>Define a template that can be specialized by smart pointers to reflect the fact that they are automatically dereferenced, and are not involved with the template selection process... the default implementation is a noop.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SimpleType {#a6f12135ed9ee0ba54bd08387bc1e8f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename From&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::simplify_type&lt; From &gt;::SimpleType =  From</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSimplifiedValue() {#a4b88874a389afad6e628d5708dcdb4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename From&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimpleType &amp; llvm::simplify_type&lt; From &gt;::getSimplifiedValue (From &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/castinfo-33bc6205d237122805eee02a60b901d1/#af38241119d52b6309919a5143fb73c65">llvm::CastInfo&lt; To, From, std::enable_if_t&lt;!is_simple_type&lt; From &gt;::value &gt; &gt;::doCast</a>, <a href="/web-llvm/docs/api/structs/llvm/castinfo-33bc6205d237122805eee02a60b901d1/#af7bdec3154a1ae60f8c950fddfabc7c6">llvm::CastInfo&lt; To, From, std::enable_if_t&lt;!is_simple_type&lt; From &gt;::value &gt; &gt;::doCastIfPossible</a>, <a href="/web-llvm/docs/api/structs/llvm/cast-convert-val/#a5fc44adb8dbcadc7609b23ddeaf48db7">llvm::cast_convert_val&lt; To, From, SimpleFrom &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/isa-impl-wrap/#ab47febb39af2947d0185cd70a93ac4d0">llvm::isa_impl_wrap&lt; To, From, SimpleFrom &gt;::doit</a>, <a href="/web-llvm/docs/api/structs/llvm/simplify-type-fc3732c49716d3bb65042e46c5412ed1/#acc163d9a2a649f64ceddc0fc5aab6d55">llvm::simplify_type&lt; const From &gt;::getSimplifiedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/castinfo-33bc6205d237122805eee02a60b901d1/#a951abb930122c490f3a1db9c7fbbbb43">llvm::CastInfo&lt; To, From, std::enable_if_t&lt;!is_simple_type&lt; From &gt;::value &gt; &gt;::isPossible</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a4d29b9fc506d2c4711e795ae794de4e0">llvm::detail::isPresent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
