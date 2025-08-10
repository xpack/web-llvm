---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/foldingsettrait
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FoldingSetTrait` Struct Template

<p><a href="/web-llvm/docs/api/structs/llvm/foldingsettrait">FoldingSetTrait</a> - This trait class is used to define behavior of how to "profile" (in the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> parlance) an object of a given type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Enable = void&gt;
struct llvm::FoldingSetTrait&lt;T, Enable&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/defaultfoldingsettrait">DefaultFoldingSetTrait&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/defaultfoldingsettrait">DefaultFoldingSetTrait</a> - This class provides default implementations for <a href="/web-llvm/docs/api/structs/llvm/foldingsettrait">FoldingSetTrait</a> implementations. <a href="/web-llvm/docs/api/structs/llvm/defaultfoldingsettrait/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/foldingsettrait">FoldingSetTrait</a> - This trait class is used to define behavior of how to "profile" (in the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> parlance) an object of a given type.</p>


<p>The default behavior is to invoke a 'Profile' method on an object, but through template specialization the behavior can be tailored for specific types. Combined with the <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodewrapper">FoldingSetNodeWrapper</a> class, one can add objects to FoldingSets that were not originally designed to have that behavior.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
