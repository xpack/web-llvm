---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/apint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `APInt` Class

<p>Class for arbitrary precision integers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::APInt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An arbitrary precision integer that knows its signedness. <a href="/web-llvm/docs/api/classes/llvm/apsint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint64_t <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Rounding { <a href="#a3a0519ef55bfe3d07f8fb2eafb5cdbbd">...</a> }</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to store the &lt;= 64 bits integer value. <a href="#ab82287ee9a2442bc0b6025a9936c88dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to store the &gt;64 bits integer value. <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a> = sizeof(<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a>)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Byte size of a word. <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a> = <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a> * CHAR_BIT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bits in a word. <a href="#aaf70a90533b469062634730e27f6577d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a> = ~<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a>(0)</td>
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

## Building-block Operations for APInt and APFloat Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/apint">llvm::APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac659654c41e422fb8059df365560f52f">U</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This union is used to store the integer value. <a href="#ac659654c41e422fb8059df365560f52f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5ba8fb7632bd479c212b0ec2033903">BitWidth</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bits in this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#acd5ba8fb7632bd479c212b0ec2033903">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20be55bb696f821d0de1f6110f04661">DynamicAPInt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d7da4e5886ac588791998f0280d4ce">DenseMapInfo&lt; APInt, void &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248989f3fc86500daacfd87a0a8657bc">APSInt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1c052266ebacdbf28164fae9106b0a">Profile</a> (FoldingSetNodeID &amp;id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to insert <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> objects, or objects that contain <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> objects, into FoldingSets. <a href="#adb1c052266ebacdbf28164fae9106b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa248cd211bcff0f457bf69b596805302">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>debug method <a href="#aa248cd211bcff0f457bf69b596805302">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4eb77ea6033d462fc6dcc0265bfa01b">needsCleanup</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this instance allocated memory. <a href="#aa4eb77ea6033d462fc6dcc0265bfa01b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082bdaab3ddeb1d8e28759423242e2d5">tcSet</a> (WordType *, WordType, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the least significant part of a bignum to the input value, and zeroes out higher parts. <a href="#a082bdaab3ddeb1d8e28759423242e2d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5027d1fc1fcb950cc207e0b39821fd10">tcAssign</a> (WordType *, const WordType *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign one bignum to another. <a href="#a5027d1fc1fcb950cc207e0b39821fd10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0a3652a0b9cd851e5b67ae442028e4">tcIsZero</a> (const WordType *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a bignum is zero, false otherwise. <a href="#a9a0a3652a0b9cd851e5b67ae442028e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffdc10d44b22d3f312c42c8922f294e">tcExtractBit</a> (const WordType *, unsigned bit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the given bit of a bignum; returns 0 or 1. Zero-based. <a href="#a0ffdc10d44b22d3f312c42c8922f294e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2732964a6de928520d3d12be196a7a15">tcExtract</a> (WordType *, unsigned dstCount, const WordType *, unsigned srcBits, unsigned srcLSB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy the bit vector of width srcBITS from SRC, starting at bit srcLSB, to DST, of dstCOUNT parts, such that the bit srcLSB becomes the least significant bit of DST. <a href="#a2732964a6de928520d3d12be196a7a15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06fd1421d0b30ea9b865b7238b8ca89d">tcSetBit</a> (WordType *, unsigned bit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the given bit of a bignum. Zero-based. <a href="#a06fd1421d0b30ea9b865b7238b8ca89d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826ad54b94fed65913c45e223099f149">tcClearBit</a> (WordType *, unsigned bit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the given bit of a bignum. Zero-based. <a href="#a826ad54b94fed65913c45e223099f149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b9c213654f22372b45d61d5db3b30c1">tcLSB</a> (const WordType *, unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bit number of the least or most significant set bit of a number. <a href="#a8b9c213654f22372b45d61d5db3b30c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f95a75462af1c1bd3a22cf805da64a0">tcMSB</a> (const WordType *parts, unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the bit number of the most significant set bit of a number. <a href="#a9f95a75462af1c1bd3a22cf805da64a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abece2572a121bb1dd2c34621c1e13f76">tcNegate</a> (WordType *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Negate a bignum in-place. <a href="#abece2572a121bb1dd2c34621c1e13f76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ca60b3924e39b65a173e2b55c6e92d">tcAdd</a> (WordType *, const WordType *, WordType carry, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST += RHS + CARRY where CARRY is zero or one. Returns the carry flag. <a href="#a25ca60b3924e39b65a173e2b55c6e92d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4be5a4a886a268b42447b2c17eb59e">tcAddPart</a> (WordType *, WordType, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST += RHS. Returns the carry flag. <a href="#ada4be5a4a886a268b42447b2c17eb59e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba546a206fb7cfbc3cc5fd95a832a653">tcSubtract</a> (WordType *, const WordType *, WordType carry, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST -= RHS + CARRY where CARRY is zero or one. Returns the carry flag. <a href="#aba546a206fb7cfbc3cc5fd95a832a653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a57add297988a66a8d6a81eff19cbb">tcSubtractPart</a> (WordType *, WordType, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST -= RHS. Returns the carry flag. <a href="#a97a57add297988a66a8d6a81eff19cbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3bfaa5ac3f017c8d3b7336d8bd4678">tcMultiplyPart</a> (WordType *dst, const WordType *src, WordType multiplier, WordType carry, unsigned srcParts, unsigned dstParts, bool add)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST += SRC * MULTIPLIER + PART if add is true DST = SRC * MULTIPLIER + PART if add is false. <a href="#aaf3bfaa5ac3f017c8d3b7336d8bd4678">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab153d6d2370c0c5526009aaa07cc00e1">tcMultiply</a> (WordType *, const WordType *, const WordType *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST = LHS * RHS, where DST has the same width as the operands and is filled with the least significant parts of the result. <a href="#ab153d6d2370c0c5526009aaa07cc00e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5442d90b169a8cbe8cfcb8724cf79b14">tcFullMultiply</a> (WordType *, const WordType *, const WordType *, unsigned, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DST = LHS * RHS, where DST has width the sum of the widths of the operands. <a href="#a5442d90b169a8cbe8cfcb8724cf79b14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a> (WordType *lhs, const WordType *rhs, WordType *remainder, WordType *scratch, unsigned parts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If RHS is zero LHS and REMAINDER are left unchanged, return one. <a href="#a9fbadc3dfac1d405b669b85267421ca5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd8fe361c9d102eb08cf77f6e4bfda4">tcShiftLeft</a> (WordType *, unsigned Words, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shift a bignum left Count bits. <a href="#a8bd8fe361c9d102eb08cf77f6e4bfda4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52506c05d3157e52f917679cfa14cf6b">tcShiftRight</a> (WordType *, unsigned Words, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shift a bignum right Count bits. <a href="#a52506c05d3157e52f917679cfa14cf6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd574e063a1cfeaa96175c5f9c4afa9">tcCompare</a> (const WordType *, const WordType *, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparison (unsigned) of two bignums. <a href="#a3dd574e063a1cfeaa96175c5f9c4afa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5bc4f0b55d702e1f7e5dea17a097e35">tcIncrement</a> (WordType *dst, unsigned parts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increment a bignum in-place. Return the carry flag. <a href="#ac5bc4f0b55d702e1f7e5dea17a097e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83af504b239085c1725913aa1743e040">tcDecrement</a> (WordType *dst, unsigned parts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrement a bignum in-place. Return the borrow flag. <a href="#a83af504b239085c1725913aa1743e040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a22c2b47f85a6562c42651d1f604d1">APInt</a> (uint64_t *val, unsigned bits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor is used only internally for speed of construction of temporaries. <a href="#aa8a22c2b47f85a6562c42651d1f604d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890df9ac2af1efad0b176f0e16505cc8">clearUnusedBits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear unused high order bits. <a href="#a890df9ac2af1efad0b176f0e16505cc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b866e976b423a794d0815b426120c14">getWord</a> (unsigned bitPosition) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the word corresponding to a bit position. <a href="#a9b866e976b423a794d0815b426120c14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3170763968bdbbbda080f1c55650a6">reallocate</a> (unsigned NewBitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility method to change the bit width of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to new bit width, allocating and/or deallocating as necessary. <a href="#a4e3170763968bdbbbda080f1c55650a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26555498613f6b4f0418544e84cc66a8">fromString</a> (unsigned numBits, StringRef str, uint8_t radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a char array into an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a26555498613f6b4f0418544e84cc66a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3ee9eec1b0f38e67e8cd050e2c73c9">initSlowCase</a> (uint64_t val, bool isSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for inline constructor <a href="#a3b3ee9eec1b0f38e67e8cd050e2c73c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d408c7d046bd8290dc63a579f61b25">initFromArray</a> (ArrayRef&lt; uint64_t &gt; array)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>shared code between two array constructors <a href="#a82d408c7d046bd8290dc63a579f61b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20370dcafe30311a38c79c59a43dc3cc">initSlowCase</a> (const APInt &amp;that)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for inline copy constructor <a href="#a20370dcafe30311a38c79c59a43dc3cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3af748a79b11e301c80cf4e2a0814fc">shlSlowCase</a> (unsigned ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for shl <a href="#ad3af748a79b11e301c80cf4e2a0814fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab540634dbecd3cd9af845c222d231688">lshrSlowCase</a> (unsigned ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for lshr. <a href="#ab540634dbecd3cd9af845c222d231688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd0de4a176d6a2d42ae545f4714a69d">ashrSlowCase</a> (unsigned ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for ashr. <a href="#afcd0de4a176d6a2d42ae545f4714a69d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8eeb818de698c2d75e3e7d980e76f8">assignSlowCase</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for operator= <a href="#a9f8eeb818de698c2d75e3e7d980e76f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb981046d3b46af85643350f9b1ecc9f">equalSlowCase</a> (const APInt &amp;RHS) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for operator== <a href="#afb981046d3b46af85643350f9b1ecc9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613b9e8e352472f9b8335408f61170bc">countLeadingZerosSlowCase</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for countLeadingZeros <a href="#a613b9e8e352472f9b8335408f61170bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87fa79c4b4550f2d57ba6a7989b58c7">countLeadingOnesSlowCase</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for countLeadingOnes. <a href="#ae87fa79c4b4550f2d57ba6a7989b58c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d067bb54b5450f126ed71afd3f77a0c">countTrailingZerosSlowCase</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for countTrailingZeros. <a href="#a7d067bb54b5450f126ed71afd3f77a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e648265f559393553dbcb602451dd8">countTrailingOnesSlowCase</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for countTrailingOnes <a href="#a65e648265f559393553dbcb602451dd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab483b2771d21710676d03b90f261789b">countPopulationSlowCase</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for countPopulation <a href="#ab483b2771d21710676d03b90f261789b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50f7ae767c4c80c49390cd6f805b21b">intersectsSlowCase</a> (const APInt &amp;RHS) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for intersects. <a href="#ac50f7ae767c4c80c49390cd6f805b21b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46b62036f824eb94e4a720315f6a233">isSubsetOfSlowCase</a> (const APInt &amp;RHS) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for isSubsetOf. <a href="#ac46b62036f824eb94e4a720315f6a233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599b3dd8ce080368264f1bd163b3e7c8">setBitsSlowCase</a> (unsigned loBit, unsigned hiBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for setBits. <a href="#a599b3dd8ce080368264f1bd163b3e7c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77153208826efd0be7b0e9191e943c61">flipAllBitsSlowCase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for flipAllBits. <a href="#a77153208826efd0be7b0e9191e943c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f503084365bf34b4e14fbfab4057b98">concatSlowCase</a> (const APInt &amp;NewLSB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for concat. <a href="#a7f503084365bf34b4e14fbfab4057b98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16e4b96a2758583f503d55ecde2d5a7">andAssignSlowCase</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for operator&amp;=. <a href="#ab16e4b96a2758583f503d55ecde2d5a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8268a612193059644ccb5c1ad32e78d0">orAssignSlowCase</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for operator|=. <a href="#a8268a612193059644ccb5c1ad32e78d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365d61f02e84652c917f69a8b471990d">xorAssignSlowCase</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>out-of-line slow case for operator^=. <a href="#a365d61f02e84652c917f69a8b471990d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b106d061f4736fc2cbcda4a30a4ee4">compare</a> (const APInt &amp;RHS) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned comparison. <a href="#a17b106d061f4736fc2cbcda4a30a4ee4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76ae2795973ea8c467aa739bd89153a">compareSigned</a> (const APInt &amp;RHS) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed comparison. <a href="#aa76ae2795973ea8c467aa739bd89153a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90f6f9cd044417121c828aafc873ad1">whichWord</a> (unsigned bitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which word a bit is in. <a href="#ad90f6f9cd044417121c828aafc873ad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe7b1978e27c8909fb8ab0276fbd269">whichBit</a> (unsigned bitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which bit in a word the specified bit position is in. <a href="#aebe7b1978e27c8909fb8ab0276fbd269">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c00b15a7066a6d9c1aace3ac9f1e93">maskBit</a> (unsigned bitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a single bit mask. <a href="#a48c00b15a7066a6d9c1aace3ac9f1e93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa318bddf2df48598a6a15d29dd4a8862">divide</a> (const WordType *LHS, unsigned lhsWords, const WordType *RHS, unsigned rhsWords, WordType *Quotient, WordType *Remainder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An internal division function for dividing APInts. <a href="#aa318bddf2df48598a6a15d29dd4a8862">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Value Tests Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db0645871a7aa6e466a1da24ba361fb">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload to compute a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value. <a href="#a5db0645871a7aa6e466a1da24ba361fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> just has one word to store value. <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine sign of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a6804d9caf15411f55e7b9e9f397f0422">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is non-negative (&gt;= 0) <a href="#ac8c0157adbe12649beac0009c2f6ad8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada19a89b7c62ce0bb713a7254b002445">isSignBitSet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if sign bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is set. <a href="#ada19a89b7c62ce0bb713a7254b002445">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bf988ca1898a53284d4e3f9dac6d9d">isSignBitClear</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if sign bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is clear. <a href="#af3bf988ca1898a53284d4e3f9dac6d9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17c104fbda554c818cf87e53f32f20a">isStrictlyPositive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is positive. <a href="#aa17c104fbda554c818cf87e53f32f20a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e0e44eba106bcebce4b276d2c541c9">isNonPositive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is non-positive (&lt;= 0). <a href="#a98e0e44eba106bcebce4b276d2c541c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a893a459d66560dde653d7c598978edd4">isOneBitSet</a> (unsigned BitNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> only has the specified bit set. <a href="#a893a459d66560dde653d7c598978edd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423e2c491de1408d54e35f0b47d076be">isAllOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if all bits are set. This is true for zero-width values. <a href="#a423e2c491de1408d54e35f0b47d076be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49cd5939942c6665aba4cae8c220dff1">isZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this value is zero, i.e. all bits are clear. <a href="#a49cd5939942c6665aba4cae8c220dff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5f26deda5ef97e02f6afc57c0c3920">isOne</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is a value of 1. <a href="#aea5f26deda5ef97e02f6afc57c0c3920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af976f3fd3889dab65f16068048c41168">isMaxValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is the largest unsigned value. <a href="#af976f3fd3889dab65f16068048c41168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8099bedfdef48644386b16230fef2e5">isMaxSignedValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is the largest signed value. <a href="#ac8099bedfdef48644386b16230fef2e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60dd597765e178719e8d4caf44ba3b64">isMinValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is the smallest unsigned value. <a href="#a60dd597765e178719e8d4caf44ba3b64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f04e382556a817950fd0390aeaf9b0e">isMinSignedValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is the smallest signed value. <a href="#a1f04e382556a817950fd0390aeaf9b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00c35cb040107c05f3fe00c15bb3da0">isIntN</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> has an N-bits unsigned integer value. <a href="#ae00c35cb040107c05f3fe00c15bb3da0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d50d10274efe9688166584391ae489">isSignedIntN</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> has an N-bits signed integer value. <a href="#a87d50d10274efe9688166584391ae489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1b0513de876d1c85cf6268ca21b2c86">isPowerOf2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s value is a power of two greater than zero. <a href="#ad1b0513de876d1c85cf6268ca21b2c86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6b4785fa27be394cf040e543d9fe7c">isNegatedPowerOf2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s negated value is a power of two greater than zero. <a href="#a1b6b4785fa27be394cf040e543d9fe7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17fee74434129df42225c7e5eaab709c">isAligned</a> (Align A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> -interpreted as an address- is aligned to the provided value. <a href="#a17fee74434129df42225c7e5eaab709c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa7e7ca8ab4093fd0dbadb223b998c0">isSignMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s value is returned by getSignMask. <a href="#a4aa7e7ca8ab4093fd0dbadb223b998c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e942dde4b113c4c0b1fd76333db93a">getBoolValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a boolean value. <a href="#ac0e942dde4b113c4c0b1fd76333db93a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a> (uint64_t Limit=UINT64_MAX) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this value is smaller than the specified limit, return it, otherwise return the limit value. <a href="#ab01d8694a759a934e01f1c558c3ce862">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841147c648072358e88b0d0a50359ebe">isSplat</a> (unsigned SplatSizeInBits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> consists of a repeated bit pattern. <a href="#a841147c648072358e88b0d0a50359ebe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac328c5d387ddf7d4a02afe9b669723c7">isMask</a> (unsigned numBits) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d68122936af3f1f89ca41c3eec2bf58">isMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea11bb657e8d5f0eacfc4ddc1a1dc16">isShiftedMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value contains a non-empty sequence of ones with the remainder zero. <a href="#aaea11bb657e8d5f0eacfc4ddc1a1dc16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920c67b5656a050f49ab14cfb488726d">isShiftedMask</a> (unsigned &amp;MaskIdx, unsigned &amp;MaskLen) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value contains a non-empty sequence of ones with the remainder zero. <a href="#a920c67b5656a050f49ab14cfb488726d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5c4385716b3fa4a96e879987cccedc">getHiBits</a> (unsigned numBits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> containing numBits highbits from this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a2d5c4385716b3fa4a96e879987cccedc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa9845f80fa0642b31c238f4ab0d5ef">getLoBits</a> (unsigned numBits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> containing numBits lowbits from this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a0fa9845f80fa0642b31c238f4ab0d5ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns a pointer to the internal storage of the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#ada7af1de63a848b2f452d63958de39fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76807eccec7690dec05dd5f36aceb08">isSameValue</a> (const APInt &amp;I1, const APInt &amp;I2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if two APInts have the same value, after zero-extending one of them (if needed!) to ensure that the bit-widths match. <a href="#ad76807eccec7690dec05dd5f36aceb08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> (unsigned numBits, uint64_t val, bool isSigned=false, bool implicitTrunc=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of numBits width, initialized as val. <a href="#a44d65323d90a63e5f572fe8f44db1154">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a46ba6ad1c259b7fa9bc638ebb0a2f8">APInt</a> (unsigned numBits, ArrayRef&lt; uint64_t &gt; bigVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of numBits width, initialized as bigVal[]. <a href="#a4a46ba6ad1c259b7fa9bc638ebb0a2f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918deddd001f5b6d1e3439cbc5a3abab">APInt</a> (unsigned numBits, unsigned numWords, const uint64_t bigVal[])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalent to APInt(numBits, ArrayRef&lt;uint64_t&gt;(bigVal, numWords)), but deprecated because this constructor is prone to ambiguity with the APInt(unsigned, uint64_t, bool) constructor. <a href="#a918deddd001f5b6d1e3439cbc5a3abab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337b62553d6b0e5ce2868e086b589a00">APInt</a> (unsigned numBits, StringRef str, uint8_t radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> from a string representation. <a href="#a337b62553d6b0e5ce2868e086b589a00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628da9238224184ed7085b6830c1fcff">APInt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor that creates an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with a 1-bit zero value. <a href="#a628da9238224184ed7085b6830c1fcff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e48746426d66487629b456a7baa5fb6">APInt</a> (const APInt &amp;that)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy Constructor. <a href="#a5e48746426d66487629b456a7baa5fb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ea4e1cdf19ee1f92265f6b3bd34e7d">APInt</a> (APInt &amp;&amp;that)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move Constructor. <a href="#a66ea4e1cdf19ee1f92265f6b3bd34e7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280ed6ffa68d01e8757332317be2557c">~APInt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destructor. <a href="#a280ed6ffa68d01e8757332317be2557c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Unary Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7c144083982c1260b97f09f07274d5">operator++</a> (int)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Postfix increment operator. <a href="#a5f7c144083982c1260b97f09f07274d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f577ba20414abdc4328d2c5c14c37f5">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prefix increment operator. <a href="#a3f577ba20414abdc4328d2c5c14c37f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7633734a43c7c7475d68fbfa343527">operator--</a> (int)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Postfix decrement operator. <a href="#a1f7633734a43c7c7475d68fbfa343527">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f371673bb2e0237b0409940657619a">operator--</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prefix decrement operator. <a href="#ae8f371673bb2e0237b0409940657619a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5625372cfd66999c6d53a063012fc8f9">operator!</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Logical negation operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> returns true if zero, like normal integers. <a href="#a5625372cfd66999c6d53a063012fc8f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Assignment Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3ff3a632850951cea84d8c6466890b">operator=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy assignment operator. <a href="#a3c3ff3a632850951cea84d8c6466890b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac425969d2fbffcdd54e3ab18b35c680e">operator=</a> (APInt &amp;&amp;that)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move assignment operator. <a href="#ac425969d2fbffcdd54e3ab18b35c680e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5706001980ca4d8b32c73ca742bcc4fa">operator=</a> (uint64_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assignment operator. <a href="#a5706001980ca4d8b32c73ca742bcc4fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c8efc9c8dd13e8cdc39109283552a0">operator&amp;=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise AND assignment operator. <a href="#a38c8efc9c8dd13e8cdc39109283552a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">operator&amp;=</a> (uint64_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise AND assignment operator. <a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea5541c90a06aae894eb1e99ba2d579">operator|=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise OR assignment operator. <a href="#a5ea5541c90a06aae894eb1e99ba2d579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a10e817a053d9ec8b63fc11a061f41e">operator|=</a> (uint64_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise OR assignment operator. <a href="#a4a10e817a053d9ec8b63fc11a061f41e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac605f0a460fdb9a65dd94d2eaa0722f1">operator^=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise XOR assignment operator. <a href="#ac605f0a460fdb9a65dd94d2eaa0722f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4627e5f0560b9d5f40fb309ea263de9d">operator^=</a> (uint64_t RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise XOR assignment operator. <a href="#a4627e5f0560b9d5f40fb309ea263de9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7984341f7e873ae3619874ae89c3afb">operator*=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiplication assignment operator. <a href="#ab7984341f7e873ae3619874ae89c3afb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed0fa6f38807df2e9ff7f643de4f42d6">operator*=</a> (uint64_t RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad550e9403dfe9c20c6b8adb6acb25180">operator+=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Addition assignment operator. <a href="#ad550e9403dfe9c20c6b8adb6acb25180">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a2fd77599a3403f6a848952dd7f82e">operator+=</a> (uint64_t RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86485d3a573bdd67a702e19fe7790c66">operator-=</a> (const APInt &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtraction assignment operator. <a href="#a86485d3a573bdd67a702e19fe7790c66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15edd02fb043f45d425b99ff92e7c4b0">operator-=</a> (uint64_t RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f57dd5ed73b3c76a3d208bb1a67228a">operator&lt;&lt;=</a> (unsigned ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left-shift assignment function. <a href="#a6f57dd5ed73b3c76a3d208bb1a67228a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66c0b07cc393cb3aa9123c5d9cbfe4b">operator&lt;&lt;=</a> (const APInt &amp;ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left-shift assignment function. <a href="#af66c0b07cc393cb3aa9123c5d9cbfe4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Binary Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiplication operator. <a href="#a8affacda773b55e259f6dc4da77d948a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e24bc7f50e82dee742541ad86b449c6">operator&lt;&lt;</a> (unsigned Bits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left logical shift operator. <a href="#a2e24bc7f50e82dee742541ad86b449c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28bc2404b2316a5e4b6ff9113ba270ab">operator&lt;&lt;</a> (const APInt &amp;Bits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left logical shift operator. <a href="#a28bc2404b2316a5e4b6ff9113ba270ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6006923d1a3139d70abc8f6552a7960">ashr</a> (unsigned ShiftAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arithmetic right-shift function. <a href="#ab6006923d1a3139d70abc8f6552a7960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e30b3aa214eba50eed018b5b19fc6aa">ashrInPlace</a> (unsigned ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by ShiftAmt in place. <a href="#a7e30b3aa214eba50eed018b5b19fc6aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a> (unsigned shiftAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Logical right-shift function. <a href="#af34549c39d6f741fbdaf9a795aa306e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af338e23a90c301183968435e80cd6a27">lshrInPlace</a> (unsigned ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by ShiftAmt in place. <a href="#af338e23a90c301183968435e80cd6a27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9c55b6986369948507ca5241b4e411">shl</a> (unsigned shiftAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left-shift function. <a href="#acb9c55b6986369948507ca5241b4e411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aeae6359e573a57ce8db93b8b26b19a">relativeLShr</a> (int RelativeShift) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>relative logical shift right <a href="#a1aeae6359e573a57ce8db93b8b26b19a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bbf73dc4411a52b8d03e582a09893ce">relativeLShl</a> (int RelativeShift) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>relative logical shift left <a href="#a3bbf73dc4411a52b8d03e582a09893ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57604a130a7bf75be0295a8ba37ff4fe">relativeAShr</a> (int RelativeShift) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>relative arithmetic shift right <a href="#a57604a130a7bf75be0295a8ba37ff4fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a793e27a4e7b6ec5ecab8e7616e0d4ac0">relativeAShl</a> (int RelativeShift) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>relative arithmetic shift left <a href="#a793e27a4e7b6ec5ecab8e7616e0d4ac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa548cc4a0fd9e7c713b180f7780655e2">rotl</a> (unsigned rotateAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rotate left by rotateAmt. <a href="#aa548cc4a0fd9e7c713b180f7780655e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7add4efc2976e2d2b52a1e5d427ce616">rotr</a> (unsigned rotateAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rotate right by rotateAmt. <a href="#a7add4efc2976e2d2b52a1e5d427ce616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c2c3c3344946ca0d70b0da418b52e4">ashr</a> (const APInt &amp;ShiftAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arithmetic right-shift function. <a href="#a61c2c3c3344946ca0d70b0da418b52e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79a42db75a127dc89f3962474caf145c">ashrInPlace</a> (const APInt &amp;shiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt in place. <a href="#a79a42db75a127dc89f3962474caf145c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d705ad0b507dd7c488017c2ad5c8ae">lshr</a> (const APInt &amp;ShiftAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Logical right-shift function. <a href="#a98d705ad0b507dd7c488017c2ad5c8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56f74cc18a1ce46c252a0280a2fa1d2">lshrInPlace</a> (const APInt &amp;ShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by ShiftAmt in place. <a href="#aa56f74cc18a1ce46c252a0280a2fa1d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1d88206e3ce5514de646f23f0042bc">shl</a> (const APInt &amp;ShiftAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left-shift function. <a href="#a8f1d88206e3ce5514de646f23f0042bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65bc3d32a3f55045259fda31d9fffb28">rotl</a> (const APInt &amp;rotateAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rotate left by rotateAmt. <a href="#a65bc3d32a3f55045259fda31d9fffb28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc8a2eb3a9949f9e26c2724ef3a109cd">rotr</a> (const APInt &amp;rotateAmt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rotate right by rotateAmt. <a href="#acc8a2eb3a9949f9e26c2724ef3a109cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc2ad05ce14ae805c176fc8abfbe0a1">concat</a> (const APInt &amp;NewLSB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concatenate the bits from "NewLSB" onto the bottom of *this. <a href="#a6bc2ad05ce14ae805c176fc8abfbe0a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned division operation. <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21fe5092047a14fb320f82d99276b99">udiv</a> (uint64_t RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f7f6e3a4774296efc7274196a74793">sdiv</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed division function for <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a71f7f6e3a4774296efc7274196a74793">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81219309bccc36e3a7c38f7f5c21de8a">sdiv</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3a2187cacdec76028617a403c47d89">urem</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned remainder operation. <a href="#a4e3a2187cacdec76028617a403c47d89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825a8dca80ee195760b908990de1a7af">urem</a> (uint64_t RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac131d830427393332e440e1d6e3013b6">srem</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> for signed remainder operation. <a href="#ac131d830427393332e440e1d6e3013b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee93929dbd2133737e30498d6e12fed">srem</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694293446a074c3d64270e7671bb5052">sadd_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8268fbc3014081004056f6466452c904">uadd_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae324de5041feaf7eb8433221cdaca9aa">ssub_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d622af4cca05108d8d7eb9bfd79977">usub_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889c63e93f521abb41e0736a3f42cf02">sdiv_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac155d7c568fc1aba25723e77b6888908">smul_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a> (const APInt &amp;Amt, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a> (unsigned Amt, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a> (const APInt &amp;Amt, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8345a3be974d824185f13fc5c196393">ushl_ov</a> (unsigned Amt, bool &amp;Overflow) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af05771dc4f41f73f052c66836657bc">sfloordiv_ov</a> (const APInt &amp;RHS, bool &amp;Overflow) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed integer floor division operation. <a href="#a5af05771dc4f41f73f052c66836657bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1e0381aeb551ad0ba58effe9232f97">sadd_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c04665274d4f30d732639dc055821c">uadd_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af888cb3cadd9a4e5f422c96e5674de88">ssub_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059dc64e71df065315050d2270cbfba5">usub_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f62de4b8b82d2f73fb4efda79954f0">smul_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4d36ebf88039604b73d3527506c3ed">umul_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e6be77d59fee53e8585874cd1ab07c">sshl_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ed902943113e485a80dff901f36494">sshl_sat</a> (unsigned RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9458a57a572f29dd261a3be65cd8ee9f">ushl_sat</a> (const APInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236aa749101900bc9e8e6cd108bdec6a">ushl_sat</a> (unsigned RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ac00f7e03b4472cc7efc04c4818bf5">operator[]</a> (unsigned bitPosition) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Array-indexing support. <a href="#a34ac00f7e03b4472cc7efc04c4818bf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a> (const APInt &amp;LHS, const APInt &amp;RHS, APInt &amp;Quotient, APInt &amp;Remainder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dual division/remainder interface. <a href="#a0f0a665210e453bb16b4bf1861dbdd58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd2f21c3219cdb1c83f080dc7e1fc31">udivrem</a> (const APInt &amp;LHS, uint64_t RHS, APInt &amp;Quotient, uint64_t &amp;Remainder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24187c2e178af0df22dac26cd5229294">sdivrem</a> (const APInt &amp;LHS, const APInt &amp;RHS, APInt &amp;Quotient, APInt &amp;Remainder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e54fadf3b01da96aaa66c35ed8c366">sdivrem</a> (const APInt &amp;LHS, int64_t RHS, APInt &amp;Quotient, int64_t &amp;Remainder)</td>
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

## Comparison Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eeb6b0ef83a291455cb52d6e0a5a612">operator==</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality operator. <a href="#a8eeb6b0ef83a291455cb52d6e0a5a612">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f74c7368cdc65e9e942faca9976d080">operator==</a> (uint64_t Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality operator. <a href="#a5f74c7368cdc65e9e942faca9976d080">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e17f9e532ca4a61804f28091b10b522">eq</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equality comparison. <a href="#a6e17f9e532ca4a61804f28091b10b522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3509642df002d9bc4e089eff3a6eedcb">operator!=</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inequality operator. <a href="#a3509642df002d9bc4e089eff3a6eedcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8fe1bb967080f5d6ba2e253e7337c1">operator!=</a> (uint64_t Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inequality operator. <a href="#afe8fe1bb967080f5d6ba2e253e7337c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad53de8dfd63f774033284907674f79ee">ne</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inequality comparison. <a href="#ad53de8dfd63f774033284907674f79ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned less than comparison. <a href="#a545e8d5dfa1688acea0d0e275b03682f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe03273b7efa986834cca7b9899a686b">ult</a> (uint64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned less than comparison. <a href="#afe03273b7efa986834cca7b9899a686b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafa9575780f9246d1df0b7e2a619356">slt</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed less than comparison. <a href="#adafa9575780f9246d1df0b7e2a619356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0735ef8bd9cc0d99266fba0c6d7b5acb">slt</a> (int64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed less than comparison. <a href="#a0735ef8bd9cc0d99266fba0c6d7b5acb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca14d9ec64ba4ab7fb2cef37c57d9ce4">ule</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned less or equal comparison. <a href="#aca14d9ec64ba4ab7fb2cef37c57d9ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab15b44dcd79305e3dbef93b452dc57e3">ule</a> (uint64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned less or equal comparison. <a href="#ab15b44dcd79305e3dbef93b452dc57e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8226e6453c8bcf7e5c06d28b1e207b">sle</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed less or equal comparison. <a href="#a7e8226e6453c8bcf7e5c06d28b1e207b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5342595638e399928d478bc84cad6b41">sle</a> (uint64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed less or equal comparison. <a href="#a5342595638e399928d478bc84cad6b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">ugt</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned greater than comparison. <a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfeca4698f01ef85e21a3e3061751781">ugt</a> (uint64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned greater than comparison. <a href="#abfeca4698f01ef85e21a3e3061751781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d430216d32f4363e4df154599b98055">sgt</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed greater than comparison. <a href="#a3d430216d32f4363e4df154599b98055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3291dd727de5786ef808475d8d9a1560">sgt</a> (int64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed greater than comparison. <a href="#a3291dd727de5786ef808475d8d9a1560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b1ccc0b78f9da9f3f3944e06007f1d">uge</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned greater or equal comparison. <a href="#af4b1ccc0b78f9da9f3f3944e06007f1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ef77e140475145bce554cf37291292">uge</a> (uint64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsigned greater or equal comparison. <a href="#a54ef77e140475145bce554cf37291292">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b7d8c018c8a37fa8ea422a13bfd412">sge</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed greater or equal comparison. <a href="#ae2b7d8c018c8a37fa8ea422a13bfd412">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c66c2a2456cbc331f206ac64491488">sge</a> (int64_t RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Signed greater or equal comparison. <a href="#ac0c66c2a2456cbc331f206ac64491488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da514c588b2668280a861a59bfc9fa5">intersects</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This operation tests if there are any pairs of corresponding bits between this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS that are both set. <a href="#a6da514c588b2668280a861a59bfc9fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfae9bdee6027ffa8ffe244cc22e3a76">isSubsetOf</a> (const APInt &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This operation checks that all bits set in this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> are also set in RHS. <a href="#acfae9bdee6027ffa8ffe244cc22e3a76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Resizing Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Truncate to new width. <a href="#a317c64fd4cfebc88e79387b3821a629d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ede0a7cd71b89d7f2f8976321bab08">truncUSat</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Truncate to new width with unsigned saturation. <a href="#a21ede0a7cd71b89d7f2f8976321bab08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Truncate to new width with signed saturation. <a href="#afe04819b980f360000f64b1b5487e0a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sign extend to a new width. <a href="#aca8fce65eb69a82aa10a635e2e79877a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Zero extend to a new width. <a href="#a1dc76cc8bf703e6ada68bededcbb9573">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5fc98b47d44d1150d3610bdfab1430">sextOrTrunc</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sign extend or truncate to width. <a href="#a9b5fc98b47d44d1150d3610bdfab1430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed912a28808268e35bd58e8f11251aa">zextOrTrunc</a> (unsigned width) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Zero extend or truncate to width. <a href="#a2ed912a28808268e35bd58e8f11251aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Bit Manipulation Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fff8a97bcb55e50e9be0ecf0c99b63">setAllBits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set every bit to 1. <a href="#ab6fff8a97bcb55e50e9be0ecf0c99b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f9f862dca8ee0f23bff5941bf433d8">setBit</a> (unsigned BitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the given bit to 1 whose position is given as "bitPosition". <a href="#a33f9f862dca8ee0f23bff5941bf433d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f1e1a4449b58958c5884c689e7f4861">setSignBit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the sign bit to 1. <a href="#a4f1e1a4449b58958c5884c689e7f4861">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f9dd7fb931d5c71749761348534109">setBitVal</a> (unsigned BitPosition, bool BitValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a given bit to a given value. <a href="#af5f9dd7fb931d5c71749761348534109">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d7462ee50c7b2ad49c08d8661f52d2">setBitsWithWrap</a> (unsigned loBit, unsigned hiBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the bits from loBit (inclusive) to hiBit (exclusive) to 1. <a href="#a97d7462ee50c7b2ad49c08d8661f52d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a> (unsigned loBit, unsigned hiBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the bits from loBit (inclusive) to hiBit (exclusive) to 1. <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286d4fa2a50c9ac6ac3a8069cccfcd0c">setBitsFrom</a> (unsigned loBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the top bits starting from loBit. <a href="#a286d4fa2a50c9ac6ac3a8069cccfcd0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8e20ecea1091e835395746448e262e">setLowBits</a> (unsigned loBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the bottom loBits bits. <a href="#ade8e20ecea1091e835395746448e262e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2780c5606880394d3f07cd2079a27697">setHighBits</a> (unsigned hiBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the top hiBits bits. <a href="#a2780c5606880394d3f07cd2079a27697">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781bd5c20864a9c185018258af774ace">clearAllBits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set every bit to 0. <a href="#a781bd5c20864a9c185018258af774ace">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155466c9ea0a2bd00e09c62fdce2c052">clearBit</a> (unsigned BitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a given bit to 0. <a href="#a155466c9ea0a2bd00e09c62fdce2c052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac76bff09195240a482b319136ab6144">clearLowBits</a> (unsigned loBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set bottom loBits bits to 0. <a href="#aac76bff09195240a482b319136ab6144">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3f66072750c56846c44817e7336a3d">clearHighBits</a> (unsigned hiBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set top hiBits bits to 0. <a href="#aef3f66072750c56846c44817e7336a3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af883359d8cdce0f853270b28d7bfc564">clearSignBit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the sign bit to 0. <a href="#af883359d8cdce0f853270b28d7bfc564">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26382591715c45666c3c6336755d529">flipAllBits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle every bit to its opposite value. <a href="#aa26382591715c45666c3c6336755d529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8466cf860f0a86eee4694fc5c097f44">flipBit</a> (unsigned bitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggles a given bit to its opposite value. <a href="#ad8466cf860f0a86eee4694fc5c097f44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8376734f311508662dd7e737752e5953">negate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Negate this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> in place. <a href="#a8376734f311508662dd7e737752e5953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a> (const APInt &amp;SubBits, unsigned bitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the bits from a smaller <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> starting at bitPosition. <a href="#aabe301a4f18d38478700ad44ba2245bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369007fafbf2f88498f412f00eb0a469">insertBits</a> (uint64_t SubBits, unsigned bitPosition, unsigned numBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf997f1047734d3b47b8d5a9b2163f11">extractBits</a> (unsigned numBits, unsigned bitPosition) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with the extracted bits [bitPosition,bitPosition+numBits). <a href="#adf997f1047734d3b47b8d5a9b2163f11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29177946d0b9d5003e7a952a9684b797">extractBitsAsZExtValue</a> (unsigned numBits, unsigned bitPosition) const</td>
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

## Value Characterization Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of bits in the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a512fe2c15ea651294688eeec1341644c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of words. <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of active bits in the value. <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c2b7a1d52ade8885995a54205a923b">getActiveWords</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of active words in the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#ad2c2b7a1d52ade8885995a54205a923b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the minimum bit size for this signed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a9f78d7e839322a6bfc0c665d29052242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get zero extended value. <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03385a25be413259dc4abb7252b3aaa4">tryZExtValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get zero extended value if possible. <a href="#a03385a25be413259dc4abb7252b3aaa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get sign extended value. <a href="#af2daa0ee117afefed4c82eee55bf97b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30d62aebec681aceb655de2489f12ba">trySExtValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get sign extended value if possible. <a href="#ae30d62aebec681aceb655de2489f12ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> version of std::countl_zero. <a href="#a8bad27827f46bca6baf814cbd2b64e84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa074b9f5a1efaa0fd8aa4522593f299a">countLeadingZeros</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the number of leading one bits. <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2a335dd528474e41dcf609f79b0be2">countLeadingOnes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8924f4d542442eecf3aac41a0bd61fa3">getNumSignBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the number of leading bits of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> that are equal to its sign bit. <a href="#a8924f4d542442eecf3aac41a0bd61fa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c7c9008ba213687483b60a658b4a13">countr_zero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the number of trailing zero bits. <a href="#a83c7c9008ba213687483b60a658b4a13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a99431f0828d0222c617eb876bc5d34">countTrailingZeros</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34a543ce8585d04c1ae22c78b3182dd">countr_one</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the number of trailing one bits. <a href="#af34a543ce8585d04c1ae22c78b3182dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae155fc08c52bcfd6026faf4c640a2cf7">countTrailingOnes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">popcount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count the number of bits set. <a href="#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2cabc55d461335724f348fa2e2c6fd7">getNumWords</a> (unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of words. <a href="#aa2cabc55d461335724f348fa2e2c6fd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9178a079b54667289f598db5b052ade">getBitsNeeded</a> (StringRef str, uint8_t radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get bits required for string value. <a href="#ab9178a079b54667289f598db5b052ade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31665d34f2904bf73a6dd6419dcd8587">getSufficientBitsNeeded</a> (StringRef Str, uint8_t Radix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bits that are sufficient to represent the string value. <a href="#a31665d34f2904bf73a6dd6419dcd8587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Conversion Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48334652c819dffc9a133ce268693858">print</a> (raw_ostream &amp;OS, bool isSigned) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned Radix, bool Signed, bool formatAsCLiteral=false, bool UpperCase=true, bool InsertSeparators=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a string and append it to Str. <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3591391b56f014b632b3af30b86dc51a">toStringUnsigned</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned Radix=10) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Considers the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to be unsigned and converts it into a string in the radix given. <a href="#a3591391b56f014b632b3af30b86dc51a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbbb8a6117fc93aa80fabdeb82f73cf0">toStringSigned</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned Radix=10) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Considers the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to be signed and converts it into a string in the radix given. <a href="#afbbb8a6117fc93aa80fabdeb82f73cf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0bd40e4bee1851ebebb276178d65fc">byteSwap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8b4253b618610eb5cb497b4104ebc3">reverseBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a> (bool isSigned) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double value. <a href="#ae5dfa02c3403baa3d057b6264eed687d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c7bc4d4687802bcd1e3628fcbec03f">roundToDouble</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts this unsigned <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double value. <a href="#a74c7bc4d4687802bcd1e3628fcbec03f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8a216000ce553ed7e8d4c3a9bd1542">signedRoundToDouble</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts this signed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double value. <a href="#aae8a216000ce553ed7e8d4c3a9bd1542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda0d1f0e4b7b739aff9601d8b4ef4e3">bitsToDouble</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits to a double. <a href="#acda0d1f0e4b7b739aff9601d8b4ef4e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaefac1a605f4e104e7c7a20ab0856889">bitsToFloat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits to a float. <a href="#aaefac1a605f4e104e7c7a20ab0856889">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac174a45e376a00ec9b2e9e8730f982c0">doubleToBits</a> (double V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts a double to <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits. <a href="#ac174a45e376a00ec9b2e9e8730f982c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b160c2704ee3819d8fda70345b4d19f">floatToBits</a> (float V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts a float to <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits. <a href="#a4b160c2704ee3819d8fda70345b4d19f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Mathematics Operations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae3b959a0a2981340fd03c29f528f2f0">logBase2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392d67031c5429420ac0b46478fe893e">ceilLogBase2</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee171002efe1360b112e2bc4bd0674f">nearestLogBase2</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1d5427c61a0f0159f6e85f41944c5c">exactLogBase2</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the square root. <a href="#af48b6a9423c3b72b453f0eb881129d3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e964f0cadf077725453884734a6c99">abs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the absolute value. <a href="#a38e964f0cadf077725453884734a6c99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba59baafccd4c4796301b857df3c40c6">multiplicativeInverse</a> () const</td>
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

## Value Generators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4e37b60ea64faafbc9a5bf3e27280f">getZero</a> (unsigned numBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the '0' value for the specified bit-width. <a href="#add4e37b60ea64faafbc9a5bf3e27280f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae66680c2cf6c3acccde9cd1189a0215">getZeroWidth</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> zero bits wide. <a href="#aae66680c2cf6c3acccde9cd1189a0215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a> (unsigned numBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets maximum unsigned value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for specific bit width. <a href="#a331d69b5f93e47e7c596062b77dd5913">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a> (unsigned numBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets maximum signed value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for a specific bit width. <a href="#a562c9513409b74f02cb3a5c9bae672ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65a6479206acd4113b8aa1c0fbc2158c">getMinValue</a> (unsigned numBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets minimum unsigned value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for a specific bit width. <a href="#a65a6479206acd4113b8aa1c0fbc2158c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a> (unsigned numBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets minimum signed value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for a specific bit width. <a href="#a8f877403433892e14ff0c692cbe9efdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6f0d8dfed0ab631b488a3e6317718e">getSignMask</a> (unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the SignMask for a specific bit width. <a href="#a1e6f0d8dfed0ab631b488a3e6317718e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071e8d814b2b30b02544fad964227b8e">getAllOnes</a> (unsigned numBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of a specified width with all bits set. <a href="#a071e8d814b2b30b02544fad964227b8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec662ee6ab1490a4cabebf2812e5b9ca">getOneBitSet</a> (unsigned numBits, unsigned BitNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with exactly one bit set in the result. <a href="#aec662ee6ab1490a4cabebf2812e5b9ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ceedee591f92727b85641794a96061">getBitsSet</a> (unsigned numBits, unsigned loBit, unsigned hiBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a value with a block of bits set. <a href="#a46ceedee591f92727b85641794a96061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bee3e462a14abdf3858c354a5cd222">getBitsSetWithWrap</a> (unsigned numBits, unsigned loBit, unsigned hiBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap version of getBitsSet. <a href="#af3bee3e462a14abdf3858c354a5cd222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf22e8d92fd978a5eca9ab031994399">getBitsSetFrom</a> (unsigned numBits, unsigned loBit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has a contiguous range of bits set. <a href="#aeaf22e8d92fd978a5eca9ab031994399">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb96bd09d7c75c7669fa5f9d1190899">getHighBitsSet</a> (unsigned numBits, unsigned hiBitsSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has the top hiBitsSet bits set. <a href="#adcb96bd09d7c75c7669fa5f9d1190899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad960e1ff48d25c382b6d28e7961f074e">getLowBitsSet</a> (unsigned numBits, unsigned loBitsSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has the bottom loBitsSet bits set. <a href="#ad960e1ff48d25c382b6d28e7961f074e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c55d8510ad4b7cb957d8f5a7cd6944e">getSplat</a> (unsigned NewLen, const APInt &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a value containing V broadcasted over NewLen bits. <a href="#a8c55d8510ad4b7cb957d8f5a7cd6944e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class for arbitrary precision integers.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is a functional replacement for common case unsigned integer type like "unsigned", "unsigned long" or "uint64_t", but also allows non-byte-width integer sizes and large integer value types such as 3-bits, 15-bits, or more than 64-bits of precision. <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> provides a variety of arithmetic operators and methods to manipulate integer values of any bit-width. It supports both the typical integer arithmetic and comparison operations as well as bitwise manipulation.</p>


<p>The class has several invariants worth noting:</p>


<ul class="doxyList ">
<li>All bit, byte, and word positions are zero-based.</li>
<li>Once the bit width is set, it doesn't change except by the Truncate, SignExtend, or ZeroExtend operations.</li>
<li>All binary operators must be on <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> instances of the same bit width. Attempting to use these operators on instances with different bit widths will yield an assertion.</li>
<li>The value is stored canonically as an unsigned value. For operations where it makes a difference, there are both signed and unsigned variants of the operation. For example, sdiv and udiv. However, because the bit widths must be the same, operations such as Mul and Add produce the same results regardless of whether the values are interpreted as signed or not.</li>
<li>In general, the class tries to follow the style of computation that LLVM uses in its IR. This simplifies its use for LLVM.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> supports zero-bit-width values, but operations that require bits are not defined on it (e.g. you cannot ask for the sign of a zero-bit integer). This means that operations like zero extension and logical shifts are defined, but sign extension and ashr is not. Zero bit values compare and hash equal to themselves, and countLeadingZeros returns 0.</li>
</ul>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### WordType {#a5221357e5b7511cb0c90c94044ba35cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint64_t llvm::APInt::WordType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Rounding {#a3a0519ef55bfe3d07f8fb2eafb5cdbbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::APInt::Rounding </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">DOWN<a id="a3a0519ef55bfe3d07f8fb2eafb5cdbbdac4e0e4e3118472beeb2ae75827450f1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOWARD_ZERO<a id="a3a0519ef55bfe3d07f8fb2eafb5cdbbdab5008efafd504d9907945f47605791aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UP<a id="a3a0519ef55bfe3d07f8fb2eafb5cdbbdafbaedde498cdead4f2780217646e9ba1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### pVal {#a23b5d5d53d9a7a8d473b61cd78b1a543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t* llvm::APInt::pVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to store the &gt;64 bits integer value.</p>

<p>Definition at line 1911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0e3c089e61a9927131ee18b4eb7c7c5c">llvm::hash_value</a>, <a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">operator&amp;=</a>, <a href="#a5706001980ca4d8b32c73ca742bcc4fa">operator=</a>, <a href="#a4627e5f0560b9d5f40fb309ea263de9d">operator^=</a>, <a href="#a4a10e817a053d9ec8b63fc11a061f41e">operator|=</a>, <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a> and <a href="#a8bd2f21c3219cdb1c83f080dc7e1fc31">udivrem</a>.</p>

</div>
</div>

### VAL {#ab82287ee9a2442bc0b6025a9936c88dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::APInt::VAL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to store the &lt;= 64 bits integer value.</p>

<p>Definition at line 1910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="#a5e48746426d66487629b456a7baa5fb6">APInt</a>, <a href="#a6bc2ad05ce14ae805c176fc8abfbe0a1">concat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e3c089e61a9927131ee18b4eb7c7c5c">llvm::hash_value</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="#a3f577ba20414abdc4328d2c5c14c37f5">operator++</a>, <a href="#a30a2fd77599a3403f6a848952dd7f82e">operator+=</a>, <a href="#ae8f371673bb2e0237b0409940657619a">operator--</a> and <a href="#a15edd02fb043f45d425b99ff92e7c4b0">operator-=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### APINT\_BITS\_PER\_WORD {#aaf70a90533b469062634730e27f6577d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::APINT_BITS_PER_WORD = <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a> * CHAR_BIT</td>
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

<p>Bits in a word.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="#a7e30b3aa214eba50eed018b5b19fc6aa">ashrInPlace</a>, <a href="#ace0bd40e4bee1851ebebb276178d65fc">byteSwap</a>, <a href="#a6bc2ad05ce14ae805c176fc8abfbe0a1">concat</a>, <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a>, <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a>, <a href="#adf997f1047734d3b47b8d5a9b2163f11">extractBits</a>, <a href="#a29177946d0b9d5003e7a952a9684b797">extractBitsAsZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a250ae807ddec8d1d8881d01a7d24dc44">llvm::detail::IEEEFloat::getExactLog2Abs</a>, <a href="#aa2cabc55d461335724f348fa2e2c6fd7">getNumWords</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a74a725ce0eb6c9d51e4c3ddf54b0de8b">highHalf</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="#a423e2c491de1408d54e35f0b47d076be">isAllOnes</a>, <a href="#ac328c5d387ddf7d4a02afe9b669723c7">isMask</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#ae876a1ecb46543fee1f374dd8c2fad13">lowBitMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a17d47a818ea2835a5ad9fee50c239ac1">lowHalf</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#af1eb91b7a599d7ef03c2282a78e99466">nextAPIntBitWidth</a>, <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>, <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a>, <a href="#a2732964a6de928520d3d12be196a7a15">tcExtract</a>, <a href="#a8b9c213654f22372b45d61d5db3b30c1">tcLSB</a>, <a href="#a9f95a75462af1c1bd3a22cf805da64a0">tcMSB</a>, <a href="#aaf3bfaa5ac3f017c8d3b7336d8bd4678">tcMultiplyPart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a42cd9369bafb2b36e67352d993845390">llvm::detail::tcSetLeastSignificantBits</a>, <a href="#a8bd8fe361c9d102eb08cf77f6e4bfda4">tcShiftLeft</a>, <a href="#a52506c05d3157e52f917679cfa14cf6b">tcShiftRight</a>, <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>

</div>
</div>

### APINT\_WORD\_SIZE {#a507f18d22ad9ce4dd96e8a664d577bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::APINT_WORD_SIZE = sizeof(<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a>)</td>
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

<p>Byte size of a word.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="#a781bd5c20864a9c185018258af774ace">clearAllBits</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">operator&amp;=</a>, <a href="#a5706001980ca4d8b32c73ca742bcc4fa">operator=</a>, <a href="#ab6fff8a97bcb55e50e9be0ecf0c99b63">setAllBits</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="#a8bd8fe361c9d102eb08cf77f6e4bfda4">tcShiftLeft</a>, <a href="#a52506c05d3157e52f917679cfa14cf6b">tcShiftRight</a>, <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>, <a href="#a8bd2f21c3219cdb1c83f080dc7e1fc31">udivrem</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>

</div>
</div>

### WORDTYPE\_MAX {#a9312eb1fba50adaeda024f10b9919136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WordType llvm::APInt::WORDTYPE_MAX = ~<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a>(0)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="#aa26382591715c45666c3c6336755d529">flipAllBits</a>, <a href="#a071e8d814b2b30b02544fad964227b8e">getAllOnes</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="#a423e2c491de1408d54e35f0b47d076be">isAllOnes</a>, <a href="#ac328c5d387ddf7d4a02afe9b669723c7">isMask</a>, <a href="#ab6fff8a97bcb55e50e9be0ecf0c99b63">setAllBits</a> and <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Building-block Operations for APInt and APFloat

### andAssignSlowCase {#ab16e4b96a2758583f503d55ecde2d5a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::andAssignSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for operator&amp;=.</p>

<p>Declaration at line 2061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### APInt {#aa8a22c2b47f85a6562c42651d1f604d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APInt::APInt (uint64_t * val, unsigned bits)</td>
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

<p>This constructor is used only internally for speed of construction of temporaries.</p>


<p>It is unsafe since it takes ownership of the pointer, so it is not public.</p>


<p>Definition at line 1925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### APSInt {#a248989f3fc86500daacfd87a0a8657bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a248989f3fc86500daacfd87a0a8657bc">APSInt</a>.</p>


<p>Referenced by <a href="#a248989f3fc86500daacfd87a0a8657bc">APSInt</a>.</p>

</div>
</div>

### ashrSlowCase {#afcd0de4a176d6a2d42ae545f4714a69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::ashrSlowCase (unsigned ShiftAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for ashr.</p>


<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Arithmetic right-shift function.</p>


<p>Declaration at line 2022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### assignSlowCase {#a9f8eeb818de698c2d75e3e7d980e76f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::assignSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for operator=</p>

<p>Declaration at line 2025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### BitWidth {#acd5ba8fb7632bd479c212b0ec2033903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::BitWidth = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bits in this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>

<p>Definition at line 1914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### clearUnusedBits {#a890df9ac2af1efad0b176f0e16505cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::clearUnusedBits ()</td>
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

<p>Clear unused high order bits.</p>


<p>This method is used internally to clear the top "N" bits in the high order word that are not used by the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. This is needed after the most significant word is assigned a value to ensure that those bits are zero'd out.</p>


<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### compare {#a17b106d061f4736fc2cbcda4a30a4ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unsigned comparison.</p>


<p>Returns -1, 0, or 1 if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is less than, equal to, or greater than RHS.</p>


<p>Declaration at line 2071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### compareSigned {#aa76ae2795973ea8c467aa739bd89153a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::compareSigned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Signed comparison.</p>


<p>Returns -1, 0, or 1 if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is less than, equal to, or greater than RHS.</p>


<p>Declaration at line 2075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### concatSlowCase {#a7f503084365bf34b4e14fbfab4057b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::concatSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NewLSB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for concat.</p>


<p>Concatenate the bits from "NewLSB" onto the bottom of *this.</p>


<p>This is equivalent to: (this-&gt;zext(NewWidth) &lt;&lt; NewLSB.getBitWidth()) | NewLSB.zext(NewWidth) In the slow case, we know the result is large.</p>


<p>Declaration at line 2058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### countLeadingOnesSlowCase {#ae87fa79c4b4550f2d57ba6a7989b58c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::countLeadingOnesSlowCase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for countLeadingOnes.</p>

<p>Declaration at line 2034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### countLeadingZerosSlowCase {#a613b9e8e352472f9b8335408f61170bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::countLeadingZerosSlowCase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for countLeadingZeros</p>

<p>Declaration at line 2031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### countPopulationSlowCase {#ab483b2771d21710676d03b90f261789b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::countPopulationSlowCase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for countPopulation</p>

<p>Declaration at line 2043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### countTrailingOnesSlowCase {#a65e648265f559393553dbcb602451dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::countTrailingOnesSlowCase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for countTrailingOnes</p>

<p>Declaration at line 2040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### countTrailingZerosSlowCase {#a7d067bb54b5450f126ed71afd3f77a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::countTrailingZerosSlowCase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for countTrailingZeros.</p>

<p>Declaration at line 2037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### DenseMapInfo&lt; APInt, void &gt; {#a20d7da4e5886ac588791998f0280d4ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, void &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### divide {#aa318bddf2df48598a6a15d29dd4a8862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::divide (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * LHS, unsigned lhsWords, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * RHS, unsigned rhsWords, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * Quotient, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * Remainder)</td>
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

<p>An internal division function for dividing APInts.</p>


<p>This is used by the toString method to divide by the radix. It simply provides a more convenient form of divide for internal use since KnuthDiv has specific constraints on its inputs. If those constraints are not met then it provides a simpler form of divide.</p>


<p>Declaration at line 2002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### dump {#aa248cd211bcff0f457bf69b596805302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void APInt::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>debug method</p>

<p>Declaration at line 1901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2272 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#afbbb8a6117fc93aa80fabdeb82f73cf0">toStringSigned</a> and <a href="#a3591391b56f014b632b3af30b86dc51a">toStringUnsigned</a>.</p>

</div>
</div>

### DynamicAPInt {#aa20be55bb696f821d0de1f6110f04661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::APInt::DynamicAPInt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### equalSlowCase {#afb981046d3b46af85643350f9b1ecc9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool APInt::equalSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for operator==</p>

<p>Declaration at line 2028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### flipAllBitsSlowCase {#a77153208826efd0be7b0e9191e943c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::flipAllBitsSlowCase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for flipAllBits.</p>


<p>Toggle every bit to its opposite value.</p>


<p>Declaration at line 2055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### fromString {#a26555498613f6b4f0418544e84cc66a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::fromString (unsigned numBits, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> str, uint8_t radix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a char array into an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">radix</td>
<td class="doxyParamItemDescription"><p>2, 8, 10, 16, or 36 Converts a string into a number. The string must be non-empty and well-formed as a number of the given base. The bit-width must be sufficient to hold the result.</p></td>
</tr>
</table>
</dd>
</dl>

<p>This is used by the constructors that take string arguments.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">StringRef::getAsInteger</a> is superficially similar but (1) does not assume that the string is well-formed and (2) grows the result to hold the input.</p>


<p>Declaration at line 1994 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2087 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### getWord {#a9b866e976b423a794d0815b426120c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::APInt::getWord (unsigned bitPosition)</td>
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

<p>Get the word corresponding to a bit position.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the corresponding word for the specified bit position.</p></dd>
</dl>


<p>Definition at line 1973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### initFromArray {#a82d408c7d046bd8290dc63a579f61b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::initFromArray (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; array)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>shared code between two array constructors</p>

<p>Declaration at line 2010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### initSlowCase {#a3b3ee9eec1b0f38e67e8cd050e2c73c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::initSlowCase (uint64_t val, bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for inline constructor</p>

<p>Declaration at line 2007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### initSlowCase {#a20370dcafe30311a38c79c59a43dc3cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::initSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; that)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for inline copy constructor</p>

<p>Declaration at line 2013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### intersectsSlowCase {#ac50f7ae767c4c80c49390cd6f805b21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool APInt::intersectsSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for intersects.</p>

<p>Declaration at line 2046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### isSubsetOfSlowCase {#ac46b62036f824eb94e4a720315f6a233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool APInt::isSubsetOfSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for isSubsetOf.</p>

<p>Declaration at line 2049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### lshrSlowCase {#ab540634dbecd3cd9af845c222d231688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::lshrSlowCase (unsigned ShiftAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for lshr.</p>


<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Logical right-shift function.</p>


<p>Declaration at line 2019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### maskBit {#a48c00b15a7066a6d9c1aace3ac9f1e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::APInt::maskBit (unsigned bitPosition)</td>
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

<p>Get a single bit mask.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a uint64_t with only bit at "whichBit(bitPosition)" set This method generates and returns a uint64_t (word) mask for a single bit at a specific bit position. This is used to mask the bit in the corresponding word.</p></dd>
</dl>


<p>Definition at line 1945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### needsCleanup {#aa4eb77ea6033d462fc6dcc0265bfa01b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::needsCleanup ()</td>
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

<p>Returns whether this instance allocated memory.</p>

<p>Definition at line 1904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="#a280ed6ffa68d01e8757332317be2557c">~APInt</a>.</p>

</div>
</div>

### orAssignSlowCase {#a8268a612193059644ccb5c1ad32e78d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::orAssignSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for operator|=.</p>

<p>Declaration at line 2064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### Profile {#adb1c052266ebacdbf28164fae9106b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to insert <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> objects, or objects that contain <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> objects, into FoldingSets.</p>


<p>This method 'profiles' an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for use with <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>.</p>


<p>Declaration at line 1898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1f33826a7081abb8cd61583464d7ca51">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aac422f9ff091a494e6d814c5abd28bdc">llvm::APSInt::Profile</a> and <a href="/web-llvm/docs/api/classes/llvm/attributeimpl/#af02f5875e490164276cc8aac0f31b78e">llvm::AttributeImpl::Profile</a>.</p>

</div>
</div>

### reallocate {#a4e3170763968bdbbbda080f1c55650a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::reallocate (unsigned NewBitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility method to change the bit width of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to new bit width, allocating and/or deallocating as necessary.</p>


<p>There is no guarantee on the value of any bits upon return. Caller should populate the bits after.</p>


<p>Declaration at line 1980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### setBitsSlowCase {#a599b3dd8ce080368264f1bd163b3e7c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::setBitsSlowCase (unsigned loBit, unsigned hiBit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for setBits.</p>

<p>Declaration at line 2052 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### shlSlowCase {#ad3af748a79b11e301c80cf4e2a0814fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::shlSlowCase (unsigned ShiftAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for shl</p>

<p>Declaration at line 2016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### tcAdd {#a25ca60b3924e39b65a173e2b55c6e92d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType APInt::tcAdd (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * rhs, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> carry, unsigned parts)</td>
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

<p>DST += RHS + CARRY where CARRY is zero or one. Returns the carry flag.</p>

<p>Declaration at line 1827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2416 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad550e9403dfe9c20c6b8adb6acb25180">operator+=</a>.</p>

</div>
</div>

### tcAddPart {#ada4be5a4a886a268b42447b2c17eb59e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType APInt::tcAddPart (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> src, unsigned parts)</td>
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

<p>DST += RHS. Returns the carry flag.</p>


<p>This function adds a single "word" integer, src, to the multiple "word" integer array, dst[].</p>


<p>dst[] is modified to reflect the addition and 1 is returned if there is a carry out, otherwise 0 is returned.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the carry of the addition.</p></dd>
</dl>


<p>Declaration at line 1829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2438 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="#a30a2fd77599a3403f6a848952dd7f82e">operator+=</a> and <a href="#ac5bc4f0b55d702e1f7e5dea17a097e35">tcIncrement</a>.</p>

</div>
</div>

### tcAssign {#a5027d1fc1fcb950cc207e0b39821fd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcAssign (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * src, unsigned parts)</td>
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

<p>Assign one bignum to another.</p>

<p>Declaration at line 1797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2322 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#aee22783789ff4a16e831ce3edd759766">llvm::detail::IEEEFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3da3eaf2f546dd6c6f631f2e2c2436a2">llvm::detail::IEEEFloat::convertFromSignExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20386e2ecd9b41340f07d02cf0403190">llvm::powerOf5</a>, <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a> and <a href="#a2732964a6de928520d3d12be196a7a15">tcExtract</a>.</p>

</div>
</div>

### tcClearBit {#a826ad54b94fed65913c45e223099f149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcClearBit (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * parts, unsigned bit)</td>
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

<p>Clear the given bit of a bignum. Zero-based.</p>


<p>Clears the given bit of a bignum.</p>


<p>Declaration at line 1816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2347 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>.</p>

</div>
</div>

### tcCompare {#a3dd574e063a1cfeaa96175c5f9c4afa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::tcCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * rhs, unsigned parts)</td>
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

<p>Comparison (unsigned) of two bignums.</p>

<p>Declaration at line 1884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2725 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a0832f8a0b59ae97b62e74839c83898b1">llvm::detail::IEEEFloat::compareAbsoluteValue</a> and <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a>.</p>

</div>
</div>

### tcDecrement {#a83af504b239085c1725913aa1743e040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WordType llvm::APInt::tcDecrement (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, unsigned parts)</td>
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

<p>Decrement a bignum in-place. Return the borrow flag.</p>

<p>Definition at line 1892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a97a57add297988a66a8d6a81eff19cbb">tcSubtractPart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#abe7488323ce38642acc4938efe0bcc82">llvm::detail::IEEEFloat::next</a> and <a href="#ae8f371673bb2e0237b0409940657619a">operator--</a>.</p>

</div>
</div>

### tcDivide {#a9fbadc3dfac1d405b669b85267421ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::tcDivide (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * rhs, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * remainder, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * scratch, unsigned parts)</td>
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

<p>If RHS is zero LHS and REMAINDER are left unchanged, return one.</p>


<p>Otherwise set LHS to LHS / RHS with the fractional part discarded, set REMAINDER to the remainder, return zero. i.e.</p>


<p>OLD_LHS = RHS * LHS + REMAINDER</p>


<p>SCRATCH is a bignum of the same size as the operands and result for use by the routine; its contents need not be initialized and are destroyed. LHS, REMAINDER and SCRATCH must be distinct.</p>


<p>Declaration at line 1872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2630 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5027d1fc1fcb950cc207e0b39821fd10">tcAssign</a>, <a href="#a3dd574e063a1cfeaa96175c5f9c4afa9">tcCompare</a>, <a href="#a9f95a75462af1c1bd3a22cf805da64a0">tcMSB</a>, <a href="#a082bdaab3ddeb1d8e28759423242e2d5">tcSet</a>, <a href="#a8bd8fe361c9d102eb08cf77f6e4bfda4">tcShiftLeft</a>, <a href="#a52506c05d3157e52f917679cfa14cf6b">tcShiftRight</a> and <a href="#aba546a206fb7cfbc3cc5fd95a832a653">tcSubtract</a>.</p>

</div>
</div>

### tcExtract {#a2732964a6de928520d3d12be196a7a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcExtract (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, unsigned dstCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * src, unsigned srcBits, unsigned srcLSB)</td>
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

<p>Copy the bit vector of width srcBITS from SRC, starting at bit srcLSB, to DST, of dstCOUNT parts, such that the bit srcLSB becomes the least significant bit of DST.</p>


<p>All high bits above srcBITS in DST are zero-filled.</p>


<p>All high bits above srcBITS in DST are zero-filled. *‍/</p>


<p>Declaration at line 1809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2386 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#ae876a1ecb46543fee1f374dd8c2fad13">lowBitMask</a>, <a href="#a5027d1fc1fcb950cc207e0b39821fd10">tcAssign</a> and <a href="#a52506c05d3157e52f917679cfa14cf6b">tcShiftRight</a>.</p>

</div>
</div>

### tcExtractBit {#a0ffdc10d44b22d3f312c42c8922f294e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::tcExtractBit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * parts, unsigned bit)</td>
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

<p>Extract the given bit of a bignum; returns 0 or 1. Zero-based.</p>


<p>Extract the given bit of a bignum; returns 0 or 1.</p>


<p>Declaration at line 1803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2337 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3da3eaf2f546dd6c6f631f2e2c2436a2">llvm::detail::IEEEFloat::convertFromSignExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a4eea8656eab72e6218242f811ec6fc1f">llvm::detail::IEEEFloat::convertFromZeroExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#af24d88dc1da69292f443d3a4cd0bbce5">llvm::detail::IEEEFloat::isDenormal</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#accc978f15db9b1b2b8e3ac171cbac4e3">llvm::detail::IEEEFloat::isSignaling</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acfc69dbf371d7d6d656538978ddb858a">llvm::lostFractionThroughTruncation</a>.</p>

</div>
</div>

### tcFullMultiply {#a5442d90b169a8cbe8cfcb8724cf79b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcFullMultiply (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * rhs, unsigned lhsParts, unsigned rhsParts)</td>
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

<p>DST = LHS * RHS, where DST has width the sum of the widths of the operands.</p>


<p>No overflow occurs. DST must be disjoint from both operands.</p>


<p>Declaration at line 1860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2605 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5442d90b169a8cbe8cfcb8724cf79b14">tcFullMultiply</a> and <a href="#aaf3bfaa5ac3f017c8d3b7336d8bd4678">tcMultiplyPart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a20386e2ecd9b41340f07d02cf0403190">llvm::powerOf5</a> and <a href="#a5442d90b169a8cbe8cfcb8724cf79b14">tcFullMultiply</a>.</p>

</div>
</div>

### tcIncrement {#ac5bc4f0b55d702e1f7e5dea17a097e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WordType llvm::APInt::tcIncrement (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, unsigned parts)</td>
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

<p>Increment a bignum in-place. Return the carry flag.</p>

<p>Definition at line 1887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#ada4be5a4a886a268b42447b2c17eb59e">tcAddPart</a>.</p>


<p>Referenced by <a href="#a3f577ba20414abdc4328d2c5c14c37f5">operator++</a> and <a href="#abece2572a121bb1dd2c34621c1e13f76">tcNegate</a>.</p>

</div>
</div>

### tcIsZero {#a9a0a3652a0b9cd851e5b67ae442028e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool APInt::tcIsZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * src, unsigned parts)</td>
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

<p>Returns true if a bignum is zero, false otherwise.</p>

<p>Declaration at line 1800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2328 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>.</p>

</div>
</div>

### tcLSB {#a8b9c213654f22372b45d61d5db3b30c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::tcLSB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * parts, unsigned n)</td>
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

<p>Returns the bit number of the least or most significant set bit of a number.</p>


<p>Returns the bit number of the least significant set bit of a number.</p>


<p>If the input number has no bits set -1U is returned.</p>


<p>If the input number has no bits set UINT_MAX is returned.</p>


<p>Declaration at line 1820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2353 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfc69dbf371d7d6d656538978ddb858a">llvm::lostFractionThroughTruncation</a>.</p>

</div>
</div>

### tcMSB {#a9f95a75462af1c1bd3a22cf805da64a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::tcMSB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * parts, unsigned n)</td>
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

<p>Returns the bit number of the most significant set bit of a number.</p>


<p>If the input number has no bits set UINT_MAX is returned.</p>


<p>Declaration at line 1821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2366 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>.</p>


<p>Referenced by <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a>.</p>

</div>
</div>

### tcMultiply {#ab153d6d2370c0c5526009aaa07cc00e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::tcMultiply (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * rhs, unsigned parts)</td>
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

<p>DST = LHS * RHS, where DST has the same width as the operands and is filled with the least significant parts of the result.</p>


<p>Returns one if overflow occurred, otherwise zero. DST must be disjoint from both operands.</p>


<p>Declaration at line 1855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2587 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaf3bfaa5ac3f017c8d3b7336d8bd4678">tcMultiplyPart</a>.</p>


<p>Referenced by <a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a>.</p>

</div>
</div>

### tcMultiplyPart {#aaf3bfaa5ac3f017c8d3b7336d8bd4678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int APInt::tcMultiplyPart (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * src, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> multiplier, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> carry, unsigned srcParts, unsigned dstParts, bool add)</td>
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

<p>DST += SRC * MULTIPLIER + PART if add is true DST = SRC * MULTIPLIER + PART if add is false.</p>


<p>DST += SRC * MULTIPLIER + CARRY if add is true DST = SRC * MULTIPLIER + CARRY if add is false Requires 0 &lt;= DSTPARTS &lt;= SRCPARTS + 1.</p>


<p>Requires 0 &lt;= DSTPARTS &lt;= SRCPARTS + 1. If DST overlaps SRC they must start at the same point, i.e. DST == SRC.</p>


<p>If DSTPARTS == SRC_PARTS + 1 no overflow occurs and zero is returned. Otherwise DST is filled with the least significant DSTPARTS parts of the result, and if all of the omitted higher parts were zero return zero, otherwise overflow occurred and return one.</p>


<p>If DST overlaps SRC they must start at the same point, i.e. DST == SRC. If DSTPARTS == SRCPARTS + 1 no overflow occurs and zero is returned. Otherwise DST is filled with the least significant DSTPARTS parts of the result, and if all of the omitted higher parts were zero return zero, otherwise overflow occurred and return one.</p>


<p>Declaration at line 1847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2504 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a74a725ce0eb6c9d51e4c3ddf54b0de8b">highHalf</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a17d47a818ea2835a5ad9fee50c239ac1">lowHalf</a>.</p>


<p>Referenced by <a href="#aed0fa6f38807df2e9ff7f643de4f42d6">operator*=</a>, <a href="#a5442d90b169a8cbe8cfcb8724cf79b14">tcFullMultiply</a> and <a href="#ab153d6d2370c0c5526009aaa07cc00e1">tcMultiply</a>.</p>

</div>
</div>

### tcNegate {#abece2572a121bb1dd2c34621c1e13f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcNegate (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, unsigned parts)</td>
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

<p>Negate a bignum in-place.</p>

<p>Declaration at line 1824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2490 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a7b409aa866bfa91f29f51fd35bb56003">tcComplement</a> and <a href="#ac5bc4f0b55d702e1f7e5dea17a097e35">tcIncrement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3da3eaf2f546dd6c6f631f2e2c2436a2">llvm::detail::IEEEFloat::convertFromSignExtendedInteger</a>.</p>

</div>
</div>

### tcSet {#a082bdaab3ddeb1d8e28759423242e2d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcSet (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> part, unsigned parts)</td>
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

<p>Sets the least significant part of a bignum to the input value, and zeroes out higher parts.</p>

<p>Declaration at line 1794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2314 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#aee22783789ff4a16e831ce3edd759766">llvm::detail::IEEEFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a4eab9b80c0530c91c8075b6e461db19f">llvm::detail::IEEEFloat::makeInf</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a4d72a16f5c9b1344026b49a271878059">llvm::detail::IEEEFloat::makeSmallest</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#ae278d92a6dd0133695b2c02d9a6d39d7">llvm::detail::IEEEFloat::makeZero</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#abe7488323ce38642acc4938efe0bcc82">llvm::detail::IEEEFloat::next</a> and <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a>.</p>

</div>
</div>

### tcSetBit {#a06fd1421d0b30ea9b865b7238b8ca89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcSetBit (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * parts, unsigned bit)</td>
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

<p>Set the given bit of a bignum. Zero-based.</p>


<p>Set the given bit of a bignum.</p>


<p>Declaration at line 1813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2342 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#aee22783789ff4a16e831ce3edd759766">llvm::detail::IEEEFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a639825b8b65055547446e8fab3709b6f">llvm::detail::IEEEFloat::makeQuiet</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a97eaebabb01bb9d32ee07f5459be3a60">llvm::detail::IEEEFloat::makeSmallestNormalized</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#abe7488323ce38642acc4938efe0bcc82">llvm::detail::IEEEFloat::next</a>.</p>

</div>
</div>

### tcShiftLeft {#a8bd8fe361c9d102eb08cf77f6e4bfda4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcShiftLeft (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * Dst, unsigned Words, unsigned Count)</td>
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

<p>Shift a bignum left Count bits.</p>


<p>Shift a bignum left Count bits in-place.</p>


<p>Shifted in bits are zero. There are no restrictions on Count.</p>


<p>Declaration at line 1877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2672 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#aee22783789ff4a16e831ce3edd759766">llvm::detail::IEEEFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#af5c4dc333adfdd30afcce056b9b97484">llvm::detail::IEEEFloat::convertToInteger</a> and <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a>.</p>

</div>
</div>

### tcShiftRight {#a52506c05d3157e52f917679cfa14cf6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::tcShiftRight (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * Dst, unsigned Words, unsigned Count)</td>
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

<p>Shift a bignum right Count bits.</p>


<p>Shift a bignum right Count bits in-place.</p>


<p>Shifted in bits are zero. There are no restrictions on Count.</p>


<p>Declaration at line 1881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2699 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8d12f6a4d4f315160afadae72c161394">llvm::shiftRight</a>, <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a> and <a href="#a2732964a6de928520d3d12be196a7a15">tcExtract</a>.</p>

</div>
</div>

### tcSubtract {#aba546a206fb7cfbc3cc5fd95a832a653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType APInt::tcSubtract (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * rhs, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> carry, unsigned parts)</td>
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

<p>DST -= RHS + CARRY where CARRY is zero or one. Returns the carry flag.</p>


<p>DST -= RHS + C where C is zero or one. Returns the carry flag.</p>


<p>Declaration at line 1832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2451 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a86485d3a573bdd67a702e19fe7790c66">operator-=</a> and <a href="#a9fbadc3dfac1d405b669b85267421ca5">tcDivide</a>.</p>

</div>
</div>

### tcSubtractPart {#a97a57add297988a66a8d6a81eff19cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::WordType APInt::tcSubtractPart (<a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> * dst, <a href="#a5221357e5b7511cb0c90c94044ba35cf">WordType</a> src, unsigned parts)</td>
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

<p>DST -= RHS. Returns the carry flag.</p>


<p>This function subtracts a single "word" (64-bit word), src, from the multi-word integer array, dst[], propagating the borrowed 1 value until no further borrowing is needed or it runs out of "words" in dst.</p>


<p>The result is 1 if "borrowing" exhausted the digits in dst, or 0 if dst was not exhausted. In other words, if src &gt; dst then this function returns 1, otherwise 0.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the borrow out of the subtraction</p></dd>
</dl>


<p>Declaration at line 1835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2476 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Referenced by <a href="#a15edd02fb043f45d425b99ff92e7c4b0">operator-=</a> and <a href="#a83af504b239085c1725913aa1743e040">tcDecrement</a>.</p>

</div>
</div>

### U {#ac659654c41e422fb8059df365560f52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::APInt llvm::APInt::U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This union is used to store the integer value.</p>


<p>When the integer bit-width &lt;= 64, it uses VAL, otherwise it uses pVal.</p>


<p>Definition at line 1912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### whichBit {#aebe7b1978e27c8909fb8ab0276fbd269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::whichBit (unsigned bitPosition)</td>
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

<p>Determine which bit in a word the specified bit position is in.</p>

<p>Definition at line 1935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### whichWord {#ad90f6f9cd044417121c828aafc873ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::whichWord (unsigned bitPosition)</td>
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

<p>Determine which word a bit is in.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the word position for the specified bit position.</p></dd>
</dl>


<p>Definition at line 1930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### xorAssignSlowCase {#a365d61f02e84652c917f69a8b471990d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::xorAssignSlowCase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>out-of-line slow case for operator^=.</p>

<p>Declaration at line 2067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Value Tests

### getBoolValue {#ac0e942dde4b113c4c0b1fd76333db93a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::getBoolValue ()</td>
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

<p>Convert <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a boolean value.</p>


<p>This converts the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a boolean value as a test against zero.</p>


<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aae38c1d54e2059046460391f880fa837">llvm::KnownBits::computeForAddCarry</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a79fab52167a8bf5725ab31360b7e1546">llvm::KnownBits::computeForSubBorrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#ab0240a68d7340353c85a26853b20b471">getPowerOf2Factor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5959d13e50c78592ca89a8a964fb510c">llvm::ConstantRange::intrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">provablyDisjointOr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a521dc9b8649af234d8bf514085b9a640">llvm::PPCTargetLowering::SelectAddressRegReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a0b1eb53b30ddeb8ebdccc60c0837300f">walkToAllocaAndPrependOffsetDeref</a>.</p>

</div>
</div>

### getHiBits {#a2d5c4385716b3fa4a96e879987cccedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::getHiBits (unsigned numBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> containing numBits highbits from this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>This function returns the high "numBits" bits of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Get an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with the same BitWidth as this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, just zero mask the low bits and right shift to the least significant bit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the high "numBits" bits of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p></dd>
</dl>


<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d298529e6e847055ce47f80d60576d1">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#acd8fb018deb0883d60ae768058d3e871">parseHexOcta</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a835501e075de398a571345a471fd74d7">parseHexOcta</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### getLimitedValue {#ab01d8694a759a934e01f1c558c3ce862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::APInt::getLimitedValue (uint64_t Limit=<a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>)</td>
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

<p>If this value is smaller than the specified limit, return it, otherwise return the limit value.</p>


<p>This causes the value to saturate to the limit.</p>


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">ugt</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="#a79a42db75a127dc89f3962474caf145c">ashrInPlace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#abe3945bfefe671a9a34f864d493d5fe7">decompose</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a57c601613d1b256c59417e392d0575bf">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#a1d8f39cf98f0412e82e2f5bd03a09b99">extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abb66b7fb706f49e1966d64fa3ebeabfb">llvm::InstCombinerImpl::foldICmpXorShiftConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d298529e6e847055ce47f80d60576d1">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#aa18696894909136556d40020664aefe1">getMaxShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#ac2c46c98ef08efa11fd207209dabba62">llvm::BlockFrequencyInfoImplBase::getProfileCountFromFreq</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a54d4f384d80faf60cae54184adc6dcb4">getUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a607229211531af1259b2603df68033f0">isConstantSplatVectorMaskForType</a>, <a href="#aa56f74cc18a1ce46c252a0280a2fa1d2">lshrInPlace</a>, <a href="#af66c0b07cc393cb3aa9123c5d9cbfe4b">operator&lt;&lt;=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af16b5429cba93f00c53d5d4627725516">simplifySetCCWithCTPOP</a>, <a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a> and <a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a>.</p>

</div>
</div>

### getLoBits {#a0fa9845f80fa0642b31c238f4ab0d5ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::getLoBits (unsigned numBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> containing numBits lowbits from this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>This function returns the low "numBits" bits of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Get an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with the same BitWidth as this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, just zero mask the high bits.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the low "numBits" bits of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p></dd>
</dl>


<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#ad960e1ff48d25c382b6d28e7961f074e">getLowBitsSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abfd7c524b17cd29c6470d1780f06d460">matchRotateSub</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#acd8fb018deb0883d60ae768058d3e871">parseHexOcta</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a835501e075de398a571345a471fd74d7">parseHexOcta</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a76616979b7159a14d6afcb13c0106326">simplifyX86vpermilvar</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### getRawData {#ada7af1de63a848b2f452d63958de39fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t * llvm::APInt::getRawData ()</td>
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

<p>This function returns a pointer to the internal storage of the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>This is useful for writing out the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> in binary form without any conversions.</p>


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a135db5ce97b04855e9e8f44d26d30d43">llvm::detail::IEEEFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a4eea8656eab72e6218242f811ec6fc1f">llvm::detail::IEEEFloat::convertFromZeroExtendedInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af8918ba9c2bab47454cfbe9bb8942871">emitGlobalConstantLargeInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c0a683d5c4984e6d58f5f3809ff6ec3">llvm::getExpressionForConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>

</div>
</div>

### hash\_value {#a5db0645871a7aa6e466a1da24ba361fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Arg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overload to compute a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value.</p>

<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### isAligned {#a17fee74434129df42225c7e5eaab709c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool APInt::isAligned (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> -interpreted as an address- is aligned to the provided value.</p>

<p>Declaration at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a83c7c9008ba213687483b60a658b4a13">countr_zero</a>, <a href="#a49cd5939942c6665aba4cae8c220dff1">isZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>.</p>

</div>
</div>

### isAllOnes {#a423e2c491de1408d54e35f0b47d076be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isAllOnes ()</td>
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

<p>Determine if all bits are set. This is true for zero-width values.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4bef95512fa985102be74adbdb966f80">areUsedBitsDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#acc600a6141b4b54703a4ead9c72a3012">bitTrackingDCE</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac1ec85c334d8b88e52733711e53be856">createAndInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01bdf0d462d6df94d15c1763169f4cf1">EmitVectorComparison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1e71f36e9936f126265e383fd67440f7">findDemandedEltsByAllUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b307d4ad3f5e1ae0c9888b5d0cc6b54">foldBinOpIntoSelectIfProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa270db889638f96fa18c715cdce379e0">llvm::InstCombinerImpl::foldICmpMulConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5f883a229d57832ae195c8d102445847">llvm::InstCombinerImpl::foldSelectToCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aedad36f1b0e2bd04f435ca9d1a595f9e">llvm::SelectionDAG::isBoolConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adf48ee86d6a806ea693f8e4088718c4d">isCompletePermute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a08b1839785665aed1d6e91dd72764713">llvm::ISD::isConstantSplatVectorAllOnes</a>, <a href="#af976f3fd3889dab65f16068048c41168">isMaxValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#adcce576b2fe9a589249be2adce38a2e8">isSelect01</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a6027bd69e80c1591deaf7dff0257fc5d">isVectorAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a91771a953d65aeb837eecfef355de17f">lowerShuffleAsVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe25313da4ec14f1e260d91672c31545">lowerShuffleWithVPMOV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab9c1fef093fb9dfcad2e86ddd0a2a4e6">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ada593279bd9a12fd24d2a6df68acb356">llvm::SDPatternMatch::m_True</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab2e632f73c35674249cdee998f104cc0">matchMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8e4e93889aaf56eb87af0a51dce84d0d">matchShuffleAsEXTRQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acabdb7ba50c76e8a7a040985d783f507">matchShuffleAsVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ada94cd83b8b150c87b337c156f027c3c">PerformReduceShuffleCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa160a2ac0c31b48c41da949e53cc21b7">llvm::ConstantRange::sdiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### isIntN {#ae00c35cb040107c05f3fe00c15bb3da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isIntN (unsigned N)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> has an N-bits unsigned integer value.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa2aac979636ecb7e658b031a557961c8">AreMulWideOperandsDemotable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aeca82ae7bafbb557b7026f7d035643b8">llvm::ScalarEvolution::getUDivExactExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a590f094c63a53f5cda018ce31a2e541b">llvm::APSInt::isRepresentableByInt64</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a2003053288ba4f0e1cd9ebf82b6a1987">mustBeFiniteCountedLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#acd8fb018deb0883d60ae768058d3e871">parseHexOcta</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a835501e075de398a571345a471fd74d7">parseHexOcta</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a> and <a href="#a21ede0a7cd71b89d7f2f8976321bab08">truncUSat</a>.</p>

</div>
</div>

### isMask {#ac328c5d387ddf7d4a02afe9b669723c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isMask (unsigned numBits)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value is a sequence of</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>ones starting at the least significant bit with the remainder zero.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab27661a31d59b1d509386b1269369c62">detectUSatPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac4102cd12659f4a5344d443b40009893">foldRoundUpIntegerWithPow2Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab8efede7dd68d6d28fa1cfd032f9ba3b">foldSelectICmpAndZeroShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a99e3727e5ff5a1c45d0ee6dfb697308a">foldSubCtlzNot</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afe728440df980a14ddaa125c441496cc">performSubsToAndsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### isMask {#a2d68122936af3f1f89ca41c3eec2bf58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isMask ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is a non-empty sequence of ones starting at the least significant bit with the remainder zero. Ex. isMask(0x0000FFFFU) == true.</p></dd>
</dl>


<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a82a9558b6319303ae62f59dab9669685">llvm::isMask_64</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>

</div>
</div>

### isMaxSignedValue {#ac8099bedfdef48644386b16230fef2e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isMaxSignedValue ()</td>
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

<p>Determine if this is the largest signed value.</p>


<p>This checks to see if the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is the maximum signed value for the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s bit width.</p>


<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8f0b6273a443e7a98755fcb08d97f22">llvm::InstCombinerImpl::foldICmpXorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab2e632f73c35674249cdee998f104cc0">matchMinMax</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>.</p>

</div>
</div>

### isMaxValue {#af976f3fd3889dab65f16068048c41168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isMaxValue ()</td>
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

<p>Determine if this is the largest unsigned value.</p>


<p>This checks to see if the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is the maximum unsigned value for the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s bit width.</p>


<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a423e2c491de1408d54e35f0b47d076be">isAllOnes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>.</p>

</div>
</div>

### isMinSignedValue {#a1f04e382556a817950fd0390aeaf9b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isMinSignedValue ()</td>
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

<p>Determine if this is the smallest signed value.</p>


<p>This checks to see if the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is the minimum signed value for the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s bit width.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae5f691e699950ed2bb93f29742112068">cannotBeIntMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8cb3ac6c16e7d651a3f05b7ad533e52">llvm::InstCombinerImpl::commonIRemTransforms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abb66b7fb706f49e1966d64fa3ebeabfb">llvm::InstCombinerImpl::foldICmpXorShiftConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a81dc31883e0cc431912d8744c6cf9172">llvm::ConstantRange::getEquivalentICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8bcb86d8d126d95b0dc05f09e8f3df96">llvm::ScalarEvolution::getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6c03d18ed744dc3b34829ec5485a68b0">llvm::ScalarEvolution::getUDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="#a4aa7e7ca8ab4093fd0dbadb223b998c0">isSignMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab2e632f73c35674249cdee998f104cc0">matchMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0309899567234d74bf87a3899207bc15">llvm::ConstantRange::multiply</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa160a2ac0c31b48c41da949e53cc21b7">llvm::ConstantRange::sdiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="#a889c63e93f521abb41e0736a3f42cf02">sdiv_ov</a>, <a href="#ac155d7c568fc1aba25723e77b6888908">smul_ov</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ab952034edc23ad21ab312e0baaea0d7e">tryFactorization</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>.</p>

</div>
</div>

### isMinValue {#a60dd597765e178719e8d4caf44ba3b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isMinValue ()</td>
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

<p>Determine if this is the smallest unsigned value.</p>


<p>This checks to see if the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is the minimum unsigned value for the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s bit width.</p>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8cb3ac6c16e7d651a3f05b7ad533e52">llvm::InstCombinerImpl::commonIRemTransforms</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>.</p>

</div>
</div>

### isNegatedPowerOf2 {#a1b6b4785fa27be394cf040e543d9fe7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isNegatedPowerOf2 ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s negated value is a power of two greater than zero.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a>, <a href="#a83c7c9008ba213687483b60a658b4a13">countr_zero</a> and <a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5583b4d2c0c7813f44df3fe6d42d20e1">llvm::PPCTargetLowering::BuildSDIVPow2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#acb4134cc102c16e03344a4b4b21f1ea7">llvm::SystemZTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### isNegative {#a6804d9caf15411f55e7b9e9f397f0422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isNegative ()</td>
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

<p>Determine sign of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>This tests the high bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to determine if it is set.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is negative, false otherwise</p></dd>
</dl>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="#a38e964f0cadf077725453884734a6c99">abs</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a135db5ce97b04855e9e8f44d26d30d43">llvm::detail::IEEEFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a6d79f7c97b9ebb6f1e78ca528ad3c3f4">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPpi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a069a4c1f69273f1402ccb7a407e9ee4c">foldAddToAshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa270db889638f96fa18c715cdce379e0">llvm::InstCombinerImpl::foldICmpMulConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8f0b6273a443e7a98755fcb08d97f22">llvm::InstCombinerImpl::foldICmpXorConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a>, <a href="#ab9178a079b54667289f598db5b052ade">getBitsNeeded</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a3fa2c7609bef28d6ba5bdb542fb40f2d">llvm::ExpressionFormat::getMatchingString</a>, <a href="#a8924f4d542442eecf3aac41a0bd61fa3">getNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac1fce2baaba15c35a2bb18563ef08678">getStrideAndModOffsetOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6c03d18ed744dc3b34829ec5485a68b0">llvm::ScalarEvolution::getUDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#af69117a9006cbdcc4a2db996cfbf13f5">isConstantPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a1b9806d21518ef7fb4d5c4299e21411f">llvm::ScalarEvolution::isKnownNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a06719fdab228f099aeac0c8ee40a7e34">llvm::ScalarEvolution::isKnownNonNegative</a>, <a href="#ac8099bedfdef48644386b16230fef2e5">isMaxSignedValue</a>, <a href="#a1f04e382556a817950fd0390aeaf9b0e">isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a16fd96ce7d6d8206ad35461a688a780f">llvm::APSInt::isNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a>, <a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aaa54a171521e00d29d7f61f33f3269d4">isNonZeroRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a59d1e0778623481e8a1599800d892946">llvm::APIntOps::RoundingSDiv</a>, <a href="#a3c1e0381aeb551ad0ba58effe9232f97">sadd_sat</a>, <a href="#a71f7f6e3a4774296efc7274196a74793">sdiv</a>, <a href="#a81219309bccc36e3a7c38f7f5c21de8a">sdiv</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="#a5af05771dc4f41f73f052c66836657bc">sfloordiv_ov</a>, <a href="#a3291dd727de5786ef808475d8d9a1560">sgt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a>, <a href="#a0735ef8bd9cc0d99266fba0c6d7b5acb">slt</a>, <a href="#a36f62de4b8b82d2f73fb4efda79954f0">smul_sat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab9e94d7f7d74b11670e87904ed30dc2a">llvm::APIntOps::SolveQuadraticEquationWrap</a>, <a href="#ac131d830427393332e440e1d6e3013b6">srem</a>, <a href="#aeee93929dbd2133737e30498d6e12fed">srem</a>, <a href="#ab3ed902943113e485a80dff901f36494">sshl_sat</a>, <a href="#af888cb3cadd9a4e5f422c96e5674de88">ssub_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a39ed92e826ef5d0893f72b26fab78aa3">llvm::RISCVTargetLowering::targetShrinkDemandedConstant</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyinstprinter-cpp/#a63c3f91798717016cc0fbef3b4dc0b34">toString</a>, <a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a>, <a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### isNonNegative {#ac8c0157adbe12649beac0009c2f6ad8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isNonNegative ()</td>
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

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is non-negative (&gt;= 0)</p>


<p>This tests the high bit of the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to determine if it is unset.</p>


<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab27661a31d59b1d509386b1269369c62">detectUSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8d91ca7ede308b821f546a33f6625115">impliesPoisonOrCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9298a379e311818b5244bcb6b386953b">llvm::isKnownInversion</a>, <a href="#a1b6b4785fa27be394cf040e543d9fe7c">isNegatedPowerOf2</a>, <a href="#aa17c104fbda554c818cf87e53f32f20a">isStrictlyPositive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0309899567234d74bf87a3899207bc15">llvm::ConstantRange::multiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="#a694293446a074c3d64270e7671bb5052">sadd_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a51ae77be815f3771d7e0e1837204af01">llvm::ConstantRange::srem</a>, <a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a36128583fce0d74508c8dc73e56ee905">llvm::ConstantRange::sshl_sat</a>, <a href="#ae324de5041feaf7eb8433221cdaca9aa">ssub_ov</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a86f75bbbe87c45fd3f9047fbad61671c">trySimplifyICmpWithAdds</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>.</p>

</div>
</div>

### isNonPositive {#a98e0e44eba106bcebce4b276d2c541c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isNonPositive ()</td>
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

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is non-positive (&lt;= 0).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is non-positive.</p></dd>
</dl>


<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#aa17c104fbda554c818cf87e53f32f20a">isStrictlyPositive</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a86f75bbbe87c45fd3f9047fbad61671c">trySimplifyICmpWithAdds</a>.</p>

</div>
</div>

### isOne {#aea5f26deda5ef97e02f6afc57c0c3920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isOne ()</td>
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

<p>Determine if this is a value of 1.</p>


<p>This checks to see if the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is one.</p>


<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7e46711e88afd58c383ff1f504a173f5">combineSelectOfTwoConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5f883a229d57832ae195c8d102445847">llvm::InstCombinerImpl::foldSelectToCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aedad36f1b0e2bd04f435ca9d1a595f9e">llvm::SelectionDAG::isBoolConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#adcce576b2fe9a589249be2adce38a2e8">isSelect01</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ada593279bd9a12fd24d2a6df68acb356">llvm::SDPatternMatch::m_True</a>, <a href="#aba59baafccd4c4796301b857df3c40c6">multiplicativeInverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isOneBitSet {#a893a459d66560dde653d7c598978edd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isOneBitSet (unsigned BitNo)</td>
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

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> only has the specified bit set.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> only has the specified bit set.</p></dd>
</dl>


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">popcount</a>.</p>

</div>
</div>

### isPowerOf2 {#ad1b0513de876d1c85cf6268ca21b2c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isPowerOf2 ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s value is a power of two greater than zero.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the argument <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value is a power of two &gt; 0.</p></dd>
</dl>


<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5583b4d2c0c7813f44df3fe6d42d20e1">llvm::PPCTargetLowering::BuildSDIVPow2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7e46711e88afd58c383ff1f504a173f5">combineSelectOfTwoConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="#a6f1d5427c61a0f0159f6e85f41944c5c">exactLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aefdb6cdad27dd579e957c1b68f87847c">foldICmpWithTruncSignExtendedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abb66b7fb706f49e1966d64fa3ebeabfb">llvm::InstCombinerImpl::foldICmpXorShiftConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#acb4134cc102c16e03344a4b4b21f1ea7">llvm::SystemZTTIImpl::getArithmeticInstrCost</a>, <a href="#ab9178a079b54667289f598db5b052ade">getBitsNeeded</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af46fd5126112a587bb12f09b1c0e385b">llvm::ConstantExpr::getExactLogBase2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a39257c6c73db3440e6d05b9eec5999a0">getMaskedICmpType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#af69117a9006cbdcc4a2db996cfbf13f5">isConstantPowerOfTwo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9941226cefb2787fa29507c4f5630d6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a174f58016581c78f194dcc75579abb7d">isPowerOf2Constant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afe728440df980a14ddaa125c441496cc">performSubsToAndsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a463fad626413d686ec86863553e1a559">useInversedSetcc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>.</p>

</div>
</div>

### isSameValue {#ad76807eccec7690dec05dd5f36aceb08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSameValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; I1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; I2)</td>
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

<p>Determine if two APInts have the same value, after zero-extending one of them (if needed!) to ensure that the bit-widths match.</p>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#af0c949f0956bdd475184e8d934dc96e2">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPii</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/specific-intval/#aeaeac10d9314d9c15d1158cef151b571">llvm::PatternMatch::specific_intval&lt; AllowPoison &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/specificint-match/#a6719b5d3d4004c67653f752f25920436">llvm::SDPatternMatch::SpecificInt_match::match</a> and <a href="/web-llvm/docs/api/structs/llvm/vplanpatternmatch/specific-intval/#afaa3726bf59f26e6b1040f80c99167aa">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::match</a>.</p>

</div>
</div>

### isShiftedMask {#aaea11bb657e8d5f0eacfc4ddc1a1dc16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isShiftedMask ()</td>
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

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value contains a non-empty sequence of ones with the remainder zero.</p>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>

</div>
</div>

### isShiftedMask {#a920c67b5656a050f49ab14cfb488726d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isShiftedMask (unsigned &amp; MaskIdx, unsigned &amp; MaskLen)</td>
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

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value contains a non-empty sequence of ones with the remainder zero.</p>


<p>If true, <span class="doxyComputerOutput">MaskIdx</span> will specify the index of the lowest set bit and <span class="doxyComputerOutput">MaskLen</span> is updated to specify the length of the mask, else neither are updated.</p>


<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a582e08755c7a8d1b0bf6c5dcb765aaa8">llvm::isShiftedMask_64</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>

</div>
</div>

### isSignBitClear {#af3bf988ca1898a53284d4e3f9dac6d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSignBitClear ()</td>
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

<p>Determine if sign bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is clear.</p>


<p>This tests the high bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to determine if it is clear.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> has its sign bit clear, false otherwise.</p></dd>
</dl>


<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#ada19a89b7c62ce0bb713a7254b002445">isSignBitSet</a>.</p>

</div>
</div>

### isSignBitSet {#ada19a89b7c62ce0bb713a7254b002445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSignBitSet ()</td>
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

<p>Determine if sign bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is set.</p>


<p>This tests the high bit of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to determine if it is set.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> has its sign bit set, false otherwise.</p></dd>
</dl>


<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="#af3bf988ca1898a53284d4e3f9dac6d9d">isSignBitClear</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ac4d3bfb8f8f9526c1e2703ef25f43418">toSigned</a>.</p>

</div>
</div>

### isSignedIntN {#a87d50d10274efe9688166584391ae489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSignedIntN (unsigned N)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> has an N-bits signed integer value.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa2aac979636ecb7e658b031a557961c8">AreMulWideOperandsDemotable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad0f859410a5e693f74b9c87a59cb9b85">combineSubOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#adcd35cd6dd267ca162a87fac0acb4925">computeFlagsForAddressComputation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab1fbe8bf005228a2fea5deb173b08e47">llvm::NVPTXTargetLowering::isLegalAddressingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a67dbc70a08c8d7078e23f0a57a9ffbbe">llvm::RISCVTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a590f094c63a53f5cda018ce31a2e541b">llvm::APSInt::isRepresentableByInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a39ed92e826ef5d0893f72b26fab78aa3">llvm::RISCVTargetLowering::targetShrinkDemandedConstant</a>, <a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a463fad626413d686ec86863553e1a559">useInversedSetcc</a>.</p>

</div>
</div>

### isSignMask {#a4aa7e7ca8ab4093fd0dbadb223b998c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSignMask ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>'s value is returned by getSignMask.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this is the value returned by getSignMask.</p></dd>
</dl>


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a1f04e382556a817950fd0390aeaf9b0e">isMinSignedValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a069a4c1f69273f1402ccb7a407e9ee4c">foldAddToAshr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8f0b6273a443e7a98755fcb08d97f22">llvm::InstCombinerImpl::foldICmpXorConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### isSingleWord {#a5ed1d98c99f36cde30cb052c78fa5e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSingleWord ()</td>
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

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> just has one word to store value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the number of bits &lt;= 64, false otherwise.</p></dd>
</dl>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>.</p>


<p>Referenced by <a href="#a5e48746426d66487629b456a7baa5fb6">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a7e30b3aa214eba50eed018b5b19fc6aa">ashrInPlace</a>, <a href="#a781bd5c20864a9c185018258af774ace">clearAllBits</a>, <a href="#a155466c9ea0a2bd00e09c62fdce2c052">clearBit</a>, <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a>, <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a>, <a href="#af34a543ce8585d04c1ae22c78b3182dd">countr_one</a>, <a href="#a83c7c9008ba213687483b60a658b4a13">countr_zero</a>, <a href="#adf997f1047734d3b47b8d5a9b2163f11">extractBits</a>, <a href="#a29177946d0b9d5003e7a952a9684b797">extractBitsAsZExtValue</a>, <a href="#aa26382591715c45666c3c6336755d529">flipAllBits</a>, <a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a>, <a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e3c089e61a9927131ee18b4eb7c7c5c">llvm::hash_value</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="#a369007fafbf2f88498f412f00eb0a469">insertBits</a>, <a href="#a6da514c588b2668280a861a59bfc9fa5">intersects</a>, <a href="#a423e2c491de1408d54e35f0b47d076be">isAllOnes</a>, <a href="#a2d68122936af3f1f89ca41c3eec2bf58">isMask</a>, <a href="#ac328c5d387ddf7d4a02afe9b669723c7">isMask</a>, <a href="#ac8099bedfdef48644386b16230fef2e5">isMaxSignedValue</a>, <a href="#a1f04e382556a817950fd0390aeaf9b0e">isMinSignedValue</a>, <a href="#aea5f26deda5ef97e02f6afc57c0c3920">isOne</a>, <a href="#ad1b0513de876d1c85cf6268ca21b2c86">isPowerOf2</a>, <a href="#aaea11bb657e8d5f0eacfc4ddc1a1dc16">isShiftedMask</a>, <a href="#a920c67b5656a050f49ab14cfb488726d">isShiftedMask</a>, <a href="#acfae9bdee6027ffa8ffe244cc22e3a76">isSubsetOf</a>, <a href="#a49cd5939942c6665aba4cae8c220dff1">isZero</a>, <a href="#af338e23a90c301183968435e80cd6a27">lshrInPlace</a>, <a href="#aa4eb77ea6033d462fc6dcc0265bfa01b">needsCleanup</a>, <a href="#a38c8efc9c8dd13e8cdc39109283552a0">operator&amp;=</a>, <a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">operator&amp;=</a>, <a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a>, <a href="#aed0fa6f38807df2e9ff7f643de4f42d6">operator*=</a>, <a href="#a3f577ba20414abdc4328d2c5c14c37f5">operator++</a>, <a href="#ad550e9403dfe9c20c6b8adb6acb25180">operator+=</a>, <a href="#a30a2fd77599a3403f6a848952dd7f82e">operator+=</a>, <a href="#ae8f371673bb2e0237b0409940657619a">operator--</a>, <a href="#a86485d3a573bdd67a702e19fe7790c66">operator-=</a>, <a href="#a15edd02fb043f45d425b99ff92e7c4b0">operator-=</a>, <a href="#a6f57dd5ed73b3c76a3d208bb1a67228a">operator&lt;&lt;=</a>, <a href="#ac425969d2fbffcdd54e3ab18b35c680e">operator=</a>, <a href="#a3c3ff3a632850951cea84d8c6466890b">operator=</a>, <a href="#a5706001980ca4d8b32c73ca742bcc4fa">operator=</a>, <a href="#a8eeb6b0ef83a291455cb52d6e0a5a612">operator==</a>, <a href="#a5f74c7368cdc65e9e942faca9976d080">operator==</a>, <a href="#ac605f0a460fdb9a65dd94d2eaa0722f1">operator^=</a>, <a href="#a4627e5f0560b9d5f40fb309ea263de9d">operator^=</a>, <a href="#a5ea5541c90a06aae894eb1e99ba2d579">operator|=</a>, <a href="#a4a10e817a053d9ec8b63fc11a061f41e">operator|=</a>, <a href="#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">popcount</a>, <a href="#adb1c052266ebacdbf28164fae9106b0a">Profile</a>, <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>, <a href="#ab6fff8a97bcb55e50e9be0ecf0c99b63">setAllBits</a>, <a href="#a33f9f862dca8ee0f23bff5941bf433d8">setBit</a>, <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>, <a href="#a3291dd727de5786ef808475d8d9a1560">sgt</a>, <a href="#a0735ef8bd9cc0d99266fba0c6d7b5acb">slt</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a7da80f756644226c925de9aa4bf77d94">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#abfeca4698f01ef85e21a3e3061751781">ugt</a>, <a href="#afe03273b7efa986834cca7b9899a686b">ult</a>, <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a> and <a href="#a825a8dca80ee195760b908990de1a7af">urem</a>.</p>

</div>
</div>

### isSplat {#a841147c648072358e88b0d0a50359ebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool APInt::isSplat (unsigned SplatSizeInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> consists of a repeated bit pattern.</p>


<p>e.g. 0x01010101 satisfies isSplat(8).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SplatSizeInBits</td>
<td class="doxyParamItemDescription"><p>The size of the pattern in bits. Must divide bit width without remainder.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> and <a href="#aa548cc4a0fd9e7c713b180f7780655e2">rotl</a>.</p>

</div>
</div>

### isStrictlyPositive {#aa17c104fbda554c818cf87e53f32f20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isStrictlyPositive ()</td>
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

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is positive.</p>


<p>This tests if the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is positive (&gt; 0). Note that 0 is not a positive value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is positive.</p></dd>
</dl>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a121ee24f11c464f3b3197cac87b0980e">llvm::ScalarEvolution::isKnownNonPositive</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a672708a81ae8da8fb56e32638ca9b3">llvm::ScalarEvolution::isKnownPositive</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a>, <a href="#a98e0e44eba106bcebce4b276d2c541c9">isNonPositive</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>.</p>

</div>
</div>

### isZero {#a49cd5939942c6665aba4cae8c220dff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isZero ()</td>
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

<p>Determine if this value is zero, i.e. all bits are clear.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a856d46e90d7159a88c175ceff667f40c">canonicalizeGEPOfConstGEPI8</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b34d93dd35343dbb2d4d9496ed85cd9">canWidenShuffleElements</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a19b02b875049489fedf9c500d2424fa3">llvm::GEPOperator::collectOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad00ef9b94ff672e7a3ef2a0cae24b757">combineBlendOfPermutes</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aa730d6c2ddb52a05e3602c501e961629">computeKnownBitsForHorizontalOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe6e3bcd34e503c8492f7aba19a3864e">computeKnownBitsForHorizontalOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac1ec85c334d8b88e52733711e53be856">createAndInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add0f77cf0080542aad1132fff681ef7c">llvm::exprDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45ec897890074179e7de73b934798976">foldAndOrOfICmpEqConstantAndICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a579fe4e09073387531e02810501c6855">foldAndOrOfSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b307d4ad3f5e1ae0c9888b5d0cc6b54">foldBinOpIntoSelectIfProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa270db889638f96fa18c715cdce379e0">llvm::InstCombinerImpl::foldICmpMulConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a47a83bda096455c177d40a2fbae13de1">llvm::InstCombinerImpl::foldICmpShlConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a8f3e4fda4ce5ab01260df66b88ebabd3">GEPToVectorIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6302b532981eadcac10d0d3ab01e3805">llvm::getShuffleDemandedElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="#a17fee74434129df42225c7e5eaab709c">isAligned</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aedad36f1b0e2bd04f435ca9d1a595f9e">llvm::SelectionDAG::isBoolConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a531723c97a9c44056fc4996bde57229e">llvm::ISD::isConstantSplatVectorAllZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0fc8d69e5f9f1289c79f3e49cc3bfc5">llvm::SelectionDAG::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aaa54a171521e00d29d7f61f33f3269d4">isNonZeroRecurrence</a>, <a href="/web-llvm/docs/api/classes/anonymous-interleavedloadcombinepass-cpp-/polynomial/#aab36480a7c88876050105835be050f98">anonymous{InterleavedLoadCombinePass.cpp}::Polynomial::isProvenEqualTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#adcce576b2fe9a589249be2adce38a2e8">isSelect01</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af83ff96c157ea2db2a7f032cc9c80369">isTargetShuffleEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab491618a9074f0b773aa605bcb9450d3">LowerBuildVectorv16i8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#aea6c92b98e36f3faf9e661361a232979">llvm::SDPatternMatch::m_False</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab2e632f73c35674249cdee998f104cc0">matchMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ab7155d5feabf02f01c4d3b7d9c422">llvm::LegalizerHelper::narrowScalarShiftByConstant</a>, <a href="#a0ee171002efe1360b112e2bc4bd0674f">nearestLogBase2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a59d1e0778623481e8a1599800d892946">llvm::APIntOps::RoundingSDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a1c533fb6a26fce38d9cec2b51a7a90b0">llvm::APIntOps::RoundingUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa160a2ac0c31b48c41da949e53cc21b7">llvm::ConstantRange::sdiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa9bbead3db102aa9d3eaeb47e695db1a">llvm::InstCombinerImpl::SimplifyAddWithRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7e500d9f027b07d62374f0cee5d56724">llvm::InstCombinerImpl::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a49bff27cd8c639d90493b91350d3d9d0">llvm::X86TTIImpl::simplifyDemandedUseBitsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a177f4d30b9356e0bc4a5dc176e825cb2">simplifyIRemMulShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab9e94d7f7d74b11670e87904ed30dc2a">llvm::APIntOps::SolveQuadraticEquationWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a51ae77be815f3771d7e0e1837204af01">llvm::ConstantRange::srem</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad41d307fed42f6776d36397336e81985">llvm::ConstantRange::udiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a96120d4062fabb503b1b92401e54d14f">llvm::KnownBits::udiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### \~APInt {#a280ed6ffa68d01e8757332317be2557c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APInt::~APInt ()</td>
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

<p>Destructor.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#aa4eb77ea6033d462fc6dcc0265bfa01b">needsCleanup</a>.</p>

</div>
</div>

### APInt {#a44d65323d90a63e5f572fe8f44db1154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APInt::APInt (unsigned numBits, uint64_t val, bool isSigned=false, bool implicitTrunc=false)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of numBits width, initialized as val.</p>


<p>If isSigned is true then val is treated as if it were a signed value (i.e. as an int64_t) and the appropriate sign extension to the bit width will be done. Otherwise, no sign extension occurs (high order bits beyond the range of val are zero filled).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the bit width of the constructed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">val</td>
<td class="doxyParamItemDescription"><p>the initial value of the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isSigned</td>
<td class="doxyParamItemDescription"><p>how to treat signedness of val</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">implicitTrunc</td>
<td class="doxyParamItemDescription"><p>allow implicit truncation of non-zero/sign bits of val beyond the range of numBits</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>.</p>


<p>Referenced by <a href="#a38e964f0cadf077725453884734a6c99">abs</a>, <a href="#a66ea4e1cdf19ee1f92265f6b3bd34e7d">APInt</a>, <a href="#a5e48746426d66487629b456a7baa5fb6">APInt</a>, <a href="#a248989f3fc86500daacfd87a0a8657bc">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a8b3f9ea222b9abce0f4a502d4504657c">llvm::APSInt::APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a8d3c6bd8729cd1fcbee8b2534affc30d">llvm::APSInt::APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a418dc37bbe3a6fbd4192291ace00300d">llvm::APSInt::APSInt</a>, <a href="#a61c2c3c3344946ca0d70b0da418b52e4">ashr</a>, <a href="#ab6006923d1a3139d70abc8f6552a7960">ashr</a>, <a href="#a79a42db75a127dc89f3962474caf145c">ashrInPlace</a>, <a href="#ace0bd40e4bee1851ebebb276178d65fc">byteSwap</a>, <a href="#a392d67031c5429420ac0b46478fe893e">ceilLogBase2</a>, <a href="#aef3f66072750c56846c44817e7336a3d">clearHighBits</a>, <a href="#aac76bff09195240a482b319136ab6144">clearLowBits</a>, <a href="#a6bc2ad05ce14ae805c176fc8abfbe0a1">concat</a>, <a href="#a20d7da4e5886ac588791998f0280d4ce">DenseMapInfo&lt; APInt, void &gt;</a>, <a href="#ac174a45e376a00ec9b2e9e8730f982c0">doubleToBits</a>, <a href="#a6e17f9e532ca4a61804f28091b10b522">eq</a>, <a href="#adf997f1047734d3b47b8d5a9b2163f11">extractBits</a>, <a href="#a4b160c2704ee3819d8fda70345b4d19f">floatToBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a12104865ac55c27d5a97bd72d4b750b7">llvm::APSInt::get</a>, <a href="#a071e8d814b2b30b02544fad964227b8e">getAllOnes</a>, <a href="#ab9178a079b54667289f598db5b052ade">getBitsNeeded</a>, <a href="#a46ceedee591f92727b85641794a96061">getBitsSet</a>, <a href="#aeaf22e8d92fd978a5eca9ab031994399">getBitsSetFrom</a>, <a href="#af3bee3e462a14abdf3858c354a5cd222">getBitsSetWithWrap</a>, <a href="#a2d5c4385716b3fa4a96e879987cccedc">getHiBits</a>, <a href="#adcb96bd09d7c75c7669fa5f9d1190899">getHighBitsSet</a>, <a href="#a0fa9845f80fa0642b31c238f4ab0d5ef">getLoBits</a>, <a href="#ad960e1ff48d25c382b6d28e7961f074e">getLowBitsSet</a>, <a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a>, <a href="#a65a6479206acd4113b8aa1c0fbc2158c">getMinValue</a>, <a href="#aec662ee6ab1490a4cabebf2812e5b9ca">getOneBitSet</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="#a1e6f0d8dfed0ab631b488a3e6317718e">getSignMask</a>, <a href="#a8c55d8510ad4b7cb957d8f5a7cd6944e">getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a6593f5aa13227a1db6af52069fcfe3b2">llvm::APSInt::getUnsigned</a>, <a href="#add4e37b60ea64faafbc9a5bf3e27280f">getZero</a>, <a href="#aae66680c2cf6c3acccde9cd1189a0215">getZeroWidth</a>, <a href="#a5db0645871a7aa6e466a1da24ba361fb">hash_value</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="#a6da514c588b2668280a861a59bfc9fa5">intersects</a>, <a href="#ad76807eccec7690dec05dd5f36aceb08">isSameValue</a>, <a href="#acfae9bdee6027ffa8ffe244cc22e3a76">isSubsetOf</a>, <a href="#a98d705ad0b507dd7c488017c2ad5c8ae">lshr</a>, <a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a>, <a href="#aa56f74cc18a1ce46c252a0280a2fa1d2">lshrInPlace</a>, <a href="#aba59baafccd4c4796301b857df3c40c6">multiplicativeInverse</a>, <a href="#ad53de8dfd63f774033284907674f79ee">ne</a>, <a href="#a3509642df002d9bc4e089eff3a6eedcb">operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a743415ef16a31bc7c84e9f7ab43ffd77">llvm::APSInt::operator&amp;</a>, <a href="#a38c8efc9c8dd13e8cdc39109283552a0">operator&amp;=</a>, <a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">operator&amp;=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a83359a4d7b4dd311575324b73e155035">llvm::APSInt::operator&amp;=</a>, <a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a362dcab03bc42a305f3c62db691daac7">llvm::APSInt::operator*</a>, <a href="#ab7984341f7e873ae3619874ae89c3afb">operator*=</a>, <a href="#aed0fa6f38807df2e9ff7f643de4f42d6">operator*=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a373350cfe26941337fedf82796444e1d">llvm::APSInt::operator*=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a4970be7e89c76c9fc31870e189487c86">llvm::APSInt::operator+</a>, <a href="#a3f577ba20414abdc4328d2c5c14c37f5">operator++</a>, <a href="#a5f7c144083982c1260b97f09f07274d5">operator++</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a3ec345f698381947eaca2b9c5a8b61c1">llvm::APSInt::operator++</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a5850ef75730e924d2a3eb1b2b8065e2f">llvm::APSInt::operator++</a>, <a href="#ad550e9403dfe9c20c6b8adb6acb25180">operator+=</a>, <a href="#a30a2fd77599a3403f6a848952dd7f82e">operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a068ebd196df9fdd6a8123fc2a3be51ec">llvm::APSInt::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a66bf0c96c9859665f6541b4ce8be8532">llvm::APSInt::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0855daeef1e9cdbe92fc5fd385eeb5e5">llvm::APSInt::operator-</a>, <a href="#ae8f371673bb2e0237b0409940657619a">operator--</a>, <a href="#a1f7633734a43c7c7475d68fbfa343527">operator--</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af2094babfc54cb625aba1a3c50a39749">llvm::APSInt::operator--</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a77cddfafc4d18f0d88d8e2712a1469c5">llvm::APSInt::operator--</a>, <a href="#a86485d3a573bdd67a702e19fe7790c66">operator-=</a>, <a href="#a15edd02fb043f45d425b99ff92e7c4b0">operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ada071da8ac7193e577b6363ecc857e08">llvm::APSInt::operator-=</a>, <a href="#a28bc2404b2316a5e4b6ff9113ba270ab">operator&lt;&lt;</a>, <a href="#a2e24bc7f50e82dee742541ad86b449c6">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a6f30b7fdef45b6381891e15058fde704">llvm::APSInt::operator&lt;&lt;</a>, <a href="#af66c0b07cc393cb3aa9123c5d9cbfe4b">operator&lt;&lt;=</a>, <a href="#a6f57dd5ed73b3c76a3d208bb1a67228a">operator&lt;&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#afe7be41cf6c4c816244791d3498f26e4">llvm::APSInt::operator&lt;&lt;=</a>, <a href="#ac425969d2fbffcdd54e3ab18b35c680e">operator=</a>, <a href="#a3c3ff3a632850951cea84d8c6466890b">operator=</a>, <a href="#a5706001980ca4d8b32c73ca742bcc4fa">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a09a4b7b345463fcac3ee2a8964556e9e">llvm::APSInt::operator=</a>, <a href="#a8eeb6b0ef83a291455cb52d6e0a5a612">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a2fdb5053e7cfd3ab44afd53c2500b7a0">llvm::APSInt::operator^</a>, <a href="#ac605f0a460fdb9a65dd94d2eaa0722f1">operator^=</a>, <a href="#a4627e5f0560b9d5f40fb309ea263de9d">operator^=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#afb8467598c22aa3ccba4d04cb56fae3a">llvm::APSInt::operator^=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ae79c7a3d485e0b7d6a1e648c71af2536">llvm::APSInt::operator|</a>, <a href="#a5ea5541c90a06aae894eb1e99ba2d579">operator|=</a>, <a href="#a4a10e817a053d9ec8b63fc11a061f41e">operator|=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa985a05855fc28f5272a235cd3f40891">llvm::APSInt::operator|=</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a8de293914759628d50bb12a1ffe6b76a">llvm::APSInt::operator~</a>, <a href="#a793e27a4e7b6ec5ecab8e7616e0d4ac0">relativeAShl</a>, <a href="#a57604a130a7bf75be0295a8ba37ff4fe">relativeAShr</a>, <a href="#a3bbf73dc4411a52b8d03e582a09893ce">relativeLShl</a>, <a href="#a1aeae6359e573a57ce8db93b8b26b19a">relativeLShr</a>, <a href="#a7b8b4253b618610eb5cb497b4104ebc3">reverseBits</a>, <a href="#a65bc3d32a3f55045259fda31d9fffb28">rotl</a>, <a href="#aa548cc4a0fd9e7c713b180f7780655e2">rotl</a>, <a href="#acc8a2eb3a9949f9e26c2724ef3a109cd">rotr</a>, <a href="#a7add4efc2976e2d2b52a1e5d427ce616">rotr</a>, <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>, <a href="#a694293446a074c3d64270e7671bb5052">sadd_ov</a>, <a href="#a3c1e0381aeb551ad0ba58effe9232f97">sadd_sat</a>, <a href="#a71f7f6e3a4774296efc7274196a74793">sdiv</a>, <a href="#a81219309bccc36e3a7c38f7f5c21de8a">sdiv</a>, <a href="#a889c63e93f521abb41e0736a3f42cf02">sdiv_ov</a>, <a href="#a24187c2e178af0df22dac26cd5229294">sdivrem</a>, <a href="#a76e54fadf3b01da96aaa66c35ed8c366">sdivrem</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="#a9b5fc98b47d44d1150d3610bdfab1430">sextOrTrunc</a>, <a href="#a5af05771dc4f41f73f052c66836657bc">sfloordiv_ov</a>, <a href="#ae2b7d8c018c8a37fa8ea422a13bfd412">sge</a>, <a href="#a3d430216d32f4363e4df154599b98055">sgt</a>, <a href="#a8f1d88206e3ce5514de646f23f0042bc">shl</a>, <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>, <a href="#a7e8226e6453c8bcf7e5c06d28b1e207b">sle</a>, <a href="#adafa9575780f9246d1df0b7e2a619356">slt</a>, <a href="#ac155d7c568fc1aba25723e77b6888908">smul_ov</a>, <a href="#a36f62de4b8b82d2f73fb4efda79954f0">smul_sat</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="#ac131d830427393332e440e1d6e3013b6">srem</a>, <a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a>, <a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a>, <a href="#a90e6be77d59fee53e8585874cd1ab07c">sshl_sat</a>, <a href="#ab3ed902943113e485a80dff901f36494">sshl_sat</a>, <a href="#ae324de5041feaf7eb8433221cdaca9aa">ssub_ov</a>, <a href="#af888cb3cadd9a4e5f422c96e5674de88">ssub_sat</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aff8bfdb27a0027b84b0c3580c0d9f530">llvm::APSInt::toString</a>, <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a>, <a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a>, <a href="#a21ede0a7cd71b89d7f2f8976321bab08">truncUSat</a>, <a href="#a8268fbc3014081004056f6466452c904">uadd_ov</a>, <a href="#ab4c04665274d4f30d732639dc055821c">uadd_sat</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>, <a href="#a8bd2f21c3219cdb1c83f080dc7e1fc31">udivrem</a>, <a href="#af4b1ccc0b78f9da9f3f3944e06007f1d">uge</a>, <a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">ugt</a>, <a href="#aca14d9ec64ba4ab7fb2cef37c57d9ce4">ule</a>, <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>, <a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a>, <a href="#acf4d36ebf88039604b73d3527506c3ed">umul_sat</a>, <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>, <a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a>, <a href="#ac8345a3be974d824185f13fc5c196393">ushl_ov</a>, <a href="#a9458a57a572f29dd261a3be65cd8ee9f">ushl_sat</a>, <a href="#a236aa749101900bc9e8e6cd108bdec6a">ushl_sat</a>, <a href="#a44d622af4cca05108d8d7eb9bfd79977">usub_ov</a>, <a href="#a059dc64e71df065315050d2270cbfba5">usub_sat</a>, <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a> and <a href="#a2ed912a28808268e35bd58e8f11251aa">zextOrTrunc</a>.</p>

</div>
</div>

### APInt {#a4a46ba6ad1c259b7fa9bc638ebb0a2f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::APInt (unsigned numBits, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; bigVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of numBits width, initialized as bigVal[].</p>


<p>Note that bigVal.size() can be smaller or larger than the corresponding bit width but any extraneous bits will be dropped.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the bit width of the constructed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">bigVal</td>
<td class="doxyParamItemDescription"><p>a sequence of words to form the initial value of the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### APInt {#a918deddd001f5b6d1e3439cbc5a3abab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::APInt (unsigned numBits, unsigned numWords, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t bigVal=[])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Equivalent to APInt(numBits, ArrayRef&lt;uint64_t&gt;(bigVal, numWords)), but deprecated because this constructor is prone to ambiguity with the APInt(unsigned, uint64_t, bool) constructor.</p>


<p>If this overload is ever deleted, care should be taken to prevent calls from being incorrectly captured by the APInt(unsigned, uint64_t, bool) constructor.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### APInt {#a337b62553d6b0e5ce2868e086b589a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt::APInt (unsigned numBits, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> str, uint8_t radix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> from a string representation.</p>


<p>This constructor interprets the string <span class="doxyComputerOutput">str</span> in the given radix. The interpretation stops when the first character that is not suitable for the radix is encountered, or the end of the string. Acceptable radix values are 2, 8, 10, 16, and 36. It is an error for the value implied by the string to require more bits than numBits.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the bit width of the constructed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">str</td>
<td class="doxyParamItemDescription"><p>the string to be interpreted</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">radix</td>
<td class="doxyParamItemDescription"><p>the radix to use for the conversion</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>

</div>
</div>

### APInt {#a628da9238224184ed7085b6830c1fcff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APInt::APInt ()</td>
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

<p>Default constructor that creates an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with a 1-bit zero value.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="#ace0bd40e4bee1851ebebb276178d65fc">byteSwap</a>, <a href="#adf997f1047734d3b47b8d5a9b2163f11">extractBits</a>, <a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a>, <a href="#a7b8b4253b618610eb5cb497b4104ebc3">reverseBits</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a>, <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>, <a href="#a8bd2f21c3219cdb1c83f080dc7e1fc31">udivrem</a>, <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>, <a href="#ac8345a3be974d824185f13fc5c196393">ushl_ov</a>, <a href="#a059dc64e71df065315050d2270cbfba5">usub_sat</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>

</div>
</div>

### APInt {#a5e48746426d66487629b456a7baa5fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APInt::APInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; that)</td>
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

<p>Copy Constructor.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a>.</p>

</div>
</div>

### APInt {#a66ea4e1cdf19ee1f92265f6b3bd34e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APInt::APInt (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;&amp; that)</td>
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

<p>Move Constructor.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Unary Operators

### operator-- {#a1f7633734a43c7c7475d68fbfa343527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::operator-- (int)</td>
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

<p>Postfix decrement operator.</p>


<p>Decrement *this by 1.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a new <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value representing the original value of *this.</p></dd>
</dl>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### operator-- {#ae8f371673bb2e0237b0409940657619a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator-- ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prefix decrement operator.</p>


<p>Prefix decrement operator. Decrements the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by one.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this decremented by one.</p></dd>
</dl>


<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a83af504b239085c1725913aa1743e040">tcDecrement</a> and <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a>.</p>

</div>
</div>

### operator! {#a5625372cfd66999c6d53a063012fc8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::operator! ()</td>
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

<p>Logical negation operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> returns true if zero, like normal integers.</p>

<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>

</div>
</div>

### operator++ {#a5f7c144083982c1260b97f09f07274d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::operator++ (int)</td>
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

<p>Postfix increment operator.</p>


<p>Increment *this by 1.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a new <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value representing the original value of *this.</p></dd>
</dl>


<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### operator++ {#a3f577ba20414abdc4328d2c5c14c37f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator++ ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prefix increment operator.</p>


<p>Prefix increment operator. Increments the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by one.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this incremented by one</p></dd>
</dl>


<p>Declaration at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#ac5bc4f0b55d702e1f7e5dea17a097e35">tcIncrement</a> and <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Assignment Operators

### operator-= {#a86485d3a573bdd67a702e19fe7790c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtraction assignment operator.</p>


<p>Subtracts the RHS <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> from this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Subtracts RHS from *this and assigns the result to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>this, after subtraction Subtraction assignment operator.</p></dd>
</dl>


<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#aba546a206fb7cfbc3cc5fd95a832a653">tcSubtract</a>.</p>

</div>
</div>

### operator-= {#a15edd02fb043f45d425b99ff92e7c4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator-= (uint64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a97a57add297988a66a8d6a81eff19cbb">tcSubtractPart</a> and <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a>.</p>

</div>
</div>

### operator\*= {#ab7984341f7e873ae3619874ae89c3afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator*= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiplication assignment operator.</p>


<p>Multiplies this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by RHS and assigns the result to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this</p></dd>
</dl>


<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### operator\*= {#aed0fa6f38807df2e9ff7f643de4f42d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator*= (uint64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#aaf3bfaa5ac3f017c8d3b7336d8bd4678">tcMultiplyPart</a>.</p>

</div>
</div>

### operator&amp;= {#a38c8efc9c8dd13e8cdc39109283552a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Bitwise AND assignment operator.</p>


<p>Performs a bitwise AND operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS. The result is assigned to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after ANDing with RHS.</p></dd>
</dl>


<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&amp;= {#ae4ebaecf630dbd7f04d1c3f9d9cfbad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator&amp;= (uint64_t RHS)</td>
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

<p>Bitwise AND assignment operator.</p>


<p>Performs a bitwise AND operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS. RHS is logically zero-extended or truncated to match the bit-width of the LHS.</p>


<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator^= {#ac605f0a460fdb9a65dd94d2eaa0722f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Bitwise XOR assignment operator.</p>


<p>Performs a bitwise XOR operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS. The result is assigned to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after XORing with RHS.</p></dd>
</dl>


<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator^= {#a4627e5f0560b9d5f40fb309ea263de9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator^= (uint64_t RHS)</td>
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

<p>Bitwise XOR assignment operator.</p>


<p>Performs a bitwise XOR operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS. RHS is logically zero-extended or truncated to match the bit-width of the LHS.</p>


<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+= {#ad550e9403dfe9c20c6b8adb6acb25180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Addition assignment operator.</p>


<p>Adds the RHS <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Adds RHS to *this and assigns the result to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>this, after addition of RHS. Addition assignment operator.</p></dd>
</dl>


<p>Declaration at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a25ca60b3924e39b65a173e2b55c6e92d">tcAdd</a>.</p>

</div>
</div>

### operator+= {#a30a2fd77599a3403f6a848952dd7f82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator+= (uint64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#ada4be5a4a886a268b42447b2c17eb59e">tcAddPart</a> and <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a>.</p>

</div>
</div>

### operator&lt;&lt;= {#a6f57dd5ed73b3c76a3d208bb1a67228a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator&lt;&lt;= (unsigned ShiftAmt)</td>
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

<p>Left-shift assignment function.</p>


<p>Shifts *this left by shiftAmt and assigns the result to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after shifting left by ShiftAmt</p></dd>
</dl>


<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>

</div>
</div>

### operator&lt;&lt;= {#af66c0b07cc393cb3aa9123c5d9cbfe4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; APInt::operator&lt;&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; shiftAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Left-shift assignment function.</p>


<p>Left-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Shifts *this left by shiftAmt and assigns the result to *this.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after shifting left by ShiftAmt</p></dd>
</dl>


<p>Left-shift function.</p>


<p>Declaration at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a>.</p>

</div>
</div>

### operator= {#a3c3ff3a632850951cea84d8c6466890b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Copy assignment operator.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after assignment of RHS.</p></dd>
</dl>


<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apsint/#a09a4b7b345463fcac3ee2a8964556e9e">llvm::APSInt::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#aed5f1c10e937b8fccfbb846736c0d1f3">llvm::APSInt::operator=</a>.</p>

</div>
</div>

### operator= {#ac425969d2fbffcdd54e3ab18b35c680e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator= (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;&amp; that)</td>
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

<p>Move assignment operator.</p>

<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>

</div>
</div>

### operator= {#a5706001980ca4d8b32c73ca742bcc4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator= (uint64_t RHS)</td>
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

<p>Assignment operator.</p>


<p>The RHS value is assigned to *this. If the significant bits in RHS exceed the bit width, the excess bits are truncated. If the bit width is larger than 64, the value is zero filled in the unspecified high order bits.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after assignment of RHS value.</p></dd>
</dl>


<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|= {#a5ea5541c90a06aae894eb1e99ba2d579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Bitwise OR assignment operator.</p>


<p>Performs a bitwise OR operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS. The result is assigned *this;</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>*this after ORing with RHS.</p></dd>
</dl>


<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|= {#a4a10e817a053d9ec8b63fc11a061f41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt &amp; llvm::APInt::operator|= (uint64_t RHS)</td>
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

<p>Bitwise OR assignment operator.</p>


<p>Performs a bitwise OR operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS. RHS is logically zero-extended or truncated to match the bit-width of the LHS.</p>


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Binary Operators

### ashr {#ab6006923d1a3139d70abc8f6552a7960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::ashr (unsigned ShiftAmt)</td>
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

<p>Arithmetic right-shift function.</p>


<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aabcad8746eb26dcbb5831974e39a3d34">llvm::ConstantRange::ashr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ae7767cf650405a9ff3d68ae59a76c15d">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a1cecee4f08f337680e2dc415f17f2ab3">llvm::AArch64TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a1dd09091b53437ee541090716cbb4a4b">llvm::X86TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a392b6c8a7962feed988bf14017205f4b">llvm::RISCVMatInt::getIntMatCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a19b21f58b23210aaa6dbe1ed62c330a3">llvm::APSInt::operator&gt;&gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="#a57604a130a7bf75be0295a8ba37ff4fe">relativeAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac56427a25d7626e4b748e8fbf1fdf9bb">llvm::Interpreter::visitAShr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

</div>
</div>

### ashr {#a61c2c3c3344946ca0d70b0da418b52e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::ashr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ShiftAmt)</td>
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

<p>Arithmetic right-shift function.</p>


<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### ashrInPlace {#a7e30b3aa214eba50eed018b5b19fc6aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::ashrInPlace (unsigned ShiftAmt)</td>
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

<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by ShiftAmt in place.</p>

<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1f1be83c0efdaff4af051b7a45faaba7">llvm::KnownBits::ashr</a>, <a href="#a79a42db75a127dc89f3962474caf145c">ashrInPlace</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af5d3388e53cb2767927dba7c18c64a00">llvm::CombinerHelper::buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#acaba218d0b8ff3581f4fbddb8c68ab4d">llvm::APSInt::operator&gt;&gt;=</a>.</p>

</div>
</div>

### ashrInPlace {#a79a42db75a127dc89f3962474caf145c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::ashrInPlace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; shiftAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt in place.</p>


<p>Arithmetic right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Arithmetic right-shift function.</p>


<p>Declaration at line 915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a7e30b3aa214eba50eed018b5b19fc6aa">ashrInPlace</a> and <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a>.</p>

</div>
</div>

### concat {#a6bc2ad05ce14ae805c176fc8abfbe0a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::concat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; NewLSB)</td>
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

<p>Concatenate the bits from "NewLSB" onto the bottom of *this.</p>


<p>This is equivalent to: (this-&gt;zext(NewWidth) &lt;&lt; NewLSB.getBitWidth()) | NewLSB.zext(NewWidth)</p>


<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> and <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a>.</p>

</div>
</div>

### lshr {#af34549c39d6f741fbdaf9a795aa306e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::lshr (unsigned shiftAmt)</td>
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

<p>Logical right-shift function.</p>


<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4bef95512fa985102be74adbdb966f80">areUsedBitsDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ae7767cf650405a9ff3d68ae59a76c15d">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aefdb6cdad27dd579e957c1b68f87847c">foldICmpWithTruncSignExtendedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="#a2d5c4385716b3fa4a96e879987cccedc">getHiBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4836b23626e1d7b24f8bb84be3a55667">getHopForBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#ac2c46c98ef08efa11fd207209dabba62">llvm::BlockFrequencyInfoImplBase::getProfileCountFromFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a020e15d458158f9576cddf71923093dd">lowerMSABinaryBitImmIntr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a452f6ecfc69e273b9005e5bac75583a3">llvm::ConstantRange::lshr</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a19b21f58b23210aaa6dbe1ed62c330a3">llvm::APSInt::operator&gt;&gt;</a>, <a href="#a1aeae6359e573a57ce8db93b8b26b19a">relativeLShr</a>, <a href="#aa548cc4a0fd9e7c713b180f7780655e2">rotl</a>, <a href="#a7add4efc2976e2d2b52a1e5d427ce616">rotr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a7da80f756644226c925de9aa4bf77d94">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a39600b19581391dccc382a54d6b79be2">llvm::Interpreter::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### lshr {#a98d705ad0b507dd7c488017c2ad5c8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::lshr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ShiftAmt)</td>
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

<p>Logical right-shift function.</p>


<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### lshrInPlace {#af338e23a90c301183968435e80cd6a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::lshrInPlace (unsigned ShiftAmt)</td>
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

<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by ShiftAmt in place.</p>

<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a27302ae9df3143ece2fcd550d6ac9adc">checkSignTestSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af8918ba9c2bab47454cfbe9bb8942871">emitGlobalConstantLargeInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a8e67baf5aacf7f9fa94cbb5d66880700">getUsefulBitsFromBitfieldMoveOpd</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="#aa56f74cc18a1ce46c252a0280a2fa1d2">lshrInPlace</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#acaba218d0b8ff3581f4fbddb8c68ab4d">llvm::APSInt::operator&gt;&gt;=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="#a7b8b4253b618610eb5cb497b4104ebc3">reverseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a76616979b7159a14d6afcb13c0106326">simplifyX86vpermilvar</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### lshrInPlace {#aa56f74cc18a1ce46c252a0280a2fa1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::lshrInPlace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; shiftAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by ShiftAmt in place.</p>


<p>Logical right-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Logical right-shift function.</p>


<p>Declaration at line 927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a> and <a href="#af338e23a90c301183968435e80cd6a27">lshrInPlace</a>.</p>

</div>
</div>

### operator\[\] {#a34ac00f7e03b4472cc7efc04c4818bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::operator[] (unsigned bitPosition)</td>
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

<p>Array-indexing support.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the bit value at bitPosition</p></dd>
</dl>


<p>Definition at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>.</p>

</div>
</div>

### operator\* {#a8affacda773b55e259f6dc4da77d948a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::operator* (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiplication operator.</p>


<p>Multiplies this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by RHS and returns the result.</p>


<p>Declaration at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#ae9eab7a6f6e43c3a48731017dd24e746">getMemory</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#ab153d6d2370c0c5526009aaa07cc00e1">tcMultiply</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a2e24bc7f50e82dee742541ad86b449c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::operator&lt;&lt; (unsigned Bits)</td>
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

<p>Left logical shift operator.</p>


<p>Shifts this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> left by <span class="doxyComputerOutput">Bits</span> and returns the result.</p>


<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a28bc2404b2316a5e4b6ff9113ba270ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Bits)</td>
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

<p>Left logical shift operator.</p>


<p>Shifts this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> left by <span class="doxyComputerOutput">Bits</span> and returns the result.</p>


<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>.</p>

</div>
</div>

### relativeAShl {#a793e27a4e7b6ec5ecab8e7616e0d4ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::relativeAShl (int RelativeShift)</td>
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

<p>relative arithmetic shift left</p>

<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a57604a130a7bf75be0295a8ba37ff4fe">relativeAShr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa9bfb82b935461edaeaff0a95e39d929">llvm::APSInt::relativeShl</a>.</p>

</div>
</div>

### relativeAShr {#a57604a130a7bf75be0295a8ba37ff4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::relativeAShr (int RelativeShift)</td>
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

<p>relative arithmetic shift right</p>

<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#ab6006923d1a3139d70abc8f6552a7960">ashr</a> and <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>.</p>


<p>Referenced by <a href="#a793e27a4e7b6ec5ecab8e7616e0d4ac0">relativeAShl</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#a4397926a41cfe940d5f071bb707b8aeb">llvm::APSInt::relativeShr</a>.</p>

</div>
</div>

### relativeLShl {#a3bbf73dc4411a52b8d03e582a09893ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::relativeLShl (int RelativeShift)</td>
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

<p>relative logical shift left</p>

<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a1aeae6359e573a57ce8db93b8b26b19a">relativeLShr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa9bfb82b935461edaeaff0a95e39d929">llvm::APSInt::relativeShl</a>.</p>

</div>
</div>

### relativeLShr {#a1aeae6359e573a57ce8db93b8b26b19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::relativeLShr (int RelativeShift)</td>
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

<p>relative logical shift right</p>

<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a> and <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>.</p>


<p>Referenced by <a href="#a3bbf73dc4411a52b8d03e582a09893ce">relativeLShl</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#a4397926a41cfe940d5f071bb707b8aeb">llvm::APSInt::relativeShr</a>.</p>

</div>
</div>

### rotl {#aa548cc4a0fd9e7c713b180f7780655e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::rotl (unsigned rotateAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rotate left by rotateAmt.</p>

<p>Declaration at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a> and <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="#a841147c648072358e88b0d0a50359ebe">isSplat</a> and <a href="#a65bc3d32a3f55045259fda31d9fffb28">rotl</a>.</p>

</div>
</div>

### rotl {#a65bc3d32a3f55045259fda31d9fffb28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::rotl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; rotateAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rotate left by rotateAmt.</p>

<p>Declaration at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a> and <a href="#aa548cc4a0fd9e7c713b180f7780655e2">rotl</a>.</p>

</div>
</div>

### rotr {#a7add4efc2976e2d2b52a1e5d427ce616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::rotr (unsigned rotateAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rotate right by rotateAmt.</p>

<p>Declaration at line 903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a> and <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="#acc8a2eb3a9949f9e26c2724ef3a109cd">rotr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#adb196c969d6d3af8de3eeeddf2bb9303">selectI64ImmDirect</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#ac75a07531324f76bfb02992249135cfb">selectI64ImmDirectPrefix</a>.</p>

</div>
</div>

### rotr {#acc8a2eb3a9949f9e26c2724ef3a109cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::rotr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; rotateAmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rotate right by rotateAmt.</p>

<p>Declaration at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a> and <a href="#a7add4efc2976e2d2b52a1e5d427ce616">rotr</a>.</p>

</div>
</div>

### sadd\_ov {#a694293446a074c3d64270e7671bb5052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sadd_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1902 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad69d1c99b0af08146faf9bdf2d9c8709">llvm::APFixedPoint::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a21d115d23f25fa3a2eabb1acaac67444">addWithOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace6abb6601b1a223dd202fa7f346ea68">llvm::checkedAdd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37d041863780218ea6838646ba00b29c">llvm::exprAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#af93581c21ffd5eccbb745274f226dbe7">maintainNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#afbe3b990798e79cc464f39472699112b">llvm::detail::SlowDynamicAPInt::operator+</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a758290c5743d18768a64d96539070fd1">optimizeIncrementingWhile</a>, <a href="#a3c1e0381aeb551ad0ba58effe9232f97">sadd_sat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f380ccafb36b01f687b5507c39d3c6e">llvm::simplifyLoopAfterUnroll</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### sadd\_sat {#a3c1e0381aeb551ad0ba58effe9232f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sadd_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2000 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a694293446a074c3d64270e7671bb5052">sadd_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad69d1c99b0af08146faf9bdf2d9c8709">llvm::APFixedPoint::add</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a54097522b509c08dd84e5ce59437c8b9">llvm::ConstantRange::sadd_sat</a>.</p>

</div>
</div>

### sdiv {#a71f7f6e3a4774296efc7274196a74793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sdiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Signed division function for <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Signed divide this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> RHS.</p>


<p>The result is rounded towards zero.</p>


<p>Declaration at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a0cf99f7dc09e330137cb10a3a42c12b3">llvm::ProfileSummaryBuilder::computeDetailedSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3932d8d07bd52eacf62adc249ac2f926">findGCD</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abf938d888e2a13a56e6fc0b3017bb4dd">isSimpleVIDSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aec0317ddb04fa2f763dd5e3a5c38a914">llvm::APSInt::operator/</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a4d18c5db1edd957046c553be317939ff">llvm::APSInt::operator/=</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa160a2ac0c31b48c41da949e53cc21b7">llvm::ConstantRange::sdiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="#a889c63e93f521abb41e0736a3f42cf02">sdiv_ov</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="#ac155d7c568fc1aba25723e77b6888908">smul_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### sdiv {#a81219309bccc36e3a7c38f7f5c21de8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sdiv (int64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1629 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>.</p>

</div>
</div>

### sdiv\_ov {#a889c63e93f521abb41e0736a3f42cf02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sdiv_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1928 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a1f04e382556a817950fd0390aeaf9b0e">isMinSignedValue</a> and <a href="#a71f7f6e3a4774296efc7274196a74793">sdiv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#add0f77cf0080542aad1132fff681ef7c">llvm::exprDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a9284a4735992c0b86c3827ecbd0d0861">llvm::detail::SlowDynamicAPInt::operator/</a> and <a href="#a5af05771dc4f41f73f052c66836657bc">sfloordiv_ov</a>.</p>

</div>
</div>

### sdivrem {#a24187c2e178af0df22dac26cd5229294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::sdivrem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Quotient, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Remainder)</td>
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



<p>Declaration at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1864 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a8376734f311508662dd7e737752e5953">negate</a> and <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a4ab89a5befb6167f9c5929f544d969eb">ceilingOfQuotient</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3932d8d07bd52eacf62adc249ac2f926">findGCD</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a4cd9a82adab8deb6708cc554dd074499">floorOfQuotient</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a59d1e0778623481e8a1599800d892946">llvm::APIntOps::RoundingSDiv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab9e94d7f7d74b11670e87904ed30dc2a">llvm::APIntOps::SolveQuadraticEquationWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ad7c510ac5f19ce17fd2b5b06d15a7aa3">llvm::SCEVDivision::visitConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>.</p>

</div>
</div>

### sdivrem {#a76e54fadf3b01da96aaa66c35ed8c366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::sdivrem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHS, int64_t RHS, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Quotient, int64_t &amp; Remainder)</td>
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



<p>Declaration at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1882 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a8376734f311508662dd7e737752e5953">negate</a> and <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>.</p>

</div>
</div>

### sfloordiv\_ov {#a5af05771dc4f41f73f052c66836657bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sfloordiv_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Signed integer floor division operation.</p>


<p>Rounds towards negative infinity, i.e. 5 / -2 = -3. Iff minimum value divided by -1 set Overflow to true.</p>


<p>Declaration at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1993 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a889c63e93f521abb41e0736a3f42cf02">sdiv_ov</a>.</p>

</div>
</div>

### shl {#acb9c55b6986369948507ca5241b4e411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::shl (unsigned shiftAmt)</td>
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

<p>Left-shift function.</p>


<p>Left-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3bbea4eec70051ce3e57b94badc624a2">convertShiftLeftToScale</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ae7767cf650405a9ff3d68ae59a76c15d">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a47a83bda096455c177d40a2fbae13de1">llvm::InstCombinerImpl::foldICmpShlConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aefdb6cdad27dd579e957c1b68f87847c">foldICmpWithTruncSignExtendedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5b5001e37af42df3e8202151fe08b3c9">llvm::CombinerHelper::matchShlOfVScale</a>, <a href="#a28bc2404b2316a5e4b6ff9113ba270ab">operator&lt;&lt;</a>, <a href="#a2e24bc7f50e82dee742541ad86b449c6">operator&lt;&lt;</a>, <a href="#a57604a130a7bf75be0295a8ba37ff4fe">relativeAShr</a>, <a href="#a1aeae6359e573a57ce8db93b8b26b19a">relativeLShr</a>, <a href="#aa548cc4a0fd9e7c713b180f7780655e2">rotl</a>, <a href="#a7add4efc2976e2d2b52a1e5d427ce616">rotr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#adaccb8a2292bd0d7fecec1c16d177cd3">llvm::Interpreter::visitShl</a>.</p>

</div>
</div>

### shl {#a8f1d88206e3ce5514de646f23f0042bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::shl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ShiftAmt)</td>
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

<p>Left-shift function.</p>


<p>Left-shift this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by shiftAmt.</p>


<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>

</div>
</div>

### smul\_ov {#ac155d7c568fc1aba25723e77b6888908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::smul_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1934 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a1f04e382556a817950fd0390aeaf9b0e">isMinSignedValue</a> and <a href="#a71f7f6e3a4774296efc7274196a74793">sdiv</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a4ef0843f4b374aae185be929453c9de5">llvm::GEPOperator::accumulateConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2f90ac4998c6dd05ecab62f8e14ef7f">llvm::checkedMul</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8258dddc7601318d4c35d8ff2523d466">llvm::exprMul</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#af93581c21ffd5eccbb745274f226dbe7">maintainNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a6fbd158fde32fbde0dcaf3ca5a06efaa">multiplyOverflows</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b1f18c3a2433393b6a48cffa8651773">MulWillOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a0fc607373675fde318c740e7bc810ff9">llvm::detail::SlowDynamicAPInt::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a3a4758c17c35cfcd1f67a4a119a95ee0">llvm::ConstantRange::smul_fast</a>, <a href="#a36f62de4b8b82d2f73fb4efda79954f0">smul_sat</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>.</p>

</div>
</div>

### smul\_sat {#a36f62de4b8b82d2f73fb4efda79954f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::smul_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2038 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#ac155d7c568fc1aba25723e77b6888908">smul_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5c68869b0c18ead32284ec3b461bcbf7">llvm::ConstantRange::smul_sat</a>.</p>

</div>
</div>

### srem {#ac131d830427393332e440e1d6e3013b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::srem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> for signed remainder operation.</p>


<p>Signed remainder operation on <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Note that this is a true remainder operation and not a modulo operation because the sign follows the sign of the dividend which is *this.</p>


<p>Declaration at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1710 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3932d8d07bd52eacf62adc249ac2f926">findGCD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac1fce2baaba15c35a2bb18563ef08678">getStrideAndModOffsetOfGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a94c9d9a24e2274adeef93424e27005d3">isRemainderZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abf938d888e2a13a56e6fc0b3017bb4dd">isSimpleVIDSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa20e09844a71113a5fe9b80dae48a219">llvm::APSInt::operator%</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa3073cdacf70e2530fde9c67be4bdaac">llvm::APSInt::operator%=</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2c78ae45454d731f51f0ce021a729816">simplifyRelativeLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### srem {#aeee93929dbd2133737e30498d6e12fed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t APInt::srem (int64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>.</p>

</div>
</div>

### sshl\_ov {#a36e003ab14cb859152427b64b665e691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sshl_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Amt, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1962 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a>, <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a> and <a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a>, <a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a> and <a href="#ab3ed902943113e485a80dff901f36494">sshl_sat</a>.</p>

</div>
</div>

### sshl\_ov {#a89f4c6b6aa9f918f4586a08d399fd1d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sshl_ov (unsigned Amt, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1966 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a>, <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> and <a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a>.</p>

</div>
</div>

### sshl\_sat {#a90e6be77d59fee53e8585874cd1ab07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sshl_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> and <a href="#a90e6be77d59fee53e8585874cd1ab07c">sshl_sat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="#a90e6be77d59fee53e8585874cd1ab07c">sshl_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a36128583fce0d74508c8dc73e56ee905">llvm::ConstantRange::sshl_sat</a>.</p>

</div>
</div>

### sshl\_sat {#ab3ed902943113e485a80dff901f36494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sshl_sat (unsigned RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2064 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a>.</p>

</div>
</div>

### ssub\_ov {#ae324de5041feaf7eb8433221cdaca9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::ssub_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1915 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#ac8c0157adbe12649beac0009c2f6ad8d">isNonNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7504b68f8f57dbbc0f72d060d6a0e12">llvm::checkedSub</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec89740de6547eaefa607d86390e8851">llvm::exprSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#af93581c21ffd5eccbb745274f226dbe7">maintainNoSignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a4cca0dd3879ab0be07e4cfa6d60d90fb">moveAddAfterMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint/#a0a7d474fe2bca892a50861086e90cf07">llvm::detail::SlowDynamicAPInt::operator-</a>, <a href="#af888cb3cadd9a4e5f422c96e5674de88">ssub_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6d9ba22fe2a57b958ba00d8b3382fffd">llvm::APFixedPoint::sub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9ca0d2b442af6eec7e00bb32d14d44b7">subWithOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### ssub\_sat {#af888cb3cadd9a4e5f422c96e5674de88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::ssub_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2019 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="#ae324de5041feaf7eb8433221cdaca9aa">ssub_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a993a75b630274a45cb0c20938962796f">llvm::ConstantRange::ssub_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6d9ba22fe2a57b958ba00d8b3382fffd">llvm::APFixedPoint::sub</a>.</p>

</div>
</div>

### uadd\_ov {#a8268fbc3014081004056f6466452c904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::uadd_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1909 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad69d1c99b0af08146faf9bdf2d9c8709">llvm::APFixedPoint::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a21d115d23f25fa3a2eabb1acaac67444">addWithOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abbaf47f00a219967b0a3d6bef5906609">llvm::checkedAddUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a758290c5743d18768a64d96539070fd1">optimizeIncrementingWhile</a>, <a href="#ab4c04665274d4f30d732639dc055821c">uadd_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### uadd\_sat {#ab4c04665274d4f30d732639dc055821c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::uadd_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2010 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a> and <a href="#a8268fbc3014081004056f6466452c904">uadd_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad69d1c99b0af08146faf9bdf2d9c8709">llvm::APFixedPoint::add</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a81da9170db4b7b8f89c9d196c07a6efb">llvm::ConstantRange::uadd_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### udiv {#a05d674becc60ba4ef8cd4dd4d38ac27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::udiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unsigned division operation.</p>


<p>Perform an unsigned divide operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> by RHS. Both this and RHS are treated as unsigned quantities for purposes of this division.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a new <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value containing the division result, rounded towards zero.</p></dd>
</dl>


<p>Declaration at line 962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1547 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a015653deceadd540a1e4fc871a1a21ea">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a4d5937fb63dff47c2112c8032650019b">calculateGEPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9175bf0e4b0c3a18e2f86bb11270ee78">llvm::InstCombinerImpl::foldICmpUDivConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#ac2c46c98ef08efa11fd207209dabba62">llvm::BlockFrequencyInfoImplBase::getProfileCountFromFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aec0317ddb04fa2f763dd5e3a5c38a914">llvm::APSInt::operator/</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a4d18c5db1edd957046c553be317939ff">llvm::APSInt::operator/=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>, <a href="#a71f7f6e3a4774296efc7274196a74793">sdiv</a>, <a href="#a81219309bccc36e3a7c38f7f5c21de8a">sdiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab9e94d7f7d74b11670e87904ed30dc2a">llvm::APIntOps::SolveQuadraticEquationWrap</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad41d307fed42f6776d36397336e81985">llvm::ConstantRange::udiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a96120d4062fabb503b1b92401e54d14f">llvm::KnownBits::udiv</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### udiv {#af21fe5092047a14fb320f82d99276b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::udiv (uint64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>

</div>
</div>

### udivrem {#a0f0a665210e453bb16b4bf1861dbdd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::udivrem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Quotient, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Remainder)</td>
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

<p>Dual division/remainder interface.</p>


<p>Sometimes it is convenient to divide two <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> values and obtain both the quotient and remainder. This function does both operations in the same computation making it a little more efficient. The pair of input arguments may overlap with the pair of output arguments. It is safe to call udivrem(X, Y, X, Y), for example.</p>


<p>Declaration at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#a8f3e4fda4ce5ab01260df66b88ebabd3">GEPToVectorIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a1c533fb6a26fce38d9cec2b51a7a90b0">llvm::APIntOps::RoundingUDiv</a>, <a href="#a24187c2e178af0df22dac26cd5229294">sdivrem</a>, <a href="#a76e54fadf3b01da96aaa66c35ed8c366">sdivrem</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>.</p>

</div>
</div>

### udivrem {#a8bd2f21c3219cdb1c83f080dc7e1fc31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::udivrem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHS, uint64_t RHS, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Quotient, uint64_t &amp; Remainder)</td>
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



<p>Declaration at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1803 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a>.</p>

</div>
</div>

### umul\_ov {#a028f4d1eead63cc33499ce3459bd27c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::umul_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1945 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>, <a href="#af34549c39d6f741fbdaf9a795aa306e9">lshr</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a55fc80e21802a32962e170b06a030e27">llvm::checkedMulUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6c03d18ed744dc3b34829ec5485a68b0">llvm::ScalarEvolution::getUDivExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a6fbd158fde32fbde0dcaf3ca5a06efaa">multiplyOverflows</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b1f18c3a2433393b6a48cffa8651773">MulWillOverflow</a>, <a href="#acf4d36ebf88039604b73d3527506c3ed">umul_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a8ccba85d5176205f41ad55236b7d8204">llvm::ConstantRange::unsignedMulMayOverflow</a>.</p>

</div>
</div>

### umul\_sat {#acf4d36ebf88039604b73d3527506c3ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::umul_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2051 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a> and <a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a19eb872c58979381c922e31a1344e0f0">llvm::ConstantRange::umul_sat</a>.</p>

</div>
</div>

### urem {#a4e3a2187cacdec76028617a403c47d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::urem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unsigned remainder operation.</p>


<p>Perform an unsigned remainder operation on this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with RHS being the divisor. Both this and RHS are treated as unsigned quantities for purposes of this operation.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a new <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value containing the remainder result</p></dd>
</dl>


<p>Declaration at line 980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1640 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6766b5f9c46b6dd7bb3b45857ec23a0f">llvm::CombinerHelper::applyFunnelShiftConstantModulo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6c03d18ed744dc3b34829ec5485a68b0">llvm::ScalarEvolution::getUDivExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0109582eb646d501101a7e6a059814fb">isLoadCombineCandidateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aced5d43b6a199d148e877d5536e95739">isNonZeroModBitWidthOrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1278833d086e5f200fcc7e576d2efa17">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4871d6290298d9eaae5b5da0160e5a21">LowerRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa20e09844a71113a5fe9b80dae48a219">llvm::APSInt::operator%</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#aa3073cdacf70e2530fde9c67be4bdaac">llvm::APSInt::operator%=</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="#ac131d830427393332e440e1d6e3013b6">srem</a>, <a href="#aeee93929dbd2133737e30498d6e12fed">srem</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff82c03c1ce8b945170bcb1f0f624c17">llvm::ScalarEvolution::verify</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>.</p>

</div>
</div>

### urem {#a825a8dca80ee195760b908990de1a7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t APInt::urem (uint64_t RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>

</div>
</div>

### ushl\_ov {#a97419fdddc400a50c7c40ef5c35903cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::ushl_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Amt, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1979 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a>, <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a> and <a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a618caf6a690e2208acbfa1b7668df3a2">computeShlNUW</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a>, <a href="#a236aa749101900bc9e8e6cd108bdec6a">ushl_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a>.</p>

</div>
</div>

### ushl\_ov {#ac8345a3be974d824185f13fc5c196393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::ushl_ov (unsigned Amt, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a> and <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a>.</p>

</div>
</div>

### ushl\_sat {#a9458a57a572f29dd261a3be65cd8ee9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::ushl_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2074 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a> and <a href="#a9458a57a572f29dd261a3be65cd8ee9f">ushl_sat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="#a9458a57a572f29dd261a3be65cd8ee9f">ushl_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a554ba11140af2b294a7e46761dfa7865">llvm::ConstantRange::ushl_sat</a>.</p>

</div>
</div>

### ushl\_sat {#a236aa749101900bc9e8e6cd108bdec6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::ushl_sat (unsigned RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2078 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a> and <a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a>.</p>

</div>
</div>

### usub\_ov {#a44d622af4cca05108d8d7eb9bfd79977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::usub_ov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, bool &amp; Overflow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1922 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">ugt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a4cca0dd3879ab0be07e4cfa6d60d90fb">moveAddAfterMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6d9ba22fe2a57b958ba00d8b3382fffd">llvm::APFixedPoint::sub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9ca0d2b442af6eec7e00bb32d14d44b7">subWithOverflow</a>, <a href="#a059dc64e71df065315050d2270cbfba5">usub_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### usub\_sat {#a059dc64e71df065315050d2270cbfba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::usub_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2029 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a44d622af4cca05108d8d7eb9bfd79977">usub_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6d9ba22fe2a57b958ba00d8b3382fffd">llvm::APFixedPoint::sub</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a7a13c7e552038eb1d567e1572d91c411">llvm::ConstantRange::usub_sat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Comparison Operators

### eq {#a6e17f9e532ca4a61804f28091b10b522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::eq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Equality comparison.</p>


<p>Compares this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with RHS for the validity of the equality relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this == Val</p></dd>
</dl>


<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7fe8accb4198eb111067fe7c4bb544dd">llvm::omp::getBestVariantMatchForContext</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a1457368e287459e33ec3f528553a94e0">llvm::APSInt::operator==</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>.</p>

</div>
</div>

### intersects {#a6da514c588b2668280a861a59bfc9fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::intersects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>This operation tests if there are any pairs of corresponding bits between this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> and RHS that are both set.</p>

<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#acc600a6141b4b54703a4ead9c72a3012">bitTrackingDCE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad00ef9b94ff672e7a3ef2a0cae24b757">combineBlendOfPermutes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a905d2324c26b7a6f5aeb929a734ce0bc">llvm::KnownBits::srem</a>.</p>

</div>
</div>

### isSubsetOf {#acfae9bdee6027ffa8ffe244cc22e3a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::isSubsetOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>This operation checks that all bits set in this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> are also set in RHS.</p>

<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#acc600a6141b4b54703a4ead9c72a3012">bitTrackingDCE</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a9dcbd38183e29746d52bb60bdcd611ba">llvm::SelectionDAGISel::CheckAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a088862cded43bb2202369f9346535d3a">llvm::SelectionDAGISel::CheckOrMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a39257c6c73db3440e6d05b9eec5999a0">getMaskedICmpType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a093fa508bcdccd1b9172fc87797c8cd6">llvm::SelectionDAG::getSplatSourceVector</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3b5afe10336a33630e00f86fab07c87">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a3cb4731330867b7a71460d3f4daa752e">performORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a36d1b77a885effd5cefdd787a7935226">llvm::LoongArchDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af619c526b5e90968d76fbd4fe4c861cb">llvm::RISCVDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a655de0b9ba51c463a01a23651abb0cf7">llvm::ARMTargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a905d2324c26b7a6f5aeb929a734ce0bc">llvm::KnownBits::srem</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a39ed92e826ef5d0893f72b26fab78aa3">llvm::RISCVTargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### ne {#ad53de8dfd63f774033284907674f79ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Inequality comparison.</p>


<p>Compares this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with RHS for the validity of the inequality relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this != Val</p></dd>
</dl>


<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!= {#a3509642df002d9bc4e089eff3a6eedcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Inequality operator.</p>


<p>Compares this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with RHS for the validity of the inequality relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this != Val</p></dd>
</dl>


<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!= {#afe8fe1bb967080f5d6ba2e253e7337c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::operator!= (uint64_t Val)</td>
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

<p>Inequality operator.</p>


<p>Compares this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with a uint64_t for the validity of the inequality relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this != Val</p></dd>
</dl>


<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>

</div>
</div>

### operator== {#a8eeb6b0ef83a291455cb52d6e0a5a612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Equality operator.</p>


<p>Compares this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with RHS for the validity of the equality relationship.</p>


<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator== {#a5f74c7368cdc65e9e942faca9976d080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::operator== (uint64_t Val)</td>
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

<p>Equality operator.</p>


<p>Compares this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with a uint64_t for the validity of the equality relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this == Val</p></dd>
</dl>


<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>

</div>
</div>

### sge {#ae2b7d8c018c8a37fa8ea422a13bfd412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::sge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Signed greater or equal comparison.</p>


<p>Regards both *this and RHS as signed quantities and compares them for validity of the greater-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt;= RHS when both are considered signed.</p></dd>
</dl>


<p>Definition at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#adafa9575780f9246d1df0b7e2a619356">slt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a83c08f911e04d76c1e01900fcfcf2a35">llvm::APSInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa8d333c2eb8d0346da6128f38cf941b5">TryMULWIDECombine</a>.</p>

</div>
</div>

### sge {#ac0c66c2a2456cbc331f206ac64491488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::sge (int64_t RHS)</td>
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

<p>Signed greater or equal comparison.</p>


<p>Regards both *this as a signed quantity and compares it with RHS for the validity of the greater-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt;= RHS when considered signed.</p></dd>
</dl>


<p>Definition at line 1245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#adafa9575780f9246d1df0b7e2a619356">slt</a>.</p>

</div>
</div>

### sgt {#a3d430216d32f4363e4df154599b98055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::sgt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Signed greater than comparison.</p>


<p>Regards both *this and RHS as signed quantities and compares them for the validity of the greater-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt; RHS when both are considered signed.</p></dd>
</dl>


<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a7e8226e6453c8bcf7e5c06d28b1e207b">sle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3d58d84dc2b521514bc59c7a9f609260">canUseSExt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aa661c3b2e01f5ece0bc84908b98036be">anonymous{LowerSwitch.cpp}::Clusterify</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a57c818fa46b39f5b70d629087c58b38c">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getEstimatedNumberOfCaseClusters</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aae4b3f95626af4abcad7012a51272475">matchClamp</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a3f2bbb768bd4508be2080a7d99c16afb">llvm::APSInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a>, <a href="#a5342595638e399928d478bc84cad6b41">sle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab9e94d7f7d74b11670e87904ed30dc2a">llvm::APIntOps::SolveQuadraticEquationWrap</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>.</p>

</div>
</div>

### sgt {#a3291dd727de5786ef808475d8d9a1560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::sgt (int64_t RHS)</td>
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

<p>Signed greater than comparison.</p>


<p>Regards both *this as a signed quantity and compares it with RHS for the validity of the greater-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt; RHS when considered signed.</p></dd>
</dl>


<p>Definition at line 1209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a>, <a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### sle {#a7e8226e6453c8bcf7e5c06d28b1e207b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::sle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Signed less or equal comparison.</p>


<p>Regards both *this and RHS as signed quantities and compares them for validity of the less-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt;= RHS when both are considered signed.</p></dd>
</dl>


<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8133ee4dcc7f8903e9b582593c09bf28">isNonEqualPointersWithRecursiveGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/vectorizer/#af0c2e6c32b60d80acb3a91698e4981eb">anonymous{LoadStoreVectorizer.cpp}::Vectorizer::isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6a2d7b6d01962d7dff4c6e3e87f4575e">isSignedMinMaxClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a84d7df6718ccd749df4e7938b11eeb08">isSignedMinMaxIntrinsicClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a050b9d439487145d988a49cf9a6132fe">isTruePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ae8cf05c10c014362077a5f166ca0ccf6">llvm::APSInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="#a3d430216d32f4363e4df154599b98055">sgt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>.</p>

</div>
</div>

### sle {#a5342595638e399928d478bc84cad6b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::sle (uint64_t RHS)</td>
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

<p>Signed less or equal comparison.</p>


<p>Regards both *this as a signed quantity and compares it with RHS for the validity of the less-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt;= RHS when considered signed.</p></dd>
</dl>


<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a3d430216d32f4363e4df154599b98055">sgt</a>.</p>

</div>
</div>

### slt {#adafa9575780f9246d1df0b7e2a619356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::slt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Signed less than comparison.</p>


<p>Regards both *this and RHS as signed quantities and compares them for validity of the less-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt; RHS when both are considered signed.</p></dd>
</dl>


<p>Definition at line 1130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ae706b72bcadad3acf12a239b257aabc6">llvm::SwitchCG::SwitchLowering::buildJumpTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3d58d84dc2b521514bc59c7a9f609260">canUseSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#af0c949f0956bdd475184e8d934dc96e2">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPii</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfdc66e0c7cae85aec3cb94533f66dbc">llvm::exprMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3932d8d07bd52eacf62adc249ac2f926">findGCD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a4d34a6e13a44aa2f7c490762cbd3afb7">getBoundsCheckCond</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a57c818fa46b39f5b70d629087c58b38c">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getEstimatedNumberOfCaseClusters</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aac6e3a0dec40a6721857cbbd4330039f">llvm::MDNode::getMostGenericRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aae4b3f95626af4abcad7012a51272475">matchClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a3b7489b8af2a6ee6301615a5838a51ea">MinOptional</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowerswitch-cpp-/casecmp/#a490fb271b66667ac24839187579633de">anonymous{LowerSwitch.cpp}::CaseCmp::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a44f54987909b9918d96f059d09dd34bc">llvm::APSInt::operator&lt;</a>, <a href="#ae2b7d8c018c8a37fa8ea422a13bfd412">sge</a>, <a href="#ac0c66c2a2456cbc331f206ac64491488">sge</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a770339f0c1b1f2c1328c48f1f4291dfa">llvm::SwitchCG::sortAndRangeify</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a01b446184a324d46a818d1d6c15d114a">llvm::ConstantRangeList::subtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa8d333c2eb8d0346da6128f38cf941b5">TryMULWIDECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a86f75bbbe87c45fd3f9047fbad61671c">trySimplifyICmpWithAdds</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#ad16e6a0c972042439d77b4a665f69d9f">llvm::ConstantRangeList::unionWith</a>.</p>

</div>
</div>

### slt {#a0735ef8bd9cc0d99266fba0c6d7b5acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::slt (int64_t RHS)</td>
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

<p>Signed less than comparison.</p>


<p>Regards both *this as a signed quantity and compares it with RHS for the validity of the less-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt; RHS when considered signed.</p></dd>
</dl>


<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a>, <a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### uge {#af4b1ccc0b78f9da9f3f3944e06007f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::uge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Unsigned greater or equal comparison.</p>


<p>Regards both *this and RHS as unsigned quantities and compares them for validity of the greater-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt;= RHS when both are considered unsigned.</p></dd>
</dl>


<p>Definition at line 1221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac83bcada2a1e9fdfeb3a5215fff012da">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a7b6c32da7b6a47b962a5bdce5a3bbc75">canTryToConstantAddTwoShiftAmounts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa734719767b4f7faea1f7b40554f30be">llvm::X86TargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab27661a31d59b1d509386b1269369c62">detectUSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af06754acf6dbda0709a6cda0b11cdab5">Expand64BitShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebfb90f3ee1b2d4d5637e74d012424af">llvm::SelectionDAG::getValidShiftAmountRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae061deb7e1ce634d402090342aeccda7">LowerShiftByScalarImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4775da751f6b1e2123b23a54dabf51c9">matchAndOrChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a83c08f911e04d76c1e01900fcfcf2a35">llvm::APSInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3eefa98bc7f6c24b6f1fa0bb220a77a4">simplifyAndCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0614870543ce4ba5b6f9c7030d6867e2">simplifyLShrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8ff215a6e938a8df32c29c99bc126603">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenRightShift</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>.</p>

</div>
</div>

### uge {#a54ef77e140475145bce554cf37291292}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::uge (uint64_t RHS)</td>
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

<p>Unsigned greater or equal comparison.</p>


<p>Regards both *this as an unsigned quantity and compares it with RHS for the validity of the greater-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt;= RHS when considered unsigned.</p></dd>
</dl>


<p>Definition at line 1229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>

</div>
</div>

### ugt {#a46a7cbf3724080a5f4f4c7e7a4551e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ugt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Unsigned greater than comparison.</p>


<p>Regards both *this and RHS as unsigned quantities and compares them for the validity of the greater-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt; RHS when both are considered unsigned.</p></dd>
</dl>


<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#aca14d9ec64ba4ab7fb2cef37c57d9ce4">ule</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac83bcada2a1e9fdfeb3a5215fff012da">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aefdb6cdad27dd579e957c1b68f87847c">foldICmpWithTruncSignExtendedVal</a>, <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebfb90f3ee1b2d4d5637e74d012424af">llvm::SelectionDAG::getValidShiftAmountRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a688f2c4ca99eb7f935cab42c4f6398e7">llvm::ConstantRange::isSizeLargerThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aae4b3f95626af4abcad7012a51272475">matchClamp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ab7155d5feabf02f01c4d3b7d9c422">llvm::LegalizerHelper::narrowScalarShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a3f2bbb768bd4508be2080a7d99c16afb">llvm::APSInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a62222502f5be2dd8e300b48469aeab4f">llvm::ConstantRange::shl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af16b5429cba93f00c53d5d4627725516">simplifySetCCWithCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a51ae77be815f3771d7e0e1837204af01">llvm::ConstantRange::srem</a>, <a href="#ab15b44dcd79305e3dbef93b452dc57e3">ule</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bf71829dbcdadbd24d3c22814113ebf">llvm::ConstantRange::unsignedAddMayOverflow</a>, <a href="#a44d622af4cca05108d8d7eb9bfd79977">usub_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>.</p>

</div>
</div>

### ugt {#abfeca4698f01ef85e21a3e3061751781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ugt (uint64_t RHS)</td>
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

<p>Unsigned greater than comparison.</p>


<p>Regards both *this as an unsigned quantity and compares it with RHS for the validity of the greater-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &gt; RHS when considered unsigned.</p></dd>
</dl>


<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### ule {#aca14d9ec64ba4ab7fb2cef37c57d9ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Unsigned less or equal comparison.</p>


<p>Regards both *this and RHS as unsigned quantities and compares them for validity of the less-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt;= RHS when both are considered unsigned.</p></dd>
</dl>


<p>Definition at line 1150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#ad23ef87f642373984461ebbd5b100659">FoldValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac098fe4f07549fb029fbf950dbe78fd3">llvm::ConstantRange::intersectWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a050b9d439487145d988a49cf9a6132fe">isTruePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7662d7ee7f100c9455f4a2c7e4992929">matchIntPart</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ae8cf05c10c014362077a5f166ca0ccf6">llvm::APSInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a08d14454ee4850cd50dd4e1dbb48d19f">processAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a62222502f5be2dd8e300b48469aeab4f">llvm::ConstantRange::shl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">ugt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>.</p>

</div>
</div>

### ule {#ab15b44dcd79305e3dbef93b452dc57e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ule (uint64_t RHS)</td>
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

<p>Unsigned less or equal comparison.</p>


<p>Regards both *this as an unsigned quantity and compares it with RHS for the validity of the less-or-equal relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt;= RHS when considered unsigned.</p></dd>
</dl>


<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a46a7cbf3724080a5f4f4c7e7a4551e26">ugt</a>.</p>

</div>
</div>

### ult {#a545e8d5dfa1688acea0d0e275b03682f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS)</td>
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

<p>Unsigned less than comparison.</p>


<p>Regards both *this and RHS as unsigned quantities and compares them for the validity of the less-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt; RHS when both are considered unsigned.</p></dd>
</dl>


<p>Definition at line 1111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a89f5f0f536cc9b0bae261737f13786f7">cheapToScalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac8a8f784b3b05320fec4c962f5b4505b">llvm::SelectionDAG::computeOverflowForUnsignedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#af0c949f0956bdd475184e8d934dc96e2">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPii</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aefdb6cdad27dd579e957c1b68f87847c">foldICmpWithTruncSignExtendedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7fe8accb4198eb111067fe7c4bb544dd">llvm::omp::getBestVariantMatchForContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af17d33003beaf2d0bb09d7b2ac7984">llvm::SelectionDAG::getShiftAmountConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebfb90f3ee1b2d4d5637e74d012424af">llvm::SelectionDAG::getValidShiftAmountRange</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a53f1dcccf8991c637acec7883aba7bfc">llvm::ConstantRange::icmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac098fe4f07549fb029fbf950dbe78fd3">llvm::ConstantRange::intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aae4b3f95626af4abcad7012a51272475">matchClamp</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a44f54987909b9918d96f059d09dd34bc">llvm::APSInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a177f4d30b9356e0bc4a5dc176e825cb2">simplifyIRemMulShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>, <a href="#a8268fbc3014081004056f6466452c904">uadd_ov</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#af4b1ccc0b78f9da9f3f3944e06007f1d">uge</a>, <a href="#a54ef77e140475145bce554cf37291292">uge</a>, <a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa81521f99442a5c30f9061b8c6ce795e">llvm::ConstantRange::unionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a24a99adda34abba8c6988f8292a93815">llvm::ConstantRange::unsignedSubMayOverflow</a>, <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>, <a href="#a825a8dca80ee195760b908990de1a7af">urem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>.</p>

</div>
</div>

### ult {#afe03273b7efa986834cca7b9899a686b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APInt::ult (uint64_t RHS)</td>
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

<p>Unsigned less than comparison.</p>


<p>Regards both *this as an unsigned quantity and compares it with RHS for the validity of the less-than relationship.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if *this &lt; RHS when considered unsigned.</p></dd>
</dl>


<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Resizing Operators

### sext {#aca8fce65eb69a82aa10a635e2e79877a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sext (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sign extend to a new width.</p>


<p>This operation sign extends the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a new width. If the high order bit is set, the fill on the left will be done with 1 bits, otherwise zero. It is an error to specify a width that is less than the current width.</p>


<p>Declaration at line 1293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#ae9eab7a6f6e43c3a48731017dd24e746">getMemory</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aed133c19018de0508c5d71e802f36ef4">detectSSatSPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#ae881b7ad9c843880674599dbe5d85dd9">llvm::BinaryOperation::eval</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#af0c949f0956bdd475184e8d934dc96e2">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPii</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ab018e5f3273fdf77d6838c1bb037137a">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSEXTi</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ad62f39c993a3723a7b735652e1e14f57">llvm::APSInt::extend</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a3fb5a21e3d12a4f09da156333cdef568">anonymous{Utils.cpp}::getConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a469a3a48f9634f5d6b0e2855d05ca42d">llvm::APIntOps::mulhs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0309899567234d74bf87a3899207bc15">llvm::ConstantRange::multiply</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2caf0087e5ae1170754a8a4503df9a98">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#ac75a07531324f76bfb02992249135cfb">selectI64ImmDirectPrefix</a>, <a href="#a9b5fc98b47d44d1150d3610bdfab1430">sextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aa494dc35a29c6f78f26ea04679887f0d">llvm::APFixedPoint::shl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ad7c510ac5f19ce17fd2b5b06d15a7aa3">llvm::SCEVDivision::visitConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### sextOrTrunc {#a9b5fc98b47d44d1150d3610bdfab1430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sextOrTrunc (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sign extend or truncate to width.</p>


<p>Make this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> have the bit width given by <span class="doxyComputerOutput">width</span>. The value is sign extended, truncated, or left alone to make it that width.</p>


<p>Declaration at line 1306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a> and <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aec8a5b489575aed066c15608ea3b9b81">anonymous{InlineCost.cpp}::CallAnalyzer::accumulateGEPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ptrusevisitorbase/#a64dcf542ea4428468c3250f5516eaad0">llvm::detail::PtrUseVisitorBase::adjustOffsetForGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a8e4ee2a70091fe36640fda28c69580c6">llvm::DIExpression::constantFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a655cabf7c0f1a0d1e8312338e86abb84">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a1cecee4f08f337680e2dc415f17f2ab3">llvm::AArch64TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a1dd09091b53437ee541090716cbb4a4b">llvm::X86TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a392b6c8a7962feed988bf14017205f4b">llvm::RISCVMatInt::getIntMatCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac195e816d7e264cbe4b74b564fa26985">hasNearbyPairedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6fd6113581071d7d586e82cf3454bc9a">llvm::CombinerHelper::matchCombineConstPtrAddToI2P</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2c78ae45454d731f51f0ce021a729816">simplifyRelativeLoad</a>.</p>

</div>
</div>

### trunc {#a317c64fd4cfebc88e79387b3821a629d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::trunc (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Truncate to new width.</p>


<p>Truncate the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a specified width. It is an error to specify a width that is greater than the current width.</p>


<p>Declaration at line 1272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#ae9eab7a6f6e43c3a48731017dd24e746">getMemory</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a015653deceadd540a1e4fc871a1a21ea">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a8d3c6bd8729cd1fcbee8b2534affc30d">llvm::APSInt::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4bef95512fa985102be74adbdb966f80">areUsedBitsDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ab018e5f3273fdf77d6838c1bb037137a">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSEXTi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3c5315388a7981c96e7f006c78980966">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSplati</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a5589e186b84c92aaeecbaeaf6253ebc8">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a3fb5a21e3d12a4f09da156333cdef568">anonymous{Utils.cpp}::getConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a3ef62399dd4b7e5dbc8398704aaa79bc">llvm::BuildVectorSDNode::isConstantSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aafb64237a88493be2c913b0a51630a0f">llvm::ISD::isConstantSplatVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a020e15d458158f9576cddf71923093dd">lowerMSABinaryBitImmIntr</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2caf0087e5ae1170754a8a4503df9a98">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a710c96cb41fa446808a270ad1e705103">rebuildExtCst</a>, <a href="#a9b5fc98b47d44d1150d3610bdfab1430">sextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a7da80f756644226c925de9aa4bf77d94">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#af02cf2ea5865f88ae2a21e446d560d5a">llvm::APSInt::trunc</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>, <a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a>, <a href="#a21ede0a7cd71b89d7f2f8976321bab08">truncUSat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a> and <a href="#a2ed912a28808268e35bd58e8f11251aa">zextOrTrunc</a>.</p>

</div>
</div>

### truncSSat {#afe04819b980f360000f64b1b5487e0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::truncSSat (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Truncate to new width with signed saturation.</p>


<p>If this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, treated as signed integer, can be losslessly truncated to the new bitwidth, then return truncated <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. Else, return either signed min value if the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> was negative, or signed max value.</p>


<p>Declaration at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>, <a href="#a87d50d10274efe9688166584391ae489">isSignedIntN</a> and <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>.</p>

</div>
</div>

### truncUSat {#a21ede0a7cd71b89d7f2f8976321bab08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::truncUSat (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Truncate to new width with unsigned saturation.</p>


<p>If the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, treated as unsigned integer, can be losslessly truncated to the new bitwidth, then return truncated <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. Else, return max value.</p>


<p>Declaration at line 1278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a>, <a href="#ae00c35cb040107c05f3fe00c15bb3da0">isIntN</a> and <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a>.</p>

</div>
</div>

### zext {#a1dc76cc8bf703e6ada68bededcbb9573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::zext (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Zero extend to a new width.</p>


<p>This operation zero extends the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a new width. The high order bits are filled with 0 bits. It is an error to specify a width that is less than the current width.</p>


<p>Declaration at line 1300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#ae9eab7a6f6e43c3a48731017dd24e746">getMemory</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4c3a3d6e30e1512fd3b160cae4025f26">llvm::ConstantRange::castOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae9b6e09822fd0b670d93487058bea45">ConstantBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac3bb0fae6ff72b015a07fe80a33339c8">detectSSatUPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abc78591e933ad7d53f7fd4d8b9b4c096">detectUSatUPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#af0c949f0956bdd475184e8d934dc96e2">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPii</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3c5315388a7981c96e7f006c78980966">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSplati</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ad62f39c993a3723a7b735652e1e14f57">llvm::APSInt::extend</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a5589e186b84c92aaeecbaeaf6253ebc8">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a3fb5a21e3d12a4f09da156333cdef568">anonymous{Utils.cpp}::getConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a6b9321187f70bb8fc4c103af466f6c21">llvm::X86TTIImpl::getReplicationShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#af4baa77e580192624b604fa2192ff41b">anonymous{DAGCombiner.cpp}::LoadedSlice::getUsedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#af278f33f3e54a61566b7fdff3835e980">isObjectSizeLessThanOrEq</a>, <a href="#ad76807eccec7690dec05dd5f36aceb08">isSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a157e2addd6e66c2f7643c2349fa2da66">llvm::APIntOps::mulhu</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0309899567234d74bf87a3899207bc15">llvm::ConstantRange::multiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aa494dc35a29c6f78f26ea04679887f0d">llvm::APFixedPoint::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ac4d3bfb8f8f9526c1e2703ef25f43418">toSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a07384ea9d8fdfb208574ff59715e5be2">llvm::APFixedPoint::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3cff897f0ed479f872425600e0800701">llvm::LegalizationArtifactCombiner::tryCombineZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a5ac801ed9e1a056f66831b7f0129fdb0">tryToMergePartialOverlappingStores</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a636ddf018d314a1d73f98e2fa4efbafb">llvm::ConstantRange::zeroExtend</a> and <a href="#a2ed912a28808268e35bd58e8f11251aa">zextOrTrunc</a>.</p>

</div>
</div>

### zextOrTrunc {#a2ed912a28808268e35bd58e8f11251aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::zextOrTrunc (unsigned width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Zero extend or truncate to width.</p>


<p>Make this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> have the bit width given by <span class="doxyComputerOutput">width</span>. The value is zero extended, truncated, or left alone to make it that width.</p>


<p>Declaration at line 1312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa734719767b4f7faea1f7b40554f30be">llvm::X86TargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a8e4ee2a70091fe36640fda28c69580c6">llvm::DIExpression::constantFold</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a80a69d92372f6bfde4ea47c1b55b84bb">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateZEXTi</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a27a48d828a2227311270264ae0e78f8c">llvm::Interpreter::exitCalled</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0080c63e713e9ead5c33929b9127e96f">llvm::APSInt::extOrTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ae67d970cf80e86c5789e52f9d57d0c70">getPreferredVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a29ee697fe94374eae9689321e811f5e9">llvm::ScalarEvolution::getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a18f51ef21d273b6674761593a311b6f4">isBitfieldDstMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9941226cefb2787fa29507c4f5630d6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6fd6113581071d7d586e82cf3454bc9a">llvm::CombinerHelper::matchCombineConstPtrAddToI2P</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5f4f153e2f8d9dd1c45d089ea3c7499f">resolveBuildVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a49bff27cd8c639d90493b91350d3d9d0">llvm::X86TTIImpl::simplifyDemandedUseBitsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a76616979b7159a14d6afcb13c0106326">simplifyX86vpermilvar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4515378302b14f9df5b64311e4c84a80">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a07384ea9d8fdfb208574ff59715e5be2">llvm::APFixedPoint::toString</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Bit Manipulation Operators

### clearAllBits {#a781bd5c20864a9c185018258af774ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::clearAllBits ()</td>
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

<p>Set every bit to 0.</p>

<p>Definition at line 1397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ac8a4a891bdc2466ae10fe03a0a44bb81">llvm::MCInstrAnalysis::clearsSuperRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>.</p>

</div>
</div>

### clearBit {#a155466c9ea0a2bd00e09c62fdce2c052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::clearBit (unsigned BitPosition)</td>
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

<p>Set a given bit to 0.</p>


<p>Set the given bit to 0 whose position is given as "bitPosition".</p>


<p>Definition at line 1407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="#af883359d8cdce0f853270b28d7bfc564">clearSignBit</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a7fbae83b06276268455de0368194f94a">defaultComponentBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4836b23626e1d7b24f8bb84be3a55667">getHopForBuildVector</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a0a402f51b5d937bbd3accc7bb354ab">llvm::possiblyDemandedEltsInMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="#af5f9dd7fb931d5c71749761348534109">setBitVal</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a58e687cb25ed94c378fc444895422a13">trimTrailingZerosInVector</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>.</p>

</div>
</div>

### clearHighBits {#aef3f66072750c56846c44817e7336a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::clearHighBits (unsigned hiBits)</td>
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

<p>Set top hiBits bits to 0.</p>

<p>Definition at line 1424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad960e1ff48d25c382b6d28e7961f074e">getLowBitsSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af3a2b03b115846b5339469ce1e603976a02bce93bff905887ad2233110bf9c49e">llvm::Keep</a>.</p>

</div>
</div>

### clearLowBits {#aac76bff09195240a482b319136ab6144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::clearLowBits (unsigned loBits)</td>
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

<p>Set bottom loBits bits to 0.</p>

<p>Definition at line 1417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adcb96bd09d7c75c7669fa5f9d1190899">getHighBitsSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af3a2b03b115846b5339469ce1e603976a02bce93bff905887ad2233110bf9c49e">llvm::Keep</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2ed221e7e8b34742e248f6f81ef15f90">llvm::KnownBits::makeGE</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a47ce2e594a05222051dc71da56d75d9b">llvm::ConstantRange::toKnownBits</a>.</p>

</div>
</div>

### clearSignBit {#af883359d8cdce0f853270b28d7bfc564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::clearSignBit ()</td>
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

<p>Set the sign bit to 0.</p>

<p>Definition at line 1431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a155466c9ea0a2bd00e09c62fdce2c052">clearBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac9384ac452485cfed65a93b238080793">llvm::KnownBits::abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>.</p>

</div>
</div>

### extractBits {#adf997f1047734d3b47b8d5a9b2163f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::extractBits (unsigned numBits, unsigned bitPosition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with the extracted bits [bitPosition,bitPosition+numBits).</p>

<p>Declaration at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac21ca860de08b06c8c3d51c536ba0c90">computeZeroableShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a174a77eb2d84ab20b1e3e58da247fd41">getExactInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab491618a9074f0b773aa605bcb9450d3">LowerBuildVectorv16i8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a91771a953d65aeb837eecfef355de17f">lowerShuffleAsVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe25313da4ec14f1e260d91672c31545">lowerShuffleWithVPMOV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acabdb7ba50c76e8a7a040985d783f507">matchShuffleAsVTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a469a3a48f9634f5d6b0e2855d05ca42d">llvm::APIntOps::mulhs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a157e2addd6e66c2f7643c2349fa2da66">llvm::APIntOps::mulhu</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#afcd344dd26b9b6b08fcb676d1c888bc8">anonymous{ConstantFolding.cpp}::ReadDataFromGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>.</p>

</div>
</div>

### extractBitsAsZExtValue {#a29177946d0b9d5003e7a952a9684b797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t APInt::extractBitsAsZExtValue (unsigned numBits, unsigned bitPosition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a48ef6764a965598939c3ecf43eeb9fb0">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNPermIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a57c601613d1b256c59417e392d0575bf">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#a6f71c07949a30c419a392f05c1a7cb6e">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodeInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#aa18696894909136556d40020664aefe1">getMaxShiftAmount</a>.</p>

</div>
</div>

### flipAllBits {#aa26382591715c45666c3c6336755d529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::flipAllBits ()</td>
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

<p>Toggle every bit to its opposite value.</p>

<p>Definition at line 1434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ad39f77bca09ecfaf5b7a80933369163a">getUsefulBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aad0daa206bfc0bc764e664e19a94d495">getUsefulBitsFromBFM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1c34ea579237aedce7149724afc490ab">insert1BitVector</a> and <a href="#a8376734f311508662dd7e737752e5953">negate</a>.</p>

</div>
</div>

### flipBit {#ad8466cf860f0a86eee4694fc5c097f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::flipBit (unsigned bitPosition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Toggles a given bit to its opposite value.</p>


<p>Toggle a given bit to its opposite value whose position is given as "bitPosition".</p>


<p>Toggles a given bit to its opposite value.</p>


<p>Declaration at line 1447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af5f9dd7fb931d5c71749761348534109">setBitVal</a>.</p>

</div>
</div>

### insertBits {#aabe301a4f18d38478700ad44ba2245bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::insertBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; SubBits, unsigned bitPosition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert the bits from a smaller <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> starting at bitPosition.</p>

<p>Declaration at line 1456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a512fe2c15ea651294688eeec1341644c">getBitWidth</a>, <a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#af5f9dd7fb931d5c71749761348534109">setBitVal</a>, <a href="#ab82287ee9a2442bc0b6025a9936c88dc">VAL</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a48ef6764a965598939c3ecf43eeb9fb0">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNPermIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a444d74103a976b2567a773f70571b3d9">getSplatableConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a710c96cb41fa446808a270ad1e705103">rebuildExtCst</a> and <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>.</p>

</div>
</div>

### insertBits {#a369007fafbf2f88498f412f00eb0a469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::insertBits (uint64_t SubBits, unsigned bitPosition, unsigned numBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>.</p>

</div>
</div>

### negate {#a8376734f311508662dd7e737752e5953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::negate ()</td>
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

<p>Negate this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> in place.</p>

<p>Definition at line 1450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#aa26382591715c45666c3c6336755d529">flipAllBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab95d4485884d2e093f534590f24cfe0d">llvm::LegalizerHelper::getDynStackAllocTargetPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="#a24187c2e178af0df22dac26cd5229294">sdivrem</a>, <a href="#a76e54fadf3b01da96aaa66c35ed8c366">sdivrem</a> and <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>.</p>

</div>
</div>

### setAllBits {#ab6fff8a97bcb55e50e9be0ecf0c99b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setAllBits ()</td>
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

<p>Set every bit to 1.</p>

<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a507f18d22ad9ce4dd96e8a664d577bdd">APINT_WORD_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aebab5179ce7e05015dcccd98da3c0ac5">clearUnusedBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1f1be83c0efdaff4af051b7a45faaba7">llvm::KnownBits::ashr</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1749d6a76a90f1117d344826f3e1e428">getExtractedDemandedElts</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#af4baa77e580192624b604fa2192ff41b">anonymous{DAGCombiner.cpp}::LoadedSlice::getUsedBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>.</p>

</div>
</div>

### setBit {#a33f9f862dca8ee0f23bff5941bf433d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setBit (unsigned BitPosition)</td>
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

<p>Set the given bit to 1 whose position is given as "bitPosition".</p>

<p>Definition at line 1330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac9384ac452485cfed65a93b238080793">llvm::KnownBits::abs</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a18790dbaa8ba6bb118ea10e8643a0597">llvm::KnownBits::blsi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a977096c9dc329a2a00fc00549fa2ff84">combineX86ShufflesConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac21ca860de08b06c8c3d51c536ba0c90">computeZeroableShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1749d6a76a90f1117d344826f3e1e428">getExtractedDemandedElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72a64c02db1b9e475fc2646e656cdb98">llvm::getHorizDemandedEltsForFirstOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="#aec662ee6ab1490a4cabebf2812e5b9ca">getOneBitSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6302b532981eadcac10d0d3ab01e3805">llvm::getShuffleDemandedElts</a>, <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af71303967827d0c63f1caa626e59aa38">getTargetShuffleAndZeroables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adf48ee86d6a806ea693f8e4088718c4d">isCompletePermute</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af83ff96c157ea2db2a7f032cc9c80369">isTargetShuffleEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6cf260b0a7ee2cfa1e24f28b771a5f24">lowerShuffleAsLanePermuteAndPermute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ada94cd83b8b150c87b337c156f027c3c">PerformReduceShuffleCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aebf9c73db3d255463a574759f2ee030c">resolveZeroablesFromTargetShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab455b98d2cc1e2a8ff7a9486ec4c2982">llvm::APIntOps::ScaleBitMask</a>, <a href="#af5f9dd7fb931d5c71749761348534109">setBitVal</a>, <a href="#a4f1e1a4449b58958c5884c689e7f4861">setSignBit</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>.</p>

</div>
</div>

### setBits {#acb95d5d8e87df053e1b53e2ec60de4b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setBits (unsigned loBit, unsigned hiBit)</td>
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

<p>Set the bits from loBit (inclusive) to hiBit (exclusive) to 1.</p>


<p>This function handles case when <span class="doxyComputerOutput">loBit</span> &lt;= <span class="doxyComputerOutput">hiBit</span>.</p>


<p>Definition at line 1367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac9384ac452485cfed65a93b238080793">llvm::KnownBits::abs</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a5974d2150b4875417b407ee6a06ff640">llvm::LanaiTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="#a46ceedee591f92727b85641794a96061">getBitsSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab455b98d2cc1e2a8ff7a9486ec4c2982">llvm::APIntOps::ScaleBitMask</a>, <a href="#a286d4fa2a50c9ac6ac3a8069cccfcd0c">setBitsFrom</a>, <a href="#a97d7462ee50c7b2ad49c08d8661f52d2">setBitsWithWrap</a>, <a href="#a2780c5606880394d3f07cd2079a27697">setHighBits</a> and <a href="#ade8e20ecea1091e835395746448e262e">setLowBits</a>.</p>

</div>
</div>

### setBitsFrom {#a286d4fa2a50c9ac6ac3a8069cccfcd0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setBitsFrom (unsigned loBit)</td>
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

<p>Set the top bits starting from loBit.</p>

<p>Definition at line 1386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a18790dbaa8ba6bb118ea10e8643a0597">llvm::KnownBits::blsi</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a3672d546ea0f6b4748807c35d620bdc9">llvm::KnownBits::blsmsk</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7b936082e1b7db71c559544b9cb8b0b2">llvm::SITargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="#aeaf22e8d92fd978a5eca9ab031994399">getBitsSetFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa142b4be3c3ce29d1c12c39b88ec687d">isTruncateOf</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a49bff27cd8c639d90493b91350d3d9d0">llvm::X86TTIImpl::simplifyDemandedUseBitsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a39ed92e826ef5d0893f72b26fab78aa3">llvm::RISCVTargetLowering::targetShrinkDemandedConstant</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a51c3c203b80468b8761416d14e6f5b7f">llvm::KnownBits::zext</a>.</p>

</div>
</div>

### setBitsWithWrap {#a97d7462ee50c7b2ad49c08d8661f52d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setBitsWithWrap (unsigned loBit, unsigned hiBit)</td>
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

<p>Set the bits from loBit (inclusive) to hiBit (exclusive) to 1.</p>


<p>This function handles "wrap" case when <span class="doxyComputerOutput">loBit</span> &gt;= <span class="doxyComputerOutput">hiBit</span>, and calls setBits when <span class="doxyComputerOutput">loBit</span> &lt; <span class="doxyComputerOutput">hiBit</span>. For <span class="doxyComputerOutput">loBit</span> == <span class="doxyComputerOutput">hiBit</span> wrap case, set every bit to 1.</p>


<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>, <a href="#a2780c5606880394d3f07cd2079a27697">setHighBits</a> and <a href="#ade8e20ecea1091e835395746448e262e">setLowBits</a>.</p>


<p>Referenced by <a href="#af3bee3e462a14abdf3858c354a5cd222">getBitsSetWithWrap</a>.</p>

</div>
</div>

### setBitVal {#af5f9dd7fb931d5c71749761348534109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setBitVal (unsigned BitPosition, bool BitValue)</td>
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

<p>Set a given bit to a given value.</p>

<p>Definition at line 1343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a155466c9ea0a2bd00e09c62fdce2c052">clearBit</a> and <a href="#a33f9f862dca8ee0f23bff5941bf433d8">setBit</a>.</p>


<p>Referenced by <a href="#ad8466cf860f0a86eee4694fc5c097f44">flipBit</a> and <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>.</p>

</div>
</div>

### setHighBits {#a2780c5606880394d3f07cd2079a27697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setHighBits (unsigned hiBits)</td>
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

<p>Set the top hiBits bits.</p>

<p>Definition at line 1392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a59eb700f7620c6a3ebbdc281bc00d3bd">llvm::SITargetLowering::computeKnownBitsForFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#adcb96bd09d7c75c7669fa5f9d1190899">getHighBitsSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac72c6a7fdaf91e99b6a6232207e57edc">knownBitsForWorkitemID</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="#a97d7462ee50c7b2ad49c08d8661f52d2">setBitsWithWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a905d2324c26b7a6f5aeb929a734ce0bc">llvm::KnownBits::srem</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a96120d4062fabb503b1b92401e54d14f">llvm::KnownBits::udiv</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2838364c4863a3b2c55c6fd7052413aa">llvm::KnownBits::urem</a>.</p>

</div>
</div>

### setLowBits {#ade8e20ecea1091e835395746448e262e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setLowBits (unsigned loBits)</td>
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

<p>Set the bottom loBits bits.</p>

<p>Definition at line 1389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac9384ac452485cfed65a93b238080793">llvm::KnownBits::abs</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a3672d546ea0f6b4748807c35d620bdc9">llvm::KnownBits::blsmsk</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a249a932d6f75f857e8caf11bcab9f920">llvm::GISelKnownBits::computeKnownBitsForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="#ad960e1ff48d25c382b6d28e7961f074e">getLowBitsSet</a>, <a href="#a97d7462ee50c7b2ad49c08d8661f52d2">setBitsWithWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>.</p>

</div>
</div>

### setSignBit {#a4f1e1a4449b58958c5884c689e7f4861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::setSignBit ()</td>
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

<p>Set the sign bit to 1.</p>

<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a33f9f862dca8ee0f23bff5941bf433d8">setBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac9384ac452485cfed65a93b238080793">llvm::KnownBits::abs</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae0b0ab35dee6bb5d9d53098111bf5c84">llvm::KnownBits::getSignedMinValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Value Characterization Functions

### countl\_one {#aa619d96a87c8a5be606b1a4a4ac0115d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countl_one ()</td>
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

<p>Count the number of leading one bits.</p>


<p>This function is an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> version of std::countl_one. It counts the number of ones from the most significant bit to the first zero bit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>0 if the high order bit is not set, otherwise returns the number of 1 bits from the most significant to the least</p></dd>
</dl>


<p>Definition at line 1594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d92de57590536d2f254fe5e903e3372">llvm::countl_one</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="#a3a2a335dd528474e41dcf609f79b0be2">countLeadingOnes</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a7fe1f82ca176ae71b0d72e241df952ea">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCLBi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="#a8924f4d542442eecf3aac41a0bd61fa3">getNumSignBits</a>, <a href="#a1b6b4785fa27be394cf040e543d9fe7c">isNegatedPowerOf2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c4d94b8b92e288f152e1f1d9e2598d">lower1BitShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa54817a233f0f0b0e3fb5f733c0b273">lowerShuffleAsByteShiftMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1039cc78150f31678aae25affc5fbec">lowerShuffleAsVALIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2fa56217f486efff0ef3cbf1b6a7f524">lowerShuffleAsVTRUNCAndUnpack</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a62222502f5be2dd8e300b48469aeab4f">llvm::ConstantRange::shl</a> and <a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a>.</p>

</div>
</div>

### countl\_zero {#a8bad27827f46bca6baf814cbd2b64e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countl_zero ()</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> version of std::countl_zero.</p>


<p>It counts the number of zeros from the most significant bit to the first one bit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>BitWidth if the value is zero, otherwise returns the number of zeros from the most significant bit to the first one bits.</p></dd>
</dl>


<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4bef95512fa985102be74adbdb966f80">areUsedBitsDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#acc600a6141b4b54703a4ead9c72a3012">bitTrackingDCE</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="#aa074b9f5a1efaa0fd8aa4522593f299a">countLeadingZeros</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a7fe1f82ca176ae71b0d72e241df952ea">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCLBi</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a8924f4d542442eecf3aac41a0bd61fa3">getNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab6bb88ba60ff98b8e2c142d472f53717">PerformBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="#a028f4d1eead63cc33499ce3459bd27c7">umul_ov</a>, <a href="#ac8345a3be974d824185f13fc5c196393">ushl_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>.</p>

</div>
</div>

### countLeadingOnes {#a3a2a335dd528474e41dcf609f79b0be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countLeadingOnes ()</td>
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



<p>Definition at line 1603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a5532e05d5caa4fb5e2b8512aa3095f1e">foldNegativePower2AndShiftedMask</a>.</p>

</div>
</div>

### countLeadingZeros {#aa074b9f5a1efaa0fd8aa4522593f299a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countLeadingZeros ()</td>
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



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a618caf6a690e2208acbfa1b7668df3a2">computeShlNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a5532e05d5caa4fb5e2b8512aa3095f1e">foldNegativePower2AndShiftedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab8efede7dd68d6d28fa1cfd032f9ba3b">foldSelectICmpAndZeroShl</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a96120d4062fabb503b1b92401e54d14f">llvm::KnownBits::udiv</a>.</p>

</div>
</div>

### countr\_one {#af34a543ce8585d04c1ae22c78b3182dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countr_one ()</td>
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

<p>Count the number of trailing one bits.</p>


<p>This function is an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> version of std::countr_one. It counts the number of ones from the least significant bit to the first zero bit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>BitWidth if the value is all ones, otherwise returns the number of ones from the least significant bit to the first zero bit.</p></dd>
</dl>


<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="#ae155fc08c52bcfd6026faf4c640a2cf7">countTrailingOnes</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a56d6f482a718e221a121400cb89aef5b">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCTBi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a99e3727e5ff5a1c45d0ee6dfb697308a">foldSubCtlzNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa54817a233f0f0b0e3fb5f733c0b273">lowerShuffleAsByteShiftMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab1039cc78150f31678aae25affc5fbec">lowerShuffleAsVALIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac0d7b6ab8ce9dce97d728aef673b1eed">PerformMinMaxToSatCombine</a>.</p>

</div>
</div>

### countr\_zero {#a83c7c9008ba213687483b60a658b4a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countr_zero ()</td>
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

<p>Count the number of trailing zero bits.</p>


<p>This function is an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> version of std::countr_zero. It counts the number of zeros from the least significant bit to the first set bit.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>BitWidth if the value is zero, otherwise returns the number of zeros from the least significant bit to the first one bit.</p></dd>
</dl>


<p>Definition at line 1618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4bef95512fa985102be74adbdb966f80">areUsedBitsDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af5d3388e53cb2767927dba7c18c64a00">llvm::CombinerHelper::buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7b8ca6f7206a11fd57d6e194b2523ffe">canonicalizeLogicFirst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a71945ca56b18be50385fea02d09db49e">checkForNegativeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="#a9a99431f0828d0222c617eb876bc5d34">countTrailingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a56d6f482a718e221a121400cb89aef5b">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCTBi</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a47a83bda096455c177d40a2fbae13de1">llvm::InstCombinerImpl::foldICmpShlConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#ab0240a68d7340353c85a26853b20b471">getPowerOf2Factor</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a1f4b3d9a1db2a863f398981ea5c1d641">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMulByConstant</a>, <a href="#a17fee74434129df42225c7e5eaab709c">isAligned</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="#a1b6b4785fa27be394cf040e543d9fe7c">isNegatedPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab6bb88ba60ff98b8e2c142d472f53717">PerformBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### countTrailingOnes {#ae155fc08c52bcfd6026faf4c640a2cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countTrailingOnes ()</td>
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



<p>Definition at line 1641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#af34a543ce8585d04c1ae22c78b3182dd">countr_one</a>.</p>

</div>
</div>

### countTrailingZeros {#a9a99431f0828d0222c617eb876bc5d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::countTrailingZeros ()</td>
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



<p>Definition at line 1626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a83c7c9008ba213687483b60a658b4a13">countr_zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a29ee697fe94374eae9689321e811f5e9">llvm::ScalarEvolution::getSmallConstantTripMultiple</a>.</p>

</div>
</div>

### getActiveBits {#a3015474e70e59c0a3ed4f9f0e8644b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getActiveBits ()</td>
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

<p>Compute the number of active bits in the value.</p>


<p>This function returns the number of active bits which is defined as the bit width minus the number of leading zeros. This is used in several computations to see how "wide" the value is.</p>


<p>Definition at line 1492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a015653deceadd540a1e4fc871a1a21ea">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a8d3c6bd8729cd1fcbee8b2534affc30d">llvm::APSInt::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4bef95512fa985102be74adbdb966f80">areUsedBitsDense</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="#a392d67031c5429420ac0b46478fe893e">ceilLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a059a0dff9799816117b8b2fd73bd1425">llvm::ConstantRange::getActiveBits</a>, <a href="#ad2c2b7a1d52ade8885995a54205a923b">getActiveWords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1cea2904e9cf054e408e6023cd8b852c">llvm::getBitwiseNotOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0bf0cf316748d2fb01a45268ffc10a02">getConstantTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ae67d970cf80e86c5789e52f9d57d0c70">getPreferredVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a29ee697fe94374eae9689321e811f5e9">llvm::ScalarEvolution::getSmallConstantTripMultiple</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="#ae00c35cb040107c05f3fe00c15bb3da0">isIntN</a>, <a href="#aae3b959a0a2981340fd03c29f528f2f0">logBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="#a5f74c7368cdc65e9e942faca9976d080">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2caf0087e5ae1170754a8a4503df9a98">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a710c96cb41fa446808a270ad1e705103">rebuildExtCst</a>, <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="#a03385a25be413259dc4abb7252b3aaa4">tryZExtValue</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#abfeca4698f01ef85e21a3e3061751781">ugt</a>, <a href="#afe03273b7efa986834cca7b9899a686b">ult</a>, <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>, <a href="#a825a8dca80ee195760b908990de1a7af">urem</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>.</p>

</div>
</div>

### getActiveWords {#ad2c2b7a1d52ade8885995a54205a923b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getActiveWords ()</td>
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

<p>Compute the number of active words in the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>This is used in conjunction with getActiveData to extract the raw value of the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Definition at line 1498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>.</p>

</div>
</div>

### getBitsNeeded {#ab9178a079b54667289f598db5b052ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::getBitsNeeded (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> str, uint8_t radix)</td>
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

<p>Get bits required for string value.</p>


<p>This method determines how many bits are required to hold the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> equivalent of the string given by <span class="doxyComputerOutput">str</span>.</p>


<p>Declaration at line 1563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="#a31665d34f2904bf73a6dd6419dcd8587">getSufficientBitsNeeded</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>, <a href="#ad1b0513de876d1c85cf6268ca21b2c86">isPowerOf2</a>, <a href="#aae3b959a0a2981340fd03c29f528f2f0">logBase2</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getBitWidth {#a512fe2c15ea651294688eeec1341644c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getBitWidth ()</td>
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

<p>Return the number of bits in the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>

<p>Definition at line 1468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add70e1fee22605cd751d89682c4dd5c7">llvm::DwarfUnit::addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0734fce4dae0f79f3a00e6b3539f8b96">llvm::DwarfUnit::addInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a015653deceadd540a1e4fc871a1a21ea">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#abb62d40db98a4479c864881fc06ce82a">APIntToHexString</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a856d46e90d7159a88c175ceff667f40c">canonicalizeGEPOfConstGEPI8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab160c4766dfd9c2f981e092e730fd1b0">combineShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a46be5bb239b3fc96e2ff377081579f72">llvm::APSInt::compareValues</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="#a6bc2ad05ce14ae805c176fc8abfbe0a1">concat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59a7ed1e5bfd8f5d0c66a7346ee5f87b">llvm::ConstantFoldBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aebaffb4b288b2508f99e75e0e8bd3ed9">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kmccodeemitter-cpp-/m68kmccodeemitter/#a6f71c07949a30c419a392f05c1a7cb6e">anonymous{M68kMCCodeEmitter.cpp}::M68kMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperation/#ae881b7ad9c843880674599dbe5d85dd9">llvm::BinaryOperation::eval</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a7fe1f82ca176ae71b0d72e241df952ea">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCLBi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#af0c949f0956bdd475184e8d934dc96e2">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPii</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a56d6f482a718e221a121400cb89aef5b">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCTBi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ae7767cf650405a9ff3d68ae59a76c15d">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ab018e5f3273fdf77d6838c1bb037137a">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSEXTi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3c5315388a7981c96e7f006c78980966">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSplati</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a80a69d92372f6bfde4ea47c1b55b84bb">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateZEXTi</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a5589e186b84c92aaeecbaeaf6253ebc8">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9e0d5c318896c80af37213924c64f2be">llvm::InstCombinerImpl::foldAddLikeCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a47a83bda096455c177d40a2fbae13de1">llvm::InstCombinerImpl::foldICmpShlConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a8b324b9fcea4493d60035273d9b8e085">foldNoWrapAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a1729c80f033d20835e31fddb245a4aae">FoldValueWithUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9606293f9b700b964e76f7fd75a0b4c9">getAVX512Node</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe7ad42a427fd0055f7f57f33b915252">getConstVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72a64c02db1b9e475fc2646e656cdb98">llvm::getHorizDemandedEltsForFirstOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#ab401f0019413b136ec7484fcb6236f68">llvm::SwitchCG::getJumpTableRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8cd15ddae8837842830d97285936440a">llvm::ScalarEvolution::getNonZeroConstantMultiple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a99c9ef8776106c1e7b35c77a32e750e1">GetQuadraticEquation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a28caa20d9fc8a395fd4253ccbfe7eb48">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#abe6716586fd3697256a6bc605a72f06f">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getReplicationShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab9de4ecd5d07314b56d5a0d1fad6f6fc">getShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a444be9352256919a844309a35dffa0f8">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a4736b509c1f8cc3d4f7a44e2a4283ee0">getStrideFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ad39f77bca09ecfaf5b7a80933369163a">getUsefulBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ab355b8de097910b27f8a8527f9d2e512">getUsefulBitsForUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acca3317ec9abd9a2b3da9870ca65c9c5">getUsefulBitsFromAndWithImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aad0daa206bfc0bc764e664e19a94d495">getUsefulBitsFromBFM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a8e67baf5aacf7f9fa94cbb5d66880700">getUsefulBitsFromBitfieldMoveOpd</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1e362f3699fd2c3f46c7a3690031dda3">llvm::SelectionDAG::getVScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8d91ca7ede308b821f546a33f6625115">impliesPoisonOrCond</a>, <a href="#aabe301a4f18d38478700ad44ba2245bc">insertBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5959d13e50c78592ca89a8a964fb510c">llvm::ConstantRange::intrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#aba6d21be69606c88eb1313d64b71c112">llvm::TargetTransformInfoImplBase::isConstantStridedAccessLessThan</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0fc8d69e5f9f1289c79f3e49cc3bfc5">llvm::SelectionDAG::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae2cb6bf0817b8dbe415405c7498b8ce7">llvm::X86TargetLowering::isGuaranteedNotToBeUndefOrPoisonForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a37947028558485b4526101a36f80dcc8">isKnownNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#ab5b599ce37d7c23ca6479c148c0a259d">isMultiple</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a587eab2c520053bb06fdc4afe5a57aa3">isPoisonShift</a>, <a href="#ad76807eccec7690dec05dd5f36aceb08">isSameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="#a841147c648072358e88b0d0a50359ebe">isSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a34faa94759387be0a4881a7e227f6caf">llvm::X86TargetLowering::isSplatValueForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a13e47380f530d0f3667a5b22fc47833e">MatchDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a0a1310e81cd1bccba5e81fe929fb7c87">MatchMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a469a3a48f9634f5d6b0e2855d05ca42d">llvm::APIntOps::mulhs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a157e2addd6e66c2f7643c2349fa2da66">llvm::APIntOps::mulhu</a>, <a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a758290c5743d18768a64d96539070fd1">optimizeIncrementingWhile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#acd8fb018deb0883d60ae768058d3e871">parseHexOcta</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a835501e075de398a571345a471fd74d7">parseHexOcta</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6b95b272aa478099397bc06bb7c286ec">PerformUMinFpToSatCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a735ccd5c4f719f05d522e22a0ade0a26">resolveTargetShuffleFromZeroables</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a36d1b77a885effd5cefdd787a7935226">llvm::LoongArchDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af619c526b5e90968d76fbd4fe4c861cb">llvm::RISCVDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#ac8a9940ba807ee771ad949f2ab9e8bea">llvm::LoongArchDAGToDAGISel::selectVSplatUimmInvPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a1a4e02c3247bc8b4134b91e707d6c146">llvm::LoongArchDAGToDAGISel::selectVSplatUimmPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aa494dc35a29c6f78f26ea04679887f0d">llvm::APFixedPoint::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7823e9650460a75ff21e53e2d62e7560">llvm::TargetLoweringBase::shouldFoldSelectWithSingleBitTest</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a177f4d30b9356e0bc4a5dc176e825cb2">simplifyIRemMulShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="#a36e003ab14cb859152427b64b665e691">sshl_ov</a>, <a href="#a89f4c6b6aa9f918f4586a08d399fd1d5">sshl_ov</a>, <a href="#a90e6be77d59fee53e8585874cd1ab07c">sshl_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1d29074c7a610816d4f328b7cd9b783d">llvm::ConstantRange::subtract</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a7da80f756644226c925de9aa4bf77d94">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#ac4d3bfb8f8f9526c1e2703ef25f43418">toSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyinstprinter-cpp/#a63c3f91798717016cc0fbef3b4dc0b34">toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a5ac801ed9e1a056f66831b7f0129fdb0">tryToMergePartialOverlappingStores</a>, <a href="#a97419fdddc400a50c7c40ef5c35903cd">ushl_ov</a>, <a href="#ac8345a3be974d824185f13fc5c196393">ushl_ov</a>, <a href="#a9458a57a572f29dd261a3be65cd8ee9f">ushl_sat</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ad7c510ac5f19ce17fd2b5b06d15a7aa3">llvm::SCEVDivision::visitConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### getNumSignBits {#a8924f4d542442eecf3aac41a0bd61fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getNumSignBits ()</td>
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

<p>Computes the number of leading bits of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> that are equal to its sign bit.</p>

<p>Definition at line 1607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#aa619d96a87c8a5be606b1a4a4ac0115d">countl_one</a>, <a href="#a8bad27827f46bca6baf814cbd2b64e84">countl_zero</a> and <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ada5a1c97857d6b28c7292bcb5496ac68">computeNumSignBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>.</p>

</div>
</div>

### getNumWords {#a5fa938f247b20cccc87cc8a6e5d20aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getNumWords ()</td>
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

<p>Get the number of words.</p>


<p>Here one word's bitwidth equals to that of uint64_t.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of words to hold the integer value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p></dd>
</dl>


<p>Definition at line 1475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>.</p>


<p>Referenced by <a href="#ace0bd40e4bee1851ebebb276178d65fc">byteSwap</a>, <a href="#a781bd5c20864a9c185018258af774ace">clearAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a135db5ce97b04855e9e8f44d26d30d43">llvm::detail::IEEEFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aebaffb4b288b2508f99e75e0e8bd3ed9">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="#adf997f1047734d3b47b8d5a9b2163f11">extractBits</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e3c089e61a9927131ee18b4eb7c7c5c">llvm::hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="#ae4ebaecf630dbd7f04d1c3f9d9cfbad5">operator&amp;=</a>, <a href="#a8affacda773b55e259f6dc4da77d948a">operator*</a>, <a href="#aed0fa6f38807df2e9ff7f643de4f42d6">operator*=</a>, <a href="#a3f577ba20414abdc4328d2c5c14c37f5">operator++</a>, <a href="#ad550e9403dfe9c20c6b8adb6acb25180">operator+=</a>, <a href="#a30a2fd77599a3403f6a848952dd7f82e">operator+=</a>, <a href="#ae8f371673bb2e0237b0409940657619a">operator--</a>, <a href="#a86485d3a573bdd67a702e19fe7790c66">operator-=</a>, <a href="#a15edd02fb043f45d425b99ff92e7c4b0">operator-=</a>, <a href="#a5706001980ca4d8b32c73ca742bcc4fa">operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="#adb1c052266ebacdbf28164fae9106b0a">Profile</a>, <a href="#ab6fff8a97bcb55e50e9be0ecf0c99b63">setAllBits</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a>, <a href="#a317c64fd4cfebc88e79387b3821a629d">trunc</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#af21fe5092047a14fb320f82d99276b99">udiv</a>, <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>, <a href="#a8bd2f21c3219cdb1c83f080dc7e1fc31">udivrem</a>, <a href="#a4e3a2187cacdec76028617a403c47d89">urem</a>, <a href="#a825a8dca80ee195760b908990de1a7af">urem</a> and <a href="#a1dc76cc8bf703e6ada68bededcbb9573">zext</a>.</p>

</div>
</div>

### getNumWords {#aa2cabc55d461335724f348fa2e2c6fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getNumWords (unsigned BitWidth)</td>
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

<p>Get the number of words.</p>


<p><em>NOTE</em> Here one word's bitwidth equals to that of uint64_t.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of words to hold the integer value with a given bit width.</p></dd>
</dl>


<p>Definition at line 1483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>.</p>

</div>
</div>

### getSExtValue {#af2daa0ee117afefed4c82eee55bf97b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::APInt::getSExtValue ()</td>
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

<p>Get sign extended value.</p>


<p>This method attempts to return the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> as a sign extended int64_t. The bit width must be &lt;= 64 or the value must fit within an int64_t. Otherwise an assertion will result.</p>


<p>Definition at line 1542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add70e1fee22605cd751d89682c4dd5c7">llvm::DwarfUnit::addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0734fce4dae0f79f3a00e6b3539f8b96">llvm::DwarfUnit::addInt</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo/#af587d7218fa15a456103c3d2125a1fc8">llvm::InterleavedAccessInfo::analyzeInterleaving</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-checkedarithmetic-h-/#afa16c7f7e608b78b961e0b6a1efdf001">anonymous{CheckedArithmetic.h}::checkedOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#ac79b06c4793c56d8155eb7c18aafa1d3">checkIfSafeAddSequence</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a1e5d35d93b0a1cd5f85018b1a98a883f">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::collectConstantsForGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a830996c6ee01a4fc50c18055a48a02a8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ab018e5f3273fdf77d6838c1bb037137a">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateSEXTi</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a477d37efcba589f51c319373cee0294e">llvm::APSInt::getExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a655cabf7c0f1a0d1e8312338e86abb84">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/corosubfninst/#a85b47c7821ab7c779250e9d61b15de4f">llvm::CoroSubFnInst::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a1cecee4f08f337680e2dc415f17f2ab3">llvm::AArch64TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a1dd09091b53437ee541090716cbb4a4b">llvm::X86TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a392b6c8a7962feed988bf14017205f4b">llvm::RISCVMatInt::getIntMatCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#ad01179d48cf278f76248683e9526a8b0">getMinimalBaseOfPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ac5d9eb48038aa973017317279eadf5">llvm::GetPointerBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a4736b509c1f8cc3d4f7a44e2a4283ee0">getStrideFromPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/argument/#a46136a8edb24437ca3ef84c207b8b392">llvm::remarks::Argument::getValAsInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8488e7918427cbc59c4216e0249bc8ee">getVShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8488e7918427cbc59c4216e0249bc8ee">getVShiftImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a09b3e808d3a4c48865a0b8cb59487f7d">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::HandleFixupError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#aba6d21be69606c88eb1313d64b71c112">llvm::TargetTransformInfoImplBase::isConstantStridedAccessLessThan</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a52376a753c8ddea8a93cc03bdecc4fcd">llvm::RISCVTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6c9e39c1fc1cf514ffd33b75339b815e">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">llvm::ARMTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abf938d888e2a13a56e6fc0b3017bb4dd">isSimpleVIDSequence</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaca63029362a3a1da53f00e79b6423aac">LLVMGenericValueToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#ab47e139366ce224347ee4ea7313c7ff9">anonymous{PassBuilder.cpp}::parseSimplifyCFGOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilbitcodewriter-cpp/#ac88a5c9203f37355fc1f385b5e5c6e7b">rotateSign</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="#a3291dd727de5786ef808475d8d9a1560">sgt</a>, <a href="#a0735ef8bd9cc0d99266fba0c6d7b5acb">slt</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aad0fb69928bec544ec83f90f26393521">tryCombineShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a> and <a href="#ae30d62aebec681aceb655de2489f12ba">trySExtValue</a>.</p>

</div>
</div>

### getSignificantBits {#a9f78d7e839322a6bfc0c665d29052242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::getSignificantBits ()</td>
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

<p>Get the minimum bit size for this signed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>


<p>Computes the minimum bit width for this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> while considering it to be a signed (and probably negative) value. If the value is not negative, this function returns the same value as <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits()</a>+1. Otherwise, it returns the smallest bit width that will retain the negative value. For example, -1 can be written as 0b1 or 0xFFFFFFFFFF. 0b1 is shorter and so for -1, this function will always return 1.</p>


<p>Definition at line 1511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a8924f4d542442eecf3aac41a0bd61fa3">getNumSignBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apsint/#a8d3c6bd8729cd1fcbee8b2534affc30d">llvm::APSInt::APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad35b9a85ea52062375c0c870be5cd228">canFoldIVIncExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a52376a753c8ddea8a93cc03bdecc4fcd">llvm::RISCVTargetLowering::isDesirableToCommuteWithShift</a>, <a href="#a87d50d10274efe9688166584391ae489">isSignedIntN</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#abd90406531e76ab0007b8cf6ebe8b34d">anonymous{LoopStrengthReduce.cpp}::Cost::RateFormula</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a710c96cb41fa446808a270ad1e705103">rebuildExtCst</a>, <a href="#a3291dd727de5786ef808475d8d9a1560">sgt</a>, <a href="#a0735ef8bd9cc0d99266fba0c6d7b5acb">slt</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a39ed92e826ef5d0893f72b26fab78aa3">llvm::RISCVTargetLowering::targetShrinkDemandedConstant</a>, <a href="#ae30d62aebec681aceb655de2489f12ba">trySExtValue</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>.</p>

</div>
</div>

### getSufficientBitsNeeded {#a31665d34f2904bf73a6dd6419dcd8587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::getSufficientBitsNeeded (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, uint8_t Radix)</td>
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

<p>Get the bits that are sufficient to represent the string value.</p>


<p>This may over estimate the amount of bits required, but it does not require parsing the value in the string.</p>


<p>Declaration at line 1568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ab9178a079b54667289f598db5b052ade">getBitsNeeded</a>.</p>

</div>
</div>

### getZExtValue {#a217e0207d9cc8e046c2dccbf0e4bb198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::APInt::getZExtValue ()</td>
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

<p>Get zero extended value.</p>


<p>This method attempts to return the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> as a zero extended uint64_t. The bitwidth must be &lt;= 64 or the value must fit within a uint64_t. Otherwise an assertion will result.</p>


<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a> and <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#add70e1fee22605cd751d89682c4dd5c7">llvm::DwarfUnit::addConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0734fce4dae0f79f3a00e6b3539f8b96">llvm::DwarfUnit::addInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6766b5f9c46b6dd7bb3b45857ec23a0f">llvm::CombinerHelper::applyFunnelShiftConstantModulo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a813af4f625c1b136c991637d08bf9087">llvm::buildSelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3d3ed8206aabad62293aeddd444bab9f">canEvaluateZExtd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-checkedarithmetic-h-/#afa16c7f7e608b78b961e0b6a1efdf001">anonymous{CheckedArithmetic.h}::checkedOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac5281f53eae7762532968413f7201798">CombineVMOVDRRCandidateWithVecOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a0cf99f7dc09e330137cb10a3a42c12b3">llvm::ProfileSummaryBuilder::computeDetailedSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#adcd35cd6dd267ca162a87fac0acb4925">computeFlagsForAddressComputation</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#aa734719767b4f7faea1f7b40554f30be">llvm::X86TargetLowering::ComputeNumSignBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a2ee4399de3a7bdd9b93639642dee7a6c">convertIntToDoubleImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#a11ee02debc81344dbf0cdd00d72e4f91">DecodeXR32RegisterClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#ae7767cf650405a9ff3d68ae59a76c15d">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateEXTRACTi</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a27a48d828a2227311270264ae0e78f8c">llvm::Interpreter::exitCalled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7808698e922d28431e93a2b7dc5b3997">llvm::extractConstantMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab8efede7dd68d6d28fa1cfd032f9ba3b">foldSelectICmpAndZeroShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a99e3727e5ff5a1c45d0ee6dfb697308a">foldSubCtlzNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a4ec3b92527a1e1b7d1a24410cbaf4b59">getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c0a683d5c4984e6d58f5f3809ff6ec3">llvm::getExpressionForConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#acf625a32c19c58380ada30e43781d0ae">anonymous{AArch64PostLegalizerLowering.cpp}::getExtMask</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a477d37efcba589f51c319373cee0294e">llvm::APSInt::getExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0f3039f831c483956c153ed9dee23dba">llvm::ScalarEvolution::getGEPExpr</a>, <a href="#ab01d8694a759a934e01f1c558c3ce862">getLimitedValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af54e9ce01961e65d9b74fef2193a8d95">llvm::SPIRVGlobalRegistry::getOrCreateConstFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af17d33003beaf2d0bb09d7b2ac7984">llvm::SelectionDAG::getShiftAmountConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a29ee697fe94374eae9689321e811f5e9">llvm::ScalarEvolution::getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/classes/llvm/gstepvector/#a3d228390eddc89596585e7392a679792">llvm::GStepVector::getStep</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9ebdafbae1fdc29135b25d537a89cd61">isEXTMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a24010a1eb5e99f1a4ace051c293a401f">isKnownTypeIdMember</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a2d9d6b4d91e3a1a4ce7ffe8ed701a40e">llvm::ARMTargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaca63029362a3a1da53f00e79b6423aac">LLVMGenericValueToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae061deb7e1ce634d402090342aeccda7">LowerShiftByScalarImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4775da751f6b1e2123b23a54dabf51c9">matchAndOrChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7662d7ee7f100c9455f4a2c7e4992929">matchIntPart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="#a5f74c7368cdc65e9e942faca9976d080">operator==</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a758290c5743d18768a64d96539070fd1">optimizeIncrementingWhile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a882ed852a717e7421c4dd8ede4908d92">optimizeLogicalImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/asmparser-cpp/#acd8fb018deb0883d60ae768058d3e871">parseHexOcta</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/masmparser-cpp/#a835501e075de398a571345a471fd74d7">parseHexOcta</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a705e25c3f466b071036bde5de60454c5">anonymous{PassBuilder.cpp}::parseInstCombineOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aec3ab4d2802494bdb8b2c3c5343f8254">PerformANDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1cb3d0ba0717491c0c28dcc2e4b3d152">performDSPShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a623fca6d1e6801438897a6335f1e4fb6">llvm::X86TargetLowering::preferedOpcodeForCmpEqPiecesOfOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a763e5d73a932a30d95c888b81f45a0c3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#afcd344dd26b9b6b08fcb676d1c888bc8">anonymous{ConstantFolding.cpp}::ReadDataFromGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a312de8232fec3e0e128f4a34b7ddc55d">llvm::PPCTargetLowering::SelectAddressRegImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#adaf95509430b29d867f49362e176027d">llvm::PPCTargetLowering::SelectAddressRegImm34</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#adb196c969d6d3af8de3eeeddf2bb9303">selectI64ImmDirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#ac75a07531324f76bfb02992249135cfb">selectI64ImmDirectPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a7da80f756644226c925de9aa4bf77d94">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyinstprinter-cpp/#a63c3f91798717016cc0fbef3b4dc0b34">toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a377cd94b272a4c49477b765611e4a434">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryBitfieldInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a380449a9ad9e4e2d3b6b3fdfa75a64d9">tryBitfieldInsertOpFromOrAndImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="#a03385a25be413259dc4abb7252b3aaa4">tryZExtValue</a>, <a href="#abfeca4698f01ef85e21a3e3061751781">ugt</a>, <a href="#afe03273b7efa986834cca7b9899a686b">ult</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>, <a href="#a825a8dca80ee195760b908990de1a7af">urem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac56427a25d7626e4b748e8fbf1fdf9bb">llvm::Interpreter::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a582723c984e76cf38ba855426a60a235">llvm::Interpreter::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a39600b19581391dccc382a54d6b79be2">llvm::Interpreter::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#adaccb8a2292bd0d7fecec1c16d177cd3">llvm::Interpreter::visitShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a0b1eb53b30ddeb8ebdccc60c0837300f">walkToAllocaAndPrependOffsetDeref</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### popcount {#a27ad8ac0b3b15a21f86c5f89e0c9cdd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::popcount ()</td>
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

<p>Count the number of bits set.</p>


<p>This function is an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> version of std::popcount. It counts the number of 1 bits in the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>0 if the value is zero, otherwise returns the number of set bits.</p></dd>
</dl>


<p>Definition at line 1649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a53f06c06e81412900ac140caaf764ff8">foldSwitchToSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9b1fee580716dee9404fc4e20c486392">llvm::X86TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a6b9321187f70bb8fc4c103af466f6c21">llvm::X86TTIImpl::getReplicationShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae63a6d9d535be11dc640352ea48b6ed">llvm::AArch64TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="#a893a459d66560dde653d7c598978edd4">isOneBitSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a380449a9ad9e4e2d3b6b3fdfa75a64d9">tryBitfieldInsertOpFromOrAndImm</a>.</p>

</div>
</div>

### trySExtValue {#ae30d62aebec681aceb655de2489f12ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; llvm::APInt::trySExtValue ()</td>
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

<p>Get sign extended value if possible.</p>


<p>This method attempts to return the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> as a sign extended int64_t. The bitwidth must be &lt;= 64 or the value must fit within an int64_t. Otherwise no value is returned.</p>


<p>Definition at line 1554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a> and <a href="#a9f78d7e839322a6bfc0c665d29052242">getSignificantBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7c0a683d5c4984e6d58f5f3809ff6ec3">llvm::getExpressionForConstant</a>.</p>

</div>
</div>

### tryZExtValue {#a03385a25be413259dc4abb7252b3aaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::APInt::tryZExtValue ()</td>
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

<p>Get zero extended value if possible.</p>


<p>This method attempts to return the value of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> as a zero extended uint64_t. The bitwidth must be &lt;= 64 or the value must fit within a uint64_t. Otherwise no value is returned.</p>


<p>Definition at line 1532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a> and <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ade6253c0c19609ec9c632e60e08896fb">mayLoopAccessLocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Conversion Functions

### bitsToDouble {#acda0d1f0e4b7b739aff9601d8b4ef4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::APInt::bitsToDouble ()</td>
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

<p>Converts <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits to a double.</p>


<p>The conversion does not do a translation from integer to double, it just re-interprets the bits as a double. Note that it is valid to do this on any bit width. Exactly 64 bits will be translated.</p>


<p>Definition at line 1700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3d43c52f31748261cbdd0e2b0bbad94a">llvm::detail::IEEEFloat::convertToDouble</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f470dbe853f135f9dc2cf67d6f2e8fe">llvm::convertToNonDenormSingle</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>.</p>

</div>
</div>

### bitsToFloat {#aaefac1a605f4e104e7c7a20ab0856889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::APInt::bitsToFloat ()</td>
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

<p>Converts <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits to a float.</p>


<p>The conversion does not do a translation from integer to float, it just re-interprets the bits as a float. Note that it is valid to do this on any bit width. Exactly 32 bits will be translated.</p>


<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3ee96d60e840c18bbd08398261142ad7">llvm::detail::IEEEFloat::convertToFloat</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>.</p>

</div>
</div>

### byteSwap {#ace0bd40e4bee1851ebebb276178d65fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::byteSwap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a byte-swapped representation of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p></dd>
</dl>


<p>Declaration at line 1680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="#a5fa938f247b20cccc87cc8a6e5d20aa6">getNumWords</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae3ba7f841807b297e7c28874c285f538">foldBitwiseLogicWithIntrinsics</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>.</p>

</div>
</div>

### doubleToBits {#ac174a45e376a00ec9b2e9e8730f982c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::doubleToBits (double V)</td>
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

<p>Converts a double to <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits.</p>


<p>The conversion does not do a translation from double to integer, it just re-interprets the bits of the double.</p>


<p>Definition at line 1722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a8aa9aea599b4c595c1ed9b8aa676895d">llvm::detail::IEEEFloat::IEEEFloat</a>.</p>

</div>
</div>

### floatToBits {#a4b160c2704ee3819d8fda70345b4d19f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::floatToBits (float V)</td>
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

<p>Converts a float to <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> bits.</p>


<p>The conversion does not do a translation from float to integer, it just re-interprets the bits of the float.</p>


<p>Definition at line 1730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#adc40250b6f1e913ab361a17c2ca02e43">llvm::detail::IEEEFloat::IEEEFloat</a>.</p>

</div>
</div>

### print {#a48334652c819dffc9a133ce268693858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2281 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a> and <a href="#aff8bfdb27a0027b84b0c3580c0d9f530">toString</a>.</p>

</div>
</div>

### reverseBits {#a7b8b4253b618610eb5cb497b4104ebc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::reverseBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the value with the bit representation reversed of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p></dd>
</dl>


<p>Declaration at line 1684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#af338e23a90c301183968435e80cd6a27">lshrInPlace</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae4ac99da28c2d9f17b8e8864697148f1">llvm::reverseBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/demandedbits-cpp/#ab0b0d4186175ae749e0fa20fca628699">determineLiveOperandBitsAddCarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#ae3ba7f841807b297e7c28874c285f538">foldBitwiseLogicWithIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>.</p>

</div>
</div>

### roundToDouble {#ae5dfa02c3403baa3d057b6264eed687d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double APInt::roundToDouble (bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double value.</p>


<p>This function converts this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double.</p>



### The layout for double is as following (IEEE Standard 754): {#autotoc_md68}


<table class="doxyTable">
<tr>
<th>Sign Exponent Fraction Bias</th>
</tr>
<tr>
<td>1[63] 11[62-52] 52[51-00] 1023</td>
</tr>
</table>

<hr/>


<p>Declaration at line 1687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#aaf70a90533b469062634730e27f6577d">APINT_BITS_PER_WORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/complexdeinterleavingpass-cpp/#a2762113571c7956c9818c452b2d256ae">isNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a23b5d5d53d9a7a8d473b61cd78b1a543">pVal</a>, <a href="#aca8fce65eb69a82aa10a635e2e79877a">sext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a54dfe8ba0babf979f348de572e312836">llvm::APIntOps::RoundAPIntToDouble</a> and <a href="#aae8a216000ce553ed7e8d4c3a9bd1542">signedRoundToDouble</a>.</p>

</div>
</div>

### roundToDouble {#a74c7bc4d4687802bcd1e3628fcbec03f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::APInt::roundToDouble ()</td>
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

<p>Converts this unsigned <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double value.</p>

<p>Definition at line 1690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a74c7bc4d4687802bcd1e3628fcbec03f">roundToDouble</a>.</p>


<p>Referenced by <a href="#a74c7bc4d4687802bcd1e3628fcbec03f">roundToDouble</a>.</p>

</div>
</div>

### signedRoundToDouble {#aae8a216000ce553ed7e8d4c3a9bd1542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::APInt::signedRoundToDouble ()</td>
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

<p>Converts this signed <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a double value.</p>

<p>Definition at line 1693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#ae5dfa02c3403baa3d057b6264eed687d">roundToDouble</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#aaa82772aeb64a449b2fd9fc56b6b2f4b">llvm::APIntOps::RoundSignedAPIntToDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad2de5c5de0ed0d2032d6990969cb97b8">llvm::APIntOps::RoundSignedAPIntToFloat</a>.</p>

</div>
</div>

### toString {#aff8bfdb27a0027b84b0c3580c0d9f530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APInt::toString (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned Radix, bool Signed, bool formatAsCLiteral=false, bool UpperCase=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool InsertSeparators=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to a string and append it to Str.</p>


<p>Str is commonly a <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>. If Radix &gt; 10, UpperCase determine the case of letter digits.</p>


<p>Declaration at line 1663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac0e942dde4b113c4c0b1fd76333db93a">getBoolValue</a>, <a href="#ada7af1de63a848b2f452d63958de39fe">getRawData</a>, <a href="#af2daa0ee117afefed4c82eee55bf97b7">getSExtValue</a>, <a href="#a217e0207d9cc8e046c2dccbf0e4bb198">getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="#a49cd5939942c6665aba4cae8c220dff1">isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af338e23a90c301183968435e80cd6a27">lshrInPlace</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a8376734f311508662dd7e737752e5953">negate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a> and <a href="#a0f0a665210e453bb16b4bf1861dbdd58">udivrem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a3fa2c7609bef28d6ba5bdb542fb40f2d">llvm::ExpressionFormat::getMatchingString</a>, <a href="#a48334652c819dffc9a133ce268693858">print</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#ab42308e3ef28ca0123864b24eeb98b5d">llvm::APSInt::toString</a>.</p>

</div>
</div>

### toStringSigned {#afbbb8a6117fc93aa80fabdeb82f73cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::toStringSigned (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned Radix=10)</td>
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

<p>Considers the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to be signed and converts it into a string in the radix given.</p>


<p>The radix can be 2, 8, 10, 16, or 36.</p>


<p>Definition at line 1675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a7206d13e3a41147c732071c64bd84825">toString</a>.</p>


<p>Referenced by <a href="#aa248cd211bcff0f457bf69b596805302">dump</a>.</p>

</div>
</div>

### toStringUnsigned {#a3591391b56f014b632b3af30b86dc51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APInt::toStringUnsigned (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned Radix=10)</td>
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

<p>Considers the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> to be unsigned and converts it into a string in the radix given.</p>


<p>The radix can be 2, 8, 10 16, or 36.</p>


<p>Definition at line 1669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a7206d13e3a41147c732071c64bd84825">toString</a>.</p>


<p>Referenced by <a href="#aa248cd211bcff0f457bf69b596805302">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mathematics Operations

### abs {#a38e964f0cadf077725453884734a6c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::abs ()</td>
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

<p>Get the absolute value.</p>


<p>If *this is &lt; 0 then return -(*this), otherwise *this. Note that the "most negative" signed number (e.g. -128 for 8 bit wide <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>) is unchanged due to how negation works.</p>


<p>Definition at line 1773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a6804d9caf15411f55e7b9e9f397f0422">isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7e46711e88afd58c383ff1f504a173f5">combineSelectOfTwoConstants</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3932d8d07bd52eacf62adc249ac2f926">findGCD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aa4ab138d4aa4beb5e35a996d3bd21765">gcd</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a3fa2c7609bef28d6ba5bdb542fb40f2d">llvm::ExpressionFormat::getMatchingString</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### ceilLogBase2 {#a392d67031c5429420ac0b46478fe893e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::ceilLogBase2 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the ceil log base 2 of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p></dd>
</dl>


<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>.</p>

</div>
</div>

### exactLogBase2 {#a6f1d5427c61a0f0159f6e85f41944c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::APInt::exactLogBase2 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the log base 2 of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> if its an exact power of two, -1 otherwise</p></dd>
</dl>


<p>Definition at line 1761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#ad1b0513de876d1c85cf6268ca21b2c86">isPowerOf2</a> and <a href="#aae3b959a0a2981340fd03c29f528f2f0">logBase2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a069a4c1f69273f1402ccb7a407e9ee4c">foldAddToAshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a1a4e02c3247bc8b4134b91e707d6c146">llvm::LoongArchDAGToDAGISel::selectVSplatUimmPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>.</p>

</div>
</div>

### logBase2 {#aae3b959a0a2981340fd03c29f528f2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APInt::logBase2 ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the floor log base 2 of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p></dd>
</dl>


<p>Definition at line 1739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="#a6f1d5427c61a0f0159f6e85f41944c5c">exactLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a60d8db999d3887919b031cd5b85db10e">foldICmpShlLHSC</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="#ab9178a079b54667289f598db5b052ade">getBitsNeeded</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af46fd5126112a587bb12f09b1c0e385b">llvm::ConstantExpr::getExactLogBase2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#acf625a32c19c58380ada30e43781d0ae">anonymous{AArch64PostLegalizerLowering.cpp}::getExtMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9ebdafbae1fdc29135b25d537a89cd61">isEXTMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="#a0ee171002efe1360b112e2bc4bd0674f">nearestLogBase2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4ba6b9afcc5b700d4c09664b5fa009d9">llvm::ARMTargetLowering::PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>.</p>

</div>
</div>

### multiplicativeInverse {#aba59baafccd4c4796301b857df3c40c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::multiplicativeInverse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the multiplicative inverse of an odd <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> modulo 2^BitWidth.</p></dd>
</dl>


<p>Declaration at line 1780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1248 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aea5f26deda5ef97e02f6afc57c0c3920">isOne</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af5d3388e53cb2767927dba7c18c64a00">llvm::CombinerHelper::buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### nearestLogBase2 {#a0ee171002efe1360b112e2bc4bd0674f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned APInt::nearestLogBase2 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the nearest log base 2 of this <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. Ties round up.</p></dd>
</dl>


<p>NOTE: When we have a BitWidth of 1, we define:</p>


<p>log2(0) = UINT32_MAX log2(1) = 0</p>


<p>to get around any mathematical concerns resulting from referencing 2 in a space where 2 does no exist.</p>


<p>Declaration at line 1757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a49cd5939942c6665aba4cae8c220dff1">isZero</a> and <a href="#aae3b959a0a2981340fd03c29f528f2f0">logBase2</a>.</p>

</div>
</div>

### sqrt {#af48b6a9423c3b72b453f0eb881129d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::sqrt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the square root.</p>

<p>Declaration at line 1768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a628da9238224184ed7085b6830c1fcff">APInt</a>, <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3015474e70e59c0a3ed4f9f0e8644b75">getActiveBits</a>, <a href="#a5ed1d98c99f36cde30cb052c78fa5e35">isSingleWord</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>, <a href="#acb9c55b6986369948507ca5241b4e411">shl</a>, <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>, <a href="#a05d674becc60ba4ef8cd4dd4d38ac27a">udiv</a>, <a href="#aca14d9ec64ba4ab7fb2cef37c57d9ce4">ule</a> and <a href="#a545e8d5dfa1688acea0d0e275b03682f">ult</a>.</p>


<p>Referenced by <a href="#af48b6a9423c3b72b453f0eb881129d3b">sqrt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Value Generators

### getAllOnes {#a071e8d814b2b30b02544fad964227b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getAllOnes (unsigned numBits)</td>
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

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> of a specified width with all bits set.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a9312eb1fba50adaeda024f10b9919136">WORDTYPE_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a62c931c6a10de7e95a8ac7d79b843770">llvm::analyzeKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#adc0733404e2b3c8b3bd7edb2e9021fae">llvm::ConstantRange::binaryNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a813af4f625c1b136c991637d08bf9087">llvm::buildSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abec3ca8e4e6dd78a431e82eaae53b5bd">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a7b6c32da7b6a47b962a5bdce5a3bbc75">canTryToConstantAddTwoShiftAmounts</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e3e38f27d866ed7730e8e30fc3877cf">combineAddOfPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0e0d5fc4a01d9f412064a5448052330">combineBEXTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a886d3292e22e113b2f04c1c35811bd0c">combineKSHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad27c58fe609558af3d02f6eb59c0d075">combinePDEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a92cb7f91737deedc3c70fb0ec0b70807">combinePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af72da135a7e8a925ffa9fbbb4ecf0b1f">combinePredicateReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae9b4450314b8e4acb9f937389b349fce">combineShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a619d32c3e94bf8ee0348f9611590dd90">combineTESTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aca03795fe4ea383d28dcf4433f994485">combineVectorCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a45f59ac6b0a55fb1b92f4b3bfd5ce327">combineVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34bed5ad51ce8926c80d2156b6b0b591">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad740a3de60e818893b8660301726f776">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02b7c84489e3efc2bf97e054ffd11332">llvm::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5eb6c8098e2277b24f748ca77fa81791">ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac01c66c983bfbac05a0cf903f08417df">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#acad77d3e231789845c6639b23249bed7">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a7fbae83b06276268455de0368194f94a">defaultComponentBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1e71f36e9936f126265e383fd67440f7">findDemandedEltsByAllUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a777bef8b513df8776aec8f3cf9ce066b">llvm::InstCombinerImpl::foldVectorSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1b134112bb3b8986d8082832a16eab6f">llvm::SelectionDAG::getAllOnesConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a581d4a580ff88de698682f78a554b2fa">llvm::APFloat::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a5f65ab13a2645935d21a119b722a55a1">getBitcastWiderVectorElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#a35c645afbcec5f66b70f92c4cd8e8be4">llvm::DemandedBits::getDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#a34469f29a61b3bcb61f8e2a9af25be65">llvm::DemandedBits::getDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a596e1e2a1e7f415e9df16dc4550f8fd9">getDemandedBitsLHSMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9ae600999d4379b1d674e0abeaec43de">getDemandedSrcElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4836b23626e1d7b24f8bb84be3a55667">getHopForBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#ab3bd16b0bda0d7c3290bf9ba7d095400">llvm::GISelKnownBits::getKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ab1577d309005660f819a91c8268ec001">llvm::X86TTIImpl::getMaskedMemoryOpCost</a>, <a href="#a331d69b5f93e47e7c596062b77dd5913">getMaxValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#af2e33549eacd75ef7ee25e37b46e5f54">getRangeForIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#acf005731b7353e3224b7742a356ffb0e">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a925361ad88aa02b69d20adaaab9f4f33">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalarizationOverhead</a>, <a href="#a562c9513409b74f02cb3a5c9bae672ea">getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a093fa508bcdccd1b9172fc87797c8cd6">llvm::SelectionDAG::getSplatSourceVector</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1d322fa0d9ca562c6b20cac2d8a0a5dd">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae903428eabca0546973c2695d608bbc9">getTargetShuffleInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1510df8e6724eea06fe764e48a5e6338">llvm::SelectionDAG::getValidMaximumShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2811a9d5b02b367167de0384fe2f173d">llvm::SelectionDAG::getValidMinimumShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8f6d0f4a96899cc73faa3a17659409a">llvm::SelectionDAG::getValidShiftAmount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb4484ddcdad2576d97870230db05ed8">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a516614c2855a763aa9eef67c6da888e0">llvm::isConstOrConstSplatFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8947affefbaa5e1099d7ba6bd401f05a">llvm::SelectionDAG::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9afd47568010f063c6ca4ed6473db03">llvm::isKnownNonEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa5950e8440c6d4ecdaf950affa6a8e97">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a31f002d1380244ed0e6fbd6af6d65881">lowerShuffleAsElementInsertion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ac436d2178c40d1c44632daa737b39323">narrowSDivOrSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a960012b61a9977dc7c2d3af3943da953">llvm::AArch64TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a0a402f51b5d937bbd3accc7bb354ab">llvm::possiblyDemandedEltsInMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a655de0b9ba51c463a01a23651abb0cf7">llvm::ARMTargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afcc877a26419c2aef195256bc0aa01e3">llvm::InstCombinerImpl::SimplifyDemandedInstructionBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a07384ea9d8fdfb208574ff59715e5be2">llvm::APFixedPoint::toString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a58e687cb25ed94c378fc444895422a13">trimTrailingZerosInVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3cff897f0ed479f872425600e0800701">llvm::LegalizationArtifactCombiner::tryCombineZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getBitsSet {#a46ceedee591f92727b85641794a96061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getBitsSet (unsigned numBits, unsigned loBit, unsigned hiBit)</td>
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

<p>Get a value with a block of bits set.</p>


<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has a contiguous range of bits set. The bits from loBit (inclusive) to hiBit (exclusive) will be set. All other bits will be zero. For example, with parameters(32, 0, 16) you would get 0x0000FFFF. Please call getBitsSetWithWrap if <span class="doxyComputerOutput">loBit</span> may be greater than <span class="doxyComputerOutput">hiBit</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the intended bit width of the result</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">loBit</td>
<td class="doxyParamItemDescription"><p>the index of the lowest bit set.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">hiBit</td>
<td class="doxyParamItemDescription"><p>the index of the highest bit set.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value with the requested bits set.</p></dd>
</dl>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#acb95d5d8e87df053e1b53e2ec60de4b6">setBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a70c5c088223e73d71c8971f218db7985">combineToExtendBoolVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a843e5745d85df82681dadbe26ce86ca2">computeShlNSWWithNNegLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9b1fee580716dee9404fc4e20c486392">llvm::X86TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1c34ea579237aedce7149724afc490ab">insert1BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a5ac801ed9e1a056f66831b7f0129fdb0">tryToMergePartialOverlappingStores</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>.</p>

</div>
</div>

### getBitsSetFrom {#aeaf22e8d92fd978a5eca9ab031994399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getBitsSetFrom (unsigned numBits, unsigned loBit)</td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has a contiguous range of bits set.</p>


<p>The bits from loBit (inclusive) to numBits (exclusive) will be set. All other bits will be zero. For example, with parameters(32, 12) you would get 0xFFFFF000.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the intended bit width of the result</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">loBit</td>
<td class="doxyParamItemDescription"><p>the index of the lowest bit to set.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value with the requested bits set.</p></dd>
</dl>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a286d4fa2a50c9ac6ac3a8069cccfcd0c">setBitsFrom</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad34d9541b1000d244dd78e0cf23b45ea">combine_CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaab5068203f7eda4cf8a53182aae5cdd">combineAddOfBooleanXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5a87447416046730b266c20001561df4">combineDeMorganOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#a1d8f39cf98f0412e82e2f5bd03a09b99">extractBits</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#abbd64fe331cf0d150d28e127653d700c">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::fillUpExtensionSupportForSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a596e1e2a1e7f415e9df16dc4550f8fd9">getDemandedBitsLHSMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a958032a0f481716e224596f732f55d35">getTruncatedUSUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac60e4a050606558fee92cecf8c6fc905">isCTTZTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaf26b08c5135c5ae2bc71189dff29b79">LowerPARITY</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a05b5cba8cfdcec8f2d1dafb06fb63ab5">llvm::RISCVDAGToDAGISel::selectZExtBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a62222502f5be2dd8e300b48469aeab4f">llvm::ConstantRange::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5956dd38d2c4e11a90da91035b52096d">tryDemorganOfBooleanCondition</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>.</p>

</div>
</div>

### getBitsSetWithWrap {#af3bee3e462a14abdf3858c354a5cd222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getBitsSetWithWrap (unsigned numBits, unsigned loBit, unsigned hiBit)</td>
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

<p>Wrap version of getBitsSet.</p>


<p>If <span class="doxyComputerOutput">hiBit</span> is bigger than <span class="doxyComputerOutput">loBit</span>, this is same with getBitsSet. If <span class="doxyComputerOutput">hiBit</span> is not bigger than <span class="doxyComputerOutput">loBit</span>, the set bits "wrap". For example, with parameters (32, 28, 4), you would get 0xF000000F. If <span class="doxyComputerOutput">hiBit</span> is equal to <span class="doxyComputerOutput">loBit</span>, you would get a result with all bits set.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a97d7462ee50c7b2ad49c08d8661f52d2">setBitsWithWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>.</p>

</div>
</div>

### getHighBitsSet {#adcb96bd09d7c75c7669fa5f9d1190899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getHighBitsSet (unsigned numBits, unsigned hiBitsSet)</td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has the top hiBitsSet bits set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the bitwidth of the result</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">hiBitsSet</td>
<td class="doxyParamItemDescription"><p>the number of high-order bits set in the result.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a2780c5606880394d3f07cd2079a27697">setHighBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3d3ed8206aabad62293aeddd444bab9f">canEvaluateZExtd</a>, <a href="#aac76bff09195240a482b319136ab6144">clearLowBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2336d9f0305e57b22c5be16c73caa">combineMulToPMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a618caf6a690e2208acbfa1b7668df3a2">computeShlNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae9b6e09822fd0b670d93487058bea45">ConstantBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa4a1701790033b3d84938d44c913da11">EmitCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4f55d7706c3a7a5983907b84d98ddbad">llvm::InstCombinerImpl::foldICmpEqIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a06857829ce5f8610c6c44e45545212f4">foldMaskAndShiftToScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a2db21ddc2a6983ec696cd972ad43031e">isFPSatMinMaxPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a2bfff40c1bfc02a21a5ed0b64a99f8a2">llvm::AArch64TTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#aecdf309a14a1e82cc28f67e6f45745b5">isTruncWithZeroHighBitsInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aecdf309a14a1e82cc28f67e6f45745b5">isTruncWithZeroHighBitsInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1278833d086e5f200fcc7e576d2efa17">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3b5afe10336a33630e00f86fab07c87">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae061deb7e1ce634d402090342aeccda7">LowerShiftByScalarImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aec76b73c15365e949f7322e371e6471b">llvm::AMDGPUTargetLowering::LowerUDIVREM64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac96fedf3e39b8aa423770a2ff05b7991">matchShuffleWithPACK</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8e96878324f2ca0f847e369f839cfd23">llvm::ARMTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a153c39776118fd1d5493774b10b9c5ae">SaturateWidenedDIVFIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2f569000b0bf158c11f67de0f6d308fe">selectUmullSmull</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a42ae88f3d9dbf2cd35c379cba4ef976f">llvm::LoongArchDAGToDAGISel::selectZExti32</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a9c8872e25eeddcc398a41e003e7c3f55">llvm::ConstantRange::signExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae43089dd5a18812d93f8542cc0be6e16">llvm::ARMTTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#afd74672cec2bec4f18c103c4cb7823d4">simplifyUnaryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### getLowBitsSet {#ad960e1ff48d25c382b6d28e7961f074e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getLowBitsSet (unsigned numBits, unsigned loBitsSet)</td>
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

<p>Constructs an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> value that has the bottom loBitsSet bits set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">numBits</td>
<td class="doxyParamItemDescription"><p>the bitwidth of the result</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">loBitsSet</td>
<td class="doxyParamItemDescription"><p>the number of low-order bits set in the result.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#ade8e20ecea1091e835395746448e262e">setLowBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2b99673a7e084ea8e75699f04b5f683a">buildBitFieldInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a26edc3c3cae5a3f4d6ddd7f628b98c45">llvm::MachineIRBuilder::buildZExtInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a508969c8bd53dfda53fb8670e9df1194">clampDynamicVectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#ab16bdfa03e042a77b677e032fa495959">clampVectorIndex</a>, <a href="#aef3f66072750c56846c44817e7336a3d">clearHighBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afab7e380356e4b22d23f87fa2f45daf9">combineBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af72da135a7e8a925ffa9fbbb4ecf0b1f">combinePredicateReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9ac1db32c7172ebb71d45a6ece209b53">combineVEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a80a69d92372f6bfde4ea47c1b55b84bb">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateZEXTi</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#a1d8f39cf98f0412e82e2f5bd03a09b99">extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4f55d7706c3a7a5983907b84d98ddbad">llvm::InstCombinerImpl::foldICmpEqIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7df35aaa0732f4b23e5458034a2c29d1">llvm::InstCombinerImpl::foldICmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="#a0fa9845f80fa0642b31c238f4ab0d5ef">getLoBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a958032a0f481716e224596f732f55d35">getTruncatedUSUBSAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a61c6720db574963baad9d12d32a3c6ad">getValueFromICmpCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a02127bae19ef433c1233c696317a8868">llvm::SelectionDAG::getVPZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6a52e913507400fcde94fd2e023a149c">llvm::SelectionDAG::getZeroExtendInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aeed184a32cfc1dd279753d4a633bfba1">lowerBuildVectorViaPacking</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad1a2f745da12a487f957812160298aa7">LowerEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9dc8c9b527c43cc36ac86886d18f00e4">llvm::LegalizerHelper::lowerFCopySign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1278833d086e5f200fcc7e576d2efa17">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3b5afe10336a33630e00f86fab07c87">LowerMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae061deb7e1ce634d402090342aeccda7">LowerShiftByScalarImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abfd7c524b17cd29c6470d1780f06d460">matchRotateSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8e96878324f2ca0f847e369f839cfd23">llvm::ARMTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a42aa092f2811f72cad69b42cc2e4bb64">llvm::ARMTargetLowering::PerformIntrinsicCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1d0f22bfc290fd2cb53c9486286359df">PerformPREDICATE_CASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af4aeb38e252532a5362ac68998d0af93">performTBISimplification</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7e495837f173dea1e6919b589d315f67">performVectorShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7da18013c41f68948709a964437238bf">performZExtUZPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a153c39776118fd1d5493774b10b9c5ae">SaturateWidenedDIVFIX</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a9c8872e25eeddcc398a41e003e7c3f55">llvm::ConstantRange::signExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae43089dd5a18812d93f8542cc0be6e16">llvm::ARMTTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#abbdb66ef7655ebae91e2bbfab4320f23">simplifyMul24</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#ad67049bfa2bb6a438fc450e018cd0dd0">simplifyX86VPERMMask</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#adc96b14a52d48d045a0a9d2cc9459a62">llvm::X86TargetLowering::targetShrinkDemandedConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### getMaxValue {#a331d69b5f93e47e7c596062b77dd5913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getMaxValue (unsigned numBits)</td>
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

<p>Gets maximum unsigned value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for specific bit width.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a071e8d814b2b30b02544fad964227b8e">getAllOnes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a1f1be83c0efdaff4af051b7a45faaba7">llvm::KnownBits::ashr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5704370a1379cfd0062d47b73ba65cb0">llvm::cannotBeMaxInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4c3a3d6e30e1512fd3b160cae4025f26">llvm::ConstantRange::castOp</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac3bb0fae6ff72b015a07fe80a33339c8">detectSSatUPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#abc78591e933ad7d53f7fd4d8b9b4c096">detectUSatUPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a6354a279f2a03839323aebcc1fe3e43a">foldBoxMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a95dbb8a4fbe44ddeb43a6de9ac218bd4">llvm::InstCombinerImpl::foldICmpAddOpConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#a11bb0046d2dde7ed854e2515cbc6b191">getIdentityValueForAtomicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a5cba4d26a4ef4ecf1cea7faac29b1786">llvm::APSInt::getMaxValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a221f053d5107888218e536fe5f1f457c">llvm::getMinMaxLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#abef1794878bfc0342648f40451a3b8d8">getRangeForAffineARHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#af2e33549eacd75ef7ee25e37b46e5f54">getRangeForIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a4b6b84b97c4ee2f0023bfd66097ca424">llvm::MinMaxIntrinsic::getSaturationPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a17e35fd9a6e590c201fd05105589ce47">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab7f67c2ed8b2799c64ec64ca31d75c60">llvm::ConstantRange::getUnsignedMax</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a688f2c4ca99eb7f935cab42c4f6398e7">llvm::ConstantRange::isSizeLargerThan</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a3ee5abf8664d1ea66e6d93fd6cf61065">llvm::LegalizerHelper::lowerFPTOINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a00a7edf44feca96dfa6abdc4ae5d705d">llvm::LegalizerHelper::lowerShlSat</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a5c34f40ce539320222a15a88ebcef716">llvm::KnownBits::lshr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a7e7e5e776b7f30a4522e2d415efe1dfb">makeExactMulNUWRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#abd85d08f35600dd19615a1efe9cacb1d">llvm::KnownBits::mul</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ae9ffa8b50ca6095202b2e8e7686c10b8">llvm::KnownBits::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>, <a href="#a21ede0a7cd71b89d7f2f8976321bab08">truncUSat</a>, <a href="#ab4c04665274d4f30d732639dc055821c">uadd_sat</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a96120d4062fabb503b1b92401e54d14f">llvm::KnownBits::udiv</a>, <a href="#acf4d36ebf88039604b73d3527506c3ed">umul_sat</a>, <a href="#a236aa749101900bc9e8e6cd108bdec6a">ushl_sat</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a267fd27cb9e177fa5f48cbb8828339a1">llvm::ScalarEvolution::willNotOverflow</a>.</p>

</div>
</div>

### getMinValue {#a65a6479206acd4113b8aa1c0fbc2158c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getMinValue (unsigned numBits)</td>
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

<p>Gets minimum unsigned value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for a specific bit width.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aef5f1583da883ba28cb113c02d29f1d9">llvm::cannotBeMinInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4c3a3d6e30e1512fd3b160cae4025f26">llvm::ConstantRange::castOp</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#a11bb0046d2dde7ed854e2515cbc6b191">getIdentityValueForAtomicOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a221f053d5107888218e536fe5f1f457c">llvm::getMinMaxLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0a441f49b4e67f435392c937e056d2d4">llvm::APSInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a4b6b84b97c4ee2f0023bfd66097ca424">llvm::MinMaxIntrinsic::getSaturationPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4d69e164b5fb0f73a15a07119c4302f7">llvm::ConstantRange::getUnsignedMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aff0515f214b4d4e5d5a3197b11d5eacc">getUnsignedOverflowLimitForStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a3ee5abf8664d1ea66e6d93fd6cf61065">llvm::LegalizerHelper::lowerFPTOINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa0830ec6778859b4abb3e8bf0b9e0e38">llvm::ConstantRange::makeAllowedICmpRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a7e7e5e776b7f30a4522e2d415efe1dfb">makeExactMulNUWRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a96120d4062fabb503b1b92401e54d14f">llvm::KnownBits::udiv</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a267fd27cb9e177fa5f48cbb8828339a1">llvm::ScalarEvolution::willNotOverflow</a>.</p>

</div>
</div>

### getOneBitSet {#aec662ee6ab1490a4cabebf2812e5b9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getOneBitSet (unsigned numBits, unsigned BitNo)</td>
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

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> with exactly one bit set in the result.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a33f9f862dca8ee0f23bff5941bf433d8">setBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad7019e6968b4004f00694d89e161625c">combineShiftAnd1ToBitTest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a188ce906e2196ffe71bda27b6cfe9d55">extractShiftForRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4f55d7706c3a7a5983907b84d98ddbad">llvm::InstCombinerImpl::foldICmpEqIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7df35aaa0732f4b23e5458034a2c29d1">llvm::InstCombinerImpl::foldICmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ac2cf93c95893f413324a4645fc39bb1a">llvm::ScalarEvolution::getPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac1fce2baaba15c35a2bb18563ef08678">getStrideAndModOffsetOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abec179193cc8369e33418e87154d7d04">lowerFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe950951aec4aa71b14f89b89d26eae0">lowerVectorFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acc354c12306e08991c73849216e09f78">lowerVectorStrictFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acac5641e821739845b8c56fa071f44ca">llvm::ConstantRange::makeMaskNotEqualRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aa24a3daa081cfbda3fe1a4b3c0e32433">MatchBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#aae7060f1dababae7ea60ae22eb9e9c6b">matchBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2caf0087e5ae1170754a8a4503df9a98">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab9e94d7f7d74b11670e87904ed30dc2a">llvm::APIntOps::SolveQuadraticEquationWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a636ddf018d314a1d73f98e2fa4efbafb">llvm::ConstantRange::zeroExtend</a>.</p>

</div>
</div>

### getSignedMaxValue {#a562c9513409b74f02cb3a5c9bae672ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getSignedMaxValue (unsigned numBits)</td>
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

<p>Gets maximum signed value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for a specific bit width.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="#a155466c9ea0a2bd00e09c62fdce2c052">clearBit</a> and <a href="#a071e8d814b2b30b02544fad964227b8e">getAllOnes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5704370a1379cfd0062d47b73ba65cb0">llvm::cannotBeMaxInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4c3a3d6e30e1512fd3b160cae4025f26">llvm::ConstantRange::castOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af2bbdc92f4c64587511d192d903ca743">combineMinMaxReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aed133c19018de0508c5d71e802f36ef4">detectSSatSPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a95dbb8a4fbe44ddeb43a6de9ac218bd4">llvm::InstCombinerImpl::foldICmpAddOpConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a5bdf52f90e0c8cf28eff0caf18654e0f">foldOverflowingAddSubSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#a11bb0046d2dde7ed854e2515cbc6b191">getIdentityValueForAtomicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a821a7e22708e349e6362496137fe5238">llvm::ConstantExpr::getIntrinsicIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a5cba4d26a4ef4ecf1cea7faac29b1786">llvm::APSInt::getMaxValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a221f053d5107888218e536fe5f1f457c">llvm::getMinMaxLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#af2e33549eacd75ef7ee25e37b46e5f54">getRangeForIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a574647158b42f4d85c9f57f1a474452b">getRangeForSelectPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a4b6b84b97c4ee2f0023bfd66097ca424">llvm::MinMaxIntrinsic::getSaturationPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ac45b1557ea43684a07058cb74396c435">llvm::ConstantRange::getSignedMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a09b3e808d3a4c48865a0b8cb59487f7d">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::HandleFixupError</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad9601b4bf1ad70c2fe4534ecf69c165f">LowerADDSAT_SUBSAT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a813d1719803526d9839b4ae8d0a6b93d">llvm::LegalizerHelper::lowerAddSubSatToMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a87cbc5eaa4440f62bdad70cce2296f3b">llvm::LegalizerHelper::lowerFAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac05773b4901540ea7eaeb572cce9b00d">LowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4f2247785b2cfa91b42485591c4a71df">lowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abc7ab426f010b3402a1e9e6a9fef1327">LowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a618e1a8b97a48a4cf1d6b8941823be50">lowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a3ee5abf8664d1ea66e6d93fd6cf61065">llvm::LegalizerHelper::lowerFPTOINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a00a7edf44feca96dfa6abdc4ae5d705d">llvm::LegalizerHelper::lowerShlSat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa69e07fa7ca7953d971574873d5ec5c2">makeExactMulNSWRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="#a3c1e0381aeb551ad0ba58effe9232f97">sadd_sat</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="#a36f62de4b8b82d2f73fb4efda79954f0">smul_sat</a>, <a href="#ab3ed902943113e485a80dff901f36494">sshl_sat</a>, <a href="#af888cb3cadd9a4e5f422c96e5674de88">ssub_sat</a>, <a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a267fd27cb9e177fa5f48cbb8828339a1">llvm::ScalarEvolution::willNotOverflow</a>.</p>

</div>
</div>

### getSignedMinValue {#a8f877403433892e14ff0c692cbe9efdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getSignedMinValue (unsigned numBits)</td>
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

<p>Gets minimum signed value of <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> for a specific bit width.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a33f9f862dca8ee0f23bff5941bf433d8">setBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a6c8069837b71990713a285cb590a0eb2">llvm::ConstantRange::abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef5f1583da883ba28cb113c02d29f1d9">llvm::cannotBeMinInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a94bc2ff14a27583461b207499f426ee2">canonicalizeForInvariantConditionInjection</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4c3a3d6e30e1512fd3b160cae4025f26">llvm::ConstantRange::castOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af2bbdc92f4c64587511d192d903ca743">combineMinMaxReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9c1c6dc178ce30e4a6c09f5c08727d65">llvm::KnownBits::computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aed133c19018de0508c5d71e802f36ef4">detectSSatSPattern</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#af5333260b4104fef104ea3459553cae1">anonymous{BasicAliasAnalysis.cpp}::CastedValue::evaluateWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a069a4c1f69273f1402ccb7a407e9ee4c">foldAddToAshr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#aa875b86e81398234a9aa576ab946c76b">foldMinimumOverTrailingOrLeadingZeroCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a5bdf52f90e0c8cf28eff0caf18654e0f">foldOverflowingAddSubSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo/#affa10b6ac03585fea6d8f1832071ebd5">llvm::SignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo/#a6a7ecd0f6bb250280a31e56173931e31">llvm::UnsignedDivisionByConstantInfo::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#a11bb0046d2dde7ed854e2515cbc6b191">getIdentityValueForAtomicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a821a7e22708e349e6362496137fe5238">llvm::ConstantExpr::getIntrinsicIdentity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a221f053d5107888218e536fe5f1f457c">llvm::getMinMaxLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a0a441f49b4e67f435392c937e056d2d4">llvm::APSInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#af2e33549eacd75ef7ee25e37b46e5f54">getRangeForIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a574647158b42f4d85c9f57f1a474452b">getRangeForSelectPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a4b6b84b97c4ee2f0023bfd66097ca424">llvm::MinMaxIntrinsic::getSaturationPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#aed10715d943d3e1b4ca75b585ea96ab8">llvm::RecurrenceDescriptor::getSentinelValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a6c03477d3ea04e382431f02a0f21aa41">llvm::ConstantRange::getSignedMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="#a1e6f0d8dfed0ab631b488a3e6317718e">getSignMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a09b3e808d3a4c48865a0b8cb59487f7d">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::HandleFixupError</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ac689bdce81e76d215f170f7eb3821be3">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleRelationalComparisonExact</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8d91ca7ede308b821f546a33f6625115">impliesPoisonOrCond</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad9601b4bf1ad70c2fe4534ecf69c165f">LowerADDSAT_SUBSAT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aae6d16ec0f044086e929d63d532178bf">llvm::LegalizerHelper::lowerAddSubSatToAddoSubo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a813d1719803526d9839b4ae8d0a6b93d">llvm::LegalizerHelper::lowerAddSubSatToMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a3ee5abf8664d1ea66e6d93fd6cf61065">llvm::LegalizerHelper::lowerFPTOINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a00a7edf44feca96dfa6abdc4ae5d705d">llvm::LegalizerHelper::lowerShlSat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa0830ec6778859b4abb3e8bf0b9e0e38">llvm::ConstantRange::makeAllowedICmpRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#aa69e07fa7ca7953d971574873d5ec5c2">makeExactMulNSWRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#af8daf8a07b3ab8645d4a6524caf57e7b">llvm::ConstantRange::multiplyWithNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ac436d2178c40d1c44632daa737b39323">narrowSDivOrSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#afc7c6cd72afb77dfb9ace19d951bf6c5">processAbsIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="#a3c1e0381aeb551ad0ba58effe9232f97">sadd_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa160a2ac0c31b48c41da949e53cc21b7">llvm::ConstantRange::sdiv</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a9f4c03962b079bed0cd6c59256844bb5">llvm::KnownBits::sdiv</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ab1e4a3ec7de159965bcee94fae9df74b">llvm::ConstantRange::signedAddMayOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae907195afbb8c9442691836e26ac0001">llvm::ConstantRange::signedSubMayOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="#a36f62de4b8b82d2f73fb4efda79954f0">smul_sat</a>, <a href="#ab3ed902943113e485a80dff901f36494">sshl_sat</a>, <a href="#af888cb3cadd9a4e5f422c96e5674de88">ssub_sat</a>, <a href="#afe04819b980f360000f64b1b5487e0a5">truncSSat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a267fd27cb9e177fa5f48cbb8828339a1">llvm::ScalarEvolution::willNotOverflow</a>.</p>

</div>
</div>

### getSignMask {#a1e6f0d8dfed0ab631b488a3e6317718e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getSignMask (unsigned BitWidth)</td>
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

<p>Get the SignMask for a specific bit width.</p>


<p>This is just a wrapper function of <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue()</a>, and it helps code readability when we want to get a SignMask.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#a8f877403433892e14ff0c692cbe9efdf">getSignedMinValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a27302ae9df3143ece2fcd550d6ac9adc">checkSignTestSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af59e4da255e65a90b6c4710be399b9e6">combineAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a19158530c7e8bd08610180be814ec9b1">combinePTESTCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae6535f37686895d8ab294ce06ffe2f15">combineX86GatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#af4bd08b53da1b6b69766e5abf2462cc0">computeShlNSWWithNegLHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5f0becba6abfe541dd2df2475c52268f">foldAndToUsubsat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a596e1e2a1e7f415e9df16dc4550f8fd9">getDemandedBitsLHSMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa411af5653e9ed6cd4f664853b61bf0d">llvm::LegalizerHelper::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac05773b4901540ea7eaeb572cce9b00d">LowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4f2247785b2cfa91b42485591c4a71df">lowerFABSorFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abc7ab426f010b3402a1e9e6a9fef1327">LowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a618e1a8b97a48a4cf1d6b8941823be50">lowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9dc8c9b527c43cc36ac86886d18f00e4">llvm::LegalizerHelper::lowerFCopySign</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab99f92278021f1921be23b762056a9cc">llvm::LegalizerHelper::lowerFPTOSI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a923b1af8c1e485549410eda36702a5ac">llvm::SelectionDAG::SignBitIsZero</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#ae8379867536cb5449ebfc7b134a8e14b">llvm::GISelKnownBits::signBitIsZero</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>.</p>

</div>
</div>

### getSplat {#a8c55d8510ad4b7cb957d8f5a7cd6944e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt APInt::getSplat (unsigned NewLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; V)</td>
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

<p>Return a value containing V broadcasted over NewLen bits.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>, definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e3e38f27d866ed7730e8e30fc3877cf">combineAddOfPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5efc2b9d3d3b40b85f5f7366bc145837">combineSubShiftToOrcB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa16bb473dbb4b04fd2b11ccb72660b0e">computeKnownBitsForPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3caf52501b70f5695183149e578fbd5a">computeKnownBitsForPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a5929353367b8b1f607f74b6137017d9a">extractConstantBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#adccfbc5892aaeafbf2178ddc7c71bde5">getAvailableLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#aa4b66161f15587adee19725b89fec713">llvm::VNCoercion::getConstantMemInstValueForLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a394f6cae3219d6fc50d8be3e88d1f793">getMemsetValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0b9d961c3e0a9fa4c0e9ce806e972c4c">llvm::LegalizerHelper::lowerBitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ed659cad017d524d63d763e19ef756f">llvm::LegalizerHelper::lowerBitreverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae43089dd5a18812d93f8542cc0be6e16">llvm::ARMTTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a165830656f5ebd0521d278a2cf583a28">tryToRecognizePopCount</a>.</p>

</div>
</div>

### getZero {#add4e37b60ea64faafbc9a5bf3e27280f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getZero (unsigned numBits)</td>
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

<p>Get the '0' value for the specified bit-width.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>Reference <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a6c8069837b71990713a285cb590a0eb2">llvm::ConstantRange::abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a225bed9cd6803933d859e79619abc590">llvm::SwitchCG::SwitchLowering::buildBitTests</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#acd47afc26efebd49949d38018cfc29ce">cmpExcludesZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aca03795fe4ea383d28dcf4433f994485">combineVectorCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a977096c9dc329a2a00fc00549fa2ff84">combineX86ShufflesConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a8c0cefa2bf3b3199ab80b4b897c49e86">llvm::ObjectSizeOffsetVisitor::compute</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a685bd53265606ced2a0cbabcf8dbd54b">computeShlNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a568eb58c528ac26f35008fce0859f576">llvm::SelectionDAG::computeVectorKnownZeroElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac21ca860de08b06c8c3d51c536ba0c90">computeZeroableShuffleElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aea93f76a9c663074d87afbac598f5590">llvm::ConstantRange::ctlz</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acde7e3c58a91a9ba77071d8a84626184">llvm::ConstantRange::ctpop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acc1e6bafefba3a5989e135575377032d">llvm::ConstantRange::cttz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79f138356acaefc8e95c039faf25e07d">detectSSatPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#a437967d8acddbcdb8cb345412f22f9dd">estimateBitMaskedAndLowerBound</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#af5333260b4104fef104ea3459553cae1">anonymous{BasicAliasAnalysis.cpp}::CastedValue::evaluateWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a5929353367b8b1f607f74b6137017d9a">extractConstantBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a53f06c06e81412900ac140caaf764ff8">foldSwitchToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a1729c80f033d20835e31fddb245a4aae">FoldValueWithUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1713768600a9f5a62eb74a616aa73428">llvm::BuildVectorSDNode::getConstantRawBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4543bee5a482ba5cc2ca71b6ac93b920">getConstVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a8c825d8718637fb081db2cf8fbade190">getDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1749d6a76a90f1117d344826f3e1e428">getExtractedDemandedElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a72a64c02db1b9e475fc2646e656cdb98">llvm::getHorizDemandedEltsForFirstOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a09656dc032c419abcec4768d009ed7a0">llvm::X86TTIImpl::getInterleavedMemoryOpCostAVX512</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad2268a8da9de7921a854b4f3e0028ae5">llvm::APFixedPoint::getIntPart</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a17fca146e0dc0228bae32fe5548ab48a">getKnownUndefForVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e33cb0aa9b4fbae99810b4d70d29f25">getPackDemandedElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#af2e33549eacd75ef7ee25e37b46e5f54">getRangeForIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a574647158b42f4d85c9f57f1a474452b">getRangeForSelectPattern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6302b532981eadcac10d0d3ab01e3805">llvm::getShuffleDemandedElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#acc4da9acea00d2b58e4d46bf97eb29c7">getSizeWithOverflow</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a71b68f9cbc43e59ed1e8689245ecb0d3">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::getSOPPBrEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a444d74103a976b2567a773f70571b3d9">getSplatableConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af71303967827d0c63f1caa626e59aa38">getTargetShuffleAndZeroables</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantrange-cpp/#ae6e0521392f7c7e8a1daa7511a533201">getUnsignedCountTrailingZerosRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a880ecb27263b592a9c72b96378c10088">llvm::getVScaleRange</a>, <a href="#aae66680c2cf6c3acccde9cd1189a0215">getZeroWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8d91ca7ede308b821f546a33f6625115">impliesPoisonOrCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adf48ee86d6a806ea693f8e4088718c4d">isCompletePermute</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae2cb6bf0817b8dbe415405c7498b8ce7">llvm::X86TargetLowering::isGuaranteedNotToBeUndefOrPoisonForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ab9c981efb05d9ee219a85648972f71bd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f4d7e1483110d8b2220f79f3ee536d6">llvm::SelectionDAG::isSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a34faa94759387be0a4881a7e227f6caf">llvm::X86TargetLowering::isSplatValueForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af83ff96c157ea2db2a7f032cc9c80369">isTargetShuffleEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abe8a849f2fea1988803555cc45d24721">LowerFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a31f002d1380244ed0e6fbd6af6d65881">lowerShuffleAsElementInsertion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6cf260b0a7ee2cfa1e24f28b771a5f24">lowerShuffleAsLanePermuteAndPermute</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa0830ec6778859b4abb3e8bf0b9e0e38">llvm::ConstantRange::makeAllowedICmpRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a7af36259c05fe6d814df34aa9932c9db">llvm::detail::IEEEFloat::makeNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a079f719b6af4bba305e041821a1e3da0">matchScalarReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a0309899567234d74bf87a3899207bc15">llvm::ConstantRange::multiply</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#af8daf8a07b3ab8645d4a6524caf57e7b">llvm::ConstantRange::multiplyWithNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a710c96cb41fa446808a270ad1e705103">rebuildExtCst</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aebf9c73db3d255463a574759f2ee030c">resolveZeroablesFromTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#ae03364150b1bad2075c2d8db2bb87b92">scalarConstantToHexString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ab455b98d2cc1e2a8ff7a9486ec4c2982">llvm::APIntOps::ScaleBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa160a2ac0c31b48c41da949e53cc21b7">llvm::ConstantRange::sdiv</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a62222502f5be2dd8e300b48469aeab4f">llvm::ConstantRange::shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a51ae77be815f3771d7e0e1837204af01">llvm::ConstantRange::srem</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a59cd1a000769414b2d832576bf689c32">stripAndComputeConstantOffsets</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a0fd3732392fdbdbc5a4436c0f1262999">anonymous{InlineCost.cpp}::CallAnalyzer::stripAndComputeInBoundsConstantOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a336e2050c47c9d72b2cb4b13726fbba3">llvm::ConstantRange::urem</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a0f8ae02669694e3f056dc0e083b3ebbf">anonymous{InlineCost.cpp}::CallAnalyzer::visitPHI</a> and <a href="/web-llvm/docs/api/classes/llvm/reassociate/xoropnd/#ae1f14c3c7ff18e2732df6fc07dd52a3a">llvm::reassociate::XorOpnd::XorOpnd</a>.</p>

</div>
</div>

### getZeroWidth {#aae66680c2cf6c3acccde9cd1189a0215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APInt::getZeroWidth ()</td>
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

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> zero bits wide.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a>.</p>


<p>References <a href="#a44d65323d90a63e5f572fe8f44db1154">APInt</a> and <a href="#add4e37b60ea64faafbc9a5bf3e27280f">getZero</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">APInt.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
