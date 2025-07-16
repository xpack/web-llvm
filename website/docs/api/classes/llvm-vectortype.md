---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vectortype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VectorType` Class Reference

<p>Base class of all SIMD vector types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VectorType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instances of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> class are immutable: once they are created, they are never changed. <a href="/web-llvm/docs/api/classes/llvm/type/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent fixed width SIMD vectors. <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to represent scalable SIMD vectors. <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbaf5917f79cb3c212376546623d93f9">VectorType</a> (const VectorType &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a> (Type *ElType, unsigned EQ, Type::TypeID TID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f7b2f19953adbf5e5db61ac8ffa141">operator=</a> (const VectorType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdce715c901d62e2c1367a0ff5248175">getElementType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> instance to represent the (possibly scalable) number of elements in the vector. <a href="#a59632c5deb0423a518ad984bdd04d41f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9531bece2eddd17e21a9fd250fcbe50a">ElementQuantity</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The element quantity of this vector. <a href="#a9531bece2eddd17e21a9fd250fcbe50a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e45eba39500cdd8464942a294925dc">ContainedType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A fully specified <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> is of the form &lt;vscale x n x Ty&gt;. <a href="#ad4e45eba39500cdd8464942a294925dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a861be1e2092622462053c6d31dddbfd5">get</a> (Type *ElementType, ElementCount EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is the primary way to construct an <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a>. <a href="#a861be1e2092622462053c6d31dddbfd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2bc88fa949977374572b32de0224b03">get</a> (Type *ElementType, unsigned NumElements, bool Scalable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a937399ee5b5885ffc2d7355ae96eda">get</a> (Type *ElementType, const VectorType *Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781c723920fb1d098c4d959f3218d9aa">getInteger</a> (VectorType *VTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method gets a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> with the same number of elements as the input type, and the element type is an integer type of the same width as the input element type. <a href="#a781c723920fb1d098c4d959f3218d9aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1f5f847d812d85eaaa8a19bd01bcf4">getExtendedElementVectorType</a> (VectorType *VTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is like getInteger except that the element types are twice as wide as the elements in the input type. <a href="#a3b1f5f847d812d85eaaa8a19bd01bcf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">getTruncatedElementVectorType</a> (VectorType *VTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62425c077bf32e483e2e041e26bce530">getSubdividedVectorType</a> (VectorType *VTy, int NumSubdivs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12589d52afe7ea72485b0a431327a6e6">getHalfElementsVectorType</a> (VectorType *VTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method returns a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> with half as many elements as the input type and the same element type. <a href="#a12589d52afe7ea72485b0a431327a6e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac423a4165a8f57cd2865ef33dd9be484">getDoubleElementsVectorType</a> (VectorType *VTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method returns a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> with twice as many elements as the input type and the same element type. <a href="#ac423a4165a8f57cd2865ef33dd9be484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a2194fc011669faabe43322d7c6c5f">isValidElementType</a> (Type *ElemTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified type is valid as a element type. <a href="#aa6a2194fc011669faabe43322d7c6c5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433e8d0e9a8db766b9a458f18b11b7c1">classof</a> (const Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#a433e8d0e9a8db766b9a458f18b11b7c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class of all SIMD vector types.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VectorType() {#afbaf5917f79cb3c212376546623d93f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VectorType::VectorType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> &amp;)</td>
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



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### VectorType() {#a302dbb3a7c0b1d6c35d76d3caaf4a6ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType::VectorType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElType, unsigned EQ, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbda">Type::TypeID</a> TID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#aaf26ea4a39f2089bc1a4ef1d9aa9f8f0">llvm::FixedVectorType::FixedVectorType</a>, <a href="#a9a937399ee5b5885ffc2d7355ae96eda">get</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="#af2bc88fa949977374572b32de0224b03">get</a>, <a href="#ac423a4165a8f57cd2865ef33dd9be484">getDoubleElementsVectorType</a>, <a href="#a3b1f5f847d812d85eaaa8a19bd01bcf4">getExtendedElementVectorType</a>, <a href="#a12589d52afe7ea72485b0a431327a6e6">getHalfElementsVectorType</a>, <a href="#a781c723920fb1d098c4d959f3218d9aa">getInteger</a>, <a href="#a62425c077bf32e483e2e041e26bce530">getSubdividedVectorType</a>, <a href="#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">getTruncatedElementVectorType</a>, <a href="#aa6f7b2f19953adbf5e5db61ac8ffa141">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#ad291d76727438314ed23080b0eb88422">llvm::ScalableVectorType::ScalableVectorType</a> and <a href="#afbaf5917f79cb3c212376546623d93f9">VectorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aa6f7b2f19953adbf5e5db61ac8ffa141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType &amp; llvm::VectorType::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> &amp;)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getElementCount() {#a59632c5deb0423a518ad984bdd04d41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount VectorType::getElementCount ()</td>
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

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> instance to represent the (possibly scalable) number of elements in the vector.</p>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#a9531bece2eddd17e21a9fd250fcbe50a">ElementQuantity</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectinst/#abd9356b1c3a69a55b72df590c48f9738">llvm::SelectInst::areInvalidOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8f832cfa0e0121c6fd066c0f3b25f5f">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertToOptType</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a19aa4af9c02f8e3571cc82c0634a25f6">llvm::VPHistogramRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a713bb53f77454635f44dd95c53fc8684">llvm::TargetTransformInfo::getArithmeticInstrCost</a>, <a href="#ac423a4165a8f57cd2865ef33dd9be484">getDoubleElementsVectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="#a3b1f5f847d812d85eaaa8a19bd01bcf4">getExtendedElementVectorType</a>, <a href="#a12589d52afe7ea72485b0a431327a6e6">getHalfElementsVectorType</a>, <a href="#a781c723920fb1d098c4d959f3218d9aa">getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a365f29ab21721393fe82ff3ae4554e5e">llvm::AArch64TargetLowering::getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3dddf52f700258ac37fa137527588809">llvm::SPIRVGlobalRegistry::getOrCreateConsIntVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a005211a6c7f26317af98d088c06f0f64">llvm::AArch64TTIImpl::getSpliceCost</a>, <a href="#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a85764bb37db07737ed0058c352f4c3b7">llvm::AArch64TargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a2bff55a07291d47843ff3e4a1548c154">llvm::fuzzerop::matchFirstLengthWAnyType</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a0b50be89487f7186a5eb7ff1bc82efc0">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapVector</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>.</p>

</div>
</div>

### getElementType() {#afdce715c901d62e2c1367a0ff5248175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::VectorType::getElementType ()</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvegatherscatterlowering-cpp/#a7393bb18a6b67be8b26127bd4aab0cd4">CheckAndCreateOffsetAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ad60130f0b45a3ff1e759b010afefb94d">anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a7d0da22d172cf90028dcf5fdc8ff2cb8">anonymous{ConstantFolding.cpp}::constantFoldVectorReduce</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a40a1fc4e57a69c562fb3d215eaa71280">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertBlendvToSelectMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae919aab2dcdca2fcb21214e33822c838">createTblShuffleForSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a93cdde383eeeb3fb45851d9660891a5f">createTblShuffleForZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a01aa2c4724ae9bf421d1cfff3a1c7fa5">foldConstantInsEltIntoShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="#ac423a4165a8f57cd2865ef33dd9be484">getDoubleElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ae3f468d365ecf76cd72b905bbaaa30c8">llvm::sandboxir::VectorType::getElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="#a3b1f5f847d812d85eaaa8a19bd01bcf4">getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a28ddde70a914cfd132fb68eb75c22630">llvm::AArch64TTIImpl::getExtractWithExtendCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1bff2054cf087e413f78d2a682a65493">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getExtractWithExtendCost</a>, <a href="#a12589d52afe7ea72485b0a431327a6e6">getHalfElementsVectorType</a>, <a href="#a781c723920fb1d098c4d959f3218d9aa">getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a04b3a69fabb49a792bdd785030325f89">llvm::HexagonTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a16a2910025aeadfd52f381a78f92faf0">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getNumberOfParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a365f29ab21721393fe82ff3ae4554e5e">llvm::AArch64TargetLowering::getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3dddf52f700258ac37fa137527588809">llvm::SPIRVGlobalRegistry::getOrCreateConsIntVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a22615a6ebaa0232be4b70be555bf0690">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getOrderedReductionCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aac05ca292709f88f6ba0ae241e0e84bf">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowOriginPtrUserspace</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#aefd2591b1c59fbc42ad11361b7e23518">llvm::GCNTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a127b3dcb8a8e72d985c53454b7b1f72c">getSVEContainerIRType</a>, <a href="#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a85764bb37db07737ed0058c352f4c3b7">llvm::AArch64TargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac9518b8cf085f38ae07134937ad85d31">llvm::ARMTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a1098ae5256eef51d3c36449fab39b0ba">llvm::X86TTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup/#ae769158e04d7d2df19b436d90e02bb85">anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::isSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aa602c4415d92f7060b1c0f1255fcf79d">isSupportedAccessType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a822917bc16eaefe906d8b1f968572a14">isV2BF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af48841917cf8f6f2ebf633b63cec48fb">isV2F16</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aadb2a52a94fd7cf1e3f1643e0f5e2934">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerTranspose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8ef0473fe81ed643d4fe2e64c6a5b3e">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::shouldReplace</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aef67bcdb0247f9b4b984725fa065e1ce">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitPHINode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ElementQuantity {#a9531bece2eddd17e21a9fd250fcbe50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::VectorType::ElementQuantity</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The element quantity of this vector.</p>


<p>The meaning of this value depends on the type of vector:</p>


<ul class="doxyList ">
<li>For <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> = &lt;ElementQuantity x ty&gt;, there are exactly ElementQuantity elements in this vector.</li>
<li>For <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype">ScalableVectorType</a> = &lt;vscale x ElementQuantity x ty&gt;, there are vscale * ElementQuantity elements in this vector, where vscale is a runtime-constant integer greater than 0.</li>
</ul>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Referenced by <a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#aa7473a4e5eb5a49846c0c161a5e56d2a">llvm::ScalableVectorType::getMinNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ContainedType {#ad4e45eba39500cdd8464942a294925dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::VectorType::ContainedType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A fully specified <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> is of the form &lt;vscale x n x Ty&gt;.</p>


<p>'n' is the minimum number of elements of type Ty contained within the vector, and 'vscale x' indicates that the total element count is an integer multiple of 'n', where the multiple is either guaranteed to be one, or is statically unknown at compile time.</p>


<p>If the multiple is known to be 1, then the extra term is discarded in textual IR:</p>


<p>&lt;4 x i32&gt; - a vector containing 4 i32s &lt;vscale x 4 x i32&gt; - a vector containing an unknown integer multiple of 4 i32s The element type of the vector.</p>


<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a433e8d0e9a8db766b9a458f18b11b7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VectorType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### get() {#a861be1e2092622462053c6d31dddbfd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC)</td>
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

<p>This static method is the primary way to construct an <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a>.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ace5fc98ee60d145881306ef4ba8c6ef0">llvm::applyWrappers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a379666f1f08149bf9e4dabcb430aee93">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::calculateConvertType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#a86d26a3e2f2b7996916c7040cd7b40b4">classifyConstantWithOpaquePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ad59bafaeacd51c2b1e6251488039d29a">llvm::VPInterleaveRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a787f048d94a8f173da27cb792cff4758">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::convertEVLToMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a3ed7e979bee3c9d43ed5128461ca9070">createAndCheckVectorTypesForPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a5662a5eb5436e4a9301827cca40b9b93">createBitOrPointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae934d6e99e0516d606ae8e65ff6aed63">llvm::IRBuilderBase::CreateStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a32f45ac41ff64c32a157182ce87e6057">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a141e9946f635323d4da5e8b4b3f64e44">llvm::VPFirstOrderRecurrencePHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ab0d48fabf61af227821d568b1c3aa4ca">llvm::VPInterleaveRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a2ed5b7b284097278ee4e550897b1f057">llvm::VPReplicateRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#acdd340f122251b99aaee3308d31f1230">llvm::VPScalarIVStepsRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a9b432a2a53b6ec71e9290e6f9d7582ea">llvm::VPWidenCastRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instsimplifyfolder/#a8db493e6d91726e469aa91fa425cd269">llvm::InstSimplifyFolder::FoldShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="#a9a937399ee5b5885ffc2d7355ae96eda">get</a>, <a href="#af2bc88fa949977374572b32de0224b03">get</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#a48955fd76dc29a6b4391aef55ce3efd3">llvm::VPTransformState::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a660392f54efb6a70e2b59a840ccf1728">getAllocaPos</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a756d58f4b6672c5083895872285931f1">llvm::IRBuilderBase::getAllOnesMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a2c38e97ad1359c63dd44a0bbe5dcf3a3">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getBoolTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a243a4cdb6c27c0c4276793b5136a01">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getByteTy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a6212e41633990ea795daea7917312bdf">llvm::RISCVTTIImpl::getCastInstrCost</a>, <a href="#ac423a4165a8f57cd2865ef33dd9be484">getDoubleElementsVectorType</a>, <a href="#a3b1f5f847d812d85eaaa8a19bd01bcf4">getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/mappingconfig/#aa4b25ffb1d9184be4a8694b940d27562">anonymous{NumericalStabilitySanitizer.cpp}::MappingConfig::getExtendedFPType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4910f3acf596de7348ca70c0b41b0040">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a131bb2ad08caba3a193dd8e1d862d704">llvm::GetElementPtrInst::getGEPReturnType</a>, <a href="#a12589d52afe7ea72485b0a431327a6e6">getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a5d1ff741add38ce427dcd488424274fe">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getHvxTy</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#abbd9ed911d1d58b73f9571f300cc6a7b">llvm::DataLayout::getIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="#a781c723920fb1d098c4d959f3218d9aa">getInteger</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a768d59ed528e3f461065b20571b913dc">anonymous{AddressSanitizer.cpp}::AddressSanitizer::getInterestingMemoryOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4988f54643e5c2613c9a0682ccccccbf">llvm::AMDGPU::getInterestingMemoryOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a3b08e9ad2a315e50f4b0189d9755deed">llvm::AArch64TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#affbb031405865e13b46411b934814a83">llvm::RISCVTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a8bb1aa8811da861ad795a3125a9e5ce7">llvm::DataLayout::getIntPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#aa3e5ac869df3bf1d37fca48c06228608">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getMulAccReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#adfa93be20aafc0740ce9e4d48640406c">getPownType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ac784928dcbbc1b0691cc8da90970391d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getPtrToShadowPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a074d013c7183283d9aaa8d7127057242">llvm::ConstantDataVector::getRaw</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/truncinstcombine-cpp/#a1539f094351301ac0da48dfd94108ffc">getReducedType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ac65e8fc0f385fe5eba1c9260f8f4c527">llvm::RISCVTTIImpl::getRegUsageForType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a03dd63ac617c1242b7694a4b0ae4ed25">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a0911ef4a610d70c5104c1932fec0e1">llvm::getTypeForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a05cf907fc03e5b3f599a3dbd02c55803">llvm::RISCVTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8fa51d3da96615af400274e9cd272df4">llvm::Type::getWithNewType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a965b006c5624011322112bb1f1325f8e">instCombineSVECondLast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#aa650124eefba1fd45866d05306385129">llvm::LoopVectorizationCostModel::isLegalGatherOrScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#abc3508a388e7f7545f2a4c745f087916">llvm::Type::isScalableTy</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ac864682b9dcdc0ce83df845bf6cfb2e8">llvm::LoopVectorizationCostModel::isScalarWithPredication</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a12fa96c1212a99f965fcce98aa550a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::joinVectorElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a7b33bd9843f6f96a4f390a9314692657">llvm::sandboxir::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a2bff55a07291d47843ff3e4a1548c154">llvm::fuzzerop::matchFirstLengthWAnyType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a83114915b4f7fec94a20efa3834a8250">maybeVectorizeType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a2b864b9948ac61152a68b54bea89ea82">llvm::SPIRV::parseBuiltinCallArgumentType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a69a4b725eeca6669bc2adb458eb5e08f">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::ptrToIntPtrType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a0b50be89487f7186a5eb7ff1bc82efc0">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a43ccb9c1a5081a041efc8db46bbcf7a2">replaceWithTLIFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a97c8c57e973ff87b44455c5d47d41770">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::rescale</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a40bdb7ed86f1fdb139eb9fd73b05405a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::splitVectorElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a3e077365cf48a773b0debd4a65499d1d">tryToFPToSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#a1fdfe91f1f9e82078936d0cde2af8a3f">validShuffleVectorIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a86163cb169435641156cbc611072c931">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vbytes</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5417dab7a760eedf39c533b1b31b1b23">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>.</p>

</div>
</div>

### get() {#af2bc88fa949977374572b32de0224b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, unsigned NumElements, bool Scalable)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>

</div>
</div>

### get() {#a9a937399ee5b5885ffc2d7355ae96eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * Other)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>

</div>
</div>

### getDoubleElementsVectorType() {#ac423a4165a8f57cd2865ef33dd9be484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::getDoubleElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy)</td>
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

<p>This static method returns a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> with twice as many elements as the input type and the same element type.</p>

<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a>, <a href="#afdce715c901d62e2c1367a0ff5248175">getElementType</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/type/#ae77d4c2d7f8556667a38ab71c72cb54f">llvm::Type::containsNonLocalTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a4581545c459454e57838691ebff7b1b6">llvm::FixedVectorType::getDoubleElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#a8e081f3e98a10acbda6534411db933f1">llvm::ScalableVectorType::getDoubleElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="#a62425c077bf32e483e2e041e26bce530">getSubdividedVectorType</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a204934c6800bce8f4ce892221de4ebbe">interleaveVectors</a>.</p>

</div>
</div>

### getExtendedElementVectorType() {#a3b1f5f847d812d85eaaa8a19bd01bcf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::getExtendedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy)</td>
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

<p>This static method is like getInteger except that the element types are twice as wide as the elements in the input type.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a>, <a href="#afdce715c901d62e2c1367a0ff5248175">getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a1b9967d7ff743d4f7f1014a74204288a">llvm::X86TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a65b7c4625325b13cb9f3db7923aae4f6">llvm::FixedVectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#ac96d755c768edd2cde7743330bbb6f5a">llvm::sandboxir::VectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#a69b2237c400e18061b981fd7bcf5bec4">llvm::ScalableVectorType::getExtendedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac59306eb826e349ac7429736b1506432">llvm::Type::getExtendedType</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>.</p>

</div>
</div>

### getHalfElementsVectorType() {#a12589d52afe7ea72485b0a431327a6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::getHalfElementsVectorType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy)</td>
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

<p>This static method returns a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> with half as many elements as the input type and the same element type.</p>

<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a>, <a href="#afdce715c901d62e2c1367a0ff5248175">getElementType</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7ea782436f7a688ebb717a91808b9c5d">llvm::AArch64TargetLowering::createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ad0c9ac06022884eb218dc8f8c4056e43">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#afdb8103793f8643efb6d981d9cfcb99c">llvm::FixedVectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a9cd3c5065659bc840e36b5a96ec94d96">llvm::sandboxir::VectorType::getHalfElementsVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#a6af250057bed5c4bc6124d0b00687a22">llvm::ScalableVectorType::getHalfElementsVectorType</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>.</p>

</div>
</div>

### getInteger() {#a781c723920fb1d098c4d959f3218d9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::getInteger (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy)</td>
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

<p>This static method gets a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> with the same number of elements as the input type, and the element type is an integer type of the same width as the input element type.</p>

<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a>, <a href="#afdce715c901d62e2c1367a0ff5248175">getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a510fe1022b20cfb823cf9f1ee7f23a00">llvm::FixedVectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a78f34fdeeb7b2cc30adc895344d8df0f">llvm::sandboxir::VectorType::getInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#a28794e2f573f76d9171a5cf18b085517">llvm::ScalableVectorType::getInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a31bd4337238731fb22410e089576f6d8">getNegativeIsTrueBoolVec</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aee0f586f3e5fc07e4c55d3e8caade9a6">llvm::Constant::isElementWiseEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a50016fb8102156a9c168cfd348b3509a">llvm::AArch64TargetLowering::optimizeExtendOrTruncateConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a8f3b97594fe4e833960ffddc2a778a53">simplifyX86movmsk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>.</p>

</div>
</div>

### getSubdividedVectorType() {#a62425c077bf32e483e2e041e26bce530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::getSubdividedVectorType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy, int NumSubdivs)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#ac423a4165a8f57cd2865ef33dd9be484">getDoubleElementsVectorType</a>, <a href="#aa0f42bf1b84f6c3dac6c70d2cc7f92bc">getTruncatedElementVectorType</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/type/#a2f0388b8315300b55a8833caf090ef71">llvm::Type::containsNonLocalTargetExtType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a62c10db57b57fc5b046c5b56d34052b2">llvm::FixedVectorType::getSubdividedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#a8df4ed4f44d9dfc2fd7e064590f5ec5e">llvm::ScalableVectorType::getSubdividedVectorType</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>.</p>

</div>
</div>

### getTruncatedElementVectorType() {#aa0f42bf1b84f6c3dac6c70d2cc7f92bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorType * llvm::VectorType::getTruncatedElementVectorType (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * VTy)</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#a861be1e2092622462053c6d31dddbfd5">get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="#a59632c5deb0423a518ad984bdd04d41f">getElementCount</a>, <a href="#afdce715c901d62e2c1367a0ff5248175">getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a> and <a href="#a302dbb3a7c0b1d6c35d76d3caaf4a6ba">VectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/type/#ae7b43432683c09a40d81b9b245a05565">llvm::Type::containsNonGlobalTargetExtType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="#a62425c077bf32e483e2e041e26bce530">getSubdividedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#ae173d4d87902647680bdd90572cf7f6f">llvm::FixedVectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalablevectortype/#ae179f1902b29144930348846cad0f777">llvm::ScalableVectorType::getTruncatedElementVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a50016fb8102156a9c168cfd348b3509a">llvm::AArch64TargetLowering::optimizeExtendOrTruncateConversion</a>.</p>

</div>
</div>

### isValidElementType() {#aa6a2194fc011669faabe43322d7c6c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VectorType::isValidElementType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy)</td>
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

<p>Return true if the specified type is valid as a element type.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15795bcb48d8b3c37995ae4459f0af7d">llvm::canVectorizeStructTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa04ec8bb885944a774a1e7e244581046">llvm::canVectorizeTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a3ed7e979bee3c9d43ed5128461ca9070">createAndCheckVectorTypesForPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a2bff55a07291d47843ff3e4a1548c154">llvm::fuzzerop::matchFirstLengthWAnyType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77e211e8fb596ed21bb29f80aeacc211">llvm::toVectorizedStructTy</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
