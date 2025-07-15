---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/smallvectorstorage-0583cbbb8abe86209428c1b11d13655f
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SmallVectorStorage` Struct Template Reference

<p>We need the storage to be properly aligned even for small-size of 0 so that the pointer math in <em><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aff209a96323a14068980fd74f1fa53df">SmallVectorTemplateCommon::getFirstEl()</a></em> is well-defined. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::SmallVectorStorage&lt;T, 0&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallvectorstorage/#a5e902e1a2df8694a6b0609906f0f04b4">InlineElts</a>[N *sizeof(T)]</td>
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

<p>We need the storage to be properly aligned even for small-size of 0 so that the pointer math in <em><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aff209a96323a14068980fd74f1fa53df">SmallVectorTemplateCommon::getFirstEl()</a></em> is well-defined.</p>

<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### InlineElts {#a5e902e1a2df8694a6b0609906f0f04b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::SmallVectorStorage&lt; T, N &gt;::InlineElts[N *sizeof(T)]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
