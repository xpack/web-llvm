---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/functionpointerliketypetraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FunctionPointerLikeTypeTraits` Struct Template Reference

<p>Provide suitable custom traits struct for function pointers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;int Alignment, typename FunctionPointerT&gt;
struct llvm::FunctionPointerLikeTypeTraits&lt;Alignment, FunctionPointerT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">llvm/Support/PointerLikeTypeTraits.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Alignment, typename FunctionPointerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae588adf5b3cc5cf13935d184f362665e">getAsVoidPointer</a> (FunctionPointerT P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Alignment, typename FunctionPointerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static FunctionPointerT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad53d1471afacf1b381c0cb3f5192251b">getFromVoidPointer</a> (void *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Alignment, typename FunctionPointerT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9270de90d202ecf2e3c2b99d4888eed3">NumLowBitsAvailable</a> = ...</td>
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

<p>Provide suitable custom traits struct for function pointers.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> pointers can't be directly given these traits as functions can't have their alignment computed with <span class="doxyComputerOutput">alignof</span> and we need different casting.</p>


<p>To rely on higher alignment for a specialized use, you can provide a customized form of this template explicitly with higher alignment, and potentially use alignment attributes on functions to satisfy that.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">PointerLikeTypeTraits.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getAsVoidPointer() {#ae588adf5b3cc5cf13935d184f362665e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Alignment, typename FunctionPointerT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::FunctionPointerLikeTypeTraits&lt; Alignment, FunctionPointerT &gt;::getAsVoidPointer (FunctionPointerT P)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">PointerLikeTypeTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9270de90d202ecf2e3c2b99d4888eed3">llvm::FunctionPointerLikeTypeTraits&lt; Alignment, FunctionPointerT &gt;::NumLowBitsAvailable</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getFromVoidPointer() {#ad53d1471afacf1b381c0cb3f5192251b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Alignment, typename FunctionPointerT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPointerT llvm::FunctionPointerLikeTypeTraits&lt; Alignment, FunctionPointerT &gt;::getFromVoidPointer (void * P)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">PointerLikeTypeTraits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NumLowBitsAvailable {#a9270de90d202ecf2e3c2b99d4888eed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Alignment, typename FunctionPointerT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::FunctionPointerLikeTypeTraits&lt; Alignment, FunctionPointerT &gt;::NumLowBitsAvailable</td>
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
      <a href="/web-llvm/docs/api/structs/llvm/detail/constantlog2">detail::ConstantLog2</a>&lt;Alignment&gt;::value
</div>
</dd>
</dl>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">PointerLikeTypeTraits.h</a>.</p>


<p>Referenced by <a href="#ae588adf5b3cc5cf13935d184f362665e">llvm::FunctionPointerLikeTypeTraits&lt; Alignment, FunctionPointerT &gt;::getAsVoidPointer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">PointerLikeTypeTraits.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
