---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantdatavector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConstantDataVector` Class Reference

<p>A vector constant whose element type is a simple 1/2/4/8-byte integer or float/double, and whose elements are just simple data values (i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantDataVector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> - A vector or array constant whose element type is a simple 1/2/4/8-byte integer or half/bfloat/float/double, and whose elements are just simple data values (i.e. <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74958cbd34e1860b1a7c946af159cbb4">ConstantDataSequential</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954ef382b0bde05a9833572852ec9c47">ConstantDataVector</a> (const ConstantDataVector &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2eae8e13aca6e4fffb9d8ed8bf80889">ConstantDataVector</a> (Type *ty, const char *Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b6d4272d7c6f16d6a614bc270f20ad">isSplat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a splat constant, meaning that all elements have the same value. <a href="#a71b6d4272d7c6f16d6a614bc270f20ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b66acacd6d23b2878904cf11f5d6ece">getSplatValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a splat constant, meaning that all of the elements have the same value, return that value. <a href="#a0b66acacd6d23b2878904cf11f5d6ece">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9244979dfbcb32adc9f628ac06a0c8">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize the <a href="#a8e9244979dfbcb32adc9f628ac06a0c8">getType()</a> method to always return a <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a>, which reduces the amount of casting needed in parts of the compiler. <a href="#a8e9244979dfbcb32adc9f628ac06a0c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a058e9e2e50ec5e02698c43b902bd5227">isSplatData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43f75125c61de872cac03bd9bd48596">IsSplatSet</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9630923990f7e256a3f6e43802c044f8">IsSplat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b693ee2fbb4c4173fa2725c110021b">get</a> (LLVMContext &amp;Context, ArrayRef&lt; uint8_t &gt; Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ab8b693ee2fbb4c4173fa2725c110021b">get()</a> constructors - Return a constant with vector type with an element count and element type matching the <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> passed in. <a href="#ab8b693ee2fbb4c4173fa2725c110021b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad360dbce483cc0903211b623b9debd">get</a> (LLVMContext &amp;Context, ArrayRef&lt; uint16_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5bc9cac664aeb67c181f9add7309cfa">get</a> (LLVMContext &amp;Context, ArrayRef&lt; uint32_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee97870547b76f8387091128a00e90c">get</a> (LLVMContext &amp;Context, ArrayRef&lt; uint64_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b15feb32345af4916487fa3fa9d6227">get</a> (LLVMContext &amp;Context, ArrayRef&lt; float &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79459acee890c44fac5c279584480b08">get</a> (LLVMContext &amp;Context, ArrayRef&lt; double &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074d013c7183283d9aaa8d7127057242">getRaw</a> (StringRef Data, uint64_t NumElements, Type *ElementTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a074d013c7183283d9aaa8d7127057242">getRaw()</a> constructor - Return a constant with vector type with an element count and element type matching the NumElements and ElementTy parameters passed in. <a href="#a074d013c7183283d9aaa8d7127057242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc193957138fece590fe07417912f018">getFP</a> (Type *ElementType, ArrayRef&lt; uint16_t &gt; Elts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#acc193957138fece590fe07417912f018">getFP()</a> constructors - Return a constant of vector type with a float element type taken from argument ‘ElementType`, and count taken from argument ‘Elts`. <a href="#acc193957138fece590fe07417912f018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeecde9516e68842cb97c340bb693a7a9">getFP</a> (Type *ElementType, ArrayRef&lt; uint32_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa736794cd9a0acefdb428c5ed892a66f">getFP</a> (Type *ElementType, ArrayRef&lt; uint64_t &gt; Elts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44124e702dc442346bd6202bb03e593b">getSplat</a> (unsigned NumElts, Constant *Elt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a> with the specified constant in each element. <a href="#a44124e702dc442346bd6202bb03e593b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a671fc05ed09910286bab6ce9e716f7">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a6a671fc05ed09910286bab6ce9e716f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A vector constant whose element type is a simple 1/2/4/8-byte integer or float/double, and whose elements are just simple data values (i.e.</p>


<p>ConstantInt/ConstantFP). This <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> node has no operands because it stores all of the elements of the constant as densely packed data, instead of as Value*'s.</p>


<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ConstantDataSequential {#a74958cbd34e1860b1a7c946af159cbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a74958cbd34e1860b1a7c946af159cbb4">ConstantDataSequential</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a74958cbd34e1860b1a7c946af159cbb4">ConstantDataSequential</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConstantDataVector() {#a954ef382b0bde05a9833572852ec9c47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantDataVector::ConstantDataVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantdatavector">ConstantDataVector</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantDataVector() {#ac2eae8e13aca6e4fffb9d8ed8bf80889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantDataVector::ConstantDataVector (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data)</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSplatValue() {#a0b66acacd6d23b2878904cf11f5d6ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::getSplatValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a splat constant, meaning that all of the elements have the same value, return that value.</p>


<p>Otherwise return NULL.</p>


<p>Declaration at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#ab1cf9198def27dfd719c425b1f9c5f50">llvm::ConstantDataSequential::getElementAsConstant</a> and <a href="#a71b6d4272d7c6f16d6a614bc270f20ad">isSplat</a>.</p>

</div>
</div>

### getType() {#a8e9244979dfbcb32adc9f628ac06a0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::ConstantDataVector::getType ()</td>
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

<p>Specialize the <a href="#a8e9244979dfbcb32adc9f628ac06a0c8">getType()</a> method to always return a <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a>, which reduces the amount of casting needed in parts of the compiler.</p>

<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### isSplat() {#a71b6d4272d7c6f16d6a614bc270f20ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantDataVector::isSplat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this is a splat constant, meaning that all elements have the same value.</p>

<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3237 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>Referenced by <a href="#a0b66acacd6d23b2878904cf11f5d6ece">getSplatValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isSplatData() {#a058e9e2e50ec5e02698c43b902bd5227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantDataVector::isSplatData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3225 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsSplat {#a9630923990f7e256a3f6e43802c044f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantDataVector::IsSplat</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### IsSplatSet {#ad43f75125c61de872cac03bd9bd48596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantDataVector::IsSplatSet</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a6a671fc05ed09910286bab6ce9e716f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantDataVector::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### get() {#ab8b693ee2fbb4c4173fa2725c110021b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Elts)</td>
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

<p><a href="#ab8b693ee2fbb4c4173fa2725c110021b">get()</a> constructors - Return a constant with vector type with an element count and element type matching the <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> passed in.</p>


<p>Note that this can return a <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> object.</p>


<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3007 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a44124e702dc442346bd6202bb03e593b">getSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d727a45696ad380a24b7fd8445182d8">LowerUINT_TO_FP_i64</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a62bf64531735d133d60ced4e7a4d4e03">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::makeAddAcquireOrderingTable</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9ecfbb98ae6069aa910e8aba30aca1d9">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::makeAddReleaseOrderingTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#ae0a656fd896bd17cb7c911a16ac2e4e4">rebuildConstant</a>.</p>

</div>
</div>

### get() {#a0ad360dbce483cc0903211b623b9debd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint16_t &gt; Elts)</td>
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



<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3012 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a87f56db834c58ca630624956ecf6972f">llvm::Type::getInt16Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### get() {#ae5bc9cac664aeb67c181f9add7309cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Elts)</td>
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



<p>Declaration at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3017 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### get() {#a8ee97870547b76f8387091128a00e90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Elts)</td>
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



<p>Declaration at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3022 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### get() {#a2b15feb32345af4916487fa3fa9d6227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; float &gt; Elts)</td>
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



<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3027 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### get() {#a79459acee890c44fac5c279584480b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; double &gt; Elts)</td>
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



<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3032 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getFP() {#acc193957138fece590fe07417912f018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::getFP (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint16_t &gt; Elts)</td>
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

<p><a href="#acc193957138fece590fe07417912f018">getFP()</a> constructors - Return a constant of vector type with a float element type taken from argument ‘ElementType`, and count taken from argument ‘Elts`.</p>


<p>The amount of bits of the contained type must match the number of bits of the type contained in the passed in <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>. (i.e. half or bfloat for 16bits, float for 32bits, double for 64bits) Note that this can return a <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> object.</p>


<p>Declaration at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3044 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a44124e702dc442346bd6202bb03e593b">getSplat</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#ae0a656fd896bd17cb7c911a16ac2e4e4">rebuildConstant</a>.</p>

</div>
</div>

### getFP() {#aeecde9516e68842cb97c340bb693a7a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::getFP (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; Elts)</td>
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



<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3052 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getFP() {#aa736794cd9a0acefdb428c5ed892a66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::getFP (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Elts)</td>
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



<p>Declaration at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3059 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getRaw() {#a074d013c7183283d9aaa8d7127057242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::ConstantDataVector::getRaw (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, uint64_t NumElements, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementTy)</td>
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

<p><a href="#a074d013c7183283d9aaa8d7127057242">getRaw()</a> constructor - Return a constant with vector type with an element count and element type matching the NumElements and ElementTy parameters passed in.</p>


<p>Note that this can return a <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> object. ElementTy must be one of i8/i16/i32/i64/half/bfloat/float/double. Data is the buffer containing the elements. Be careful to make sure Data uses the right endianness, the buffer will be used as-is.</p>


<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>.</p>

</div>
</div>

### getSplat() {#a44124e702dc442346bd6202bb03e593b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataVector::getSplat (unsigned NumElts, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Elt)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a> with the specified constant in each element.</p>


<p>The specified constant has to be a of a compatible type (i8/i16/ i32/i64/half/bfloat/float/double) and must be a <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> or <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a>.</p>


<p>Declaration at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3068 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a5bd16c2fbe755cda66b18d56761038ea">llvm::ConstantDataSequential::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab8b693ee2fbb4c4173fa2725c110021b">get</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#acc193957138fece590fe07417912f018">getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afdcd0a1d482f4048baba27f0bc051411">llvm::ConstantDataSequential::isElementTypeCompatible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
