---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/calculatesmallvectordefaultinlinedelements
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CalculateSmallVectorDefaultInlinedElements` Struct Template Reference

<p>Helper class for calculating the default number of inline elements for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt;T&gt;</span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::CalculateSmallVectorDefaultInlinedElements&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
</div>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a322876b665b12084a3401951797b440e">kPreferredSmallVectorSizeof</a> = 64</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adebf52e29c244776b4747cb57ec94290">PreferredInlineBytes</a> = ...</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add4da5518b19db6e0bdf69e7972cb7e3">NumElementsThatFit</a> = <a href="#adebf52e29c244776b4747cb57ec94290">PreferredInlineBytes</a> / sizeof(T)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a737320006b419bc7865600d50e558017">value</a> = ...</td>
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

<p>Helper class for calculating the default number of inline elements for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt;T&gt;</span>.</p>


<p>This should be migrated to a constexpr function when our minimum compiler support is enough for multi-statement constexpr functions.</p>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<div class="doxySectionDef">

## Public Static Attributes

### kPreferredSmallVectorSizeof {#a322876b665b12084a3401951797b440e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::CalculateSmallVectorDefaultInlinedElements&lt; T &gt;::kPreferredSmallVectorSizeof = 64</td>
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



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### NumElementsThatFit {#add4da5518b19db6e0bdf69e7972cb7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::CalculateSmallVectorDefaultInlinedElements&lt; T &gt;::NumElementsThatFit = <a href="#adebf52e29c244776b4747cb57ec94290">PreferredInlineBytes</a> / sizeof(T)</td>
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



<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### PreferredInlineBytes {#adebf52e29c244776b4747cb57ec94290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::CalculateSmallVectorDefaultInlinedElements&lt; T &gt;::PreferredInlineBytes</td>
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
      <a href="#a322876b665b12084a3401951797b440e">kPreferredSmallVectorSizeof</a> - sizeof(<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt;T, 0&gt;)
</div>
</dd>
</dl>

<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### value {#a737320006b419bc7865600d50e558017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::CalculateSmallVectorDefaultInlinedElements&lt; T &gt;::value</td>
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
      <a href="#add4da5518b19db6e0bdf69e7972cb7e3">NumElementsThatFit</a> == 0 ? 1 : <a href="#add4da5518b19db6e0bdf69e7972cb7e3">NumElementsThatFit</a>
</div>
</dd>
</dl>

<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
