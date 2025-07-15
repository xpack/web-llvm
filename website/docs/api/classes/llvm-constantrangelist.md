---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantrangelist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstantRangeList` Class Reference

<p>This class represents a list of constant ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantRangeList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">llvm/IR/ConstantRangeList.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1226cc33da9186b9bb703fb6e6db55">ConstantRangeList</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff62ed88f20c152da1c550d77d1e559b">ConstantRangeList</a> (ArrayRef&lt; ConstantRange &gt; RangesRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35f47f7cb4b262333458939beb4597c">operator==</a> (const ConstantRangeList &amp;CRL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this range list is equal to another range list. <a href="#ae35f47f7cb4b262333458939beb4597c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09595da10a87c10beecd991df141867">operator!=</a> (const ConstantRangeList &amp;CRL) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61eefc2024082167d4176620bc3272c2">rangesRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5782c1e5b2fcad40ec713ab81f0655">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3192347e9ed06640b5a63f25bbd0f9">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;::const_iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2cbb63f36cb93feaa4efc375d42f2a">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;::const_iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437bcee0646cbd03fd420aff5e977443">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01de56edfbaf77ed1cd239fb9053a4b0">getRange</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad56085375ff21711ca97af4bb7ef44">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this list contains no members. <a href="#a5ad56085375ff21711ca97af4bb7ef44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061e91d5567bc9bafb0c39edf6e92532">getBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bit width of this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>. <a href="#a061e91d5567bc9bafb0c39edf6e92532">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7bb6ba03311ea7bb96234d8e366c385">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of ranges in this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>. <a href="#ab7bb6ba03311ea7bb96234d8e366c385">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1109f77d1d986c8e1e04f5da7ed197f9">insert</a> (const ConstantRange &amp;NewRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new range to Ranges and keep the list ordered. <a href="#a1109f77d1d986c8e1e04f5da7ed197f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a709fbe769536b93e127705651cdef5d0">insert</a> (int64_t Lower, int64_t Upper)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b446184a324d46a818d1d6c15d114a">subtract</a> (const ConstantRange &amp;SubRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad16e6a0c972042439d77b4a665f69d9f">unionWith</a> (const ConstantRangeList &amp;CRL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range list that results from the union of this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> with another <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>, "CRL". <a href="#ad16e6a0c972042439d77b4a665f69d9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca217062a175bb4f99a3416bcce120af">intersectWith</a> (const ConstantRangeList &amp;CRL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range list that results from the intersection of this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> with another <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>, "CRL". <a href="#aca217062a175bb4f99a3416bcce120af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f32bf88f0c95803ac134210308d54c">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print out the ranges to a stream. <a href="#a81f32bf88f0c95803ac134210308d54c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a56493540d0bd657d461e920a29de55">dump</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8825642a3532a0ca2b5d535cb715a046">Ranges</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb78ce0ad4d22082b130cd97900caa5d">isOrderedRanges</a> (ArrayRef&lt; ConstantRange &gt; RangesRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9752af795e1a5c9e192bbb481cb7828c">getConstantRangeList</a> (ArrayRef&lt; ConstantRange &gt; RangesRef)</td>
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

<p>This class represents a list of constant ranges.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConstantRangeList() {#aad1226cc33da9186b9bb703fb6e6db55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantRangeList::ConstantRangeList ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Referenced by <a href="#a9752af795e1a5c9e192bbb481cb7828c">getConstantRangeList</a>, <a href="#aca217062a175bb4f99a3416bcce120af">intersectWith</a>, <a href="#ad09595da10a87c10beecd991df141867">operator!=</a>, <a href="#ae35f47f7cb4b262333458939beb4597c">operator==</a> and <a href="#ad16e6a0c972042439d77b4a665f69d9f">unionWith</a>.</p>

</div>
</div>

### ConstantRangeList() {#aff62ed88f20c152da1c550d77d1e559b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantRangeList::ConstantRangeList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; RangesRef)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ad56085375ff21711ca97af4bb7ef44">empty</a>, <a href="#a061e91d5567bc9bafb0c39edf6e92532">getBitWidth</a> and <a href="#aeb78ce0ad4d22082b130cd97900caa5d">isOrderedRanges</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ad09595da10a87c10beecd991df141867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantRangeList::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> &amp; CRL)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>References <a href="#aad1226cc33da9186b9bb703fb6e6db55">ConstantRangeList</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp/#ad5db311411b09e79fcad62e7cee12e6b">operator==</a>.</p>

</div>
</div>

### operator==() {#ae35f47f7cb4b262333458939beb4597c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantRangeList::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> &amp; CRL)</td>
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

<p>Return true if this range list is equal to another range list.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Reference <a href="#aad1226cc33da9186b9bb703fb6e6db55">ConstantRangeList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a1e5782c1e5b2fcad40ec713ab81f0655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ConstantRange &gt;::iterator llvm::ConstantRangeList::begin ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>

</div>
</div>

### begin() {#a3e2cbb63f36cb93feaa4efc375d42f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ConstantRange &gt;::const_iterator llvm::ConstantRangeList::begin ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>.</p>

</div>
</div>

### dump() {#a0a56493540d0bd657d461e920a29de55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ConstantRangeList::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a81f32bf88f0c95803ac134210308d54c">print</a>.</p>

</div>
</div>

### empty() {#a5ad56085375ff21711ca97af4bb7ef44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantRangeList::empty ()</td>
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

<p>Return true if this list contains no members.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Referenced by <a href="#aff62ed88f20c152da1c550d77d1e559b">ConstantRangeList</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>, <a href="#a1109f77d1d986c8e1e04f5da7ed197f9">insert</a>, <a href="#aca217062a175bb4f99a3416bcce120af">intersectWith</a>, <a href="#a01b446184a324d46a818d1d6c15d114a">subtract</a> and <a href="#ad16e6a0c972042439d77b4a665f69d9f">unionWith</a>.</p>

</div>
</div>

### end() {#a5c3192347e9ed06640b5a63f25bbd0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ConstantRange &gt;::iterator llvm::ConstantRangeList::end ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>

</div>
</div>

### end() {#a437bcee0646cbd03fd420aff5e977443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ConstantRange &gt;::const_iterator llvm::ConstantRangeList::end ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>

</div>
</div>

### getBitWidth() {#a061e91d5567bc9bafb0c39edf6e92532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ConstantRangeList::getBitWidth ()</td>
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

<p>Get the bit width of this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>.</p>


<p>It is invalid to call this with an empty range.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Referenced by <a href="#aff62ed88f20c152da1c550d77d1e559b">ConstantRangeList</a>, <a href="#a1109f77d1d986c8e1e04f5da7ed197f9">insert</a>, <a href="#aca217062a175bb4f99a3416bcce120af">intersectWith</a>, <a href="#a01b446184a324d46a818d1d6c15d114a">subtract</a> and <a href="#ad16e6a0c972042439d77b4a665f69d9f">unionWith</a>.</p>

</div>
</div>

### getRange() {#a01de56edfbaf77ed1cd239fb9053a4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ConstantRangeList::getRange (unsigned i)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>

</div>
</div>

### insert() {#a1109f77d1d986c8e1e04f5da7ed197f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantRangeList::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; NewRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new range to Ranges and keep the list ordered.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a5ad56085375ff21711ca97af4bb7ef44">empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad7f81241f958a1f5917a3410942d3199">llvm::ConstantRange::getBitWidth</a>, <a href="#a061e91d5567bc9bafb0c39edf6e92532">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e8226e6453c8bcf7e5c06d28b1e207b">llvm::APInt::sle</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a> and <a href="#a709fbe769536b93e127705651cdef5d0">insert</a>.</p>

</div>
</div>

### insert() {#a709fbe769536b93e127705651cdef5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ConstantRangeList::insert (int64_t Lower, int64_t Upper)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>References <a href="#a1109f77d1d986c8e1e04f5da7ed197f9">insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>

</div>
</div>

### intersectWith() {#aca217062a175bb4f99a3416bcce120af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRangeList ConstantRangeList::intersectWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> &amp; CRL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the range list that results from the intersection of this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> with another <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>, "CRL".</p>

<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aad1226cc33da9186b9bb703fb6e6db55">ConstantRangeList</a>, <a href="#a5ad56085375ff21711ca97af4bb7ef44">empty</a>, <a href="#a061e91d5567bc9bafb0c39edf6e92532">getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#ab7bb6ba03311ea7bb96234d8e366c385">size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a688eca8fbe6295f4b002f1e705d3e916">llvm::APIntOps::smin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ae6155da930181ded60bf9106eccec2b0">anonymous{DeadStoreElimination.cpp}::getIntersectedInitRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a45a64ff2883d51edeb926ee63a4f64ac">llvm::MDNode::getMostGenericNoaliasAddrspace</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>.</p>

</div>
</div>

### print() {#a81f32bf88f0c95803ac134210308d54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantRangeList::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print out the ranges to a stream.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3b4daeeeabc6cdcff5627aace66de8a3">llvm::interleaveComma</a>.</p>


<p>Referenced by <a href="#a0a56493540d0bd657d461e920a29de55">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>.</p>

</div>
</div>

### rangesRef() {#a61eefc2024082167d4176620bc3272c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ConstantRange &gt; llvm::ConstantRangeList::rangesRef ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>.</p>

</div>
</div>

### size() {#ab7bb6ba03311ea7bb96234d8e366c385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ConstantRangeList::size ()</td>
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

<p>Return the number of ranges in this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>


<p>Referenced by <a href="#aca217062a175bb4f99a3416bcce120af">intersectWith</a> and <a href="#ad16e6a0c972042439d77b4a665f69d9f">unionWith</a>.</p>

</div>
</div>

### subtract() {#a01b446184a324d46a818d1d6c15d114a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantRangeList::subtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; SubRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ad56085375ff21711ca97af4bb7ef44">empty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad7f81241f958a1f5917a3410942d3199">llvm::ConstantRange::getBitWidth</a>, <a href="#a061e91d5567bc9bafb0c39edf6e92532">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae2b7d8c018c8a37fa8ea422a13bfd412">llvm::APInt::sge</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e8226e6453c8bcf7e5c06d28b1e207b">llvm::APInt::sle</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>.</p>

</div>
</div>

### unionWith() {#ad16e6a0c972042439d77b4a665f69d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRangeList ConstantRangeList::unionWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> &amp; CRL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the range list that results from the union of this <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> with another <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a>, "CRL".</p>

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aad1226cc33da9186b9bb703fb6e6db55">ConstantRangeList</a>, <a href="#a5ad56085375ff21711ca97af4bb7ef44">empty</a>, <a href="#a061e91d5567bc9bafb0c39edf6e92532">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>, <a href="#ab7bb6ba03311ea7bb96234d8e366c385">size</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ranges {#a8825642a3532a0ca2b5d535cb715a046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ConstantRange, 2&gt; llvm::ConstantRangeList::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getConstantRangeList() {#a9752af795e1a5c9e192bbb481cb7828c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRangeList &gt; ConstantRangeList::getConstantRangeList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; RangesRef)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="#aad1226cc33da9186b9bb703fb6e6db55">ConstantRangeList</a> and <a href="#aeb78ce0ad4d22082b130cd97900caa5d">isOrderedRanges</a>.</p>

</div>
</div>

### isOrderedRanges() {#aeb78ce0ad4d22082b130cd97900caa5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantRangeList::isOrderedRanges (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; RangesRef)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#aff62ed88f20c152da1c550d77d1e559b">ConstantRangeList</a> and <a href="#a9752af795e1a5c9e192bbb481cb7828c">getConstantRangeList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">ConstantRangeList.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constantrangelist-cpp">ConstantRangeList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
