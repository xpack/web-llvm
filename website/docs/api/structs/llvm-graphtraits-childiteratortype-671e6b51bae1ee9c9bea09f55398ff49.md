---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/graphtraits/childiteratortype-671e6b51bae1ee9c9bea09f55398ff49
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ChildIteratorType` Struct Template Reference

<p>Add the VectorizableTree to the index iterator to be able to return <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a7ceeff5a65c10abe289db52446ac088a">TreeEntry</a> pointers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::GraphTraits::ChildIteratorType&lt;BoUpSLP * &gt;::ChildIteratorType { ... }
</div>

## Base struct

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa709fbae8ecf0c4d40fdbbcd1a37114f">ChildIteratorType</a> (SmallVector&lt; BoUpSLP::EdgeInfo, 1 &gt;::iterator W, ContainerTy &amp;VT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a55cdb660a488b62f949a57dc65f5296e">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078cde4ddd868aff68189c7b4fe56f00">operator*</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#aba5049d783b8594ef0a36b6c1d1a973b">ContainerTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5f85f0c5276e1cc3a9bcee214ab81e">VectorizableTree</a></td>
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

<p>Add the VectorizableTree to the index iterator to be able to return <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a7ceeff5a65c10abe289db52446ac088a">TreeEntry</a> pointers.</p>

<p>Definition at line 4441 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ChildIteratorType() {#aa709fbae8ecf0c4d40fdbbcd1a37114f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GraphTraits&lt; BoUpSLP * &gt;::ChildIteratorType::ChildIteratorType (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo">BoUpSLP::EdgeInfo</a>, 1 &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> W, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#aba5049d783b8594ef0a36b6c1d1a973b">ContainerTy</a> &amp; VT)</td>
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



<p>Definition at line 4446 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="#aa709fbae8ecf0c4d40fdbbcd1a37114f">ChildIteratorType</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a8170d24cedaf5c2a22d8fc0c986529aa">llvm::iterator_adaptor_base&lt; ChildIteratorType, SmallVector&lt; BoUpSLP::EdgeInfo, 1 &gt;::iterator &gt;::iterator_adaptor_base</a> and <a href="#afd5f85f0c5276e1cc3a9bcee214ab81e">VectorizableTree</a>.</p>


<p>Referenced by <a href="#aa709fbae8ecf0c4d40fdbbcd1a37114f">ChildIteratorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#a078cde4ddd868aff68189c7b4fe56f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::GraphTraits&lt; BoUpSLP * &gt;::ChildIteratorType::operator* ()</td>
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



<p>Definition at line 4450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a563ec95255977c34566292cbdce193b3">llvm::iterator_adaptor_base&lt; ChildIteratorType, SmallVector&lt; BoUpSLP::EdgeInfo, 1 &gt;::iterator &gt;::I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### VectorizableTree {#afd5f85f0c5276e1cc3a9bcee214ab81e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContainerTy&amp; llvm::GraphTraits&lt; BoUpSLP * &gt;::ChildIteratorType::VectorizableTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4444 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#aa709fbae8ecf0c4d40fdbbcd1a37114f">ChildIteratorType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
