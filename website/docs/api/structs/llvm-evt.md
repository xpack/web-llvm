---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/evt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `EVT` Struct

<p>Extended <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::EVT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1993979005aae58b47312a7d0fe246c5">EVT</a> (MVT::SimpleValueType SVT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cda3e2e7fbf93de27f9bf612c958c13">EVT</a> (MVT S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2be0588fc2f9cc904d95179fd83e63e">operator==</a> (EVT VT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8804ef803cb893d306f7c5ebd26693">operator!=</a> (EVT VT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0351571482fea42a3b326147fb2ce9e2">changeVectorElementTypeToInteger</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector with the same number of elements as this vector, but with the element type converted to an integer type with the same bitwidth. <a href="#a0351571482fea42a3b326147fb2ce9e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d00ad929ec93255787f7f80c4659d9">changeVectorElementType</a> (EVT EltVT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a VT for a vector type whose attributes match ourselves with the exception of the element type that is chosen by the caller. <a href="#ad9d00ad929ec93255787f7f80c4659d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6e40b44c47abc845e297c30bbf830c">changeElementType</a> (EVT EltVT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a VT for a type whose attributes match ourselves with the exception of the element type that is chosen by the caller. <a href="#a4e6e40b44c47abc845e297c30bbf830c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25eda78153285bc3bc4708e149b7e9e8">changeTypeToInteger</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type converted to an equivalently sized integer or vector with integer element type. <a href="#a25eda78153285bc3bc4708e149b7e9e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ee94a616a11388828c36d1e0b4798c">isZeroSized</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> has zero size, this will fail if called on a scalable type. <a href="#ae2ee94a616a11388828c36d1e0b4798c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> is simple (as opposed to being extended). <a href="#a19738f4334d4de357b22349bbb56fb5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda309a31acb43c06215c1772727bf1c">isExtended</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> is extended (as opposed to being simple). <a href="#abda309a31acb43c06215c1772727bf1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cb888a2ce8e95e0d9769687a5e2f7d8">isFloatingPoint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a FP or a vector FP type. <a href="#a3cb888a2ce8e95e0d9769687a5e2f7d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af975bf04c49cc895cfe38e7dc126a2f1">isInteger</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer or a vector integer type. <a href="#af975bf04c49cc895cfe38e7dc126a2f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad958859a7af278dd5ea2b593c2b25050">isScalarInteger</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an integer, but not a vector. <a href="#ad958859a7af278dd5ea2b593c2b25050">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90cace0f677d0c16e4507465eff00a8">isScalableTargetExtVT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a vector type where the runtime length is machine dependent. <a href="#ad90cace0f677d0c16e4507465eff00a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54976197fff266f4143beb44fc9764c">isVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a vector value type. <a href="#aa54976197fff266f4143beb44fc9764c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a vector type where the runtime length is machine dependent. <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7687d0ddaf12046ae258432e98ad083e">isRISCVVectorTuple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a vector value type. <a href="#a7687d0ddaf12046ae258432e98ad083e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920f0719057d7352f9da10908859368d">isFixedLengthVector</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a889af4545b49ab18942b3c726f7b13">isScalableVT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the type is a scalable type. <a href="#a8a889af4545b49ab18942b3c726f7b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8dc60b275ae1a147a9b24d4ccdfd305">is16BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 16-bit vector type. <a href="#aa8dc60b275ae1a147a9b24d4ccdfd305">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a407fe71968756ae65989f791f641c375">is32BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 32-bit vector type. <a href="#a407fe71968756ae65989f791f641c375">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa40b0ea2c1858e1e297227cc17d77db">is64BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 64-bit vector type. <a href="#afa40b0ea2c1858e1e297227cc17d77db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db1f207286bd8bc6a978593a55955e9">is128BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 128-bit vector type. <a href="#a6db1f207286bd8bc6a978593a55955e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd05b71fb3b325dcc53a7df09d37edb">is256BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 256-bit vector type. <a href="#aacd05b71fb3b325dcc53a7df09d37edb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eed7940698816c772ded7b098f2e1a1">is512BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 512-bit vector type. <a href="#a8eed7940698816c772ded7b098f2e1a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50fc902bfa2d3dd0cf0fef0a4790716a">is1024BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 1024-bit vector type. <a href="#a50fc902bfa2d3dd0cf0fef0a4790716a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767efe6535626636e7b78470235b5175">is2048BitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a 2048-bit vector type. <a href="#a767efe6535626636e7b78470235b5175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38de8ca5ba228de0eba69c7dfa3639f4">isOverloaded</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an overloaded type for <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>. <a href="#a38de8ca5ba228de0eba69c7dfa3639f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470621733f1ffb597e6f502040216da4">isByteSized</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the bit size is a multiple of 8. <a href="#a470621733f1ffb597e6f502040216da4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41e50273c70287914ded0ae668bc507">isRound</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the size is a power-of-two number of bytes. <a href="#ab41e50273c70287914ded0ae668bc507">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad0b781d8b8a804437e919429069fcd7">bitsEq</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this has the same number of bits as VT. <a href="#aad0b781d8b8a804437e919429069fcd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a510d9e3eba90bc4a7e9925583fbccc3b">knownBitsGT</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know at compile time this has more bits than VT. <a href="#a510d9e3eba90bc4a7e9925583fbccc3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9182379fc7c4d4b8031f1a81221fafd">knownBitsGE</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know at compile time this has more than or the same bits as VT. <a href="#ab9182379fc7c4d4b8031f1a81221fafd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcabb100313dd886a3b9ce7b599337c">knownBitsLT</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know at compile time this has fewer bits than VT. <a href="#a7bcabb100313dd886a3b9ce7b599337c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd3e03c399e181366f177964eaae62b">knownBitsLE</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know at compile time this has fewer than or the same bits as VT. <a href="#a1cd3e03c399e181366f177964eaae62b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad406477784397709a339d5a2957b43">bitsGT</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this has more bits than VT. <a href="#a3ad406477784397709a339d5a2957b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa994416d7190670c5fc0e295ebe6f6b0">bitsGE</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this has no less bits than VT. <a href="#aa994416d7190670c5fc0e295ebe6f6b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf257bfbd279ecfad670be03b00210e">bitsLT</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this has less bits than VT. <a href="#a3bf257bfbd279ecfad670be03b00210e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae67a729c436915221367d8e77412dff4">bitsLE</a> (EVT VT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this has no more bits than VT. <a href="#ae67a729c436915221367d8e77412dff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a81c1cc06a00a0096d839032b5984e9">getSimpleVT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the SimpleValueType held in the specified simple <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>. <a href="#a6a81c1cc06a00a0096d839032b5984e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a vector type, return the element type, otherwise return this. <a href="#aa85c75e8eb097f02caeb5b9119eebfef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a vector type, return the type of each element. <a href="#abc4c6365ade17ad4443ad0e381e7479d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae245d70802e4ebe1cae2b6122c62a22a">getVectorNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a vector type, return the number of elements it contains. <a href="#ae245d70802e4ebe1cae2b6122c62a22a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53fb11c0140efce7e25ca9ff5ccbac96">getVectorMinNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a vector type, return the minimum number of elements it contains. <a href="#a53fb11c0140efce7e25ca9ff5ccbac96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545976aff7ffb1bdec644f6ca5ddfc68">getRISCVVectorTupleNumFields</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a <a href="/web-llvm/docs/api/namespaces/llvm/riscv">RISCV</a> vector tuple type, return the num_fields. <a href="#a545976aff7ffb1bdec644f6ca5ddfc68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the specified value type in bits. <a href="#a45e76d44a189e456d52e37ba3dda0fce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7712dd4392b7eb944b709ac8442634d9">getFixedSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the specified fixed width value type in bits. <a href="#a7712dd4392b7eb944b709ac8442634d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547a88964f1673c84410baa7a2a83f4d">getScalarSizeInBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1572b31fadbd0d758314b8d35a050410">getStoreSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bytes overwritten by a store of the specified value type. <a href="#a1572b31fadbd0d758314b8d35a050410">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2648fd0c9417e0aeb3e8b194c6509357">getScalarStoreSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f64c589a5312630fe76a37f62a39707">getStoreSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bits overwritten by a store of the specified value type. <a href="#a5f64c589a5312630fe76a37f62a39707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb27b88840e7d2d002f721594ec4578">getRoundIntegerType</a> (LLVMContext &amp;Context) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rounds the bit-width of the given integer <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> up to the nearest power of two (and at least to eight), and returns the integer <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> with that number of bits. <a href="#a9cb27b88840e7d2d002f721594ec4578">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587873e0de35da196d3f5fa6d60f738c">getHalfSizedIntegerVT</a> (LLVMContext &amp;Context) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the smallest simple value type that is greater than or equal to half the width of this <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>. <a href="#a587873e0de35da196d3f5fa6d60f738c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a> (LLVMContext &amp;Context) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a VT for an integer vector type with the size of the elements doubled. <a href="#a7913deec1cb15f66661ba96b54391fd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee35a362966ced72913881d8a2dc3be8">getHalfNumVectorElementsVT</a> (LLVMContext &amp;Context) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f78e3bf25a5e4bef300d42dde0d8477">getDoubleNumVectorElementsVT</a> (LLVMContext &amp;Context) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59eee3929b9155fd268e3e3f6c0efde9">isPow2VectorType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given vector is a power of 2. <a href="#a59eee3929b9155fd268e3e3f6c0efde9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f3027fdcad3b33960402d9739afe4b">getPow2VectorType</a> (LLVMContext &amp;Context) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widens the length of the given vector <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> up to the nearest power of 2 and returns that type. <a href="#a15f3027fdcad3b33960402d9739afe4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns value type as a string, e.g. "i32". <a href="#a923e1e1096d253c80d8a241754cb878f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ccc5defb5558c1aad8b592b0352ae90">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for debugging, callable in GDB: VT.dump() <a href="#a6ccc5defb5558c1aad8b592b0352ae90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01a572f584fc9431b4b58eda40075a9">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt;. <a href="#ad01a572f584fc9431b4b58eda40075a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cfceeb37508e56f9c127e59766a668">getTypeForEVT</a> (LLVMContext &amp;Context) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns an LLVM type corresponding to the specified <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>. <a href="#ab0cfceeb37508e56f9c127e59766a668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">intptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab39b6dd48de0a16afa90214d78b2c4">getRawBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf42d7b6a69dc15a64f841d51a9c93b7">getFltSemantics</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> semantics tag appropriate for the value type. <a href="#adf42d7b6a69dc15a64f841d51a9c93b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379f30d5c6c3cd97ebb5fc1a428bcff4">changeExtendedTypeToInteger</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb0b5938523e13297a0355e2068942b">changeExtendedVectorElementType</a> (EVT EltVT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1728d74cf34337d36576208b279b42b">changeExtendedVectorElementTypeToInteger</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314783e8ff418729775d102c31ad2f8d">isExtendedFloatingPoint</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac758bd6f5c454ffff8e6e4a387986fb2">isExtendedInteger</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0971c7bf43884a214b157517e037bd8f">isExtendedScalarInteger</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c69a2302512946dfe1ee066b63b20d">isExtendedVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b2cb62bcf10ae424678cba7829ae08">isExtended16BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9622b3fd44ba620deb2385b9e1134eff">isExtended32BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b90e3d30759c68a3bf4fb119c3cc3e8">isExtended64BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0fe6961ba8683f5b7dfe9200c0e8ab1">isExtended128BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0066573091b25b0b61742700da1bd6b7">isExtended256BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b4baead2bc9e7af713d864d6c7c288">isExtended512BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5530a624984971c9ef1c69eb3cb59c8c">isExtended1024BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac1175d1deb088b8a57571cf3a4695e">isExtended2048BitVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5688e84fbfdf8f6db9e7f1fd50adf06e">isExtendedFixedLengthVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235a9e0b06e3e044ac1fba0fa58a7ca2">isExtendedScalableVector</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5262fef9df4b016ee7c0262b073f5be">getExtendedVectorElementType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216ccc1c772127285c00583055dafbfa">getExtendedVectorNumElements</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40e284a4abd29b622292e55f706b019">getExtendedVectorElementCount</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51f7d097e42c8007368cffae5042072">getExtendedSizeInBits</a> () const LLVM_READONLY</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532e3d47ccc8c419d53c21a494ad8fef">V</a> = <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">MVT::INVALID_SIMPLE_VALUE_TYPE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd16ea35c1ba5a89151427229d403966">LLVMTy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a76e0197f5c34a3e15ba92fbdc9c8b4">getFloatingPointVT</a> (unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents a floating-point type with the given number of bits. <a href="#a9a76e0197f5c34a3e15ba92fbdc9c8b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752372e170e4e7c595bf8810bb52adf2">getIntegerVT</a> (LLVMContext &amp;Context, unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents an integer with the given number of bits. <a href="#a752372e170e4e7c595bf8810bb52adf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a> (LLVMContext &amp;Context, EVT VT, unsigned NumElements, bool IsScalable=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents a vector NumElements in length, where each element is of type VT. <a href="#a210ba6b43ba451b698857dd9de71bd15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f86132c602eed040fd6f48794b1eec">getVectorVT</a> (LLVMContext &amp;Context, EVT VT, ElementCount EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents a vector EC.Min elements in length, where each element is of type VT. <a href="#ab5f86132c602eed040fd6f48794b1eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">getEVT</a> (Type *Ty, bool HandleUnknown=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value type corresponding to the specified type. <a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab0fa2dda3118c3507df13b74d36386">getExtendedIntegerVT</a> (LLVMContext &amp;C, unsigned BitWidth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b263b75a4baebfb5710d6469947f03">getExtendedVectorVT</a> (LLVMContext &amp;C, EVT VT, unsigned NumElements, bool IsScalable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817823345f957416cea36ea226d6244e">getExtendedVectorVT</a> (LLVMContext &amp;Context, EVT VT, ElementCount EC)</td>
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

<p>Extended <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>


<p>Capable of holding value types which are not native for any processor (such as the i12345 type), as well as the types an <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> can represent.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EVT() {#a05ba7800be90a94bec3d4a4eaf29cfa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EVT::EVT ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Referenced by <a href="#aad0b781d8b8a804437e919429069fcd7">bitsEq</a>, <a href="#aa994416d7190670c5fc0e295ebe6f6b0">bitsGE</a>, <a href="#a3ad406477784397709a339d5a2957b43">bitsGT</a>, <a href="#ae67a729c436915221367d8e77412dff4">bitsLE</a>, <a href="#a3bf257bfbd279ecfad670be03b00210e">bitsLT</a>, <a href="#a4e6e40b44c47abc845e297c30bbf830c">changeElementType</a>, <a href="#a25eda78153285bc3bc4708e149b7e9e8">changeTypeToInteger</a>, <a href="#ad9d00ad929ec93255787f7f80c4659d9">changeVectorElementType</a>, <a href="#a0351571482fea42a3b326147fb2ce9e2">changeVectorElementTypeToInteger</a>, <a href="#a3f78e3bf25a5e4bef300d42dde0d8477">getDoubleNumVectorElementsVT</a>, <a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">getEVT</a>, <a href="#a9a76e0197f5c34a3e15ba92fbdc9c8b4">getFloatingPointVT</a>, <a href="#aee35a362966ced72913881d8a2dc3be8">getHalfNumVectorElementsVT</a>, <a href="#a587873e0de35da196d3f5fa6d60f738c">getHalfSizedIntegerVT</a>, <a href="#a752372e170e4e7c595bf8810bb52adf2">getIntegerVT</a>, <a href="#a15f3027fdcad3b33960402d9739afe4b">getPow2VectorType</a>, <a href="#a9cb27b88840e7d2d002f721594ec4578">getRoundIntegerType</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a>, <a href="#ab5f86132c602eed040fd6f48794b1eec">getVectorVT</a>, <a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a>, <a href="#ab9182379fc7c4d4b8031f1a81221fafd">knownBitsGE</a>, <a href="#a510d9e3eba90bc4a7e9925583fbccc3b">knownBitsGT</a>, <a href="#a1cd3e03c399e181366f177964eaae62b">knownBitsLE</a>, <a href="#a7bcabb100313dd886a3b9ce7b599337c">knownBitsLT</a>, <a href="#a9c8804ef803cb893d306f7c5ebd26693">operator!=</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/comparerawbits/#a3d250addffd841fff13204ac44bd2110">llvm::EVT::compareRawBits::operator()</a>, <a href="#ae2be0588fc2f9cc904d95179fd83e63e">operator==</a> and <a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a>.</p>

</div>
</div>

### EVT() {#a1993979005aae58b47312a7d0fe246c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EVT::EVT (<a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a> SVT)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>

</div>
</div>

### EVT() {#a6cda3e2e7fbf93de27f9bf612c958c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EVT::EVT (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> S)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a9c8804ef803cb893d306f7c5ebd26693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::operator!= (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>

</div>
</div>

### operator==() {#ae2be0588fc2f9cc904d95179fd83e63e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::operator== (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### bitsEq() {#aad0b781d8b8a804437e919429069fcd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::bitsEq (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if this has the same number of bits as VT.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a> and <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aaa74206833e0a1c2a2c0a3c53a64267c">llvm::SelectionDAG::getStrictFPExtendOrRound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad02dfd40a37e1c0fc6365a700c4263dc">lowerFCMPIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6ffcf0878851c4e84a8c11a68b07e9e7">lowerICMPIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a7003b5e44eb73177e8c26b4a91247e57">llvm::AMDGPUDAGToDAGISel::SelectVectorShuffle</a>.</p>

</div>
</div>

### bitsGE() {#aa994416d7190670c5fc0e295ebe6f6b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::bitsGE (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if this has no less bits than VT.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a> and <a href="#ab9182379fc7c4d4b8031f1a81221fafd">knownBitsGE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp/#a219666604b8d066914b87cdf21db4e21">findFPToIntLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ceb04284d179d66b26dede64956d9c7">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2c8bc97059759cb53b363069723311ef">llvm::AMDGPUTargetLowering::performAssertSZExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9843d498d81fb04dfb533d4702589ae8">performSIGN_EXTEND_INREGCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a57e07229bb762532f34ea34c656dc6eb">unrollVectorShift</a>.</p>

</div>
</div>

### bitsGT() {#a3ad406477784397709a339d5a2957b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::bitsGT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if this has more bits than VT.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a> and <a href="#a510d9e3eba90bc4a7e9925583fbccc3b">knownBitsGT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#aba88c9378ff5001a15ced63b0212cd10">llvm::R600TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aae7e97fa59261cc890aa2359971adfd4">llvm::SelectionDAG::getAnyExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abb12b9027c14ccb724eb3c506a7f8745">llvm::SelectionDAG::getFPExtendOrRound</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5997c4992589047ebc712b52b6e101cb">llvm::FastISel::getRegForGEPIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9c2450d7d33fb2ecb9b645f1ca6a9a64">llvm::SelectionDAG::getSExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aaa74206833e0a1c2a2c0a3c53a64267c">llvm::SelectionDAG::getStrictFPExtendOrRound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1cdb38ba97d3ced9be618b22a8053581">getSVEPredicateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4b28f0998adc5a00c50c23a919ddeaac">llvm::SelectionDAG::getVPZExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad0c6f059b29535f2c790d1c4f92b7a93">llvm::SelectionDAG::getZExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2ee3671994de5e466ba0feabe827bf5d">LowerSELECTWithCmpZero</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a35eced9d40135070fe0e267898a9be26">llvm::HexagonTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ab30094b924bc7333b5bf134d7985ca18">llvm::FastISel::selectOperator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>.</p>

</div>
</div>

### bitsLE() {#ae67a729c436915221367d8e77412dff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::bitsLE (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if this has no more bits than VT.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a> and <a href="#a1cd3e03c399e181366f177964eaae62b">knownBitsLE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7e66d5a43444879fa5037f2cfaa4de5">llvm::SelectionDAG::getBoolExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aca0e8562bea682465caada8d71a47234">llvm::SelectionDAG::getSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8ab55d055af84ce8d884844d5171198e">llvm::SelectionDAG::getSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02127bae19ef433c1233c696317a8868">llvm::SelectionDAG::getVPZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab049ba889709df922c683e1961c32ae9">llvm::AMDGPUTargetLowering::performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a>.</p>

</div>
</div>

### bitsLT() {#a3bf257bfbd279ecfad670be03b00210e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::bitsLT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if this has less bits than VT.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a> and <a href="#a7bcabb100313dd886a3b9ce7b599337c">knownBitsLT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#aba88c9378ff5001a15ced63b0212cd10">llvm::R600TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a46d3f3df1ff44267f1bf6ef7831df4fd">getLoadExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5997c4992589047ebc712b52b6e101cb">llvm::FastISel::getRegForGEPIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1aad91323f0a3814a7918d472e6e5bbb">llvm::SelectionDAG::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a940aa5c3b3202d4d987e2a999450f240">llvm::MipsTargetLowering::getTypeForExtReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a2b10a312e4ab7eb05f1b88f6e5eb8e56">llvm::TargetLowering::getTypeForExtReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4b28f0998adc5a00c50c23a919ddeaac">llvm::SelectionDAG::getVPZExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a3f2d2ccbfc46c0e13c61e6ef6980f309">handleCMSEValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6e9a1f8a595e1e9b2bb022451203ccc2">legalizeScatterGatherIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2ee3671994de5e466ba0feabe827bf5d">LowerSELECTWithCmpZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697277613cca131c099969ca5d421041">llvm::SITargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ab30094b924bc7333b5bf134d7985ca18">llvm::FastISel::selectOperator</a>.</p>

</div>
</div>

### changeElementType() {#a4e6e40b44c47abc845e297c30bbf830c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::changeElementType (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> EltVT)</td>
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

<p>Return a VT for a type whose attributes match ourselves with the exception of the element type that is chosen by the caller.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#ad9d00ad929ec93255787f7f80c4659d9">changeVectorElementType</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>

</div>
</div>

### changeTypeToInteger() {#a25eda78153285bc3bc4708e149b7e9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::changeTypeToInteger ()</td>
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

<p>Return the type converted to an equivalently sized integer or vector with integer element type.</p>


<p>Similar to changeVectorElementTypeToInteger, but also handles scalars.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a5217fc9da38fc836d161d01c8d79ad68">llvm::MVT::changeTypeToInteger</a>, <a href="#a0351571482fea42a3b326147fb2ce9e2">changeVectorElementTypeToInteger</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a6a81c1cc06a00a0096d839032b5984e9">getSimpleVT</a>, <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a068555b4b66d140162c7d3c2cb16beae">adjustLoadValueTypeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#acab5bf267b2b761c038dd0976779a5e9">constructRetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a22aeb0a2fa8f9d75380e4a0df63afead">llvm::SITargetLowering::lowerFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae814004d3aa90fb312b7ac62cedb284">performLD1ReplicateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed80d9ad70fe74f3136dd25a2eee1c47">performLDNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a13534e47159f35c97e261aac72664214">performSTNT1Combine</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>.</p>

</div>
</div>

### changeVectorElementType() {#ad9d00ad929ec93255787f7f80c4659d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::changeVectorElementType (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> EltVT)</td>
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

<p>Return a VT for a vector type whose attributes match ourselves with the exception of the element type that is chosen by the caller.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e9e0d1cbe1230db327c317c3658070f">llvm::MVT::changeVectorElementType</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a6a81c1cc06a00a0096d839032b5984e9">getSimpleVT</a> and <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="#a4e6e40b44c47abc845e297c30bbf830c">changeElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aba30f84d7fd0dd3361ff92fe1e53d9ca">llvm::X86TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a94f640528921c3098a4dbaeef460e2ae">getPredicateForScalableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7c19f0fe8ae2a12ed0c5cf142a520522">llvm::X86TargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9f81a81b890192ac2e40f2995080feaa">llvm::X86TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6e9a1f8a595e1e9b2bb022451203ccc2">legalizeScatterGatherIndexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adc552041debc73d1122de01993523820">LowerFLDEXP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a90b1ef73daf047e3bc666006c9e35a77">performBuildShuffleExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53300f43eec34fc01f85c153445e4a37">reduceMaskedLoadToScalarLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6dc0d17c5d20afdfa4004345e930584c">widenVectorToPartType</a>.</p>

</div>
</div>

### changeVectorElementTypeToInteger() {#a0351571482fea42a3b326147fb2ce9e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::changeVectorElementTypeToInteger ()</td>
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

<p>Return a vector with the same number of elements as this vector, but with the element type converted to an integer type with the same bitwidth.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#af5b209a6f104d5204b17793cddfbc160">llvm::MVT::changeVectorElementTypeToInteger</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a6a81c1cc06a00a0096d839032b5984e9">getSimpleVT</a> and <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="#a25eda78153285bc3bc4708e149b7e9e8">changeTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad2800cb88996291ed1676f5899997ebe">combineExtSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a482f0fad081b3094561d510c11335bfd">createVariablePermute</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4fce00050967f2d8237319f1912a0103">llvm::AArch64TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a667a905e2496f6b0b9c7915a97f58da1">llvm::ARMTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetlowering/#aea1223f03c63339534884b7dc67ed3bf">llvm::CSKYTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a3612d2574f9af7ad6fe1fbd439141ef3">llvm::LoongArchTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a38b88641f5f9abe6b18b921f0eaceb93">llvm::MipsTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#aea8d3912f4a0d003d32577f1098a8b44">llvm::PPCTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a92a4ac2a18c3585d85a9ed7023bdec9b">llvm::R600TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6cf51cce9a6839a2849aeadcc0312d31">llvm::RISCVTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab6fdf85d994da1352162850ae53f7020">llvm::SparcTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a344d2899c3ac0b0d124ace1fe503f56d">llvm::SystemZTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae93a1ba51c086441ec1b9ea4cdca853a">llvm::X86TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a9cd8e49a0ab3c32b798c972a75a6611c">llvm::XtensaTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab8d9e84c7d48cbe98372e43cc9f009d6">lowerVECTOR_SHUFFLE_VSHF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>.</p>

</div>
</div>

### dump() {#a6ccc5defb5558c1aad8b592b0352ae90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void EVT::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Support for debugging, callable in GDB: VT.dump()</p>

<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ad01a572f584fc9431b4b58eda40075a9">print</a>.</p>

</div>
</div>

### getDoubleNumVectorElementsVT() {#a3f78e3bf25a5e4bef300d42dde0d8477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getDoubleNumVectorElementsVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a> and <a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6f6622d37de7bdbf2708835f57864a96">LowerCONCAT_VECTORS_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72895c7f66e26be35e106221a2ab26ae">performSignExtendInRegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae1413a27963c6b3bb1f370867e16b61e">performUADDVZextCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>.</p>

</div>
</div>

### getEVTString() {#a923e1e1096d253c80d8a241754cb878f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string EVT::getEVTString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function returns value type as a string, e.g. "i32".</p>


<p>getEVTString - This function returns value type as a string, e.g. "i32".</p>


<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>


<p>References <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a545976aff7ffb1bdec644f6ca5ddfc68">getRISCVVectorTupleNumFields</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a>, <a href="#a3cb888a2ce8e95e0d9769687a5e2f7d8">isFloatingPoint</a>, <a href="#af975bf04c49cc895cfe38e7dc126a2f1">isInteger</a>, <a href="#a7687d0ddaf12046ae258432e98ad083e">isRISCVVectorTuple</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a>, <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="#ad01a572f584fc9431b4b58eda40075a9">print</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aed94d0d6681eb2f9d3ea4d22dbbde35c">llvm::MVT::print</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad4e2295ddf513d5a4898fa7b3f1c2121">llvm::SDNode::print_types</a>.</p>

</div>
</div>

### getFixedSizeInBits() {#a7712dd4392b7eb944b709ac8442634d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::EVT::getFixedSizeInBits ()</td>
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

<p>Return the size of the specified fixed width value type in bits.</p>


<p>The function will assert if the type is scalable.</p>


<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a> and <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1b64f17c84bc615a735f48746a0740">combineBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#adeba9ee43ee94300c5bb47b99b47a945">findMemType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a20da1c5593bda4b444a75755223a96fe">getReducedGprRegisterClass</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#abd46b9ca1d156bc7e3dd9150cc106a28">llvm::SDValue::getScalarValueSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d9cbc37a87cd3868398004c7ec37b04">IsMulWideOperandDemotable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3ee90d2d8bdc505c6422560cd54d4a54">llvm::AArch64TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#ac0da0afbc93eeaad18d82408f439551e">llvm::MSP430TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a4f1989424b52e6c76aa2272e0e26a492">llvm::SystemZTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aea8c2b718c1dd866d61c29081c1eb44f">llvm::RISCVTargetLowering::joinRegisterPartsIntoValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abf668b25006ed7fd3e0b86681aa0e5e1">lookThroughSignExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ae1416413e8b25024ca51882c2e1cd4db">LowerVAARG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1f71843f178d1cbe0f1bd95af528c46">lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7cdac11a3fa70f7ccb30ead4228dced4">LowerVectorMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae0ba07379c6e2b16764ab8ac1cacb13c">PromoteScalarIntegerPTX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionimpl/#a2ff692eefcb74ae2bbd96ff5f9241287">anonymous{TypePromotion.cpp}::TypePromotionImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab0ca85a9323ae8a5965a7c4d9e96a097">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVEShiftSplatImmR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#adafeb00ea78374224e3589c91b88f02e">truncateScalarIntegerArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d9cb8881ecb22d3225e564b5b2fb01c">tryWidenMaskForShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a2f7ac4b96278419769d4bd3caa6fcf26">llvm::AArch64Subtarget::useSVEForFixedLengthVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a>.</p>

</div>
</div>

### getFltSemantics() {#adf42d7b6a69dc15a64f841d51a9c93b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; EVT::getFltSemantics ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> semantics tag appropriate for the value type.</p>


<p>If this is a vector type, the element semantics are returned.</p>


<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a> and <a href="#a6a81c1cc06a00a0096d839032b5984e9">getSimpleVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9940526e89938ffd29ad3135da3e2f7d">FoldIntToFPToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a354aae224911d4dab66e34bfa10cf5d6">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af37a2a886a9f299db7e743315975b611">llvm::SelectionDAG::getDenormalMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae07d5efbe94a4af292ffa12c5e9de0e5">getEstimate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8fd61f288d29d0a4114ca74f4befd17d">llvm::AMDGPUTargetLowering::getIsFinite</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b9405405e3fd94cb6afc437af701f68">llvm::AMDGPUTargetLowering::getIsLtSmallestNormal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2f8b153ed08786f54cf5e64aa404552">llvm::isNeutralConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a032c3c529239728e58f7fccdbcdbc033">llvm::ConstantFPSDNode::isValueValidForType</a>.</p>

</div>
</div>

### getHalfNumVectorElementsVT() {#aee35a362966ced72913881d8a2dc3be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getHalfNumVectorElementsVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a> and <a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4149392e82922475c1b566db35e3c8b8">combineAndShuffleNot</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a576060235339ed4cc1615a55ed869bf0">llvm::SelectionDAG::GetSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9855e2b319987248786fd81ba1d8c35d">isUpperSubvectorUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab18e3739ef247af415be89a6d40fc20c">LowerVectorExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a95b61f0543f51a5dca686a9f9f258240">tryFormConcatFromShuffle</a>.</p>

</div>
</div>

### getHalfSizedIntegerVT() {#a587873e0de35da196d3f5fa6d60f738c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getHalfSizedIntegerVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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

<p>Finds the smallest simple value type that is greater than or equal to half the width of this <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>.</p>


<p>If no simple value type can be found, an extended integer value type of half the size (rounded up) is returned.</p>


<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a752372e170e4e7c595bf8810bb52adf2">getIntegerVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>, <a href="#af975bf04c49cc895cfe38e7dc126a2f1">isInteger</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4c55ea322cde31251b9727c6109895bd">llvm::AMDGPUTargetLowering::LowerSDIVREM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aec76b73c15365e949f7322e371e6471b">llvm::AMDGPUTargetLowering::LowerUDIVREM64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac5670c01bc722932c40b06aaab52a0df">skipExtensionForVectorMULL</a>.</p>

</div>
</div>

### getPow2VectorType() {#a15f3027fdcad3b33960402d9739afe4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getPow2VectorType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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

<p>Widens the length of the given vector <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> up to the nearest power of 2 and returns that type.</p>

<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a79ea372f9aa69492fccfafc0e5a1589c">llvm::ElementCount::get</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a>, <a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a>, <a href="#a59eee3929b9155fd268e3e3f6c0efde9">isPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>.</p>

</div>
</div>

### getRawBits() {#a1ab39b6dd48de0a16afa90214d78b2c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">intptr_t llvm::EVT::getRawBits ()</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2319cb3270540dfd23ffd53d5a9bd8aa">llvm::SelectionDAG::getStridedLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4eeee43813ecf8dee2c4ccb837ec33b5">llvm::SelectionDAG::getStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a73d581dbc9d76b6c57f2f909d339c176">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa3052a5dfb8e3c218c92592ae46635a2">llvm::SelectionDAG::getVTList</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4cdeb5f52125a40eb8675eb60095e2ff">llvm::SelectionDAG::getVTList</a>.</p>

</div>
</div>

### getRISCVVectorTupleNumFields() {#a545976aff7ffb1bdec644f6ca5ddfc68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::EVT::getRISCVVectorTupleNumFields ()</td>
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

<p>Given a <a href="/web-llvm/docs/api/namespaces/llvm/riscv">RISCV</a> vector tuple type, return the num_fields.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Referenced by <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>.</p>

</div>
</div>

### getRoundIntegerType() {#a9cb27b88840e7d2d002f721594ec4578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getRoundIntegerType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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

<p>Rounds the bit-width of the given integer <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> up to the nearest power of two (and at least to eight), and returns the integer <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> with that number of bits.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a752372e170e4e7c595bf8810bb52adf2">getIntegerVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>, <a href="#af975bf04c49cc895cfe38e7dc126a2f1">isInteger</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>.</p>

</div>
</div>

### getScalarSizeInBits() {#a547a88964f1673c84410baa7a2a83f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::EVT::getScalarSizeInBits ()</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a> and <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a815d0ad0c6f04717c0dd61b12b44095b">llvm::AArch64TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac897a80df1070effb9d5a5b6a023c5d0">llvm::ARMTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae4847ee848f0f09e6e3bee5ab50c4430">areLoadedOffsetButOtherwiseSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6a1c71b7d20e3cf09cc8ff5a8efdb34f">canCombineShuffleToExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#ac8600b395666a2e54d6f347b58df6f62">canExpandVectorCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a415e74316c092fb208d6725d7ee4ff95">canLowerSRLToRoundingShiftForVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad300ebbb9f1787468bee5209194857ef">canonicalizeShuffleWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63b3ac6067f94151d39d197391477436">canReduceVMulWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af59e4da255e65a90b6c4710be399b9e6">combineAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6b1491b47f4868ea3e305573799a2561">combineBitOpWithMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abee0476f2cd1449e29bfca26702bd865">combineI8TruncStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada799c570dd41ead38f73ba71244c2b2">combineLogicBlendIntoConditionalNegate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a04f34c6d2aa331eb6fe9c1f1e52f2f9d">combineLogicBlendIntoPBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4b6e33228c180cdc5b3b927e63afcb92">combineOrXorWithSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad7019e6968b4004f00694d89e161625c">combineShiftAnd1ToBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7324b1333eec1b04ee358d58c42834ef">combineShiftLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#afa64cc7dfc401b9825b62c2b19808ad0">combineShiftToAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab5a426cb5c2105ca954c4ab9f12ef76f">combineShiftToMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a68b7af58bc3486a7e1a872337cee003f">combineTruncatedArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aac1c6dbf15b6867cf3e1d11b7a02c289">combineTruncOfSraSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#accd2edb7bf3dca29f9a0f5e233134d09">combineTruncSelectToSMaxUSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a45f59ac6b0a55fb1b92f4b3bfd5ce327">combineVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9f2e8d6c231138f3ab4c8f75eb240904">computeNumSignBitsBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aec59d76b8a13655705b0c55d99edf165">llvm::AArch64TargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aa9599760faf614e6274f8e5fd6f472fc">llvm::SystemZTargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa734719767b4f7faea1f7b40554f30be">llvm::X86TargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp/#ad378536508f0c71b730daf4da2026076">createBSWAPShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7eda61e02d6245a6cbc5ec5c09f1198a">createShuffleMaskFromVSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79354a2324d1cc1c1fd42e5d8a771479">llvm::createUnpackShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a482f0fad081b3094561d510c11335bfd">createVariablePermute</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aaef16aaed0ce790c381e75d7c9253f1e">llvm::X86TargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a5aaa4e25dcb7c49efaa3a2a5423a9416">llvm::XtensaTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aed133c19018de0508c5d71e802f36ef4">detectSSatSPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac3bb0fae6ff72b015a07fe80a33339c8">detectSSatUPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab27661a31d59b1d509386b1269369c62">detectUSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abc78591e933ad7d53f7fd4d8b9b4c096">detectUSatUPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01bdf0d462d6df94d15c1763169f4cf1">EmitVectorComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a0c43f88b7b733fa84bb93583d9163b54">expandVPFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2d63c559640ebacf58b26c51ffa5b358">foldAddSubMasked1</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6ff9876b9195d71118f24729147be47a">foldAddSubOfSignBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5f0becba6abfe541dd2df2475c52268f">foldAndToUsubsat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afd003bf0bf59d030e193b0772500ef66">foldBoolSelectToLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9940526e89938ffd29ad3135da3e2f7d">FoldIntToFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a99e3727e5ff5a1c45d0ee6dfb697308a">foldSubCtlzNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae0975a935b1b17c1591b86a7bbf8e692">foldVSelectToSignBitSplatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7266504e88c036bd48704ba439eababb">GeneratePerfectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab412ed28f090cbd85f13e2dbf3a52377">GeneratePerfectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a4809cfaa4940985ecc6dd5f78d24ffc4">generateSToVPermutedForVecShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1b134112bb3b8986d8082832a16eab6f">llvm::SelectionDAG::getAllOnesConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5dcb8d597c1066eec7ef713b758f78f4">llvm::ARMTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#afe02f4d6b04ada7f0864494bd23b83d7">llvm::GCNTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1713768600a9f5a62eb74a616aa73428">llvm::BuildVectorSDNode::getConstantRawBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6d7162a570369a85f2a5238452e196e3">getEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a7b2fcbe31b1e7a23ebe5be0c1e70343a">llvm::ARMTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a21d34e75ec9f5b42d39e85688a0f0d20">llvm::GCNTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a252df3516bdd18a47c638e745bcd01f4">llvm::AArch64TTIImpl::getPartialReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af17d33003beaf2d0bb09d7b2ac7984">llvm::SelectionDAG::getShiftAmountConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8a2567d305d0f9929660220a4d6f916a">llvm::SelectionDAG::getSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7b737b38b2728dacc7ed4fef24705d5f">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a444be9352256919a844309a35dffa0f8">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a958032a0f481716e224596f732f55d35">getTruncatedUSUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a201cec669c3caecff012ed5f2fe81c1e">getVectorShuffleOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02127bae19ef433c1233c696317a8868">llvm::SelectionDAG::getVPZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acaa6c3509bbddcd993aeec7334361c9d">llvm::AArch64TargetLowering::isComplexDeinterleavingOperationSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa8f55419227d2b25fcfca130f3f1dc63">llvm::ARMTargetLowering::isComplexDeinterleavingOperationSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1b7427c6c75d193f9899b8a2849ed8aa">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37f06b796addd745c44af4546b84fe76">isFNEG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a575fde9315284d194030bd1f0052d126">llvm::RISCVTargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9c9e38be1df7a70627fec8fa8a2eb42b">llvm::SelectionDAG::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3e9938aeee2aaef4ca5933920bb8c2af">isLegalBitRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8ffc0933141e7a87b1b1b2b474f576da">llvm::AMDGPUTargetLowering::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">llvm::ARMTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a67dbc70a08c8d7078e23f0a57a9ffbbe">llvm::RISCVTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae14323a03c6bd118c28baa4bf381e532">llvm::AMDGPUTargetLowering::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a1c7cb6b368ef7cba8da95f1f11ed4fc0">llvm::AArch64TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a779e5a75f5bf9f3672698656b56663fc">llvm::ARMTargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad228a0beee72778d8ea7dbd9de249158">isValidEGW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a27f76de53b5b15274dbf8e4f30adf81c">isVectorElementSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5ed6a1c7f9a09c16fc02c716d3f32f9">llvm::isVREVMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad34aa0262dce6014056d3d3be02682af">isVShiftLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad34aa0262dce6014056d3d3be02682af">isVShiftLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac25de93a27afbf8db3303c5f841075b6">isVShiftRImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03ce20d2138535663fed2e0fcc5ec604">isVShiftRImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6430d7837d2e985a3afc6e9c3d78c7dc">isVTRN_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a355dbd33acb5fd07a2b6418ba17051e3">isVTRNMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae4d5393f007c020e1bd59d37127b1904">isVUZP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8409a4a25c5001a552a5e21d4febadbb">isVUZPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d3f97d988494d78dc6ec1673b685bdc">isVZIP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a63cb14d47a8b27e0427f67087faa7152">isVZIPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a670137fe83c1213c3c2e82b8144e9af3">isWideDUPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c4d94b8b92e288f152e1f1d9e2598d">lower1BitShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ae213cc887b37c1743d66d2d9542a55c8">lowerBALLOTIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a25018debfdb73e1591f2fef057c92fc2">LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7701507d5a5024692d7dfe93a90df8c6">LowerCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a24cc4a1d21ea4653fdd760e2d7ae930e">llvm::AMDGPUTargetLowering::LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36623d79590f271aff0f88734e356708">LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99177f2de5b052f54f240d0299a06650">LowerEXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6b8a3bc9fb24fbb3d45971e84e42ce1b">LowerEXTRACT_VECTOR_ELT_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa9d588deb8a61aba4ae8f3e173df1229">LowerFP_TO_INT_SAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a0cfc0098376b7037c13877bea5659ebe">LowerINSERT_VECTOR_ELT_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a0b42f4e70f8b4f10a40e67d8540e9f31">lowerMSABitClearImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6b5025511ed198dfe7a49b67cf6d57ca">LowerVECTOR_SHUFFLEUsingMovs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ae4606620c1b4162cef84781678953b3f">lowerVectorBitClearImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a6b3401ff0fd3212bdf794979558b50c9">lowerVectorBitRevImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5a880b31811be9159307e8b14bf3acbc">lowerVectorBitSetImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a51359c8ddfa214a514dbaab1b2ad2d29">PerformBITCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a90b1ef73daf047e3bc666006c9e35a77">performBuildShuffleExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7054eb07a4962c7516115555800c017">performFpToIntCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d6307dece29d3f347afff0ba4f2c2cd">PerformMVEVMULLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae1413a27963c6b3bb1f370867e16b61e">performUADDVZextCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57a099df9c79ef37ef7f89374247ac0e">PerformVDUPLANECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99f918c3264972ed6aea09c675404952">PerformVSetCCToVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a036a964199eef5a0aab70732233b5e8d">performZExtDeinterleaveShuffleCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7da18013c41f68948709a964437238bf">performZExtUZPCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a36f078885862bc3b837dcfe057d05649">llvm::ARMTargetLowering::preferIncOfAddToSubOfNot</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a153c39776118fd1d5493774b10b9c5ae">SaturateWidenedDIVFIX</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a3156528a5f67da8543e7ef32f9218a79">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectRoundingVLShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2f569000b0bf158c11f67de0f6d308fe">selectUmullSmull</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aac3337c401bb0145fbecced8d947cebf">llvm::SelectionDAG::SplitEVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6f0cac8b7a7acd364d34649335444ceb">stripModuloOnShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70ab6e6fcc6015c6cdce1aa4497cd7f5">supportedVectorShiftWithImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6f5f3de82cbdb6a05c7f49ecf791382e">supportedVectorVarShift</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac3077960f12b940e1085e66a3eca06b4">visitORCommutative</a>.</p>

</div>
</div>

### getScalarStoreSize() {#a2648fd0c9417e0aeb3e8b194c6509357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::EVT::getScalarStoreSize ()</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a> and <a href="#a1572b31fadbd0d758314b8d35a050410">getStoreSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3de24662ee719e2c772575317d208116">matchIndexAsWiderOp</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### getScalarType() {#aa85c75e8eb097f02caeb5b9119eebfef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getScalarType ()</td>
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

<p>If this is a vector type, return the element type, otherwise return this.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="#a4e6e40b44c47abc845e297c30bbf830c">changeElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af59e4da255e65a90b6c4710be399b9e6">combineAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af2bbdc92f4c64587511d192d903ca743">combineMinMaxReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a68b7af58bc3486a7e1a872337cee003f">combineTruncatedArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac11671a35605d3033849a1e314831179">concatSubVectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79354a2324d1cc1c1fd42e5d8a771479">llvm::createUnpackShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1cecbf06f780c6264fc01c069fb04551">llvm::SITargetLowering::denormalsEnabledForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0841165650bd49aa4995c4dfa3fdf650">detectPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a781a75dfc661452760864c019bafd96e">foldShuffleOfConcatUndefs</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a646cdefda88e785573dffb15889de1d1">llvm::ARMTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad1ed10076dcd144800421886c7caea42">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a354aae224911d4dab66e34bfa10cf5d6">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a358de7df4d2c34f66bcce7dbe0253cd7">getEstimateRefinementSteps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acb8ed05f5ebe5a8e1b2805675e61a8db">getEstimateRefinementSteps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="#adf42d7b6a69dc15a64f841d51a9c93b7">getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a402c372a2886c19770de2cc65b41a7e0">llvm::X86TargetLowering::getNegatedExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa8ee36cbd5d910c4f4a1d899a109baf6">llvm::SITargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a70e999991e3aeb3052927df01099bf4c">getReciprocalOpName</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9ff4217411d6a24d497a1a0d504a86c8">llvm::SITargetLowering::getRegisterTypeForCallingConv</a>, <a href="#a547a88964f1673c84410baa7a2a83f4d">getScalarSizeInBits</a>, <a href="#a2648fd0c9417e0aeb3e8b194c6509357">getScalarStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#abd46b9ca1d156bc7e3dd9150cc106a28">llvm::SDValue::getScalarValueSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1aad91323f0a3814a7918d472e6e5bbb">llvm::SelectionDAG::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a43be1b9abf919e872b51cfd766dbe8ed">getVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af37fa82c85e811c7ed496ebcbacf99c8">llvm::SITargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acaa6c3509bbddcd993aeec7334361c9d">llvm::AArch64TargetLowering::isComplexDeinterleavingOperationSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa8f55419227d2b25fcfca130f3f1dc63">llvm::ARMTargetLowering::isComplexDeinterleavingOperationSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#afee5e52fd75b2906a16655fa264ee3d5">llvm::X86TargetLowering::isExtractVecEltCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa5bf9253e7424a041215974fc5696ac8">llvm::AArch64TargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a3e2659b4bac369ae2aa509712d6af245">llvm::LoongArchTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a9ae8be871dd199c4ba70bd599afb181b">llvm::RISCVTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a09d003869fdbb4295da2fe546c17a9ab">llvm::SITargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a85d61a5d0c2951b9e414a3a3112ad909">llvm::SystemZTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab5a3a214752cd4c83a68f99de65ad908">llvm::X86TargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4cb5f3e841a19c00cf078f9b65886e4e">llvm::AMDGPUTargetLowering::isFNegFree</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9f70fef2f29624d157355066a70fccb0">llvm::SITargetLowering::isFPExtFoldable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#acd2d8ceb743ffe76c8647eeba439fcdd">llvm::AMDGPUTargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acdb094fc50fe7940c520020f9008aa2f">llvm::RISCVTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a2548c54b76e921b3e1c0350002cf6fc1">llvm::RISCVTTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a755123fd18e5b8be4de7684fe173f21d">llvm::RISCVTTIImpl::isLegalMaskedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af295b67dfc09620609d22ba31761365e">llvm::RISCVTargetLowering::isLegalStridedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8ffc0933141e7a87b1b1b2b474f576da">llvm::AMDGPUTargetLowering::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aec5602ebffe4f185bb771a7ea328ad31">llvm::X86TargetLowering::isVectorLoadExtDesirable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6f6622d37de7bdbf2708835f57864a96">LowerCONCAT_VECTORS_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36623d79590f271aff0f88734e356708">LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b4d189fb624411d2c3e6d460da3796f">llvm::AMDGPUTargetLowering::lowerFEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a22aeb0a2fa8f9d75380e4a0df63afead">llvm::SITargetLowering::lowerFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa9d588deb8a61aba4ae8f3e173df1229">LowerFP_TO_INT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ac2a107ae57d52b3efb40096c179e270d">llvm::AMDGPUTargetLowering::LowerSIGN_EXTEND_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade7f9db31555260ac7d00622f0ddfff0">LowerTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1b11056f4136f56eaeb871857e5a53a2">LowerVECTOR_SHUFFLEUsingOneOff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab18e3739ef247af415be89a6d40fc20c">LowerVectorExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#aa55c0421a55a968b85f611e3124cb170">lowerVectorSplatImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ab283a383171c46fb4445cb64eb6b687a">llvm::ISD::matchBinaryPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af6fb44d5b8fabbbd624ebe34231c5ce6">llvm::SelectionDAG::matchBinOpReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6dba756ac7230f1732b09161ca525bdd">padEltsToUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a90b1ef73daf047e3bc666006c9e35a77">performBuildShuffleExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abf0bc161f51dbc01add0270eb00b2f77">PerformMinMaxFpToSatCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab049ba889709df922c683e1961c32ae9">llvm::AMDGPUTargetLowering::performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a273d2011b48b740db185cdcdf4decf76">llvm::AMDGPUTargetLowering::shouldCombineMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5cd2ddff46dc5822bcc7666e336da52b">llvm::X86TargetLowering::shouldFoldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4a6ec610f1626d7d5198a8d06e9eba18">llvm::AArch64TargetLowering::shouldRemoveRedundantExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a49dc5e9232eafe3ae3dab7b6f43f4711">llvm::RISCVTargetLowering::shouldScalarizeBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa74ba35350fae122acd7284555740ba5">llvm::X86TargetLowering::shouldScalarizeBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad6aad70f3c5691f093fdda1782dcc8d5">llvm::AMDGPUTargetLowering::ShouldShrinkFPConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a0cd03e62d1193e7b7e6562270356fdbb">simplifyDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac5670c01bc722932c40b06aaab52a0df">skipExtensionForVectorMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a>.</p>

</div>
</div>

### getSimpleVT() {#a6a81c1cc06a00a0096d839032b5984e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::EVT::getSimpleVT ()</td>
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

<p>Return the SimpleValueType held in the specified simple <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a589a475ec9e7607bfb645905d5170402">llvm::HexagonTargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac897a80df1070effb9d5a5b6a023c5d0">llvm::ARMTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8d6a68be38777fb05ac35c8ac8ec0535">llvm::HexagonTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#abe5fd0b5b59ac087ea3e1d91a4602766">llvm::MipsSETargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad5d9213c39b2fc64eaed3639539e8f65">llvm::PPCTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#a3359f38a412c6b9685e8fd39bd81b6a7">anonymous{DAGCombiner.cpp}::LoadedSlice::canMergeExpensiveCrossRegisterBankCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac1639f9e80414a665a5826e6e4ca6095">canonicalizeShuffleMaskWithHorizOp</a>, <a href="#a25eda78153285bc3bc4708e149b7e9e8">changeTypeToInteger</a>, <a href="#ad9d00ad929ec93255787f7f80c4659d9">changeVectorElementType</a>, <a href="#a0351571482fea42a3b326147fb2ce9e2">changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6d9136998f9ff100ad8449a69477ab94">combineScalarCTPOPToVCPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7094504ff72e8db0894faac2216aa00a">llvm::VETargetLowering::combineSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a482f0fad081b3094561d510c11335bfd">createVariablePermute</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1cecbf06f780c6264fc01c069fb04551">llvm::SITargetLowering::denormalsEnabledForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#ac9784ca12ba090d5ab2924df8f535a86">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#a7fbc8a0e79b77a4eec73dceef97127a4">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a1f580ab00002a65787ab52ef2aa9a439">foldFCmpToFPClassTest</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f80d4b8b70f58b247193379a39d5541">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae70ddddbfd05ed5831918fa1836b947">llvm::AArch64TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80ea223c590adb7c6fddc635804401c6">llvm::TargetLoweringBase::getAtomicLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a646cdefda88e785573dffb15889de1d1">llvm::ARMTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a8728267f1d12f3c91b61da0187e4be7d">llvm::X86TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a45b557c1f3f224d01fc38c055ced3c58">llvm::AArch64TTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a10930c52b74a578790352742b8139389">getContainerForFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4f87d8844454c664483111762bd8dab7">getExtensionTo64Bits</a>, <a href="#adf42d7b6a69dc15a64f841d51a9c93b7">getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a5d1ff741add38ce427dcd488424274fe">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getHvxTy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#a5d963dea45bb93b0a3dce47d04d1b959">getLdStRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9fd228909f3f1a59c6ef7d15c3547b61">llvm::TargetLoweringBase::getLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af7966eae031882124c0beee58c4c922e">llvm::TargetLoweringBase::getOperationAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a468ab481eae62623c2ef12e743b420b5">getPackedSVEVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a391ef092ff421faccdfef4cb88424742">llvm::HexagonTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a68a18462f9529b0e75812794eeedbb5f">getPredicateForFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#a1d2667ec9f866e346e4bd6b85380bf67">llvm::SPIRVTargetLowering::getPreferredSwitchConditionType</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5997c4992589047ebc712b52b6e101cb">llvm::FastISel::getRegForGEPIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5cec24eb4eadf1232a1463fdbb1cc1a0">llvm::FastISel::getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3f52b55c29541c64f2af910d479579f5">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9ff4217411d6a24d497a1a0d504a86c8">llvm::SITargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae93a1ba51c086441ec1b9ea4cdca853a">llvm::X86TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada7f52028e75ee798b0fbbde2445b95e">getShuffleScalarElt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7a6096cff14db41b299758115c6e261c">llvm::SDNode::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#acbcc973a299b6f8733774668210b5227">llvm::SDValue::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a795c61cf1031636a1f7d90056da39afc">llvm::TargetLoweringBase::getSimpleValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a005211a6c7f26317af98d088c06f0f64">llvm::AArch64TTIImpl::getSpliceCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2b15e3bc244c5fde8d06c39e9fc7ef6d">getSVEContainerType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a924b8ce261b7b394b47b82a07cd2456a">llvm::TargetLoweringBase::getTruncStoreAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7c335b50ec450e5955b50d2ea468ea78">getVectorLoweringShape</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a3ad6b42504c45aad0f8a9787bdede7ed">getVectorTyFromPredicateVector</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21321ab7669a253fc0fe731602fe5695">llvm::MipsTargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af37fa82c85e811c7ed496ebcbacf99c8">llvm::SITargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg/#af17961fd0d980900eff4cef28e965418">llvm::ISD::InputArg::InputArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad46bc4ab207e93c35b24f708aa24cf0b">is32Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abcc89aad99c6a03adb5443eb5fa9f93c">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aec601d177f33c89713cff3857f97aa77">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a607229211531af1259b2603df68033f0">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5961d8a9524e219b55d22dc9e43e15af">llvm::HexagonTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa5bf9253e7424a041215974fc5696ac8">llvm::AArch64TargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a3e2659b4bac369ae2aa509712d6af245">llvm::LoongArchTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a9ae8be871dd199c4ba70bd599afb181b">llvm::RISCVTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a09d003869fdbb4295da2fe546c17a9ab">llvm::SITargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a85d61a5d0c2951b9e414a3a3112ad909">llvm::SystemZTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab5a3a214752cd4c83a68f99de65ad908">llvm::X86TargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a350cbdd9ddbb2a048799fca9d93f3993">llvm::ARMTargetLowering::isFNegFree</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a90186243528cfcd7b02837f130da5de2">llvm::PPCTargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a40892ab1e0ab2dcb208fdedac55ebd2b">llvm::HexagonSubtarget::isHVXVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab57d04d7949ffdf008c6a2e222ebbe43">llvm::TargetLoweringBase::isIndexedLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a623aec2b1908acf20c615e16a870cc8b">llvm::TargetLoweringBase::isIndexedMaskedLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acc21c72422f4757e0d633c2f380abde6">llvm::TargetLoweringBase::isIndexedMaskedStoreLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0fd231e43d25de7b9d908c140a5a29f0">llvm::TargetLoweringBase::isIndexedStoreLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad09933ec95486d26cd31cf1536190091">isLegalAddressImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a14ba388c0893657958340f94a164faa9">llvm::ARMTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abd6384b6c46252ca57f5d73b5ffd8076">llvm::RISCVTargetLowering::isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acdb094fc50fe7940c520020f9008aa2f">llvm::RISCVTargetLowering::isLegalInterleavedAccessType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad10f4d741391b254c1f27c389d7546dd">isLegalT1AddressImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a81f0b427ff9a532ec2b6bf98c132db26">isLegalT2AddressImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a1b478e338eb3e2c6ab20ac7462896c58">llvm::ARMTargetLowering::isLegalT2ScaledAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a460fe5aea074c37615e0106c2a13a1e4">llvm::TargetLoweringBase::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aa9f61dd4cf5e9bdff7ab3e0ccd9b49e1">llvm::RISCVTargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9fdafe65d9378c70d936af1019040b0f">llvm::X86TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp/#a52ecad9ffa97dab239dbfc607c4a1738">isSupportedType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ad8a821e221b81ea4fa8dc4653072ff1c">llvm::HexagonTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a67dabd2d424cff174a83b5681f1dc6b5">llvm::HexagonInstrInfo::isValidAutoIncImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430iseldagtodag-cpp/#a3794e51a3fc8f833622d1b8f142ff5b9">isValidIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8d59d0a2b9e117e74cd61f315aabf247">llvm::ARMTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adda85bdff9375435866fa2bebaca4b27">llvm::X86TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a0f5ccdafc0c37296755f59436f277115">llvm::XCoreTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6512c9219b1c585d57adf5bbf276cba6">LowerADDSUBSAT</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6f6622d37de7bdbf2708835f57864a96">LowerCONCAT_VECTORS_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36623d79590f271aff0f88734e356708">LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aafc2949271a07751ceab94ce5e91f9ca">lowerRegToMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a946850e76d96e9deaab8c5053a86f02b">llvm::HexagonTargetLowering::LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1f71843f178d1cbe0f1bd95af528c46">lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a15ae77c55dfbf20a719b9851d73d1900">NarrowVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/widenvector/#a1c7d0aa7f38f624303070d06ad7b3736">anonymous{AArch64ISelDAGToDAG.cpp}::WidenVector::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae1413a27963c6b3bb1f370867e16b61e">performUADDVZextCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a00eceab7a08d0acc74a729ebd9660475">llvm::SITargetLowering::PostISelFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionimpl/#a2ff692eefcb74ae2bbd96ff5f9241287">anonymous{TypePromotion.cpp}::TypePromotionImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac399325c88de95b03c19e68e1229a8f7">llvm::FastISel::selectBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aedd7b25487ab7f0871e3d722c1766c18">llvm::FastISel::selectBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a59ec796e4ddba85e210d5a226d56f16f">llvm::FastISel::selectCast</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a6420a6b27b9be369ca91fcdf54051ad0">llvm::HexagonDAGToDAGISel::SelectExtractSubvector</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ab4355a6f0290136cbba4b0b1a0617914">llvm::HvxSelector::selectExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1434fc5d1782f15a392af0320f13f6c7">llvm::FastISel::selectExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9b79346e8152f683a6ad35f8049c74ea">llvm::FastISel::selectFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5718bb42ac48e382b259cd668ad38e21">llvm::FastISel::selectFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a5ed109e1cb014423460d747d1bad657c">llvm::HexagonDAGToDAGISel::SelectIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#af4925542ba74593f756efe144083d031">llvm::HexagonDAGToDAGISel::SelectIndexedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ae39c938299ddc0dc8534e1a05cb0c2fc">llvm::ARMTargetLowering::shouldConvertFpToSat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a0b23f096c92f38f9001ae3ea9ddc8dde">llvm::RISCVTargetLowering::shouldConvertFpToSat</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a72ba34ed2a0e75181bfecf7d463156f8">llvm::X86InstrInfo::shouldScheduleLoadsNear</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a68dfe495fc0800bc00b676bae53711bc">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryTLSXFormLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a8ea966a78e9df2ec2b419272c293d000">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryTLSXFormStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#af586c31be6208a365b50ac3a892be6d7">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad96e48f13961854d2242e9462a920394">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a448318fedd7b77f12f1163c8d5a5b10a">unpackFromRegLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9b97177f4c89df3fd0a2f05deec3378f">usePartialVectorLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a31f9f0db1bb0b321286db70b58fb001e">llvm::SelectionDAGBuilder::visitBitTestHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae138473fc11097221f02e42677663dc">WidenVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a1eee6ac4842ce6fca9bdd513b73eb003">X86ChooseCmpImmediateOpcode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a8a37b9d5aa1120121a9f73dfc2e302ba">X86ChooseCmpOpcode</a>.</p>

</div>
</div>

### getSizeInBits() {#a45e76d44a189e456d52e37ba3dda0fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::EVT::getSizeInBits ()</td>
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

<p>Return the size of the specified value type in bits.</p>


<p>If the value type is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a0aa60141f3fc64eccae5554fa3eb6426">AddRequiredExtensionForVMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#acca525d32f859c8c653921b5fff62ed3">llvm::X86TargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae8d8a343d3ada0387181b0ce2b470b91">llvm::SITargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5843fbc0765c997fa4bf9b6d876891b6">allUsesTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a776d43d877fa5cb4d75783e63990cc58">llvm::SelectionDAG::areNonVolatileConsecutiveLoads</a>, <a href="#aad0b781d8b8a804437e919429069fcd7">bitsEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#a0884e3469837e8ef87a3a989096f0809">BuildVectorFromScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a40bdcac44bd6d189cc6b65984baf3303">llvm::AArch64TargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad4d6848e5070beeb8a9d0a8711ecd671">llvm::ARMTargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a4b4e2a3ad3e7b2eeac3b96951d2746df">llvm::R600TargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac9c871c7f1222d14e8f90aca6f4c71f3">llvm::SITargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a66a0f33d36e31ddfbd254a77524f9192">llvm::X86TargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac1639f9e80414a665a5826e6e4ca6095">canonicalizeShuffleMaskWithHorizOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab51eccb824edbda20ca098e164d9779b">checkZExtBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e8360ec6c03540a7ad4753613cfc66f">collectConcatOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaab5068203f7eda4cf8a53182aae5cdd">combineAddOfBooleanXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e3e38f27d866ed7730e8e30fc3877cf">combineAddOfPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c3d86d724323d88d2fdf99d29d3de72">combineBasicSADPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0e0d5fc4a01d9f412064a5448052330">combineBEXTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6b1491b47f4868ea3e305573799a2561">combineBitOpWithMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1b64f17c84bc615a735f48746a0740">combineBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a670c95cba653503ce21f4abeea37cd2f">combineConcatVectorOfExtracts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5a87447416046730b266c20001561df4">combineDeMorganOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad2800cb88996291ed1676f5899997ebe">combineExtSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abee0476f2cd1449e29bfca26702bd865">combineI8TruncStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af2bbdc92f4c64587511d192d903ca743">combineMinMaxReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af72da135a7e8a925ffa9fbbb4ecf0b1f">combinePredicateReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac1953eca2805574de12debdab3116430">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab73df8541f091c30ed34fd2c89c57746">combineShiftToPMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0cccf679aa7f34055f858474bf8bdcdf">combineSignExtendInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5efc2b9d3d3b40b85f5f7366bc145837">combineSubShiftToOrcB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2cc720ee13ee570307048e7940784be">combineToFPTruncExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a57f2ddafb29f40fe83f17e93300e1a71">combineVectorSizedSetCCEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9ac1db32c7172ebb71d45a6ece209b53">combineVEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8389740010ccf99686a066f0bdc4dbdc">combineVPDPBUSDPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aab7406f11829e7505acce1a7d4a7803d">combineX86ShuffleChainWithExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac11671a35605d3033849a1e314831179">concatSubVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae9b6e09822fd0b670d93487058bea45">ConstantBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5bd62ec61571d2805d0d609d279a3e3e">constructDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#acab5bf267b2b761c038dd0976779a5e9">constructRetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a009e2b4ee04eedc57c666678f3e8ef1b">convertIntLogicToFPLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05e32f779d033fe0757134346ba52aa2">createPSADBW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79354a2324d1cc1c1fd42e5d8a771479">llvm::createUnpackShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a4b9031dbdb100545e0f3a0c0b11efe03">llvm::LoongArchTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a4608dc92a33ef6d74921a28eaa20140d">llvm::RISCVTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a5aaa4e25dcb7c49efaa3a2a5423a9416">llvm::XtensaTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01bdf0d462d6df94d15c1763169f4cf1">EmitVectorComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af06754acf6dbda0709a6cda0b11cdab5">Expand64BitShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aecabf0b51b7f3a579c05fc08e06c265a">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d2572a2d7cf0d8584f28c2c1c2e14c8">extractSubVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ab5de88dc9568b784876478e316042ba6">llvm::SwitchCG::SwitchLowering::findBitTestClusters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#adeba9ee43ee94300c5bb47b99b47a945">findMemType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad191ffcc7522367aaecb263b8d149717">foldExtendedSignBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa8e7d7856b86905a5ce055fb23d0c9b2">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a974687eecfd14705774360c10e1c731a">foldXorTruncShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7266504e88c036bd48704ba439eababb">GeneratePerfectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07cdd12114b2452d5dc26ab23460bb60">GenerateTBL</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a646cdefda88e785573dffb15889de1d1">llvm::ARMTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3aa26bcaab679f3bc76dfdf06e929b73">llvm::SelectionDAG::getElementCount</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6d7162a570369a85f2a5238452e196e3">getEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ad8dd87df6641e5698b9af97fd574b186">llvm::ARMTTIImpl::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4f87d8844454c664483111762bd8dab7">getExtensionTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae94d01adfba8b1a65f781ecd925111ea">getExtFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="#a7712dd4392b7eb944b709ac8442634d9">getFixedSizeInBits</a>, <a href="#a587873e0de35da196d3f5fa6d60f738c">getHalfSizedIntegerVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8c620fc470731fdb2a41678c294a1e6c">getHorizDemandedElts</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a5d1ff741add38ce427dcd488424274fe">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getHvxTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a8ff39e7e0c390fbc8db3e7e10748c466">getLeftShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a0f49cd7f0f28bd9b7aaed4b5a0df02d6">getLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4cbc62bcd4117c7767755022e0ef6a8a">llvm::ARMTTIImpl::getMulAccReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">llvm::MipsTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa8ee36cbd5d910c4f4a1d899a109baf6">llvm::SITargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#a9869cb9330f243cad6d20c176de62d19">llvm::SPIRVTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a458b41b670c695bfe6c37217b7007c">getOnesVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a68a18462f9529b0e75812794eeedbb5f">getPredicateForFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab40e47d665eb61ef848654a1d6526f7d">llvm::X86TargetLowering::getPreferredSwitchConditionType</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a04c394dca43220a262f8a67825cd4fb5">llvm::MipsTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9ff4217411d6a24d497a1a0d504a86c8">llvm::SITargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a0b74111574af484ef33597940f5e9c56">llvm::SystemZTargetLowering::getRegisterTypeForCallingConv</a>, <a href="#a9cb27b88840e7d2d002f721594ec4578">getRoundIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a770ff017bd46a0f9737ad642fe0ab5e1">llvm::XtensaTargetLowering::getScalarShiftAmountTy</a>, <a href="#a547a88964f1673c84410baa7a2a83f4d">getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6a2579bc0354806c6c9708b068777c3a">llvm::TargetLoweringBase::getShiftAmountTy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="#a1572b31fadbd0d758314b8d35a050410">getStoreSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0b1f78ee0016593bc78e5a7d926ee668">llvm::AMDGPUTargetLowering::getTypeForExtReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a940aa5c3b3202d4d987e2a999450f240">llvm::MipsTargetLowering::getTypeForExtReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a75de6a9cc37e7d0a70e488ad3c4159c7">llvm::SDNode::getValueSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a8915297f72f1020167562805827f7160">llvm::SDValue::getValueSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab3d70bf3dae5a7c20d3a0ff4fc67a000">llvm::X86TTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7c335b50ec450e5955b50d2ea468ea78">getVectorLoweringShape</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac477f229337de92be9c48dae99bf5546">llvm::AArch64TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af37fa82c85e811c7ed496ebcbacf99c8">llvm::SITargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1e362f3699fd2c3f46c7a3690031dda3">llvm::SelectionDAG::getVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa69a30633eb175372a93a42bfc5d89f2">llvm::AArch64TargetLowering::hasAndNot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a69fbe6a7969fadd37ebea537ba3041e3">llvm::X86TargetLowering::hasAndNot</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acb51326eb72adb30e442667892c1f5ae">llvm::AArch64TargetLowering::hasPairedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7cb0f27acb965339dde328392c1adaf7">insertSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a18f51ef21d273b6674761593a311b6f4">isBitfieldDstMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4b1f6c2a4e7b3aed4f56643d545f305b">isBitfieldExtractOpFromAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a04d8bec5e4e1e6af669b1a018363b8b4">isBitfieldExtractOpFromSExtInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aaf4b732e582e80caaceee1ed402180b8">isBitfieldExtractOpFromShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2db2cea3a0eb5d8ddb8a14e64eb86a0b">isBitfieldPositioningOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aaa913771ef6203d3911e1284ca0bcd5f">isBitfieldPositioningOpFromAnd</a>, <a href="#a470621733f1ffb597e6f502040216da4">isByteSized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a016f7b15a2e335153beb2421ac622ce5">isConcatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7d9494014ff9dbd992928542dee2e477">isConsecutiveLSLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aaae643b7e80395e0c51c7bc29912f31d">isExtendedFrom16Bits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a0b3bbcd8728609a52e420775a7f7cf">llvm::RISCVTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab75bfa0d750449f745ed10dba2f81e31">llvm::X86TargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#abc42cb694d5b2c6b2b7daf8f2cb4411e">llvm::SITargetLowering::isExtractVecEltCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a40892ab1e0ab2dcb208fdedac55ebd2b">llvm::HexagonSubtarget::isHVXVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a8361d68123c66f4a7915b1dd3fc337b4">isI24</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a81f0b427ff9a532ec2b6bf98c132db26">isLegalT2AddressImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8ffc0933141e7a87b1b1b2b474f576da">llvm::AMDGPUTargetLowering::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a78b1cfe835bfe405897b9b75cf17fb">llvm::X86TargetLowering::isMemoryAccessFast</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae14323a03c6bd118c28baa4bf381e532">llvm::AMDGPUTargetLowering::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad0581b9db1cc9ac63ca3c7eb944d4fd8">isPackedVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a36eb7d7a2391433da8399b0c2fb9b56e">isPerfectIncrement</a>, <a href="#ab41e50273c70287914ded0ae668bc507">isRound</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a1c7cb6b368ef7cba8da95f1f11ed4fc0">llvm::AArch64TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2ed8040b1178ab7333dc69161e2b09b6">llvm::AMDGPUTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a1f7dae0343b89773eaaea832fc9f3ae5">llvm::ARMTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#af075f198cd750d859857bb7b87544931">llvm::PPCTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a8aa9bbddf3b01dca458a497c72348b78">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a731fed7d3e9a9ebe3a9940afd6a3bdc2">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6cc2cb7b5433e21565a41f6154b7c816">llvm::X86TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a768562b4668773f96f4ac2d425a5d547">isUnpackedVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a67dabd2d424cff174a83b5681f1dc6b5">llvm::HexagonInstrInfo::isValidAutoIncImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad228a0beee72778d8ea7dbd9de249158">isValidEGW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a27f76de53b5b15274dbf8e4f30adf81c">isVectorElementSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a670137fe83c1213c3c2e82b8144e9af3">isWideDUPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#af20b4c8887374431df7cafec53a124bb">isWorthFoldingIntoOrrWithShift</a>, <a href="#ae2ee94a616a11388828c36d1e0b4798c">isZeroSized</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a02e65e6f505c44832bf833b385e51ba6">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac7b70a67bb5d182866c5485835286509">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aea8c2b718c1dd866d61c29081c1eb44f">llvm::RISCVTargetLowering::joinRegisterPartsIntoValue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aa4063a2a697fa5c8713c86cd2cbcd46c">llvm::SystemZTargetLowering::joinRegisterPartsIntoValue</a>, <a href="#ab9182379fc7c4d4b8031f1a81221fafd">knownBitsGE</a>, <a href="#a510d9e3eba90bc4a7e9925583fbccc3b">knownBitsGT</a>, <a href="#a1cd3e03c399e181366f177964eaae62b">knownBitsLE</a>, <a href="#a7bcabb100313dd886a3b9ce7b599337c">knownBitsLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab733cc9ef2c6f6e0872469b0ba899483">lowerAddSubToHorizontalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13428801d19f40af7da16a16d76329fb">llvm::AMDGPUTargetLowering::LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6f30e11353716cf175b1fb59b11cb6f4">llvm::AMDGPUTargetLowering::LowerDIVREM24</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#af8cb1a782bf62a812f68aac1af065a5e">llvm::MipsTargetLowering::lowerLOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa32a8c1fba431700b7564e94ea5ab4d2">LowerPredicateLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aedabf4c69af716c22c9957d6ca5758e1">LowerPredicateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8a3f7047284d9a1811eb22bd8b86c898">llvm::HexagonTargetLowering::LowerSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a5c19ca49e4455ef4a1ae64c7ef6dc587">llvm::LanaiTargetLowering::LowerSHL_PARTS</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8308bacd5a1d10fdc7ac14c784f6ce0d">llvm::MipsTargetLowering::lowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aec76b73c15365e949f7322e371e6471b">llvm::AMDGPUTargetLowering::LowerUDIVREM64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#ae1416413e8b25024ca51882c2e1cd4db">LowerVAARG</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a3fd074728d9823c0dd39e25d08fffe00">llvm::VETargetLowering::lowerVAARG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#aa55c0421a55a968b85f611e3124cb170">lowerVectorSplatImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611391ccebf150b7064f586835d388d3">lowerX86CmpEqZeroToCtlzSrl</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#abc928b96601086c4735b9ea8331f0b9f">llvm::ARMTargetLowering::LowerXConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#ab268a162e6da94b8012d8366563ae9f7">MatchingStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac76473b9005e8953bfde5975fc7d2eca">matchTruncateWithPACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0da6ddfc44f329add717e0ac64b0b54d">llvm::ARMTTIImpl::maybeLoweredToCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a06205ea56e17027e23e321056e351c58">NormalizeBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ace90a1ae5966f6c7a0830a440698d4c5">performBITREVERSECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaece9d12c539bbab91aff76ea7e95096">PerformInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afa4334801ad99c95a1b5fd0f417e16af">performInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7b49e80a5c71aff0a4a6d6a637cafe3f">performLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab049ba889709df922c683e1961c32ae9">llvm::AMDGPUTargetLowering::performMulCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a09d46d8519c83130e03376d0d2e0008a">llvm::AMDGPUTargetLowering::performMulhuCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ada4201742fab8916f9da75acd2b58fc1">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5c12d92b2d9e291ad311d1468da07410">performVectorCompareAndMaskUnaryOpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2c166ebb81953ce2aa531c18213e0011">reduceBuildVecToShuffleWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0670f21ebeafbaab3f4b34c8140b8dc8">replaceZeroVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5f4f153e2f8d9dd1c45d089ea3c7499f">resolveBuildVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abe588c29e26c909dcffe4c763aacaffe">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a0e48eed8c71f1e31ececec593aa98908">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9b79346e8152f683a6ad35f8049c74ea">llvm::FastISel::selectFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a5ed109e1cb014423460d747d1bad657c">llvm::HexagonDAGToDAGISel::SelectIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#af4925542ba74593f756efe144083d031">llvm::HexagonDAGToDAGISel::SelectIndexedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9208ba235fd513181d17277332f9bde2">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a87024e3cd8e787fed3e17063882847aa">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a7e3d9cf3f95460906ecb45fd30a3c6e5">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af52e44fa59b89ae4c520c10a6de3eb4d">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostStoreLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af03e0b9fbf705b2a8ecf9b5b44597ff9">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a5984d3a5a8969d8d3238c4eaea8e4835">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectStoreLane</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#ac8a9940ba807ee771ad949f2ab9e8bea">llvm::LoongArchDAGToDAGISel::selectVSplatUimmInvPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a1a4e02c3247bc8b4134b91e707d6c146">llvm::LoongArchDAGToDAGISel::selectVSplatUimmPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8272c4da36b8d295addf73f56c548155">llvm::SITargetLowering::shouldExpandVectorDynExt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa03cec0d3e2e816167f41ac37995f274">llvm::AArch64TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0409fb04e071cd7a523f022dffec2a3">SplitOpsAndApply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a6b741ae800a442b04981541b9c8b326a">llvm::SystemZTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8b77cecfc2091e2d9c9116ca578983e2">splitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aca53f243b0008543a30a78356ac59010">llvm::AArch64TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a91b6b0ccb484e79d3d1558e8d9c12cd8">tryAdvSIMDModImm321s</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52b49fd007d3e59011c1e924579f3a80">tryAdvSIMDModImm64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a55e427e6bf5d495e92fbbe9ba86e9990">tryAdvSIMDModImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41506ddab8a425491f9ebf969036eb84">tryAdvSIMDModImmFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab9e3068f5d58302b996d7e3be3babd3f">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryBitfieldExtractOpFromSExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ad20f6dc8f2338b85fb4092df26df1b1e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryBitfieldInsertInZeroOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a380449a9ad9e4e2d3b6b3fdfa75a64d9">tryBitfieldInsertOpFromOrAndImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5956dd38d2c4e11a90da91035b52096d">tryDemorganOfBooleanCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa8d333c2eb8d0346da6128f38cf941b5">TryMULWIDECombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af415da4daf8365b80a0f0dba2ee8490e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastFixedLengthToScalableVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac490424228331c1beb5025ef6d45d2a6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastScalableToFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae234b678192f5c7be49f8507bcce5936">tryToFoldExtOfAtomicLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#ae809b55a75992a119dd6441aaeabd49b">UnpackFromArgumentSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a57e07229bb762532f34ea34c656dc6eb">unrollVectorShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab30bbf3bcf699a32f7113173b5cee991">llvm::AArch64TargetLowering::verifyTargetSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a31f9f0db1bb0b321286db70b58fb001e">llvm::SelectionDAGBuilder::visitBitTestHeader</a>, <a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ab9c026bf7b5362d2b79a43bd04e769a7">widenVec</a>.</p>

</div>
</div>

### getStoreSize() {#a1572b31fadbd0d758314b8d35a050410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::EVT::getStoreSize ()</td>
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

<p>Return the number of bytes overwritten by a store of the specified value type.</p>


<p>If the value type is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#aae881b014fee000d713159f7464f860e">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::add</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a815d0ad0c6f04717c0dd61b12b44095b">llvm::AArch64TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a25d4d29a2e8f87e039add92fe76ef88c">llvm::RISCVTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a168f3532cb1605bbc91fcc079892e357">llvm::X86TargetLowering::BuildFILD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af412df17add838f012f81de13961060c">calculateSrcByte</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a5e0048496768e682947aedca8e3aa3d9">CalculateStackSlotAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aacd7e508c9e6dd17afc738da27b87bc2">CalculateStackSlotSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a42ca2573c85e6aa37315472c556116d1">CanMergeParamLoadStoresStartingAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3de9644ea2dd81453acf760bd2c1f921">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8bf72f690d62d0f26a984b9cbe96f37e">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a564ffef4d327c872fe912322813e6a2f">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab847f1d70cf17cd2250d78d4bb19ec4e">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab7458c4c1d0b716494b03ba16ee86ad2">getParamsForOneTrueMaskedElt</a>, <a href="#a2648fd0c9417e0aeb3e8b194c6509357">getScalarStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="#a5f64c589a5312630fe76a37f62a39707">getStoreSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a3f04233ae02eabefa03b17d72ff73601">llvm::PPCTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8063c77c39146c0790e66f5e0679475c">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf715e866131db937a292ab35643ca0c">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6dfe0c9c0080f43b8e889d93c3248b3b">getVPermMask</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a2548c54b76e921b3e1c0350002cf6fc1">llvm::RISCVTTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a755123fd18e5b8be4de7684fe173f21d">llvm::RISCVTTIImpl::isLegalMaskedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af295b67dfc09620609d22ba31761365e">llvm::RISCVTargetLowering::isLegalStridedLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a176c5cbd80b59d908680911c34fdde6f">isOnlyUsedByStores</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9c10e3651139ad6ec8af95a7b7fb152d">llvm::AMDGPUTargetLowering::loadStackInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a94ec50da525b52281c1d4bbde196c520">llvm::MSP430TargetLowering::LowerRETURNADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a00a2cd9501aed5f7e8746c0458990503">llvm::MemSDNode::MemSDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697277613cca131c099969ca5d421041">llvm::SITargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a273d2011b48b740db185cdcdf4decf76">llvm::AMDGPUTargetLowering::shouldCombineMemoryType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0bd751c4c85d494e52e578b6bc10f8bc">llvm::AMDGPUTargetLowering::SplitVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aad3b6954334c350e17f08d707e1f102f">llvm::AMDGPUTargetLowering::SplitVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6e73a48328462ff271d3a9bb6c4694af">splitVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7298635e3ff67acc13c250c5cefb0a05">unpackFromMemLoc</a>.</p>

</div>
</div>

### getStoreSizeInBits() {#a5f64c589a5312630fe76a37f62a39707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::EVT::getStoreSizeInBits ()</td>
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

<p>Return the number of bits overwritten by a store of the specified value type.</p>


<p>If the value type is a scalable vector type, the scalable property will be set and the runtime size will be a positive integer multiple of the base size.</p>


<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a1572b31fadbd0d758314b8d35a050410">getStoreSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae63d3420be279c225fb7bad70c0b8046">combineBoolVectorAndTruncateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa1cac5332a31f59e2455eaad0fb11278">llvm::AMDGPUTargetLowering::getEquivalentMemType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9131ae18383241b54e466cf623a7312b">llvm::AMDGPUTargetLowering::shouldReduceLoadWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>.</p>

</div>
</div>

### getTypeForEVT() {#ab0cfceeb37508e56f9c127e59766a668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * EVT::getTypeForEVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method returns an LLVM type corresponding to the specified <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>.</p>


<p>getTypeForEVT - This method returns an LLVM type corresponding to the specified <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>.</p>


<p>For integer types, this returns an unsigned type. Note that this will abort for types that cannot be represented.</p>


<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/targetexttype/#a4807dd672ac18ce59733b41885eff1be">llvm::TargetExtType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a28fdf240b8220065bc60d6d1b1a2f174">llvm::Type::getMetadataTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a18e4e0af5b02a410a87c9cdbcd1423b6">llvm::Type::getWasm_ExternrefTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#adc56186d80974cb7f4928e9f0abf8904">llvm::Type::getWasm_FuncrefTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a08ceb864464bce07aed4387d665f6565">llvm::Type::getX86_AMXTy</a> and <a href="#abda309a31acb43c06215c1772727bf1c">isExtended</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4acc56660c01a31efea93dc0e9ea8ad">llvm::TargetLoweringBase::allowsMemoryAccessForAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a631357f1796c922cce73dae4bff6018f">canFoldInAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3de9644ea2dd81453acf760bd2c1f921">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8bf72f690d62d0f26a984b9cbe96f37e">llvm::SelectionDAG::CreateStackTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ebd0350b058932668b0e22ca723cf5b">llvm::SelectionDAG::expandVAArg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a42466c49bccd4a1295c6aedb623ab072">llvm::RISCVTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a38dd0562fe8267823b87ef5c3bacc264">llvm::AArch64TTIImpl::getArithmeticReductionCostSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a6212e41633990ea795daea7917312bdf">llvm::RISCVTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8fb36df786ff6728049d25647092c350">getDivRemArgList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a467226658bbb3854ea3e1f625a73a128">llvm::SelectionDAG::getEVTAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#adb7e05c95393c231260785fc1ce4700b">llvm::AArch64TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a16a2910025aeadfd52f381a78f92faf0">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getNumberOfParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a531405bfbd93bc7c3464eea0d9144774">getPrefTypeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a531405bfbd93bc7c3464eea0d9144774">getPrefTypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a017a91fde9e329082de784114d8f137c">llvm::SelectionDAG::getReducedAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#aba994389c740a90705e8995aa61e609e">llvm::CallLowering::getReturnInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a005211a6c7f26317af98d088c06f0f64">llvm::AArch64TTIImpl::getSpliceCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad357707a4ab97832b2f9ad24490b4376">llvm::PPCTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a525e9355bccd735cf648afbde45acfc5">llvm::SparcTargetLowering::LowerF128_LibCallArg</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a54af997c0e800a9cdfb65dabe296f7c4">llvm::SystemZTargetLowering::makeExternalCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697277613cca131c099969ca5d421041">llvm::SITargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### getVectorElementCount() {#a3d102abca1c9c95f36546dff2f39273b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::EVT::getVectorElementCount ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad45a536ce828d7fe0a889a1666437654">combineConcatVectorOfCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#afa64cc7dfc401b9825b62c2b19808ad0">combineShiftToAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a41d90ad30eef03eda7c41e46c1839ded">foldExtendVectorInregToExtendOfSubvector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae968aa14d25b7b04bf82019ad48f599c">llvm::SelectionDAG::GetDependentSplitDestVTs</a>, <a href="#a3f78e3bf25a5e4bef300d42dde0d8477">getDoubleNumVectorElementsVT</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="#aee35a362966ced72913881d8a2dc3be8">getHalfNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0d2d9c6df58f2916c90d15bc635d871f">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3f4445d350e1253b4c05ab25011d766d">llvm::AArch64TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a7c14a3a22d127469c3490092627c2368">getPackedVectorTypeFromPredicateType</a>, <a href="#a15f3027fdcad3b33960402d9739afe4b">getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0f1ad23af20c2a0b3e3f5c0a995c1969">llvm::AArch64TargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4fce00050967f2d8237319f1912a0103">llvm::AArch64TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a667a905e2496f6b0b9c7915a97f58da1">llvm::ARMTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6cf51cce9a6839a2849aeadcc0312d31">llvm::RISCVTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae93a1ba51c086441ec1b9ea4cdca853a">llvm::X86TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="#a53fb11c0140efce7e25ca9ff5ccbac96">getVectorMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02127bae19ef433c1233c696317a8868">llvm::SelectionDAG::getVPZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abf0bc161f51dbc01add0270eb00b2f77">PerformMinMaxFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ade6927c3ebfbd00cbede63e5a1d1426d">PromoteBinOpToF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0c9502505ab5e9910350e241f20d976a">llvm::AArch64TargetLowering::shouldExpandPartialReductionIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac5670c01bc722932c40b06aaab52a0df">skipExtensionForVectorMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aac3337c401bb0145fbecced8d947cebf">llvm::SelectionDAG::SplitEVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4340bab6e118d0614449e74a779b30c">tryCombineWhileLo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab30bbf3bcf699a32f7113173b5cee991">llvm::AArch64TargetLowering::verifyTargetSDNode</a>, <a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6dc0d17c5d20afdfa4004345e930584c">widenVectorToPartType</a>.</p>

</div>
</div>

### getVectorElementType() {#abc4c6365ade17ad4443ad0e381e7479d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getVectorElementType ()</td>
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

<p>Given a vector type, return the type of each element.</p>

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a> and <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#aae881b014fee000d713159f7464f860e">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a068555b4b66d140162c7d3c2cb16beae">adjustLoadValueTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a25d4d29a2e8f87e039add92fe76ef88c">llvm::RISCVTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#addec051710bc0afc4147859062eb31a4">CollectOpsToWiden</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae63d3420be279c225fb7bad70c0b8046">combineBoolVectorAndTruncateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bd495ab23d43ebbe7e2d167103d8991">combineCastedMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad45a536ce828d7fe0a889a1666437654">combineConcatVectorOfCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad2800cb88996291ed1676f5899997ebe">combineExtSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2336d9f0305e57b22c5be16c73caa">combineMulToPMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab5a426cb5c2105ca954c4ab9f12ef76f">combineShiftToMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab73df8541f091c30ed34fd2c89c57746">combineShiftToPMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a364872c4ff0debf2cd93e9694b261b07">combineShuffleOfConcatUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa51b13f3d4866613aac6907835f51f83">combinevXi1ConstantToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a321df2422ee45cfd96e738928fb178f7">combineXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600isellowering-cpp/#ad9e1097d647444e0c961dcd323944ff9">CompactSwizzlableVector</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#acab5bf267b2b761c038dd0976779a5e9">constructRetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0841165650bd49aa4995c4dfa3fdf650">detectPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af95bcf95fcfc5d82d24423018024641e">detectZextAbsDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01bdf0d462d6df94d15c1763169f4cf1">EmitVectorComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aecabf0b51b7f3a579c05fc08e06c265a">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d2572a2d7cf0d8584f28c2c1c2e14c8">extractSubVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c383bff50576c84343b3b8ea609f3e1">llvm::SelectionDAG::ExtractVectorElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#adeba9ee43ee94300c5bb47b99b47a945">findMemType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac2e1d91d4013f7c45951b5fb918f94f0">foldIndexIntoBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa8e7d7856b86905a5ce055fb23d0c9b2">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7266504e88c036bd48704ba439eababb">GeneratePerfectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5dcb8d597c1066eec7ef713b758f78f4">llvm::ARMTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a10930c52b74a578790352742b8139389">getContainerForFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae968aa14d25b7b04bf82019ad48f599c">llvm::SelectionDAG::GetDependentSplitDestVTs</a>, <a href="#a3f78e3bf25a5e4bef300d42dde0d8477">getDoubleNumVectorElementsVT</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae94d01adfba8b1a65f781ecd925111ea">getExtFactor</a>, <a href="#aee35a362966ced72913881d8a2dc3be8">getHalfNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a999f6375546ae5d8aeb9024493fc118c">getInvertedVectorForFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a7b2fcbe31b1e7a23ebe5be0c1e70343a">llvm::ARMTTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0d2d9c6df58f2916c90d15bc635d871f">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">llvm::MipsTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#a9869cb9330f243cad6d20c176de62d19">llvm::SPIRVTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aba30f84d7fd0dd3361ff92fe1e53d9ca">llvm::X86TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe1ee0c3600d3982d5dcb722f8079ebd">getOneTrueElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a7c14a3a22d127469c3490092627c2368">getPackedVectorTypeFromPredicateType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab7458c4c1d0b716494b03ba16ee86ad2">getParamsForOneTrueMaskedElt</a>, <a href="#a15f3027fdcad3b33960402d9739afe4b">getPow2VectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a68a18462f9529b0e75812794eeedbb5f">getPredicateForFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc1bb69bd08d87b899c1a5d9866acea1">getPredicateRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa83fc29419d3244b75d7a1d31d8d10d2">getPromotedVTForPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a04c394dca43220a262f8a67825cd4fb5">llvm::MipsTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#aa3b5623e42a15bdd63bfea603699d01d">llvm::SPIRVTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7c19f0fe8ae2a12ed0c5cf142a520522">llvm::X86TargetLowering::getRegisterTypeForCallingConv</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada7f52028e75ee798b0fbbde2445b95e">getShuffleScalarElt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aca0e8562bea682465caada8d71a47234">llvm::SelectionDAG::getSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8ab55d055af84ce8d884844d5171198e">llvm::SelectionDAG::getSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#af11e81ec39d8b1108c8aae7a8cc4d605">llvm::AMDGPUTargetLowering::getSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a444be9352256919a844309a35dffa0f8">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1cdb38ba97d3ced9be618b22a8053581">getSVEPredicateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7c335b50ec450e5955b50d2ea468ea78">getVectorLoweringShape</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac477f229337de92be9c48dae99bf5546">llvm::AArch64TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21321ab7669a253fc0fe731602fe5695">llvm::MipsTargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9f81a81b890192ac2e40f2995080feaa">llvm::X86TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6dfe0c9c0080f43b8e889d93c3248b3b">getVPermMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7cb0f27acb965339dde328392c1adaf7">insertSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aec601d177f33c89713cff3857f97aa77">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5961d8a9524e219b55d22dc9e43e15af">llvm::HexagonTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a0b3bbcd8728609a52e420775a7f7cf">llvm::RISCVTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab75bfa0d750449f745ed10dba2f81e31">llvm::X86TargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#abc42cb694d5b2c6b2b7daf8f2cb4411e">llvm::SITargetLowering::isExtractVecEltCheap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37f06b796addd745c44af4546b84fe76">isFNEG</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a8ab3eaadf7f52ab7ca677e6c545e6508">llvm::X86TargetLowering::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c242ac8227e53a677e25cac39aaad82">llvm::isMaskType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a731fed7d3e9a9ebe3a9940afd6a3bdc2">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4217293101179a3839b8afb1fafb2e0d">llvm::X86TargetLowering::isTypeDesirableForOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aea8c2b718c1dd866d61c29081c1eb44f">llvm::RISCVTargetLowering::joinRegisterPartsIntoValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6e9a1f8a595e1e9b2bb022451203ccc2">legalizeScatterGatherIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13428801d19f40af7da16a16d76329fb">llvm::AMDGPUTargetLowering::LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6fd620f229a9cde3e60fc77ab234cd1e">LowerCTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1e66c7cdb5788173f5681ee37389dee1">lowerMSACopyIntr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5d48bc80fa2c6e61a0ad0dfedac1553a">LowerMULO</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a40581570b38300f3a21e2e8ec8c80839">llvm::AArch64TargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab39855d189957c348ae6db001226dc8f">lowerScalarInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac7770c117c42378101694b6f865978fc">LowerVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8c20dd640b6afb2b2f75fbfb8b5f7428">LowerVecReduceMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1f71843f178d1cbe0f1bd95af528c46">lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab8d9e84c7d48cbe98372e43cc9f009d6">lowerVECTOR_SHUFFLE_VSHF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac8364c810117e878351a8b7b3ecfb833">LowerVectorINT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7cdac11a3fa70f7ccb30ead4228dced4">LowerVectorMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac76473b9005e8953bfde5975fc7d2eca">matchTruncateWithPACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a15ae77c55dfbf20a719b9851d73d1900">NarrowVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a06205ea56e17027e23e321056e351c58">NormalizeBuildVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/widenvector/#a1c7d0aa7f38f624303070d06ad7b3736">anonymous{AArch64ISelDAGToDAG.cpp}::WidenVector::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a635ad8d6dba2689cc34e3bb3fb12c2a6">performAddUADDVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af84a0dc03b9bdd1ccfd5f88dae1a4aab">performBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a88130de22a0c1eefe0ff49acda2ca4fd">performDupLane128Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab253557e698e63e5f05d8d9dd1d91f5">performExtractSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77e5d35ccfe68c41092edc168cfb393e">performFirstTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a20421c306f02a92c47eef00c2a1f02f8">performGLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72895c7f66e26be35e106221a2ab26ae">performSignExtendInRegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57a099df9c79ef37ef7f89374247ac0e">PerformVDUPLANECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a49ed4ed152a2f6e8533ccac1deb10ca0">performVecReduceBitwiseCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a84a7819a9f36f529085ab85492b5a4d7">performVP_REVERSECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53300f43eec34fc01f85c153445e4a37">reduceMaskedLoadToScalarLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600isellowering-cpp/#a5dc22dc930f2a262ed4e67b2915bbb11">ReorganizeVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d18c51ca04dfa5c2b56ad650ab0d7d9">replaceBoolVectorBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a8685d453cbabec8c0826789a79879242">replaceVPICKVE2GRResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0670f21ebeafbaab3f4b34c8140b8dc8">replaceZeroVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae002ed884c63140cccb45d854b6bd013">scalarizeBinOpOfSplats</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1e801ca0fc0ae63d482926b72ce3b45c">scalarizeExtractedBinOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a278bc9f5720547f5e171d0a62290d69f">llvm::AMDGPUDAGToDAGISel::SelectBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a750e795af7ca75cfebb03e563cbaddc5">SelectOpcodeFromVT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a7003b5e44eb73177e8c26b4a91247e57">llvm::AMDGPUDAGToDAGISel::SelectVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a5577e59801b2de97a243a46e0f6ca84a">llvm::RISCVTargetLowering::shouldExpandCttzElements</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0c9502505ab5e9910350e241f20d976a">llvm::AArch64TargetLowering::shouldExpandPartialReductionIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8272c4da36b8d295addf73f56c548155">llvm::SITargetLowering::shouldExpandVectorDynExt</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2376efddac62782331d4217be9fa0b8b">llvm::RISCVTargetLowering::shouldRemoveExtendFromGSIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adcd2433bf37019679f7e14d3b8cd7708">truncateAVX512SetCCNoBWI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a95b61f0543f51a5dca686a9f9f258240">tryFormConcatFromShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1efa0c093d9b13546c2b2dc1d699c517">tryGetOriginalBoolVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a11ecac3a9729434713c118b4e1a6f52f">tryLowerPartialReductionToWideAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d9cb8881ecb22d3225e564b5b2fb01c">tryWidenMaskForShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5a8d860cc5c733afd761c1e292b5a0aa">llvm::SelectionDAG::UnrollVectorOverflowOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab4a216c3f1033e64e9340aca44316ee4">llvm::X86TargetLowering::visitMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a3f2022425f9155911916a81841455566">llvm::X86TargetLowering::visitMaskedStore</a>, <a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aeca06367a5dacb988586dfa1b94fa0c1">llvm::AMDGPUTargetLowering::WidenOrSplitVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ab9c026bf7b5362d2b79a43bd04e769a7">widenVec</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab255633ec6629254aeb996969bc7a212">llvm::SelectionDAG::WidenVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae138473fc11097221f02e42677663dc">WidenVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6dc0d17c5d20afdfa4004345e930584c">widenVectorToPartType</a>.</p>

</div>
</div>

### getVectorMinNumElements() {#a53fb11c0140efce7e25ca9ff5ccbac96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::EVT::getVectorMinNumElements ()</td>
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

<p>Given a vector type, return the minimum number of elements it contains.</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a> and <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac83bcada2a1e9fdfeb3a5215fff012da">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9dd90159d2669297cd6ed1b61b3587a0">llvm::SelectionDAG::getPartialReduceAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa83fc29419d3244b75d7a1d31d8d10d2">getPromotedVTForPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa5eeaff1c30e200ebb792540219132e7">getSubVectorSrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb4484ddcdad2576d97870230db05ed8">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a516614c2855a763aa9eef67c6da888e0">llvm::isConstOrConstSplatFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae1f54fa7a42bfe0913b9fe2e869a958c">llvm::AArch64TargetLowering::isExtractSubvectorCheap</a>, <a href="#a59eee3929b9155fd268e3e3f6c0efde9">isPow2VectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a750e795af7ca75cfebb03e563cbaddc5">SelectOpcodeFromVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aac3337c401bb0145fbecced8d947cebf">llvm::SelectionDAG::SplitEVL</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8695950995820e5f6c0407c68f91f44f">llvm::SelectionDAG::SplitVector</a>.</p>

</div>
</div>

### getVectorNumElements() {#ae245d70802e4ebe1cae2b6122c62a22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::EVT::getVectorNumElements ()</td>
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

<p>Given a vector type, return the number of elements it contains.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a>, <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>, <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a916e9619e70faa6bc1f4daf0c21292c5">llvm::reportInvalidSizeRequest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1a0cd3e4178d08fadb03d4e4e9404dcd">addShuffleForVecExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a068555b4b66d140162c7d3c2cb16beae">adjustLoadValueTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a1b8378147a68d3e61fbf9e5315283c72">buildScalarToVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6a1c71b7d20e3cf09cc8ff5a8efdb34f">canCombineShuffleToExtendVectorInreg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abec3ca8e4e6dd78a431e82eaae53b5bd">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac1639f9e80414a665a5826e6e4ca6095">canonicalizeShuffleMaskWithHorizOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e8360ec6c03540a7ad4753613cfc66f">collectConcatOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#addec051710bc0afc4147859062eb31a4">CollectOpsToWiden</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e3e38f27d866ed7730e8e30fc3877cf">combineAddOfPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c3d86d724323d88d2fdf99d29d3de72">combineBasicSADPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a670c95cba653503ce21f4abeea37cd2f">combineConcatVectorOfExtracts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69c29dade9c2c83e9928f92e0e6452f0">combineCVTP2I_CVTTP2I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a886d3292e22e113b2f04c1c35811bd0c">combineKSHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2a2b06cd0043981c801d852ace83fded">combineMaskedLoadConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2336d9f0305e57b22c5be16c73caa">combineMulToPMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af72da135a7e8a925ffa9fbbb4ecf0b1f">combinePredicateReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae9b4450314b8e4acb9f937389b349fce">combineShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a69d159ccc8c9f4f70ed369d35c5c420b">combineShuffleOfBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a364872c4ff0debf2cd93e9694b261b07">combineShuffleOfConcatUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6da34b4a62e36f7b3b51720f19d3e753">combineShuffleToAnyExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a208df5267fac83f34e5dbb36815b17b4">combineToConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8389740010ccf99686a066f0bdc4dbdc">combineVPDPBUSDPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa51b13f3d4866613aac6907835f51f83">combinevXi1ConstantToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa734719767b4f7faea1f7b40554f30be">llvm::X86TargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac11671a35605d3033849a1e314831179">concatSubVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5bd62ec61571d2805d0d609d279a3e3e">constructDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#acab5bf267b2b761c038dd0976779a5e9">constructRetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a0d7b181917dd3066841199e4299d8b91">ConvertSelectToConcatVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp/#ad378536508f0c71b730daf4da2026076">createBSWAPShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7eda61e02d6245a6cbc5ec5c09f1198a">createShuffleMaskFromVSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79354a2324d1cc1c1fd42e5d8a771479">llvm::createUnpackShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a482f0fad081b3094561d510c11335bfd">createVariablePermute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0841165650bd49aa4995c4dfa3fdf650">detectPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af4acdb0d749d0537888000052aadf256">ExtractBitFromMaskVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aecabf0b51b7f3a579c05fc08e06c265a">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d2572a2d7cf0d8584f28c2c1c2e14c8">extractSubVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c383bff50576c84343b3b8ea609f3e1">llvm::SelectionDAG::ExtractVectorElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#adc81cc844c6c6c32c8be216807aa54f5">FoldBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a65dff372171f9d4e3e07a272214fb94d">foldExtractSubvectorFromShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a781a75dfc661452760864c019bafd96e">foldShuffleOfConcatUndefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a29b991787209a4f8c221fb5cf7e70e84">getBuildVectorSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a646cdefda88e785573dffb15889de1d1">llvm::ARMTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae40536e54a704fc900dd851134869a48">getConstantLaneNumOfExtractHalfOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6d7162a570369a85f2a5238452e196e3">getEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a9b491c57b85b9102e646df663d7f55e3">llvm::ShuffleVectorSDNode::getMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vecustomdag/#a5cbffc44ad31b145185f0cf56289c7d3">llvm::VECustomDAG::getMaskBroadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">llvm::MipsTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa8ee36cbd5d910c4f4a1d899a109baf6">llvm::SITargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#a9869cb9330f243cad6d20c176de62d19">llvm::SPIRVTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aba30f84d7fd0dd3361ff92fe1e53d9ca">llvm::X86TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe1ee0c3600d3982d5dcb722f8079ebd">getOneTrueElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a68a18462f9529b0e75812794eeedbb5f">getPredicateForFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#aa3b5623e42a15bdd63bfea603699d01d">llvm::SPIRVTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a0b74111574af484ef33597940f5e9c56">llvm::SystemZTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7c19f0fe8ae2a12ed0c5cf142a520522">llvm::X86TargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a9dae8eb30ecc1fabd7e64f4b713b6280">llvm::HexagonTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#aa90aff23586273a6669ee0a23f385933">llvm::NVPTXTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1f4f77bf289589785c34e8eebc274dd6">llvm::SITargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada7f52028e75ee798b0fbbde2445b95e">getShuffleScalarElt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aca0e8562bea682465caada8d71a47234">llvm::SelectionDAG::getSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a78735185fd19e227f3c2f0bcfcd46ae8">llvm::ShuffleVectorSDNode::getSplatIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a093fa508bcdccd1b9172fc87797c8cd6">llvm::SelectionDAG::getSplatSourceVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#af11e81ec39d8b1108c8aae7a8cc4d605">llvm::AMDGPUTargetLowering::getSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a444be9352256919a844309a35dffa0f8">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6388d46f1b629bc93ef3a8b25d61c141">getSToVPermuted</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af71303967827d0c63f1caa626e59aa38">getTargetShuffleAndZeroables</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1510df8e6724eea06fe764e48a5e6338">llvm::SelectionDAG::getValidMaximumShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2811a9d5b02b367167de0384fe2f173d">llvm::SelectionDAG::getValidMinimumShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8f6d0f4a96899cc73faa3a17659409a">llvm::SelectionDAG::getValidShiftAmount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7c335b50ec450e5955b50d2ea468ea78">getVectorLoweringShape</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac477f229337de92be9c48dae99bf5546">llvm::AArch64TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21321ab7669a253fc0fe731602fe5695">llvm::MipsTargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af37fa82c85e811c7ed496ebcbacf99c8">llvm::SITargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9f81a81b890192ac2e40f2995080feaa">llvm::X86TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6dfe0c9c0080f43b8e889d93c3248b3b">getVPermMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab17595c13740973595e3e453704985a">isAllConstantBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a016f7b15a2e335153beb2421ac622ce5">isConcatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9ebdafbae1fdc29135b25d537a89cd61">isEXTMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a73ff0ebe4440fb057e9206dd88bb8c7c">llvm::ARMTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a0b3bbcd8728609a52e420775a7f7cf">llvm::RISCVTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab75bfa0d750449f745ed10dba2f81e31">llvm::X86TargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8947affefbaa5e1099d7ba6bd401f05a">llvm::SelectionDAG::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0bf38c29e86627800a241dc0f1005d5c">isHorizontalBinOpPart</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a40892ab1e0ab2dcb208fdedac55ebd2b">llvm::HexagonSubtarget::isHVXVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3e9938aeee2aaef4ca5933920bb8c2af">isLegalBitRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a460fe5aea074c37615e0106c2a13a1e4">llvm::TargetLoweringBase::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0346da3fb8d131cf057b3f5c1757400b">llvm::isPackedVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2b8fb99a1e250aac47d7fc77425edc8e">isReverseMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a1c7cb6b368ef7cba8da95f1f11ed4fc0">llvm::AArch64TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a779e5a75f5bf9f3672698656b56663fc">llvm::ARMTargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0547dd3b2c2f8064c78de596bd957c92">isSingletonEXTMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ace16f1ef986475b765a538d7e64914eb">isSingletonVEXTMask</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a00abad87897a8bf77c53b38666451400">llvm::ShuffleVectorSDNode::isSplatMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa5950e8440c6d4ecdaf950affa6a8e97">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af83ff96c157ea2db2a7f032cc9c80369">isTargetShuffleEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad1476240ebd4bc1b48535567993515fb">isTRN_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a79bc1802f4c2b4a2523206b0df1f959a">isTruncMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3b5254c39b86764ce2ca093701342756">isUZP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a27f76de53b5b15274dbf8e4f30adf81c">isVectorElementSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a76388bd3043bf7119606cfec35ffb544">isVEXTMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa47d7aa438a94dc4bdc96008c058d675">isVMOVNMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a875013a3b871d454c0029aa65e124667">isVMOVNTruncMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6430d7837d2e985a3afc6e9c3d78c7dc">isVTRN_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a355dbd33acb5fd07a2b6418ba17051e3">isVTRNMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae4d5393f007c020e1bd59d37127b1904">isVUZP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8409a4a25c5001a552a5e21d4febadbb">isVUZPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d3f97d988494d78dc6ec1673b685bdc">isVZIP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a63cb14d47a8b27e0427f67087faa7152">isVZIPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a670137fe83c1213c3c2e82b8144e9af3">isWideDUPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af9d6419fc209e6d03e89a3bb8b3675a6">isZIP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab733cc9ef2c6f6e0872469b0ba899483">lowerAddSubToHorizontalOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a072943808f01aab9f39ecd7887019ff6">LowerBUILD_VECTOR_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9a90bcacc0044e2fb442d934fba4f062">LowerBUILD_VECTORToVIDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6f6622d37de7bdbf2708835f57864a96">LowerCONCAT_VECTORS_i1</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a24cc4a1d21ea4653fdd760e2d7ae930e">llvm::AMDGPUTargetLowering::LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36623d79590f271aff0f88734e356708">LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a8d6169e2e4a0e60c74e95dab53907e2f">lowerMSASplatZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aedabf4c69af716c22c9957d6ca5758e1">LowerPredicateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae6e3df9a1ecaccea324e9fde7f3d810a">LowerReverse_VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac7770c117c42378101694b6f865978fc">LowerVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8c20dd640b6afb2b2f75fbfb8b5f7428">LowerVecReduceMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1f71843f178d1cbe0f1bd95af528c46">lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab8d9e84c7d48cbe98372e43cc9f009d6">lowerVECTOR_SHUFFLE_VSHF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6b5025511ed198dfe7a49b67cf6d57ca">LowerVECTOR_SHUFFLEUsingMovs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1b11056f4136f56eaeb871857e5a53a2">LowerVECTOR_SHUFFLEUsingOneOff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3de24662ee719e2c772575317d208116">matchIndexAsWiderOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a079f719b6af4bba305e041821a1e3da0">matchScalarReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2e18d86a676154c8ddeb0a9dbdce719d">mergeEltWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a15ae77c55dfbf20a719b9851d73d1900">NarrowVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/widenvector/#a1c7d0aa7f38f624303070d06ad7b3736">anonymous{AArch64ISelDAGToDAG.cpp}::WidenVector::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a466591fe7edc07ef1ffac406020984bd">partitionShuffleOfConcats</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af84a0dc03b9bdd1ccfd5f88dae1a4aab">performBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a172a1f5983db0d10ae90c0d3f5beccdb">PerformExtractEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaece9d12c539bbab91aff76ea7e95096">PerformInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afa4334801ad99c95a1b5fd0f417e16af">performInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7ece31c45ed2351976803ebe4df89425">performUADDVAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8544593225835a30146f86a3187740e7">PerformVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99f918c3264972ed6aea09c675404952">PerformVSetCCToVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a036a964199eef5a0aab70732233b5e8d">performZExtDeinterleaveShuffleCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7da18013c41f68948709a964437238bf">performZExtUZPCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af2093ca4a132848caa9d8acc509df1b2">ReconstructShuffleWithRuntimeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab81263b19a504166d5c027a21cc15740">reduceVMULWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a824cd060277e4cb924783db572374c66">replaceSplatVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0670f21ebeafbaab3f4b34c8140b8dc8">replaceZeroVectorStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600iseldagtodag-cpp-/r600dagtodagisel/#a526fd2710d7457e09c2b4715b2367638">anonymous{R600ISelDAGToDAG.cpp}::R600DAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a278bc9f5720547f5e171d0a62290d69f">llvm::AMDGPUDAGToDAGISel::SelectBuildVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a829a79c8cbee3cc9c372d70ab9df47d6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectExtractHigh</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a7003b5e44eb73177e8c26b4a91247e57">llvm::AMDGPUDAGToDAGISel::SelectVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8272c4da36b8d295addf73f56c548155">llvm::SITargetLowering::shouldExpandVectorDynExt</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0409fb04e071cd7a523f022dffec2a3">SplitOpsAndApply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a95e6431ff6ad6b548c061a19df107850">llvm::AMDGPUTargetLowering::splitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8b77cecfc2091e2d9c9116ca578983e2">splitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad73ee74c3375a93fef67a9d60b51d817">splitVectorIntUnary</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0bd751c4c85d494e52e578b6bc10f8bc">llvm::AMDGPUTargetLowering::SplitVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aad3b6954334c350e17f08d707e1f102f">llvm::AMDGPUTargetLowering::SplitVectorStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa541e074a612b8ca4a7291a3b0746b7e">tryBuildVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d9cb8881ecb22d3225e564b5b2fb01c">tryWidenMaskForShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5a8d860cc5c733afd761c1e292b5a0aa">llvm::SelectionDAG::UnrollVectorOverflowOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aeca06367a5dacb988586dfa1b94fa0c1">llvm::AMDGPUTargetLowering::WidenOrSplitVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ab9c026bf7b5362d2b79a43bd04e769a7">widenVec</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab255633ec6629254aeb996969bc7a212">llvm::SelectionDAG::WidenVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae138473fc11097221f02e42677663dc">WidenVector</a>.</p>

</div>
</div>

### is1024BitVector() {#a50fc902bfa2d3dd0cf0fef0a4790716a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is1024BitVector ()</td>
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

<p>Return true if this is a 1024-bit vector type.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>

</div>
</div>

### is128BitVector() {#a6db1f207286bd8bc6a978593a55955e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is128BitVector ()</td>
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

<p>Return true if this is a 128-bit vector type.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a0aa60141f3fc64eccae5554fa3eb6426">AddRequiredExtensionForVMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4149392e82922475c1b566db35e3c8b8">combineAndShuffleNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a04f34c6d2aa331eb6fe9c1f1e52f2f9d">combineLogicBlendIntoPBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a364872c4ff0debf2cd93e9694b261b07">combineShuffleOfConcatUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5bd62ec61571d2805d0d609d279a3e3e">constructDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a458b41b670c695bfe6c37217b7007c">getOnesVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0f73140cd7f0b2c566b8ee7c1b86042d">getTargetVShiftNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a201cec669c3caecff012ed5f2fe81c1e">getVectorShuffleOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a82ea3e3b3362aee4beee97df4ed04ec2">getVShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9130245943505c30b0ba979c8a77d723">getZeroVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22d41ad70a90ca184815fa009b650b97">insert128BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a026121a7546e6370b59fc4b70af584d7">isLegalMaskCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a1c7cb6b368ef7cba8da95f1f11ed4fc0">llvm::AArch64TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a779e5a75f5bf9f3672698656b56663fc">llvm::ARMTargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac424ec93d0c7fd6666e2200a60cb20b9">isVMOVModifiedImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8c20dd640b6afb2b2f75fbfb8b5f7428">LowerVecReduceMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7cdac11a3fa70f7ccb30ead4228dced4">LowerVectorMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a88130de22a0c1eefe0ff49acda2ca4fd">performDupLane128Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aeda6315d246cafab6d912b425d4e7218">scalarizeVectorStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a829a79c8cbee3cc9c372d70ab9df47d6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectExtractHigh</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac5670c01bc722932c40b06aaab52a0df">skipExtensionForVectorMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70ab6e6fcc6015c6cdce1aa4497cd7f5">supportedVectorShiftWithImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6f5f3de82cbdb6a05c7f49ecf791382e">supportedVectorVarShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a01d5b65fa577bc031d0774c32a047e31">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryIndexedLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a>.</p>

</div>
</div>

### is16BitVector() {#aa8dc60b275ae1a147a9b24d4ccdfd305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is16BitVector ()</td>
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

<p>Return true if this is a 16-bit vector type.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>

</div>
</div>

### is2048BitVector() {#a767efe6535626636e7b78470235b5175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is2048BitVector ()</td>
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

<p>Return true if this is a 2048-bit vector type.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>

</div>
</div>

### is256BitVector() {#aacd05b71fb3b325dcc53a7df09d37edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is256BitVector ()</td>
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

<p>Return true if this is a 256-bit vector type.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4149392e82922475c1b566db35e3c8b8">combineAndShuffleNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a04f34c6d2aa331eb6fe9c1f1e52f2f9d">combineLogicBlendIntoPBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a364872c4ff0debf2cd93e9694b261b07">combineShuffleOfConcatUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af1235e2e2ca58b93e3b22bc6c8b3d9ab">extract128BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a458b41b670c695bfe6c37217b7007c">getOnesVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0bf38c29e86627800a241dc0f1005d5c">isHorizontalBinOpPart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a026121a7546e6370b59fc4b70af584d7">isLegalMaskCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2a97ef0e99d8dd358ff9296a748e894">narrowShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a309d56d62904382ce197ab216f4ec43f">narrowVectorSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6ad23b58059ffd91df6a2dddf30c5d71">llvm::X86TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a711fc4155ad349094a5d3d1f4a3741a6">splitVectorIntBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad73ee74c3375a93fef67a9d60b51d817">splitVectorIntUnary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6e73a48328462ff271d3a9bb6c4694af">splitVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70ab6e6fcc6015c6cdce1aa4497cd7f5">supportedVectorShiftWithImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6f5f3de82cbdb6a05c7f49ecf791382e">supportedVectorVarShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a>.</p>

</div>
</div>

### is32BitVector() {#a407fe71968756ae65989f791f641c375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is32BitVector ()</td>
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

<p>Return true if this is a 32-bit vector type.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>

</div>
</div>

### is512BitVector() {#a8eed7940698816c772ded7b098f2e1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is512BitVector ()</td>
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

<p>Return true if this is a 512-bit vector type.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4149392e82922475c1b566db35e3c8b8">combineAndShuffleNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af1235e2e2ca58b93e3b22bc6c8b3d9ab">extract128BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2433dc6459ebb75035c03803968a2cd7">extract256BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a458b41b670c695bfe6c37217b7007c">getOnesVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2a97ef0e99d8dd358ff9296a748e894">narrowShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5cd2ddff46dc5822bcc7666e336da52b">llvm::X86TargetLowering::shouldFoldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6ad23b58059ffd91df6a2dddf30c5d71">llvm::X86TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a711fc4155ad349094a5d3d1f4a3741a6">splitVectorIntBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad73ee74c3375a93fef67a9d60b51d817">splitVectorIntUnary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6e73a48328462ff271d3a9bb6c4694af">splitVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70ab6e6fcc6015c6cdce1aa4497cd7f5">supportedVectorShiftWithImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6f5f3de82cbdb6a05c7f49ecf791382e">supportedVectorVarShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>.</p>

</div>
</div>

### is64BitVector() {#afa40b0ea2c1858e1e297227cc17d77db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::is64BitVector ()</td>
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

<p>Return true if this is a 64-bit vector type.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a201cec669c3caecff012ed5f2fe81c1e">getVectorShuffleOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a1c7cb6b368ef7cba8da95f1f11ed4fc0">llvm::AArch64TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a779e5a75f5bf9f3672698656b56663fc">llvm::ARMTargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae4d5393f007c020e1bd59d37127b1904">isVUZP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8409a4a25c5001a552a5e21d4febadbb">isVUZPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d3f97d988494d78dc6ec1673b685bdc">isVZIP_v_undef_Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a63cb14d47a8b27e0427f67087faa7152">isVZIPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7701507d5a5024692d7dfe93a90df8c6">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a829a79c8cbee3cc9c372d70ab9df47d6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectExtractHigh</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a01d5b65fa577bc031d0774c32a047e31">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryIndexedLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a>.</p>

</div>
</div>

### isByteSized() {#a470621733f1ffb597e6f502040216da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isByteSized ()</td>
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

<p>Return true if the bit size is a multiple of 8.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a1618ca92d9fa0b2b577698fb006b84cc">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isKnownMultipleOf</a> and <a href="#ae2ee94a616a11388828c36d1e0b4798c">isZeroSized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#af412df17add838f012f81de13961060c">calculateSrcByte</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347cc43c09f54dab457a45b11183461b">llvm::TargetLoweringBase::isPaddedAtMostSignificantBitsWhenStored</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa435f2b01aca963d926bd31cd95e7f03">matchPERM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a84a7819a9f36f529085ab85492b5a4d7">performVP_REVERSECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a273d2011b48b740db185cdcdf4decf76">llvm::AMDGPUTargetLowering::shouldCombineMemoryType</a>.</p>

</div>
</div>

### isExtended() {#abda309a31acb43c06215c1772727bf1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isExtended ()</td>
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

<p>Test if the given <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> is extended (as opposed to being simple).</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80ea223c590adb7c6fddc635804401c6">llvm::TargetLoweringBase::getAtomicLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9fd228909f3f1a59c6ef7d15c3547b61">llvm::TargetLoweringBase::getLoadExtAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af7966eae031882124c0beee58c4c922e">llvm::TargetLoweringBase::getOperationAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a924b8ce261b7b394b47b82a07cd2456a">llvm::TargetLoweringBase::getTruncStoreAction</a>, <a href="#ab0cfceeb37508e56f9c127e59766a668">getTypeForEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#aa8b06263dc30cdbef2780acdf3e73c69">anonymous{DAGCombiner.cpp}::LoadedSlice::isLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### isFixedLengthVector() {#a920f0719057d7352f9da10908859368d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isFixedLengthVector ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abec3ca8e4e6dd78a431e82eaae53b5bd">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a40bdcac44bd6d189cc6b65984baf3303">llvm::AArch64TargetLowering::canMergeStoresTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a905bf60f4a852a875fe2058dec3494c3">convertFromScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afb001768f7eb9930ca97753a1e39e5e0">convertFromScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a65dff372171f9d4e3e07a272214fb94d">foldExtractSubvectorFromShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae40536e54a704fc900dd851134869a48">getConstantLaneNumOfExtractHalfOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a10930c52b74a578790352742b8139389">getContainerForFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3f4445d350e1253b4c05ab25011d766d">llvm::AArch64TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a68a18462f9529b0e75812794eeedbb5f">getPredicateForFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa238c0945ce9c3ba4fd71439a8c316c6">getPredicateForVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0f1ad23af20c2a0b3e3f5c0a995c1969">llvm::AArch64TargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1510df8e6724eea06fe764e48a5e6338">llvm::SelectionDAG::getValidMaximumShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2811a9d5b02b367167de0384fe2f173d">llvm::SelectionDAG::getValidMinimumShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8f6d0f4a96899cc73faa3a17659409a">llvm::SelectionDAG::getValidShiftAmount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb4484ddcdad2576d97870230db05ed8">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a516614c2855a763aa9eef67c6da888e0">llvm::isConstOrConstSplatFP</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7567a37e7689d3f5b2cce9441597b37a">llvm::RISCVTargetLowering::isCtpopFast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8947affefbaa5e1099d7ba6bd401f05a">llvm::SelectionDAG::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a2548c54b76e921b3e1c0350002cf6fc1">llvm::RISCVTTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a755123fd18e5b8be4de7684fe173f21d">llvm::RISCVTTIImpl::isLegalMaskedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a460fe5aea074c37615e0106c2a13a1e4">llvm::TargetLoweringBase::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad0581b9db1cc9ac63ca3c7eb944d4fd8">isPackedVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62748fc6c30d6e3f7c851344bd2dfd4d">isPassedInFPR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaece9d12c539bbab91aff76ea7e95096">PerformInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afa4334801ad99c95a1b5fd0f417e16af">performInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a49ed4ed152a2f6e8533ccac1deb10ca0">performVecReduceBitwiseCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3ce9ba59f8e02ebc4646f41ee4d57f8a">llvm::AArch64TargetLowering::shouldExpandCmpUsingSelects</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a1652477e0e5b2968e8d160f87031cdf5">llvm::RISCVTargetLowering::shouldFoldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aac3337c401bb0145fbecced8d947cebf">llvm::SelectionDAG::SplitEVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3cce50ef77513b8bd1cbeb48b4d9339d">tryAdvSIMDModImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed120dd6850080b309b6054efd2b142b">tryAdvSIMDModImm32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af415da4daf8365b80a0f0dba2ee8490e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastFixedLengthToScalableVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac490424228331c1beb5025ef6d45d2a6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastScalableToFixedLengthVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a2f7ac4b96278419769d4bd3caa6fcf26">llvm::AArch64Subtarget::useSVEForFixedLengthVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### isFloatingPoint() {#a3cb888a2ce8e95e0d9769687a5e2f7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isFloatingPoint ()</td>
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

<p>Return true if this is a FP or a vector FP type.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad5d9213c39b2fc64eaed3639539e8f65">llvm::PPCTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5f71cfbbaacd538471dd7b3e5da4733b">combineBitcastToBoolVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6b1491b47f4868ea3e305573799a2561">combineBitOpWithMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a42586d078a0c852f7571d5d4fb0daa04">llvm::VETargetLowering::combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7094504ff72e8db0894faac2216aa00a">llvm::VETargetLowering::combineSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a096ef3eeb61c748a1c1a120171a7c71f">decideComp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0194fe7dca15bfabd4f391e01ba7606d">emitComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01bdf0d462d6df94d15c1763169f4cf1">EmitVectorComparison</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af35d763b74cc1ae6f4da3a698b6e3027">llvm::AArch64TargetLowering::enableAggressiveFMAFusion</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a6f3484a5a16158cba22281a95a187e38">llvm::PPCTargetLowering::enableAggressiveFMAFusion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad1ed10076dcd144800421886c7caea42">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#a5d963dea45bb93b0a3dce47d04d1b959">getLdStRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a6925b6f3924454060cc817238f2a8f2c">getPredicateForSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa16505b46d66798daa417510b68ee4ac">llvm::ARMTargetLowering::getSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acb51326eb72adb30e442667892c1f5ae">llvm::AArch64TargetLowering::hasPairedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9b9007ba3cc8c225dbb8e89fbfabc1a9">llvm::AMDGPUTargetLowering::isFAbsFree</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af4dac2cd51ca7d7082cabfba3f81dd27">llvm::TargetLoweringBase::isFAbsFree</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4cb5f3e841a19c00cf078f9b65886e4e">llvm::AMDGPUTargetLowering::isFNegFree</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9e691980ff29653e6bcc97fe1fa30a17">llvm::TargetLoweringBase::isFNegFree</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a58ed954e5eaff1b63e086855f2183b38">llvm::TargetLoweringBase::isFPExtFoldable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a19198578d08502db0acb9cd75ccbcae0">llvm::PPCTargetLowering::isFPExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a75b5f43626eca6f155a21f22e4a5acd0">llvm::TargetLoweringBase::isFPExtFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a81f0b427ff9a532ec2b6bf98c132db26">isLegalT2AddressImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a684dc96f8f8c8d2e9473fea07a6f5917">isLegalToCombineMinNumMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a2813d266aebd06f8db45b0dab6bfaa01">isMImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ae48d974556a4a4ac56f2ce1f5ba11586">llvm::RISCVTargetLowering::isMultiStoresCheaperThanBitsMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1134e24a9f51b06d69b66aaede5eb422">llvm::X86TargetLowering::isMultiStoresCheaperThanBitsMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62748fc6c30d6e3f7c851344bd2dfd4d">isPassedInFPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a0ab8c631af35cb8fb070e4c1c5678377">isSimm7</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp/#a52ecad9ffa97dab239dbfc607c4a1738">isSupportedType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a032c3c529239728e58f7fccdbcdbc033">llvm::ConstantFPSDNode::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#abc928b96601086c4735b9ea8331f0b9f">llvm::ARMTargetLowering::LowerXConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a2aa47f16031986718a30310f73c8c90c">llvm::X86TargetLowering::LowerXConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0da6ddfc44f329add717e0ac64b0b54d">llvm::ARMTTIImpl::maybeLoweredToCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a06205ea56e17027e23e321056e351c58">NormalizeBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae814004d3aa90fb312b7ac62cedb284">performLD1ReplicateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed80d9ad70fe74f3136dd25a2eee1c47">performLDNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d287a92051d679a9eb264a553c64ffd">performST1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a13534e47159f35c97e261aac72664214">performSTNT1Combine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d29144f0f49ccc2a115d389beaef36e">PerformVCMPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a90cebf16a00cfcbf593595502bd34be9">llvm::X86TargetLowering::reduceSelectOfFPConstantLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a824cd060277e4cb924783db572374c66">replaceSplatVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a535f1868c0897f3eee5851626fdfe5c0">safeWithoutCompWithNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d9cb8881ecb22d3225e564b5b2fb01c">tryWidenMaskForShuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a>.</p>

</div>
</div>

### isInteger() {#af975bf04c49cc895cfe38e7dc126a2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isInteger ()</td>
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

<p>Return true if this is an integer or a vector integer type.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6a1c71b7d20e3cf09cc8ff5a8efdb34f">canCombineShuffleToExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a064060d88e13e0fe28415d9bb1683b4f">combineAddOrSubToADCOrSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a16e4d757dd734397239791b2cbb221c7">combineCarryThroughADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada799c570dd41ead38f73ba71244c2b2">combineLogicBlendIntoConditionalNegate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a04f34c6d2aa331eb6fe9c1f1e52f2f9d">combineLogicBlendIntoPBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7324b1333eec1b04ee358d58c42834ef">combineShiftLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade03879f56390aad1613d54401f911a5">combineShuffleOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6da34b4a62e36f7b3b51720f19d3e753">combineShuffleToAnyExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad0f859410a5e693f74b9c87a59cb9b85">combineSubOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af01458f5f68de9153c5392eebedfa0f1">combineTruncationShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59c8bc2723e6744d5618db1f430fc94a">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3b1a609daab06e074288990116f07dc0">llvm::SelectionDAG::getAssertAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="#a587873e0de35da196d3f5fa6d60f738c">getHalfSizedIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#a9869cb9330f243cad6d20c176de62d19">llvm::SPIRVTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3f52b55c29541c64f2af910d479579f5">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9ff4217411d6a24d497a1a0d504a86c8">llvm::SITargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>, <a href="#a9cb27b88840e7d2d002f721594ec4578">getRoundIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a45c74ebe73ebaf0bd8463164e0b764">llvm::SelectionDAG::getShiftAmountConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6a2579bc0354806c6c9708b068777c3a">llvm::TargetLoweringBase::getShiftAmountTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aca0e8562bea682465caada8d71a47234">llvm::SelectionDAG::getSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1aad91323f0a3814a7918d472e6e5bbb">llvm::SelectionDAG::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8ab55d055af84ce8d884844d5171198e">llvm::SelectionDAG::getSplatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af37fa82c85e811c7ed496ebcbacf99c8">llvm::SITargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02127bae19ef433c1233c696317a8868">llvm::SelectionDAG::getVPZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acb51326eb72adb30e442667892c1f5ae">llvm::AArch64TargetLowering::hasPairedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad952c5828f21002a545e9de9f64cc4aa">llvm::X86TargetLowering::isDesirableToCombineLogicOpOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a81f0b427ff9a532ec2b6bf98c132db26">isLegalT2AddressImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a2813d266aebd06f8db45b0dab6bfaa01">isMImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ae48d974556a4a4ac56f2ce1f5ba11586">llvm::RISCVTargetLowering::isMultiStoresCheaperThanBitsMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1134e24a9f51b06d69b66aaede5eb422">llvm::X86TargetLowering::isMultiStoresCheaperThanBitsMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae14323a03c6bd118c28baa4bf381e532">llvm::AMDGPUTargetLowering::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a0ab8c631af35cb8fb070e4c1c5678377">isSimm7</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp/#a52ecad9ffa97dab239dbfc607c4a1738">isSupportedType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3ee90d2d8bdc505c6422560cd54d4a54">llvm::AArch64TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a1f7dae0343b89773eaaea832fc9f3ae5">llvm::ARMTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#ac0da0afbc93eeaad18d82408f439551e">llvm::MSP430TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#af075f198cd750d859857bb7b87544931">llvm::PPCTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a8aa9bbddf3b01dca458a497c72348b78">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a4f1989424b52e6c76aa2272e0e26a492">llvm::SystemZTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a02e65e6f505c44832bf833b385e51ba6">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac7b70a67bb5d182866c5485835286509">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8d59d0a2b9e117e74cd61f315aabf247">llvm::ARMTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adda85bdff9375435866fa2bebaca4b27">llvm::X86TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a0f5ccdafc0c37296755f59436f277115">llvm::XCoreTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab254961e69630f8f3d82f83429dd4be4">LowerMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0da6ddfc44f329add717e0ac64b0b54d">llvm::ARMTTIImpl::maybeLoweredToCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4ba6b9afcc5b700d4c09664b5fa009d9">llvm::ARMTargetLowering::PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7b49e80a5c71aff0a4a6d6a637cafe3f">performLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#add39487738bda59bdf85c85cb21b7e9a">performSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a60f3ecc52d65b8827909808283319dfa">performSignExtendSetCCCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af16b5429cba93f00c53d5d4627725516">simplifySetCCWithCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6e6c7bf0aa3c33fcec7be35b9437a505">splitVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab30bbf3bcf699a32f7113173b5cee991">llvm::AArch64TargetLowering::verifyTargetSDNode</a>.</p>

</div>
</div>

### isOverloaded() {#a38de8ca5ba228de0eba69c7dfa3639f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isOverloaded ()</td>
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

<p>Return true if this is an overloaded type for <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>

</div>
</div>

### isPow2VectorType() {#a59eee3929b9155fd268e3e3f6c0efde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isPow2VectorType ()</td>
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

<p>Returns true if the given vector is a power of 2.</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a53fb11c0140efce7e25ca9ff5ccbac96">getVectorMinNumElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">llvm::MipsTargetLowering::getNumRegistersForCallingConv</a>, <a href="#a15f3027fdcad3b33960402d9739afe4b">getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a04c394dca43220a262f8a67825cd4fb5">llvm::MipsTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21321ab7669a253fc0fe731602fe5695">llvm::MipsTargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a49ed4ed152a2f6e8533ccac1deb10ca0">performVecReduceBitwiseCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a>.</p>

</div>
</div>

### isRISCVVectorTuple() {#a7687d0ddaf12046ae258432e98ad083e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isRISCVVectorTuple ()</td>
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

<p>Return true if this is a vector value type.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Referenced by <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>.</p>

</div>
</div>

### isRound() {#ab41e50273c70287914ded0ae668bc507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isRound ()</td>
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

<p>Return true if the size is a power-of-two number of bytes.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">llvm::MipsTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a04c394dca43220a262f8a67825cd4fb5">llvm::MipsTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21321ab7669a253fc0fe731602fe5695">llvm::MipsTargetLowering::getVectorTypeBreakdownForCallingConv</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a176c5cbd80b59d908680911c34fdde6f">isOnlyUsedByStores</a>.</p>

</div>
</div>

### isScalableTargetExtVT() {#ad90cace0f677d0c16e4507465eff00a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isScalableTargetExtVT ()</td>
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

<p>Return true if this is a vector type where the runtime length is machine dependent.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="#a8a889af4545b49ab18942b3c726f7b13">isScalableVT</a>.</p>

</div>
</div>

### isScalableVector() {#ab8967b7214f38cdea9c0158dbe2ffa31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isScalableVector ()</td>
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

<p>Return true if this is a vector type where the runtime length is machine dependent.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a815d0ad0c6f04717c0dd61b12b44095b">llvm::AArch64TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="#aa994416d7190670c5fc0e295ebe6f6b0">bitsGE</a>, <a href="#a3ad406477784397709a339d5a2957b43">bitsGT</a>, <a href="#ae67a729c436915221367d8e77412dff4">bitsLE</a>, <a href="#a3bf257bfbd279ecfad670be03b00210e">bitsLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a670c95cba653503ce21f4abeea37cd2f">combineConcatVectorOfExtracts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04ad73999a08bcb1ee7f9db3a2d9322d">convertToScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad979c12cf8b226899e08c1c0d8bfdf8a">convertToScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59c8bc2723e6744d5618db1f430fc94a">convertValVTToLocVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#adeba9ee43ee94300c5bb47b99b47a945">findMemType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#adc81cc844c6c6c32c8be216807aa54f5">FoldBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acaa0f01ce8216a0cc8704e2a086805c2">llvm::AArch64TargetLowering::generateFMAsInMachineCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a7c14a3a22d127469c3490092627c2368">getPackedVectorTypeFromPredicateType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a94f640528921c3098a4dbaeef460e2ae">getPredicateForScalableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc1bb69bd08d87b899c1a5d9866acea1">getPredicateRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa83fc29419d3244b75d7a1d31d8d10d2">getPromotedVTForPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4fce00050967f2d8237319f1912a0103">llvm::AArch64TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6cf51cce9a6839a2849aeadcc0312d31">llvm::RISCVTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af3da6f92909b5cf14f30953a302edd34">llvm::SelectionDAG::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a093fa508bcdccd1b9172fc87797c8cd6">llvm::SelectionDAG::getSplatSourceVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a444be9352256919a844309a35dffa0f8">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1cdb38ba97d3ced9be618b22a8053581">getSVEPredicateBitCast</a>, <a href="#ae245d70802e4ebe1cae2b6122c62a22a">getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7567a37e7689d3f5b2cce9441597b37a">llvm::RISCVTargetLowering::isCtpopFast</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a0b3bbcd8728609a52e420775a7f7cf">llvm::RISCVTargetLowering::isExtractSubvectorCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a40892ab1e0ab2dcb208fdedac55ebd2b">llvm::HexagonSubtarget::isHVXVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a2548c54b76e921b3e1c0350002cf6fc1">llvm::RISCVTTIImpl::isLegalMaskedGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62748fc6c30d6e3f7c851344bd2dfd4d">isPassedInFPR</a>, <a href="#ab41e50273c70287914ded0ae668bc507">isRound</a>, <a href="#a8a889af4545b49ab18942b3c726f7b13">isScalableVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa5950e8440c6d4ecdaf950affa6a8e97">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a95c8b57eb11e8d25decddd3c86c9703c">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isSupportedRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a768562b4668773f96f4ac2d425a5d547">isUnpackedVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aea8c2b718c1dd866d61c29081c1eb44f">llvm::RISCVTargetLowering::joinRegisterPartsIntoValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7cdac11a3fa70f7ccb30ead4228dced4">LowerVectorMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab22a8cab92ee5978be7e541e30667c55">performBSPExpandForSVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af84a0dc03b9bdd1ccfd5f88dae1a4aab">performBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab253557e698e63e5f05d8d9dd1d91f5">performExtractSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77e5d35ccfe68c41092edc168cfb393e">performFirstTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d8e109ce3c796c31524f5a06dd745ac">performSVEMulAddSubCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af2093ca4a132848caa9d8acc509df1b2">ReconstructShuffleWithRuntimeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0670f21ebeafbaab3f4b34c8140b8dc8">replaceZeroVectorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a750e795af7ca75cfebb03e563cbaddc5">SelectOpcodeFromVT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a06dd823fa615051cc96e1d7b9de7a2bb">llvm::AArch64TargetLowering::shouldFoldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa03cec0d3e2e816167f41ac37995f274">llvm::AArch64TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8695950995820e5f6c0407c68f91f44f">llvm::SelectionDAG::SplitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af415da4daf8365b80a0f0dba2ee8490e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastFixedLengthToScalableVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac490424228331c1beb5025ef6d45d2a6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastScalableToFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aedd894c113704ea926d5339d9f1aa2e7">trySimplifySrlAddToRshrnb</a>.</p>

</div>
</div>

### isScalableVT() {#a8a889af4545b49ab18942b3c726f7b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isScalableVT ()</td>
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

<p>Return true if the type is a scalable type.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#ad90cace0f677d0c16e4507465eff00a8">isScalableTargetExtVT</a> and <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a415e74316c092fb208d6725d7ee4ff95">canLowerSRLToRoundingShiftForVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>.</p>

</div>
</div>

### isScalarInteger() {#ad958859a7af278dd5ea2b593c2b25050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isScalarInteger ()</td>
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

<p>Return true if this is an integer, but not a vector.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d33df2c00851a783858052d263c2546">combineBMILogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bd495ab23d43ebbe7e2d167103d8991">combineCastedMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6d9136998f9ff100ad8449a69477ab94">combineScalarCTPOPToVCPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a57f2ddafb29f40fe83f17e93300e1a71">combineVectorSizedSetCCEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8f2ba5f07dc33b4bc9b5f75cc71c731d">llvm::ARMTargetLowering::convertSetCCLogicToBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a91d45f6f637b1db940277d23e6d471db">llvm::PPCTargetLowering::convertSetCCLogicToBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aa268221b0c532cecb1b9675c614edac1">llvm::RISCVTargetLowering::convertSetCCLogicToBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2627fe486a9df16c64c587e341943318">llvm::SystemZTargetLowering::convertSetCCLogicToBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#abba0e811da8d1436a96fda0e356a6d24">llvm::X86TargetLowering::convertSetCCLogicToBitwiseLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a4b9031dbdb100545e0f3a0c0b11efe03">llvm::LoongArchTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a700728edd4a6a3ebe5797715cb535874">llvm::PPCTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a4608dc92a33ef6d74921a28eaa20140d">llvm::RISCVTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a5aaa4e25dcb7c49efaa3a2a5423a9416">llvm::XtensaTargetLowering::decomposeMulByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a20da1c5593bda4b444a75755223a96fe">getReducedGprRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a3f2d2ccbfc46c0e13c61e6ef6980f309">handleCMSEValue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#af06956f4bacf1c2d150c176648e0b244">llvm::SystemZTTIImpl::hasDivRemOp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a347cc43c09f54dab457a45b11183461b">llvm::TargetLoweringBase::isPaddedAtMostSignificantBitsWhenStored</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6cc2cb7b5433e21565a41f6154b7c816">llvm::X86TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a641563566f08db6108848bf61de2f323">isWorthFoldingAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2ee3671994de5e466ba0feabe827bf5d">LowerSELECTWithCmpZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae2006316fe1239e3e559f680aa00e365">performAddCSelIntoCSinc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a635ad8d6dba2689cc34e3bb3fb12c2a6">performAddUADDVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ace90a1ae5966f6c7a0830a440698d4c5">performBITREVERSECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6249d1435318ffc44640d1b46f4ac294">llvm::AArch64TargetLowering::preferIncOfAddToSubOfNot</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a36f078885862bc3b837dcfe057d05649">llvm::ARMTargetLowering::preferIncOfAddToSubOfNot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a79450c12a2b980587b2b71d175b15f11">llvm::PPCTargetLowering::preferIncOfAddToSubOfNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae0ba07379c6e2b16764ab8ac1cacb13c">PromoteScalarIntegerPTX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#adafeb00ea78374224e3589c91b88f02e">truncateScalarIntegerArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5956dd38d2c4e11a90da91035b52096d">tryDemorganOfBooleanCondition</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a463fad626413d686ec86863553e1a559">useInversedSetcc</a>.</p>

</div>
</div>

### isSimple() {#a19738f4334d4de357b22349bbb56fb5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isSimple ()</td>
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

<p>Test if the given <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> is simple (as opposed to being extended).</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a589a475ec9e7607bfb645905d5170402">llvm::HexagonTargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac897a80df1070effb9d5a5b6a023c5d0">llvm::ARMTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8d6a68be38777fb05ac35c8ac8ec0535">llvm::HexagonTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad5d9213c39b2fc64eaed3639539e8f65">llvm::PPCTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#aba88c9378ff5001a15ced63b0212cd10">llvm::R600TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="#a25eda78153285bc3bc4708e149b7e9e8">changeTypeToInteger</a>, <a href="#ad9d00ad929ec93255787f7f80c4659d9">changeVectorElementType</a>, <a href="#a0351571482fea42a3b326147fb2ce9e2">changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6d9136998f9ff100ad8449a69477ab94">combineScalarCTPOPToVCPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79354a2324d1cc1c1fd42e5d8a771479">llvm::createUnpackShuffleMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#ac9784ca12ba090d5ab2924df8f535a86">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#a7fbc8a0e79b77a4eec73dceef97127a4">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f80d4b8b70f58b247193379a39d5541">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5dcb8d597c1066eec7ef713b758f78f4">llvm::ARMTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa0e22cc6f0e4ea9717d5ad07df6806ee">llvm::X86TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a646cdefda88e785573dffb15889de1d1">llvm::ARMTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a8728267f1d12f3c91b61da0187e4be7d">llvm::X86TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a45b557c1f3f224d01fc38c055ced3c58">llvm::AArch64TTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ad8dd87df6641e5698b9af97fd574b186">llvm::ARMTTIImpl::getExtendedReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4f87d8844454c664483111762bd8dab7">getExtensionTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a5d1ff741add38ce427dcd488424274fe">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getHvxTy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7cf79a6310f5976179616844e2fab292">llvm::X86TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a5bbf78518932b5f97922ea947063ed58">llvm::X86TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4cbc62bcd4117c7767755022e0ef6a8a">llvm::ARMTTIImpl::getMulAccReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a391ef092ff421faccdfef4cb88424742">llvm::HexagonTargetLowering::getPostIndexedAddressParts</a>, <a href="#a1ab39b6dd48de0a16afa90214d78b2c4">getRawBits</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5cec24eb4eadf1232a1463fdbb1cc1a0">llvm::FastISel::getRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3f52b55c29541c64f2af910d479579f5">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0c4f8734623aa917fe30c3cce1abf4a3">getShuffleHalfVectors</a>, <a href="#a6a81c1cc06a00a0096d839032b5984e9">getSimpleVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2b15e3bc244c5fde8d06c39e9fc7ef6d">getSVEContainerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb74cb21d8fa460f25834fb226bfc6fa">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae903428eabca0546973c2695d608bbc9">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0f73140cd7f0b2c566b8ee7c1b86042d">getTargetVShiftNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7c335b50ec450e5955b50d2ea468ea78">getVectorLoweringShape</a>, <a href="#ae245d70802e4ebe1cae2b6122c62a22a">getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acb51326eb72adb30e442667892c1f5ae">llvm::AArch64TargetLowering::hasPairedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="#a50fc902bfa2d3dd0cf0fef0a4790716a">is1024BitVector</a>, <a href="#a6db1f207286bd8bc6a978593a55955e9">is128BitVector</a>, <a href="#aa8dc60b275ae1a147a9b24d4ccdfd305">is16BitVector</a>, <a href="#a767efe6535626636e7b78470235b5175">is2048BitVector</a>, <a href="#aacd05b71fb3b325dcc53a7df09d37edb">is256BitVector</a>, <a href="#a407fe71968756ae65989f791f641c375">is32BitVector</a>, <a href="#a8eed7940698816c772ded7b098f2e1a1">is512BitVector</a>, <a href="#afa40b0ea2c1858e1e297227cc17d77db">is64BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aec601d177f33c89713cff3857f97aa77">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a607229211531af1259b2603df68033f0">isConstantSplatVectorMaskForType</a>, <a href="#abda309a31acb43c06215c1772727bf1c">isExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5961d8a9524e219b55d22dc9e43e15af">llvm::HexagonTargetLowering::isExtractSubvectorCheap</a>, <a href="#a920f0719057d7352f9da10908859368d">isFixedLengthVector</a>, <a href="#a3cb888a2ce8e95e0d9769687a5e2f7d8">isFloatingPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa5bf9253e7424a041215974fc5696ac8">llvm::AArch64TargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a3e2659b4bac369ae2aa509712d6af245">llvm::LoongArchTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a9ae8be871dd199c4ba70bd599afb181b">llvm::RISCVTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a85d61a5d0c2951b9e414a3a3112ad909">llvm::SystemZTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab5a3a214752cd4c83a68f99de65ad908">llvm::X86TargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a350cbdd9ddbb2a048799fca9d93f3993">llvm::ARMTargetLowering::isFNegFree</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a90186243528cfcd7b02837f130da5de2">llvm::PPCTargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a40892ab1e0ab2dcb208fdedac55ebd2b">llvm::HexagonSubtarget::isHVXVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab57d04d7949ffdf008c6a2e222ebbe43">llvm::TargetLoweringBase::isIndexedLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a623aec2b1908acf20c615e16a870cc8b">llvm::TargetLoweringBase::isIndexedMaskedLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acc21c72422f4757e0d633c2f380abde6">llvm::TargetLoweringBase::isIndexedMaskedStoreLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a0fd231e43d25de7b9d908c140a5a29f0">llvm::TargetLoweringBase::isIndexedStoreLegal</a>, <a href="#af975bf04c49cc895cfe38e7dc126a2f1">isInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad09933ec95486d26cd31cf1536190091">isLegalAddressImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a14ba388c0893657958340f94a164faa9">llvm::ARMTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abd6384b6c46252ca57f5d73b5ffd8076">llvm::RISCVTargetLowering::isLegalElementTypeForRVV</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a460fe5aea074c37615e0106c2a13a1e4">llvm::TargetLoweringBase::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="#ad90cace0f677d0c16e4507465eff00a8">isScalableTargetExtVT</a>, <a href="#ab8967b7214f38cdea9c0158dbe2ffa31">isScalableVector</a>, <a href="#ad958859a7af278dd5ea2b593c2b25050">isScalarInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9fdafe65d9378c70d936af1019040b0f">llvm::X86TargetLowering::isShuffleMaskLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp/#a52ecad9ffa97dab239dbfc607c4a1738">isSupportedType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ad8a821e221b81ea4fa8dc4653072ff1c">llvm::HexagonTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="#aa54976197fff266f4143beb44fc9764c">isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a27f76de53b5b15274dbf8e4f30adf81c">isVectorElementSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac7b70a67bb5d182866c5485835286509">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8d59d0a2b9e117e74cd61f315aabf247">llvm::ARMTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adda85bdff9375435866fa2bebaca4b27">llvm::X86TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a0f5ccdafc0c37296755f59436f277115">llvm::XCoreTargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6512c9219b1c585d57adf5bbf276cba6">LowerADDSUBSAT</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionimpl/#a2ff692eefcb74ae2bbd96ff5f9241287">anonymous{TypePromotion.cpp}::TypePromotionImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac399325c88de95b03c19e68e1229a8f7">llvm::FastISel::selectBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a59ec796e4ddba85e210d5a226d56f16f">llvm::FastISel::selectCast</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1434fc5d1782f15a392af0320f13f6c7">llvm::FastISel::selectExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a5ed109e1cb014423460d747d1bad657c">llvm::HexagonDAGToDAGISel::SelectIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#af4925542ba74593f756efe144083d031">llvm::HexagonDAGToDAGISel::SelectIndexedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ae39c938299ddc0dc8534e1a05cb0c2fc">llvm::ARMTargetLowering::shouldConvertFpToSat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a0b23f096c92f38f9001ae3ea9ddc8dde">llvm::RISCVTargetLowering::shouldConvertFpToSat</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b6f74fbe8b15567434fa5d20a540c5c">llvm::TargetLoweringBase::shouldFormOverflowOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a0023312f4ffae5c8a127a8da0c812dba">llvm::X86TargetLowering::shouldFormOverflowOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70ab6e6fcc6015c6cdce1aa4497cd7f5">supportedVectorShiftWithImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6f5f3de82cbdb6a05c7f49ecf791382e">supportedVectorVarShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1efa0c093d9b13546c2b2dc1d699c517">tryGetOriginalBoolVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9b97177f4c89df3fd0a2f05deec3378f">usePartialVectorLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#afa8bfec034d066ec24d18d3fd76ac590">llvm::AArch64TargetLowering::useSVEForFixedLengthVectorVT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>.</p>

</div>
</div>

### isVector() {#aa54976197fff266f4143beb44fc9764c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isVector ()</td>
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

<p>Return true if this is a vector value type.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a19738f4334d4de357b22349bbb56fb5c">isSimple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a068555b4b66d140162c7d3c2cb16beae">adjustLoadValueTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#acca525d32f859c8c653921b5fff62ed3">llvm::X86TargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad5d9213c39b2fc64eaed3639539e8f65">llvm::PPCTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a25d4d29a2e8f87e039add92fe76ef88c">llvm::RISCVTargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7fdb4a73925c17adcb4eaeafda02978d">llvm::X86TargetLowering::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a90fd5f576348f26036497e8de8a3a15c">CanCombineFCOPYSIGN_EXTEND_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#ac8600b395666a2e54d6f347b58df6f62">canExpandVectorCTPOP</a>, <a href="#a4e6e40b44c47abc845e297c30bbf830c">changeElementType</a>, <a href="#a25eda78153285bc3bc4708e149b7e9e8">changeTypeToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#addec051710bc0afc4147859062eb31a4">CollectOpsToWiden</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af59e4da255e65a90b6c4710be399b9e6">combineAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5f71cfbbaacd538471dd7b3e5da4733b">combineBitcastToBoolVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae63d3420be279c225fb7bad70c0b8046">combineBoolVectorAndTruncateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bd495ab23d43ebbe7e2d167103d8991">combineCastedMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad45a536ce828d7fe0a889a1666437654">combineConcatVectorOfCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad2800cb88996291ed1676f5899997ebe">combineExtSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1e500fbed9b5849bfd76724ccf3825">combineFMinNumFMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2336d9f0305e57b22c5be16c73caa">combineMulToPMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a42586d078a0c852f7571d5d4fb0daa04">llvm::VETargetLowering::combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac1953eca2805574de12debdab3116430">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7094504ff72e8db0894faac2216aa00a">llvm::VETargetLowering::combineSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad7c52d56e60df127f4f9a429a5455590">combineSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7324b1333eec1b04ee358d58c42834ef">combineShiftLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#afa64cc7dfc401b9825b62c2b19808ad0">combineShiftToAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab5a426cb5c2105ca954c4ab9f12ef76f">combineShiftToMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab73df8541f091c30ed34fd2c89c57746">combineShiftToPMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a69d159ccc8c9f4f70ed369d35c5c420b">combineShuffleOfBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a68b7af58bc3486a7e1a872337cee003f">combineTruncatedArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aac1c6dbf15b6867cf3e1d11b7a02c289">combineTruncOfSraSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#accd2edb7bf3dca29f9a0f5e233134d09">combineTruncSelectToSMaxUSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a321df2422ee45cfd96e738928fb178f7">combineXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#acab5bf267b2b761c038dd0976779a5e9">constructRetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a35f30c99560e45f1031fe1855c73b02c">llvm::X86TargetLowering::convertSelectOfConstantsToMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0841165650bd49aa4995c4dfa3fdf650">detectPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac2e1d91d4013f7c45951b5fb918f94f0">foldIndexIntoBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa8e7d7856b86905a5ce055fb23d0c9b2">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5d53350abda65b1649007d310f0714e9">llvm::SelectionDAG::getBitcastedAnyExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a21815640f1226ac80cfb06d82b0213bc">llvm::SelectionDAG::getBitcastedSExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a41a7b504ed10d1af75b756e5804133b6">llvm::SelectionDAG::getBitcastedZExtOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/vecustomdag/#a33828d2d1154bc3142d35300e0460959">llvm::VECustomDAG::getBroadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad1ed10076dcd144800421886c7caea42">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6d7162a570369a85f2a5238452e196e3">getEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="#a587873e0de35da196d3f5fa6d60f738c">getHalfSizedIntegerVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0d2d9c6df58f2916c90d15bc635d871f">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42bf7ed3daec395fe644414494888bc6">llvm::TargetLoweringBase::getNumRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a7d161cb9d6e4a3ef9c4af88bef2d3ab4">llvm::MipsTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa8ee36cbd5d910c4f4a1d899a109baf6">llvm::SITargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#a9869cb9330f243cad6d20c176de62d19">llvm::SPIRVTargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aba30f84d7fd0dd3361ff92fe1e53d9ca">llvm::X86TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#af4269b2cd295687cb69f61729f91de3b">llvm::ARMTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a22338caf16030dc171ee6dfb5580d308">llvm::ARMTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7e08a461c58c82e0564d2cd25c6d9990">llvm::PPCTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a70e999991e3aeb3052927df01099bf4c">getReciprocalOpName</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a017a91fde9e329082de784114d8f137c">llvm::SelectionDAG::getReducedAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a3f52b55c29541c64f2af910d479579f5">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a04c394dca43220a262f8a67825cd4fb5">llvm::MipsTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9ff4217411d6a24d497a1a0d504a86c8">llvm::SITargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#aa3b5623e42a15bdd63bfea603699d01d">llvm::SPIRVTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a0b74111574af484ef33597940f5e9c56">llvm::SystemZTargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7c19f0fe8ae2a12ed0c5cf142a520522">llvm::X86TargetLowering::getRegisterTypeForCallingConv</a>, <a href="#a9cb27b88840e7d2d002f721594ec4578">getRoundIntegerType</a>, <a href="#aa85c75e8eb097f02caeb5b9119eebfef">getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa16505b46d66798daa417510b68ee4ac">llvm::ARMTargetLowering::getSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2c237b0f007548cb6bc021d00ffee87f">llvm::SelectionDAG::getSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4fce00050967f2d8237319f1912a0103">llvm::AArch64TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a667a905e2496f6b0b9c7915a97f58da1">llvm::ARMTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#aedbcc9ff827c2906f48ea77fa6736007">llvm::AVRTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetlowering/#aea1223f03c63339534884b7dc67ed3bf">llvm::CSKYTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a9dae8eb30ecc1fabd7e64f4b713b6280">llvm::HexagonTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a3612d2574f9af7ad6fe1fbd439141ef3">llvm::LoongArchTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a38b88641f5f9abe6b18b921f0eaceb93">llvm::MipsTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#aa90aff23586273a6669ee0a23f385933">llvm::NVPTXTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#aea8d3912f4a0d003d32577f1098a8b44">llvm::PPCTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a92a4ac2a18c3585d85a9ed7023bdec9b">llvm::R600TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6cf51cce9a6839a2849aeadcc0312d31">llvm::RISCVTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1f4f77bf289589785c34e8eebc274dd6">llvm::SITargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ab6fdf85d994da1352162850ae53f7020">llvm::SparcTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a344d2899c3ac0b0d124ace1fe503f56d">llvm::SystemZTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76483b2b4498079d3778c57326c39e99">llvm::TargetLoweringBase::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae93a1ba51c086441ec1b9ea4cdca853a">llvm::X86TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a9cd8e49a0ab3c32b798c972a75a6611c">llvm::XtensaTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02e9a5f0cb0b32dac5ce2e5e329b2abd">llvm::SelectionDAG::getShiftAmountOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6a2579bc0354806c6c9708b068777c3a">llvm::TargetLoweringBase::getShiftAmountTy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada7f52028e75ee798b0fbbde2445b95e">getShuffleScalarElt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af3da6f92909b5cf14f30953a302edd34">llvm::SelectionDAG::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a576060235339ed4cc1615a55ed869bf0">llvm::SelectionDAG::GetSplitDestVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb74cb21d8fa460f25834fb226bfc6fa">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae903428eabca0546973c2695d608bbc9">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0b1f78ee0016593bc78e5a7d926ee668">llvm::AMDGPUTargetLowering::getTypeForExtReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1b6d700f803718300ba21413283f7eb">llvm::getTypePacking</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a28cd6368ac9562cde04d4865813b82d5">llvm::TargetLoweringBase::getTypeToExpandTo</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7c335b50ec450e5955b50d2ea468ea78">getVectorLoweringShape</a>, <a href="#ae245d70802e4ebe1cae2b6122c62a22a">getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#af37fa82c85e811c7ed496ebcbacf99c8">llvm::SITargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9f81a81b890192ac2e40f2995080feaa">llvm::X86TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02127bae19ef433c1233c696317a8868">llvm::SelectionDAG::getVPZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9130245943505c30b0ba979c8a77d723">getZeroVector</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa69a30633eb175372a93a42bfc5d89f2">llvm::AArch64TargetLowering::hasAndNot</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a33e56801bdba0e16aa88b5e81fee88d5">llvm::VETargetLowering::hasAndNot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a69fbe6a7969fadd37ebea537ba3041e3">llvm::X86TargetLowering::hasAndNot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a49d50ba3cb52f8e5e6d34c6cec90a3e5">llvm::RISCVTargetLowering::hasAndNotCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a8e8d15fa57104d892b14366c39fafa77">llvm::X86TargetLowering::hasAndNotCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad952c5828f21002a545e9de9f64cc4aa">llvm::X86TargetLowering::isDesirableToCombineLogicOpOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aaae643b7e80395e0c51c7bc29912f31d">isExtendedFrom16Bits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a9ae8be871dd199c4ba70bd599afb181b">llvm::RISCVTargetLowering::isFMAFasterThanFMulAndFAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0bf38c29e86627800a241dc0f1005d5c">isHorizontalBinOpPart</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a40892ab1e0ab2dcb208fdedac55ebd2b">llvm::HexagonSubtarget::isHVXVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a494cbaa147365ad6fd75c3bb3297c8bd">llvm::AArch64TargetLowering::isIntDivCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ad0f72d43380dc7896c344a32bb9b4953">llvm::RISCVTargetLowering::isIntDivCheap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ac7a7243ff0d08f8e17239f3fab12a20f">llvm::X86TargetLowering::isIntDivCheap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a81f0b427ff9a532ec2b6bf98c132db26">isLegalT2AddressImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a8ab3eaadf7f52ab7ca677e6c545e6508">llvm::X86TargetLowering::isLoadBitCastBeneficial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c242ac8227e53a677e25cac39aaad82">llvm::isMaskType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a2813d266aebd06f8db45b0dab6bfaa01">isMImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">llvm::ARMTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a67dbc70a08c8d7078e23f0a57a9ffbbe">llvm::RISCVTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae14323a03c6bd118c28baa4bf381e532">llvm::AMDGPUTargetLowering::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad0581b9db1cc9ac63ca3c7eb944d4fd8">isPackedVectorType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0346da3fb8d131cf057b3f5c1757400b">llvm::isPackedVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a0ab8c631af35cb8fb070e4c1c5678377">isSimm7</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa5950e8440c6d4ecdaf950affa6a8e97">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp/#a52ecad9ffa97dab239dbfc607c4a1738">isSupportedType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3ee90d2d8bdc505c6422560cd54d4a54">llvm::AArch64TargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a1f7dae0343b89773eaaea832fc9f3ae5">llvm::ARMTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a8aa9bbddf3b01dca458a497c72348b78">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a731fed7d3e9a9ebe3a9940afd6a3bdc2">llvm::RISCVTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4217293101179a3839b8afb1fafb2e0d">llvm::X86TargetLowering::isTypeDesirableForOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a27f76de53b5b15274dbf8e4f30adf81c">isVectorElementSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad34aa0262dce6014056d3d3be02682af">isVShiftLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad34aa0262dce6014056d3d3be02682af">isVShiftLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac25de93a27afbf8db3303c5f841075b6">isVShiftRImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03ce20d2138535663fed2e0fcc5ec604">isVShiftRImm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6601dcbc51d3043764e700c20db26e9c">llvm::X86TargetLowering::isXAndYEqZeroPreferableToXAndYEqY</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a02e65e6f505c44832bf833b385e51ba6">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac7b70a67bb5d182866c5485835286509">llvm::AArch64TargetLowering::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a9440e31a32ea6624c0b77e7e45223be9">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::LegalizeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6fd620f229a9cde3e60fc77ab234cd1e">LowerCTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b4d189fb624411d2c3e6d460da3796f">llvm::AMDGPUTargetLowering::lowerFEXP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a57a0d1b6cabb33defc1c9f2d2d82a7f8">llvm::VETargetLowering::lowerLOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a07bef52d3581440af08be07591f29990">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9f5002398f225b7a1c111cb707669258">llvm::VETargetLowering::lowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4110b1e3bbc8037545ca4a7440a681b1">LowerTruncateVectorStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#abc928b96601086c4735b9ea8331f0b9f">llvm::ARMTargetLowering::LowerXConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad6940a3eec597c799eeee15cb0f7e808">llvm::X86TargetLowering::mergeStoresAfterLegalization</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6dba756ac7230f1732b09161ca525bdd">padEltsToUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a05b3fae8db805d575354f7d359d11c5e">PerformADDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a2ce1fcf4e82d82ce6c46cb189b1100a3">PerformFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4118089abb4cbadaf4b698cbbe05154f">PerformLOADCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a313d642b3a7b838825ec80b84909b9ce">performMADD_MSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abf0bc161f51dbc01add0270eb00b2f77">PerformMinMaxFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a11579efb56ca3f28a43e11ddf6011a1d">performMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa26e9cc2dafb4d8b4af1d6e8f252ef09">performMULCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab049ba889709df922c683e1961c32ae9">llvm::AMDGPUTargetLowering::performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a85cbf79249f0c5054e0ff0ab3f351090">PerformMULCombineWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a3e110576778e9ccf929885efddeea4aa">llvm::AMDGPUTargetLowering::performMulhsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a09d46d8519c83130e03376d0d2e0008a">llvm::AMDGPUTargetLowering::performMulhuCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5c12d92b2d9e291ad311d1468da07410">performVectorCompareAndMaskUnaryOpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a099d3d496bc5d6948101f22543d154b9">llvm::X86TargetLowering::preferSextInRegOfTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ade6927c3ebfbd00cbede63e5a1d1426d">PromoteBinOpToF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5ca0a8558bfafc5249f833982956d4cc">PromoteMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d18c51ca04dfa5c2b56ad650ab0d7d9">replaceBoolVectorBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a273d2011b48b740db185cdcdf4decf76">llvm::AMDGPUTargetLowering::shouldCombineMemoryType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a85fb0d7e000c96b972014b0405aa9c88">llvm::X86TargetLowering::shouldFoldConstantShiftPairToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adaff89efc72db02240bc69c44c8f0691">llvm::X86TargetLowering::shouldFoldMaskToVariableShiftPair</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a1652477e0e5b2968e8d160f87031cdf5">llvm::RISCVTargetLowering::shouldFoldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5cd2ddff46dc5822bcc7666e336da52b">llvm::X86TargetLowering::shouldFoldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b6f74fbe8b15567434fa5d20a540c5c">llvm::TargetLoweringBase::shouldFormOverflowOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a0023312f4ffae5c8a127a8da0c812dba">llvm::X86TargetLowering::shouldFormOverflowOp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9a0590fb25613550cffc505a2affc293">llvm::TargetLoweringBase::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ad3e6a84b6c78f3b26132a2f124749347">llvm::AArch64TargetLowering::shouldTransformSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a8400b6de80b208779f0ec1f1e83ddb95">llvm::RISCVTargetLowering::shouldTransformSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a193b8c17079133af40829a1fef4adf6c">llvm::X86TargetLowering::shouldTransformSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af16b5429cba93f00c53d5d4627725516">simplifySetCCWithCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af587fdddecfd87186f09f4b1e9b4bc0a">llvm::SelectionDAG::SplitScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a01001268634e40bee4795018346e91b4">llvm::SITargetLowering::splitTernaryVectorOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a95e6431ff6ad6b548c061a19df107850">llvm::AMDGPUTargetLowering::splitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0bd751c4c85d494e52e578b6bc10f8bc">llvm::AMDGPUTargetLowering::SplitVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6f0cac8b7a7acd364d34649335444ceb">stripModuloOnShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aca53f243b0008543a30a78356ac59010">llvm::AArch64TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a98a503af3a695653b6093323a1c4b9cf">llvm::ARMTargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a39ed92e826ef5d0893f72b26fab78aa3">llvm::RISCVTargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adcd2433bf37019679f7e14d3b8cd7708">truncateAVX512SetCCNoBWI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af4956a6ceaf1627102278355b386f44e">tryFoldToZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1efa0c093d9b13546c2b2dc1d699c517">tryGetOriginalBoolVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab30bbf3bcf699a32f7113173b5cee991">llvm::AArch64TargetLowering::verifyTargetSDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab2278ad575ade428648fc629fb5ecb45">widenAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ab9c026bf7b5362d2b79a43bd04e769a7">widenVec</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6dc0d17c5d20afdfa4004345e930584c">widenVectorToPartType</a>.</p>

</div>
</div>

### isZeroSized() {#ae2ee94a616a11388828c36d1e0b4798c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::isZeroSized ()</td>
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

<p>Test if the given <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> has zero size, this will fail if called on a scalable type.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ad96fee81c3174ef427bf779d73fb1ef2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4acc56660c01a31efea93dc0e9ea8ad">llvm::TargetLoweringBase::allowsMemoryAccessForAlignment</a> and <a href="#a470621733f1ffb597e6f502040216da4">isByteSized</a>.</p>

</div>
</div>

### knownBitsGE() {#ab9182379fc7c4d4b8031f1a81221fafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::knownBitsGE (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if we know at compile time this has more than or the same bits as VT.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGE</a>.</p>


<p>Referenced by <a href="#aa994416d7190670c5fc0e295ebe6f6b0">bitsGE</a>.</p>

</div>
</div>

### knownBitsGT() {#a510d9e3eba90bc4a7e9925583fbccc3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::knownBitsGT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if we know at compile time this has more bits than VT.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGT</a>.</p>


<p>Referenced by <a href="#a3ad406477784397709a339d5a2957b43">bitsGT</a>.</p>

</div>
</div>

### knownBitsLE() {#a1cd3e03c399e181366f177964eaae62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::knownBitsLE (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if we know at compile time this has fewer than or the same bits as VT.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a338ba7ca7a526243ab1853d07d90fe38">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLE</a>.</p>


<p>Referenced by <a href="#ae67a729c436915221367d8e77412dff4">bitsLE</a>.</p>

</div>
</div>

### knownBitsLT() {#a7bcabb100313dd886a3b9ce7b599337c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EVT::knownBitsLT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Return true if we know at compile time this has fewer bits than VT.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLT</a>.</p>


<p>Referenced by <a href="#a3bf257bfbd279ecfad670be03b00210e">bitsLT</a>.</p>

</div>
</div>

### print() {#ad01a572f584fc9431b4b58eda40075a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::EVT::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Implement operator&lt;&lt;.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>Reference <a href="#a923e1e1096d253c80d8a241754cb878f">getEVTString</a>.</p>


<p>Referenced by <a href="#a6ccc5defb5558c1aad8b592b0352ae90">dump</a>.</p>

</div>
</div>

### widenIntegerVectorElementType() {#a7913deec1cb15f66661ba96b54391fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::widenIntegerVectorElementType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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

<p>Return a VT for an integer vector type with the size of the elements doubled.</p>


<p>The typed returned may be an extended type.</p>


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="#a752372e170e4e7c595bf8810bb52adf2">getIntegerVT</a>, <a href="#a45e76d44a189e456d52e37ba3dda0fce">getSizeInBits</a>, <a href="#a3d102abca1c9c95f36546dff2f39273b">getVectorElementCount</a>, <a href="#abc4c6365ade17ad4443ad0e381e7479d">getVectorElementType</a> and <a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### changeExtendedTypeToInteger() {#a379f30d5c6c3cd97ebb5fc1a428bcff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::changeExtendedTypeToInteger ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### changeExtendedVectorElementType() {#abdb0b5938523e13297a0355e2068942b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::changeExtendedVectorElementType (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> EltVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### changeExtendedVectorElementTypeToInteger() {#ac1728d74cf34337d36576208b279b42b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::changeExtendedVectorElementTypeToInteger ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### getExtendedSizeInBits() {#aa51f7d097e42c8007368cffae5042072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize EVT::getExtendedSizeInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### getExtendedVectorElementCount() {#ac40e284a4abd29b622292e55f706b019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount EVT::getExtendedVectorElementCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### getExtendedVectorElementType() {#af5262fef9df4b016ee7c0262b073f5be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::getExtendedVectorElementType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### getExtendedVectorNumElements() {#a216ccc1c772127285c00583055dafbfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned EVT::getExtendedVectorNumElements ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended1024BitVector() {#a5530a624984971c9ef1c69eb3cb59c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended1024BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended128BitVector() {#ac0fe6961ba8683f5b7dfe9200c0e8ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended128BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended16BitVector() {#a44b2cb62bcf10ae424678cba7829ae08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended16BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended2048BitVector() {#a2ac1175d1deb088b8a57571cf3a4695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended2048BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended256BitVector() {#a0066573091b25b0b61742700da1bd6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended256BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended32BitVector() {#a9622b3fd44ba620deb2385b9e1134eff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended32BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended512BitVector() {#a76b4baead2bc9e7af713d864d6c7c288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended512BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtended64BitVector() {#a1b90e3d30759c68a3bf4fb119c3cc3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtended64BitVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtendedFixedLengthVector() {#a5688e84fbfdf8f6db9e7f1fd50adf06e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtendedFixedLengthVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtendedFloatingPoint() {#a314783e8ff418729775d102c31ad2f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtendedFloatingPoint ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtendedInteger() {#ac758bd6f5c454ffff8e6e4a387986fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtendedInteger ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtendedScalableVector() {#a235a9e0b06e3e044ac1fba0fa58a7ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtendedScalableVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtendedScalarInteger() {#a0971c7bf43884a214b157517e037bd8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtendedScalarInteger ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### isExtendedVector() {#a17c69a2302512946dfe1ee066b63b20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EVT::isExtendedVector ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LLVMTy {#afd16ea35c1ba5a89151427229d403966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::EVT::LLVMTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>

</div>
</div>

### V {#a532e3d47ccc8c419d53c21a494ad8fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::EVT::V = <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">MVT::INVALID_SIMPLE_VALUE_TYPE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEVT() {#a5db8faf73cf29bcefdb3bdfadf3dc2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::getEVT (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool HandleUnknown=false)</td>
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

<p>Return the value type corresponding to the specified type.</p>


<p>getEVT - Return the value type corresponding to the specified type.</p>


<p>If HandleUnknown is true, unknown types are returned as Other, otherwise they are invalid. NB: This includes pointer types, which require a <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> to convert to a concrete value type.</p>


<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa98aa825426dd4de2d19a3de9983a2d5d">llvm::Type::FixedVectorTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#afdce715c901d62e2c1367a0ff5248175">llvm::VectorType::getElementType</a>, <a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">getEVT</a>, <a href="#a752372e170e4e7c595bf8810bb52adf2">getIntegerVT</a>, <a href="#a210ba6b43ba451b698857dd9de71bd15">getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6188e4e2fb839d904debf0cbe7fc11f6">llvm::Type::ScalableVectorTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae01900ccd0d696ce7ede9d710415f162">llvm::Type::TokenTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#adaf74e11d3b6f4feaee9dd7711e92202">llvm::ARMTargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a9c91bde4107b00ee5520f121253437ef">llvm::X86TargetLowering::allowTruncateForTailCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsoutgoingvalueassigner/#a3df6a7e63762376a088acec41d1f3623">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::assignArg</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ac6db7ce806dd7cbdce7f3c1b06dcd54e">llvm::CallLowering::determineAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ad0c9ac06022884eb218dc8f8c4056e43">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getCastInstrCost</a>, <a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">getEVT</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a5d1ff741add38ce427dcd488424274fe">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getHvxTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a02b5aaf4357ae931647439e312a034bc">llvm::TargetLoweringBase::getMemValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a252df3516bdd18a47c638e745bcd01f4">llvm::AArch64TTIImpl::getPartialReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5997c4992589047ebc712b52b6e101cb">llvm::FastISel::getRegForGEPIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa262bd68fe6b244861c0a5d249d68c30">llvm::TargetLoweringBase::isExtFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a3076fea1b794e7dc299925aa153dd39d">isNoopBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a217b5b16e1040a5ad5578bd59f60f62b">llvm::HexagonTargetLowering::isTruncateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac04b69adb2b2657b80c8e86eb8e04099">llvm::HexagonSubtarget::isTypeForHVX</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a333bc33c92a4288cf0b3e4514f4cb075">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::lowerIntrinsics</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac399325c88de95b03c19e68e1229a8f7">llvm::FastISel::selectBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0c9502505ab5e9910350e241f20d976a">llvm::AArch64TargetLowering::shouldExpandPartialReductionIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8ef0473fe81ed643d4fe2e64c6a5b3e">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::shouldReplace</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a>.</p>

</div>
</div>

### getFloatingPointVT() {#a9a76e0197f5c34a3e15ba92fbdc9c8b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getFloatingPointVT (unsigned BitWidth)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents a floating-point type with the given number of bits.</p>


<p>There are two floating-point types with 128 bits - this returns f128 rather than ppcf128.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a063563f5f87a96c0cd15403eeacf458e">llvm::MVT::getFloatingPointVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### getIntegerVT() {#a752372e170e4e7c595bf8810bb52adf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getIntegerVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned BitWidth)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents an integer with the given number of bits.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a86754e919e3f94a9e4042267ce657f5e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6a1c71b7d20e3cf09cc8ff5a8efdb34f">canCombineShuffleToExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae63d3420be279c225fb7bad70c0b8046">combineBoolVectorAndTruncateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af72da135a7e8a925ffa9fbbb4ecf0b1f">combinePredicateReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#afa64cc7dfc401b9825b62c2b19808ad0">combineShiftToAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa51b13f3d4866613aac6907835f51f83">combinevXi1ConstantToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c2999836b5dd4ca2d272970cc0b9a0f">llvm::getApproximateEVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5d53350abda65b1649007d310f0714e9">llvm::SelectionDAG::getBitcastedAnyExtOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#acb8cf9e50c3979193572ea36f327d0a4">getCopyFromParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8910923e28ba24c5abedb60c66c86cc5">getCopyToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa1cac5332a31f59e2455eaad0fb11278">llvm::AMDGPUTargetLowering::getEquivalentMemType</a>, <a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">getEVT</a>, <a href="#a587873e0de35da196d3f5fa6d60f738c">getHalfSizedIntegerVT</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#a194d0b24bfe82015617637c7feafd34f">anonymous{DAGCombiner.cpp}::LoadedSlice::getLoadedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a7c14a3a22d127469c3490092627c2368">getPackedVectorTypeFromPredicateType</a>, <a href="#a9cb27b88840e7d2d002f721594ec4578">getRoundIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aed6a89a13d6da0fb09c283664b86ccd0">llvm::X86TargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a0b1f78ee0016593bc78e5a7d926ee668">llvm::AMDGPUTargetLowering::getTypeForExtReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af23e95d85be78026c607fa689dda4cd1">llvm::X86TargetLowering::getTypeToTransformTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af8920819f67500dd921827ee046e399c">getVectorBitwiseReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6f30e11353716cf175b1fb59b11cb6f4">llvm::AMDGPUTargetLowering::LowerDIVREM24</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad02dfd40a37e1c0fc6365a700c4263dc">lowerFCMPIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6ffcf0878851c4e84a8c11a68b07e9e7">lowerICMPIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa32a8c1fba431700b7564e94ea5ab4d2">LowerPredicateLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aedabf4c69af716c22c9957d6ca5758e1">LowerPredicateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a3756185351596750edbb4790d9923eea">llvm::SelectionDAGBuilder::lowerRangeToAssertZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abf0bc161f51dbc01add0270eb00b2f77">PerformMinMaxFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9b79346e8152f683a6ad35f8049c74ea">llvm::FastISel::selectFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a> and <a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a>.</p>

</div>
</div>

### getVectorVT() {#a210ba6b43ba451b698857dd9de71bd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getVectorVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned NumElements, bool IsScalable=false)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents a vector NumElements in length, where each element is of type VT.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1a0cd3e4178d08fadb03d4e4e9404dcd">addShuffleForVecExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a068555b4b66d140162c7d3c2cb16beae">adjustLoadValueTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#a0884e3469837e8ef87a3a989096f0809">BuildVectorFromScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6a1c71b7d20e3cf09cc8ff5a8efdb34f">canCombineShuffleToExtendVectorInreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#addec051710bc0afc4147859062eb31a4">CollectOpsToWiden</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c3d86d724323d88d2fdf99d29d3de72">combineBasicSADPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5f71cfbbaacd538471dd7b3e5da4733b">combineBitcastToBoolVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad45a536ce828d7fe0a889a1666437654">combineConcatVectorOfCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abee0476f2cd1449e29bfca26702bd865">combineI8TruncStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#afa64cc7dfc401b9825b62c2b19808ad0">combineShiftToAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2cc720ee13ee570307048e7940784be">combineToFPTruncExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa67e6dbc4f25b155ae19303e76819f6">combineTruncateWithSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab2361f33fc2b1c3908ad60fd0e437b6a">combineV3I8LoadExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8389740010ccf99686a066f0bdc4dbdc">combineVPDPBUSDPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac11671a35605d3033849a1e314831179">concatSubVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#acab5bf267b2b761c038dd0976779a5e9">constructRetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a009e2b4ee04eedc57c666678f3e8ef1b">convertIntLogicToFPLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0841165650bd49aa4995c4dfa3fdf650">detectPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a69f0725f2fda3046317ef070e37e06ec">expandDivFix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aecabf0b51b7f3a579c05fc08e06c265a">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d2572a2d7cf0d8584f28c2c1c2e14c8">extractSubVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a41d90ad30eef03eda7c41e46c1839ded">foldExtendVectorInregToExtendOfSubvector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a781a75dfc661452760864c019bafd96e">foldShuffleOfConcatUndefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c2999836b5dd4ca2d272970cc0b9a0f">llvm::getApproximateEVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#af47fbc357d61496b2ec06c60c79f6400">getCopyFromPartsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae968aa14d25b7b04bf82019ad48f599c">llvm::SelectionDAG::GetDependentSplitDestVTs</a>, <a href="#a3f78e3bf25a5e4bef300d42dde0d8477">getDoubleNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa1cac5332a31f59e2455eaad0fb11278">llvm::AMDGPUTargetLowering::getEquivalentMemType</a>, <a href="#a5db8faf73cf29bcefdb3bdfadf3dc2c1">getEVT</a>, <a href="#aee35a362966ced72913881d8a2dc3be8">getHalfNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a02b5aaf4357ae931647439e312a034bc">llvm::TargetLoweringBase::getMemValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a7c14a3a22d127469c3490092627c2368">getPackedVectorTypeFromPredicateType</a>, <a href="#a15f3027fdcad3b33960402d9739afe4b">getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a4fce00050967f2d8237319f1912a0103">llvm::AArch64TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a9dae8eb30ecc1fabd7e64f4b713b6280">llvm::HexagonTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#aa90aff23586273a6669ee0a23f385933">llvm::NVPTXTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6cf51cce9a6839a2849aeadcc0312d31">llvm::RISCVTargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1f4f77bf289589785c34e8eebc274dd6">llvm::SITargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae93a1ba51c086441ec1b9ea4cdca853a">llvm::X86TargetLowering::getSetCCResultType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#af11e81ec39d8b1108c8aae7a8cc4d605">llvm::AMDGPUTargetLowering::getSplitDestVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a798a85d56b9dc609e615130607563819">llvm::AArch64TargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a75880fa01f2a6719716b1e3ac002f40e">llvm::ARMTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a3e8b055fdb7e07479b83d69c15211d54">getUniformBase</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac477f229337de92be9c48dae99bf5546">llvm::AArch64TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/vecustomdag/#ada28169376dccd18b7bf89215c83adc5">llvm::VECustomDAG::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aea8c2b718c1dd866d61c29081c1eb44f">llvm::RISCVTargetLowering::joinRegisterPartsIntoValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8679ab19e5fd70f2011394a4923d7c43">LowerAsSplatVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab83ddc0d46d65b1f035e1c8599b22b8d">lowerBitreverseShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13428801d19f40af7da16a16d76329fb">llvm::AMDGPUTargetLowering::LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a24cc4a1d21ea4653fdd760e2d7ae930e">llvm::AMDGPUTargetLowering::LowerEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a09b35db55ed7bd3a4027630fff72d970">LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad0c1ef61c1fa5a02b8d6d66756b35d18">LowerVSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af6fb44d5b8fabbbd624ebe34231c5ce6">llvm::SelectionDAG::matchBinOpReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad97fbbe4189ec9050e03f6e67b97caa3">memVTFromLoadIntrData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a488da8d90b5af11b00e77838d99cbaa2">narrowExtractedVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abf0bc161f51dbc01add0270eb00b2f77">PerformMinMaxFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ade6927c3ebfbd00cbede63e5a1d1426d">PromoteBinOpToF32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab81263b19a504166d5c027a21cc15740">reduceVMULWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac5670c01bc722932c40b06aaab52a0df">skipExtensionForVectorMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ac8adfd3d099db48171fe93c1111663e0">llvm::RISCVTargetLowering::splitValueIntoRegisterParts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#af3333c324c5d8907cc8d45bcf3b636eb">truncateVectorWithNARROW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa038574a2252340dd1eb6885856717ce">truncateVectorWithPACK</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5a8d860cc5c733afd761c1e292b5a0aa">llvm::SelectionDAG::UnrollVectorOverflowOp</a>, <a href="#a7913deec1cb15f66661ba96b54391fd7">widenIntegerVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aeca06367a5dacb988586dfa1b94fa0c1">llvm::AMDGPUTargetLowering::WidenOrSplitVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ab9c026bf7b5362d2b79a43bd04e769a7">widenVec</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab255633ec6629254aeb996969bc7a212">llvm::SelectionDAG::WidenVector</a>.</p>

</div>
</div>

### getVectorVT() {#ab5f86132c602eed040fd6f48794b1eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::EVT::getVectorVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> that represents a vector EC.Min elements in length, where each element is of type VT.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>.</p>


<p>References <a href="#a05ba7800be90a94bec3d4a4eaf29cfa8">EVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getExtendedIntegerVT() {#a6ab0fa2dda3118c3507df13b74d36386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::getExtendedIntegerVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned BitWidth)</td>
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



<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### getExtendedVectorVT() {#a48b263b75a4baebfb5710d6469947f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::getExtendedVectorVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, unsigned NumElements, bool IsScalable)</td>
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



<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

### getExtendedVectorVT() {#a817823345f957416cea36ea226d6244e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT EVT::getExtendedVectorVT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC)</td>
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



<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">ValueTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/valuetypes-cpp">ValueTypes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
