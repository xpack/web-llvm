---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/attributelist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AttributeList` Class Reference

<p>This class holds the attributes for a function, its return value, and its parameters. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AttributeList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad976ce39a2c7b654a9174afe3a99fa9">iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> *</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttrIndex : unsigned { <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1abc877ace897e9064c968a96a266dfe">AttributeListImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7fc09e6d51b06742728a42accbca9d">AttributeSetNode</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Ty, typename Enable&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c449a1f7f0fc08e792806925ddbed72">AttributeList</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2885d9e0a24b49b1b451eb07335e3ecd">AttributeList</a> (AttributeListImpl *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077134723a79280e93101adb56e36614">operator==</a> (const AttributeList &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>operator==/!= - Provide equality predicates. <a href="#a077134723a79280e93101adb56e36614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b788ffb2fa7e52afacff05ac28269c1">operator!=</a> (const AttributeList &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a> (LLVMContext &amp;C, unsigned Index, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to the attribute set at the given index. <a href="#ada583c27bb2634195f2964c7e695a0b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51a5d5a3a63f237d28e10eedf5fcd2b">addAttributeAtIndex</a> (LLVMContext &amp;C, unsigned Index, StringRef Kind, StringRef Value=StringRef()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to the attribute set at the given index. <a href="#af51a5d5a3a63f237d28e10eedf5fcd2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a927b6368c3822a66d37651a978f4f">addAttributeAtIndex</a> (LLVMContext &amp;C, unsigned Index, Attribute A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to the attribute set at the given index. <a href="#ab5a927b6368c3822a66d37651a978f4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a> (LLVMContext &amp;C, unsigned Index, const AttrBuilder &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attributes to the attribute set at the given index. <a href="#ab58814a61429a0b976eae58a0695c206">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ec2da7f0fb48a9208234c425f83ea6">addFnAttribute</a> (LLVMContext &amp;C, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function attribute to the list. <a href="#a54ec2da7f0fb48a9208234c425f83ea6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa32c5a977d6e4bb922611a29d8f7482">addFnAttribute</a> (LLVMContext &amp;C, Attribute Attr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function attribute to the list. <a href="#afa32c5a977d6e4bb922611a29d8f7482">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb72fdaef87bc94257783b6d2bd8817">addFnAttribute</a> (LLVMContext &amp;C, StringRef Kind, StringRef Value=StringRef()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function attribute to the list. <a href="#aafb72fdaef87bc94257783b6d2bd8817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7d1a9d74e14b7535745a80fbc51f70">addFnAttributes</a> (LLVMContext &amp;C, const AttrBuilder &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add function attribute to the list. <a href="#a5d7d1a9d74e14b7535745a80fbc51f70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32c2b32d61cf856c6a5b2ceb3de7fd0d">addRetAttribute</a> (LLVMContext &amp;C, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a return value attribute to the list. <a href="#a32c2b32d61cf856c6a5b2ceb3de7fd0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca368a465f897becfa3a426fa59c2fd9">addRetAttribute</a> (LLVMContext &amp;C, Attribute Attr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a return value attribute to the list. <a href="#aca368a465f897becfa3a426fa59c2fd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2663f4f16dd7748ba4b0d68836aa5c">addRetAttributes</a> (LLVMContext &amp;C, const AttrBuilder &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a return value attribute to the list. <a href="#a3e2663f4f16dd7748ba4b0d68836aa5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a6727ecc3f601729c11f37a19f93f8">addParamAttribute</a> (LLVMContext &amp;C, unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an argument attribute to the list. <a href="#af3a6727ecc3f601729c11f37a19f93f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731a5e7d7624c487d5dbb8471e1e2857">addParamAttribute</a> (LLVMContext &amp;C, unsigned ArgNo, StringRef Kind, StringRef Value=StringRef()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an argument attribute to the list. <a href="#a731a5e7d7624c487d5dbb8471e1e2857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1e8df5d1ec58e81979760331f7808e">addParamAttribute</a> (LLVMContext &amp;C, ArrayRef&lt; unsigned &gt; ArgNos, Attribute A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to the attribute list at the given arg indices. <a href="#a3f1e8df5d1ec58e81979760331f7808e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae18cffa676178ae60f0692ad4410e940">addParamAttributes</a> (LLVMContext &amp;C, unsigned ArgNo, const AttrBuilder &amp;B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an argument attribute to the list. <a href="#ae18cffa676178ae60f0692ad4410e940">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a> (LLVMContext &amp;C, unsigned Index, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the specified index from this attribute list. <a href="#a0fdf10b37833524db3870b2dd98693a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac2c888655f9fa00f53c7c7e851ff20">removeAttributeAtIndex</a> (LLVMContext &amp;C, unsigned Index, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the specified index from this attribute list. <a href="#abac2c888655f9fa00f53c7c7e851ff20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be93bfc0865b2bc93136f67be092471">removeAttribute</a> (LLVMContext &amp;C, unsigned Index, StringRef Kind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a> (LLVMContext &amp;C, unsigned Index, const AttributeMask &amp;AttrsToRemove) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attributes at the specified index from this attribute list. <a href="#a2240c7569f0786a6bea570d21e924060">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2077a29ae8c3a0a7afe3bd0345f8738">removeAttributesAtIndex</a> (LLVMContext &amp;C, unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all attributes at the specified index from this attribute list. <a href="#ad2077a29ae8c3a0a7afe3bd0345f8738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22a21db26809ce1d18b8ee41295b474">removeFnAttribute</a> (LLVMContext &amp;C, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the function index from this attribute list. <a href="#ac22a21db26809ce1d18b8ee41295b474">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0308f412730541938ee571fea17925d">removeFnAttribute</a> (LLVMContext &amp;C, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the function index from this attribute list. <a href="#ad0308f412730541938ee571fea17925d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58229d1b1450ad0311f0a138fce5a73">removeFnAttributes</a> (LLVMContext &amp;C, const AttributeMask &amp;AttrsToRemove) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the function index from this attribute list. <a href="#ad58229d1b1450ad0311f0a138fce5a73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6847a760305fc6dfb31721c185a1aa6">removeFnAttributes</a> (LLVMContext &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the attributes at the function index from this attribute list. <a href="#ab6847a760305fc6dfb31721c185a1aa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0a2e70b99735033d6c8565181fbacf">removeRetAttribute</a> (LLVMContext &amp;C, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the return value index from this attribute list. <a href="#aec0a2e70b99735033d6c8565181fbacf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aad76febe84315bf8b5cae3336bd612">removeRetAttribute</a> (LLVMContext &amp;C, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the return value index from this attribute list. <a href="#a1aad76febe84315bf8b5cae3336bd612">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42c63d5e6fd828727093857e31c22cd3">removeRetAttributes</a> (LLVMContext &amp;C, const AttributeMask &amp;AttrsToRemove) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the return value index from this attribute list. <a href="#a42c63d5e6fd828727093857e31c22cd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcd25c0256b5c210d20ada500ca7faf">removeParamAttribute</a> (LLVMContext &amp;C, unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the specified arg index from this attribute list. <a href="#aabcd25c0256b5c210d20ada500ca7faf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4ebc3eed35009a0cc35d7a8f6d878e">removeParamAttribute</a> (LLVMContext &amp;C, unsigned ArgNo, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the specified arg index from this attribute list. <a href="#a4f4ebc3eed35009a0cc35d7a8f6d878e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161139dd3cce264762282c9009eb1acd">removeParamAttributes</a> (LLVMContext &amp;C, unsigned ArgNo, const AttributeMask &amp;AttrsToRemove) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute at the specified arg index from this attribute list. <a href="#a161139dd3cce264762282c9009eb1acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14fe429b8e7e3af4cab47a826ae6918f">removeParamAttributes</a> (LLVMContext &amp;C, unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all attributes at the specified arg index from this attribute list. <a href="#a14fe429b8e7e3af4cab47a826ae6918f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d7d74d32e67259997832a663e14739">replaceAttributeTypeAtIndex</a> (LLVMContext &amp;C, unsigned ArgNo, Attribute::AttrKind Kind, Type *ReplacementTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the type contained by attribute <span class="doxyComputerOutput">AttrKind</span> at index <span class="doxyComputerOutput">ArgNo</span> wih <span class="doxyComputerOutput">ReplacementTy</span>, preserving all other attributes. <a href="#af4d7d74d32e67259997832a663e14739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402a2e4e215f051eb560a99327b8c49e">addDereferenceableRetAttr</a> (LLVMContext &amp;C, uint64_t Bytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the dereferenceable attribute to the attribute set at the given index. <a href="#a402a2e4e215f051eb560a99327b8c49e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8aeaa2675b027d52c93a39ae453471">addDereferenceableParamAttr</a> (LLVMContext &amp;C, unsigned ArgNo, uint64_t Bytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the dereferenceable attribute to the attribute set at the given arg index. <a href="#a0e8aeaa2675b027d52c93a39ae453471">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e6fb5739626983930f5cfd8d8b0f07">addDereferenceableOrNullParamAttr</a> (LLVMContext &amp;C, unsigned ArgNo, uint64_t Bytes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the dereferenceable_or_null attribute to the attribute set at the given arg index. <a href="#ac6e6fb5739626983930f5cfd8d8b0f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17828da99c4b2a5fc6b0384e6689fb0c">addRangeRetAttr</a> (LLVMContext &amp;C, const ConstantRange &amp;CR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the range attribute to the attribute set at the return value index. <a href="#a17828da99c4b2a5fc6b0384e6689fb0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19f7bd764bed56888170d913d6915c7">addAllocSizeParamAttr</a> (LLVMContext &amp;C, unsigned ArgNo, unsigned ElemSizeArg, const std::optional&lt; unsigned &gt; &amp;NumElemsArg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the allocsize attribute to the attribute set at the given arg index. <a href="#ac19f7bd764bed56888170d913d6915c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67533111413cc397100c48c82291ec7">intersectWith</a> (LLVMContext &amp;C, AttributeList Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to intersect this <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> with Other. <a href="#ad67533111413cc397100c48c82291ec7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> (unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attributes for the specified index are returned. <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attributes for the argument or parameter at the given index are returned. <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attributes for the ret value are returned. <a href="#a5604157867b3d226260f6388b987e49a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function attributes are returned. <a href="#a1cf553641e8527095ae4c8ec88a2cd92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a> (unsigned Index, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists at the given index. <a href="#a09a57939ead526bbae148522e31f198d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6590789e70f40b3d72d525bb7327dcbc">hasAttributeAtIndex</a> (unsigned Index, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists at the given index. <a href="#a6590789e70f40b3d72d525bb7327dcbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180523993bcaffcbbb7cca7a3fc0d51c">hasAttributesAtIndex</a> (unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if attribute exists at the given index. <a href="#a180523993bcaffcbbb7cca7a3fc0d51c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04846c93ea7d802afbaa48efd84f37e">hasParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists for the given argument. <a href="#ab04846c93ea7d802afbaa48efd84f37e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726d79ceb91ce0b86d8dfeb8d50dd0b1">hasParamAttr</a> (unsigned ArgNo, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists for the given argument. <a href="#a726d79ceb91ce0b86d8dfeb8d50dd0b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3737e67f34f29a0244b6e1b236652bc8">hasParamAttrs</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if attributes exists for the given argument. <a href="#a3737e67f34f29a0244b6e1b236652bc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4e348d7ff2f6b76dcaa69382b78980">hasRetAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists for the return value. <a href="#afe4e348d7ff2f6b76dcaa69382b78980">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aeb561c53719a10aecb2757ef0fff79">hasRetAttr</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists for the return value. <a href="#a1aeb561c53719a10aecb2757ef0fff79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58b17d02803ec68e3dbfc82a8f45d5e">hasRetAttrs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if attributes exist for the return value. <a href="#ac58b17d02803ec68e3dbfc82a8f45d5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61054ea97168f709c1e46345f80c16a3">hasFnAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists for the function. <a href="#a61054ea97168f709c1e46345f80c16a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65daa7efe6ca841a6772474c62137aa3">hasFnAttr</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists for the function. <a href="#a65daa7efe6ca841a6772474c62137aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e7e25df5981be38867dd67df81f92">hasFnAttrs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true the attributes exist for the function. <a href="#ad78e7e25df5981be38867dd67df81f92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d6c6f22bf21c4725e3f9be5ec0b07e">hasAttrSomewhere</a> (Attribute::AttrKind Kind, unsigned *Index=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified attribute is set for at least one parameter or for the return value. <a href="#a75d6c6f22bf21c4725e3f9be5ec0b07e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a> (unsigned Index, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object that exists at the given index. <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b2a026f921a5c932f3320ede3e19ac">getAttributeAtIndex</a> (unsigned Index, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object that exists at the given index. <a href="#ab6b2a026f921a5c932f3320ede3e19ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd6dadb077a5c3503a74b8c5850a805">getParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object that exists at the arg index. <a href="#a4bd6dadb077a5c3503a74b8c5850a805">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0327f306fb6582ae6b1a55586e2410">getParamAttr</a> (unsigned ArgNo, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object that exists at the given index. <a href="#abe0327f306fb6582ae6b1a55586e2410">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90024ee48918b2167a4c9409750d4148">getFnAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object that exists for the function. <a href="#a90024ee48918b2167a4c9409750d4148">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060fe3a67cf9794919c0559515be2ffc">getFnAttr</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object that exists for the function. <a href="#a060fe3a67cf9794919c0559515be2ffc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fa6901843f6a775399fcbb31fee52a">getRetAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute for the given attribute kind for the return value. <a href="#ab6fa6901843f6a775399fcbb31fee52a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb1595f5c255bb9ec836172ad5537e9">getRetAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment of the return value. <a href="#a9bb1595f5c255bb9ec836172ad5537e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704aa0a94c0e6bf8fd60e6e4e463e93d">getParamAlignment</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment for the specified function parameter. <a href="#a704aa0a94c0e6bf8fd60e6e4e463e93d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9095b759fb33104bdcafec14e2b15c1">getParamStackAlignment</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the stack alignment for the specified function parameter. <a href="#ab9095b759fb33104bdcafec14e2b15c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58adac46c3ade432914ab977a69e17e">getParamByValType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the byval type for the specified function parameter. <a href="#ab58adac46c3ade432914ab977a69e17e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3b1e69f26a3784d71f161942e31829">getParamStructRetType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the sret type for the specified function parameter. <a href="#a0e3b1e69f26a3784d71f161942e31829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada3107abfa5601f959a5403190d230f8">getParamByRefType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the byref type for the specified function parameter. <a href="#ada3107abfa5601f959a5403190d230f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa27e1eb608ff6d7e99bbba7d7aaf5b71">getParamPreallocatedType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preallocated type for the specified function parameter. <a href="#aa27e1eb608ff6d7e99bbba7d7aaf5b71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b3b0b8961a38c7735a4b9660c42be7b">getParamInAllocaType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the inalloca type for the specified function parameter. <a href="#a7b3b0b8961a38c7735a4b9660c42be7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d429f5f04915251440ffdafeb462616">getParamElementType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the elementtype type for the specified function parameter. <a href="#a9d429f5f04915251440ffdafeb462616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0eaea88fb8f6bc99c7547113ec906bc">getFnStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the stack alignment of the function. <a href="#ab0eaea88fb8f6bc99c7547113ec906bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5a24c43e105c203f779ca9a0ae0093">getRetStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the stack alignment of the return value. <a href="#a3a5a24c43e105c203f779ca9a0ae0093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda2f1696e90762ee9b7b64065c64969">getRetDereferenceableBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of dereferenceable bytes (or zero if unknown) of the return value. <a href="#abda2f1696e90762ee9b7b64065c64969">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f9460daf3f10c40cbeae0fd222cbd9">getParamDereferenceableBytes</a> (unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of dereferenceable bytes (or zero if unknown) of an arg. <a href="#a62f9460daf3f10c40cbeae0fd222cbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b7413239e3f901328769ef2b5a23b0">getRetDereferenceableOrNullBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of dereferenceable_or_null bytes (or zero if unknown) of the return value. <a href="#ae6b7413239e3f901328769ef2b5a23b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ac94e810bcb4e307b82617c2d1f22d">getParamDereferenceableOrNullBytes</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of dereferenceable_or_null bytes (or zero if unknown) of an arg. <a href="#ac2ac94e810bcb4e307b82617c2d1f22d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6559a2babd0e7bd0f96d7116fb49940">getParamRange</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get range (or std::nullopt if unknown) of an arg. <a href="#ae6559a2babd0e7bd0f96d7116fb49940">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d05f2b6b9067ce92dc32f2f6443df5d">getRetNoFPClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the disallowed floating-point classes of the return value. <a href="#a7d05f2b6b9067ce92dc32f2f6443df5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc215f164f494921945f7cb648056c56">getParamNoFPClass</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the disallowed floating-point classes of the argument value. <a href="#acc215f164f494921945f7cb648056c56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98312c308907b87211168eda9c6b605b">getUWTableKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the unwind table kind requested for the function. <a href="#a98312c308907b87211168eda9c6b605b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50abfb2dceb5d84bcbf1cf263e33d7d9">getAllocKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb984e3fb006d09d90fcc934789cfbd8">getMemoryEffects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns memory effects of the function. <a href="#afb984e3fb006d09d90fcc934789cfbd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917739f8f62442b8fea20bbe72cab891">getAsString</a> (unsigned Index, bool InAttrGrp=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attributes at the index as a string. <a href="#a917739f8f62442b8fea20bbe72cab891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34082941d26848b9383954c70054792">hasParentContext</a> (LLVMContext &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this attribute list belongs to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#aa34082941d26848b9383954c70054792">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aad976ce39a2c7b654a9174afe3a99fa9">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361c9c88d8b9972fa0071b508acc9de2">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aad976ce39a2c7b654a9174afe3a99fa9">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77dcf96d9d822c5289b9506ba191e0d8">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b3e5b33beb7828efdd751c208bfbee9">getNumAttrSets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/attributelist/index-iterator">index_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f51ca3a752de383f463899aaf39104d">indexes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this to iterate over the valid attribute indexes. <a href="#a1f51ca3a752de383f463899aaf39104d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb7d44e0a657e7807506627647ea203">getRawPointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a raw pointer that uniquely identifies this attribute list. <a href="#a4cb7d44e0a657e7807506627647ea203">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5269e6b95f5007a652d53ca847cca6f3">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are no attributes. <a href="#a5269e6b95f5007a652d53ca847cca6f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa5ba0fe693cb5a3739950924cb2033">print</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88787fab8a5d948bd5100aded6fc799">dump</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00e1c0c71d57328a34d6b09fe44d7ed">setAttributesAtIndex</a> (LLVMContext &amp;C, unsigned Index, AttributeSet Attrs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelistimpl">AttributeListImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1343a33d10b62461677274e4b354eaa">pImpl</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attributes that we are managing. <a href="#af1343a33d10b62461677274e4b354eaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a> (LLVMContext &amp;C, ArrayRef&lt; std::pair&lt; unsigned, Attribute &gt; &gt; Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> with the specified parameters in it. <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0934a03f7182abfbf5e57fc4e7c7c82">get</a> (LLVMContext &amp;C, ArrayRef&lt; std::pair&lt; unsigned, AttributeSet &gt; &gt; Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad544515efb693b15ac9855c6be03189b">get</a> (LLVMContext &amp;C, AttributeSet FnAttrs, AttributeSet RetAttrs, ArrayRef&lt; AttributeSet &gt; ArgAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> from attribute sets for a function, its return value, and all of its arguments. <a href="#ad544515efb693b15ac9855c6be03189b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b476a2ef81faca335499a5cafb9241">get</a> (LLVMContext &amp;C, ArrayRef&lt; AttributeList &gt; Attrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> with the specified parameters in it. <a href="#ac0b476a2ef81faca335499a5cafb9241">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4387a04798ee02597a248ac196fc1d53">get</a> (LLVMContext &amp;C, unsigned Index, ArrayRef&lt; Attribute::AttrKind &gt; Kinds)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15fc36bf8d33e06423d939bb34bc9305">get</a> (LLVMContext &amp;C, unsigned Index, ArrayRef&lt; Attribute::AttrKind &gt; Kinds, ArrayRef&lt; uint64_t &gt; Values)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9345ab199d872cbb5a7c31b84a4cde">get</a> (LLVMContext &amp;C, unsigned Index, ArrayRef&lt; StringRef &gt; Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf23368370765012fba0a78c1b42fdf9">get</a> (LLVMContext &amp;C, unsigned Index, AttributeSet Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e752c843b2d32061a0dfbb3b784eb9">get</a> (LLVMContext &amp;C, unsigned Index, const AttrBuilder &amp;B)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309fbc0a0cba5a9d8f4ada5402f8fbe8">getImpl</a> (LLVMContext &amp;C, ArrayRef&lt; AttributeSet &gt; AttrSets)</td>
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

<p>This class holds the attributes for a function, its return value, and its parameters.</p>


<p>You access the attributes for each of them via an index into the <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> object. The function attributes are at index ‘<a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">AttributeList::FunctionIndex</a>`, the return value is at index ‘<a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">AttributeList::ReturnIndex</a>`, and the attributes for the parameters start at index ‘<a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">AttributeList::FirstArgIndex</a>`.</p>


<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#aad976ce39a2c7b654a9174afe3a99fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AttributeList::iterator =  const AttributeSet *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### AttrIndex {#af5dcb6d3da4b30a7d21c9fb39bbf1a68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AttributeList::AttrIndex : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ReturnIndex<a id="af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df"></a></td>
<td class="doxyEnumItemDescription"> (= 0U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FunctionIndex<a id="af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8"></a></td>
<td class="doxyEnumItemDescription"> (= ~0U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstArgIndex<a id="af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### AttrBuilder {#a5d48a1514b932419965e18798ab4f9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>.</p>


<p>Referenced by <a href="#ac19f7bd764bed56888170d913d6915c7">addAllocSizeParamAttr</a>, <a href="#ab5a927b6368c3822a66d37651a978f4f">addAttributeAtIndex</a>, <a href="#af51a5d5a3a63f237d28e10eedf5fcd2b">addAttributeAtIndex</a>, <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#ac6e6fb5739626983930f5cfd8d8b0f07">addDereferenceableOrNullParamAttr</a>, <a href="#a0e8aeaa2675b027d52c93a39ae453471">addDereferenceableParamAttr</a>, <a href="#a402a2e4e215f051eb560a99327b8c49e">addDereferenceableRetAttr</a>, <a href="#a5d7d1a9d74e14b7535745a80fbc51f70">addFnAttributes</a>, <a href="#a3f1e8df5d1ec58e81979760331f7808e">addParamAttribute</a>, <a href="#ae18cffa676178ae60f0692ad4410e940">addParamAttributes</a>, <a href="#a17828da99c4b2a5fc6b0384e6689fb0c">addRangeRetAttr</a>, <a href="#a3e2663f4f16dd7748ba4b0d68836aa5c">addRetAttributes</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="#a2c449a1f7f0fc08e792806925ddbed72">AttributeList</a>, <a href="#ac0b476a2ef81faca335499a5cafb9241">get</a> and <a href="#aa3e752c843b2d32061a0dfbb3b784eb9">get</a>.</p>

</div>
</div>

### AttributeListImpl {#a1abc877ace897e9064c968a96a266dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/attributelistimpl">AttributeListImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a1abc877ace897e9064c968a96a266dfe">AttributeListImpl</a>.</p>


<p>Referenced by <a href="#a1abc877ace897e9064c968a96a266dfe">AttributeListImpl</a> and <a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a>.</p>

</div>
</div>

### AttributeSet {#a2870b20bc1c79303e5d4cc6c1c97a21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>.</p>


<p>Referenced by <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="#a2c449a1f7f0fc08e792806925ddbed72">AttributeList</a>, <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a>, <a href="#ad544515efb693b15ac9855c6be03189b">get</a>, <a href="#acf23368370765012fba0a78c1b42fdf9">get</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>, <a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a>, <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a>, <a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a>, <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>, <a href="#abac2c888655f9fa00f53c7c7e851ff20">removeAttributeAtIndex</a>, <a href="#ad2077a29ae8c3a0a7afe3bd0345f8738">removeAttributesAtIndex</a> and <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a>.</p>

</div>
</div>

### AttributeSetNode {#a7e7fc09e6d51b06742728a42accbca9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/attributesetnode">AttributeSetNode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a7e7fc09e6d51b06742728a42accbca9d">AttributeSetNode</a>.</p>


<p>Referenced by <a href="#a7e7fc09e6d51b06742728a42accbca9d">AttributeSetNode</a>.</p>

</div>
</div>

### DenseMapInfo {#ac84243e1c08596f66aa0ee1f836ebe00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a1abc877ace897e9064c968a96a266dfe">AttributeListImpl</a>, <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a>.</p>


<p>Referenced by <a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AttributeList() {#a2c449a1f7f0fc08e792806925ddbed72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeList::AttributeList ()</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### AttributeList() {#a2885d9e0a24b49b1b451eb07335e3ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeList::AttributeList (<a href="/web-llvm/docs/api/classes/llvm/attributelistimpl">AttributeListImpl</a> * LI)</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a7b788ffb2fa7e52afacff05ac28269c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; RHS)</td>
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



<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a077134723a79280e93101adb56e36614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; RHS)</td>
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

<p>operator==/!= - Provide equality predicates.</p>

<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAllocSizeParamAttr() {#ac19f7bd764bed56888170d913d6915c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addAllocSizeParamAttr (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, unsigned ElemSizeArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; unsigned &gt; &amp; NumElemsArg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the allocsize attribute to the attribute set at the given arg index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1816 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ae18cffa676178ae60f0692ad4410e940">addParamAttributes</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addAttributeAtIndex() {#ada583c27bb2634195f2964c7e695a0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addAttributeAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute to the attribute set at the given index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1669 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#afa32c5a977d6e4bb922611a29d8f7482">addFnAttribute</a>, <a href="#a54ec2da7f0fb48a9208234c425f83ea6">addFnAttribute</a>, <a href="#aafb72fdaef87bc94257783b6d2bd8817">addFnAttribute</a>, <a href="#af3a6727ecc3f601729c11f37a19f93f8">addParamAttribute</a>, <a href="#a731a5e7d7624c487d5dbb8471e1e2857">addParamAttribute</a>, <a href="#aca368a465f897becfa3a426fa59c2fd9">addRetAttribute</a> and <a href="#a32c2b32d61cf856c6a5b2ceb3de7fd0d">addRetAttribute</a>.</p>

</div>
</div>

### addAttributeAtIndex() {#af51a5d5a3a63f237d28e10eedf5fcd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addAttributeAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute to the attribute set at the given index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addAttributeAtIndex() {#ab5a927b6368c3822a66d37651a978f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addAttributeAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute to the attribute set at the given index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1688 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addAttributesAtIndex() {#ab58814a61429a0b976eae58a0695c206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addAttributesAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attributes to the attribute set at the given index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="#ab5a927b6368c3822a66d37651a978f4f">addAttributeAtIndex</a>, <a href="#af51a5d5a3a63f237d28e10eedf5fcd2b">addAttributeAtIndex</a>, <a href="#a5d7d1a9d74e14b7535745a80fbc51f70">addFnAttributes</a>, <a href="#ae18cffa676178ae60f0692ad4410e940">addParamAttributes</a> and <a href="#a3e2663f4f16dd7748ba4b0d68836aa5c">addRetAttributes</a>.</p>

</div>
</div>

### addDereferenceableOrNullParamAttr() {#ac6e6fb5739626983930f5cfd8d8b0f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addDereferenceableOrNullParamAttr (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, uint64_t Bytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the dereferenceable_or_null attribute to the attribute set at the given arg index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1802 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ae18cffa676178ae60f0692ad4410e940">addParamAttributes</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addDereferenceableParamAttr() {#a0e8aeaa2675b027d52c93a39ae453471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addDereferenceableParamAttr (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, uint64_t Bytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the dereferenceable attribute to the attribute set at the given arg index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1793 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ae18cffa676178ae60f0692ad4410e940">addParamAttributes</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addDereferenceableRetAttr() {#a402a2e4e215f051eb560a99327b8c49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addDereferenceableRetAttr (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, uint64_t Bytes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the dereferenceable attribute to the attribute set at the given index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1786 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a3e2663f4f16dd7748ba4b0d68836aa5c">addRetAttributes</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addFnAttribute() {#a54ec2da7f0fb48a9208234c425f83ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a925bbfb44898a7e8da7d6170278aaf71">emitTPIDR2Save</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a4d28b0b4536be47a57ac82367c0b04a7">llvm::AMDGPULibFunc::getOrInsertFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/nsanmemopfn/#a85787eb1162b7d741f8f3b29601e7860">anonymous{NumericalStabilitySanitizer.cpp}::NsanMemOpFn::NsanMemOpFn</a>.</p>

</div>
</div>

### addFnAttribute() {#afa32c5a977d6e4bb922611a29d8f7482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a>.</p>

</div>
</div>

### addFnAttribute() {#aafb72fdaef87bc94257783b6d2bd8817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a>.</p>

</div>
</div>

### addFnAttributes() {#a5d7d1a9d74e14b7535745a80fbc51f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addFnAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add function attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6e7da554442443ffe8928fd5a93086f5">legalizeCallAttributes</a>.</p>

</div>
</div>

### addParamAttribute() {#af3a6727ecc3f601729c11f37a19f93f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addParamAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an argument attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>.</p>

</div>
</div>

### addParamAttribute() {#a731a5e7d7624c487d5dbb8471e1e2857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addParamAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an argument attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>.</p>

</div>
</div>

### addParamAttribute() {#a3f1e8df5d1ec58e81979760331f7808e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addParamAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; ArgNos, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute to the attribute list at the given arg indices.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9cee1ad5adf2690eb7b15f3f5a71dee5">attrIdxToArrayIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="#a361c9c88d8b9972fa0071b508acc9de2">begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a77dcf96d9d822c5289b9506ba191e0d8">end</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### addParamAttributes() {#ae18cffa676178ae60f0692ad4410e940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addParamAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an argument attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>.</p>


<p>Referenced by <a href="#ac19f7bd764bed56888170d913d6915c7">addAllocSizeParamAttr</a>, <a href="#ac6e6fb5739626983930f5cfd8d8b0f07">addDereferenceableOrNullParamAttr</a>, <a href="#a0e8aeaa2675b027d52c93a39ae453471">addDereferenceableParamAttr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6e7da554442443ffe8928fd5a93086f5">legalizeCallAttributes</a>.</p>

</div>
</div>

### addRangeRetAttr() {#a17828da99c4b2a5fc6b0384e6689fb0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::addRangeRetAttr (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the range attribute to the attribute set at the return value index.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1809 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a3e2663f4f16dd7748ba4b0d68836aa5c">addRetAttributes</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### addRetAttribute() {#a32c2b32d61cf856c6a5b2ceb3de7fd0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addRetAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a return value attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### addRetAttribute() {#aca368a465f897becfa3a426fa59c2fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addRetAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a return value attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### addRetAttributes() {#a3e2663f4f16dd7748ba4b0d68836aa5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::addRetAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a return value attribute to the list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>


<p>Referenced by <a href="#a402a2e4e215f051eb560a99327b8c49e">addDereferenceableRetAttr</a>, <a href="#a17828da99c4b2a5fc6b0384e6689fb0c">addRangeRetAttr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>.</p>

</div>
</div>

### begin() {#a361c9c88d8b9972fa0071b508acc9de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList::iterator AttributeList::begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2008 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a3f1e8df5d1ec58e81979760331f7808e">addParamAttribute</a>.</p>

</div>
</div>

### dump() {#ae88787fab8a5d948bd5100aded6fc799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void AttributeList::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2048 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a3fa5ba0fe693cb5a3739950924cb2033">print</a>.</p>

</div>
</div>

### end() {#a77dcf96d9d822c5289b9506ba191e0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList::iterator AttributeList::end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2012 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a3f1e8df5d1ec58e81979760331f7808e">addParamAttribute</a>.</p>

</div>
</div>

### getAllocKind() {#a50abfb2dceb5d84bcbf1cf263e33d7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocFnKind AttributeList::getAllocKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a022e1f0b85c0273bd954327152f43d5a">llvm::AttributeSet::getAllocKind</a> and <a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a>.</p>

</div>
</div>

### getAsString() {#a917739f8f62442b8fea20bbe72cab891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AttributeList::getAsString (unsigned Index, bool InAttrGrp=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attributes at the index as a string.</p>

<p>Declaration at line 972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1989 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a7d970fbb2839d43eea2ca4675abd3380">llvm::AttributeSet::getAsString</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="#a3fa5ba0fe693cb5a3739950924cb2033">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>.</p>

</div>
</div>

### getAttributeAtIndex() {#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute AttributeList::getAttributeAtIndex (unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute object that exists at the given index.</p>

<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1890 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ab50af3bf5ee8727df07c79065d61c204">llvm::AttributeSet::getAttribute</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#abcdfbff6a28275c90eab24a36cbc4240">llvm::CallBase::getAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#affe34085f142d12218c875ad46b506b8">llvm::CallBase::getAttributeAtIndex</a>, <a href="#a90024ee48918b2167a4c9409750d4148">getFnAttr</a>, <a href="#a060fe3a67cf9794919c0559515be2ffc">getFnAttr</a>, <a href="#a4bd6dadb077a5c3503a74b8c5850a805">getParamAttr</a>, <a href="#abe0327f306fb6582ae6b1a55586e2410">getParamAttr</a>, <a href="#ab6fa6901843f6a775399fcbb31fee52a">getRetAttr</a> and <a href="#af4d7d74d32e67259997832a663e14739">replaceAttributeTypeAtIndex</a>.</p>

</div>
</div>

### getAttributeAtIndex() {#ab6b2a026f921a5c932f3320ede3e19ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute AttributeList::getAttributeAtIndex (unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute object that exists at the given index.</p>

<p>Declaration at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1895 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ab50af3bf5ee8727df07c79065d61c204">llvm::AttributeSet::getAttribute</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>

</div>
</div>

### getAttributes() {#ac8d6f220fcf8f327c6c739813df8c4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeList::getAttributes (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The attributes for the specified index are returned.</p>

<p>Declaration at line 811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1993 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9cee1ad5adf2690eb7b15f3f5a71dee5">attrIdxToArrayIdx</a> and <a href="#a7b3e5b33beb7828efdd751c208bfbee9">getNumAttrSets</a>.</p>


<p>Referenced by <a href="#ada583c27bb2634195f2964c7e695a0b3">addAttributeAtIndex</a>, <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="#a917739f8f62442b8fea20bbe72cab891">getAsString</a>, <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a>, <a href="#ab6b2a026f921a5c932f3320ede3e19ac">getAttributeAtIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4081fd08df96363717c46a40ea774794">llvm::IRPosition::getAttrList</a>, <a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a>, <a href="#a704aa0a94c0e6bf8fd60e6e4e463e93d">getParamAlignment</a>, <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a>, <a href="#ada3107abfa5601f959a5403190d230f8">getParamByRefType</a>, <a href="#ab58adac46c3ade432914ab977a69e17e">getParamByValType</a>, <a href="#a9d429f5f04915251440ffdafeb462616">getParamElementType</a>, <a href="#a7b3b0b8961a38c7735a4b9660c42be7b">getParamInAllocaType</a>, <a href="#aa27e1eb608ff6d7e99bbba7d7aaf5b71">getParamPreallocatedType</a>, <a href="#ab9095b759fb33104bdcafec14e2b15c1">getParamStackAlignment</a>, <a href="#a0e3b1e69f26a3784d71f161942e31829">getParamStructRetType</a>, <a href="#a9bb1595f5c255bb9ec836172ad5537e9">getRetAlignment</a>, <a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a>, <a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a>, <a href="#a6590789e70f40b3d72d525bb7327dcbc">hasAttributeAtIndex</a>, <a href="#a180523993bcaffcbbb7cca7a3fc0d51c">hasAttributesAtIndex</a>, <a href="#ad67533111413cc397100c48c82291ec7">intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a23ff02c4dc0c7eb4bc173bc9af346765">llvm::CombinerHelper::matchSDivByConst</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a51f93c65cadd67241250f97598ab1358">llvm::CombinerHelper::matchUDivByConst</a>, <a href="#a3fa5ba0fe693cb5a3739950924cb2033">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>, <a href="#abac2c888655f9fa00f53c7c7e851ff20">removeAttributeAtIndex</a> and <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a>.</p>

</div>
</div>

### getFnAttr() {#a90024ee48918b2167a4c9409750d4148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::AttributeList::getFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return the attribute object that exists for the function.</p>

<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ad6d87a400bc9669540b19739d36b4488">getDeoptLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a838a60b97fcf512dbf9116b564b05f2c">llvm::CallBase::getFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9e46a3a4bf99f8dcea9cb9efb4d977a3">llvm::CallBase::getFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a830906f493a6d5c69ac5a94675c657fb">llvm::parseStatepointDirectivesFromAttrs</a>.</p>

</div>
</div>

### getFnAttr() {#a060fe3a67cf9794919c0559515be2ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::AttributeList::getFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Return the attribute object that exists for the function.</p>

<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a>.</p>

</div>
</div>

### getFnAttrs() {#a1cf553641e8527095ae4c8ec88a2cd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeList::getFnAttrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function attributes are returned.</p>

<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1860 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a80f30a0c0c861405e3eeb6f37c364256">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>, <a href="#a50abfb2dceb5d84bcbf1cf263e33d7d9">getAllocKind</a>, <a href="#ab0eaea88fb8f6bc99c7547113ec906bc">getFnStackAlignment</a>, <a href="#afb984e3fb006d09d90fcc934789cfbd8">getMemoryEffects</a>, <a href="#a98312c308907b87211168eda9c6b605b">getUWTableKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6e7da554442443ffe8928fd5a93086f5">legalizeCallAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### getFnStackAlignment() {#ab0eaea88fb8f6bc99c7547113ec906bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeList::getFnStackAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the stack alignment of the function.</p>

<p>Declaration at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1936 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#aa90abd2918349f316b579114bd44ef17">llvm::AttributeSet::getStackAlignment</a>.</p>

</div>
</div>

### getMemoryEffects() {#afb984e3fb006d09d90fcc934789cfbd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects AttributeList::getMemoryEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns memory effects of the function.</p>

<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1985 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a481ff076fc621dd7d69f160632b8f7df">llvm::AttributeSet::getMemoryEffects</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0af057818885e78ae73169231c243b2a">llvm::CallBase::getMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>.</p>

</div>
</div>

### getNumAttrSets() {#a7b3e5b33beb7828efdd751c208bfbee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AttributeList::getNumAttrSets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2020 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>, <a href="#a1f51ca3a752de383f463899aaf39104d">indexes</a>, <a href="#ad67533111413cc397100c48c82291ec7">intersectWith</a>, <a href="#ad2077a29ae8c3a0a7afe3bd0345f8738">removeAttributesAtIndex</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a>.</p>

</div>
</div>

### getParamAlignment() {#a704aa0a94c0e6bf8fd60e6e4e463e93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeList::getParamAlignment (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the alignment for the specified function parameter.</p>

<p>Declaration at line 910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1904 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#abbebeeab2f7fc663ae61eb5c391a79db">llvm::AttributeSet::getAlignment</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>

</div>
</div>

### getParamAttr() {#a4bd6dadb077a5c3503a74b8c5850a805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::AttributeList::getParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return the attribute object that exists at the arg index.</p>

<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#a50b4d34365cf704260dd9e43796144ea">llvm::CallBase::getParamAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a29461b85f0f7f0d91323ff2e40de2d75">llvm::CallBase::getParamAttr</a>.</p>

</div>
</div>

### getParamAttr() {#abe0327f306fb6582ae6b1a55586e2410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::AttributeList::getParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Return the attribute object that exists at the given index.</p>

<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a>.</p>

</div>
</div>

### getParamAttrs() {#ada7a173c40ca7ac048a4b7099ceb71c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeList::getParamAttrs (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The attributes for the argument or parameter at the given index are returned.</p>

<p>Declaration at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1852 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a80f30a0c0c861405e3eeb6f37c364256">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a31dce9e2b84da293213f996778355b32">llvm::CallBase::getParamAttributes</a>, <a href="#a62f9460daf3f10c40cbeae0fd222cbd9">getParamDereferenceableBytes</a>, <a href="#ac2ac94e810bcb4e307b82617c2d1f22d">getParamDereferenceableOrNullBytes</a>, <a href="#acc215f164f494921945f7cb648056c56">getParamNoFPClass</a>, <a href="#ae6559a2babd0e7bd0f96d7116fb49940">getParamRange</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6e7da554442443ffe8928fd5a93086f5">legalizeCallAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a5c59325f9c3c1526f4439392c892fd41">optimizeCallInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a>.</p>

</div>
</div>

### getParamByRefType() {#ada3107abfa5601f959a5403190d230f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeList::getParamByRefType (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the byref type for the specified function parameter.</p>

<p>Declaration at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1920 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae07c0c5638ef5fa4da628d22a3347e8b">llvm::AttributeSet::getByRefType</a>.</p>

</div>
</div>

### getParamByValType() {#ab58adac46c3ade432914ab977a69e17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeList::getParamByValType (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the byval type for the specified function parameter.</p>

<p>Declaration at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a2ade48bec43f06da0e142b9c8d27ccb1">llvm::AttributeSet::getByValType</a>.</p>

</div>
</div>

### getParamDereferenceableBytes() {#a62f9460daf3f10c40cbeae0fd222cbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeList::getParamDereferenceableBytes (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of dereferenceable bytes (or zero if unknown) of an arg.</p>

<p>Declaration at line 944 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1948 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#abac98c505a75cb4d3883913ca0aa0437">llvm::AttributeSet::getDereferenceableBytes</a> and <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a>.</p>

</div>
</div>

### getParamDereferenceableOrNullBytes() {#ac2ac94e810bcb4e307b82617c2d1f22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeList::getParamDereferenceableOrNullBytes (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of dereferenceable_or_null bytes (or zero if unknown) of an arg.</p>

<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1957 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#aec6315746619b1a42c4a466582f82d34">llvm::AttributeSet::getDereferenceableOrNullBytes</a> and <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a>.</p>

</div>
</div>

### getParamElementType() {#a9d429f5f04915251440ffdafeb462616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeList::getParamElementType (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the elementtype type for the specified function parameter.</p>

<p>Declaration at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1932 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae05f76fbca2d63deaa0afcdfad5b60d0">llvm::AttributeSet::getElementType</a>.</p>

</div>
</div>

### getParamInAllocaType() {#a7b3b0b8961a38c7735a4b9660c42be7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeList::getParamInAllocaType (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the inalloca type for the specified function parameter.</p>

<p>Declaration at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1928 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a1948967a0a7675ab316c1b30d2cabdef">llvm::AttributeSet::getInAllocaType</a>.</p>

</div>
</div>

### getParamNoFPClass() {#acc215f164f494921945f7cb648056c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest AttributeList::getParamNoFPClass (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the disallowed floating-point classes of the argument value.</p>

<p>Declaration at line 961 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1973 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ac65bf55d7831e567f14c791ab3a9376f">llvm::AttributeSet::getNoFPClass</a> and <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a>.</p>

</div>
</div>

### getParamPreallocatedType() {#aa27e1eb608ff6d7e99bbba7d7aaf5b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeList::getParamPreallocatedType (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the preallocated type for the specified function parameter.</p>

<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1924 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ab7f8b65e8459440e4a71c3076cdad21d">llvm::AttributeSet::getPreallocatedType</a>.</p>

</div>
</div>

### getParamRange() {#ae6559a2babd0e7bd0f96d7116fb49940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; AttributeList::getParamRange (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get range (or std::nullopt if unknown) of an arg.</p>

<p>Declaration at line 955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1962 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ab50af3bf5ee8727df07c79065d61c204">llvm::AttributeSet::getAttribute</a>, <a href="#ada7a173c40ca7ac048a4b7099ceb71c0">getParamAttrs</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a10eb642c38648a5edb4a6bc7ce217a17">llvm::Attribute::getRange</a>.</p>

</div>
</div>

### getParamStackAlignment() {#ab9095b759fb33104bdcafec14e2b15c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeList::getParamStackAlignment (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the stack alignment for the specified function parameter.</p>

<p>Declaration at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1908 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#aa90abd2918349f316b579114bd44ef17">llvm::AttributeSet::getStackAlignment</a>.</p>

</div>
</div>

### getParamStructRetType() {#a0e3b1e69f26a3784d71f161942e31829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeList::getParamStructRetType (unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the sret type for the specified function parameter.</p>

<p>Declaration at line 919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1916 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a73e118d056b68673a2c5b4f85d1a4c17">llvm::AttributeSet::getStructRetType</a>.</p>

</div>
</div>

### getRawPointer() {#a4cb7d44e0a657e7807506627647ea203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::AttributeList::getRawPointer ()</td>
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

<p>Return a raw pointer that uniquely identifies this attribute list.</p>

<p>Definition at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

### getRetAlignment() {#a9bb1595f5c255bb9ec836172ad5537e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeList::getRetAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the alignment of the return value.</p>

<p>Declaration at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1900 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#abbebeeab2f7fc663ae61eb5c391a79db">llvm::AttributeSet::getAlignment</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### getRetAttr() {#ab6fa6901843f6a775399fcbb31fee52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::AttributeList::getRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return the attribute for the given attribute kind for the return value.</p>

<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### getRetAttrs() {#a5604157867b3d226260f6388b987e49a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeList::getRetAttrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The attributes for the ret value are returned.</p>

<p>Declaration at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1856 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a82be2ba8b164fb0cf70e254f9c8a13a3">llvm::CallBase::getRetAttributes</a>, <a href="#abda2f1696e90762ee9b7b64065c64969">getRetDereferenceableBytes</a>, <a href="#ae6b7413239e3f901328769ef2b5a23b0">getRetDereferenceableOrNullBytes</a>, <a href="#a7d05f2b6b9067ce92dc32f2f6443df5d">getRetNoFPClass</a>, <a href="#a3a5a24c43e105c203f779ca9a0ae0093">getRetStackAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### getRetDereferenceableBytes() {#abda2f1696e90762ee9b7b64065c64969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeList::getRetDereferenceableBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of dereferenceable bytes (or zero if unknown) of the return value.</p>

<p>Declaration at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1944 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#abac98c505a75cb4d3883913ca0aa0437">llvm::AttributeSet::getDereferenceableBytes</a> and <a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a>.</p>

</div>
</div>

### getRetDereferenceableOrNullBytes() {#ae6b7413239e3f901328769ef2b5a23b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeList::getRetDereferenceableOrNullBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of dereferenceable_or_null bytes (or zero if unknown) of the return value.</p>

<p>Declaration at line 948 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1952 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#aec6315746619b1a42c4a466582f82d34">llvm::AttributeSet::getDereferenceableOrNullBytes</a> and <a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a>.</p>

</div>
</div>

### getRetNoFPClass() {#a7d05f2b6b9067ce92dc32f2f6443df5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest AttributeList::getRetNoFPClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the disallowed floating-point classes of the return value.</p>

<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1969 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ac65bf55d7831e567f14c791ab3a9376f">llvm::AttributeSet::getNoFPClass</a> and <a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a>.</p>

</div>
</div>

### getRetStackAlignment() {#a3a5a24c43e105c203f779ca9a0ae0093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeList::getRetStackAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the stack alignment of the return value.</p>

<p>Declaration at line 937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1940 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a5604157867b3d226260f6388b987e49a">getRetAttrs</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#aa90abd2918349f316b579114bd44ef17">llvm::AttributeSet::getStackAlignment</a>.</p>

</div>
</div>

### getUWTableKind() {#a98312c308907b87211168eda9c6b605b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UWTableKind AttributeList::getUWTableKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the unwind table kind requested for the function.</p>

<p>Declaration at line 964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1977 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a1cf553641e8527095ae4c8ec88a2cd92">getFnAttrs</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a869ddfab05d4e80046bf248d211e3e96">llvm::AttributeSet::getUWTableKind</a>.</p>

</div>
</div>

### hasAttributeAtIndex() {#a09a57939ead526bbae148522e31f198d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasAttributeAtIndex (unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists at the given index.</p>

<p>Declaration at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1864 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a51fc96070af1597981c3000171e1a5ab">llvm::AttributeSet::hasAttribute</a>.</p>


<p>Referenced by <a href="#a65daa7efe6ca841a6772474c62137aa3">hasFnAttr</a>, <a href="#ab04846c93ea7d802afbaa48efd84f37e">hasParamAttr</a>, <a href="#a726d79ceb91ce0b86d8dfeb8d50dd0b1">hasParamAttr</a>, <a href="#afe4e348d7ff2f6b76dcaa69382b78980">hasRetAttr</a> and <a href="#a1aeb561c53719a10aecb2757ef0fff79">hasRetAttr</a>.</p>

</div>
</div>

### hasAttributeAtIndex() {#a6590789e70f40b3d72d525bb7327dcbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasAttributeAtIndex (unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists at the given index.</p>

<p>Declaration at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1869 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a51fc96070af1597981c3000171e1a5ab">llvm::AttributeSet::hasAttribute</a>.</p>

</div>
</div>

### hasAttributesAtIndex() {#a180523993bcaffcbbb7cca7a3fc0d51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasAttributesAtIndex (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if attribute exists at the given index.</p>

<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1873 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a03e88ecc68b413d829593f385d84dca6">llvm::AttributeSet::hasAttributes</a>.</p>


<p>Referenced by <a href="#ad78e7e25df5981be38867dd67df81f92">hasFnAttrs</a>, <a href="#a3737e67f34f29a0244b6e1b236652bc8">hasParamAttrs</a> and <a href="#ac58b17d02803ec68e3dbfc82a8f45d5e">hasRetAttrs</a>.</p>

</div>
</div>

### hasAttrSomewhere() {#a75d6c6f22bf21c4725e3f9be5ec0b07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasAttrSomewhere (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, unsigned * Index=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified attribute is set for at least one parameter or for the return value.</p>


<p>If Index is not nullptr, the index of a parameter with the specified attribute is provided.</p>


<p>Declaration at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1885 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ac26dae5c257bfaab5aa15cab7255f107">llvm::AArch64RegisterInfo::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#a948f65c38b613d36deb501eb8b8476c8">llvm::SystemZELFRegisters::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a2a4f0d74a9e54517b5009c2ac31503b5">llvm::AArch64RegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#abb9d03a862069b7f3c4f446e0be8b826">llvm::ARMBaseRegisterInfo::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#af9a3f20abd67b17fdb105aa2fe63e08d">llvm::SystemZELFRegisters::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aaab57b42c1306819f384fbc8917e728b">llvm::AArch64RegisterInfo::getDarwinCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ace1d2fbafd80bd71d27a949593da97f7">llvm::AArch64RegisterInfo::getDarwinCallPreservedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af917fe9cdb70db029cf2ddd236fae738">getFixedObjectSize</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>.</p>

</div>
</div>

### hasFnAttr() {#a61054ea97168f709c1e46345f80c16a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists for the function.</p>

<p>Declaration at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ad6d87a400bc9669540b19739d36b4488">getDeoptLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab72c286743e675ffbe81f7c9e9771fa5">llvm::AArch64TargetLowering::getOptimalMemOpLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a5de718ef1b1e3a0da7a3f35a139d5197">llvm::AArch64TargetLowering::getOptimalMemOpType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#abd29a7e70a14fb7b45ff277e5c935424">llvm::ARMTargetLowering::getOptimalMemOpType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a24d0c79fc6f4ac2aca2deb4d48d0605c">llvm::RISCVTargetLowering::getOptimalMemOpType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a53dee73973a09e035447943bb5bde29e">llvm::X86TargetLowering::getOptimalMemOpType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a494cbaa147365ad6fd75c3bb3297c8bd">llvm::AArch64TargetLowering::isIntDivCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ad0f72d43380dc7896c344a32bb9b4953">llvm::RISCVTargetLowering::isIntDivCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac7a7243ff0d08f8e17239f3fab12a20f">llvm::X86TargetLowering::isIntDivCheap</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#aabd8a84d1694dda293cbdce6bde5fc11">maySpeculateLanes</a>.</p>

</div>
</div>

### hasFnAttr() {#a65daa7efe6ca841a6772474c62137aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists for the function.</p>

<p>Declaration at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1881 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a>.</p>

</div>
</div>

### hasFnAttrs() {#ad78e7e25df5981be38867dd67df81f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasFnAttrs ()</td>
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

<p>Return true the attributes exist for the function.</p>

<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#a180523993bcaffcbbb7cca7a3fc0d51c">hasAttributesAtIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>.</p>

</div>
</div>

### hasParamAttr() {#ab04846c93ea7d802afbaa48efd84f37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return true if the attribute exists for the given argument.</p>

<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### hasParamAttr() {#a726d79ceb91ce0b86d8dfeb8d50dd0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Return true if the attribute exists for the given argument.</p>

<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a>.</p>

</div>
</div>

### hasParamAttrs() {#a3737e67f34f29a0244b6e1b236652bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasParamAttrs (unsigned ArgNo)</td>
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

<p>Return true if attributes exists for the given argument.</p>

<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a180523993bcaffcbbb7cca7a3fc0d51c">hasAttributesAtIndex</a>.</p>

</div>
</div>

### hasParentContext() {#aa34082941d26848b9383954c70054792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeList::hasParentContext (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this attribute list belongs to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>

<p>Declaration at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2000 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a5269e6b95f5007a652d53ca847cca6f3">isEmpty</a>.</p>

</div>
</div>

### hasRetAttr() {#afe4e348d7ff2f6b76dcaa69382b78980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return true if the attribute exists for the return value.</p>

<p>Definition at line 848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a>.</p>

</div>
</div>

### hasRetAttr() {#a1aeb561c53719a10aecb2757ef0fff79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasRetAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Return true if the attribute exists for the return value.</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a09a57939ead526bbae148522e31f198d">hasAttributeAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### hasRetAttrs() {#ac58b17d02803ec68e3dbfc82a8f45d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::hasRetAttrs ()</td>
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

<p>Return true if attributes exist for the return value.</p>

<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a180523993bcaffcbbb7cca7a3fc0d51c">hasAttributesAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>.</p>

</div>
</div>

### indexes() {#a1f51ca3a752de383f463899aaf39104d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">index_iterator llvm::AttributeList::indexes ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this to iterate over the valid attribute indexes.</p>

<p>Definition at line 1013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a7b3e5b33beb7828efdd751c208bfbee9">getNumAttrSets</a>.</p>


<p>Referenced by <a href="#a3fa5ba0fe693cb5a3739950924cb2033">print</a>.</p>

</div>
</div>

### intersectWith() {#ad67533111413cc397100c48c82291ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AttributeList &gt; AttributeList::intersectWith (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to intersect this <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> with Other.</p>


<p>Returns std::nullopt if the two lists are inherently incompatible (imply different behavior, not just analysis).</p>


<p>Declaration at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>, <a href="#a7b3e5b33beb7828efdd751c208bfbee9">getNumAttrSets</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### isEmpty() {#a5269e6b95f5007a652d53ca847cca6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeList::isEmpty ()</td>
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

<p>Return true if there are no attributes.</p>

<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/valueenumerator/#a59914e9dccb00b57d22367af49ee63ce">llvm::dxil::ValueEnumerator::getAttributeListID</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a62665f1ab639a21566eb89d827446efc">llvm::ValueEnumerator::getAttributeListID</a>, <a href="#aa34082941d26848b9383954c70054792">hasParentContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6e7da554442443ffe8928fd5a93086f5">legalizeCallAttributes</a> and <a href="/web-llvm/docs/api/structs/llvm/gvnpass/expression/#a63b54431c6f3c26280339dea8c89ca61">llvm::GVNPass::Expression::operator==</a>.</p>

</div>
</div>

### print() {#a3fa5ba0fe693cb5a3739950924cb2033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AttributeList::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2024 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a>, <a href="#a917739f8f62442b8fea20bbe72cab891">getAsString</a>, <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>, <a href="#a1f51ca3a752de383f463899aaf39104d">indexes</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>


<p>Referenced by <a href="#ae88787fab8a5d948bd5100aded6fc799">dump</a>.</p>

</div>
</div>

### removeAttribute() {#a4be93bfc0865b2bc93136f67be092471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>.</p>

</div>
</div>

### removeAttributeAtIndex() {#a0fdf10b37833524db3870b2dd98693a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::removeAttributeAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the specified index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1747 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="#a4be93bfc0865b2bc93136f67be092471">removeAttribute</a>, <a href="#ac22a21db26809ce1d18b8ee41295b474">removeFnAttribute</a>, <a href="#ad0308f412730541938ee571fea17925d">removeFnAttribute</a>, <a href="#aabcd25c0256b5c210d20ada500ca7faf">removeParamAttribute</a>, <a href="#a4f4ebc3eed35009a0cc35d7a8f6d878e">removeParamAttribute</a>, <a href="#aec0a2e70b99735033d6c8565181fbacf">removeRetAttribute</a>, <a href="#a1aad76febe84315bf8b5cae3336bd612">removeRetAttribute</a> and <a href="#af4d7d74d32e67259997832a663e14739">replaceAttributeTypeAtIndex</a>.</p>

</div>
</div>

### removeAttributeAtIndex() {#abac2c888655f9fa00f53c7c7e851ff20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::removeAttributeAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the specified index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1756 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>

</div>
</div>

### removeAttributesAtIndex() {#a2240c7569f0786a6bea570d21e924060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::removeAttributesAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attributes at the specified index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ac8d6f220fcf8f327c6c739813df8c4c9">getAttributes</a>.</p>


<p>Referenced by <a href="#ab6847a760305fc6dfb31721c185a1aa6">removeFnAttributes</a>, <a href="#ad58229d1b1450ad0311f0a138fce5a73">removeFnAttributes</a>, <a href="#a14fe429b8e7e3af4cab47a826ae6918f">removeParamAttributes</a>, <a href="#a161139dd3cce264762282c9009eb1acd">removeParamAttributes</a> and <a href="#a42c63d5e6fd828727093857e31c22cd3">removeRetAttributes</a>.</p>

</div>
</div>

### removeAttributesAtIndex() {#ad2077a29ae8c3a0a7afe3bd0345f8738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::removeAttributesAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all attributes at the specified index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1777 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9cee1ad5adf2690eb7b15f3f5a71dee5">attrIdxToArrayIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a7b3e5b33beb7828efdd751c208bfbee9">getNumAttrSets</a>.</p>

</div>
</div>

### removeFnAttribute() {#ac22a21db26809ce1d18b8ee41295b474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the function index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>.</p>

</div>
</div>

### removeFnAttribute() {#ad0308f412730541938ee571fea17925d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeFnAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the function index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>.</p>

</div>
</div>

### removeFnAttributes() {#ad58229d1b1450ad0311f0a138fce5a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeFnAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the function index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a>.</p>

</div>
</div>

### removeFnAttributes() {#ab6847a760305fc6dfb31721c185a1aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeFnAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the attributes at the function index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a> and <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a>.</p>

</div>
</div>

### removeParamAttribute() {#aabcd25c0256b5c210d20ada500ca7faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeParamAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the specified arg index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>.</p>

</div>
</div>

### removeParamAttribute() {#a4f4ebc3eed35009a0cc35d7a8f6d878e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeParamAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the specified arg index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>.</p>

</div>
</div>

### removeParamAttributes() {#a161139dd3cce264762282c9009eb1acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeParamAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the specified arg index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>.</p>

</div>
</div>

### removeParamAttributes() {#a14fe429b8e7e3af4cab47a826ae6918f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeParamAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all attributes at the specified arg index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">FirstArgIndex</a> and <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a>.</p>

</div>
</div>

### removeRetAttribute() {#aec0a2e70b99735033d6c8565181fbacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeRetAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the return value index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### removeRetAttribute() {#a1aad76febe84315bf8b5cae3336bd612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeRetAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the return value index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### removeRetAttributes() {#a42c63d5e6fd828727093857e31c22cd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::removeRetAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified attribute at the return value index from this attribute list.</p>


<p>Returns a new list because attribute lists are immutable.</p>


<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a2240c7569f0786a6bea570d21e924060">removeAttributesAtIndex</a> and <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">ReturnIndex</a>.</p>

</div>
</div>

### replaceAttributeTypeAtIndex() {#af4d7d74d32e67259997832a663e14739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::AttributeList::replaceAttributeTypeAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReplacementTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the type contained by attribute <span class="doxyComputerOutput">AttrKind</span> at index <span class="doxyComputerOutput">ArgNo</span> wih <span class="doxyComputerOutput">ReplacementTy</span>, preserving all other attributes.</p>

<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">getAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#acd074cd44460fcae84c1608fa9deba1e">llvm::Attribute::getWithNewType</a> and <a href="#a0fdf10b37833524db3870b2dd98693a8">removeAttributeAtIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setAttributesAtIndex() {#ae00e1c0c71d57328a34d6b09fe44d7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::setAttributesAtIndex (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### pImpl {#af1343a33d10b62461677274e4b354eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeListImpl* llvm::AttributeList::pImpl = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The attributes that we are managing.</p>


<p>This can be null to represent the empty attributes list.</p>


<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a4ac0d01bf5ca24e679de53067c8f6a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &gt; &gt; Attrs)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> with the specified parameters in it.</p>

<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1499 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ab58814a61429a0b976eae58a0695c206">addAttributesAtIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a9ae7045e9bc2bab2a756c683a24f45">llvm::CloneFunctionAttributesInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#ad915c31dcf8d35cf0affa3f8f13a043b">llvm::AtomicInfo::EmitAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1484bdcb6b4c84ceb447270f8acca352">llvm::emitMemCpyChk</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a>, <a href="#a4387a04798ee02597a248ac196fc1d53">get</a>, <a href="#a15fc36bf8d33e06423d939bb34bc9305">get</a>, <a href="#abc9345ab199d872cbb5a7c31b84a4cde">get</a>, <a href="#aa3e752c843b2d32061a0dfbb3b784eb9">get</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a7f97c03389898566620894f7ba674df7">llvm::GlobalVariable::getAttributesAsList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3c16ae9b6c38652cd59f72eeecc4e176">getReturnAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a1a4145a18b32a1bc1030bf789e370963">InsertCall</a>, <a href="#ad67533111413cc397100c48c82291ec7">intersectWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### get() {#aa0934a03f7182abfbf5e57fc4e7c7c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &gt; &gt; Attrs)</td>
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



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1532 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9cee1ad5adf2690eb7b15f3f5a71dee5">attrIdxToArrayIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">FunctionIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>.</p>

</div>
</div>

### get() {#ad544515efb693b15ac9855c6be03189b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> FnAttrs, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> RetAttrs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &gt; ArgAttrs)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> from attribute sets for a function, its return value, and all of its arguments.</p>

<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1559 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a03e88ecc68b413d829593f385d84dca6">llvm::AttributeSet::hasAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a33da2ddf6f447892591c86d9d3771b9c">llvm::ArrayRef&lt; T &gt;::take_front</a>.</p>

</div>
</div>

### get() {#ac0b476a2ef81faca335499a5cafb9241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &gt; Attrs)</td>
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

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> with the specified parameters in it.</p>

<p>Declaration at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1642 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a3f05fda2b6c78a87f8d6e608b55693f7">llvm::AttrBuilder::merge</a>.</p>

</div>
</div>

### get() {#a4387a04798ee02597a248ac196fc1d53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> &gt; Kinds)</td>
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



<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1615 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a> and <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a>.</p>

</div>
</div>

### get() {#a15fc36bf8d33e06423d939bb34bc9305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> &gt; Kinds, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Values)</td>
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



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### get() {#abc9345ab199d872cbb5a7c31b84a4cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Kind)</td>
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



<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a> and <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a>.</p>

</div>
</div>

### get() {#acf23368370765012fba0a78c1b42fdf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> Attrs)</td>
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



<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a2870b20bc1c79303e5d4cc6c1c97a21f">AttributeSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9cee1ad5adf2690eb7b15f3f5a71dee5">attrIdxToArrayIdx</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### get() {#aa3e752c843b2d32061a0dfbb3b784eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
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



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a5d48a1514b932419965e18798ab4f9b8">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a4ac0d01bf5ca24e679de53067c8f6a44">get</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#a309fbc0a0cba5a9d8f4ada5402f8fbe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList AttributeList::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &gt; AttrSets)</td>
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



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
