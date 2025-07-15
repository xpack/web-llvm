---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sparsesetvaltraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SparseSetValTraits` Struct Template Reference

<p><a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits</a> - Objects in a <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> are identified by keys that can be uniquely converted to a small integer less than the set's universe. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ValueT&gt;
struct llvm::SparseSetValTraits&lt;ValueT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">llvm/ADT/SparseSet.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a933585c9ca05122d9fc6e234f3f3a212">getValIndex</a> (const ValueT &amp;Val)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits</a> - Objects in a <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> are identified by keys that can be uniquely converted to a small integer less than the set's universe.</p>


<p>This class allows the set to hold values that differ from the set's key type as long as an index can still be derived from the value. <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> never directly compares ValueT, only their indices, so it can map keys to arbitrary values. <a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits</a> computes the index from the value object. To compute the index from a key, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a> uses a separate KeyFunctorT template argument.</p>


<p>A simple type declaration, <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet&lt;Type&gt;</a>, handles these cases:</p>


<ul class="doxyList ">
<li>unsigned key, identity index, identity value</li>
<li>unsigned key, identity index, fat value providing getSparseSetIndex()</li>
</ul>

<p>The type declaration <a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet&lt;Type, UnaryFunction&gt;</a> handles:</p>


<ul class="doxyList ">
<li>unsigned key, remapped index, identity value (virtual registers)</li>
<li>pointer key, pointer-derived index, identity value (node+ID)</li>
<li>pointer key, pointer-derived index, fat value with getSparseSetIndex()</li>
</ul>

<p>Only other, unexpected cases require specializing <a href="/web-llvm/docs/api/structs/llvm/sparsesetvaltraits">SparseSetValTraits</a>.</p>


<p>For best results, ValueT should not require a destructor.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getValIndex() {#a933585c9ca05122d9fc6e234f3f3a212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SparseSetValTraits&lt; ValueT &gt;::getValIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ValueT &amp; Val)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/sparsesetvalfunctor/#a04a0c5526098b1af513719abb6c82823">llvm::SparseSetValFunctor&lt; KeyT, ValueT, KeyFunctorT &gt;::operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sparseset-h">SparseSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
