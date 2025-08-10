---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/typesaredistinct
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TypesAreDistinct` Struct Template

<p>Determine if all types in Ts are distinct. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename... Ts&gt;
struct llvm::TypesAreDistinct&lt;Ts&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::integral_constant&lt; bool, detail::TypesAreDistinct&lt; Ts... &gt;::value &gt;</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Determine if all types in Ts are distinct.</p>


<p>Useful to statically assert when Ts is intended to describe a non-multi set of types.</p>


<p>Expensive (currently quadratic in sizeof(Ts...)), and so should only be asserted once per instantiation of a type which requires it.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
