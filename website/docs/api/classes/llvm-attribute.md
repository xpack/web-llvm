---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/attribute
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Attribute` Class

<p>Functions, function parameters, and return types can have attributes to indicate how they should be treated by optimizations and code generation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Attribute { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttrKind { <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This enumeration lists the attributes that can be associated with parameters, function results, or the function itself. <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c35fe2eda413e2962cb7f4db6ae88fa">Attribute</a> (AttributeImpl *A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c489bca200589e7b76e8220f53bfa7f">operator==</a> (Attribute A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality and non-equality operators. <a href="#a0c489bca200589e7b76e8220f53bfa7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66141548ab771821d839ebc03d828460">operator!=</a> (Attribute A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5698841d3390f68811f92c61746f5aa">operator&lt;</a> (Attribute A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Less-than operator. Useful for sorting the attributes list. <a href="#af5698841d3390f68811f92c61746f5aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd074cd44460fcae84c1608fa9deba1e">getWithNewType</a> (LLVMContext &amp;Context, Type *ReplacementTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a typed attribute, return the equivalent attribute with the type changed to <span class="doxyComputerOutput">ReplacementTy</span>. <a href="#acd074cd44460fcae84c1608fa9deba1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4d4e6a852d283cafe0b0413cfb6430">isEnumAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is an <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> type. <a href="#a0f4d4e6a852d283cafe0b0413cfb6430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142250c7b671591390912db907532036">isIntAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is an integer attribute. <a href="#a142250c7b671591390912db907532036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is a string (target-dependent) attribute. <a href="#a0571df3e57128211e09cba4544aa9ca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fc71def3a243f7c93d39db21344240">isTypeAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is a type attribute. <a href="#ab6fc71def3a243f7c93d39db21344240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a259761353a6ddbb637d44b5e18a65a26">isConstantRangeAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> attribute. <a href="#a259761353a6ddbb637d44b5e18a65a26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6eebf7187794b85e9546dfe4fb61b6c">isConstantRangeListAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is a <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute. <a href="#ac6eebf7187794b85e9546dfe4fb61b6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4d22686e85732b2fef71e3c45531c6">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is any kind of attribute. <a href="#adf4d22686e85732b2fef71e3c45531c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a> (AttrKind Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute is present. <a href="#ad1f5f68d66cc65213e32d67a78992fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f8ffb34d5d5ecd8879bb76277e660c">hasAttribute</a> (StringRef Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the target-dependent attribute is present. <a href="#aa9f8ffb34d5d5ecd8879bb76277e660c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7776eef7d7515a9288bbc4e4654388">hasKindAsEnum</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the attribute's kind can be represented as an enum (Enum, Integer, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>, or <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute). <a href="#a9e7776eef7d7515a9288bbc4e4654388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fea074fd9120ff82abd8f9e0036a12a">getKindAsEnum</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's kind as an enum (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a>). <a href="#a6fea074fd9120ff82abd8f9e0036a12a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db9b109e0e28e38eb43086b679dc271">getValueAsInt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's value as an integer. <a href="#a1db9b109e0e28e38eb43086b679dc271">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f42ed02a8993b84bdf97da5d54d097">getValueAsBool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's value as a boolean. <a href="#a70f42ed02a8993b84bdf97da5d54d097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad8f83f8d6165314fe8f173645dd458">getKindAsString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's kind as a string. <a href="#a3ad8f83f8d6165314fe8f173645dd458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a968930aea9d9efa8d46dd890fce75643">getValueAsString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's value as a string. <a href="#a968930aea9d9efa8d46dd890fce75643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1705f60feb6936d4e9cf126347c5e7">getValueAsType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's value as a <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#aff1705f60feb6936d4e9cf126347c5e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e419fa4236059d9acf513a2d9b603b">getValueAsConstantRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's value as a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>. <a href="#a77e419fa4236059d9acf513a2d9b603b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a771ed3c28612ca7852e1d9c62ab05">getValueAsConstantRangeList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute's value as a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> array. <a href="#a93a771ed3c28612ca7852e1d9c62ab05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c88577e9470957be5ad4e4d401146a">getAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the alignment field of an attribute as a byte alignment value. <a href="#af1c88577e9470957be5ad4e4d401146a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16611668da23acd765262e5d079f462">getStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the stack alignment field of an attribute as a byte alignment value. <a href="#ae16611668da23acd765262e5d079f462">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7458f7bdc291db1a43ad26f149cfed">getDereferenceableBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of dereferenceable bytes from the dereferenceable attribute. <a href="#a7a7458f7bdc291db1a43ad26f149cfed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49fa360a9d36f3b7668437a0385bf436">getDereferenceableOrNullBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of dereferenceable_or_null bytes from the dereferenceable_or_null attribute. <a href="#a49fa360a9d36f3b7668437a0385bf436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bac674280b8fed3e09ea688b91bb1a0">getAllocSizeArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the argument numbers for the allocsize attribute. <a href="#a5bac674280b8fed3e09ea688b91bb1a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2340c9d2c47ffa7fc07568ba059b62a2">getVScaleRangeMin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum value for the vscale_range attribute. <a href="#a2340c9d2c47ffa7fc07568ba059b62a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190a29f5df3964b269383c0d6fba0ea9">getVScaleRangeMax</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum value for the vscale_range attribute or std::nullopt when unknown. <a href="#a190a29f5df3964b269383c0d6fba0ea9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c175adc74c833d57ab21f177e99c73">getUWTableKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2473a7c5ee60c5a3ae90782d494b436e">getAllocKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c68b48aeb5f2440cf65d5e8b2e16040">getMemoryEffects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns memory effects. <a href="#a7c68b48aeb5f2440cf65d5e8b2e16040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/captureinfo">CaptureInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af356410c6b277e5a12369be877371edb">getCaptureInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns information from captures attribute. <a href="#af356410c6b277e5a12369be877371edb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b18d31b344ea210a82c4028b7684946">getNoFPClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> for nofpclass. <a href="#a6b18d31b344ea210a82c4028b7684946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10eb642c38648a5edb4a6bc7ce217a17">getRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the range attribute. <a href="#a10eb642c38648a5edb4a6bc7ce217a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76851ce1968746201d39b872e122e530">getInitializes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of the initializes attribute. <a href="#a76851ce1968746201d39b872e122e530">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a> (bool InAttrGrp=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> is converted to a string of equivalent mnemonic. <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f63a12196c8f1a595311d67a4bdd3d">hasParentContext</a> (LLVMContext &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this attribute belongs to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#ab4f63a12196c8f1a595311d67a4bdd3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af541f10f39f755eb0713d404017cae4e">cmpKind</a> (Attribute A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to sort attribute by kind. <a href="#af541f10f39f755eb0713d404017cae4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8133f46432136f4daf84ceaa63734e78">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3acc035135394d0b3ccf4c062d72810">getRawPointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a raw pointer that uniquely identifies this attribute. <a href="#ab3acc035135394d0b3ccf4c062d72810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55318c4d90472ba993547b9c6c078755">pImpl</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad343d2ea041d596a04db3252e3017cad">isEnumAttrKind</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d5f8ba4215304f89a401248abed393">isIntAttrKind</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b9bbfc65ea129fe5c7fe72ea004d00">isTypeAttrKind</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae62cfe03629c96ee1cc2697c3d66117">isConstantRangeAttrKind</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3f018f989664ac6588f604ccca98143">isConstantRangeListAttrKind</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d1daaf72feb4d1ecb59df592bdc3d7">canUseAsFnAttr</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade0ea4e187f04c1339866dab77cb7181">canUseAsParamAttr</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44151f9f498f20ce0aa95010c25fd2d4">canUseAsRetAttr</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b008eee2735671b4bfdabd4df07b35">intersectMustPreserve</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa586fffdd286955ca876838f11a5f6d3">intersectWithAnd</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d708ef8b38a269452e88f7c0fcfa5f8">intersectWithMin</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f48b3f20c58e11564df402e02a1592">intersectWithCustom</a> (AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43708098bd7085788a680fd02f47c750">get</a> (LLVMContext &amp;Context, AttrKind Kind, uint64_t Val=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a uniquified <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object. <a href="#a43708098bd7085788a680fd02f47c750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3469e685d3fadac587ccaa4ca8144d70">get</a> (LLVMContext &amp;Context, StringRef Kind, StringRef Val=StringRef())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438a746d30d8cd255a96ffb06749602e">get</a> (LLVMContext &amp;Context, AttrKind Kind, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f33826a7081abb8cd61583464d7ca51">get</a> (LLVMContext &amp;Context, AttrKind Kind, const ConstantRange &amp;CR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a3342c858856b421c6e2c306aaf241">get</a> (LLVMContext &amp;Context, AttrKind Kind, ArrayRef&lt; ConstantRange &gt; Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8975f28d8418cad8ea770575736b81">getWithAlignment</a> (LLVMContext &amp;Context, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a uniquified <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object that has the specific alignment set. <a href="#afb8975f28d8418cad8ea770575736b81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d1cac7b43caeef3f78bd86429a881a">getWithStackAlignment</a> (LLVMContext &amp;Context, Align Alignment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2c8769ea6c7af6f24285e87a7e3aa1">getWithDereferenceableBytes</a> (LLVMContext &amp;Context, uint64_t Bytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afbda215c9d4599ff4edcac57340268">getWithDereferenceableOrNullBytes</a> (LLVMContext &amp;Context, uint64_t Bytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f90f8b9a9209911cdd0573c4e25388e">getWithAllocSizeArgs</a> (LLVMContext &amp;Context, unsigned ElemSizeArg, const std::optional&lt; unsigned &gt; &amp;NumElemsArg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b20ebfa9bcf271438ffda63f623d0f5">getWithVScaleRangeArgs</a> (LLVMContext &amp;Context, unsigned MinValue, unsigned MaxValue)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc00a93ed593f135b4b54de32d484e6b">getWithByValType</a> (LLVMContext &amp;Context, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c2b2c1eb0fcfe3f1e14192eae42eb4">getWithStructRetType</a> (LLVMContext &amp;Context, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e54dbebfcc4ad4c764af94cab0979e">getWithByRefType</a> (LLVMContext &amp;Context, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbd08b6c2cddabb8dfa41272133f027">getWithPreallocatedType</a> (LLVMContext &amp;Context, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd67d0c42d48781c7d2819638c109a47">getWithInAllocaType</a> (LLVMContext &amp;Context, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600a01b826220fa1896bcecb198184e1">getWithUWTableKind</a> (LLVMContext &amp;Context, UWTableKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf42001b3cc4c8c631902cbb48106d5">getWithMemoryEffects</a> (LLVMContext &amp;Context, MemoryEffects ME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6913b6616150e5f65ef723520dbcc77">getWithNoFPClass</a> (LLVMContext &amp;Context, FPClassTest Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c53a4c5456480dc377772d5d2f4f832">getAttrKindFromName</a> (StringRef AttrName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f1de7d65958c48ef95760927081625c">getNameFromAttrKind</a> (Attribute::AttrKind AttrKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0a1acb1f888349f2e47466c73f2d97">isExistingAttribute</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the provided string matches the IR name of an attribute. <a href="#a9b0a1acb1f888349f2e47466c73f2d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a3efd17863479b39d4abc926b85336">fromRawPointer</a> (void *RawPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an attribute from a raw pointer created by getRawPointer. <a href="#ae1a3efd17863479b39d4abc926b85336">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e34d497535013df4857850c013d85f">NumIntAttrKinds</a> = LastIntAttr - FirstIntAttr + 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043cae0ec5fae762c2f2e5c108da971e">NumTypeAttrKinds</a> = LastTypeAttr - FirstTypeAttr + 1</td>
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

<p>Functions, function parameters, and return types can have attributes to indicate how they should be treated by optimizations and code generation.</p>


<p>This class represents one of those attributes. It's light-weight and should be passed around by-value.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AttrKind {#aab7ee4b8fd1d3e7e4cea87868855e60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Attribute::AttrKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This enumeration lists the attributes that can be associated with parameters, function results, or the function itself.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c"></a></td>
<td class="doxyEnumItemDescription">No attributes have been set</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndAttrKinds<a id="aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b"></a></td>
<td class="doxyEnumItemDescription">Sentinel value useful for loops</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EmptyKey<a id="aab7ee4b8fd1d3e7e4cea87868855e60eaa108685538d49543443a0ce281efd1d8"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> as Empty key for <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> of <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TombstoneKey<a id="aab7ee4b8fd1d3e7e4cea87868855e60ea3e672d8a791835da7d662b61f79590a6"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> as Tombstone key for <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> of <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a></td>
</tr>

</table>
</dd>
</dl>


<p>Note: The ‘uwtable` attribute is about the ABI or the user mandating an entry in the unwind table. The ‘nounwind` attribute is about an exception passing by the function.</p>


<p>In a theoretical system that uses tables for profiling and SjLj for exceptions, they would be fully independent. In a normal system that uses tables for both, the semantics are:</p>


<p>nil = Needs an entry because an exception might pass by. nounwind = No need for an entry uwtable = Needs an entry because the ABI says so and because an exception might pass by. uwtable + nounwind = Needs an entry because the ABI says so.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Attribute() {#a7074bcba216ff000eb0d163b53868c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Attribute::Attribute ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="#ae1a3efd17863479b39d4abc926b85336">fromRawPointer</a>, <a href="#a39a3342c858856b421c6e2c306aaf241">get</a>, <a href="#a1f33826a7081abb8cd61583464d7ca51">get</a>, <a href="#a438a746d30d8cd255a96ffb06749602e">get</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a> and <a href="#a3469e685d3fadac587ccaa4ca8144d70">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Attribute() {#a4c35fe2eda413e2962cb7f4db6ae88fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Attribute::Attribute (<a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> * A)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a66141548ab771821d839ebc03d828460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::operator!= (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### operator&lt;() {#af5698841d3390f68811f92c61746f5aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::operator&lt; (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Less-than operator. Useful for sorting the attributes list.</p>

<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### operator==() {#a0c489bca200589e7b76e8220f53bfa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::operator== (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
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

<p>Equality and non-equality operators.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cmpKind() {#af541f10f39f755eb0713d404017cae4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Attribute::cmpKind (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to sort attribute by kind.</p>

<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### getAlignment() {#af1c88577e9470957be5ad4e4d401146a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign Attribute::getAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the alignment field of an attribute as a byte alignment value.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### getAllocKind() {#a2473a7c5ee60c5a3ae90782d494b436e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocFnKind Attribute::getAllocKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>.</p>

</div>
</div>

### getAllocSizeArgs() {#a5bac674280b8fed3e09ea688b91bb1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; Attribute::getAllocSizeArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the argument numbers for the allocsize attribute.</p>

<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#ab67846129bc1b313c0a7606f285f2168">unpackAllocSizeArgs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a7a4b1bb434f664cf880b1dd79909c61a">getAllocationSize</a> and <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>.</p>

</div>
</div>

### getAsString() {#a493e72ce53ee16d92489ba67d7ce2bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Attribute::getAsString (bool InAttrGrp=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> is converted to a string of equivalent mnemonic.</p>


<p>This is, presumably, for writing out the mnemonics for the assembly writer.</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1a1d5b772bea21e5e949413e09eedf17de">llvm::Aligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa16fb931dad01a15ae45a7a90cd3e6276">llvm::ArgMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1ab24ce0cd392a5b0b8dedc66c25213594">llvm::Free</a>, <a href="#a2473a7c5ee60c5a3ae90782d494b436e">getAllocKind</a>, <a href="#a5bac674280b8fed3e09ea688b91bb1a0">getAllocSizeArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad7f81241f958a1f5917a3410942d3199">llvm::ConstantRange::getBitWidth</a>, <a href="#af356410c6b277e5a12369be877371edb">getCaptureInfo</a>, <a href="#a76851ce1968746201d39b872e122e530">getInitializes</a>, <a href="#a6fea074fd9120ff82abd8f9e0036a12a">getKindAsEnum</a>, <a href="#a3ad8f83f8d6165314fe8f173645dd458">getKindAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="#a7c68b48aeb5f2440cf65d5e8b2e16040">getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a76a16756c4c05000711a5ab6c68756dc">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getModRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#af852b70a5b417dc2dc05caf87caf9457">getModRefStr</a>, <a href="#a9f1de7d65958c48ef95760927081625c">getNameFromAttrKind</a>, <a href="#a6b18d31b344ea210a82c4028b7684946">getNoFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>, <a href="#a84c175adc74c833d57ab21f177e99c73">getUWTableKind</a>, <a href="#a77e419fa4236059d9acf513a2d9b603b">getValueAsConstantRange</a>, <a href="#a1db9b109e0e28e38eb43086b679dc271">getValueAsInt</a>, <a href="#aff1705f60feb6936d4e9cf126347c5e7">getValueAsType</a>, <a href="#a190a29f5df3964b269383c0d6fba0ea9">getVScaleRangeMax</a>, <a href="#a2340c9d2c47ffa7fc07568ba059b62a2">getVScaleRangeMin</a>, <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1facf7e5975f35256eb4d98f15f212f2a4c">llvm::InaccessibleMem</a>, <a href="#a0f4d4e6a852d283cafe0b0413cfb6430">isEnumAttribute</a>, <a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a>, <a href="#ab6fc71def3a243f7c93d39db21344240">isTypeAttribute</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#abfc43f0b4a68c9701a315cae51761f66">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::locations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a81f32bf88f0c95803ac134210308d54c">llvm::ConstantRangeList::print</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a91bbc1ac424839ba7e85d2d8542c288a">llvm::Type::print</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1afe2fa75dbfe34e67fd470a047a431619">llvm::Realloc</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1af704f57ea420275ad51bf55b7dec2c96">llvm::Uninitialized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1accb602a05d0e65e8416c643f0e32bd64">llvm::Zeroed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantcomposite/#gabe4c7d6466398b1254d11be8bb308564">LLVMGetAsString</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a2a2835a14441938516c2ae9e545d330a">anonymous{AsmWriter.cpp}::AssemblyWriter::writeAttribute</a>.</p>

</div>
</div>

### getCaptureInfo() {#af356410c6b277e5a12369be877371edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaptureInfo Attribute::getCaptureInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns information from captures attribute.</p>

<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/captureinfo/#a083be9a76fcc4cd75dcbfebd8ca65f5f">llvm::CaptureInfo::createFromIntValue</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### getDereferenceableBytes() {#a7a7458f7bdc291db1a43ad26f149cfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Attribute::getDereferenceableBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of dereferenceable bytes from the dereferenceable attribute.</p>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>.</p>

</div>
</div>

### getDereferenceableOrNullBytes() {#a49fa360a9d36f3b7668437a0385bf436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Attribute::getDereferenceableOrNullBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of dereferenceable_or_null bytes from the dereferenceable_or_null attribute.</p>

<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>

</div>
</div>

### getInitializes() {#a76851ce1968746201d39b872e122e530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ConstantRange &gt; Attribute::getInitializes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the value of the initializes attribute.</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>.</p>

</div>
</div>

### getKindAsEnum() {#a6fea074fd9120ff82abd8f9e0036a12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind Attribute::getKindAsEnum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's kind as an enum (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a>).</p>


<p>This requires the attribute be representable as an enum (see: <span class="doxyComputerOutput">hasKindAsEnum</span>).</p>


<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9e7776eef7d7515a9288bbc4e4654388">hasKindAsEnum</a> and <a href="#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aa411f806557fdaf4af309b7c541757d2">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a7464f6980d299143f57a229f73181c39">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="#acd074cd44460fcae84c1608fa9deba1e">getWithNewType</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga08d1304979a5ea706b1641c11937b80d">LLVMGetEnumAttributeKind</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a9a1b2954b9c4eb6f178a0c7e66581822">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/attributecomparator/#a97f77173f1afdf6a7491a9518cdf9b31">AttributeComparator::operator()</a>, <a href="/web-llvm/docs/api/structs/attributecomparator/#ae99dcd97c18ca3dab4b516aa6fb86c4e">AttributeComparator::operator()</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a2a2835a14441938516c2ae9e545d330a">anonymous{AsmWriter.cpp}::AssemblyWriter::writeAttribute</a>.</p>

</div>
</div>

### getKindAsString() {#a3ad8f83f8d6165314fe8f173645dd458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Attribute::getKindAsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's kind as a string.</p>


<p>This requires the attribute to be a string attribute.</p>


<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a7464f6980d299143f57a229f73181c39">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gaaa5bd5bf0cf14ab350f63dbf90089980">LLVMGetStringAttributeKind</a>, <a href="/web-llvm/docs/api/structs/attributecomparator/#a97f77173f1afdf6a7491a9518cdf9b31">AttributeComparator::operator()</a> and <a href="/web-llvm/docs/api/structs/attributecomparator/#a231e754dca9cc089e6adc293d28db631">AttributeComparator::operator()</a>.</p>

</div>
</div>

### getMemoryEffects() {#a7c68b48aeb5f2440cf65d5e8b2e16040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects Attribute::getMemoryEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns memory effects.</p>

<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a93c6a6bc46c56b292db3ba60e92341a5">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::createFromIntValue</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### getNoFPClass() {#a6b18d31b344ea210a82c4028b7684946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest Attribute::getNoFPClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> for nofpclass.</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### getRange() {#a10eb642c38648a5edb4a6bc7ce217a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; Attribute::getRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the value of the range attribute.</p>

<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a35dd2e0efa71641e526e898918af9ef6">addNoUndefAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ae6559a2babd0e7bd0f96d7116fb49940">llvm::AttributeList::getParamRange</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#ac809872a1cc7c2d6be09b58f8cf7b400">llvm::AttrBuilder::getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa64b47f684944bcb9aea2c1350440cd7">llvm::CallBase::getRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a62841df6cf509ad386f9b62d44397238">runImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#ab2dcaa046e6a38983e74ce28a120ce79">llvm::AttributeFuncs::typeIncompatible</a>.</p>

</div>
</div>

### getRawPointer() {#ab3acc035135394d0b3ccf4c062d72810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::Attribute::getRawPointer ()</td>
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

<p>Return a raw pointer that uniquely identifies this attribute.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### getStackAlignment() {#ae16611668da23acd765262e5d079f462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign Attribute::getStackAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the stack alignment field of an attribute as a byte alignment value.</p>

<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>

</div>
</div>

### getUWTableKind() {#a84c175adc74c833d57ab21f177e99c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UWTableKind Attribute::getUWTableKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>.</p>

</div>
</div>

### getValueAsBool() {#a70f42ed02a8993b84bdf97da5d54d097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::getValueAsBool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's value as a boolean.</p>


<p>This requires that the attribute be a string attribute.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a068641b222182c6ca0412660993bf1fe">llvm::AMDGPUMachineFunction::AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a392f6e72d46ff14ee31481e3452f6c31">llvm::TargetLoweringBase::areJTsAllowed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>.</p>

</div>
</div>

### getValueAsConstantRange() {#a77e419fa4236059d9acf513a2d9b603b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; Attribute::getValueAsConstantRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's value as a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>.</p>


<p>This requires the attribute to be a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> attribute.</p>


<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a259761353a6ddbb637d44b5e18a65a26">isConstantRangeAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>.</p>

</div>
</div>

### getValueAsConstantRangeList() {#a93a771ed3c28612ca7852e1d9c62ab05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ConstantRange &gt; Attribute::getValueAsConstantRangeList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's value as a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> array.</p>


<p>This requires the attribute to be a <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute.</p>


<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac6eebf7187794b85e9546dfe4fb61b6c">isConstantRangeListAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a> and <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>.</p>

</div>
</div>

### getValueAsInt() {#a1db9b109e0e28e38eb43086b679dc271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Attribute::getValueAsInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's value as an integer.</p>


<p>This requires that the attribute be an integer attribute.</p>


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a142250c7b671591390912db907532036">isIntAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aa411f806557fdaf4af309b7c541757d2">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a2f76ccb620fc227f0b307e3457cb5228">getAllocFnKind</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a9460e7e520ab945be65ecc565f727cf5">isEqualOrWorse</a>.</p>

</div>
</div>

### getValueAsString() {#a968930aea9d9efa8d46dd890fce75643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Attribute::getValueAsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's value as a string.</p>


<p>This requires the attribute to be a string attribute.</p>


<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a5861f2cf66ad90de99ef9dfe8054f75d">adjustCallerStackProbeSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a4edf7cbc1ca95769993535d584f66a3f">adjustMinLegalVectorWidth</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#abee7911947922a80fe782ead0742972e">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ad6d87a400bc9669540b19739d36b4488">getDeoptLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a388dd65231ec660233341f507f02f91d">llvm::AMDGPUTargetMachine::getFeatureString</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ac7c7ab2466ba18c193faea8966362085">llvm::AMDGPUTargetMachine::getGPUName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a92e17e524fe1c82a26b5433b6e9715e3">llvm::X86TargetLowering::getStackProbeSymbolName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7a00b18388711db81874093cc266614">llvm::getStringFnAttrAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a9009458436b2d38a2be9636993ab17e2">llvm::SparcTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#ac5c975b4faf36ed756851c7a84d870ea">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a20e0ba2c46bef474e31cf8c2f9322db0">llvm::PPCTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a889bd3ec782a056c71f40ea116bad9b8">llvm::RISCVTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a20daff715a896d9ada2a604ab403e1f2">llvm::SystemZTargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5cf46104ca48a9577dc4a61cf080003a">llvm::X86TargetLowering::hasInlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a5af65e382f22a93146221fa34dbd91eb">isThumbFunction</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gabca54c426e386c00fe4f4483693191f2">LLVMGetStringAttributeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#add0594bfc35119c8d898c51bb3697823">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromNumthreadsAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a830906f493a6d5c69ac5a94675c657fb">llvm::parseStatepointDirectivesFromAttrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-fentryinserter-cpp-/fentryinserter/#ae3c9ad9123c1338bda3254b781eb08fc">anonymous{FEntryInserter.cpp}::FEntryInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a11d99203cc91bbd49c59f32943541747">anonymous{PatchableFunction.cpp}::PatchableFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#a8b02ace8c1f9abda69c009da0432e901">llvm::AttributeFuncs::updateMinLegalVectorWidthAttr</a>.</p>

</div>
</div>

### getValueAsType() {#aff1705f60feb6936d4e9cf126347c5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Attribute::getValueAsType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute's value as a <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>


<p>This requires the attribute to be a type attribute.</p>


<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab6fc71def3a243f7c93d39db21344240">isTypeAttribute</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a2a2835a14441938516c2ae9e545d330a">anonymous{AsmWriter.cpp}::AssemblyWriter::writeAttribute</a>.</p>

</div>
</div>

### getVScaleRangeMax() {#a190a29f5df3964b269383c0d6fba0ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; Attribute::getVScaleRangeMax ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum value for the vscale_range attribute or std::nullopt when unknown.</p>

<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a44f5f98b926132d88f0211642cc9dcb2">unpackVScaleRangeArgs</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a880ecb27263b592a9c72b96378c10088">llvm::getVScaleRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### getVScaleRangeMin() {#a2340c9d2c47ffa7fc07568ba059b62a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Attribute::getVScaleRangeMin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum value for the vscale_range attribute.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f5f68d66cc65213e32d67a78992fad">hasAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a44f5f98b926132d88f0211642cc9dcb2">unpackVScaleRangeArgs</a>.</p>


<p>Referenced by <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a4e108201f94f2fe89865e7868390bbf6">getVScaleForTuning</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a880ecb27263b592a9c72b96378c10088">llvm::getVScaleRange</a>.</p>

</div>
</div>

### getWithNewType() {#acd074cd44460fcae84c1608fa9deba1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::Attribute::getWithNewType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ReplacementTy)</td>
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

<p>For a typed attribute, return the equivalent attribute with the type changed to <span class="doxyComputerOutput">ReplacementTy</span>.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a>, <a href="#a6fea074fd9120ff82abd8f9e0036a12a">getKindAsEnum</a> and <a href="#ab6fc71def3a243f7c93d39db21344240">isTypeAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af4d7d74d32e67259997832a663e14739">llvm::AttributeList::replaceAttributeTypeAtIndex</a>.</p>

</div>
</div>

### hasAttribute() {#ad1f5f68d66cc65213e32d67a78992fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::hasAttribute (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is present.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">None</a>.</p>


<p>Referenced by <a href="#af1c88577e9470957be5ad4e4d401146a">getAlignment</a>, <a href="#a2473a7c5ee60c5a3ae90782d494b436e">getAllocKind</a>, <a href="#a5bac674280b8fed3e09ea688b91bb1a0">getAllocSizeArgs</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="#af356410c6b277e5a12369be877371edb">getCaptureInfo</a>, <a href="#a7a7458f7bdc291db1a43ad26f149cfed">getDereferenceableBytes</a>, <a href="#a49fa360a9d36f3b7668437a0385bf436">getDereferenceableOrNullBytes</a>, <a href="#a76851ce1968746201d39b872e122e530">getInitializes</a>, <a href="#a7c68b48aeb5f2440cf65d5e8b2e16040">getMemoryEffects</a>, <a href="#a6b18d31b344ea210a82c4028b7684946">getNoFPClass</a>, <a href="#a10eb642c38648a5edb4a6bc7ce217a17">getRange</a>, <a href="#ae16611668da23acd765262e5d079f462">getStackAlignment</a>, <a href="#a84c175adc74c833d57ab21f177e99c73">getUWTableKind</a>, <a href="#a190a29f5df3964b269383c0d6fba0ea9">getVScaleRangeMax</a>, <a href="#a2340c9d2c47ffa7fc07568ba059b62a2">getVScaleRangeMin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae63d2db6b5c5d02973f882f17caf52b6">llvm::isStatepointDirectiveAttr</a>.</p>

</div>
</div>

### hasAttribute() {#aa9f8ffb34d5d5ecd8879bb76277e660c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the target-dependent attribute is present.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a>.</p>

</div>
</div>

### hasKindAsEnum() {#a9e7776eef7d7515a9288bbc4e4654388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::hasKindAsEnum ()</td>
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

<p>Returns true if the attribute's kind can be represented as an enum (Enum, Integer, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a>, or <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute).</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a0571df3e57128211e09cba4544aa9ca7">isStringAttribute</a>.</p>


<p>Referenced by <a href="#a6fea074fd9120ff82abd8f9e0036a12a">getKindAsEnum</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### hasParentContext() {#ab4f63a12196c8f1a595311d67a4bdd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::hasParentContext (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this attribute belongs to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#adf4d22686e85732b2fef71e3c45531c6">isValid</a>.</p>

</div>
</div>

### isConstantRangeAttribute() {#a259761353a6ddbb637d44b5e18a65a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isConstantRangeAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> attribute.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a77e419fa4236059d9acf513a2d9b603b">getValueAsConstantRange</a>.</p>

</div>
</div>

### isConstantRangeListAttribute() {#ac6eebf7187794b85e9546dfe4fb61b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isConstantRangeListAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is a <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute.</p>

<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a93a771ed3c28612ca7852e1d9c62ab05">getValueAsConstantRangeList</a>.</p>

</div>
</div>

### isEnumAttribute() {#a0f4d4e6a852d283cafe0b0413cfb6430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isEnumAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is an <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> type.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a> and <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>.</p>

</div>
</div>

### isIntAttribute() {#a142250c7b671591390912db907532036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isIntAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is an integer attribute.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aa411f806557fdaf4af309b7c541757d2">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="#a1db9b109e0e28e38eb43086b679dc271">getValueAsInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a9460e7e520ab945be65ecc565f727cf5">isEqualOrWorse</a>.</p>

</div>
</div>

### isStringAttribute() {#a0571df3e57128211e09cba4544aa9ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isStringAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is a string (target-dependent) attribute.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aa411f806557fdaf4af309b7c541757d2">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a7464f6980d299143f57a229f73181c39">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="#a3ad8f83f8d6165314fe8f173645dd458">getKindAsString</a>, <a href="#a70f42ed02a8993b84bdf97da5d54d097">getValueAsBool</a>, <a href="#a968930aea9d9efa8d46dd890fce75643">getValueAsString</a>, <a href="#aa9f8ffb34d5d5ecd8879bb76277e660c">hasAttribute</a>, <a href="#a9e7776eef7d7515a9288bbc4e4654388">hasKindAsEnum</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gab835d65835c777cd435e5502da143564">LLVMIsStringAttribute</a>, <a href="/web-llvm/docs/api/structs/attributecomparator/#a97f77173f1afdf6a7491a9518cdf9b31">AttributeComparator::operator()</a>, <a href="/web-llvm/docs/api/structs/attributecomparator/#ae99dcd97c18ca3dab4b516aa6fb86c4e">AttributeComparator::operator()</a>, <a href="/web-llvm/docs/api/structs/attributecomparator/#a231e754dca9cc089e6adc293d28db631">AttributeComparator::operator()</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a830906f493a6d5c69ac5a94675c657fb">llvm::parseStatepointDirectivesFromAttrs</a>.</p>

</div>
</div>

### isTypeAttribute() {#ab6fc71def3a243f7c93d39db21344240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isTypeAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute is a type attribute.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aa411f806557fdaf4af309b7c541757d2">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAttribute</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="#aff1705f60feb6936d4e9cf126347c5e7">getValueAsType</a>, <a href="#acd074cd44460fcae84c1608fa9deba1e">getWithNewType</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gaba042344564d49d7bfcc15534fdbd232">LLVMIsTypeAttribute</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a2a2835a14441938516c2ae9e545d330a">anonymous{AsmWriter.cpp}::AssemblyWriter::writeAttribute</a>.</p>

</div>
</div>

### isValid() {#adf4d22686e85732b2fef71e3c45531c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::isValid ()</td>
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

<p>Return true if the attribute is any kind of attribute.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a35dd2e0efa71641e526e898918af9ef6">addNoUndefAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a5861f2cf66ad90de99ef9dfe8054f75d">adjustCallerStackProbeSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a4edf7cbc1ca95769993535d584f66a3f">adjustMinLegalVectorWidth</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a6abb550fd00c7568af7b045429491d9e">llvm::AttrBuilder::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a0a656771b0cea2b1276b684e1cba00f5">llvm::AttrBuilder::contains</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#abee7911947922a80fe782ead0742972e">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a2f76ccb620fc227f0b307e3457cb5228">getAllocFnKind</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a388dd65231ec660233341f507f02f91d">llvm::AMDGPUTargetMachine::getFeatureString</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9e46a3a4bf99f8dcea9cb9efb4d977a3">llvm::CallBase::getFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ac7c7ab2466ba18c193faea8966362085">llvm::AMDGPUTargetMachine::getGPUName</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#acbf6c3d92e9a2387568dfb1fc9997eda">getParameterABIAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#ac809872a1cc7c2d6be09b58f8cf7b400">llvm::AttrBuilder::getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa64b47f684944bcb9aea2c1350440cd7">llvm::CallBase::getRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7a00b18388711db81874093cc266614">llvm::getStringFnAttrAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af3a94bd62230f4b9f99b54976663dfe8">llvm::ARMBaseTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a662d6e7c2aa31e6cac9212319d5349e3">llvm::CSKYTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#ab8055e9f4ea2a04ea313d2bcbfeab1a1">llvm::HexagonTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#ac0030767228d11167dfbe14d6c0d369b">llvm::LoongArchTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#acc8d7e573d75a9749702efefef9dc9a2">llvm::M68kTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#ae3a3a1690e01cf8d748aae7010f97687">llvm::MipsTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#afac904db14a3a55833a6293e7b3f222f">llvm::PPCTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a9009458436b2d38a2be9636993ab17e2">llvm::SparcTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ae65ab39e3d2d3b91527cb482c735aa">llvm::SystemZTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetmachine/#ac5c975b4faf36ed756851c7a84d870ea">llvm::WebAssemblyTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#afc11b3df4a2d81fbf25988baf63fc6b3">llvm::X86TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#afcd734d7f68ecebea11378e93eb4b3be">llvm::XtensaTargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a880ecb27263b592a9c72b96378c10088">llvm::getVScaleRange</a>, <a href="#ab4f63a12196c8f1a595311d67a4bdd3d">hasParentContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a5af65e382f22a93146221fa34dbd91eb">isThumbFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#add0594bfc35119c8d898c51bb3697823">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExecutionModeFromNumthreadsAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a62841df6cf509ad386f9b62d44397238">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#ab2dcaa046e6a38983e74ce28a120ce79">llvm::AttributeFuncs::typeIncompatible</a> and <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#a8b02ace8c1f9abda69c009da0432e901">llvm::AttributeFuncs::updateMinLegalVectorWidthAttr</a>.</p>

</div>
</div>

### Profile() {#a8133f46432136f4daf84ceaa63734e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Attribute::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### pImpl {#a55318c4d90472ba993547b9c6c078755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeImpl* llvm::Attribute::pImpl = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### canUseAsFnAttr() {#aa1d1daaf72feb4d1ecb59df592bdc3d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::canUseAsFnAttr (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039dadd899aa9755b6823dea0f942ee1ba150">FnAttr</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#af6ac4e7c6dca400b4cbcf176dc94ca0d">hasAttributeProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp/#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a> and <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>.</p>

</div>
</div>

### canUseAsParamAttr() {#ade0ea4e187f04c1339866dab77cb7181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::canUseAsParamAttr (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#af6ac4e7c6dca400b4cbcf176dc94ca0d">hasAttributeProperty</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039dad5a6337c700ccb13f576dee2034aa5ea">ParamAttr</a>.</p>

</div>
</div>

### canUseAsRetAttr() {#a44151f9f498f20ce0aa95010c25fd2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::canUseAsRetAttr (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#af6ac4e7c6dca400b4cbcf176dc94ca0d">hasAttributeProperty</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039da19331ed2fb57db290a26f2869bae2f45">RetAttr</a>.</p>

</div>
</div>

### fromRawPointer() {#ae1a3efd17863479b39d4abc926b85336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::Attribute::fromRawPointer (void * RawPtr)</td>
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

<p>Get an attribute from a raw pointer created by getRawPointer.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### get() {#a43708098bd7085788a680fd02f47c750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind, uint64_t Val=0)</td>
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

<p>Return a uniquified <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a>, <a href="#ad343d2ea041d596a04db3252e3017cad">isEnumAttrKind</a> and <a href="#ac2d5f8ba4215304f89a401248abed393">isIntAttrKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#ade3d002f2a3c1617aacaddf25e561833">addAllocTypeAttribute</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-assumptions-cpp-/#a2b9453af013b5f96564c2cb0b92a010b">anonymous{Assumptions.cpp}::addAssumptionsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a1df399b697ebab2755c841d66350778f">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada583c27bb2634195f2964c7e695a0b3">llvm::AttributeList::addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a773374bcf6e6f638f8a996c1df6cc998">llvm::AttrBuilder::addConstantRangeAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a731a53feffdd319d9fbaaf4154e30f09">llvm::AttrBuilder::addConstantRangeListAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a57bb5ff1076799c12e720e248f40a791">llvm::AttrBuilder::addRawIntAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#ad79f5341284d1c6e5d0be00043b1235c">llvm::AttrBuilder::addTypeAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeac445a66283c4e567ebd390c058e39d">llvm::IRBuilderBase::CreatePreserveArrayAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4804fd7127d8e249a628e93d6b8b3f2a">llvm::IRBuilderBase::CreatePreserveStructAccessIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a67ae1ad562dccec0023641ab0e8fc48e">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::emitAttributeIfNotDefaultAfterClamp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8631130c37aa54ae6c9127abc5fe392a">llvm::AArch64TargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab439771b84f342c37a8823fb2f797642">llvm::ARMTargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a925bbfb44898a7e8da7d6170278aaf71">emitTPIDR2Save</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4387a04798ee02597a248ac196fc1d53">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a15fc36bf8d33e06423d939bb34bc9305">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#abc9345ab199d872cbb5a7c31b84a4cde">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a34e094853fc48c4acf66ca5e1c5a73dd">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a051fd4ce3d6dd22954dc588c14b9ced1">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/irattribute/#af43837e00533ca9862ae5b767fe91cd9">llvm::IRAttribute&lt; AK, BaseType, AAType &gt;::getDeducedAttributes</a>, <a href="#afb8975f28d8418cad8ea770575736b81">getWithAlignment</a>, <a href="#a6f90f8b9a9209911cdd0573c4e25388e">getWithAllocSizeArgs</a>, <a href="#a16e54dbebfcc4ad4c764af94cab0979e">getWithByRefType</a>, <a href="#acc00a93ed593f135b4b54de32d484e6b">getWithByValType</a>, <a href="#a4b2c8769ea6c7af6f24285e87a7e3aa1">getWithDereferenceableBytes</a>, <a href="#a8afbda215c9d4599ff4edcac57340268">getWithDereferenceableOrNullBytes</a>, <a href="#abd67d0c42d48781c7d2819638c109a47">getWithInAllocaType</a>, <a href="#adaf42001b3cc4c8c631902cbb48106d5">getWithMemoryEffects</a>, <a href="#acd074cd44460fcae84c1608fa9deba1e">getWithNewType</a>, <a href="#aa6913b6616150e5f65ef723520dbcc77">getWithNoFPClass</a>, <a href="#a3cbd08b6c2cddabb8dfa41272133f027">getWithPreallocatedType</a>, <a href="#a10d1cac7b43caeef3f78bd86429a881a">getWithStackAlignment</a>, <a href="#a09c2b2c1eb0fcfe3f1e14192eae42eb4">getWithStructRetType</a>, <a href="#a600a01b826220fa1896bcecb198184e1">getWithUWTableKind</a>, <a href="#a7b20ebfa9bcf271438ffda63f623d0f5">getWithVScaleRangeArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abc575c6c80287df1f51f698ec74e315e">llvm::Attributor::hasAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb708ab48a84e8d45f8b640ffbb395ac">llvm::inferAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a490ad1c48c230e1b6d37e946faee435a">llvm::AANoSync::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoundef/#ad91f1de0705a6d8cfb9d1269ae996737">llvm::AANoUndef::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aawillreturn/#ad363b24d67098ccf362ea38277ce9c61">llvm::AAWillReturn::isImpliedByIR</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#gaebff9c76379397445b16d0fa92720fb8">LLVMAddTargetDependentFunctionAttr</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga9c30325536839609a6764bd4921f00fa">LLVMCreateConstantRangeAttribute</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gaa89424a969c6fb483bbadc4289d45f59">LLVMCreateEnumAttribute</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga94714a6fcfe57ba4358c97bb276bb087">LLVMCreateStringAttribute</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga93cbbd51070b2849693677d8c45bbf31">LLVMCreateTypeAttribute</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga07712e5d4d664c623674c09e03c9c011">LLVMDIBuilderGetOrCreateArray</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadbd363bcd72a98cc8225b11a0ea0f6fa">LLVMDIBuilderGetOrCreateTypeArray</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a508aceda7d46a30692b5bb3531e16dba">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdgpunoagpr/#af41e92c622f732d73b21ab36030fa90b">anonymous{AMDGPUAttributor.cpp}::AAAMDGPUNoAGPR::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a858b2d1d8e8f50fb043e650fb6197d91">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a7e545ca98465fdb21ed037cb8cd05f06">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfoimpl/#afd7017a3f3a492552121875308910210">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a3930112816f97f9c7a92b22d4e332107">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a1cfca839ff13dd1c214a5dae9c737bda">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#ab5784e92545941ed78762b81c4e2189b">setAllocKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac12e315180fb16cb5874fb41526ca453">llvm::codegen::setFunctionAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a444e3e622a00db2be6dcaf46cef996f5">llvm::setInlineRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a199f0b21470b0b5224b2347603d43a94">setParamElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a4ab42d331e885c91e9eec5eaf9b82647">setParamReadNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a70d15119886ee33e9a6e0a5990213a9c">setParamReadOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#adac3163394efa3963f6ae6c395cd077e">setParamWriteOnly</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>.</p>

</div>
</div>

### get() {#a3469e685d3fadac587ccaa4ca8144d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Val=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
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



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="/web-llvm/docs/api/classes/llvm/stringattributeimpl/#ad3ad8ac9b5c1d0ee83844044220d691c">llvm::StringAttributeImpl::totalSizeToAlloc</a>.</p>

</div>
</div>

### get() {#a438a746d30d8cd255a96ffb06749602e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a> and <a href="#a44b9bbfc65ea129fe5c7fe72ea004d00">isTypeAttrKind</a>.</p>

</div>
</div>

### get() {#a1f33826a7081abb8cd61583464d7ca51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
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



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>, <a href="#aae62cfe03629c96ee1cc2697c3d66117">isConstantRangeAttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#adb1c052266ebacdbf28164fae9106b0a">llvm::APInt::Profile</a>.</p>

</div>
</div>

### get() {#a39a3342c858856b421c6e2c306aaf241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; Val)</td>
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



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7074bcba216ff000eb0d163b53868c1e">Attribute</a>, <a href="#ac3f018f989664ac6588f604ccca98143">isConstantRangeListAttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrangelistattributeimpl/#a86df45aa005496277266b034a8ddfdcd">llvm::ConstantRangeListAttributeImpl::totalSizeToAlloc</a>.</p>

</div>
</div>

### getAttrKindFromName() {#a0c53a4c5456480dc377772d5d2f4f832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind Attribute::getAttrKindFromName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AttrName)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a> and <a href="#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad0cb3b7526df89b44d7c13b54cd25a51">llvm::fillMapFromAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp/#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b33634e0aa97435f13845ce7e10411e">llvm::getKnowledgeFromBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac175548dea024de495368b0dcd301f09">llvm::hasAttributeInAssume</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga4bd62e3a1b94b92e32d892c8f89dea1c">LLVMGetEnumAttributeKindForName</a> and <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>.</p>

</div>
</div>

### getNameFromAttrKind() {#a9f1de7d65958c48ef95760927081625c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Attribute::getNameFromAttrKind (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> AttrKind)</td>
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



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aadca3692ce40afeb83b7765b2d7dfc9c">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build</a>, <a href="#a493e72ce53ee16d92489ba67d7ce2bb0">getAsString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4ef3e6d4cf3115d5fdd70b5e35a96df">llvm::hasAttributeInAssume</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a09453ddb2ea4103fd552fed3db38f794">printFunctionArgExts</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a2a2835a14441938516c2ae9e545d330a">anonymous{AsmWriter.cpp}::AssemblyWriter::writeAttribute</a>.</p>

</div>
</div>

### getWithAlignment() {#afb8975f28d8418cad8ea770575736b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithAlignment (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Return a uniquified <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object that has the specific alignment set.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a089e46429cea4cfcd2ba23a6fc6aa676">llvm::Value::MaximumAlignment</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ae5881267e88ebfd0527460a92b61f960">llvm::MatrixBuilder::CreateColumnMajorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a69138108d0e5888e6cafcdd27d082fc8">llvm::MatrixBuilder::CreateColumnMajorStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac3e775626bfa565297feec5807947efc">llvm::IRBuilderBase::CreateElementUnorderedAtomicMemMove</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2001dcf6278f9e7e10b895d060d15abb">llvm::IRBuilderBase::CreateMaskedCompressStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad878957c30eb65983e09b60edb0e1a1b">llvm::IRBuilderBase::CreateMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a19f9814e01d7c1d3167216cba953eab2">llvm::IRBuilderBase::CreateThreadLocalAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a5aa1b2d25d74dea13d0262ab5ad610a4">anonymous{AttributorAttributes.cpp}::AAAlignImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructioncall/#gacd1c1f1b108ad128ae628a63379fa141">LLVMSetInstrParamAlignment</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunctionparameters/#ga989cab5b609afce92724f43c31e24e57">LLVMSetParamAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a3e1cfc51d4ab9b192f09e050b24e410b">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a4ab0f2c30ee83d6377488de9a1f089e9">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#ac4c3eecc7e156718cb3f01dacdc0631a">llvm::MemTransferBase&lt; BaseCL &gt;::setSourceAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#ab5f836ddc7548470c429fd5daaea2784">llvm::MemTransferBase&lt; BaseCL &gt;::setSourceAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getWithAllocSizeArgs() {#a6f90f8b9a9209911cdd0573c4e25388e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithAllocSizeArgs (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned ElemSizeArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; unsigned &gt; &amp; NumElemsArg)</td>
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



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a84f56e05a576b94b89af30ba313805c4">packAllocSizeArgs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a7e5e759cb3f6cf4f3f67df086825189e">setAllocSize</a>.</p>

</div>
</div>

### getWithByRefType() {#a16e54dbebfcc4ad4c764af94cab0979e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithByRefType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>

</div>
</div>

### getWithByValType() {#acc00a93ed593f135b4b54de32d484e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithByValType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>

</div>
</div>

### getWithDereferenceableBytes() {#a4b2c8769ea6c7af6f24285e87a7e3aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithDereferenceableBytes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, uint64_t Bytes)</td>
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



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a994c04cdb21b071d608c92eef461a88f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::getDeducedAttributes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a>.</p>

</div>
</div>

### getWithDereferenceableOrNullBytes() {#a8afbda215c9d4599ff4edcac57340268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithDereferenceableOrNullBytes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, uint64_t Bytes)</td>
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



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a994c04cdb21b071d608c92eef461a88f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::getDeducedAttributes</a>.</p>

</div>
</div>

### getWithInAllocaType() {#abd67d0c42d48781c7d2819638c109a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithInAllocaType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>

</div>
</div>

### getWithMemoryEffects() {#adaf42001b3cc4c8c631902cbb48106d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithMemoryEffects (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> ME)</td>
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



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a43708098bd7085788a680fd02f47c750">get</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ac96f712f6d153d48c535886b4f8aef99">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::toIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a0b7d633cf22c2f54d391f3f5c0a5ef56">fixupFPReturnAndCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a8df2e20241276fa840a50aaf747a059e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a4d28b0b4536be47a57ac82367c0b04a7">llvm::AMDGPULibFunc::getOrInsertFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a9971c8a3647ef1b5439ed7cd18aee749">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aecb5289d51bac327bc2f7f5a2d0ad5c3">llvm::CallBase::setMemoryEffects</a>.</p>

</div>
</div>

### getWithNoFPClass() {#aa6913b6616150e5f65ef723520dbcc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithNoFPClass (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> Mask)</td>
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



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#add57ea3af5fecc6508e938a1b0ddce44">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::getDeducedAttributes</a>.</p>

</div>
</div>

### getWithPreallocatedType() {#a3cbd08b6c2cddabb8dfa41272133f027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithPreallocatedType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>

</div>
</div>

### getWithStackAlignment() {#a10d1cac7b43caeef3f78bd86429a881a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithStackAlignment (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>

</div>
</div>

### getWithStructRetType() {#a09c2b2c1eb0fcfe3f1e14192eae42eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithStructRetType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>

</div>
</div>

### getWithUWTableKind() {#a600a01b826220fa1896bcecb198184e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithUWTableKind (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a> Kind)</td>
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



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="#a43708098bd7085788a680fd02f47c750">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#a7a383eea189e7af487299e904c0b5fcc">llvm::Function::setUWTableKind</a>.</p>

</div>
</div>

### getWithVScaleRangeArgs() {#a7b20ebfa9bcf271438ffda63f623d0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Attribute::getWithVScaleRangeArgs (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned MinValue, unsigned MaxValue)</td>
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



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a43708098bd7085788a680fd02f47c750">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9a8cb941feb6e29b5089568ab1dc2044">packVScaleRangeArgs</a>.</p>

</div>
</div>

### intersectMustPreserve() {#af3b008eee2735671b4bfdabd4df07b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::intersectMustPreserve (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9c5fbaf034ddf1c9e224c2399990a280">hasIntersectProperty</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039da8fed3b85e5feb06ed9845023fd4e6943">IntersectPreserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### intersectWithAnd() {#aa586fffdd286955ca876838f11a5f6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::intersectWithAnd (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9c5fbaf034ddf1c9e224c2399990a280">hasIntersectProperty</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039daf650824d160fd62add79797968edd3d9">IntersectAnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### intersectWithCustom() {#a11f48b3f20c58e11564df402e02a1592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::intersectWithCustom (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9c5fbaf034ddf1c9e224c2399990a280">hasIntersectProperty</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039dacb175e20be6509f68d603623035fab53">IntersectCustom</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### intersectWithMin() {#a3d708ef8b38a269452e88f7c0fcfa5f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::intersectWithMin (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9c5fbaf034ddf1c9e224c2399990a280">hasIntersectProperty</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039daab253a0d03a4a41f574be7a4ed6ed51d">IntersectMin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### isConstantRangeAttrKind() {#aae62cfe03629c96ee1cc2697c3d66117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::isConstantRangeAttrKind (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="#a1f33826a7081abb8cd61583464d7ca51">get</a>.</p>

</div>
</div>

### isConstantRangeListAttrKind() {#ac3f018f989664ac6588f604ccca98143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::isConstantRangeListAttrKind (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="#a39a3342c858856b421c6e2c306aaf241">get</a>.</p>

</div>
</div>

### isEnumAttrKind() {#ad343d2ea041d596a04db3252e3017cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::isEnumAttrKind (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a1bdef12f6088e0d320946736b48fb137">anonymous{AttributorAttributes.cpp}::clampCallSiteArgumentStates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a3c38e0e568db780d1a47a0b2ce3991f7">clampReturnedValueStates</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a193d427e5f23228ebb54da668ab02360">anonymous{AttributorAttributes.cpp}::getArgumentStateFromCallBaseContext</a>, <a href="/web-llvm/docs/api/structs/llvm/irattribute/#aa3a4aef2a8552613042d8c85ff5d22b3">llvm::IRAttribute&lt; AK, BaseType, AAType &gt;::hasTrivialInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#a4b9407f2fcb1a0cc5624be342512a31f">llvm::AttributeImpl::Profile</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#a13627a051dc8e791e2f3f1699575605b">anonymous{AttributorAttributes.cpp}::AACalleeToCallSite&lt; AADereferenceable, AADereferenceableImpl &gt;::updateImpl</a>.</p>

</div>
</div>

### isExistingAttribute() {#a9b0a1acb1f888349f2e47466c73f2d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Attribute::isExistingAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Return true if the provided string matches the IR name of an attribute.</p>


<p>example: "noalias" return true but not "NoAlias"</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac175548dea024de495368b0dcd301f09">llvm::hasAttributeInAssume</a>.</p>

</div>
</div>

### isIntAttrKind() {#ac2d5f8ba4215304f89a401248abed393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::isIntAttrKind (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="#a43708098bd7085788a680fd02f47c750">get</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a196eaf12b6408f442a6d164c336d3d52">llvm::AttrBuilder::getRawIntAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac175548dea024de495368b0dcd301f09">llvm::hasAttributeInAssume</a>, <a href="/web-llvm/docs/api/classes/llvm/intattributeimpl/#a34c6e85f659c7905c79d47d4b6f9ac74">llvm::IntAttributeImpl::IntAttributeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a336ed98852175e7e955e9217080bd596">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::isKnowledgeWorthPreserving</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#a48b71d6b1b3a5ef2016ed307e23b2f71">llvm::AttributeImpl::Profile</a>.</p>

</div>
</div>

### isTypeAttrKind() {#a44b9bbfc65ea129fe5c7fe72ea004d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Attribute::isTypeAttrKind (<a href="#aab7ee4b8fd1d3e7e4cea87868855e60e">AttrKind</a> Kind)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a88097e7039070e670b83a2f0c420f977">addRawAttributeValue</a>, <a href="#a438a746d30d8cd255a96ffb06749602e">get</a> and <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#abc11c5784b54b55a9e82aa4bbbcb06bf">llvm::AttrBuilder::getTypeAttr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NumIntAttrKinds {#ae7e34d497535013df4857850c013d85f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::Attribute::NumIntAttrKinds = LastIntAttr - FirstIntAttr + 1</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

### NumTypeAttrKinds {#a043cae0ec5fae762c2f2e5c108da971e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::Attribute::NumTypeAttrKinds = LastTypeAttr - FirstTypeAttr + 1</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

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
