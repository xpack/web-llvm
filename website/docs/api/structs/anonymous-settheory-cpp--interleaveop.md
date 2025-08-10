---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-settheory-cpp-/interleaveop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InterleaveOp` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{SetTheory.cpp}::InterleaveOp { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/settheory/operator">Operator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/settheory/operator">Operator</a> - A callback representing a DAG operator. <a href="/web-llvm/docs/api/classes/llvm/settheory/operator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87ac8424a0fc3954cea34e45059f9ac">apply</a> (SetTheory &amp;ST, const DagInit *Expr, RecSet &amp;Elts, ArrayRef&lt; SMLoc &gt; Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>apply - Apply this operator to Expr's arguments and insert the result in Elts. <a href="#ac87ac8424a0fc3954cea34e45059f9ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### apply() {#ac87ac8424a0fc3954cea34e45059f9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SetTheory.cpp}::InterleaveOp::apply (<a href="/web-llvm/docs/api/classes/llvm/settheory">SetTheory</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/daginit">DagInit</a> * Expr, <a href="/web-llvm/docs/api/namespaces/anonymous-settheory-cpp-/#a7bb4cdf28f18d7ab5d42f0ab3f7e32f4">RecSet</a> &amp; Elts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; Loc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>apply - Apply this operator to Expr's arguments and insert the result in Elts.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/daginit/#af0faf7207f3f675ea46a190d3c8a3003">llvm::DagInit::getArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a1a9157bc668269d337209788f161ef43">llvm::DagInit::getNumArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
