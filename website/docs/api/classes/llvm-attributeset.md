---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/attributeset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AttributeSet` Class Reference

<p>This class holds the attributes for a particular argument, parameter, function, or return value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AttributeSet { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e90e873ae304e75966619a3e706a295">iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae89691953facd45503846331c71859f7">AttributeSet</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> is a trivially copyable value type. <a href="#ae89691953facd45503846331c71859f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb1949c764bb38c15b7c5bd8107fb2f">AttributeSet</a> (const AttributeSet &amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ea8aea916cd8302e4713f2c2345204">AttributeSet</a> (AttributeSetNode *ASN)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7bbd0aec416d43a29e60e851aa00f8">~AttributeSet</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53727566039329ca5e9208d25fc4afa0">operator==</a> (const AttributeSet &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0f20be890835497699df17c616909f">operator!=</a> (const AttributeSet &amp;O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b9418751d1f1f1b99e5b05d0ed7efa">addAttribute</a> (LLVMContext &amp;C, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an argument attribute. <a href="#af2b9418751d1f1f1b99e5b05d0ed7efa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415b8a189bf60e9f7f743c59408e3b95">addAttribute</a> (LLVMContext &amp;C, StringRef Kind, StringRef Value=StringRef()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a target-dependent attribute. <a href="#a415b8a189bf60e9f7f743c59408e3b95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f189c4026ace551d70a16566e641b1">addAttributes</a> (LLVMContext &amp;C, AttributeSet AS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attributes to the attribute set. <a href="#a46f189c4026ace551d70a16566e641b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1247d3316a7816eaee459556671caab5">removeAttribute</a> (LLVMContext &amp;C, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute from this set. <a href="#a1247d3316a7816eaee459556671caab5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac0004bd4937c1de995d7fd1ef010efd">removeAttribute</a> (LLVMContext &amp;C, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attribute from this set. <a href="#aac0004bd4937c1de995d7fd1ef010efd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3392828dc2b425dbafab7dd81fae786">removeAttributes</a> (LLVMContext &amp;C, const AttributeMask &amp;AttrsToRemove) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified attributes from this set. <a href="#aa3392828dc2b425dbafab7dd81fae786">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d9b863a7b6781a87890f1474b55150">intersectWith</a> (LLVMContext &amp;C, AttributeSet Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to intersect this <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> with Other. <a href="#a63d9b863a7b6781a87890f1474b55150">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af135b1c30e805d731ab9a709cfb74ce5">getNumAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of attributes in this set. <a href="#af135b1c30e805d731ab9a709cfb74ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e88ecc68b413d829593f385d84dca6">hasAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if attributes exists in this set. <a href="#a03e88ecc68b413d829593f385d84dca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51fc96070af1597981c3000171e1a5ab">hasAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists in this set. <a href="#a51fc96070af1597981c3000171e1a5ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4a9dbe24069cc098527b505fab861c">hasAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the attribute exists in this set. <a href="#aae4a9dbe24069cc098527b505fab861c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50af3bf5ee8727df07c79065d61c204">getAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute object. <a href="#ab50af3bf5ee8727df07c79065d61c204">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3322f35facffb8a21244b040e2a9599">getAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target-dependent attribute object. <a href="#aa3322f35facffb8a21244b040e2a9599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbebeeab2f7fc663ae61eb5c391a79db">getAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90abd2918349f316b579114bd44ef17">getStackAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac98c505a75cb4d3883913ca0aa0437">getDereferenceableBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6315746619b1a42c4a466582f82d34">getDereferenceableOrNullBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ade48bec43f06da0e142b9c8d27ccb1">getByValType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e118d056b68673a2c5b4f85d1a4c17">getStructRetType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07c0c5638ef5fa4da628d22a3347e8b">getByRefType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7f8b65e8459440e4a71c3076cdad21d">getPreallocatedType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1948967a0a7675ab316c1b30d2cabdef">getInAllocaType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae05f76fbca2d63deaa0afcdfad5b60d0">getElementType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867c581afc07ab3d8066493ba6fb047e">getAllocSizeArgs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820e9cc1761fc0b1abf0eae5791d8ab9">getVScaleRangeMin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ce8577645d6ed872880aacd53ac8ce">getVScaleRangeMax</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869ddfab05d4e80046bf248d211e3e96">getUWTableKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022e1f0b85c0273bd954327152f43d5a">getAllocKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481ff076fc621dd7d69f160632b8f7df">getMemoryEffects</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/captureinfo">CaptureInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae543167d9a338d4a3d5adb63b3643d1c">getCaptureInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65bf55d7831e567f14c791ab3a9376f">getNoFPClass</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d970fbb2839d43eea2ca4675abd3380">getAsString</a> (bool InAttrGrp=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8984085edcf095d697764f03314c7ae6">hasParentContext</a> (LLVMContext &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this attribute set belongs to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#a8984085edcf095d697764f03314c7ae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0e90e873ae304e75966619a3e706a295">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb72099c01f493de3b1b4768cddf770">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0e90e873ae304e75966619a3e706a295">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d6284eaaa73040ae5829d51dbeacfe3">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ce36dbf14e9ac50946fb22b1c2bca2">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c7c9d4e73d1faca03266302e5c8dee">AttributeListImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributesetnode">AttributeSetNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82990293b2bafd376a3a58e2d17e35d4">SetNode</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private implementation pointer. <a href="#a82990293b2bafd376a3a58e2d17e35d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a> (LLVMContext &amp;C, const AttrBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cf798325c216183c6894d028d02117b">get</a> (LLVMContext &amp;C, ArrayRef&lt; Attribute &gt; Attrs)</td>
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

<p>This class holds the attributes for a particular argument, parameter, function, or return value.</p>


<p>It is an immutable value type that is cheap to copy. Adding and removing enum attributes is intended to be fast, but adding and removing string or integer attributes involves a <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> lookup.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a0e90e873ae304e75966619a3e706a295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AttributeSet::iterator =  const Attribute *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

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


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a>.</p>


<p>Referenced by <a href="#ac84243e1c08596f66aa0ee1f836ebe00">DenseMapInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AttributeSet() {#ae89691953facd45503846331c71859f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeSet::AttributeSet ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> is a trivially copyable value type.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="#a5cf798325c216183c6894d028d02117b">get</a> and <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a>.</p>

</div>
</div>

### AttributeSet() {#aceb1949c764bb38c15b7c5bd8107fb2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeSet::AttributeSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &amp;)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### AttributeSet() {#a16ea8aea916cd8302e4713f2c2345204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeSet::AttributeSet (<a href="/web-llvm/docs/api/classes/llvm/attributesetnode">AttributeSetNode</a> * ASN)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AttributeSet() {#a7e7bbd0aec416d43a29e60e851aa00f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeSet::~AttributeSet ()</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a3e0f20be890835497699df17c616909f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeSet::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &amp; O)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

### operator==() {#a53727566039329ca5e9208d25fc4afa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeSet::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> &amp; O)</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttribute() {#af2b9418751d1f1f1b99e5b05d0ed7efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Add an argument attribute.</p>


<p>Returns a new set because attribute sets are immutable.</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a46f189c4026ace551d70a16566e641b1">addAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a> and <a href="#a51fc96070af1597981c3000171e1a5ab">hasAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a50c6490cf353f064946c4e32673ac098">llvm::OpenMPIRBuilder::addAttributes</a>.</p>

</div>
</div>

### addAttribute() {#a415b8a189bf60e9f7f743c59408e3b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
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

<p>Add a target-dependent attribute.</p>


<p>Returns a new set because attribute sets are immutable.</p>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a46f189c4026ace551d70a16566e641b1">addAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a>.</p>

</div>
</div>

### addAttributes() {#a46f189c4026ace551d70a16566e641b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::addAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> AS)</td>
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

<p>Add attributes to the attribute set.</p>


<p>Returns a new set because attribute sets are immutable.</p>


<p>Declaration at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a> and <a href="#a03e88ecc68b413d829593f385d84dca6">hasAttributes</a>.</p>


<p>Referenced by <a href="#af2b9418751d1f1f1b99e5b05d0ed7efa">addAttribute</a>, <a href="#a415b8a189bf60e9f7f743c59408e3b95">addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a50c6490cf353f064946c4e32673ac098">llvm::OpenMPIRBuilder::addAttributes</a>.</p>

</div>
</div>

### begin() {#a8cb72099c01f493de3b1b4768cddf770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet::iterator AttributeSet::begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a63d9b863a7b6781a87890f1474b55150">intersectWith</a>.</p>

</div>
</div>

### dump() {#af6ce36dbf14e9ac50946fb22b1c2bca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void AttributeSet::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a7d970fbb2839d43eea2ca4675abd3380">getAsString</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### end() {#a8d6284eaaa73040ae5829d51dbeacfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet::iterator AttributeSet::end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#a63d9b863a7b6781a87890f1474b55150">intersectWith</a>.</p>

</div>
</div>

### getAlignment() {#abbebeeab2f7fc663ae61eb5c391a79db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeSet::getAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a704aa0a94c0e6bf8fd60e6e4e463e93d">llvm::AttributeList::getParamAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a9bb1595f5c255bb9ec836172ad5537e9">llvm::AttributeList::getRetAlignment</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a5c59325f9c3c1526f4439392c892fd41">optimizeCallInst</a>.</p>

</div>
</div>

### getAllocKind() {#a022e1f0b85c0273bd954327152f43d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocFnKind AttributeSet::getAllocKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a50abfb2dceb5d84bcbf1cf263e33d7d9">llvm::AttributeList::getAllocKind</a>.</p>

</div>
</div>

### getAllocSizeArgs() {#a867c581afc07ab3d8066493ba6fb047e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; &gt; AttributeSet::getAllocSizeArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>.</p>

</div>
</div>

### getAsString() {#a7d970fbb2839d43eea2ca4675abd3380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AttributeSet::getAsString (bool InAttrGrp=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1198 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#af6ce36dbf14e9ac50946fb22b1c2bca2">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a917739f8f62442b8fea20bbe72cab891">llvm::AttributeList::getAsString</a>.</p>

</div>
</div>

### getAttribute() {#ab50af3bf5ee8727df07c79065d61c204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute AttributeSet::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the attribute object.</p>

<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343af2bbdf9f72c085adc4d0404e370f0f4c">llvm::Attribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">llvm::AttributeList::getAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ab6b2a026f921a5c932f3320ede3e19ac">llvm::AttributeList::getAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ae6559a2babd0e7bd0f96d7116fb49940">llvm::AttributeList::getParamRange</a>, <a href="#a63d9b863a7b6781a87890f1474b55150">intersectWith</a> and <a href="/web-llvm/docs/api/namespaces/llvm/attributefuncs/#ab2dcaa046e6a38983e74ce28a120ce79">llvm::AttributeFuncs::typeIncompatible</a>.</p>

</div>
</div>

### getAttribute() {#aa3322f35facffb8a21244b040e2a9599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute AttributeSet::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the target-dependent attribute object.</p>

<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343af2bbdf9f72c085adc4d0404e370f0f4c">llvm::Attribute</a>.</p>

</div>
</div>

### getByRefType() {#ae07c0c5638ef5fa4da628d22a3347e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeSet::getByRefType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada3107abfa5601f959a5403190d230f8">llvm::AttributeList::getParamByRefType</a>.</p>

</div>
</div>

### getByValType() {#a2ade48bec43f06da0e142b9c8d27ccb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeSet::getByValType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ab58adac46c3ade432914ab977a69e17e">llvm::AttributeList::getParamByValType</a>.</p>

</div>
</div>

### getCaptureInfo() {#ae543167d9a338d4a3d5adb63b3643d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaptureInfo AttributeSet::getCaptureInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/captureinfo/#a31aa72bf151bb3f45d97317ccafc071c">llvm::CaptureInfo::all</a>.</p>

</div>
</div>

### getDereferenceableBytes() {#abac98c505a75cb4d3883913ca0aa0437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeSet::getDereferenceableBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a62f9460daf3f10c40cbeae0fd222cbd9">llvm::AttributeList::getParamDereferenceableBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#abda2f1696e90762ee9b7b64065c64969">llvm::AttributeList::getRetDereferenceableBytes</a>.</p>

</div>
</div>

### getDereferenceableOrNullBytes() {#aec6315746619b1a42c4a466582f82d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeSet::getDereferenceableOrNullBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac2ac94e810bcb4e307b82617c2d1f22d">llvm::AttributeList::getParamDereferenceableOrNullBytes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ae6b7413239e3f901328769ef2b5a23b0">llvm::AttributeList::getRetDereferenceableOrNullBytes</a>.</p>

</div>
</div>

### getElementType() {#ae05f76fbca2d63deaa0afcdfad5b60d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeSet::getElementType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a9d429f5f04915251440ffdafeb462616">llvm::AttributeList::getParamElementType</a>.</p>

</div>
</div>

### getInAllocaType() {#a1948967a0a7675ab316c1b30d2cabdef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeSet::getInAllocaType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a7b3b0b8961a38c7735a4b9660c42be7b">llvm::AttributeList::getParamInAllocaType</a>.</p>

</div>
</div>

### getMemoryEffects() {#a481ff076fc621dd7d69f160632b8f7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects AttributeSet::getMemoryEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#aff771abf487136aeebb6862871d5e715">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#afb984e3fb006d09d90fcc934789cfbd8">llvm::AttributeList::getMemoryEffects</a>.</p>

</div>
</div>

### getNoFPClass() {#ac65bf55d7831e567f14c791ab3a9376f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest AttributeSet::getNoFPClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4759a508982cd525d9f17024f09aea22">llvm::fcNone</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#acc215f164f494921945f7cb648056c56">llvm::AttributeList::getParamNoFPClass</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a7d05f2b6b9067ce92dc32f2f6443df5d">llvm::AttributeList::getRetNoFPClass</a>.</p>

</div>
</div>

### getNumAttributes() {#af135b1c30e805d731ab9a709cfb74ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AttributeSet::getNumAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of attributes in this set.</p>

<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### getPreallocatedType() {#ab7f8b65e8459440e4a71c3076cdad21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeSet::getPreallocatedType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#aa27e1eb608ff6d7e99bbba7d7aaf5b71">llvm::AttributeList::getParamPreallocatedType</a>.</p>

</div>
</div>

### getStackAlignment() {#aa90abd2918349f316b579114bd44ef17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign AttributeSet::getStackAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ab0eaea88fb8f6bc99c7547113ec906bc">llvm::AttributeList::getFnStackAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ab9095b759fb33104bdcafec14e2b15c1">llvm::AttributeList::getParamStackAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a3a5a24c43e105c203f779ca9a0ae0093">llvm::AttributeList::getRetStackAlignment</a>.</p>

</div>
</div>

### getStructRetType() {#a73e118d056b68673a2c5b4f85d1a4c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeSet::getStructRetType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a0e3b1e69f26a3784d71f161942e31829">llvm::AttributeList::getParamStructRetType</a>.</p>

</div>
</div>

### getUWTableKind() {#a869ddfab05d4e80046bf248d211e3e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UWTableKind AttributeSet::getUWTableKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a98312c308907b87211168eda9c6b605b">llvm::AttributeList::getUWTableKind</a>.</p>

</div>
</div>

### getVScaleRangeMax() {#aa5ce8577645d6ed872880aacd53ac8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; AttributeSet::getVScaleRangeMax ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### getVScaleRangeMin() {#a820e9cc1761fc0b1abf0eae5791d8ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AttributeSet::getVScaleRangeMin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### hasAttribute() {#a51fc96070af1597981c3000171e1a5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeSet::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists in this set.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1107 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>Referenced by <a href="#af2b9418751d1f1f1b99e5b05d0ed7efa">addAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a09a57939ead526bbae148522e31f198d">llvm::AttributeList::hasAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a6590789e70f40b3d72d525bb7327dcbc">llvm::AttributeList::hasAttributeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a794d6b65a466293b4ce971189b2e9ab1">llvm::GlobalVariable::hasImplicitSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a09453ddb2ea4103fd552fed3db38f794">printFunctionArgExts</a>, <a href="#a1247d3316a7816eaee459556671caab5">removeAttribute</a> and <a href="#aac0004bd4937c1de995d7fd1ef010efd">removeAttribute</a>.</p>

</div>
</div>

### hasAttribute() {#aae4a9dbe24069cc098527b505fab861c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeSet::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the attribute exists in this set.</p>

<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### hasAttributes() {#a03e88ecc68b413d829593f385d84dca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeSet::hasAttributes ()</td>
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

<p>Return true if attributes exists in this set.</p>

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="#a46f189c4026ace551d70a16566e641b1">addAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad544515efb693b15ac9855c6be03189b">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a180523993bcaffcbbb7cca7a3fc0d51c">llvm::AttributeList::hasAttributesAtIndex</a>, <a href="#a8984085edcf095d697764f03314c7ae6">hasParentContext</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>.</p>

</div>
</div>

### hasParentContext() {#a8984085edcf095d697764f03314c7ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeSet::hasParentContext (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this attribute set belongs to the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a03e88ecc68b413d829593f385d84dca6">hasAttributes</a>.</p>

</div>
</div>

### intersectWith() {#a63d9b863a7b6781a87890f1474b55150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AttributeSet &gt; AttributeSet::intersectWith (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> Other)</td>
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

<p>Try to intersect this <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> with Other.</p>


<p>Returns std::nullopt if the two lists are inherently incompatible (imply different behavior, not just analysis).</p>


<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a062f49b866f0e49c0dd872c2a904b5db">llvm::AttrBuilder::addAlignmentAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a39b827eb3d46a1c7c9c66905b46c2a48">llvm::AttrBuilder::addCapturesAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a6ac29dd4821e6321d0987b951582a85d">llvm::AttrBuilder::addMemoryAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a2eaea5837bb95874261fd1bca760e137">llvm::AttrBuilder::addNoFPClassAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#ae84514c1d131430da5f249455d15041f">llvm::AttrBuilder::addRangeAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a57bb5ff1076799c12e720e248f40a791">llvm::AttrBuilder::addRawIntAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8cb72099c01f493de3b1b4768cddf770">begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8d6284eaaa73040ae5829d51dbeacfe3">end</a>, <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#af1c88577e9470957be5ad4e4d401146a">llvm::Attribute::getAlignment</a>, <a href="#ab50af3bf5ee8727df07c79065d61c204">getAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#af356410c6b277e5a12369be877371edb">llvm::Attribute::getCaptureInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6fea074fd9120ff82abd8f9e0036a12a">llvm::Attribute::getKindAsEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a7c68b48aeb5f2440cf65d5e8b2e16040">llvm::Attribute::getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6b18d31b344ea210a82c4028b7684946">llvm::Attribute::getNoFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a10eb642c38648a5edb4a6bc7ce217a17">llvm::Attribute::getRange</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1db9b109e0e28e38eb43086b679dc271">llvm::Attribute::getValueAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a9e7776eef7d7515a9288bbc4e4654388">llvm::Attribute::hasKindAsEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#af3b008eee2735671b4bfdabd4df07b35">llvm::Attribute::intersectMustPreserve</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aa586fffdd286955ca876838f11a5f6d3">llvm::Attribute::intersectWithAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a11f48b3f20c58e11564df402e02a1592">llvm::Attribute::intersectWithCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a3d708ef8b38a269452e88f7c0fcfa5f8">llvm::Attribute::intersectWithMin</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#ad343d2ea041d596a04db3252e3017cad">llvm::Attribute::isEnumAttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#ac2d5f8ba4215304f89a401248abed393">llvm::Attribute::isIntAttrKind</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a> and <a href="/web-llvm/docs/api/structs/llvm/maybealign/#a06846474be3ab85f8d30c388faf3b116">llvm::MaybeAlign::valueOrOne</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad67533111413cc397100c48c82291ec7">llvm::AttributeList::intersectWith</a>.</p>

</div>
</div>

### removeAttribute() {#a1247d3316a7816eaee459556671caab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::removeAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Remove the specified attribute from this set.</p>


<p>Returns a new set because attribute sets are immutable.</p>


<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a> and <a href="#a51fc96070af1597981c3000171e1a5ab">hasAttribute</a>.</p>

</div>
</div>

### removeAttribute() {#aac0004bd4937c1de995d7fd1ef010efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::removeAttribute (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Remove the specified attribute from this set.</p>


<p>Returns a new set because attribute sets are immutable.</p>


<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a> and <a href="#a51fc96070af1597981c3000171e1a5ab">hasAttribute</a>.</p>

</div>
</div>

### removeAttributes() {#aa3392828dc2b425dbafab7dd81fae786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::removeAttributes (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
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

<p>Remove the specified attributes from this set.</p>


<p>Returns a new set because attribute sets are immutable.</p>


<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ae8ed437b15a7ca943716e5284a9cb9a6">get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AttributeListImpl {#a72c7c9d4e73d1faca03266302e5c8dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::AttributeSet::AttributeListImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

### SetNode {#a82990293b2bafd376a3a58e2d17e35d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSetNode* llvm::AttributeSet::SetNode = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private implementation pointer.</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#ae8ed437b15a7ca943716e5284a9cb9a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
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



<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ae89691953facd45503846331c71859f7">AttributeSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/attributesetnode/#aea231e8710d7b9a61e424c3f0ad22e85">llvm::AttributeSetNode::get</a>.</p>


<p>Referenced by <a href="#af2b9418751d1f1f1b99e5b05d0ed7efa">addAttribute</a>, <a href="#a415b8a189bf60e9f7f743c59408e3b95">addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada583c27bb2634195f2964c7e695a0b3">llvm::AttributeList::addAttributeAtIndex</a>, <a href="#a46f189c4026ace551d70a16566e641b1">addAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ab58814a61429a0b976eae58a0695c206">llvm::AttributeList::addAttributesAtIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a3f1e8df5d1ec58e81979760331f7808e">llvm::AttributeList::addParamAttribute</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac0b476a2ef81faca335499a5cafb9241">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4ac0d01bf5ca24e679de53067c8f6a44">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#aa3e752c843b2d32061a0dfbb3b784eb9">llvm::AttributeList::get</a>, <a href="#a63d9b863a7b6781a87890f1474b55150">intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="#a1247d3316a7816eaee459556671caab5">removeAttribute</a>, <a href="#aac0004bd4937c1de995d7fd1ef010efd">removeAttribute</a> and <a href="#aa3392828dc2b425dbafab7dd81fae786">removeAttributes</a>.</p>

</div>
</div>

### get() {#a5cf798325c216183c6894d028d02117b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet AttributeSet::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &gt; Attrs)</td>
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



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ae89691953facd45503846331c71859f7">AttributeSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/attributesetnode/#aea231e8710d7b9a61e424c3f0ad22e85">llvm::AttributeSetNode::get</a>.</p>

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
