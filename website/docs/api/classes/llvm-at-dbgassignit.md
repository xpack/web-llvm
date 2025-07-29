---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/at/dbgassignit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbgAssignIt` Class

<p>High level: this is an iterator for llvm.dbg.assign intrinsics. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::at::DbgAssignIt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base">iterator_adaptor_base&lt;DerivedT, WrappedIteratorT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class for adapting an iterator to a different type. <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c32d576ac4917f4ee05f9667cb012d2">DbgAssignIt</a> (Value::user_iterator It)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic">DbgAssignIntrinsic</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad199a62007b3aef843aa6327ba8c6def">operator*</a> () const</td>
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

<p>High level: this is an iterator for llvm.dbg.assign intrinsics.</p>


<p>Implementation details: this is a wrapper around <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s <a href="/web-llvm/docs/api/classes/llvm/user">User</a> iterator that dereferences to a <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic">DbgAssignIntrinsic</a> ptr rather than a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> ptr.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgAssignIt() {#a8c32d576ac4917f4ee05f9667cb012d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::at::DbgAssignIt::DbgAssignIt (<a href="/web-llvm/docs/api/classes/llvm/value/#acd2fbee42afeb868be98aaae56528636">Value::user_iterator</a> It)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a8170d24cedaf5c2a22d8fc0c986529aa">llvm::iterator_adaptor_base&lt; DbgAssignIt, Value::user_iterator, std::iterator_traits&lt; Value::user_iterator &gt;::iterator_category, DbgAssignIntrinsic *, std::ptrdiff_t, DbgAssignIntrinsic **, DbgAssignIntrinsic *&amp; &gt;::iterator_adaptor_base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#ad199a62007b3aef843aa6327ba8c6def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgAssignIntrinsic * llvm::at::DbgAssignIt::operator* ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a563ec95255977c34566292cbdce193b3">llvm::iterator_adaptor_base&lt; DbgAssignIt, Value::user_iterator, std::iterator_traits&lt; Value::user_iterator &gt;::iterator_category, DbgAssignIntrinsic *, std::ptrdiff_t, DbgAssignIntrinsic **, DbgAssignIntrinsic *&amp; &gt;::I</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">DebugInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
