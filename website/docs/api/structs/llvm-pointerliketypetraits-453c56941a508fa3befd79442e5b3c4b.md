---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/pointerliketypetraits-453c56941a508fa3befd79442e5b3c4b
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PointerLikeTypeTraits` Struct Template

<p>Provide a default specialization for function pointers that assumes 4-byte alignment. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ReturnT, typename... ParamTs&gt;
struct llvm::PointerLikeTypeTraits&lt;ReturnT(*)(ParamTs...)&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">llvm/Support/PointerLikeTypeTraits.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/functionpointerliketypetraits">FunctionPointerLikeTypeTraits&lt;Alignment, FunctionPointerT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide suitable custom traits struct for function pointers. <a href="/web-llvm/docs/api/structs/llvm/functionpointerliketypetraits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Provide a default specialization for function pointers that assumes 4-byte alignment.</p>


<p>We assume here that functions used with this are always at least 4-byte aligned. This means that, for example, thumb functions won't work or systems with weird unaligned function pointers won't work. But all practical systems we support satisfy this requirement.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pointerliketypetraits-h">PointerLikeTypeTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
