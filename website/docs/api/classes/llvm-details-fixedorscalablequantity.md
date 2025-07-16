---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/details/fixedorscalablequantity
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FixedOrScalableQuantity` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename LeafTy, typename ValueTy&gt;
class llvm::details::FixedOrScalableQuantity&lt;LeafTy, ValueTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">llvm/Support/TypeSize.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> = ValueTy</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LeafTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59675c5fa1fc34247739c1df536b9133">operator+=</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LeafTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c0d88b8d823c0c18c21b4b91365e0a4">operator-=</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LeafTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ab27bb0e58cb46a74af0ea692e77eac">operator*=</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e28b88fcfb3b13fe5261fd36c3494ce">operator+</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8eacff679953e94be89455a833918426">operator-</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab94b07c6934d7e020724ae604a5071f4">operator*</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U = ScalarTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::enable_if_t&lt; std::is_signed_v&lt; U &gt;, LeafTy &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6faa75af0be43f118a793a6725578d97">operator-</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57beba2321012fb9cb702573f26fefff">FixedOrScalableQuantity</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83554f332972d3e99357ab6574583da7">FixedOrScalableQuantity</a> (ScalarTy Quantity, bool Scalable)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac09a553664c52c31c224889f13203db5">operator==</a> (const FixedOrScalableQuantity &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a262f60815eefc33a8eca40965e7e9e24">operator!=</a> (const FixedOrScalableQuantity &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a09ebb5b0890e1564c60b9ba44f46b7b2">operator bool</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad96fee81c3174ef427bf779d73fb1ef2">isZero</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5cafb166cf7c4937f5647a084c4eaee2">isNonZero</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7fe5b99b6520cb29c14b69dcf50d031f">getWithIncrement</a> (ScalarTy RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">RHS</span> to the underlying quantity. <a href="#a7fe5b99b6520cb29c14b69dcf50d031f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr <a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4ab9dd9440c55bee1aa4a1195cee759">getKnownMinValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum value this quantity can represent. <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9188f84e1dd67530330dcab9cae787d7">isScalable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the quantity is scaled by a runtime quantity (vscale). <a href="#a9188f84e1dd67530330dcab9cae787d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab9a9b0568c1c524f01499c7930b3bf9">isFixed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the quantity is not scaled by vscale. <a href="#aab9a9b0568c1c524f01499c7930b3bf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa9a9e04ec6182c18c74c9cf5380651a2">isKnownEven</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A return value of true indicates we know at compile time that the number of elements (vscale * Min) is definitely even. <a href="#aa9a9e04ec6182c18c74c9cf5380651a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1618ca92d9fa0b2b577698fb006b84cc">isKnownMultipleOf</a> (ScalarTy RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function tells the caller whether the element count is known at compile time to be a multiple of the scalar value RHS. <a href="#a1618ca92d9fa0b2b577698fb006b84cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7b551b121b963cff16967ccee0ac6a1">isKnownMultipleOf</a> (const FixedOrScalableQuantity &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether or not the callee is known to be a multiple of RHS. <a href="#ad7b551b121b963cff16967ccee0ac6a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr <a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a33880aaca0ad05e5f1557f079305bde5">getFixedValue</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7510a639ca53c1bfa1c90c6dfc7eb2e">divideCoefficientBy</a> (ScalarTy RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We do not provide the '/' operator here because division for polynomial types does not work in the same way as for normal integer types. <a href="#ae7510a639ca53c1bfa1c90c6dfc7eb2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5b3e822013fe51665e9bddc4874cd48">multiplyCoefficientBy</a> (ScalarTy RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr LeafTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7809cb455d050177426fa66f1bb82222">coefficientNextPowerOf2</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a171e00e7870c0461608394f2270e78b7">hasKnownScalarFactor</a> (const FixedOrScalableQuantity &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there exists a value X where RHS.multiplyCoefficientBy(X) will result in a value whose quantity matches our own. <a href="#a171e00e7870c0461608394f2270e78b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr <a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a807f8d60eeb99bb92773f3291db1c428">getKnownScalarFactor</a> (const FixedOrScalableQuantity &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a value X where RHS.multiplyCoefficientBy(X) will result in a value whose quantity matches our own. <a href="#a807f8d60eeb99bb92773f3291db1c428">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a767d56aed7d6c8252ad71590dcf90222">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Printing function. <a href="#a767d56aed7d6c8252ad71590dcf90222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00f7f73f257f28c032fec06f21b7d42e">Quantity</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea2efb72b66f0b71d52898a155f20ab0">Scalable</a> = false</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83e6442f8ebefccdb5e089732fe397ac">isKnownLT</a> (const FixedOrScalableQuantity &amp;LHS, const FixedOrScalableQuantity &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#addaa86bfa4ca26b7f366cbdd868f99bf">isKnownGT</a> (const FixedOrScalableQuantity &amp;LHS, const FixedOrScalableQuantity &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a338ba7ca7a526243ab1853d07d90fe38">isKnownLE</a> (const FixedOrScalableQuantity &amp;LHS, const FixedOrScalableQuantity &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LeafTy, typename ValueTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afb486f9022a26e1cc53ff189710dbde5">isKnownGE</a> (const FixedOrScalableQuantity &amp;LHS, const FixedOrScalableQuantity &amp;RHS)</td>
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


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ScalarTy {#acedfd762498bd93768c82e145023a2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::ScalarTy =  ValueTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator- {#a8eacff679953e94be89455a833918426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend LeafTy <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; RHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator- {#a6faa75af0be43f118a793a6725578d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend std::enable_if_t&lt; std::is_signed_v&lt; U &gt;, LeafTy &gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; LHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>.</p>

</div>
</div>

### operator-= {#a2c0d88b8d823c0c18c21b4b91365e0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend LeafTy &amp; LeafTy &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; RHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\* {#ab94b07c6934d7e020724ae604a5071f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend LeafTy <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; LHS, <a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*= {#a1ab27bb0e58cb46a74af0ea692e77eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend LeafTy &amp; LeafTy &amp; LHS, <a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+ {#a1e28b88fcfb3b13fe5261fd36c3494ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend LeafTy <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; RHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+= {#a59675c5fa1fc34247739c1df536b9133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend LeafTy &amp; LeafTy &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> LeafTy &amp; RHS</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### FixedOrScalableQuantity() {#a57beba2321012fb9cb702573f26fefff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="#a807f8d60eeb99bb92773f3291db1c428">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownScalarFactor</a>, <a href="#a171e00e7870c0461608394f2270e78b7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::hasKnownScalarFactor</a>, <a href="#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownGE</a>, <a href="#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownGT</a>, <a href="#a338ba7ca7a526243ab1853d07d90fe38">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownLE</a>, <a href="#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownLT</a>, <a href="#ad7b551b121b963cff16967ccee0ac6a1">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a>, <a href="#a262f60815eefc33a8eca40965e7e9e24">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator!=</a> and <a href="#ac09a553664c52c31c224889f13203db5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator==</a>.</p>

</div>
</div>

### FixedOrScalableQuantity() {#a83554f332972d3e99357ab6574583da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity (<a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> Quantity, bool Scalable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a> and <a href="#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a09ebb5b0890e1564c60b9ba44f46b7b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator bool ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#a5cafb166cf7c4937f5647a084c4eaee2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isNonZero</a>.</p>

</div>
</div>

### operator!=() {#a262f60815eefc33a8eca40965e7e9e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable</a>.</p>

</div>
</div>

### operator==() {#ac09a553664c52c31c224889f13203db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### coefficientNextPowerOf2() {#a7809cb455d050177426fa66f1bb82222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LeafTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::coefficientNextPowerOf2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afb65eef479f0473d0fe1666b80155237">llvm::NextPowerOf2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>.</p>

</div>
</div>

### divideCoefficientBy() {#ae7510a639ca53c1bfa1c90c6dfc7eb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LeafTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy (<a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We do not provide the '/' operator here because division for polynomial types does not work in the same way as for normal integer types.</p>


<p>We can only divide the minimum value (or coefficient) by RHS, which is not the same as (Min * Vscale) / RHS The caller is recommended to use this function in combination with isKnownMultipleOf(RHS), which lets the caller know if it's possible to perform a lossless divide by RHS.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bc1ae031c7513b30d9ddaed87eb4f31">getDeinterleaveShiftAndTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40558d23c7bc31dd0b4f1d6b00199487">llvm::LegalizerHelper::lowerEXT</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>.</p>

</div>
</div>

### getFixedValue() {#a33880aaca0ad05e5f1557f079305bde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="#ad96fee81c3174ef427bf779d73fb1ef2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memcpyoptimizer-cpp-/memsetranges/#aa8fa6e6b269b75ce442434704398c792">anonymous{MemCpyOptimizer.cpp}::MemsetRanges::addStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#af57aa964441f0796b3d49de878edaca5">areExtractShuffleVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad07ba9d946b424c9de4782f4ae7879bb">llvm::ARMTargetLowering::canCombineStoreAndExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a787f048d94a8f173da27cb792cff4758">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::convertEVLToMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8f832cfa0e0121c6fd066c0f3b25f5f">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertToOptType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad46652b66427679d9c221df6915019ca">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a01b9989f797101a150d7a960255adfec">doInstrumentAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae4c50e6300599d50ba706c0d2b780502">llvm::LoopVectorizationCostModel::expectedCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#adccfbc5892aaeafbf2178ddc7c71bde5">getAvailableLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a906498ba76d47e4abcb2d3892e5301b2">llvm::TargetTransformInfoImplBase::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a7712dd4392b7eb944b709ac8442634d9">llvm::EVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a874fbbec4937797974c9d5056769421a">llvm::MVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a503e6d0278c44cd66c3e17913cc08d4e">llvm::X86TTIImpl::getLoadStoreVecRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a2ec6ecbecf7304214d0593f863e9db95">llvm::RISCVTTIImpl::getMaximumVF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aab7f609c46a7e90bfd662c80db4ad29b">llvm::AArch64TTIImpl::getMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a04b3a69fabb49a792bdd785030325f89">llvm::HexagonTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a2648fd0c9417e0aeb3e8b194c6509357">llvm::EVT::getScalarStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7e724b18dda7c663005261457f5fce3b">llvm::MVT::getScalarStoreSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a694f0a06fb32a28862ef184803eaadd8">llvm::SystemZTTIImpl::getVectorTruncCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa69a30633eb175372a93a42bfc5d89f2">llvm::AArch64TargetLowering::hasAndNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0b80ad51fe1f4372499e354b6f2e402">llvm::AMDGPU::instrumentAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a36ca78229b46f9e53eb095d48647cdf3">llvm::AArch64TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5a707ef219e51df6fbaff782ed1d44a6">llvm::X86TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#af278f33f3e54a61566b7fdff3835e980">isObjectSizeLessThanOrEq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c56296baea6c99fa0e3d10ff2c0145a">llvm::isSafeToLoadUnconditionally</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a01cb590e9c05c3675fe75693d84b3120">llvm::AArch64TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a5ac204c71b6c7eefceba4fdcbf6a4a79">llvm::MSP430TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aa537392c1f43f9b471c6cb9dead13df7">llvm::SystemZTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#af7d561e1175f661ea1725d1026a10677">llvm::LoopAccessInfo::LoopAccessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a313bdf934f1f8454b6800d8d997801d2">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a4d9b426f332b379758b891f032f85d52">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::paintOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a5372f41d26211efe4518e2c77f559ba5">TypeSizeToSizeIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aa4e6667108e3ef2a76f536bd8f5e93e6">upgradeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#aa558a9e76bb04a92258576836a53592b">llvm::LLT::vector</a>.</p>

</div>
</div>

### getKnownMinValue() {#ac4ab9dd9440c55bee1aa4a1195cee759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum value this quantity can represent.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a65edce9c8505e3d3b9c0d90794458288">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a2a5ba8caf566b63bea759399eb58927f">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="#a7809cb455d050177426fa66f1bb82222">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::coefficientNextPowerOf2</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a465d0006e51f34ba35fccf2cb3f72f89">llvm::VPFirstOrderRecurrencePHIRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a002897456acb2af7a1e3cbb5f7a3b245">llvm::RISCVTargetLowering::computeVLMAXBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8bf72f690d62d0f26a984b9cbe96f37e">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a01ee44fd979fc25e2afe3d23a2079494">llvm::RISCVTargetLowering::decomposeSubvectorInsertExtractToSubRegs</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad46652b66427679d9c221df6915019ca">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter</a>, <a href="#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ac503442fd011b1b4a03ab40ad3f9402e">llvm::VPRegionBlock::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#adeba9ee43ee94300c5bb47b99b47a945">findMemType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a85b96f315b961f037b6aedfca25133c5">llvm::AArch64TargetLowering::functionArgumentNeedsConsecutiveRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a94b8d8925deffd735f51d36b77d3f9ca">getAddressForMemoryInput</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#a2855a09c41f64a31ab555a9ab7ec9c5f">llvm::VPLane::getAsRuntimeExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae968aa14d25b7b04bf82019ad48f599c">llvm::SelectionDAG::GetDependentSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad8398a35cd187d6a75b460fcf54b5236">llvm::LoopVectorizationCostModel::getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a923e1e1096d253c80d8a241754cb878f">llvm::EVT::getEVTString</a>, <a href="#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d1a24269cf97e06932cf3d8a482d2077/#aaf68376c4e8b4d85f3cdb154f4ec1023">llvm::DenseMapInfo&lt; ElementCount, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="#a807f8d60eeb99bb92773f3291db1c428">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownScalarFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#a837587e1ae180bf0ba71faec8349de4a">llvm::VPLane::getLaneFromEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac27709ca33b27034fb25d6fb83cb5fb1">llvm::RISCVTargetLowering::getLMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aab7f609c46a7e90bfd662c80db4ad29b">llvm::AArch64TTIImpl::getMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a8f69c05b63d549b2e51069b6edaf73c6">getMinimalExtentFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a365f29ab21721393fe82ff3ae4554e5e">llvm::AArch64TargetLowering::getNumInterleavedAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a252df3516bdd18a47c638e745bcd01f4">llvm::AArch64TTIImpl::getPartialReductionCost</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a15f3027fdcad3b33960402d9739afe4b">llvm::EVT::getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#af5d482532f3f9df9fed007e78e983dcd">llvm::MVT::getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a78d9c499deb0a2aadbf8e7ed5e717a8e">llvm::RISCVTargetLowering::getRegClassIDForVecVT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a0a09a1144b3dbb1ddc00f0ced5030522">anonymous{VFABIDemangler.cpp}::getScalableECFromSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a3b229a84730d00c5e9ed36784521d304">llvm::DataLayout::getTypeStoreSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a53fb11c0140efce7e25ca9ff5ccbac96">llvm::EVT::getVectorMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a0ea8063abb874faff99f39c4e849f8de">HasAddressTaken</a>, <a href="#a171e00e7870c0461608394f2270e78b7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::hasKnownScalarFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/giseladdressing/#ada859501cbde2153a4e7fd7a19a7f682">llvm::GISelAddressing::instMayAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aa2915714199e899f7766d49f87ec2ad6">llvm::CastInst::isBitCastable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab7edde995b7986f98c3f59788b960eba">isIndvarOverflowCheckKnownFalse</a>, <a href="#aa9a9e04ec6182c18c74c9cf5380651a2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownEven</a>, <a href="#ad7b551b121b963cff16967ccee0ac6a1">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a>, <a href="#a1618ca92d9fa0b2b577698fb006b84cc">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad0581b9db1cc9ac63ca3c7eb944d4fd8">isPackedVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a86e581cb8e98cb0649e8b524eed5c9c0">llvm::LoopVectorizationLegality::isUniform</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a768562b4668773f96f4ac2d425a5d547">isUnpackedVectorVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad228a0beee72778d8ea7dbd9de249158">isValidEGW</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a9a537a836fd9ef45c214308647907c69">llvm::LocationSize::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aea8c2b718c1dd866d61c29081c1eb44f">llvm::RISCVTargetLowering::joinRegisterPartsIntoValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#afd30020fad29faa956eb3bc6647244de">llvm::VPLane::mapToCacheIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a66c37e901bc47ad309a6f13c2edeecd4">llvm::LegalityPredicates::memSizeNotByteSizePow2</a>, <a href="#aa5b3e822013fe51665e9bddc4874cd48">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::multiplyCoefficientBy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7b49e80a5c71aff0a4a6d6a637cafe3f">performLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>, <a href="#a767d56aed7d6c8252ad71590dcf90222">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a0e48eed8c71f1e31ececec593aa98908">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af415da4daf8365b80a0f0dba2ee8490e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastFixedLengthToScalableVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac490424228331c1beb5025ef6d45d2a6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastScalableToFixedLengthVector</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a3bf0370381bb5be6f2e6f4bbe28f3289">llvm::ObjectSizeOffsetVisitor::visitAllocaInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

### getKnownScalarFactor() {#a807f8d60eeb99bb92773f3291db1c428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownScalarFactor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a value X where RHS.multiplyCoefficientBy(X) will result in a value whose quantity matches our own.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a171e00e7870c0461608394f2270e78b7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::hasKnownScalarFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getWithIncrement() {#a7fe5b99b6520cb29c14b69dcf50d031f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LeafTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getWithIncrement (<a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add <span class="doxyComputerOutput">RHS</span> to the underlying quantity.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable</a>.</p>

</div>
</div>

### hasKnownScalarFactor() {#a171e00e7870c0461608394f2270e78b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::hasKnownScalarFactor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if there exists a value X where RHS.multiplyCoefficientBy(X) will result in a value whose quantity matches our own.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a807f8d60eeb99bb92773f3291db1c428">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownScalarFactor</a>.</p>

</div>
</div>

### isFixed() {#aab9a9b0568c1c524f01499c7930b3bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isFixed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the quantity is not scaled by vscale.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae4c50e6300599d50ba706c0d2b780502">llvm::LoopVectorizationCostModel::expectedCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a252df3516bdd18a47c638e745bcd01f4">llvm::AArch64TTIImpl::getPartialReductionCost</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a07db8a5919c9879e3327549f20cda2f9">llvm::LoopVectorizationCostModel::isEpilogueVectorizationProfitable</a>.</p>

</div>
</div>

### isKnownEven() {#aa9a9e04ec6182c18c74c9cf5380651a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownEven ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A return value of true indicates we know at compile time that the number of elements (vscale * Min) is definitely even.</p>


<p>However, returning false does not guarantee that the total number of elements is odd.</p>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aac3337c401bb0145fbecced8d947cebf">llvm::SelectionDAG::SplitEVL</a>.</p>

</div>
</div>

### isKnownMultipleOf() {#a1618ca92d9fa0b2b577698fb006b84cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf (<a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function tells the caller whether the element count is known at compile time to be a multiple of the scalar value RHS.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/evt/#a470621733f1ffb597e6f502040216da4">llvm::EVT::isByteSized</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a8b8f5d788ec31cd57f429ce38b5e3bb7">llvm::LLT::isByteSized</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a072534d2fcddddcd69e3c34d22c9df9d">llvm::MVT::isByteSized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aa602c4415d92f7060b1c0f1255fcf79d">isSupportedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9e44e0e5bdc7526a1b299ae804752709">llvm::CombinerHelper::matchUseVectorTruncate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>.</p>

</div>
</div>

### isKnownMultipleOf() {#ad7b551b121b963cff16967ccee0ac6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether or not the callee is known to be a multiple of RHS.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### isNonZero() {#a5cafb166cf7c4937f5647a084c4eaee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isNonZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#af7d561e1175f661ea1725d1026a10677">llvm::LoopAccessInfo::LoopAccessInfo</a>, <a href="#a09ebb5b0890e1564c60b9ba44f46b7b2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator bool</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### isScalable() {#a9188f84e1dd67530330dcab9cae787d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether the quantity is scaled by a runtime quantity (vscale).</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memcpyoptimizer-cpp-/memsetranges/#aa8fa6e6b269b75ce442434704398c792">anonymous{MemCpyOptimizer.cpp}::MemsetRanges::addStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="#a7809cb455d050177426fa66f1bb82222">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::coefficientNextPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a351251756a2dcf559089f626d9241131">llvm::VNCoercion::coerceAvailableValueToLoadType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#afcbf4a19be078644e784b539379d59b7">llvm::LoopVectorizationCostModel::collectInstsToScalarize</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a465d0006e51f34ba35fccf2cb3f72f89">llvm::VPFirstOrderRecurrencePHIRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a787f048d94a8f173da27cb792cff4758">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::convertEVLToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8bf72f690d62d0f26a984b9cbe96f37e">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae83b3d8e9a944b5d818e80524a5003e2">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad46652b66427679d9c221df6915019ca">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::discardEVLParameter</a>, <a href="#ae7510a639ca53c1bfa1c90c6dfc7eb2e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::divideCoefficientBy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a01b9989f797101a150d7a960255adfec">doInstrumentAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a85b96f315b961f037b6aedfca25133c5">llvm::AArch64TargetLowering::functionArgumentNeedsConsecutiveRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a94b8d8925deffd735f51d36b77d3f9ca">getAddressForMemoryInput</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#aecfb2afc99cffa8880ec262d026a5038">anonymous{FunctionAttrs.cpp}::getArgmentAccessInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#adccfbc5892aaeafbf2178ddc7c71bde5">getAvailableLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a906498ba76d47e4abcb2d3892e5301b2">llvm::TargetTransformInfoImplBase::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae968aa14d25b7b04bf82019ad48f599c">llvm::SelectionDAG::GetDependentSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad8398a35cd187d6a75b460fcf54b5236">llvm::LoopVectorizationCostModel::getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>, <a href="#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d1a24269cf97e06932cf3d8a482d2077/#aaf68376c4e8b4d85f3cdb154f4ec1023">llvm::DenseMapInfo&lt; ElementCount, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#a837587e1ae180bf0ba71faec8349de4a">llvm::VPLane::getLaneFromEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a6fc00f70e954c5d710caf7dbe7c231ce">llvm::RISCVTTIImpl::getMaxInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aab7f609c46a7e90bfd662c80db4ad29b">llvm::AArch64TTIImpl::getMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a78df0524a69edda72e6325cfefdcb2c1">getMinClassForRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a60be12dda0289837dae43964608cf568">llvm::ScalarEvolution::getOffsetOfExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a252df3516bdd18a47c638e745bcd01f4">llvm::AArch64TTIImpl::getPartialReductionCost</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a15f3027fdcad3b33960402d9739afe4b">llvm::EVT::getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#af5d482532f3f9df9fed007e78e983dcd">llvm::MVT::getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acfcd22eb38dbfe1acbf138754297437a">llvm::DataLayout::getTypeStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a3b229a84730d00c5e9ed36784521d304">llvm::DataLayout::getTypeStoreSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a0786ad18996fdeb6bb0e33c3bfa4ce82">llvm::VNCoercion::getValueForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a272cd16957d147ad113779617eeabf77">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::handleAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa69a30633eb175372a93a42bfc5d89f2">llvm::AArch64TargetLowering::hasAndNot</a>, <a href="#a171e00e7870c0461608394f2270e78b7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::hasKnownScalarFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0b80ad51fe1f4372499e354b6f2e402">llvm::AMDGPU::instrumentAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5964ce9ba38fe5a4d372242ac39e3f1d">llvm::LoopVectorizationCostModel::interleavedAccessCanBeWidened</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab7edde995b7986f98c3f59788b960eba">isIndvarOverflowCheckKnownFalse</a>, <a href="#ad7b551b121b963cff16967ccee0ac6a1">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a36ca78229b46f9e53eb095d48647cdf3">llvm::AArch64TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5a707ef219e51df6fbaff782ed1d44a6">llvm::X86TTIImpl::isLegalBroadcastLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a31212d6ba24ec9ee5e31110dae47ee94">llvm::AArch64TTIImpl::isLegalToVectorizeReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ae7200479e50b7404b1b98874993c341d">llvm::RISCVTTIImpl::isLegalToVectorizeReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#af278f33f3e54a61566b7fdff3835e980">isObjectSizeLessThanOrEq</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad2005ee17b5b6cb575257dc12793a077">anonymous{DeadStoreElimination.cpp}::DSEState::isOverwrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c56296baea6c99fa0e3d10ff2c0145a">llvm::isSafeToLoadUnconditionally</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a86e581cb8e98cb0649e8b524eed5c9c0">llvm::LoopVectorizationLegality::isUniform</a>, <a href="/web-llvm/docs/api/classes/llvm/vplane/#afd30020fad29faa956eb3bc6647244de">llvm::VPLane::mapToCacheIndex</a>, <a href="#aa5b3e822013fe51665e9bddc4874cd48">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::multiplyCoefficientBy</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a4d9b426f332b379758b891f032f85d52">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::paintOrigin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>, <a href="#a767d56aed7d6c8252ad71590dcf90222">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memorysanitizer-cpp/#a5372f41d26211efe4518e2c77f559ba5">TypeSizeToSizeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a3bf0370381bb5be6f2e6f4bbe28f3289">llvm::ObjectSizeOffsetVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6dc0d17c5d20afdfa4004345e930584c">widenVectorToPartType</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

### isZero() {#ad96fee81c3174ef427bf779d73fb1ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#a00f7f73f257f28c032fec06f21b7d42e">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#afcbf4a19be078644e784b539379d59b7">llvm::LoopVectorizationCostModel::collectInstsToScalarize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae2ee94a616a11388828c36d1e0b4798c">llvm::EVT::isZeroSized</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>.</p>

</div>
</div>

### multiplyCoefficientBy() {#aa5b3e822013fe51665e9bddc4874cd48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LeafTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::multiplyCoefficientBy (<a href="#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a8bc641490449721bebf9b78d67c67f05">anonymous{AArch64PostLegalizerCombiner.cpp}::applyCombineMulCMLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4156fb8bcc6a7e29ee021b01d22551e">llvm::createStepForVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2b002084e30ad9a9607108932eeae5e2">getWideningInterleave</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>.</p>

</div>
</div>

### print() {#a767d56aed7d6c8252ad71590dcf90222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Printing function.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a> and <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a15b709cd67d42712b1c324e0626b82fe">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Quantity {#a00f7f73f257f28c032fec06f21b7d42e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarTy llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Quantity = 0</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="#a83554f332972d3e99357ab6574583da7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a7fe5b99b6520cb29c14b69dcf50d031f">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getWithIncrement</a>, <a href="#a5cafb166cf7c4937f5647a084c4eaee2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isNonZero</a>, <a href="#ad96fee81c3174ef427bf779d73fb1ef2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero</a>, <a href="#a262f60815eefc33a8eca40965e7e9e24">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator!=</a> and <a href="#ac09a553664c52c31c224889f13203db5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator==</a>.</p>

</div>
</div>

### Scalable {#aea2efb72b66f0b71d52898a155f20ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::Scalable = false</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="#a83554f332972d3e99357ab6574583da7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="#a7fe5b99b6520cb29c14b69dcf50d031f">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getWithIncrement</a>, <a href="#aab9a9b0568c1c524f01499c7930b3bf9">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isFixed</a>, <a href="#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="#a262f60815eefc33a8eca40965e7e9e24">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator!=</a> and <a href="#ac09a553664c52c31c224889f13203db5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isKnownGE() {#afb486f9022a26e1cc53ff189710dbde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownGE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### isKnownGT() {#addaa86bfa4ca26b7f366cbdd868f99bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownGT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### isKnownLE() {#a338ba7ca7a526243ab1853d07d90fe38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownLE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### isKnownLT() {#a83e6442f8ebefccdb5e089732fe397ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LeafTy, typename ValueTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownLT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::FixedOrScalableQuantity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
