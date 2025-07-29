---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sparsesetvalfunctor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SparseSetValFunctor` Struct Template

<p><a href="/web-llvm/docs/api/structs/llvm/sparsesetvalfunctor">SparseSetValFunctor</a> - Helper class for selecting <a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValueT, typename KeyFunctorT&gt;
struct llvm::SparseSetValFunctor&lt;KeyT, ValueT, KeyFunctorT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">llvm/ADT/SparseSet.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename KeyFunctorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04a0c5526098b1af513719abb6c82823">operator()</a> (const ValueT &amp;Val) const</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/sparsesetvalfunctor">SparseSetValFunctor</a> - Helper class for selecting <a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits</a>.</p>


<p>The generic implementation handles ValueT classes which either provide getSparseSetIndex() or specialize <a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits&lt;&gt;</a>.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#a04a0c5526098b1af513719abb6c82823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename KeyFunctorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseSetValFunctor&lt; KeyT, ValueT, KeyFunctorT &gt;::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp; Val)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits/#a933585c9ca05122d9fc6e234f3f3a212">llvm::SparseSetValTraits&lt; ValueT &gt;::getValIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
