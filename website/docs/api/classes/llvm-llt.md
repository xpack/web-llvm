---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLT` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LLT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">llvm/CodeGenTypes/LowLevelType.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">int <a href="#a6a0a993d61caeac20bf8b25f2b4f564c">BitFieldInfo</a>[2]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is packed into 64 bits as follows: isScalar : 1 isPointer : 1 isVector : 1 with 61 bits remaining for Kind-specific data, packed in bitfields as described below. <a href="#a6a0a993d61caeac20bf8b25f2b4f564c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5577efc9d11fdc6f67722ec63890784b">DenseMapInfo&lt; LLT &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c1661410c92af9684c9f2a43325342">GISelInstProfileBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> (bool isPointer, bool isVector, bool isScalar, ElementCount EC, uint64_t SizeInBits, unsigned AddressSpace)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de4bf39741198a8e6712bd7ec1acd95">LLT</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a8919ec199949c9c5241e6c59872b5">LLT</a> (MVT VT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e16dfcff77042f93b5e237803b1bfc6">operator==</a> (const LLT &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7229c556f8111a65f13593302983f7d3">operator!=</a> (const LLT &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fb30748f1b3e8a0affd486a9f59f6d">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3989251b1a714fc8296685f77eac6e87">isScalar</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5056b68b503b3a05a4fdda5c51110d">isToken</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d825f5954d7bd527aea490668c624c6">isPointer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ca901a46a6561125ef38f6c33c2700">isPointerVector</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd23ed05c97e269d0d268636c7d6a6b7">isPointerOrPointerVector</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71181d67d0bf68c3b8a535ec20463f90">getNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of elements in a vector <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>. <a href="#a71181d67d0bf68c3b8a535ec20463f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8028200b9efbd55fe7db4c69199893d2">isScalable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is a scalable vector. <a href="#a8028200b9efbd55fe7db4c69199893d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1db89614d919436714d099c99ff12a0">isFixedVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is a fixed vector. <a href="#ad1db89614d919436714d099c99ff12a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3016e0f01ad96a198f81f74397b1c0e6">isScalableVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is a scalable vector. <a href="#a3016e0f01ad96a198f81f74397b1c0e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total size of the type. Must only be called on sized types. <a href="#a956ffd0de93798f523683b447646dd92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae456a811703836ee5d9e32c3e51a15b6">getSizeInBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total size of the type in bytes, i.e. <a href="#ae456a811703836ee5d9e32c3e51a15b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4165ca7bcbee300d5e9c065adcc1415">getScalarType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f404daab6050b7a8e95bb247d4aefb2">changeElementType</a> (LLT NewEltTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this type is a vector, return a vector with the same number of elements but the new element type. <a href="#a4f404daab6050b7a8e95bb247d4aefb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a> (unsigned NewEltSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this type is a vector, return a vector with the same number of elements but the new element size. <a href="#aaa6f42b31892a929914872c879e4b365">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adabd45e67a1847750a117317b5ef8f9f">changeElementCount</a> (ElementCount EC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector or scalar with the same element type and the new element count. <a href="#adabd45e67a1847750a117317b5ef8f9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11a4c235044d52af7fbf840dec3f278">divide</a> (int Factor) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a type that is <span class="doxyComputerOutput">Factor</span> times smaller. <a href="#af11a4c235044d52af7fbf840dec3f278">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a> (int Factor) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce a vector type that is <span class="doxyComputerOutput">Factor</span> times bigger, preserving the element type. <a href="#a52cd802a268f6ed25d878c96d8b16247">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8f5d788ec31cd57f429ce38b5e3bb7">isByteSized</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32472b5afd0ae6edb4a233a25056a6aa">getScalarSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33fa4c8cfeb9287f51f95404a459de8">getAddressSpace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the vector's element type. Only valid for vector types. <a href="#aa24450f600cabd7212bd264a6dbc190c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe2b50c065f9de917bf34a1d573253b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831ad5290836e63683b75d99679f72cc">getUniqueRAWLLTData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85735a256dd26b96c54f8ea86cb19692">getFieldValue</a> (const BitFieldInfo FieldInfo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bdd7055d7318dd851ac1510b66bc45">init</a> (bool IsPointer, bool IsVector, bool IsScalar, ElementCount EC, uint64_t SizeInBits, unsigned AddressSpace)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ea5a7549220aedf9c4f547e0c98e36">IsScalar</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36179e74cc695458feb8d53a51617f1e">IsPointer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7884b54043ff7c50d8f80148f9ff61">IsVector</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4fe0afca29f2753eed6830601b71fe">RawData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a> (unsigned SizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level scalar or aggregate "bag of bits". <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c874bad47bf92187afb13eb2840643">token</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level token; just a scalar with zero bits (or no size). <a href="#ad2c874bad47bf92187afb13eb2840643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff0361855acbbe71b15b8dc6003fbc5">pointer</a> (unsigned AddressSpace, unsigned SizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level pointer in the given address space. <a href="#a7ff0361855acbbe71b15b8dc6003fbc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5360139c6b31d85cf3e29e2e6b7cf873">vector</a> (ElementCount EC, unsigned ScalarSizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level vector of some number of elements and element width. <a href="#a5360139c6b31d85cf3e29e2e6b7cf873">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa558a9e76bb04a92258576836a53592b">vector</a> (ElementCount EC, LLT ScalarTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level vector of some number of elements and element type. <a href="#aa558a9e76bb04a92258576836a53592b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1f260fc4da86ce2e93fa8628aa0b1d">float16</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a 16-bit IEEE half value. <a href="#abb1f260fc4da86ce2e93fa8628aa0b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6abb440f4fe52097595d934283f0a1">float32</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a 32-bit IEEE float value. <a href="#aee6abb440f4fe52097595d934283f0a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0631408a6598e34659cc5495c3ec090b">float64</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a 64-bit IEEE double value. <a href="#a0631408a6598e34659cc5495c3ec090b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1eca3232b7b3072543294cd2377a37">fixed_vector</a> (unsigned NumElements, unsigned ScalarSizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level fixed-width vector of some number of elements and element width. <a href="#acd1eca3232b7b3072543294cd2377a37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9e947d00e373eba50e79fd0da66792">fixed_vector</a> (unsigned NumElements, LLT ScalarTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level fixed-width vector of some number of elements and element type. <a href="#aac9e947d00e373eba50e79fd0da66792">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8d482078435a16e34c2cc13caa6f75">scalable_vector</a> (unsigned MinNumElements, unsigned ScalarSizeInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level scalable vector of some number of elements and element width. <a href="#a3c8d482078435a16e34c2cc13caa6f75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae614d7a67bd01700a068c8e4eb6e2ef9">scalable_vector</a> (unsigned MinNumElements, LLT ScalarTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a low-level scalable vector of some number of elements and element type. <a href="#ae614d7a67bd01700a068c8e4eb6e2ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a> (ElementCount EC, LLT ScalarTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c9d40cb2f72eba97644766b2439092">scalarOrVector</a> (ElementCount EC, uint64_t ScalarSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2dab30e835a4a5c0b1bd3c04025be3">getMask</a> (const BitFieldInfo FieldInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af661ea6ff23d30dfcc385efc3c2e4168">maskAndShift</a> (uint64_t Val, uint64_t Mask, uint8_t Shift)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd694cf0e2cfd29cc8aab141bbcfa04">maskAndShift</a> (uint64_t Val, const BitFieldInfo FieldInfo)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> constexpr BitFieldInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4304de22945478f044ba43a53e17748">ScalarSizeFieldInfo</a> {32, 29}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is how the bitfields are packed per Kind: <a href="#ad4304de22945478f044ba43a53e17748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> constexpr BitFieldInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e05a7f8ac0640b2f428955ef9e517c">PointerSizeFieldInfo</a> {16, 45}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> constexpr BitFieldInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96eb54b262f9e208ab253778312198fc">PointerAddressSpaceFieldInfo</a> {24, 21}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> constexpr BitFieldInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94accdf30c05bf911f0f7729dc06c4c7">VectorElementsFieldInfo</a> {16, 5}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> constexpr BitFieldInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9cc1a3af7c8fa4101ee1689bbec7639">VectorScalableFieldInfo</a> {1, 0}</td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BitFieldInfo {#a6a0a993d61caeac20bf8b25f2b4f564c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int llvm::LLT::BitFieldInfo[2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is packed into 64 bits as follows: isScalar : 1 isPointer : 1 isVector : 1 with 61 bits remaining for Kind-specific data, packed in bitfields as described below.</p>


<p>As there isn't a simple portable way to pack bits into bitfields, here the different fields in the packed structure is described in static const *Field variables. Each of these variables is a 2-element array, with the first element describing the bitfield size and the second element describing the bitfield offset.</p>


<p>+-----—+------—+-----—+-------—+-------------------—+ |isScalar|isPointer|isVector| RawData |Notes | +-----—+------—+-----—+-------—+-------------------—+ | 0 | 0 | 0 | 0 |Invalid | +-----—+------—+-----—+-------—+-------------------—+ | 0 | 0 | 1 | 0 |Tombstone Key | +-----—+------—+-----—+-------—+-------------------—+ | 0 | 1 | 0 | 0 |Empty Key | +-----—+------—+-----—+-------—+-------------------—+ | 1 | 0 | 0 | 0 |Token | +-----—+------—+-----—+-------—+-------------------—+ | 1 | 0 | 0 | non-zero |Scalar | +-----—+------—+-----—+-------—+-------------------—+ | 0 | 1 | 0 | non-zero |Pointer | +-----—+------—+-----—+-------—+-------------------—+ | 0 | 0 | 1 | non-zero |Vector of non-pointer | +-----—+------—+-----—+-------—+-------------------—+ | 0 | 1 | 1 | non-zero |Vector of pointer | +-----—+------—+-----—+-------—+-------------------—+</p>


<p>Everything else is reserved.</p>


<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DenseMapInfo&lt; LLT &gt; {#a5577efc9d11fdc6f67722ec63890784b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### GISelInstProfileBuilder {#a73c1661410c92af9684c9f2a43325342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder">GISelInstProfileBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Reference <a href="#a73c1661410c92af9684c9f2a43325342">GISelInstProfileBuilder</a>.</p>


<p>Referenced by <a href="#a73c1661410c92af9684c9f2a43325342">GISelInstProfileBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LLT() {#a38374ccd4721f95ba3942d38afe726c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLT::LLT (bool isPointer, bool isVector, bool isScalar, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, uint64_t SizeInBits, unsigned AddressSpace)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a9d825f5954d7bd527aea490668c624c6">isPointer</a>, <a href="#a3989251b1a714fc8296685f77eac6e87">isScalar</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>


<p>Referenced by <a href="#adabd45e67a1847750a117317b5ef8f9f">changeElementCount</a>, <a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a>, <a href="#a4f404daab6050b7a8e95bb247d4aefb2">changeElementType</a>, <a href="#a5577efc9d11fdc6f67722ec63890784b">DenseMapInfo&lt; LLT &gt;</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="#aac9e947d00e373eba50e79fd0da66792">fixed_vector</a>, <a href="#acd1eca3232b7b3072543294cd2377a37">fixed_vector</a>, <a href="#abb1f260fc4da86ce2e93fa8628aa0b1d">float16</a>, <a href="#aee6abb440f4fe52097595d934283f0a1">float32</a>, <a href="#a0631408a6598e34659cc5495c3ec090b">float64</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="#ae4165ca7bcbee300d5e9c065adcc1415">getScalarType</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a>, <a href="#a4e16dfcff77042f93b5e237803b1bfc6">operator==</a>, <a href="#a7ff0361855acbbe71b15b8dc6003fbc5">pointer</a>, <a href="#ae614d7a67bd01700a068c8e4eb6e2ef9">scalable_vector</a>, <a href="#a3c8d482078435a16e34c2cc13caa6f75">scalable_vector</a>, <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a>, <a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a>, <a href="#a31c9d40cb2f72eba97644766b2439092">scalarOrVector</a>, <a href="#ad2c874bad47bf92187afb13eb2840643">token</a>, <a href="#aa558a9e76bb04a92258576836a53592b">vector</a> and <a href="#a5360139c6b31d85cf3e29e2e6b7cf873">vector</a>.</p>

</div>
</div>

### LLT() {#a9de4bf39741198a8e6712bd7ec1acd95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLT::LLT ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### LLT() {#af5a8919ec199949c9c5241e6c59872b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT::LLT (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/codegentypes/lowleveltype-cpp">LowLevelType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aa1abe2e0d36a43d780ce54ea3b197217">llvm::MVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a1eb420ba23c865af3024a336e491b983">llvm::MVT::getVectorMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2d0eea72b9e8c302a78fe1f61eb43620">llvm::MVT::isScalableTargetExtVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a447ebcc5de7a1d9bc163862bf2c78e41">llvm::MVT::isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adde2b3c4de4c4ded2b80ff32f1020b9b">llvm::MVT::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a7229c556f8111a65f13593302983f7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &amp; RHS)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### operator==() {#a4e16dfcff77042f93b5e237803b1bfc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &amp; RHS)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changeElementCount() {#adabd45e67a1847750a117317b5ef8f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::changeElementCount (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC)</td>
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

<p>Return a vector or scalar with the same element type and the new element count.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#ae4165ca7bcbee300d5e9c065adcc1415">getScalarType</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a8bc641490449721bebf9b78d67c67f05">anonymous{AArch64PostLegalizerCombiner.cpp}::applyCombineMulCMLT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a4fff4e593b92ebdfd3e0e394d52fa817">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a0ac1646365dca61b7727ec5291144c38">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1eac84349f5abc12d101036412730c5c">llvm::LegalizerHelper::fewerElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40558d23c7bc31dd0b4f1d6b00199487">llvm::LegalizerHelper::lowerEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae51c8cf31e26c03753e3f6acb6f48d56">llvm::LegalizerHelper::lowerTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>.</p>

</div>
</div>

### changeElementSize() {#aaa6f42b31892a929914872c879e4b365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::changeElementSize (unsigned NewEltSize)</td>
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

<p>If this type is a vector, return a vector with the same number of elements but the new element size.</p>


<p>Otherwise, return the new element type. Invalid for pointer types. For pointer types, use changeElementType.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="#acd23ed05c97e269d0d268636c7d6a6b7">isPointerOrPointerVector</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a> and <a href="#a5360139c6b31d85cf3e29e2e6b7cf873">vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a8bc641490449721bebf9b78d67c67f05">anonymous{AArch64PostLegalizerCombiner.cpp}::applyCombineMulCMLT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a7e7daf470bcde39a7ada1da705c076da">anonymous{AArch64PreLegalizerCombiner.cpp}::applyPushAddSubExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#ad38e4c590871c5419bce5648dd9a79e4">getMidVTForTruncRightShiftCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae91b4ff9d9c084c672f78adb9ed4006a">llvm::LegalizerHelper::getVectorElementPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40558d23c7bc31dd0b4f1d6b00199487">llvm::LegalizerHelper::lowerEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a7287c6cc84f805db4ae46d581b4deecc">llvm::LegalizerHelper::lowerMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1a84546a5ff646ed05b5772e00084db6">llvm::LegalizerHelper::lowerSMULH_UMULH</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a04a0bfc5807bbedc770b17d4691e3142">llvm::LegalizerHelper::lowerThreewayCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae51c8cf31e26c03753e3f6acb6f48d56">llvm::LegalizerHelper::lowerTRUNC</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a51f93c65cadd67241250f97598ab1358">llvm::CombinerHelper::matchUDivByConst</a>.</p>

</div>
</div>

### changeElementType() {#a4f404daab6050b7a8e95bb247d4aefb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::changeElementType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NewEltTy)</td>
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

<p>If this type is a vector, return a vector with the same number of elements but the new element type.</p>


<p>Otherwise, return the new element type.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#a5360139c6b31d85cf3e29e2e6b7cf873">vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6cbfa42d7993571ddbfe46d0c37abafb">llvm::CombinerHelper::applyUseVectorTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#acc9d5942b26515a4412b230f2672e647">llvm::LegalizerHelper::bitcastShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#af1ee247ef88b451470210e27a2eefb44">llvm::LegalizeMutations::changeElementSizeTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a91e3c7e954902215b9f7b5fe585f38bd">llvm::LegalizeMutations::changeElementTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#aae4505920e551500fa2dff08f5d99f50">llvm::LegalizeMutations::changeElementTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aec28181fa8c84646c097212f19e379f1">llvm::AMDGPULegalizerInfo::legalizeExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad29042068469adc2859360985494dbb9">llvm::LegalizerHelper::lowerSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9e44e0e5bdc7526a1b299ae804752709">llvm::CombinerHelper::matchUseVectorTruncate</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### divide() {#af11a4c235044d52af7fbf840dec3f278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::divide (int Factor)</td>
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

<p>Return a type that is <span class="doxyComputerOutput">Factor</span> times smaller.</p>


<p>Reduces the number of elements if this is a vector, or the bitwidth for scalar/pointers. Does not attempt to handle cases that aren't evenly divisible.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="#a32472b5afd0ae6edb4a233a25056a6aa">getScalarSizeInBits</a>, <a href="#a3989251b1a714fc8296685f77eac6e87">isScalar</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a> and <a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>.</p>

</div>
</div>

### dump() {#adbe2b50c065f9de917bf34a1d573253b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LLT::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegentypes/lowleveltype-cpp">LowLevelType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>.</p>

</div>
</div>

### getAddressSpace() {#ac33fa4c8cfeb9287f51f95404a459de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LLT::getAddressSpace ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#acd23ed05c97e269d0d268636c7d6a6b7">isPointerOrPointerVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ab65adad01ce4004d6fe95c5b740190ab">llvm::AMDGPURegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a61f99fec329ba9cbb633996ee0452363">llvm::AMDGPURegisterBankInfo::getInstrMappingForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a941f1e23c69340ff634ea8bbb015e6d0">llvm::AMDGPURegisterBankInfo::getValueMappingForPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="#aa558a9e76bb04a92258576836a53592b">vector</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getElementCount() {#aa911a7e9e51b7ed20810fc819efe6a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::LLT::getElementCount ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a> and <a href="#a8028200b9efbd55fe7db4c69199893d2">isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a8bc641490449721bebf9b78d67c67f05">anonymous{AArch64PostLegalizerCombiner.cpp}::applyCombineMulCMLT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#acc9d5942b26515a4412b230f2672e647">llvm::LegalizerHelper::bitcastShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a2a5ba8caf566b63bea759399eb58927f">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a4fff4e593b92ebdfd3e0e394d52fa817">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a0ac1646365dca61b7727ec5291144c38">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a>, <a href="#a4f404daab6050b7a8e95bb247d4aefb2">changeElementType</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#ad1f97111fb4c021a0584599e68e93032">getMaskTypeFor</a>, <a href="#a71181d67d0bf68c3b8a535ec20463f90">getNumElements</a>, <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40558d23c7bc31dd0b4f1d6b00199487">llvm::LegalizerHelper::lowerEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9e44e0e5bdc7526a1b299ae804752709">llvm::CombinerHelper::matchUseVectorTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a91a10c5f7ca3b7a86768cb33f8955b5c">llvm::MachineIRBuilder::validateSelectOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adfd8cf26645132e9a23697eed85685e1">llvm::MachineIRBuilder::validateTruncExt</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a46d2e4271c38bdc43a3b072a050a1a0f">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyVectorElementMatch</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getElementType() {#aa24450f600cabd7212bd264a6dbc190c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::getElementType ()</td>
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

<p>Returns the vector's element type. Only valid for vector types.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac33fa4c8cfeb9287f51f95404a459de8">getAddressSpace</a>, <a href="#a32472b5afd0ae6edb4a233a25056a6aa">getScalarSizeInBits</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="#a7ff0361855acbbe71b15b8dc6003fbc5">pointer</a> and <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7b80b62a08d65dc70ac57954b7955ca0">llvm::LegalizeRuleSet::alignNumElementsTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a37f8fb6797142b53677bc4b59bf540">llvm::LegalizerHelper::bitcastInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a96b7ed72c9782cd69b2b9b341cf73112">llvm::MachineIRBuilder::buildBuildVectorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a43b43271e5bcbbc5cc620b4dfa94937a">llvm::MachineIRBuilder::buildShuffleSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aded2b440bea348970816da1ecd40f2c1">llvm::MachineIRBuilder::buildShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af1b182c58ed8ff82a5958635de5ccb15">llvm::MachineIRBuilder::buildStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a79837ead25e5a97d27a176df66809a5b">llvm::LegalizationArtifactCombiner::canFoldMergeOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ac56e6d7519b8f4f908174aa570bc5e61">llvm::LegalizeRuleSet::clampNumElements</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a7e87df9fdd3792e1b0c27ccf85466cfe">llvm::LegalityPredicates::elementTypeIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#aed4feaa9baf8df7fe949b9a5ce246646">elementTypeIsLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0935a3e7269909f95115fb8452b1058c">llvm::LegalizerHelper::equalizeVectorShuffleLengths</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1eac84349f5abc12d101036412730c5c">llvm::LegalizerHelper::fewerElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a2792f75920a3f0a318385a95f8a5702a">getLMUL1Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="#ae4165ca7bcbee300d5e9c065adcc1415">getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae91b4ff9d9c084c672f78adb9ed4006a">llvm::LegalizerHelper::getVectorElementPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-cpp/#a6828238e57f3a265b56fb009a227af4e">isRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aec28181fa8c84646c097212f19e379f1">llvm::AMDGPULegalizerInfo::legalizeExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6fb535803cbc7430528cdb19a157dd47">llvm::LegalizerHelper::lowerBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2fdcff9cc28cfffa71717b8d3c32c781">llvm::LegalizerHelper::lowerExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac29774c06843a7c183ae3fd328d43bc8">llvm::LegalizerHelper::lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa654694a53f814ff3cb1b2d04513da6e">llvm::CombinerHelper::matchBuildVectorIdentityFold</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a726cda62bb8fa499c865bc2d38b17265">anonymous{AArch64PostLegalizerLowering.cpp}::matchDupLane</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a12794dfd41dd116d9e295524d932f6c0">llvm::CombinerHelper::matchUnmergeValuesAnyExtBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a039bb9a10ad812f936f4325facc13ab3">llvm::LegalizeMutations::moreElementsToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getNumElements() {#a71181d67d0bf68c3b8a535ec20463f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::LLT::getNumElements ()</td>
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

<p>Returns the number of elements in a vector <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>.</p>


<p>Must only be called on vector types.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a8028200b9efbd55fe7db4c69199893d2">isScalable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a916e9619e70faa6bc1f4daf0c21292c5">llvm::reportInvalidSizeRequest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7b80b62a08d65dc70ac57954b7955ca0">llvm::LegalizeRuleSet::alignNumElementsTo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a0647544d97241e683cd0d0b7f3f51927">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6cbfa42d7993571ddbfe46d0c37abafb">llvm::CombinerHelper::applyUseVectorTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a37f8fb6797142b53677bc4b59bf540">llvm::LegalizerHelper::bitcastInsertVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a43b43271e5bcbbc5cc620b4dfa94937a">llvm::MachineIRBuilder::buildShuffleSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ac56e6d7519b8f4f908174aa570bc5e61">llvm::LegalizeRuleSet::clampNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab16bdfa03e042a77b677e032fa495959">clampVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa8fe481cda91a90b364e410009785003">llvm::LegalizerHelper::fewerElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae18cc835581a3f8882d7725891b67e4e">llvm::LegalizerHelper::fewerElementsVectorExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abb2458b37415bd3ed547b405507ebc6b">llvm::LegalizerHelper::fewerElementsVectorMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#addd0c111e12b07d02698a1fdcba59b0d">llvm::LegalizerHelper::fewerElementsVectorReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1eac84349f5abc12d101036412730c5c">llvm::LegalizerHelper::fewerElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aacaa5cd359fad565f73313045b5c83f0">hasSameNumEltsOnAllVectorOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aec28181fa8c84646c097212f19e379f1">llvm::AMDGPULegalizerInfo::legalizeExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2fdcff9cc28cfffa71717b8d3c32c781">llvm::LegalizerHelper::lowerExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae51c8cf31e26c03753e3f6acb6f48d56">llvm::LegalizerHelper::lowerTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac29774c06843a7c183ae3fd328d43bc8">llvm::LegalizerHelper::lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a7474d0e2d570539a3e93b86c67b1bae9">llvm::CombinerHelper::matchCombineShuffleConcat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a0e7fcc80fba58e49993976fe1ca63bb6">anonymous{AArch64PostLegalizerLowering.cpp}::matchEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8bd2bb9d716a15d8d914b0236e32e2ee">llvm::CombinerHelper::matchExtractAllEltsFromBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4f83785782b043b22a617554b65b5f0a">llvm::CombinerHelper::matchExtractVectorElement</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a89092e8630095ccf5b948def71d884f1">llvm::CombinerHelper::matchExtractVectorElementWithShuffleVector</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a8106e2049da0be5e2759557e0c7cd971">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a881fab40a57c999ccf31ebc208f8d859">llvm::CombinerHelper::matchInsertExtractVecEltOutOfBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4726b2a74fcb79e35ec78c54ec7aa8ee">llvm::CombinerHelper::matchInsertVectorElementOOB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a861321d522c24689003932ddbf9cdec1">anonymous{AArch64PostLegalizerCombiner.cpp}::matchOrToBSP</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a12794dfd41dd116d9e295524d932f6c0">llvm::CombinerHelper::matchUnmergeValuesAnyExtBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9e44e0e5bdc7526a1b299ae804752709">llvm::CombinerHelper::matchUseVectorTruncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a039bb9a10ad812f936f4325facc13ab3">llvm::LegalizeMutations::moreElementsToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1a3548d0921506d0cd736b7960c12485">llvm::LegalizerHelper::moreElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a8e4a67e6620c2b437e4b7a7707ac0914">numElementsNotEven</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a18f92b98415f16ce9abea7570e4f4df0">llvm::LegalityPredicates::numElementsNotPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a>.</p>

</div>
</div>

### getScalarSizeInBits() {#a32472b5afd0ae6edb4a233a25056a6aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LLT::getScalarSizeInBits ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Reference <a href="#acd23ed05c97e269d0d268636c7d6a6b7">isPointerOrPointerVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a8bc641490449721bebf9b78d67c67f05">anonymous{AArch64PostLegalizerCombiner.cpp}::applyCombineMulCMLT</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#acaf0ebafd584479c2c6a1a782ff149f9">llvm::CombinerHelper::applyCombineMulToShl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a0647544d97241e683cd0d0b7f3f51927">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6766b5f9c46b6dd7bb3b45857ec23a0f">llvm::CombinerHelper::applyFunnelShiftConstantModulo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#acc9d5942b26515a4412b230f2672e647">llvm::LegalizerHelper::bitcastShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a64309ae031097cf3cde8199ea5e0249a">llvm::CallLowering::IncomingValueHandler::buildExtensionHint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a4265ff404073d12b765bc9fee4e7f186">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a26edc3c3cae5a3f4d6ddd7f628b98c45">llvm::MachineIRBuilder::buildZExtInReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#af1ee247ef88b451470210e27a2eefb44">llvm::LegalizeMutations::changeElementSizeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d47901be0242bad9d2e085c3e9e73fe">llvm::ConstantFoldCastOp</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#ad38e4c590871c5419bce5648dd9a79e4">getMidVTForTruncRightShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a85287e14b9ed04197180e41b3bafcb24">llvm::SITargetLowering::isFPExtFoldable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa411af5653e9ed6cd4f664853b61bf0d">llvm::LegalizerHelper::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a21f36be0b82249def611e5709ff7dd15">llvm::LegalizerHelper::lowerAbsToAddXor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40558d23c7bc31dd0b4f1d6b00199487">llvm::LegalizerHelper::lowerEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1a84546a5ff646ed05b5772e00084db6">llvm::LegalizerHelper::lowerSMULH_UMULH</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae51c8cf31e26c03753e3f6acb6f48d56">llvm::LegalizerHelper::lowerTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aeb8af468cabe232d8d64944acf6930b7">llvm::CombinerHelper::matchCastOfInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a642669b9384277a3f5fc513928d6bee3">llvm::CombinerHelper::matchCombineAddP2IToPtrAdd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a35c23e5f8eea73c94cc6d8d70c9cec56">anonymous{AArch64PostLegalizerCombiner.cpp}::matchCombineMulCMLT</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ade65624657027af925c73882186d00ed">llvm::CombinerHelper::matchCombineZextTrunc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a045bd704a82578777117625df4358b32">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a8106e2049da0be5e2759557e0c7cd971">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a164cd36852df7d88fdbefc96c733d769">anonymous{AArch64PreLegalizerCombiner.cpp}::matchPushAddSubExt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5036ae118b8d8b9debc1c596eff93259">llvm::CombinerHelper::matchSextOfTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a21e1dc2aa53c4d2b688e9a1e5fe4a95b">llvm::CombinerHelper::matchShiftsTooBig</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a633b0486bab32c1b91cc923d82a72c2d">llvm::CombinerHelper::matchTruncateOfExt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a27942d2942b84e3453b75e3417def841">llvm::CombinerHelper::matchZextOfTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad66885c64b6a5ee434c62d1583de8589">llvm::LegalizerHelper::narrowScalarFLDEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a687c20941b83380477f4a3d95ad4e390">llvm::LegalizerHelper::narrowScalarFPTOI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2f99d62852a3fab708983d8ea2139755">llvm::LegalizerHelper::narrowScalarShift</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a87c5e76f97f435ea42bccaa6242aba92">llvm::LegalityPredicates::scalarOrEltNarrowerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a56e5ea86447c9f63597873fcdc69e631">llvm::LegalityPredicates::scalarOrEltSizeNotPow2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a0460dde35b7517637d8ac040900d42ba">llvm::LegalityPredicates::scalarOrEltWiderThan</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a5ccd1c1459e615587ee51ab55dea54bc">llvm::LegalizationArtifactCombiner::tryCombineSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3cff897f0ed479f872425600e0800701">llvm::LegalizationArtifactCombiner::tryCombineZExt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a60f1d0c2492ebc3d0e6eba6c6be95424">widenScalarLLTNextPow2</a>.</p>

</div>
</div>

### getScalarType() {#ae4165ca7bcbee300d5e9c065adcc1415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::getScalarType ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afb7bd8a1c290e9acba95192edd1be268">llvm::CombinerHelper::applyCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6cbfa42d7993571ddbfe46d0c37abafb">llvm::CombinerHelper::applyUseVectorTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#acc9d5942b26515a4412b230f2672e647">llvm::LegalizerHelper::bitcastShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af5d3388e53cb2767927dba7c18c64a00">llvm::CombinerHelper::buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="#adabd45e67a1847750a117317b5ef8f9f">changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abb2458b37415bd3ed547b405507ebc6b">llvm::LegalizerHelper::fewerElementsVectorMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abce993680c63fae7b6cc5814e9b07826">llvm::LegalizerHelper::fewerElementsVectorUnmergeValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#ad4d564b29ec78229d8d9ab0970db529d">isCopyCompatibleType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abac7927a227a6c370e26ee82af77567d">llvm::LegalizerHelper::lowerShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae88fdd4a40851c70c1f04282174034c2">llvm::CombinerHelper::matchCastOfBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9e44e0e5bdc7526a1b299ae804752709">llvm::CombinerHelper::matchUseVectorTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getSizeInBits() {#a956ffd0de93798f523683b447646dd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::LLT::getSizeInBits ()</td>
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

<p>Returns the total size of the type. Must only be called on sized types.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="#a32472b5afd0ae6edb4a233a25056a6aa">getScalarSizeInBits</a>, <a href="#a9d825f5954d7bd527aea490668c624c6">isPointer</a> and <a href="#a3989251b1a714fc8296685f77eac6e87">isScalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a00301689820a26a9f3b438f6dece6ef0">llvm::CombinerHelper::applyCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afe9d6cb97689cb5efb1a5b8f9dc68ea0">llvm::CombinerHelper::applyCombineUnmergeZExtToZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa3bd6f239db6919e67236164cd0d840f">llvm::CombinerHelper::applyExtractVecEltBuildVec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#adf82bf97d32fede84099257eb720a1a2">anonymous{AArch64PostLegalizerLowering.cpp}::applyFullRev</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6766b5f9c46b6dd7bb3b45857ec23a0f">llvm::CombinerHelper::applyFunnelShiftConstantModulo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0494e300dac616c8ca39b2dbc8b1276c">llvm::AMDGPURegisterBankInfo::applyMappingDynStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a1cdf9ea1d249387f26e37569d6cdb088">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6c12dbad109a5d725ce01a9a8363f948">llvm::LegalizerHelper::bitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a37f8fb6797142b53677bc4b59bf540">llvm::LegalizerHelper::bitcastInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad5c38c10f947e4226f85aade1ebf57f1">llvm::AMDGPULegalizerInfo::buildAbsGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2b99673a7e084ea8e75699f04b5f683a">buildBitFieldInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a2f52fec4aa17c3066db14a8d4717469d">llvm::MachineIRBuilder::buildExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a010032df630a417383fa44deee43ac0c">llvm::MachineIRBuilder::buildLoadFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af6aed1d3b2cf7133b73cf8bfa5122186">llvm::MachineIRBuilder::buildMaskLowPtrBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6006bd8b7a7155240e3a11c12d104c50">llvm::AMDGPULegalizerInfo::buildPCRelGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af1b182c58ed8ff82a5958635de5ccb15">llvm::MachineIRBuilder::buildStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeec9f9188630ac797d11be83445197b0">llvm::MachineIRBuilder::buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ac3c19ecc16565c150796b834a8a63963">llvm::MachineIRBuilder::buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a79837ead25e5a97d27a176df66809a5b">llvm::LegalizationArtifactCombiner::canFoldMergeOpcode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#af7d81ffe276a47a4226c0f9ee75575f9">anonymous{CombinerHelper.cpp}::ChoosePreferredUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab16bdfa03e042a77b677e032fa495959">clampVectorIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a2a681b9303b51d21a9392975a6cd422c">llvm::CallLowering::ValueHandler::copyArgumentMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#aed4feaa9baf8df7fe949b9a5ce246646">elementTypeIsLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a78e425f7e61cda2ed4db6054c39beb18">llvm::LegalizerHelper::fewerElementsBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abb2458b37415bd3ed547b405507ebc6b">llvm::LegalizerHelper::fewerElementsVectorMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abce993680c63fae7b6cc5814e9b07826">llvm::LegalizerHelper::fewerElementsVectorUnmergeValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a1476a89aa41e0a21b60bfc63a292f2c3">findGISelOptimalMemOpLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a5f65ab13a2645935d21a119b722a55a1">getBitcastWiderVectorElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab95d4485884d2e093f534590f24cfe0d">llvm::LegalizerHelper::getDynStackAllocTargetPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad7c01a9166d49578fc9cb3162a87f396">llvm::AMDGPULegalizerInfo::getImplicitArgPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ab65adad01ce4004d6fe95c5b740190ab">llvm::AMDGPURegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#af59ec25334715d44d5eecd8568b29e36">llvm::ARMRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a7394a9cae0a48251b9ccaca67393ef89">llvm::MipsRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#ab84d39303f3dab27a9cf03cd488b23c6">llvm::X86RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a61f99fec329ba9cbb633996ee0452363">llvm::AMDGPURegisterBankInfo::getInstrMappingForLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a2792f75920a3f0a318385a95f8a5702a">getLMUL1Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliselutils-cpp/#a50a705446015e4b43ea1f59a13eba3b8">getReadAnyLaneSplitTy</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697cb1debe6ad1be7e59990072185844">llvm::SITargetLowering::getRegisterByName</a>, <a href="#ae456a811703836ee5d9e32c3e51a15b6">getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a941f1e23c69340ff634ea8bbb015e6d0">llvm::AMDGPURegisterBankInfo::getValueMappingForPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae91b4ff9d9c084c672f78adb9ed4006a">llvm::LegalizerHelper::getVectorElementPointer</a>, <a href="#a8b8f5d788ec31cd57f429ce38b5e3bb7">isByteSized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#ad4d564b29ec78229d8d9ab0970db529d">isCopyCompatibleType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-cpp/#a6828238e57f3a265b56fb009a227af4e">isRegisterType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a31648fb7411d04ec274b46d8dd635564">isRegisterVectorElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0dbe048033c8b5adaf283b8fe7de3ba1">isSmallOddVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a3d552c29a563f3462800870d14e72b0f">isWideVec16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a40f12f2bde2de188bff061f11bcd976c">llvm::AMDGPULegalizerInfo::legalizeCTLZ_CTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aec28181fa8c84646c097212f19e379f1">llvm::AMDGPULegalizerInfo::legalizeExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40558d23c7bc31dd0b4f1d6b00199487">llvm::LegalizerHelper::lowerEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6abe0f5db91bf445b3962dba969c5c7f">llvm::LegalizerHelper::lowerUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9511578c9aa47dc8c5d7df3e9b623be3">llvm::LegalizerHelper::lowerVAArg</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac29774c06843a7c183ae3fd328d43bc8">llvm::LegalizerHelper::lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8e25418b93784160f4a660950f5fa806">llvm::LegalizerHelper::lowerVectorReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa654694a53f814ff3cb1b2d04513da6e">llvm::CombinerHelper::matchBuildVectorIdentityFold</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab5ece2e19fefdc8f1112b05d6274e649">llvm::CombinerHelper::matchCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afc1c60085dd818c0586c87f44db3d10a">llvm::CombinerHelper::matchCombineUnmergeMergeToPlainValues</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a19db4f1b27ef7d29e4c77f6f7dd0ec5d">llvm::CombinerHelper::matchCombineUnmergeZExtToZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4cc9ea97355c96a953b9a6fc5ce2fcc2">llvm::CombinerHelper::matchConstantLargerBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a726cda62bb8fa499c865bc2d38b17265">anonymous{AArch64PostLegalizerLowering.cpp}::matchDupLane</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a74c47491ee867baa1f14586d759342ee">anonymous{AArch64PostLegalizerCombiner.cpp}::matchExtractVecEltPairwiseAdd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#afa0ed64c2bf09a336fb47c9488d2880b">anonymous{AArch64PreLegalizerCombiner.cpp}::matchICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a79ff9815398a2c3331b42832035f21c6">llvm::CombinerHelper::matchICmpToLHSKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a59e682863250eb07290a348d548eee0d">llvm::CombinerHelper::matchNarrowBinopFeedingAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8f5dd5583d12f1c7dcf63b86ff444394">llvm::CombinerHelper::matchSextInRegOfLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a350580c34bfdfd93dbeb51e3f2b44fa4">llvm::CombinerHelper::matchTruncLshrBuildVectorFold</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#acd56c0d001ca90095d61c52099f90cd3">llvm::LegalizeRuleSet::maxScalarIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af0cb74dd5e94daaea299005867eac63d">llvm::LegalizeRuleSet::minScalarIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad64f039266036a2ac4d704000928d65b">moreEltsToNext32Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae25927a69e107ef1477822b884ca034b">llvm::LegalizerHelper::narrowScalarCTLZ</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a048378560a1f3ddd48ddf9c60ae488f5">llvm::LegalizerHelper::narrowScalarCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2db1bc1a16d89298b92a13857146e28d">llvm::LegalizerHelper::narrowScalarCTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaec7c9b0ed49d3297c833d8d9def42c0">llvm::LegalizerHelper::narrowScalarExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad43f277d8baa4b080bfd1beed8542bd6">llvm::LegalizerHelper::narrowScalarInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0c0426a2303d102874f24e00608e3de4">llvm::LegalizerHelper::narrowScalarMul</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ab7155d5feabf02f01c4d3b7d9c422">llvm::LegalizerHelper::narrowScalarShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#aff9e886f18a84258e4f794e31aad0bd9">llvm::LegalityPredicates::scalarNarrowerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#af80fd220e67295d05887d3f948695ab2">llvm::LegalityPredicates::scalarWiderThan</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a18c672925e05a23b72838be961003fc7">selectFPConvOpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#abd86d813757b6a6e4b94c03a856002a4">setRegsToType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2d595a51e66614b8adb83efbc8114401">shouldWidenLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#adec4750bfce575e00982f15e55ee044f">llvm::LegalityPredicates::sizeNotMultipleOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ac444cce31f4cc1906cea922fc1f208e2">llvm::LegalityPredicates::sizeNotPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a909ca36ce602ebf9224694d163064009">llvm::AMDGPURegisterBankInfo::split64BitValueForMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#ab4c2bc39e4119d3c2098986cfd7be179">splitUnequalType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#af4696dcc1ada21996da960c711f26ee1">llvm::LegalizationArtifactCombiner::tryCombineAnyExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#aaaa5a895e6a8003daae912a9bf636040">llvm::LegalizationArtifactCombiner::tryCombineExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#aba0755f8db842bb12cb51ef2f3977bac">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineMergeLike</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a5ccd1c1459e615587ee51ab55dea54bc">llvm::LegalizationArtifactCombiner::tryCombineSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a525b60970cc862aa413d171d805704d4">llvm::LegalizationArtifactCombiner::tryCombineTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a90cc54876f57e2f6ee698215c7550ba7">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3cff897f0ed479f872425600e0800701">llvm::LegalizationArtifactCombiner::tryCombineZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adfd8cf26645132e9a23697eed85685e1">llvm::MachineIRBuilder::validateTruncExt</a>, <a href="#aa558a9e76bb04a92258576836a53592b">vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a144b2ed41ce4f22842225b0b1b117a58">vectorSmallerThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2d0beabfcf00e6fd23c97eff8ee516a6">vectorWiderThan</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#af1deb020986939504194841306a9da79">widen96To128</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a>.</p>

</div>
</div>

### getSizeInBytes() {#ae456a811703836ee5d9e32c3e51a15b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::LLT::getSizeInBytes ()</td>
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

<p>Returns the total size of the type in bytes, i.e.</p>


<p>number of whole bytes needed to represent the size in bits. Must only be called on sized types.</p>


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a475797835e85ab2eee4c3364cfc79a2f">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a1476a89aa41e0a21b60bfc63a292f2c3">findGISelOptimalMemOpLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a25a5ee99366e3b0d347b60918e6d51a6">getOutlineAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2fdcff9cc28cfffa71717b8d3c32c781">llvm::LegalizerHelper::lowerExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ad00560f7fdae2f561cc4bf8d7b70b94a">anonymous{AArch64PostLegalizerLowering.cpp}::matchUnmergeExtToUnmerge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a66c37e901bc47ad309a6f13c2edeecd4">llvm::LegalityPredicates::memSizeNotByteSizePow2</a>.</p>

</div>
</div>

### getUniqueRAWLLTData() {#a831ad5290836e63683b75d99679f72cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLT::getUniqueRAWLLTData ()</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### isByteSized() {#a8b8f5d788ec31cd57f429ce38b5e3bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isByteSized ()</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a1618ca92d9fa0b2b577698fb006b84cc">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a45aaa22f9450b9e89c1008c90e20659c">llvm::LegalizerInfo::getExtOpcodeForWideningConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2fdcff9cc28cfffa71717b8d3c32c781">llvm::LegalizerHelper::lowerExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a66c37e901bc47ad309a6f13c2edeecd4">llvm::LegalityPredicates::memSizeNotByteSizePow2</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>.</p>

</div>
</div>

### isFixedVector() {#ad1db89614d919436714d099c99ff12a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isFixedVector ()</td>
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

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is a fixed vector.</p>


<p>Returns false otherwise, even if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is not a vector type.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a8028200b9efbd55fe7db4c69199893d2">isScalable</a> and <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7b80b62a08d65dc70ac57954b7955ca0">llvm::LegalizeRuleSet::alignNumElementsTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4f83785782b043b22a617554b65b5f0a">llvm::CombinerHelper::matchExtractVectorElement</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4726b2a74fcb79e35ec78c54ec7aa8ee">llvm::CombinerHelper::matchInsertVectorElementOOB</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a12794dfd41dd116d9e295524d932f6c0">llvm::CombinerHelper::matchUnmergeValuesAnyExtBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a18f92b98415f16ce9abea7570e4f4df0">llvm::LegalityPredicates::numElementsNotPow2</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a>.</p>

</div>
</div>

### isPointer() {#a9d825f5954d7bd527aea490668c624c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isPointer ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Reference <a href="#a69fb30748f1b3e8a0affd486a9f59f6d">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a497e8884b8ae421c7dadff0f0eea5e3e">llvm::MachineIRBuilder::buildAtomicRMW</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a7394a9cae0a48251b9ccaca67393ef89">llvm::MipsRegisterBankInfo::getInstrMapping</a>, <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#ad4d564b29ec78229d8d9ab0970db529d">isCopyCompatibleType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aec28181fa8c84646c097212f19e379f1">llvm::AMDGPULegalizerInfo::legalizeExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6abe0f5db91bf445b3962dba969c5c7f">llvm::LegalizerHelper::lowerUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9098323777f98b3dd53bef412554961c">llvm::CombinerHelper::matchSelectIMinMax</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a91a10c5f7ca3b7a86768cb33f8955b5c">llvm::MachineIRBuilder::validateSelectOp</a>, <a href="#aa558a9e76bb04a92258576836a53592b">vector</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isPointerOrPointerVector() {#acd23ed05c97e269d0d268636c7d6a6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isPointerOrPointerVector ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Reference <a href="#a69fb30748f1b3e8a0affd486a9f59f6d">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a3493ece271aff0f2c3d162494e3fcc81">llvm::MachineIRBuilder::buildCast</a>, <a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a>, <a href="#ac33fa4c8cfeb9287f51f95404a459de8">getAddressSpace</a>, <a href="#a32472b5afd0ae6edb4a233a25056a6aa">getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isPointerVector() {#a55ca901a46a6561125ef38f6c33c2700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isPointerVector ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Reference <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isScalable() {#a8028200b9efbd55fe7db4c69199893d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isScalable ()</td>
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

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is a scalable vector.</p>


<p>Must only be called on vector types.</p>


<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>.</p>


<p>Referenced by <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="#a71181d67d0bf68c3b8a535ec20463f90">getNumElements</a>, <a href="#ad1db89614d919436714d099c99ff12a0">isFixedVector</a>, <a href="#a3016e0f01ad96a198f81f74397b1c0e6">isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isScalableVector() {#a3016e0f01ad96a198f81f74397b1c0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isScalableVector ()</td>
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

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is a scalable vector.</p>


<p>Returns false otherwise, even if the <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> is not a vector type.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a8028200b9efbd55fe7db4c69199893d2">isScalable</a> and <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a45e6e22e05efa275135c8ae32f60da40">buildDefaultVLOps</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ac56e6d7519b8f4f908174aa570bc5e61">llvm::LegalizeRuleSet::clampNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a881fab40a57c999ccf31ebc208f8d859">llvm::CombinerHelper::matchInsertExtractVecEltOutOfBounds</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isScalar() {#a3989251b1a714fc8296685f77eac6e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isScalar ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7adc16cc9bc8db5fd3c8a6798a846ab0">llvm::LegalizeRuleSet::clampScalar</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#addd0c111e12b07d02698a1fdcba59b0d">llvm::LegalizerHelper::fewerElementsVectorReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab6561daa27ec7fcc5335edb91ddae768">llvm::LegalizerHelper::fewerElementsVectorSeqReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a7394a9cae0a48251b9ccaca67393ef89">llvm::MipsRegisterBankInfo::getInstrMapping</a>, <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#ad4d564b29ec78229d8d9ab0970db529d">isCopyCompatibleType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab5ece2e19fefdc8f1112b05d6274e649">llvm::CombinerHelper::matchCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#afa0ed64c2bf09a336fb47c9488d2880b">anonymous{AArch64PreLegalizerCombiner.cpp}::matchICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a59e682863250eb07290a348d548eee0d">llvm::CombinerHelper::matchNarrowBinopFeedingAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#acd56c0d001ca90095d61c52099f90cd3">llvm::LegalizeRuleSet::maxScalarIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af0cb74dd5e94daaea299005867eac63d">llvm::LegalizeRuleSet::minScalarIf</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#aff9e886f18a84258e4f794e31aad0bd9">llvm::LegalityPredicates::scalarNarrowerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#af80fd220e67295d05887d3f948695ab2">llvm::LegalityPredicates::scalarWiderThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a18c672925e05a23b72838be961003fc7">selectFPConvOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#adec4750bfce575e00982f15e55ee044f">llvm::LegalityPredicates::sizeNotMultipleOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ac444cce31f4cc1906cea922fc1f208e2">llvm::LegalityPredicates::sizeNotPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a525b60970cc862aa413d171d805704d4">llvm::LegalizationArtifactCombiner::tryCombineTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9856f0ee59ced7e9724315502ea9a380">llvm::MachineIRBuilder::validateBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a91a10c5f7ca3b7a86768cb33f8955b5c">llvm::MachineIRBuilder::validateSelectOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9c8154c310c33839a5d134b63c4d9cb6">llvm::MachineIRBuilder::validateShiftOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adfd8cf26645132e9a23697eed85685e1">llvm::MachineIRBuilder::validateTruncExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae63e90ab103cd2159b9431b5ed5e9a53">llvm::MachineIRBuilder::validateUnaryOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a60f1d0c2492ebc3d0e6eba6c6be95424">widenScalarLLTNextPow2</a>.</p>

</div>
</div>

### isToken() {#a7a5056b68b503b3a05a4fdda5c51110d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isToken ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### isValid() {#a69fb30748f1b3e8a0affd486a9f59f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isValid ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adbf5d6125fa84e067907320d93e9fab5">llvm::MachineIRBuilder::buildAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acc22ffc46525708d66c036f878572523">llvm::MachineIRBuilder::buildAtomicCmpXchgWithSuccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a2f52fec4aa17c3066db14a8d4717469d">llvm::MachineIRBuilder::buildExtract</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#af7d81ffe276a47a4226c0f9ee75575f9">anonymous{CombinerHelper.cpp}::ChoosePreferredUse</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#acd28b31b311bb88a92825ed630dd4269">llvm::MachineRegisterInfo::constrainRegAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02134e88cd18139c71d9274c7d287ac3">llvm::getFunctionLiveInPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9dbc9a748353035febcc488160ba9956">llvm::MachineInstr::getTypeToPrint</a>, <a href="#a9d825f5954d7bd527aea490668c624c6">isPointer</a>, <a href="#acd23ed05c97e269d0d268636c7d6a6b7">isPointerOrPointerVector</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### isVector() {#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLT::isVector ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>Reference <a href="#a69fb30748f1b3e8a0affd486a9f59f6d">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a37f8fb6797142b53677bc4b59bf540">llvm::LegalizerHelper::bitcastInsertVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aded2b440bea348970816da1ecd40f2c1">llvm::MachineIRBuilder::buildShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a79837ead25e5a97d27a176df66809a5b">llvm::LegalizationArtifactCombiner::canFoldMergeOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a4fff4e593b92ebdfd3e0e394d52fa817">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a0ac1646365dca61b7727ec5291144c38">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a>, <a href="#a4f404daab6050b7a8e95bb247d4aefb2">changeElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#a7e87df9fdd3792e1b0c27ccf85466cfe">llvm::LegalityPredicates::elementTypeIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#aed4feaa9baf8df7fe949b9a5ce246646">elementTypeIsLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa8fe481cda91a90b364e410009785003">llvm::LegalizerHelper::fewerElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae18cc835581a3f8882d7725891b67e4e">llvm::LegalizerHelper::fewerElementsVectorExtractInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abb2458b37415bd3ed547b405507ebc6b">llvm::LegalizerHelper::fewerElementsVectorMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#addd0c111e12b07d02698a1fdcba59b0d">llvm::LegalizerHelper::fewerElementsVectorReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1eac84349f5abc12d101036412730c5c">llvm::LegalizerHelper::fewerElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abce993680c63fae7b6cc5814e9b07826">llvm::LegalizerHelper::fewerElementsVectorUnmergeValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a1476a89aa41e0a21b60bfc63a292f2c3">findGISelOptimalMemOpLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a7394a9cae0a48251b9ccaca67393ef89">llvm::MipsRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#ad1f97111fb4c021a0584599e68e93032">getMaskTypeFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a25a5ee99366e3b0d347b60918e6d51a6">getOutlineAtomicLibcall</a>, <a href="#ae4165ca7bcbee300d5e9c065adcc1415">getScalarType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a7917a4a285e36269f30a2a1de721136e">anonymous{AArch64PostLegalizerLowering.cpp}::getVectorFCMP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aacaa5cd359fad565f73313045b5c83f0">hasSameNumEltsOnAllVectorOperands</a>, <a href="#ad1db89614d919436714d099c99ff12a0">isFixedVector</a>, <a href="#a55ca901a46a6561125ef38f6c33c2700">isPointerVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-cpp/#a6828238e57f3a265b56fb009a227af4e">isRegisterType</a>, <a href="#a8028200b9efbd55fe7db4c69199893d2">isScalable</a>, <a href="#a3016e0f01ad96a198f81f74397b1c0e6">isScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a04a0bfc5807bbedc770b17d4691e3142">llvm::LegalizerHelper::lowerThreewayCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae51c8cf31e26c03753e3f6acb6f48d56">llvm::LegalizerHelper::lowerTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a19db4f1b27ef7d29e4c77f6f7dd0ec5d">llvm::CombinerHelper::matchCombineUnmergeZExtToZExt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a6288bdc9c0864757a314ab233c31590d">anonymous{AArch64PostLegalizerLowering.cpp}::matchExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a89092e8630095ccf5b948def71d884f1">llvm::CombinerHelper::matchExtractVectorElementWithShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a79ff9815398a2c3331b42832035f21c6">llvm::CombinerHelper::matchICmpToLHSKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a661e6393009add33162594f630c4c775">anonymous{AArch64PostLegalizerLowering.cpp}::matchLowerVectorFCMP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a861321d522c24689003932ddbf9cdec1">anonymous{AArch64PostLegalizerCombiner.cpp}::matchOrToBSP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a164cd36852df7d88fdbefc96c733d769">anonymous{AArch64PreLegalizerCombiner.cpp}::matchPushAddSubExt</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8f5dd5583d12f1c7dcf63b86ff444394">llvm::CombinerHelper::matchSextInRegOfLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adc129334a6d3d83eb003dd1a49540f80">llvm::CombinerHelper::matchSuboCarryOut</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a51f93c65cadd67241250f97598ab1358">llvm::CombinerHelper::matchUDivByConst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ad00560f7fdae2f561cc4bf8d7b70b94a">anonymous{AArch64PostLegalizerLowering.cpp}::matchUnmergeExtToUnmerge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ad46be7825f60fea273692628c6e569b5">anonymous{AArch64PostLegalizerLowering.cpp}::matchVectorSextInReg</a>, <a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab483400178810f8c04f3ee4ebe5db4c9">llvm::LegalizerHelper::narrowScalarExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6f143ae3ebc33b4f3f97e486bf7112">llvm::LegalizerHelper::narrowScalarSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2f99d62852a3fab708983d8ea2139755">llvm::LegalizerHelper::narrowScalarShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a8e4a67e6620c2b437e4b7a7707ac0914">numElementsNotEven</a>, <a href="#a1872b438567a6c68dcfb0bf0bfc18631">print</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#aba0755f8db842bb12cb51ef2f3977bac">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineMergeLike</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a9ef6fa1f344222ac170e33582b82c482">llvm::LegalizationArtifactCombiner::tryCombineUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9856f0ee59ced7e9724315502ea9a380">llvm::MachineIRBuilder::validateBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a91a10c5f7ca3b7a86768cb33f8955b5c">llvm::MachineIRBuilder::validateSelectOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9c8154c310c33839a5d134b63c4d9cb6">llvm::MachineIRBuilder::validateShiftOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adfd8cf26645132e9a23697eed85685e1">llvm::MachineIRBuilder::validateTruncExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae63e90ab103cd2159b9431b5ed5e9a53">llvm::MachineIRBuilder::validateUnaryOp</a>, <a href="#aa558a9e76bb04a92258576836a53592b">vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a144b2ed41ce4f22842225b0b1b117a58">vectorSmallerThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2d0beabfcf00e6fd23c97eff8ee516a6">vectorWiderThan</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a46d2e4271c38bdc43a3b072a050a1a0f">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyVectorElementMatch</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### multiplyElements() {#a52cd802a268f6ed25d878c96d8b16247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LLT::multiplyElements (int Factor)</td>
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

<p>Produce a vector type that is <span class="doxyComputerOutput">Factor</span> times bigger, preserving the element type.</p>


<p>For a scalar or pointer, this will produce a new vector with <span class="doxyComputerOutput">Factor</span> elements.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#acd1eca3232b7b3072543294cd2377a37">fixed_vector</a>, <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a>.</p>

</div>
</div>

### print() {#a1872b438567a6c68dcfb0bf0bfc18631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLT::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegentypes/lowleveltype-cpp">LowLevelType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac33fa4c8cfeb9287f51f95404a459de8">getAddressSpace</a>, <a href="#aa911a7e9e51b7ed20810fc819efe6a26">getElementCount</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="#a32472b5afd0ae6edb4a233a25056a6aa">getScalarSizeInBits</a>, <a href="#a9d825f5954d7bd527aea490668c624c6">isPointer</a>, <a href="#a3989251b1a714fc8296685f77eac6e87">isScalar</a>, <a href="#a69fb30748f1b3e8a0affd486a9f59f6d">isValid</a> and <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a>.</p>


<p>Referenced by <a href="#adbe2b50c065f9de917bf34a1d573253b">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getFieldValue() {#a85735a256dd26b96c54f8ea86cb19692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLT::getFieldValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BitFieldInfo FieldInfo)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### init() {#a40bdd7055d7318dd851ac1510b66bc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLT::init (bool IsPointer, bool IsVector, bool IsScalar, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, uint64_t SizeInBits, unsigned AddressSpace)</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsPointer {#a36179e74cc695458feb8d53a51617f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLT::IsPointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### IsScalar {#a39ea5a7549220aedf9c4f547e0c98e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLT::IsScalar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<ul class="doxyList ">
<li>Vector-of-pointer (isPointer == 1 &amp;&amp; isVector == 1): NumElements: 16; SizeOfElement: 16; <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dc">AddressSpace</a>: 24; Scalable: 1;</li>
</ul>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### IsVector {#abd7884b54043ff7c50d8f80148f9ff61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLT::IsVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### RawData {#a3e4fe0afca29f2753eed6830601b71fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLT::RawData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fixed\_vector() {#acd1eca3232b7b3072543294cd2377a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::fixed_vector (unsigned NumElements, unsigned ScalarSizeInBits)</td>
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

<p>Get a low-level fixed-width vector of some number of elements and element width.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a7b80b62a08d65dc70ac57954b7955ca0">llvm::LegalizeRuleSet::alignNumElementsTo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8ecd479d22b89a38549d035861ce1d84">llvm::AArch64TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a0647544d97241e683cd0d0b7f3f51927">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3da19f78bfc264962a18568ea4b8d6c7">llvm::LegalizeRuleSet::clampMinNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0935a3e7269909f95115fb8452b1058c">llvm::LegalizerHelper::equalizeVectorShuffleLengths</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a78e425f7e61cda2ed4db6054c39beb18">llvm::LegalizerHelper::fewerElementsBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4bf8d79fb617413b09980966a60e5a">llvm::generateBuiltinVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a64443e60c47deb77ad3bb491d2da3c5f">getBufferRsrcRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab72c286743e675ffbe81f7c9e9771fa5">llvm::AArch64TargetLowering::getOptimalMemOpLLT</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a9ccdd07da05e067c1e31356005bb39b0">llvm::AMDGPUFunctionArgInfo::getPreloadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliselutils-cpp/#a50a705446015e4b43ea1f59a13eba3b8">getReadAnyLaneSplitTy</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a755cbbd3d8b7e1f3e6659ede9cd88f94">llvm::AMDGPUCallLowering::handleImplicitCallArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a44896316bcf65958ba14a3afa8fa193f">isExtractHiElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a22a60a10a1cda01d7cef79f4634984dc">llvm::AMDGPULegalizerInfo::legalizeAtomicCmpXChg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4117d1ecf36af9158c825fb376c4082e">llvm::AMDGPULegalizerInfo::legalizeBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#a5430de9bfca0f2700d4afb0121e156fe">LLTToBId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6fb535803cbc7430528cdb19a157dd47">llvm::LegalizerHelper::lowerBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a35c23e5f8eea73c94cc6d8d70c9cec56">anonymous{AArch64PostLegalizerCombiner.cpp}::matchCombineMulCMLT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a6288bdc9c0864757a314ab233c31590d">anonymous{AArch64PostLegalizerLowering.cpp}::matchExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a4b2db808be70ea68e0f121c1942982a9">moreElementsToNextExistingRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a039bb9a10ad812f936f4325facc13ab3">llvm::LegalizeMutations::moreElementsToNextPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad64f039266036a2ac4d704000928d65b">moreEltsToNext32Bit</a>, <a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0e3fd79bb281f248eefd08814023d8c8">oneMoreElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#af1deb020986939504194841306a9da79">widen96To128</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### fixed\_vector() {#aac9e947d00e373eba50e79fd0da66792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::fixed_vector (unsigned NumElements, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ScalarTy)</td>
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

<p>Get a low-level fixed-width vector of some number of elements and element type.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a>.</p>

</div>
</div>

### float16() {#abb1f260fc4da86ce2e93fa8628aa0b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::float16 ()</td>
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

<p>Get a 16-bit IEEE half value.</p>


<p>TODO: Add IEEE semantics to type - This currently returns a simple <span class="doxyComputerOutput">scalar(16)</span>.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4774d239d20e55380840e775aed66efc">llvm::AMDGPULegalizerInfo::legalizeFMad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#abf712aff736a372430ea6ea027fe32e5">llvm::AMDGPULegalizerInfo::legalizeFPow</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>.</p>

</div>
</div>

### float32() {#aee6abb440f4fe52097595d934283f0a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::float32 ()</td>
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

<p>Get a 32-bit IEEE float value.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4774d239d20e55380840e775aed66efc">llvm::AMDGPULegalizerInfo::legalizeFMad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#abf712aff736a372430ea6ea027fe32e5">llvm::AMDGPULegalizerInfo::legalizeFPow</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>.</p>

</div>
</div>

### float64() {#a0631408a6598e34659cc5495c3ec090b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::float64 ()</td>
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

<p>Get a 64-bit IEEE double value.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44186e632d4bab1d35012ed738a23870">llvm::AMDGPULegalizerInfo::legalizeFFloor</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>.</p>

</div>
</div>

### pointer() {#a7ff0361855acbbe71b15b8dc6003fbc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::pointer (unsigned AddressSpace, unsigned SizeInBits)</td>
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

<p>Get a low-level pointer in the given address space.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a0f19540db0c8b48eebad9481053dc719">addCallTargetOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#af375ca05eecaafa17b7a92ec352537d4">llvm::AMDGPU::RegBankLegalizeHelper::applyMappingPHI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6006bd8b7a7155240e3a11c12d104c50">llvm::AMDGPULegalizerInfo::buildPCRelGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a576b964fe2d7d8750601681e04f05a9c">llvm::LegalizerHelper::createStackTemporary</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#adeb18e3c3ca254b1eac668a91c0a18e8">llvm::AMDGPULegalizerInfo::getKernargParameterPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#a90aa66fae0afdb22ada20af8c400e9d4">getLeaOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd34773dd33963769279868ab39d5fdc">llvm::getLLTForType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a9ccdd07da05e067c1e31356005bb39b0">llvm::AMDGPUFunctionArgInfo::getPreloadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2fd97f50411bc650c7f9f6e3118147f4">llvm::AMDGPULegalizerInfo::getSegmentAperture</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a18bab7a0c4783a00f51d05cae58ee7da">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a84d626ad52140616b26b997d67d2c7b1">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#ab81aa7a77f61bbabb3f265712cd8ad53">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a1de30cc152058819888b9d02619f16ac">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a2cc4d384d22ddae8f252b9cbb9313949">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a0256194175f52db6cc06eb379bd412dc">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler/#a1ebcdacc79bcbbbb515e69090df3ea18">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a059b61bb0bab07b3cf7da0e06f5893dd">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a202a7e2a16e7921c97c6767cb68bdae9">M68kOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a5176666164b27a32c0b6093b921cde29">llvm::CallLowering::ValueHandler::getStackValueStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#aabf8e09177e2ae41bc06eb1f2be342e8">llvm::MipsLegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af9de933caeeaebd4387c7c62f02a3bbd">llvm::AMDGPULegalizerInfo::legalizeTrapHsaQueuePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#a5430de9bfca0f2700d4afb0121e156fe">LLTToBId</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a4119a7f5d262af0d89332b5c2d30abbc">llvm::AMDGPUCallLowering::lowerFormalArgumentsKernel</a>, <a href="/web-llvm/docs/api/structs/llvm/m68klegalizerinfo/#a77a1ff087fb51dfd9397ffc153578c43">llvm::M68kLegalizerInfo::M68kLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstructionselector-cpp-/ppcinstructionselector/#a051c8a2638fc5f95b9ccd5e82a7a8559">anonymous{PPCInstructionSelector.cpp}::PPCInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### scalable\_vector() {#a3c8d482078435a16e34c2cc13caa6f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::scalable_vector (unsigned MinNumElements, unsigned ScalarSizeInBits)</td>
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

<p>Get a low-level scalable vector of some number of elements and element width.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a1bddc4949ab247dd1474f79b9bc6e34e">llvm::ElementCount::getScalable</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a2792f75920a3f0a318385a95f8a5702a">getLMUL1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#acbb662ad1799057d6bea1501cbaf5d46">llvm::MachineFunction::getMachineMemOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a>.</p>

</div>
</div>

### scalable\_vector() {#ae614d7a67bd01700a068c8e4eb6e2ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::scalable_vector (unsigned MinNumElements, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ScalarTy)</td>
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

<p>Get a low-level scalable vector of some number of elements and element type.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a1bddc4949ab247dd1474f79b9bc6e34e">llvm::ElementCount::getScalable</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a>.</p>

</div>
</div>

### scalar() {#a67021459c7ef8f9a634b4eac7ffd0f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::scalar (unsigned SizeInBits)</td>
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

<p>Get a low-level scalar or aggregate "bag of bits".</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#add01b669c3b94782f5e3a2babaa12f50">llvm::SITargetLowering::allocateSpecialEntryInputVGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregisterbankinfo-cpp-/applyregbankmapping/#aeef19e805c256d7c5a9135ebe84362cc">anonymous{AMDGPURegisterBankInfo.cpp}::ApplyRegBankMapping::applyBank</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afae5d269529ade8f678f13c1dde831d1">llvm::CombinerHelper::applyCombineShiftToUnmerge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#afda3e606ec193ca5b66ef40e9b6da474">anonymous{AArch64PostLegalizerLowering.cpp}::applyDupLane</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#af04d5efb4c01491738f47fb92325d238">llvm::AMDGPUCombinerHelper::applyExpandPromotedF16FMed3</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ab5aa406f974e74967376237df439846a">anonymous{AArch64PostLegalizerLowering.cpp}::applyEXT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a0abbf3ef98128dcfc14aa5b3f99e8731">anonymous{AArch64PostLegalizerCombiner.cpp}::applyExtractVecEltPairwiseAdd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a0647544d97241e683cd0d0b7f3f51927">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a89a1d7d6a7cd7ea75a68ff3719372321">anonymous{AArch64PreLegalizerCombiner.cpp}::applyFoldGlobalOffset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#adf82bf97d32fede84099257eb720a1a2">anonymous{AArch64PostLegalizerLowering.cpp}::applyFullRev</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a79c39eb0fd06bbc443b66f4b6d6711af">anonymous{AArch64PostLegalizerLowering.cpp}::applyINS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1db29ac06ff4dea847d6e5dae7f21ee2">anonymous{AArch64PostLegalizerLowering.cpp}::applyLowerBuildToInsertVecElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0494e300dac616c8ca39b2dbc8b1276c">llvm::AMDGPURegisterBankInfo::applyMappingDynStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a59ce3aa458b07483cb7422b0303b589b">llvm::AMDGPURegisterBankInfo::applyMappingMAD_64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#af375ca05eecaafa17b7a92ec352537d4">llvm::AMDGPU::RegBankLegalizeHelper::applyMappingPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afd96526160e781989c15d6879ad1f9f1">llvm::AMDGPURegisterBankInfo::applyMappingSMULU64</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a41cebcf8d37086a913f6a5424e0bff66">llvm::CombinerHelper::applySDivByPow2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a274719c8dc257cea312dec45a36829fd">anonymous{AArch64PostLegalizerCombiner.cpp}::applySplitStoreZero128</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a976bf3034ffa13d0fd59454e588e316a">anonymous{AArch64PostLegalizerLowering.cpp}::applyVAshrLshrImm</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a84f5d960aa6e996db2572c7d5c7b163e">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a3769dc3bae28271b452cf69cf3494761">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingvaluehandler/#a0d589439dcf785bc8f36eaf8f4b25a90">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#aa35ca40243a91b75afd51c04ee241788">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9f5bc640bcfb6af808fee1216d3895d6">llvm::LegalizerHelper::bitcastConcatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad5c38c10f947e4226f85aade1ebf57f1">llvm::AMDGPULegalizerInfo::buildAbsGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7e58ecea881b2ea06fee315563860e39">llvm::MachineIRBuilder::buildExtractVectorElementConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a010032df630a417383fa44deee43ac0c">llvm::MachineIRBuilder::buildLoadFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af6aed1d3b2cf7133b73cf8bfa5122186">llvm::MachineIRBuilder::buildMaskLowPtrBits</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#af693d8401a06eab53b8b5b2d6df05243">llvm::AMDGPURegisterBankInfo::buildReadFirstLane</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a43b43271e5bcbbc5cc620b4dfa94937a">llvm::MachineIRBuilder::buildShuffleSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#a77d3589f9460c3f08bc6afc49a9985c6">buildSplatSplitS64WithVL</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a5a32fa3ab512ce8c3afa4e68c2b56765">castBufferRsrcToV4I32</a>, <a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#af1ee247ef88b451470210e27a2eefb44">llvm::LegalizeMutations::changeElementSizeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#acc6c42a7b5fe244fad430ca7df32d346">llvm::LegalizerHelper::coerceToScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a03ce5016666b0f1d6de775b6fec814c4">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::constrainAsLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a2a681b9303b51d21a9392975a6cd422c">llvm::CallLowering::ValueHandler::copyArgumentMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a22e9703f8897754ae0ff79ce70b211eb">createTypeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a6817453b853abea76fab37803ade6ef4">llvm::RegisterBankInfo::OperandsMapper::createVRegs</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#aed4feaa9baf8df7fe949b9a5ce246646">elementTypeIsLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a62e3406e85438cd0a8d5e3de179ef6eb">emitReciprocalU64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a6448cfc677ca653b92b0c0bf5f3b29cd">extendLow32IntoHigh32</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucalllowering-cpp-/#af49a6097a8071a69f37f57febd91c05c">anonymous{AMDGPUCallLowering.cpp}::extendRegisterMin32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a47ea7f32b98178dbcb9bf3d1ff00daa1">extractF64Exponent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1eac84349f5abc12d101036412730c5c">llvm::LegalizerHelper::fewerElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a1476a89aa41e0a21b60bfc63a292f2c3">findGISelOptimalMemOpLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af3c20d55579ac56788b8134a4d3e724f">llvm::AMDGPULegalizerInfo::fixStoreSourceType</a>, <a href="#abb1f260fc4da86ce2e93fa8628aa0b1d">float16</a>, <a href="#aee6abb440f4fe52097595d934283f0a1">float32</a>, <a href="#a0631408a6598e34659cc5495c3ec090b">float64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4bf8d79fb617413b09980966a60e5a">llvm::generateBuiltinVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63b94467b9a18c31a4ee6d6ec4c34425">llvm::generateWaveInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7d4da10beff712762d6e9ebbf51b339a">getAnySgprS1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a639711ef50cb300db9e9ade1445ccf07">getBitcastRegisterType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a64443e60c47deb77ad3bb491d2da3c5f">getBufferRsrcRegisterType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0440dee786271aa77b3f640b1c63363c">getBufferRsrcScalarType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ae8882b2a7fc8ce50e0ae8a34ffd802c1">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::getCandidatesForLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab95d4485884d2e093f534590f24cfe0d">llvm::LegalizerHelper::getDynStackAllocTargetPtr</a>, <a href="#aa24450f600cabd7212bd264a6dbc190c">getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#afa3232adbead0d5386a1e7636a9d772f">getHalfSizedType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad7c01a9166d49578fc9cb3162a87f396">llvm::AMDGPULegalizerInfo::getImplicitArgPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#adeb18e3c3ca254b1eac668a91c0a18e8">llvm::AMDGPULegalizerInfo::getKernargParameterPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45e006fa9af3ebf9405bb3154f70f9af">llvm::getLLTForMVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd34773dd33963769279868ab39d5fdc">llvm::getLLTForType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#acbb662ad1799057d6bea1501cbaf5d46">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#ad1f97111fb4c021a0584599e68e93032">getMaskTypeFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab72c286743e675ffbe81f7c9e9771fa5">llvm::AArch64TargetLowering::getOptimalMemOpLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a35c2ba2ad91e2fe027f8f64e92a7502f">llvm::SPIRVGlobalRegistry::getOrCreateUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ae9bc1717e31ed947b2eae89a230c744b">getPow2ScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a9ccdd07da05e067c1e31356005bb39b0">llvm::AMDGPUFunctionArgInfo::getPreloadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliselutils-cpp/#a50a705446015e4b43ea1f59a13eba3b8">getReadAnyLaneSplitTy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a53fe77055b01a82e1a53e7798cef110a">llvm::AMDGPURegisterBankInfo::getRegBankFromRegClass</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#a3567eeb5329842ab332bee9c2cd43edf">RegBankSelectHelper::getRegBankToAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#abc10c981c4505185b1d517237acaf9c2">llvm::AVRTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a6fae73b0e495a895c3ce49f127bf8ef7">llvm::PPCTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6cccbc4ab2203366175f55aba0035679">llvm::AMDGPULegalizerInfo::getScaledLogInput</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2fd97f50411bc650c7f9f6e3118147f4">llvm::AMDGPULegalizerInfo::getSegmentAperture</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a1de30cc152058819888b9d02619f16ac">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a0256194175f52db6cc06eb379bd412dc">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a059b61bb0bab07b3cf7da0e06f5893dd">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a202a7e2a16e7921c97c6767cb68bdae9">M68kOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3cc2ef5101115495b8700d1e71834d9e">isFPExtFromF16OrConst</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a3c10b311bd64612a48062c43193f566a">AMDGPURegBankLegalizeCombiner::isLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3cc7860fbf211f566f62809ac1144023">llvm::AMDGPULegalizerInfo::legalizeBufferAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4117d1ecf36af9158c825fb376c4082e">llvm::AMDGPULegalizerInfo::legalizeBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6bd6caf03c29de76c97c536f89349bd7">llvm::SPIRVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aec28181fa8c84646c097212f19e379f1">llvm::AMDGPULegalizerInfo::legalizeExtractVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aa71647a93d5e73c28332b6e52407979c">llvm::AMDGPULegalizerInfo::legalizeFastUnsafeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae468aab9eee24365f029a78836e6435d">llvm::AMDGPULegalizerInfo::legalizeFceil</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4f3b6abeaf9c509c93062f2246a0f40b">llvm::AMDGPULegalizerInfo::legalizeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6451bf061f754edbcd6043a20bfc663c">llvm::AMDGPULegalizerInfo::legalizeFDIV16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a464ac3e6051fb78eb3ee985975d17cb2">llvm::AMDGPULegalizerInfo::legalizeFDIV32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a30fc420ff83b1e2c4ab42e86d9071e34">llvm::AMDGPULegalizerInfo::legalizeFDIV64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6f737d47e92bb08927c272b12fba32d8">llvm::AMDGPULegalizerInfo::legalizeFDIVFastIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3c2bbefdd60b95a56cf8eeab162ea2ae">llvm::AMDGPULegalizerInfo::legalizeFExp2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a79967954fb48056dab46d231e4aab954">llvm::AMDGPULegalizerInfo::legalizeFExpUnsafe</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44186e632d4bab1d35012ed738a23870">llvm::AMDGPULegalizerInfo::legalizeFFloor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2b530047260b0f52c4dd8823764acb2d">llvm::AMDGPULegalizerInfo::legalizeFFREXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#afb13811bb447af9b35a1ae4257e37a36">llvm::AMDGPULegalizerInfo::legalizeFlog2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a39adc1637ddc1df880ec4ab13529879e">llvm::AMDGPULegalizerInfo::legalizeFlogCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ac7d32c396b93d03561c3c14fde634e9c">llvm::AMDGPULegalizerInfo::legalizeFlogUnsafe</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ac6475a6b99e088697d90032ddab24447">llvm::AMDGPULegalizerInfo::legalizeFPTOI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ab2bd62dca48651e04d811aff7bfc2aa6">llvm::AMDGPULegalizerInfo::legalizeFroundeven</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad8779ad5bc404af71eaa72036c8be55f">llvm::AMDGPULegalizerInfo::legalizeFSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a07957999af426a9136774abb7a037286">llvm::AMDGPULegalizerInfo::legalizeFSQRTF16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a20562025b5dd6e948bb3346d29417237">llvm::AMDGPULegalizerInfo::legalizeFSQRTF32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae6424442b4dd0280dd56bc1c577e68ed">llvm::AMDGPULegalizerInfo::legalizeFSQRTF64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a0e7378d479179ae1df0b61b83c637a4d">llvm::AMDGPULegalizerInfo::legalizeIntrinsicTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a1a1ef8cdc87d83bb4e114e897e86d58c">llvm::AMDGPULegalizerInfo::legalizeIsAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#abb023d557c720f8730e0c266c1cd0f9c">llvm::AMDGPULegalizerInfo::legalizeITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#acd7e869bdfe172fce447a9d289343d1a">llvm::AMDGPULegalizerInfo::legalizeKernargMemParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2645b2c5fc9b404821322ad403c87810">llvm::AMDGPULegalizerInfo::legalizeMul</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a376125f5ee6f0a21fdd6336557fa3913">llvm::AMDGPULegalizerInfo::legalizePointerAsRsrcIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a68b29f4aff8a6db0040bc8e00a520116">llvm::AMDGPULegalizerInfo::legalizeRsqClampIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aba263b2348b84c2d9a10adc0a42d9606">llvm::AMDGPULegalizerInfo::legalizeSignedDIV_REM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af9de933caeeaebd4387c7c62f02a3bbd">llvm::AMDGPULegalizerInfo::legalizeTrapHsaQueuePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a1d0eafc5b0af4bf05b288d62caa72ac9">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3db547888c8d2ed5323f320bb5763014">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM32Impl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a93bbde2af63d129f752ef7c3a0f84c15">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM64Impl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ab0873d6f5bfe8490b5ef6be3a84dd805">llvm::AMDGPULegalizerInfo::legalizeWaveID</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af7e4619611fab877c69f6ec0a1d57525">llvm::AMDGPULegalizerInfo::legalizeWorkitemIDIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#a5430de9bfca0f2700d4afb0121e156fe">LLTToBId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a724c83948fec4d3162f4620ec6f61a7a">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae63198baedfab72494f0d79823e99b75">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a41da6a2461e80e2d3b6b226281477bfa">llvm::LegalizerHelper::lowerAbsToCNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a76e5a8c6363a48b3ca4e924a8f59f0e5">llvm::LegalizerHelper::lowerExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab99f92278021f1921be23b762056a9cc">llvm::LegalizerHelper::lowerFPTOSI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaa03d66b30e1b6173c99b9a4266b7da9">llvm::LegalizerHelper::lowerFPTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a04ee040b3b0253a0832ddb7915d55ae1">llvm::LegalizerHelper::lowerFPTRUNC_F64_TO_F16</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abce8515ac1fb3b6be13d5a39418847cb">llvm::LegalizerHelper::lowerMergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad29042068469adc2859360985494dbb9">llvm::LegalizerHelper::lowerSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abac7927a227a6c370e26ee82af77567d">llvm::LegalizerHelper::lowerShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a4f859f973b7f797f2d510c369980ad">llvm::LegalizerHelper::lowerSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9b5ad9f5de612dc98a4f3232a98ab754">llvm::LegalizerHelper::lowerU64ToF32BitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac9599381b406afe38a263b028248e407">llvm::LegalizerHelper::lowerU64ToF32WithSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a13531e23193d32ac81bdefa1db2ad987">llvm::LegalizerHelper::lowerU64ToF64BitFloatOps</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aba403eaa336a6c9d869717c9e54edd9c">llvm::LegalizerHelper::lowerUITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9511578c9aa47dc8c5d7df3e9b623be3">llvm::LegalizerHelper::lowerVAArg</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac29774c06843a7c183ae3fd328d43bc8">llvm::LegalizerHelper::lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/structs/llvm/m68klegalizerinfo/#a77a1ff087fb51dfd9397ffc153578c43">llvm::M68kLegalizerInfo::M68kLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#abc221f9ddb2aa39e4a840a7c55a3d1c5">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::markAsLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a78bf4f9ce583ccdc1b4dbaf6c56a0030">llvm::AMDGPUCombinerHelper::matchExpandPromotedF16FMed3</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a63f58e0b8724553f94baf162c3672f32">anonymous{AArch64PostLegalizerCombiner.cpp}::matchFoldMergeToZext</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a59e682863250eb07290a348d548eee0d">llvm::CombinerHelper::matchNarrowBinopFeedingAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8f5dd5583d12f1c7dcf63b86ff444394">llvm::CombinerHelper::matchSextInRegOfLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a51f93c65cadd67241250f97598ab1358">llvm::CombinerHelper::matchUDivByConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a92451ecb6973ca4c1190514f75618d40">matchZeroExtendFromS32</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a4aca13e5c1613b22b7c3c9411895fdae">llvm::LegalizeRuleSet::minScalarEltSameAsIf</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aea9d2b3b2a626fb7c5093f5f8fa9cf95">llvm::LegalizerHelper::narrowScalarAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae25927a69e107ef1477822b884ca034b">llvm::LegalizerHelper::narrowScalarCTLZ</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2db1bc1a16d89298b92a13857146e28d">llvm::LegalizerHelper::narrowScalarCTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaec7c9b0ed49d3297c833d8d9def42c0">llvm::LegalizerHelper::narrowScalarExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a687c20941b83380477f4a3d95ad4e390">llvm::LegalizerHelper::narrowScalarFPTOI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad43f277d8baa4b080bfd1beed8542bd6">llvm::LegalizerHelper::narrowScalarInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2f99d62852a3fab708983d8ea2139755">llvm::LegalizerHelper::narrowScalarShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">anonymous{MIParser.cpp}::MIParser::parseMachineMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#af31cf7c3246e88cbfbb4a3dab768a047">llvm::RISCVLegalizerInfo::RISCVLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#a477b123c7ac80e57d0c8ac4abb0ff293">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ad1210df2e489436f417f18f10180ea44">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>, <a href="#a31c9d40cb2f72eba97644766b2439092">scalarOrVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a4a8b881c0637c6f85c3eb6891abcfab4">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a978498ac91a6e163a70f06bf1259e224">llvm::AMDGPUInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a8532a373e31385aa7f7ff3c4d14eff4b">llvm::AMDGPURegisterBankInfo::setBufferOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a381f41669927321758998407f3fe0994">llvm::MipsRegisterBankInfo::setRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a14daf64c8f1ebcbe259a41854f49ad12">llvm::AMDGPULegalizerInfo::splitBufferOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0924254734e306adcc8cdcd0e2a3544c">llvm::AMDGPURegisterBankInfo::splitBufferOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#ab4c2bc39e4119d3c2098986cfd7be179">splitUnequalType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a5227e311d2ae980540efa4033943595e">unpackV2S16ToS32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a344a4fa1e7c1a3a6f6ede4213058ad12">valueIsKnownNeverF32Denorm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#af1deb020986939504194841306a9da79">widen96To128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a60f1d0c2492ebc3d0e6eba6c6be95424">widenScalarLLTNextPow2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acbd3ab3957032feb181df036bb6a8d27">widenToNextPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a430225b2e66451c27e9f4e9462be7df1">llvm::LegalizeRuleSet::widenVectorEltsToVectorMinSize</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### scalarOrVector() {#ae74a60e5edcee0609a1e4fddc62a8a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::scalarOrVector (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ScalarTy)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a> and <a href="#a5360139c6b31d85cf3e29e2e6b7cf873">vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0aab1c76215e1773caa058744d6ae6af">bitcastToVectorElement32</a>, <a href="#adabd45e67a1847750a117317b5ef8f9f">changeElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="#af11a4c235044d52af7fbf840dec3f278">divide</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a3b5805e73f162bbb84584fbc2091806e">fewerEltsToSize64Vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a639711ef50cb300db9e9ade1445ccf07">getBitcastRegisterType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#afa3232adbead0d5386a1e7636a9d772f">getHalfSizedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45e006fa9af3ebf9405bb3154f70f9af">llvm::getLLTForMVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="#a52cd802a268f6ed25d878c96d8b16247">multiplyElements</a>, <a href="#a31c9d40cb2f72eba97644766b2439092">scalarOrVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#ab4c2bc39e4119d3c2098986cfd7be179">splitUnequalType</a>.</p>

</div>
</div>

### scalarOrVector() {#a31c9d40cb2f72eba97644766b2439092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::scalarOrVector (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, uint64_t ScalarSize)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>, <a href="#a67021459c7ef8f9a634b4eac7ffd0f96">scalar</a> and <a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a>.</p>

</div>
</div>

### token() {#ad2c874bad47bf92187afb13eb2840643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::token ()</td>
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

<p>Get a low-level token; just a scalar with zero bits (or no size).</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afd34773dd33963769279868ab39d5fdc">llvm::getLLTForType</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>.</p>

</div>
</div>

### vector() {#a5360139c6b31d85cf3e29e2e6b7cf873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::vector (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, unsigned ScalarSizeInBits)</td>
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

<p>Get a low-level vector of some number of elements and element width.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a41cebcf8d37086a913f6a5424e0bff66">llvm::CombinerHelper::applySDivByPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a4871db57e613d42877b6c9e1b901f6be">llvm::LegalizerHelper::bitcastExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6988a4a2d7b33093620e7a456e811a4b">llvm::LegalizerHelper::bitcastInsertSubvector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="#aaa6f42b31892a929914872c879e4b365">changeElementSize</a>, <a href="#a4f404daab6050b7a8e95bb247d4aefb2">changeElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0440dee786271aa77b3f640b1c63363c">getBufferRsrcScalarType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd34773dd33963769279868ab39d5fdc">llvm::getLLTForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvlegalizerinfo-cpp/#ad1f97111fb4c021a0584599e68e93032">getMaskTypeFor</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a5176666164b27a32c0b6093b921cde29">llvm::CallLowering::ValueHandler::getStackValueStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="#ae74a60e5edcee0609a1e4fddc62a8a01">scalarOrVector</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### vector() {#aa558a9e76bb04a92258576836a53592b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr LLT llvm::LLT::vector (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ScalarTy)</td>
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

<p>Get a low-level vector of some number of elements and element type.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac33fa4c8cfeb9287f51f95404a459de8">getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="#a956ffd0de93798f523683b447646dd92">getSizeInBits</a>, <a href="#a9d825f5954d7bd527aea490668c624c6">isPointer</a>, <a href="#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">isVector</a> and <a href="#a38374ccd4721f95ba3942d38afe726c5">LLT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getMask() {#aab2dab30e835a4a5c0b1bd3c04025be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t llvm::LLT::getMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BitFieldInfo FieldInfo)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### maskAndShift() {#af661ea6ff23d30dfcc385efc3c2e4168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t llvm::LLT::maskAndShift (uint64_t Val, uint64_t Mask, uint8_t Shift)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### maskAndShift() {#a9bd694cf0e2cfd29cc8aab141bbcfa04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr uint64_t llvm::LLT::maskAndShift (uint64_t Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BitFieldInfo FieldInfo)</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### PointerAddressSpaceFieldInfo {#a96eb54b262f9e208ab253778312198fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const constexpr LLT::BitFieldInfo LLT::PointerAddressSpaceFieldInfo {24, 21}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### PointerSizeFieldInfo {#a72e05a7f8ac0640b2f428955ef9e517c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const constexpr LLT::BitFieldInfo LLT::PointerSizeFieldInfo {16, 45}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<ul class="doxyList ">
<li>Pointer (isPointer == 1 &amp;&amp; isVector == 0): SizeInBits: 16; <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dc">AddressSpace</a>: 24;</li>
</ul>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### ScalarSizeFieldInfo {#ad4304de22945478f044ba43a53e17748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const constexpr LLT::BitFieldInfo LLT::ScalarSizeFieldInfo {32, 29}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is how the bitfields are packed per Kind:</p>


<ul class="doxyList ">
<li>Invalid: gets encoded as RawData == 0, as that is an invalid encoding, since for valid encodings, SizeInBits/SizeOfElement must be larger than 0.</li>
<li>Non-pointer scalar (isPointer == 0 &amp;&amp; isVector == 0): SizeInBits: 32;</li>
</ul>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### VectorElementsFieldInfo {#a94accdf30c05bf911f0f7729dc06c4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const constexpr LLT::BitFieldInfo LLT::VectorElementsFieldInfo {16, 5}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<ul class="doxyList ">
<li>Vector-of-non-pointer (isPointer == 0 &amp;&amp; isVector == 1): NumElements: 16; SizeOfElement: 32; Scalable: 1;</li>
</ul>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

### VectorScalableFieldInfo {#ad9cc1a3af7c8fa4101ee1689bbec7639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const constexpr LLT::BitFieldInfo LLT::VectorScalableFieldInfo {1, 0}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">LowLevelType.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegentypes/lowleveltype-cpp">LowLevelType.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
