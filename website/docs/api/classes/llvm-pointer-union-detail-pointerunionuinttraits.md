---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pointer-union-detail/pointerunionuinttraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PointerUnionUIntTraits` Class Template Reference

<p>Provide <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a> for void* that is used by <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a> for the template arguments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ... PTs&gt;
class llvm::pointer_union_detail::PointerUnionUIntTraits&lt;PTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">llvm/ADT/PointerUnion.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af4aef2faa09e521d4bb0f9cfce0fb901">getAsVoidPointer</a> (void *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bb1148ff698f3fc1ca483419215ac9f">getFromVoidPointer</a> (void *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... PTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a654005149960c9ac69a4c9d65914736d">NumLowBitsAvailable</a> = <a href="/web-llvm/docs/api/namespaces/llvm/pointer-union-detail/#ab3a1b893284fbc5aaf78527e30151e3e">lowBitsAvailable</a>&lt;PTs...&gt;()</td>
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

<p>Provide <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a> for void* that is used by <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a> for the template arguments.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getAsVoidPointer() {#af4aef2faa09e521d4bb0f9cfce0fb901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::pointer_union_detail::PointerUnionUIntTraits&lt; PTs &gt;::getAsVoidPointer (void * P)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getFromVoidPointer() {#a3bb1148ff698f3fc1ca483419215ac9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::pointer_union_detail::PointerUnionUIntTraits&lt; PTs &gt;::getFromVoidPointer (void * P)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NumLowBitsAvailable {#a654005149960c9ac69a4c9d65914736d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... PTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::pointer_union_detail::PointerUnionUIntTraits&lt; PTs &gt;::NumLowBitsAvailable = <a href="/web-llvm/docs/api/namespaces/llvm/pointer-union-detail/#ab3a1b893284fbc5aaf78527e30151e3e">lowBitsAvailable</a>&lt;PTs...&gt;()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerunion-h">PointerUnion.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
