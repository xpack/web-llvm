---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/indexed-accessor-range
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `indexed_accessor_range` Class Template

<p>This class provides an implementation of a range of indexed_accessor_iterators where the base is not indexable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;
class llvm::indexed_accessor_range&lt;DerivedT, BaseT, T, PointerT, ReferenceT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">indexed_accessor_range_base&lt;DerivedT, BaseT, T, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The class represents the base of a range of indexed_accessor_iterators. <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a0cacfe0434b9b176d8c03062c3f9131f">indexed_accessor_range</a> (BaseT base, ptrdiff_t startIndex, ptrdiff_t count)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a328550129cecb95abafa217ab71904ab">getBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current base of the range. <a href="#a328550129cecb95abafa217ab71904ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ptrdiff_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f29791ad71a2ee8a9dc88182811088d">getStartIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current start index of the range. <a href="#a6f29791ad71a2ee8a9dc88182811088d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88b9f997a8e78fee022bb06dac0a7d11">offset_base</a> (const std::pair&lt; BaseT, ptrdiff_t &gt; &amp;base, ptrdiff_t index) -&gt; std::pair&lt; BaseT, ptrdiff_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">detail::indexed_accessor_range_base</a></span> for details. <a href="#a88b9f997a8e78fee022bb06dac0a7d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static ReferenceT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8822961359c270f3b14d35160e33ee3c">dereference_iterator</a> (const std::pair&lt; BaseT, ptrdiff_t &gt; &amp;base, ptrdiff_t index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">detail::indexed_accessor_range_base</a></span> for details. <a href="#a8822961359c270f3b14d35160e33ee3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides an implementation of a range of indexed_accessor_iterators where the base is not indexable.</p>


<p>Ranges with bases that are offsetable should derive from indexed_accessor_range_base instead. Derived range classes are expected to implement the following static method:</p>


<ul class="doxyList ">
<li>ReferenceT dereference(const BaseT &amp;base, ptrdiff_t index)

<ul class="doxyList ">
<li>Dereference an iterator pointing to a parent base at the given index.</li>
</ul></li>
</ul>

<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### indexed\_accessor\_range() {#a0cacfe0434b9b176d8c03062c3f9131f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::indexed_accessor_range&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::indexed_accessor_range (BaseT base, ptrdiff_t startIndex, ptrdiff_t count)</td>
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



<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::base</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#af9433a1702cda5c69423a7dc08171ab8">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#acf0f3d80cf8d7bc25c8b106554e68904">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::indexed_accessor_range_base</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBase() {#a328550129cecb95abafa217ab71904ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BaseT &amp; llvm::indexed_accessor_range&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getBase ()</td>
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

<p>Returns the current base of the range.</p>

<p>Definition at line 1404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::base</a>.</p>

</div>
</div>

### getStartIndex() {#a6f29791ad71a2ee8a9dc88182811088d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ptrdiff_t llvm::indexed_accessor_range&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::getStartIndex ()</td>
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

<p>Returns the current start index of the range.</p>

<p>Definition at line 1407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### dereference\_iterator() {#a8822961359c270f3b14d35160e33ee3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReferenceT llvm::indexed_accessor_range&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::dereference_iterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; BaseT, ptrdiff_t &gt; &amp; base, ptrdiff_t index)</td>
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

<p>See <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">detail::indexed_accessor_range_base</a></span> for details.</p>

<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::base</a>.</p>

</div>
</div>

### offset\_base() {#a88b9f997a8e78fee022bb06dac0a7d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename BaseT, typename T, typename PointerT = T *, typename ReferenceT = T &amp;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; BaseT, ptrdiff_t &gt; llvm::indexed_accessor_range&lt; DerivedT, BaseT, T, PointerT, ReferenceT &gt;::offset_base (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; BaseT, ptrdiff_t &gt; &amp; base, ptrdiff_t index)</td>
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

<p>See <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base">detail::indexed_accessor_range_base</a></span> for details.</p>

<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/detail/indexed-accessor-range-base/#afb143d573a4e41d3a8cac8ea071cf1cd">llvm::detail::indexed_accessor_range_base&lt; DerivedT, std::pair&lt; BaseT, ptrdiff_t &gt;, T, T *, T &amp; &gt;::base</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
