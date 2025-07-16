---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-scalarizer-cpp-/binarysplitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BinarySplitter` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{Scalarizer.cpp}::BinarySplitter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec2de8c978fa6ad2dd0db6244ba8e3e8">BinarySplitter</a> (BinaryOperator &amp;bo)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353459bb5dd067533ec643c7fefd4159">operator()</a> (IRBuilder&lt;&gt; &amp;Builder, Value *Op0, Value *Op1, const Twine &amp;Name) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff73296692dc548767da45a1b04bd7a">BO</a></td>
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


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizer-cpp">Scalarizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinarySplitter() {#aec2de8c978fa6ad2dd0db6244ba8e3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{Scalarizer.cpp}::BinarySplitter::BinarySplitter (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; bo)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizer-cpp">Scalarizer.cpp</a>.</p>


<p>Reference <a href="#adff73296692dc548767da45a1b04bd7a">BO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a353459bb5dd067533ec643c7fefd4159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{Scalarizer.cpp}::BinarySplitter::operator() (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizer-cpp">Scalarizer.cpp</a>.</p>


<p>References <a href="#adff73296692dc548767da45a1b04bd7a">BO</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BO {#adff73296692dc548767da45a1b04bd7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOperator&amp; anonymous{Scalarizer.cpp}::BinarySplitter::BO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizer-cpp">Scalarizer.cpp</a>.</p>


<p>Referenced by <a href="#aec2de8c978fa6ad2dd0db6244ba8e3e8">BinarySplitter</a> and <a href="#a353459bb5dd067533ec643c7fefd4159">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizer-cpp">Scalarizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
