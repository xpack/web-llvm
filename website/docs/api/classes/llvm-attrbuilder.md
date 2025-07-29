---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/attrbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AttrBuilder` Class

<p>This class is used in conjunction with the <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">Attribute::get</a> method to create an <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AttrBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> (LLVMContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126b8d1322df4469acdd78cd068b9cd9">AttrBuilder</a> (const AttrBuilder &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7b8635dbe2ea1164deb68b3472bec2">AttrBuilder</a> (AttrBuilder &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04c6ca27bfe182389cccf2ec1113460">AttrBuilder</a> (LLVMContext &amp;Ctx, const Attribute &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd4de1460995af3299849187d09c4e1">AttrBuilder</a> (LLVMContext &amp;Ctx, AttributeSet AS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19fdcd83e92aeff9d2bf8ff322d6618">operator==</a> (const AttrBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff33b435e0a75999042827ca4f4b28c">operator!=</a> (const AttrBuilder &amp;B) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1546ba76a8d78e0a34a7e9111467288d">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a> (Attribute::AttrKind Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an attribute to the builder. <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7464f6980d299143f57a229f73181c39">addAttribute</a> (Attribute A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object to the builder. <a href="#a7464f6980d299143f57a229f73181c39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df399b697ebab2755c841d66350778f">addAttribute</a> (StringRef A, StringRef V=StringRef())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the target-dependent attribute to the builder. <a href="#a1df399b697ebab2755c841d66350778f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63e528eeff5082f6920b10244143920">removeAttribute</a> (Attribute::AttrKind Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an attribute from the builder. <a href="#aa63e528eeff5082f6920b10244143920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a9eff4713139ed6dc481a14a2a6897">removeAttribute</a> (StringRef A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the target-dependent attribute from the builder. <a href="#aa9a9eff4713139ed6dc481a14a2a6897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987229e1e53239051e8e0d581c7b6395">removeAttribute</a> (Attribute A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the target-dependent attribute from the builder. <a href="#a987229e1e53239051e8e0d581c7b6395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f05fda2b6c78a87f8d6e608b55693f7">merge</a> (const AttrBuilder &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the attributes from the builder. <a href="#a3f05fda2b6c78a87f8d6e608b55693f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8bb6f24f26021a4ea1b6486bc983db">remove</a> (const AttributeMask &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the attributes from the builder. <a href="#abf8bb6f24f26021a4ea1b6486bc983db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39fc1d3fa5b22ffc2dc48e94b40409e2">overlaps</a> (const AttributeMask &amp;AM) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the builder has any attribute that's in the specified builder. <a href="#a39fc1d3fa5b22ffc2dc48e94b40409e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6abb550fd00c7568af7b045429491d9e">contains</a> (Attribute::AttrKind A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the builder has the specified attribute. <a href="#a6abb550fd00c7568af7b045429491d9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a656771b0cea2b1276b684e1cba00f5">contains</a> (StringRef A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the builder has the specified target-dependent attribute. <a href="#a0a656771b0cea2b1276b684e1cba00f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cf3cb56358d18065c78992569c32d2f">hasAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the builder has IR-level attributes. <a href="#a4cf3cb56358d18065c78992569c32d2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b551ed387e14d474d11852713de201">getAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> with the given Kind. <a href="#a25b551ed387e14d474d11852713de201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9210487118bedcf64de77fc4427941c7">getAttribute</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> with the given Kind. <a href="#a9210487118bedcf64de77fc4427941c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac809872a1cc7c2d6be09b58f8cf7b400">getRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the range if the attribute exists (std::nullopt is returned otherwise). <a href="#ac809872a1cc7c2d6be09b58f8cf7b400">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196eaf12b6408f442a6d164c336d3d52">getRawIntAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return raw (possibly packed/encoded) value of integer attribute or std::nullopt if not set. <a href="#a196eaf12b6408f442a6d164c336d3d52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c04a127391177020d55364130abc481">getAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the alignment attribute, if it exists. <a href="#a5c04a127391177020d55364130abc481">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405a29f0133cf557a593dcc3cca7ffe2">getStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the stack alignment attribute, if it exists. <a href="#a405a29f0133cf557a593dcc3cca7ffe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477c1842d901f08be882df39e2622190">getDereferenceableBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the number of dereferenceable bytes, if the dereferenceable attribute exists (zero is returned otherwise). <a href="#a477c1842d901f08be882df39e2622190">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6368ff5b970cdae9731e73e92ded8e">getDereferenceableOrNullBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the number of dereferenceable_or_null bytes, if the dereferenceable_or_null attribute exists (zero is returned otherwise). <a href="#a9e6368ff5b970cdae9731e73e92ded8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve type for the given type attribute. <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083aac381cdc9cfb2194983b3d568825">getByValType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the byval type. <a href="#a083aac381cdc9cfb2194983b3d568825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ae84086635f30842f58148b2f12153">getStructRetType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the sret type. <a href="#ae6ae84086635f30842f58148b2f12153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423397fe206ed3dc1dcb5197481cf5e3">getByRefType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the byref type. <a href="#a423397fe206ed3dc1dcb5197481cf5e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689e4253d15e22e474fe0bade6747a15">getPreallocatedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the preallocated type. <a href="#a689e4253d15e22e474fe0bade6747a15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab02acc2888e8d6360a57d767038faa">getInAllocaType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the inalloca type. <a href="#a8ab02acc2888e8d6360a57d767038faa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad808bb8ebc706c23f9a9a513e74262be">getAllocSizeArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the allocsize args, or std::nullopt if the attribute does not exist. <a href="#ad808bb8ebc706c23f9a9a513e74262be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a> (Attribute::AttrKind Kind, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add integer attribute with raw value (packed/encoded if necessary). <a href="#a57bb5ff1076799c12e720e248f40a791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062f49b866f0e49c0dd872c2a904b5db">addAlignmentAttr</a> (MaybeAlign Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns an alignment into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a062f49b866f0e49c0dd872c2a904b5db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5aa952b736a1bc4b079799fb0cfeee3">addAlignmentAttr</a> (unsigned Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns an int alignment (which must be a power of 2) into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#ad5aa952b736a1bc4b079799fb0cfeee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9099509c2ae2a88e0bb1b01fd404f40a">addStackAlignmentAttr</a> (MaybeAlign Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns a stack alignment into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a9099509c2ae2a88e0bb1b01fd404f40a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fdcd265c364dba7fcb4fa50cdb8510">addStackAlignmentAttr</a> (unsigned Align)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns an int stack alignment (which must be a power of 2) into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a19fdcd265c364dba7fcb4fa50cdb8510">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676e566281b7f39a0c685bc6d1032283">addDereferenceableAttr</a> (uint64_t Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns the number of dereferenceable bytes into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a676e566281b7f39a0c685bc6d1032283">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac857d238048717f6284dd46bbf867fcd">addDereferenceableOrNullAttr</a> (uint64_t Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns the number of dereferenceable_or_null bytes into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#ac857d238048717f6284dd46bbf867fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea27caeeec5d68cef4a452b8cc25162">addAllocSizeAttr</a> (unsigned ElemSizeArg, const std::optional&lt; unsigned &gt; &amp;NumElemsArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns one (or two) ints into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#adea27caeeec5d68cef4a452b8cc25162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4566311f748debbde7053963d802d87e">addVScaleRangeAttr</a> (unsigned MinValue, std::optional&lt; unsigned &gt; MaxValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns two ints into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a4566311f748debbde7053963d802d87e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a> (Attribute::AttrKind Kind, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a type attribute with the given type. <a href="#ad79f5341284d1c6e5d0be00043b1235c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0b4baa6787e964dded34f7137090ff">addByValAttr</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns a byval type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a5f0b4baa6787e964dded34f7137090ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046d7cf22a984d2bc22d82443375706e">addStructRetAttr</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns a sret type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a046d7cf22a984d2bc22d82443375706e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6c55813387d70c3263f0aa9d9f731f">addByRefAttr</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns a byref type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a2a6c55813387d70c3263f0aa9d9f731f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867308c21cb0d61d6569651f3174b9e8">addPreallocatedAttr</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns a preallocated type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#a867308c21cb0d61d6569651f3174b9e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4629ac8989d1523b9d92c979b8e7bdf">addInAllocaAttr</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns an inalloca type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#aa4629ac8989d1523b9d92c979b8e7bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8240e42bf15e889595d0a5f054f32f04">addAllocSizeAttrFromRawRepr</a> (uint64_t RawAllocSizeRepr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an allocsize attribute, using the representation returned by Attribute.getIntValue(). <a href="#a8240e42bf15e889595d0a5f054f32f04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed6d6889a7e667138cb66e12cd41e27">addVScaleRangeAttrFromRawRepr</a> (uint64_t RawVScaleRangeRepr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a vscale_range attribute, using the representation returned by Attribute.getIntValue(). <a href="#a0ed6d6889a7e667138cb66e12cd41e27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af841d3a8b19fc08621a782d9f4091921">addUWTableAttr</a> (UWTableKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This turns the unwind table kind into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>. <a href="#af841d3a8b19fc08621a782d9f4091921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a230b26f00b5d9bb361631d0ed53c1730">addAllocKindAttr</a> (AllocFnKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac29dd4821e6321d0987b951582a85d">addMemoryAttr</a> (MemoryEffects ME)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add memory effect attribute. <a href="#a6ac29dd4821e6321d0987b951582a85d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39b827eb3d46a1c7c9c66905b46c2a48">addCapturesAttr</a> (CaptureInfo CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add captures attribute. <a href="#a39b827eb3d46a1c7c9c66905b46c2a48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eaea5837bb95874261fd1bca760e137">addNoFPClassAttr</a> (FPClassTest NoFPClassMask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773374bcf6e6f638f8a996c1df6cc998">addConstantRangeAttr</a> (Attribute::AttrKind Kind, const ConstantRange &amp;CR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> attribute with the given range. <a href="#a773374bcf6e6f638f8a996c1df6cc998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84514c1d131430da5f249455d15041f">addRangeAttr</a> (const ConstantRange &amp;CR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add range attribute. <a href="#ae84514c1d131430da5f249455d15041f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a731a53feffdd319d9fbaaf4154e30f09">addConstantRangeListAttr</a> (Attribute::AttrKind Kind, ArrayRef&lt; ConstantRange &gt; Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute with the given ranges. <a href="#a731a53feffdd319d9fbaaf4154e30f09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68bcd3ec2f0fecf3aa12a335ceb45d94">addInitializesAttr</a> (const ConstantRangeList &amp;CRL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add initializes attribute. <a href="#a68bcd3ec2f0fecf3aa12a335ceb45d94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42e22bee0625f08b9d569a6d62bbd3b">attrs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f9e984e933c2e6b3985e7902488686">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a295469fcde5bbe8fa8c6770fb33bd6c2">Attrs</a></td>
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

<p>This class is used in conjunction with the <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">Attribute::get</a> method to create an <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object.</p>


<p>The object itself is uniquified. The Builder's value, however, is not. So this can be used as a quick way to test for equality, presence of attributes, etc.</p>


<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AttrBuilder() {#a4566caff986223552a7433e011c0832f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttrBuilder::AttrBuilder (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx)</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="#a062f49b866f0e49c0dd872c2a904b5db">addAlignmentAttr</a>, <a href="#ad5aa952b736a1bc4b079799fb0cfeee3">addAlignmentAttr</a>, <a href="#a230b26f00b5d9bb361631d0ed53c1730">addAllocKindAttr</a>, <a href="#a8240e42bf15e889595d0a5f054f32f04">addAllocSizeAttrFromRawRepr</a>, <a href="#a7464f6980d299143f57a229f73181c39">addAttribute</a>, <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a>, <a href="#a1df399b697ebab2755c841d66350778f">addAttribute</a>, <a href="#a2a6c55813387d70c3263f0aa9d9f731f">addByRefAttr</a>, <a href="#a5f0b4baa6787e964dded34f7137090ff">addByValAttr</a>, <a href="#a39b827eb3d46a1c7c9c66905b46c2a48">addCapturesAttr</a>, <a href="#a773374bcf6e6f638f8a996c1df6cc998">addConstantRangeAttr</a>, <a href="#a676e566281b7f39a0c685bc6d1032283">addDereferenceableAttr</a>, <a href="#ac857d238048717f6284dd46bbf867fcd">addDereferenceableOrNullAttr</a>, <a href="#aa4629ac8989d1523b9d92c979b8e7bdf">addInAllocaAttr</a>, <a href="#a68bcd3ec2f0fecf3aa12a335ceb45d94">addInitializesAttr</a>, <a href="#a6ac29dd4821e6321d0987b951582a85d">addMemoryAttr</a>, <a href="#a2eaea5837bb95874261fd1bca760e137">addNoFPClassAttr</a>, <a href="#a867308c21cb0d61d6569651f3174b9e8">addPreallocatedAttr</a>, <a href="#ae84514c1d131430da5f249455d15041f">addRangeAttr</a>, <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="#a9099509c2ae2a88e0bb1b01fd404f40a">addStackAlignmentAttr</a>, <a href="#a19fdcd265c364dba7fcb4fa50cdb8510">addStackAlignmentAttr</a>, <a href="#a046d7cf22a984d2bc22d82443375706e">addStructRetAttr</a>, <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a>, <a href="#af841d3a8b19fc08621a782d9f4091921">addUWTableAttr</a>, <a href="#a4566311f748debbde7053963d802d87e">addVScaleRangeAttr</a>, <a href="#a0ed6d6889a7e667138cb66e12cd41e27">addVScaleRangeAttrFromRawRepr</a>, <a href="#a0e7b8635dbe2ea1164deb68b3472bec2">AttrBuilder</a>, <a href="#a126b8d1322df4469acdd78cd068b9cd9">AttrBuilder</a>, <a href="#a3f05fda2b6c78a87f8d6e608b55693f7">merge</a>, <a href="#adff33b435e0a75999042827ca4f4b28c">operator!=</a>, <a href="#ab19fdcd83e92aeff9d2bf8ff322d6618">operator==</a>, <a href="#abf8bb6f24f26021a4ea1b6486bc983db">remove</a>, <a href="#a987229e1e53239051e8e0d581c7b6395">removeAttribute</a>, <a href="#aa63e528eeff5082f6920b10244143920">removeAttribute</a> and <a href="#aa9a9eff4713139ed6dc481a14a2a6897">removeAttribute</a>.</p>

</div>
</div>

### AttrBuilder() {#a126b8d1322df4469acdd78cd068b9cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttrBuilder::AttrBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;)</td>
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



<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### AttrBuilder() {#a0e7b8635dbe2ea1164deb68b3472bec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttrBuilder::AttrBuilder (<a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp;&amp;)</td>
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



<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### AttrBuilder() {#af04c6ca27bfe182389cccf2ec1113460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttrBuilder::AttrBuilder (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &amp; A)</td>
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



<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a>.</p>

</div>
</div>

### AttrBuilder() {#a4dd4de1460995af3299849187d09c4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder::AttrBuilder (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2055 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#adff33b435e0a75999042827ca4f4b28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttrBuilder::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
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



<p>Definition at line 1290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### operator==() {#ab19fdcd83e92aeff9d2bf8ff322d6618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttrBuilder::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2334 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAlignmentAttr() {#a062f49b866f0e49c0dd872c2a904b5db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAlignmentAttr (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns an alignment into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>


<p>This call has no effect if <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is not set.</p>


<p>Declaration at line 1193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a089e46429cea4cfcd2ba23a6fc6aa676">llvm::Value::MaximumAlignment</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#ad5aa952b736a1bc4b079799fb0cfeee3">addAlignmentAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a7c497627acf5128770bd9fa245b44fbd">addFramePointerAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### addAlignmentAttr() {#ad5aa952b736a1bc4b079799fb0cfeee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; llvm::AttrBuilder::addAlignmentAttr (unsigned Align)</td>
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

<p>This turns an int alignment (which must be a power of 2) into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>


<p>This call has no effect if <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is 0. Deprecated, use the version using a <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a>.</p>


<p>Definition at line 1199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a062f49b866f0e49c0dd872c2a904b5db">addAlignmentAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### addAllocKindAttr() {#a230b26f00b5d9bb361631d0ed53c1730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAllocKindAttr (<a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2231 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### addAllocSizeAttr() {#adea27caeeec5d68cef4a452b8cc25162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAllocSizeAttr (unsigned ElemSizeArg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; unsigned &gt; &amp; NumElemsArg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns one (or two) ints into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a8240e42bf15e889595d0a5f054f32f04">addAllocSizeAttrFromRawRepr</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a84f56e05a576b94b89af30ba313805c4">packAllocSizeArgs</a>.</p>

</div>
</div>

### addAllocSizeAttrFromRawRepr() {#a8240e42bf15e889595d0a5f054f32f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAllocSizeAttrFromRawRepr (uint64_t RawAllocSizeRepr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an allocsize attribute, using the representation returned by Attribute.getIntValue().</p>

<p>Declaration at line 1251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2191 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="#adea27caeeec5d68cef4a452b8cc25162">addAllocSizeAttr</a>.</p>

</div>
</div>

### addAttribute() {#a59d23ba2e7eac46cbc6cd3086e013b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an attribute to the builder.</p>

<p>Declaration at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2108 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a050caf901311dc932e97973d70d17916">addAttributeImpl</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a2c299a4357972cc32be0eda57abda580">addAsyncContextAttrs</a>, <a href="#a773374bcf6e6f638f8a996c1df6cc998">addConstantRangeAttr</a>, <a href="#a731a53feffdd319d9fbaaf4154e30f09">addConstantRangeListAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a7c497627acf5128770bd9fa245b44fbd">addFramePointerAttrs</a>, <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a0e09834bc2b325fc2f777641292396e1">addSwiftSelfAttrs</a>, <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a>, <a href="#af04c6ca27bfe182389cccf2ec1113460">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#ad915c31dcf8d35cf0affa3f8f13a043b">llvm::AtomicInfo::EmitAtomicLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>, <a href="#a3f05fda2b6c78a87f8d6e608b55693f7">merge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac12e315180fb16cb5874fb41526ca453">llvm::codegen::setFunctionAttributes</a>.</p>

</div>
</div>

### addAttribute() {#a7464f6980d299143f57a229f73181c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> object to the builder.</p>

<p>Declaration at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2100 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a050caf901311dc932e97973d70d17916">addAttributeImpl</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6fea074fd9120ff82abd8f9e0036a12a">llvm::Attribute::getKindAsEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a3ad8f83f8d6165314fe8f173645dd458">llvm::Attribute::getKindAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0571df3e57128211e09cba4544aa9ca7">llvm::Attribute::isStringAttribute</a>.</p>

</div>
</div>

### addAttribute() {#a1df399b697ebab2755c841d66350778f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> A, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> V=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the target-dependent attribute to the builder.</p>

<p>Declaration at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2113 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a050caf901311dc932e97973d70d17916">addAttributeImpl</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>.</p>

</div>
</div>

### addByRefAttr() {#a2a6c55813387d70c3263f0aa9d9f731f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addByRefAttr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns a byref type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2253 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### addByValAttr() {#a5f0b4baa6787e964dded34f7137090ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addByValAttr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns a byval type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### addCapturesAttr() {#a39b827eb3d46a1c7c9c66905b46c2a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addCapturesAttr (<a href="/web-llvm/docs/api/classes/llvm/captureinfo">CaptureInfo</a> CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add captures attribute.</p>

<p>Declaration at line 1268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2220 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/captureinfo/#af61cca54b7388093a13c70663bf10f2f">llvm::CaptureInfo::toIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### addConstantRangeAttr() {#a773374bcf6e6f638f8a996c1df6cc998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addConstantRangeAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> attribute with the given range.</p>

<p>Declaration at line 1274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2265 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>.</p>


<p>Referenced by <a href="#ae84514c1d131430da5f249455d15041f">addRangeAttr</a>.</p>

</div>
</div>

### addConstantRangeListAttr() {#a731a53feffdd319d9fbaaf4154e30f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addConstantRangeListAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> attribute with the given ranges.</p>

<p>Declaration at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2278 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>.</p>


<p>Referenced by <a href="#a68bcd3ec2f0fecf3aa12a335ceb45d94">addInitializesAttr</a>.</p>

</div>
</div>

### addDereferenceableAttr() {#a676e566281b7f39a0c685bc6d1032283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addDereferenceableAttr (uint64_t Bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns the number of dereferenceable bytes into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2172 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a7c497627acf5128770bd9fa245b44fbd">addFramePointerAttrs</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a>.</p>

</div>
</div>

### addDereferenceableOrNullAttr() {#ac857d238048717f6284dd46bbf867fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addDereferenceableOrNullAttr (uint64_t Bytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns the number of dereferenceable_or_null bytes into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2178 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a>.</p>

</div>
</div>

### addInAllocaAttr() {#aa4629ac8989d1523b9d92c979b8e7bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addInAllocaAttr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns an inalloca type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2261 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### addInitializesAttr() {#a68bcd3ec2f0fecf3aa12a335ceb45d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addInitializesAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrangelist">ConstantRangeList</a> &amp; CRL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add initializes attribute.</p>

<p>Declaration at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2283 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a731a53feffdd319d9fbaaf4154e30f09">addConstantRangeListAttr</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a61eefc2024082167d4176620bc3272c2">llvm::ConstantRangeList::rangesRef</a>.</p>

</div>
</div>

### addMemoryAttr() {#a6ac29dd4821e6321d0987b951582a85d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addMemoryAttr (<a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> ME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add memory effect attribute.</p>

<p>Declaration at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2216 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ac96f712f6d153d48c535886b4f8aef99">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::toIntValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### addNoFPClassAttr() {#a2eaea5837bb95874261fd1bca760e137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addNoFPClassAttr (<a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> NoFPClassMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2224 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da4759a508982cd525d9f17024f09aea22">llvm::fcNone</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### addPreallocatedAttr() {#a867308c21cb0d61d6569651f3174b9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addPreallocatedAttr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns a preallocated type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2257 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### addRangeAttr() {#ae84514c1d131430da5f249455d15041f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addRangeAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add range attribute.</p>

<p>Declaration at line 1278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2273 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a773374bcf6e6f638f8a996c1df6cc998">addConstantRangeAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### addRawIntAttr() {#a57bb5ff1076799c12e720e248f40a791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addRawIntAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add integer attribute with raw value (packed/encoded if necessary).</p>

<p>Declaration at line 1189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2142 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>.</p>


<p>Referenced by <a href="#a062f49b866f0e49c0dd872c2a904b5db">addAlignmentAttr</a>, <a href="#a230b26f00b5d9bb361631d0ed53c1730">addAllocKindAttr</a>, <a href="#a8240e42bf15e889595d0a5f054f32f04">addAllocSizeAttrFromRawRepr</a>, <a href="#a39b827eb3d46a1c7c9c66905b46c2a48">addCapturesAttr</a>, <a href="#a676e566281b7f39a0c685bc6d1032283">addDereferenceableAttr</a>, <a href="#ac857d238048717f6284dd46bbf867fcd">addDereferenceableOrNullAttr</a>, <a href="#a6ac29dd4821e6321d0987b951582a85d">addMemoryAttr</a>, <a href="#a2eaea5837bb95874261fd1bca760e137">addNoFPClassAttr</a>, <a href="#a9099509c2ae2a88e0bb1b01fd404f40a">addStackAlignmentAttr</a>, <a href="#af841d3a8b19fc08621a782d9f4091921">addUWTableAttr</a>, <a href="#a0ed6d6889a7e667138cb66e12cd41e27">addVScaleRangeAttrFromRawRepr</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a63d9b863a7b6781a87890f1474b55150">llvm::AttributeSet::intersectWith</a>.</p>

</div>
</div>

### addStackAlignmentAttr() {#a9099509c2ae2a88e0bb1b01fd404f40a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addStackAlignmentAttr (<a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns a stack alignment into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>


<p>This call has no effect if <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is not set.</p>


<p>Declaration at line 1205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2163 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a19fdcd265c364dba7fcb4fa50cdb8510">addStackAlignmentAttr</a>.</p>

</div>
</div>

### addStackAlignmentAttr() {#a19fdcd265c364dba7fcb4fa50cdb8510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; llvm::AttrBuilder::addStackAlignmentAttr (unsigned Align)</td>
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

<p>This turns an int stack alignment (which must be a power of 2) into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>


<p>This call has no effect if <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is 0. Deprecated, use the version using a <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a>.</p>


<p>Definition at line 1211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="#a9099509c2ae2a88e0bb1b01fd404f40a">addStackAlignmentAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### addStructRetAttr() {#a046d7cf22a984d2bc22d82443375706e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addStructRetAttr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns a sret type into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2249 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ad79f5341284d1c6e5d0be00043b1235c">addTypeAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>

</div>
</div>

### addTypeAttr() {#ad79f5341284d1c6e5d0be00043b1235c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addTypeAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a type attribute with the given type.</p>

<p>Declaration at line 1232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2241 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>.</p>


<p>Referenced by <a href="#a2a6c55813387d70c3263f0aa9d9f731f">addByRefAttr</a>, <a href="#a5f0b4baa6787e964dded34f7137090ff">addByValAttr</a>, <a href="#aa4629ac8989d1523b9d92c979b8e7bdf">addInAllocaAttr</a>, <a href="#a867308c21cb0d61d6569651f3174b9e8">addPreallocatedAttr</a> and <a href="#a046d7cf22a984d2bc22d82443375706e">addStructRetAttr</a>.</p>

</div>
</div>

### addUWTableAttr() {#af841d3a8b19fc08621a782d9f4091921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addUWTableAttr (<a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns the unwind table kind into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2210 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### addVScaleRangeAttr() {#a4566311f748debbde7053963d802d87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addVScaleRangeAttr (unsigned MinValue, std::optional&lt; unsigned &gt; MaxValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This turns two ints into the form used internally in <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a>.</p>

<p>Declaration at line 1228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2197 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a0ed6d6889a7e667138cb66e12cd41e27">addVScaleRangeAttrFromRawRepr</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a9a8cb941feb6e29b5089568ab1dc2044">packVScaleRangeArgs</a>.</p>

</div>
</div>

### addVScaleRangeAttrFromRawRepr() {#a0ed6d6889a7e667138cb66e12cd41e27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::addVScaleRangeAttrFromRawRepr (uint64_t RawVScaleRangeRepr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a vscale_range attribute, using the representation returned by Attribute.getIntValue().</p>

<p>Declaration at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a57bb5ff1076799c12e720e248f40a791">addRawIntAttr</a> and <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>.</p>


<p>Referenced by <a href="#a4566311f748debbde7053963d802d87e">addVScaleRangeAttr</a>.</p>

</div>
</div>

### attrs() {#aa42e22bee0625f08b9d569a6d62bbd3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Attribute &gt; llvm::AttrBuilder::attrs ()</td>
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



<p>Definition at line 1287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

### clear() {#a1546ba76a8d78e0a34a7e9111467288d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AttrBuilder::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>

</div>
</div>

### contains() {#a6abb550fd00c7568af7b045429491d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttrBuilder::contains (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the builder has the specified attribute.</p>

<p>Declaration at line 1116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2326 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a25b551ed387e14d474d11852713de201">getAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9f172ff9cc319871a4d4b30b1c442dba">llvm::attributesPermitTailCall</a>.</p>

</div>
</div>

### contains() {#a0a656771b0cea2b1276b684e1cba00f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttrBuilder::contains (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the builder has the specified target-dependent attribute.</p>

<p>Declaration at line 1120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2330 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a25b551ed387e14d474d11852713de201">getAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>

</div>
</div>

### getAlignment() {#a5c04a127391177020d55364130abc481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::AttrBuilder::getAlignment ()</td>
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

<p>Retrieve the alignment attribute, if it exists.</p>

<p>Definition at line 1142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a196eaf12b6408f442a6d164c336d3d52">getRawIntAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>.</p>

</div>
</div>

### getAllocSizeArgs() {#ad808bb8ebc706c23f9a9a513e74262be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; unsigned, std::optional&lt; unsigned &gt; &gt; &gt; AttrBuilder::getAllocSizeArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the allocsize args, or std::nullopt if the attribute does not exist.</p>

<p>Declaration at line 1185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2148 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a25b551ed387e14d474d11852713de201">getAttribute</a>.</p>

</div>
</div>

### getAttribute() {#a25b551ed387e14d474d11852713de201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute AttrBuilder::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> with the given Kind.</p>


<p>The returned attribute will be invalid if the Kind is not present in the builder.</p>


<p>Declaration at line 1127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2304 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="#a6abb550fd00c7568af7b045429491d9e">contains</a>, <a href="#a0a656771b0cea2b1276b684e1cba00f5">contains</a>, <a href="#ad808bb8ebc706c23f9a9a513e74262be">getAllocSizeArgs</a>, <a href="#ac809872a1cc7c2d6be09b58f8cf7b400">getRange</a>, <a href="#a196eaf12b6408f442a6d164c336d3d52">getRawIntAttr</a> and <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a>.</p>

</div>
</div>

### getAttribute() {#a9210487118bedcf64de77fc4427941c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute AttrBuilder::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> with the given Kind.</p>


<p>The returned attribute will be invalid if the Kind is not present in the builder.</p>


<p>Declaration at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2312 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### getByRefType() {#a423397fe206ed3dc1dcb5197481cf5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AttrBuilder::getByRefType ()</td>
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

<p>Retrieve the byref type.</p>

<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a>.</p>

</div>
</div>

### getByValType() {#a083aac381cdc9cfb2194983b3d568825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AttrBuilder::getByValType ()</td>
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

<p>Retrieve the byval type.</p>

<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### getDereferenceableBytes() {#a477c1842d901f08be882df39e2622190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AttrBuilder::getDereferenceableBytes ()</td>
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

<p>Retrieve the number of dereferenceable bytes, if the dereferenceable attribute exists (zero is returned otherwise).</p>

<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a196eaf12b6408f442a6d164c336d3d52">getRawIntAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>.</p>

</div>
</div>

### getDereferenceableOrNullBytes() {#a9e6368ff5b970cdae9731e73e92ded8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AttrBuilder::getDereferenceableOrNullBytes ()</td>
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

<p>Retrieve the number of dereferenceable_or_null bytes, if the dereferenceable_or_null attribute exists (zero is returned otherwise).</p>

<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a196eaf12b6408f442a6d164c336d3d52">getRawIntAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>.</p>

</div>
</div>

### getInAllocaType() {#a8ab02acc2888e8d6360a57d767038faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AttrBuilder::getInAllocaType ()</td>
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

<p>Retrieve the inalloca type.</p>

<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### getPreallocatedType() {#a689e4253d15e22e474fe0bade6747a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AttrBuilder::getPreallocatedType ()</td>
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

<p>Retrieve the preallocated type.</p>

<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a>.</p>

</div>
</div>

### getRange() {#ac809872a1cc7c2d6be09b58f8cf7b400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; AttrBuilder::getRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the range if the attribute exists (std::nullopt is returned otherwise).</p>

<p>Declaration at line 1135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2319 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a25b551ed387e14d474d11852713de201">getAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a10eb642c38648a5edb4a6bc7ce217a17">llvm::Attribute::getRange</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>.</p>

</div>
</div>

### getRawIntAttr() {#a196eaf12b6408f442a6d164c336d3d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; AttrBuilder::getRawIntAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return raw (possibly packed/encoded) value of integer attribute or std::nullopt if not set.</p>

<p>Declaration at line 1139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2134 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a25b551ed387e14d474d11852713de201">getAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#ac2d5f8ba4215304f89a401248abed393">llvm::Attribute::isIntAttrKind</a>.</p>


<p>Referenced by <a href="#a5c04a127391177020d55364130abc481">getAlignment</a>, <a href="#a477c1842d901f08be882df39e2622190">getDereferenceableBytes</a>, <a href="#a9e6368ff5b970cdae9731e73e92ded8e">getDereferenceableOrNullBytes</a> and <a href="#a405a29f0133cf557a593dcc3cca7ffe2">getStackAlignment</a>.</p>

</div>
</div>

### getStackAlignment() {#a405a29f0133cf557a593dcc3cca7ffe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::AttrBuilder::getStackAlignment ()</td>
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

<p>Retrieve the stack alignment attribute, if it exists.</p>

<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#a196eaf12b6408f442a6d164c336d3d52">getRawIntAttr</a>.</p>

</div>
</div>

### getStructRetType() {#ae6ae84086635f30842f58148b2f12153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AttrBuilder::getStructRetType ()</td>
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

<p>Retrieve the sret type.</p>

<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Reference <a href="#abc11c5784b54b55a9e82aa4bbbcb06bf">getTypeAttr</a>.</p>

</div>
</div>

### getTypeAttr() {#abc11c5784b54b55a9e82aa4bbbcb06bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttrBuilder::getTypeAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve type for the given type attribute.</p>

<p>Declaration at line 1164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2235 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a25b551ed387e14d474d11852713de201">getAttribute</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a44b9bbfc65ea129fe5c7fe72ea004d00">llvm::Attribute::isTypeAttrKind</a>.</p>


<p>Referenced by <a href="#a423397fe206ed3dc1dcb5197481cf5e3">getByRefType</a>, <a href="#a083aac381cdc9cfb2194983b3d568825">getByValType</a>, <a href="#a8ab02acc2888e8d6360a57d767038faa">getInAllocaType</a>, <a href="#a689e4253d15e22e474fe0bade6747a15">getPreallocatedType</a> and <a href="#ae6ae84086635f30842f58148b2f12153">getStructRetType</a>.</p>

</div>
</div>

### hasAttributes() {#a4cf3cb56358d18065c78992569c32d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttrBuilder::hasAttributes ()</td>
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

<p>Return true if the builder has IR-level attributes.</p>

<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a>.</p>

</div>
</div>

### merge() {#a3f05fda2b6c78a87f8d6e608b55693f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the attributes from the builder.</p>


<p>Attributes in the passed builder overwrite attributes in this builder if they have the same key.</p>


<p>Declaration at line 1106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2287 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a59d23ba2e7eac46cbc6cd3086e013b49">addAttribute</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac0b476a2ef81faca335499a5cafb9241">llvm::AttributeList::get</a>.</p>

</div>
</div>

### overlaps() {#a39fc1d3fa5b22ffc2dc48e94b40409e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttrBuilder::overlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the builder has any attribute that's in the specified builder.</p>

<p>Declaration at line 1113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2300 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/classes/llvm/attributemask/#ab0582254d525e9b4612f0239ac19fd39">llvm::AttributeMask::contains</a>.</p>

</div>
</div>

### remove() {#abf8bb6f24f26021a4ea1b6486bc983db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::remove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the attributes from the builder.</p>

<p>Declaration at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2295 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/attributemask/#ab0582254d525e9b4612f0239ac19fd39">llvm::AttributeMask::contains</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### removeAttribute() {#aa63e528eeff5082f6920b10244143920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::removeAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove an attribute from the builder.</p>

<p>Declaration at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2118 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f172ff9cc319871a4d4b30b1c442dba">llvm::attributesPermitTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6e7da554442443ffe8928fd5a93086f5">legalizeCallAttributes</a> and <a href="#a987229e1e53239051e8e0d581c7b6395">removeAttribute</a>.</p>

</div>
</div>

### removeAttribute() {#aa9a9eff4713139ed6dc481a14a2a6897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; AttrBuilder::removeAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the target-dependent attribute from the builder.</p>

<p>Declaration at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>, definition at line 2126 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### removeAttribute() {#a987229e1e53239051e8e0d581c7b6395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttrBuilder &amp; llvm::AttrBuilder::removeAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> A)</td>
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

<p>Remove the target-dependent attribute from the builder.</p>

<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a4566caff986223552a7433e011c0832f">AttrBuilder</a> and <a href="#aa63e528eeff5082f6920b10244143920">removeAttribute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Attrs {#a295469fcde5bbe8fa8c6770fb33bd6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Attribute, 8&gt; llvm::AttrBuilder::Attrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

</div>
</div>

### Ctx {#a20f9e984e933c2e6b3985e7902488686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::AttrBuilder::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">Attributes.h</a>.</p>

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
