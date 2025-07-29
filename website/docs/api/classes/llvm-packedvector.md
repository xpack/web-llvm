---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/packedvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PackedVector` Class Template

<p>Store a vector of values using a specific number of bits for each value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;
class llvm::PackedVector&lt;T, BitNum, BitVectorTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">llvm/ADT/PackedVector.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/packedvectorbase">PackedVectorBase&lt;T, BitNum, BitVectorTy, isSigned&gt;</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab327bdefcfd3adb9fdf4370361908d1f">base</a> = <a href="/web-llvm/docs/api/classes/llvm/packedvectorbase">PackedVectorBase</a>&lt; T, BitNum, BitVectorTy, std::numeric_limits&lt; T &gt;::is_signed &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3849acfead17a2212a7142f1811af9f2">PackedVector</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a568055fe0aa5bf88a42c331efd01ce4f">PackedVector</a> (unsigned size)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/packedvector/reference">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe5d640cd9f071d9b9db2956f669f1b0">operator[]</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a520a38a386a83dc53b0baecc3aaeddac">operator[]</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbe369dda7eb08d0ad77eb2f44ff5c4f">operator==</a> (const PackedVector &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5c0d70a0e4f75deef5c240a54f138ac">operator!=</a> (const PackedVector &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/packedvector">PackedVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9cb3c9f0ee92ff517974e80fb53e818f">operator|=</a> (const PackedVector &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27f159234a1da3bb5b24d03ec582c1f8">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a336dace215be3ec31708bcb8cf54c71a">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a65d46594f698c99bab030a16c3fb38b6">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0856c7e0322e026ec7b88979656506a5">resize</a> (unsigned N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2779b3b1858a954e442e4219d1707d5">reserve</a> (unsigned N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/packedvector">PackedVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a18299dc6e8c75bbaa5878c11e2a98229">reset</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88d18e9d7dc76b67787d24f34b401d8f">push_back</a> (T val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BitVectorTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09debebb8aa63e7467c6775788111cff">raw_bits</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BitVectorTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a995393948fbcae4b33f6f9eb77878654">raw_bits</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BitVectorTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee44a13d1dda5c189a43e17e198f2e52">Bits</a></td>
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

<p>Store a vector of values using a specific number of bits for each value.</p>


<p>Both signed and unsigned types can be used, e.g</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a3849acfead17a2212a7142f1811af9f2">PackedVector&lt;signed, 2&gt;</a> vec;</span></span></div>

</div>


<p>will create a vector accepting values -2, -1, 0, 1. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> other value will hit an assertion.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### base {#ab327bdefcfd3adb9fdf4370361908d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::base =  PackedVectorBase&lt;T, BitNum, BitVectorTy,
                                std::numeric_limits&lt;T&gt;::is_signed&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PackedVector() {#a3849acfead17a2212a7142f1811af9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>Referenced by <a href="#ab5c0d70a0e4f75deef5c240a54f138ac">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator!=</a>, <a href="#afbe369dda7eb08d0ad77eb2f44ff5c4f">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator==</a>, <a href="#a9cb3c9f0ee92ff517974e80fb53e818f">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator|=</a>, <a href="/web-llvm/docs/api/classes/llvm/packedvector/reference/#a68b96bd55519b156c0024803de5b3c25">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reference::reference</a> and <a href="#a18299dc6e8c75bbaa5878c11e2a98229">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reset</a>.</p>

</div>
</div>

### PackedVector() {#a568055fe0aa5bf88a42c331efd01ce4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector (unsigned size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>Reference <a href="#a336dace215be3ec31708bcb8cf54c71a">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ab5c0d70a0e4f75deef5c240a54f138ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/packedvector">PackedVector</a> &amp; RHS)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>References <a href="#a3849acfead17a2212a7142f1811af9f2">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\[\]() {#afe5d640cd9f071d9b9db2956f669f1b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator[] (unsigned Idx)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

### operator\[\]() {#a520a38a386a83dc53b0baecc3aaeddac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator[] (unsigned Idx)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### operator==() {#afbe369dda7eb08d0ad77eb2f44ff5c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/packedvector">PackedVector</a> &amp; RHS)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>References <a href="#a3849acfead17a2212a7142f1811af9f2">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|=() {#a9cb3c9f0ee92ff517974e80fb53e818f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedVector &amp; llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/packedvector">PackedVector</a> &amp; RHS)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>References <a href="#a3849acfead17a2212a7142f1811af9f2">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a65d46594f698c99bab030a16c3fb38b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::clear ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

### empty() {#a27f159234a1da3bb5b24d03ec582c1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::empty ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

### push\_back() {#a88d18e9d7dc76b67787d24f34b401d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::push_back (T val)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>References <a href="#a0856c7e0322e026ec7b88979656506a5">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::resize</a>, <a href="#a336dace215be3ec31708bcb8cf54c71a">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### raw\_bits() {#a09debebb8aa63e7467c6775788111cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVectorTy &amp; llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::raw_bits ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

### raw\_bits() {#a995393948fbcae4b33f6f9eb77878654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVectorTy &amp; llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::raw_bits ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

### reserve() {#af2779b3b1858a954e442e4219d1707d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reserve (unsigned N)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### reset() {#a18299dc6e8c75bbaa5878c11e2a98229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedVector &amp; llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reset ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>References <a href="#a3849acfead17a2212a7142f1811af9f2">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector</a> and <a href="#a18299dc6e8c75bbaa5878c11e2a98229">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reset</a>.</p>


<p>Referenced by <a href="#a18299dc6e8c75bbaa5878c11e2a98229">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reset</a>.</p>

</div>
</div>

### resize() {#a0856c7e0322e026ec7b88979656506a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::resize (unsigned N)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a88d18e9d7dc76b67787d24f34b401d8f">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::push_back</a>.</p>

</div>
</div>

### size() {#a336dace215be3ec31708bcb8cf54c71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::size ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>


<p>Referenced by <a href="#a568055fe0aa5bf88a42c331efd01ce4f">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::PackedVector</a> and <a href="#a88d18e9d7dc76b67787d24f34b401d8f">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bits {#aee44a13d1dda5c189a43e17e198f2e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned BitNum, typename BitVectorTy = BitVector&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVectorTy llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::Bits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/packedvector-h">PackedVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
