---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-settheory-cpp-/sequenceop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SequenceOp` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{SetTheory.cpp}::SequenceOp { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7a266e9600285cf4d964d18790e9ce">apply</a> (SetTheory &amp;ST, const DagInit *Expr, RecSet &amp;Elts, ArrayRef&lt; SMLoc &gt; Loc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>apply - Apply this operator to Expr's arguments and insert the result in Elts. <a href="#aca7a266e9600285cf4d964d18790e9ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### apply() {#aca7a266e9600285cf4d964d18790e9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SetTheory.cpp}::SequenceOp::apply (<a href="/web-llvm/docs/api/classes/llvm/settheory">SetTheory</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/daginit">DagInit</a> * Expr, <a href="/web-llvm/docs/api/namespaces/anonymous-settheory-cpp-/#a7bb4cdf28f18d7ab5d42f0ab3f7e32f4">RecSet</a> &amp; Elts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; Loc)</td>
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

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/daginit/#a3d4a644883755522c1704e7723081dd3">llvm::DagInit::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#aad7499a93d0fd38b9875c8bee6f44713">llvm::DagInit::arg_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#af2a7d55b296392d5ed5ae25c769503c6">llvm::DagInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a72f75c3a5b886e7861b0ee2bdc31cf5f">llvm::DagInit::getOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
