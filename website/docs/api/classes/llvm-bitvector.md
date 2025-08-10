---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitVector` Class



## Declaration

<div class="doxyDeclaration">
class llvm::BitVector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">llvm/ADT/BitVector.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset">RegisterSet</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6104504eedef0699dbe8623982da15">size_type</a> = unsigned</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/const-set-bits-iterator-impl">const_set_bits_iterator_impl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &gt; <a href="#a99a6a1febf299d51eab9d14ce188afe5">const_set_bits_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a6a1febf299d51eab9d14ce188afe5">const_set_bits_iterator</a> <a href="#a60d0b749ce1e04837860b29ac1c1d22b">set_iterator</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uintptr_t <a href="#af12d2cb19540fb731469500b220e5fca">BitWord</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae791b094757e8716aef7fd492f12554b">Storage</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; BitWord &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a0ff166d670d5de19b5c2d581e7af5f46">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> default ctor - Creates an empty bitvector. <a href="#a460ff64bbb831ae656e54858e5ce4a10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799b8fe6913385ba81a7c1b7c51738ae">BitVector</a> (unsigned s, bool t=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> ctor - Creates a bitvector of specified number of bits. <a href="#a799b8fe6913385ba81a7c1b7c51738ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector/reference">reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff34ed187f7b78f420f6e9c2f487b057">operator[]</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9c3b90c31886c3b1dbf43c25d6c248">operator[]</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a962cb3c05d00577f5414f225c09c39a0">operator==</a> (const BitVector &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48828a7cc5114a39b7bd9f0a2c324edb">operator!=</a> (const BitVector &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae780a5b785fe506496569586559019d3">operator&amp;=</a> (const BitVector &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersection, union, disjoint union. <a href="#ae780a5b785fe506496569586559019d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cca642c52ada1e4ac73618a95c532da">operator|=</a> (const BitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c95bca131e8866498bb42740ff4393">operator^=</a> (const BitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09395da97c764bcd5804c40f1f0bff35">operator&gt;&gt;=</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a571c3958ecb1aa9ee1e3178b3544b9ca">operator&lt;&lt;=</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a99a6a1febf299d51eab9d14ce188afe5">const_set_bits_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25f6d432c1168cc80f102fb515bdc71">set_bits_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a99a6a1febf299d51eab9d14ce188afe5">const_set_bits_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c5829390a22af83b66ae1632474dd20">set_bits_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a99a6a1febf299d51eab9d14ce188afe5">const_set_bits_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56c07cdb4f03ddef7dfdf460811d36e">set_bits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae308e6ee93ceb33e921d72d659230669">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - Tests whether there are no bits in this bitvector. <a href="#ae308e6ee93ceb33e921d72d659230669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adb6104504eedef0699dbe8623982da15">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>size - Returns the number of bits in this bitvector. <a href="#abf86e1383aec181a5a2d9967eb8070fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adb6104504eedef0699dbe8623982da15">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a568ff706b8c5991bd299c8c00b803897">count</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>count - Returns the number of bits which are set. <a href="#a568ff706b8c5991bd299c8c00b803897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d0f5c7e6117335f31a0cd1753a594b">any</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>any - Returns true if any bit is set. <a href="#a72d0f5c7e6117335f31a0cd1753a594b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75146e730671c449f870a97db0cbfc6d">all</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>all - Returns true if all bits are set. <a href="#a75146e730671c449f870a97db0cbfc6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19094c99ca405ec1efe38da727d27de">none</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>none - Returns true if none of the bits are set. <a href="#aa19094c99ca405ec1efe38da727d27de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ee0d8424b1acd34ba6256f0ccc2208">find_first_in</a> (unsigned Begin, unsigned End, bool Set=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_first_in - Returns the index of the first set / unset bit, depending on <span class="doxyComputerOutput">Set</span>, in the range [Begin, End). <a href="#ab9ee0d8424b1acd34ba6256f0ccc2208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb8a9448b6a7eb73173ea4251ed5a2b">find_last_in</a> (unsigned Begin, unsigned End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_last_in - Returns the index of the last set bit in the range [Begin, End). <a href="#a8cb8a9448b6a7eb73173ea4251ed5a2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5623afb4b792490104f5197babb435d0">find_first_unset_in</a> (unsigned Begin, unsigned End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_first_unset_in - Returns the index of the first unset bit in the range [Begin, End). <a href="#a5623afb4b792490104f5197babb435d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf7b498bf417c1561bf7c1a0a1f699f">find_last_unset_in</a> (unsigned Begin, unsigned End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_last_unset_in - Returns the index of the last unset bit in the range [Begin, End). <a href="#afbf7b498bf417c1561bf7c1a0a1f699f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da3bac3ad70ccb97150626385ebd6a7">find_first</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_first - Returns the index of the first set bit, -1 if none of the bits are set. <a href="#a2da3bac3ad70ccb97150626385ebd6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b6af088c02711ff015fc585c3d86b7">find_last</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_last - Returns the index of the last set bit, -1 if none of the bits are set. <a href="#a55b6af088c02711ff015fc585c3d86b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9941bbcdd7fadda44146fcc6f91af71f">find_next</a> (unsigned Prev) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_next - Returns the index of the next set bit following the "Prev" bit. <a href="#a9941bbcdd7fadda44146fcc6f91af71f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8535ec99830935ce6bc4e5c0b3dbb3ef">find_prev</a> (unsigned PriorTo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_prev - Returns the index of the first set bit that precedes the the bit at <span class="doxyComputerOutput">PriorTo</span>. <a href="#a8535ec99830935ce6bc4e5c0b3dbb3ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9578f4cf6cb46ac82fa67b6d58b5839">find_first_unset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_first_unset - Returns the index of the first unset bit, -1 if all of the bits are set. <a href="#ae9578f4cf6cb46ac82fa67b6d58b5839">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36a1161123f8c3e4212584a13e737ab">find_next_unset</a> (unsigned Prev) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_next_unset - Returns the index of the next unset bit following the "Prev" bit. <a href="#ae36a1161123f8c3e4212584a13e737ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6328707af67f6405c12011acf468f45c">find_last_unset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_last_unset - Returns the index of the last unset bit, -1 if all of the bits are set. <a href="#a6328707af67f6405c12011acf468f45c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74598865d0e9269f0432688d421c7415">find_prev_unset</a> (unsigned PriorTo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_prev_unset - Returns the index of the first unset bit that precedes the bit at <span class="doxyComputerOutput">PriorTo</span>. <a href="#a74598865d0e9269f0432688d421c7415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bbc237e4a675c5332103ac6e7dcce1">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Removes all bits from the bitvector. <a href="#a35bbc237e4a675c5332103ac6e7dcce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32859a24aa7a3be269855b989d92a4b4">resize</a> (unsigned N, bool t=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>resize - Grow or shrink the bitvector. <a href="#a32859a24aa7a3be269855b989d92a4b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6940ad301a9c7053fdcb2acfbda169e5">reserve</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62237ebe27691377a942abe7446332ec">set</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae384b1e2009113396f689f39a4a04ed8">set</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8c980ce45e26cd450a52d4e407c087">set</a> (unsigned I, unsigned E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>set - Efficiently set a range of bits in [I, E) <a href="#aab8c980ce45e26cd450a52d4e407c087">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168122d6ac4ed2a8b722e01b592ad289">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60139438f1e7f8860ccc91db8319a2b0">reset</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c1fc728e67d1b7adfd8912fb6dca24">reset</a> (unsigned I, unsigned E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - Efficiently reset a range of bits in [I, E) <a href="#a94c1fc728e67d1b7adfd8912fb6dca24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927a42e9ba460032b09028af4e9eb57a">flip</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac341dd7986cdec212dd96112d597cb1b">flip</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f07515f4207097b7e00c345fb4bf95">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last element in the vector. <a href="#a47f07515f4207097b7e00c345fb4bf95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d63c566878e964c19139b2c76c0dab">test</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78fbaa7c0fb39fae884cc54feb8c67da">push_back</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804e552d674729dafd91b7d4f3342aad">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop one bit from the end of the vector. <a href="#a804e552d674729dafd91b7d4f3342aad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352d7cd6ee10aa08d981fc1c67efe786">anyCommon</a> (const BitVector &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if any common bits are set. <a href="#a352d7cd6ee10aa08d981fc1c67efe786">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b66c6417b49152236d8735fe920b03b">reset</a> (const BitVector &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - Reset bits that are set in RHS. Same as *this &amp;= ~RHS. <a href="#a7b66c6417b49152236d8735fe920b03b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4404a4c8d476df9c09f6f2058d6d1c4e">test</a> (const BitVector &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>test - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if (This - RHS) is zero. <a href="#a4404a4c8d476df9c09f6f2058d6d1c4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25130f27dbf92ccb89c1fec09d956add">swap</a> (BitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2b5128fc97be5779e416448fcea8b3">invalid</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3383708ad16f1c9b2948a4fdb52055c">isInvalid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; BitWord &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596bf26045be5b3ef3262b52cbdb3f28">getData</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70087136d08e0945efab3c947b5e89c7">setBitsInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setBitsInMask - Add '1' bits from Mask to this vector. <a href="#a70087136d08e0945efab3c947b5e89c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80574cc00241317f14490d296742fa3f">clearBitsInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearBitsInMask - Clear any bits in this vector that are set in Mask. <a href="#a80574cc00241317f14490d296742fa3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed8d6c8b5f2e6f8afbabdcfaf40d6ff">setBitsNotInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setBitsNotInMask - Add a bit to this vector for every '0' bit in Mask. <a href="#a8ed8d6c8b5f2e6f8afbabdcfaf40d6ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51711ad960e294ac064a578ebfae0de7">clearBitsNotInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearBitsNotInMask - Clear a bit in this vector for every '0' bit in Mask. <a href="#a51711ad960e294ac064a578ebfae0de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adb6104504eedef0699dbe8623982da15">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf1d4ad351c281af220fba49aae5929e">getMemorySize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size (in bytes) of the bit vector. <a href="#acf1d4ad351c281af220fba49aae5929e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adb6104504eedef0699dbe8623982da15">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab108b879b22e4cf0ee7a4dadea0a9279">getBitCapacity</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b9b9053c292521a0ca484f3333bd6c">wordShl</a> (uint32_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a logical left shift of <span class="doxyComputerOutput">Count</span> words by moving everything <span class="doxyComputerOutput">Count</span> words to the right in memory. <a href="#ad9b9b9053c292521a0ca484f3333bd6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87571f841702b93e1c45472cb97c4c36">wordShr</a> (uint32_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a logical right shift of <span class="doxyComputerOutput">Count</span> words by moving those words to the left in memory. <a href="#a87571f841702b93e1c45472cb97c4c36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32992c3732d60b7471643ebc6e210073">next_unset_in_word</a> (int WordIndex, BitWord Word) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0e459b95ff3e6da5b28784fa6b3c84c">NumBitWords</a> (unsigned S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5514494e8515ce000a47169e1eda80df">set_unused_bits</a> (bool t=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ef2b1a75cb745bffe64f221af91439">clear_unused_bits</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacada9c3eca9c3e462ca993d33130a71">init_words</a> (bool t)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool AddBits, bool InvertMask&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a08b94ae318d4a33aeba3e15a526617">applyMask</a> (const uint32_t *Mask, unsigned MaskWords)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">Storage</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea57ef6b7d3251923bf85b04428ae8a">Bits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b4dcce6c20c59e0727d44da25b141e">Size</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class F, class... ArgTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad6ca449f8f0ec4831ecb61be5b25a15e">apply</a> (F &amp;&amp;f, BitVector &amp;Out, BitVector const &amp;Arg, ArgTys const &amp;...Args)</td>
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


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_set\_bits\_iterator {#a99a6a1febf299d51eab9d14ce188afe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef const_set_bits_iterator_impl&lt;BitVector&gt; llvm::BitVector::const_set_bits_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### set\_iterator {#a60d0b749ce1e04837860b29ac1c1d22b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef const_set_bits_iterator llvm::BitVector::set_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### size\_type {#adb6104504eedef0699dbe8623982da15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BitVector::size_type =  unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BitWord {#af12d2cb19540fb731469500b220e5fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uintptr_t llvm::BitVector::BitWord</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### Storage {#ae791b094757e8716aef7fd492f12554b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BitVector::Storage =  SmallVector&lt;BitWord&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a0ff166d670d5de19b5c2d581e7af5f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">BITWORD_SIZE<a id="a0ff166d670d5de19b5c2d581e7af5f46ab32e40657378cde31f72d26670f00f80"></a></td>
<td class="doxyEnumItemDescription"> (= (unsigned)sizeof(BitWord) * CHAR_BIT)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BitVector() {#a460ff64bbb831ae656e54858e5ce4a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitVector::BitVector ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> default ctor - Creates an empty bitvector.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="#a352d7cd6ee10aa08d981fc1c67efe786">anyCommon</a>, <a href="#ad6ca449f8f0ec4831ecb61be5b25a15e">apply</a>, <a href="#a927a42e9ba460032b09028af4e9eb57a">flip</a>, <a href="#ac341dd7986cdec212dd96112d597cb1b">flip</a>, <a href="#a48828a7cc5114a39b7bd9f0a2c324edb">operator!=</a>, <a href="#ae780a5b785fe506496569586559019d3">operator&amp;=</a>, <a href="#a571c3958ecb1aa9ee1e3178b3544b9ca">operator&lt;&lt;=</a>, <a href="#a962cb3c05d00577f5414f225c09c39a0">operator==</a>, <a href="#a09395da97c764bcd5804c40f1f0bff35">operator&gt;&gt;=</a>, <a href="#ac0c95bca131e8866498bb42740ff4393">operator^=</a>, <a href="#a7cca642c52ada1e4ac73618a95c532da">operator|=</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/reference/#a607bdfaedb445f5b9bfdbda9a77098de">llvm::BitVector::reference::reference</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a1cac597fda008ddea577f9f3a6be2b63">anonymous{HexagonGenInsert.cpp}::RegisterSet::RegisterSet</a>, <a href="#a168122d6ac4ed2a8b722e01b592ad289">reset</a>, <a href="#a7b66c6417b49152236d8735fe920b03b">reset</a>, <a href="#a94c1fc728e67d1b7adfd8912fb6dca24">reset</a>, <a href="#a60139438f1e7f8860ccc91db8319a2b0">reset</a>, <a href="#a62237ebe27691377a942abe7446332ec">set</a>, <a href="#aab8c980ce45e26cd450a52d4e407c087">set</a>, <a href="#ae384b1e2009113396f689f39a4a04ed8">set</a>, <a href="#a25130f27dbf92ccb89c1fec09d956add">swap</a> and <a href="#a4404a4c8d476df9c09f6f2058d6d1c4e">test</a>.</p>

</div>
</div>

### BitVector() {#a799b8fe6913385ba81a7c1b7c51738ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitVector::BitVector (unsigned s, bool t=false)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> ctor - Creates a bitvector of specified number of bits.</p>


<p>All bits are initialized to the specified value.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a48828a7cc5114a39b7bd9f0a2c324edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\[\]() {#aff34ed187f7b78f420f6e9c2f487b057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::BitVector::operator[] (unsigned Idx)</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#ac593635ec7ce5c46f2163ea44f628537">anonymous{HexagonGenInsert.cpp}::RegisterSet::operator[]</a> and <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a2bc851bde979df6d33f160c57afb6416">anonymous{HexagonGenInsert.cpp}::RegisterSet::operator[]</a>.</p>

</div>
</div>

### operator\[\]() {#afd9c3b90c31886c3b1dbf43c25d6c248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::operator[] (unsigned Idx)</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator&amp;=() {#ae780a5b785fe506496569586559019d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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

<p>Intersection, union, disjoint union.</p>

<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### operator^=() {#ac0c95bca131e8866498bb42740ff4393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a32859a24aa7a3be269855b989d92a4b4">resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### operator&lt;&lt;=() {#a571c3958ecb1aa9ee1e3178b3544b9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::operator&lt;&lt;= (unsigned N)</td>
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



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="#ae308e6ee93ceb33e921d72d659230669">empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3d063b3cfffeac6b26118598d1f8413">llvm::maskLeadingOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### operator==() {#a962cb3c05d00577f5414f225c09c39a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### operator&gt;&gt;=() {#a09395da97c764bcd5804c40f1f0bff35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::operator&gt;&gt;= (unsigned N)</td>
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



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="#ae308e6ee93ceb33e921d72d659230669">empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### operator|=() {#a7cca642c52ada1e4ac73618a95c532da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a32859a24aa7a3be269855b989d92a4b4">resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a4b8105885d13964c7a0ebb9623cc4acc">anonymous{HexagonGenInsert.cpp}::RegisterSet::insert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### all() {#a75146e730671c449f870a97db0cbfc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::all ()</td>
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

<p>all - Returns true if all bits are set.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a77de311a4aa9ca492ad4fd8e6a363186">isInterestingPHIIncomingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a3f77e2cab72167554d1d13c44fc9877d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::verifyGraph</a>.</p>

</div>
</div>

### any() {#a72d0f5c7e6117335f31a0cd1753a594b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::any ()</td>
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

<p>any - Returns true if any bit is set.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a0ad5cb616fdce8d90db0927dbdf0533c">llvm::SIFrameLowering::determinePrologEpilogSGPRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a3e5d598372d427a9440a5f3aafce6880">anonymous{HexagonGenInsert.cpp}::RegisterSet::empty</a> and <a href="#aa19094c99ca405ec1efe38da727d27de">none</a>.</p>

</div>
</div>

### anyCommon() {#a352d7cd6ee10aa08d981fc1c67efe786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::anyCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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

<p>Test if any common bits are set.</p>

<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#accf377e3b6262cfbdb2b1d7ee3af4187">anonymous{HexagonGenInsert.cpp}::RegisterSet::intersects</a>.</p>

</div>
</div>

### back() {#a47f07515f4207097b7e00c345fb4bf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::back ()</td>
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

<p>Return the last element in the vector.</p>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae308e6ee93ceb33e921d72d659230669">empty</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### clear() {#a35bbc237e4a675c5332103ac6e7dcce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::clear ()</td>
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

<p>clear - Removes all bits from the bitvector.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a75b902b674dccf813eded0d99d6b012e">llvm::CriticalAntiDepBreaker::FinishBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a28caa20d9fc8a395fd4253ccbfe7eb48">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#afed349e48fe08eab8f09c318267987f5">anonymous{HexagonGenInsert.cpp}::RegisterSet::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#a329177b9cd260516a4aca8f55c199020">llvm::SpillPlacement::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>.</p>

</div>
</div>

### clearBitsInMask() {#a80574cc00241317f14490d296742fa3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::clearBitsInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
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

<p>clearBitsInMask - Clear any bits in this vector that are set in Mask.</p>


<p>Don't resize. This computes "*this &amp;= ~Mask".</p>


<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a> and <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>.</p>

</div>
</div>

### clearBitsNotInMask() {#a51711ad960e294ac064a578ebfae0de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::clearBitsNotInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
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

<p>clearBitsNotInMask - Clear a bit in this vector for every '0' bit in Mask.</p>


<p>Don't resize. This computes "*this &amp;= Mask".</p>


<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a> and <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>.</p>

</div>
</div>

### count() {#a568ff706b8c5991bd299c8c00b803897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::BitVector::count ()</td>
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

<p>count - Returns the number of bits which are set.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a93c4e1b8420517136bbb2f5d6a9af796">llvm::pdb::UDTLayoutBase::addChildToLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a225bed9cd6803933d859e79619abc590">llvm::SwitchCG::SwitchLowering::buildBitTests</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ab5de88dc9568b784876478e316042ba6">llvm::SwitchCG::SwitchLowering::findBitTestClusters</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a1a15e8dd266694612ad050ea8d4b4cbd">llvm::SystemZTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b3a50936d453ae4dcadc704958bb35">llvm::AArch64Subtarget::getNumXRegisterReserved</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aae9ffc1cff57df706ebe6dcd34c56723">lowerBuildVectorAsBroadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>.</p>

</div>
</div>

### empty() {#ae308e6ee93ceb33e921d72d659230669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::empty ()</td>
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

<p>empty - Tests whether there are no bits in this bitvector.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="#a47f07515f4207097b7e00c345fb4bf95">back</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aae11cbd7196aeff4a4b2a12be9835f28">llvm::SIRegisterInfo::getReservedRegs</a>, <a href="#a571c3958ecb1aa9ee1e3178b3544b9ca">operator&lt;&lt;=</a>, <a href="#a09395da97c764bcd5804c40f1f0bff35">operator&gt;&gt;=</a>, <a href="#a804e552d674729dafd91b7d4f3342aad">pop_back</a> and <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### find\_first() {#a2da3bac3ad70ccb97150626385ebd6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_first ()</td>
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

<p>find_first - Returns the index of the first set bit, -1 if none of the bits are set.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#ab9ee0d8424b1acd34ba6256f0ccc2208">find_first_in</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#acee1b8853250afb7856e26623c828491">dump_registers</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a4e1c7c49e2e1b6800c2dd9d3c1c19cd5">anonymous{HexagonGenInsert.cpp}::RegisterSet::find_first</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a83ce85b85f9e56f8d578f6d9965723af">llvm::rdf::RegisterAggr::makeRegRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a7aa6619ca9adae49a9c4cb1b40c6f4e0">needsStackFrame</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/ref-iterator/#a3342e14c1073d2f5957e38a40d13c407">llvm::rdf::RegisterAggr::ref_iterator::ref_iterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>.</p>

</div>
</div>

### find\_first\_in() {#ab9ee0d8424b1acd34ba6256f0ccc2208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_first_in (unsigned Begin, unsigned End, bool Set=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>find_first_in - Returns the index of the first set / unset bit, depending on <span class="doxyComputerOutput">Set</span>, in the range [Begin, End).</p>


<p>Returns -1 if all bits in the range are unset / set.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>.</p>


<p>Referenced by <a href="#a2da3bac3ad70ccb97150626385ebd6a7">find_first</a>, <a href="#a5623afb4b792490104f5197babb435d0">find_first_unset_in</a> and <a href="#a9941bbcdd7fadda44146fcc6f91af71f">find_next</a>.</p>

</div>
</div>

### find\_first\_unset() {#ae9578f4cf6cb46ac82fa67b6d58b5839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_first_unset ()</td>
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

<p>find_first_unset - Returns the index of the first unset bit, -1 if all of the bits are set.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a5623afb4b792490104f5197babb435d0">find_first_unset_in</a>.</p>

</div>
</div>

### find\_first\_unset\_in() {#a5623afb4b792490104f5197babb435d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_first_unset_in (unsigned Begin, unsigned End)</td>
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

<p>find_first_unset_in - Returns the index of the first unset bit in the range [Begin, End).</p>


<p>Returns -1 if all bits in the range are set.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#ab9ee0d8424b1acd34ba6256f0ccc2208">find_first_in</a>.</p>


<p>Referenced by <a href="#ae9578f4cf6cb46ac82fa67b6d58b5839">find_first_unset</a>, <a href="#ae36a1161123f8c3e4212584a13e737ab">find_next_unset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>.</p>

</div>
</div>

### find\_last() {#a55b6af088c02711ff015fc585c3d86b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_last ()</td>
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

<p>find_last - Returns the index of the last set bit, -1 if none of the bits are set.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a8cb8a9448b6a7eb73173ea4251ed5a2b">find_last_in</a>.</p>

</div>
</div>

### find\_last\_in() {#a8cb8a9448b6a7eb73173ea4251ed5a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_last_in (unsigned Begin, unsigned End)</td>
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

<p>find_last_in - Returns the index of the last set bit in the range [Begin, End).</p>


<p>Returns -1 if all bits in the range are unset.</p>


<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>.</p>


<p>Referenced by <a href="#a55b6af088c02711ff015fc585c3d86b7">find_last</a> and <a href="#a8535ec99830935ce6bc4e5c0b3dbb3ef">find_prev</a>.</p>

</div>
</div>

### find\_last\_unset() {#a6328707af67f6405c12011acf468f45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_last_unset ()</td>
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

<p>find_last_unset - Returns the index of the last unset bit, -1 if all of the bits are set.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#afbf7b498bf417c1561bf7c1a0a1f699f">find_last_unset_in</a>.</p>

</div>
</div>

### find\_last\_unset\_in() {#afbf7b498bf417c1561bf7c1a0a1f699f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_last_unset_in (unsigned Begin, unsigned End)</td>
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

<p>find_last_unset_in - Returns the index of the last unset bit in the range [Begin, End).</p>


<p>Returns -1 if all bits in the range are set.</p>


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d92de57590536d2f254fe5e903e3372">llvm::countl_one</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>.</p>


<p>Referenced by <a href="#a6328707af67f6405c12011acf468f45c">find_last_unset</a> and <a href="#a74598865d0e9269f0432688d421c7415">find_prev_unset</a>.</p>

</div>
</div>

### find\_next() {#a9941bbcdd7fadda44146fcc6f91af71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_next (unsigned Prev)</td>
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

<p>find_next - Returns the index of the next set bit following the "Prev" bit.</p>


<p>Returns -1 if the next set bit is not found.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#ab9ee0d8424b1acd34ba6256f0ccc2208">find_first_in</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#acee1b8853250afb7856e26623c828491">dump_registers</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#abc866d556baebe360b8c19ef9acb4c46">anonymous{HexagonGenInsert.cpp}::RegisterSet::find_next</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a83ce85b85f9e56f8d578f6d9965723af">llvm::rdf::RegisterAggr::makeRegRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a7aa6619ca9adae49a9c4cb1b40c6f4e0">needsStackFrame</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/ref-iterator/#a3342e14c1073d2f5957e38a40d13c407">llvm::rdf::RegisterAggr::ref_iterator::ref_iterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>.</p>

</div>
</div>

### find\_next\_unset() {#ae36a1161123f8c3e4212584a13e737ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_next_unset (unsigned Prev)</td>
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

<p>find_next_unset - Returns the index of the next unset bit following the "Prev" bit.</p>


<p>Returns -1 if all remaining bits are set.</p>


<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a5623afb4b792490104f5197babb435d0">find_first_unset_in</a>.</p>

</div>
</div>

### find\_prev() {#a8535ec99830935ce6bc4e5c0b3dbb3ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_prev (unsigned PriorTo)</td>
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

<p>find_prev - Returns the index of the first set bit that precedes the the bit at <span class="doxyComputerOutput">PriorTo</span>.</p>


<p>Returns -1 if all previous bits are unset.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a8cb8a9448b6a7eb73173ea4251ed5a2b">find_last_in</a>.</p>

</div>
</div>

### find\_prev\_unset() {#a74598865d0e9269f0432688d421c7415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::find_prev_unset (unsigned PriorTo)</td>
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

<p>find_prev_unset - Returns the index of the first unset bit that precedes the bit at <span class="doxyComputerOutput">PriorTo</span>.</p>


<p>Returns -1 if all previous bits are set.</p>


<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#afbf7b498bf417c1561bf7c1a0a1f699f">find_last_unset_in</a>.</p>

</div>
</div>

### flip() {#a927a42e9ba460032b09028af4e9eb57a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::flip ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipostrabundler-cpp-/sipostrabundler/#a8912872a213b3beab85a7f9a92e86e93">anonymous{SIPostRABundler.cpp}::SIPostRABundler::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#adb26143a53c2c642b1ee05805ba3d3cb">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::setUnallocatableRegs</a>.</p>

</div>
</div>

### flip() {#ac341dd7986cdec212dd96112d597cb1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::flip (unsigned Idx)</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>.</p>

</div>
</div>

### getBitCapacity() {#ab108b879b22e4cf0ee7a4dadea0a9279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::BitVector::getBitCapacity ()</td>
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



<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="#a78fbaa7c0fb39fae884cc54feb8c67da">push_back</a>.</p>

</div>
</div>

### getData() {#a596bf26045be5b3ef3262b52cbdb3f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BitWord &gt; llvm::BitVector::getData ()</td>
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



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### getMemorySize() {#acf1d4ad351c281af220fba49aae5929e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::BitVector::getMemorySize ()</td>
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

<p>Return the size (in bytes) of the bit vector.</p>

<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### invalid() {#a6f2b5128fc97be5779e416448fcea8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::invalid ()</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-e8bf709c880f724f94905ff4a2a59baf/#aab15821390002c13baecc34408b098fb">llvm::DenseMapInfo&lt; BitVector &gt;::getTombstoneKey</a>.</p>

</div>
</div>

### isInvalid() {#af3383708ad16f1c9b2948a4fdb52055c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::isInvalid ()</td>
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



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### none() {#aa19094c99ca405ec1efe38da727d27de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::none ()</td>
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

<p>none - Returns true if none of the bits are set.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a72d0f5c7e6117335f31a0cd1753a594b">any</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ceb04284d179d66b26dede64956d9c7">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedef5fbc8b36ae2d384e6a2d2dbae6ca">llvm::isConstOrConstSplatFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipostrabundler-cpp-/sipostrabundler/#a8912872a213b3beab85a7f9a92e86e93">anonymous{SIPostRABundler.cpp}::SIPostRABundler::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#add05bb6a2fc43dfa726b8a1a02d1b4c0">llvm::PPCFrameLowering::updateCalleeSaves</a>.</p>

</div>
</div>

### pop\_back() {#a804e552d674729dafd91b7d4f3342aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::pop_back ()</td>
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

<p>Pop one bit from the end of the vector.</p>

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae308e6ee93ceb33e921d72d659230669">empty</a>, <a href="#a32859a24aa7a3be269855b989d92a4b4">resize</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### push\_back() {#a78fbaa7c0fb39fae884cc54feb8c67da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::push_back (bool Val)</td>
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



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#ab108b879b22e4cf0ee7a4dadea0a9279">getBitCapacity</a>, <a href="#a32859a24aa7a3be269855b989d92a4b4">resize</a> and <a href="#a62237ebe27691377a942abe7446332ec">set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>.</p>

</div>
</div>

### reserve() {#a6940ad301a9c7053fdcb2acfbda169e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::reserve (unsigned N)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a36e2a6d15c30784c94effc174d573c2b">llvm::SmallBitVector::reserve</a>.</p>

</div>
</div>

### reset() {#a168122d6ac4ed2a8b722e01b592ad289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::reset ()</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfframelowering/#a6902342411e347a41b347f9c866433b1">llvm::BPFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#af9008c34cdebe84ae9252952470f0599">llvm::LanaiFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#aaabcdae312538836cccf2ed4e8069999">llvm::XCoreFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a02e130cc7c8eead6d7c19d6b4455a4ec">determineFPRegsToClear</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afa9e8234d75eca83a898e143f4b2502e">llvm::TargetRegisterInfo::getAllocatableSet</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a141c1355ec5e74412b594d6daabaa0a3">anonymous{HexagonGenInsert.cpp}::RegisterSet::remove</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a7d466728ce72f2c39e383cd2606d9042">anonymous{HexagonGenInsert.cpp}::RegisterSet::remove</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa4d444250018e8e065ca05a73bdf3d35">llvm::rdf::Liveness::resetKills</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipostrabundler-cpp-/sipostrabundler/#a8912872a213b3beab85a7f9a92e86e93">anonymous{SIPostRABundler.cpp}::SIPostRABundler::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#aea759a40aec24ad7cbc5c1761cdf2dbd">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::setCallerSaved</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1101a933da1fae1b166dc36e2a384ce1">llvm::SIMachineFunctionInfo::shiftWwmVGPRsToLowestRange</a>.</p>

</div>
</div>

### reset() {#a60139438f1e7f8860ccc91db8319a2b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::reset (unsigned Idx)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>.</p>

</div>
</div>

### reset() {#a94c1fc728e67d1b7adfd8912fb6dca24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::reset (unsigned I, unsigned E)</td>
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

<p>reset - Efficiently reset a range of bits in [I, E)</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### reset() {#a7b66c6417b49152236d8735fe920b03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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

<p>reset - Reset bits that are set in RHS. Same as *this &amp;= ~RHS.</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### resize() {#a32859a24aa7a3be269855b989d92a4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::resize (unsigned N, bool t=false)</td>
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

<p>resize - Grow or shrink the bitvector.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/udtlayoutbase/#a93c4e1b8420517136bbb2f5d6a9af796">llvm::pdb::UDTLayoutBase::addChildToLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="#ad6ca449f8f0ec4831ecb61be5b25a15e">apply</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a878a2b864e18e3d074d75b426ea7912d">llvm::HexagonFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a647fbf2c5d5bb2fe4f4b5b9af7e0ab00">llvm::TargetFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a2d771e664c8cbfcf4ed1e5a51d052b29">llvm::IndexedInstrProfReader::getFunctionBitmap</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#aba7fb21a2d5ab45963fa25629ad883aa">anonymous{MachineCopyPropagation.cpp}::CopyTracker::getPreservedRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a28caa20d9fc8a395fd4253ccbfe7eb48">llvm::BuildVectorSDNode::getRepeatedSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a66b06a3a00ea8358c447658d398dc3f8">llvm::BuildVectorSDNode::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="#ac0c95bca131e8866498bb42740ff4393">operator^=</a>, <a href="#a7cca642c52ada1e4ac73618a95c532da">operator|=</a>, <a href="#a804e552d674729dafd91b7d4f3342aad">pop_back</a>, <a href="#a78fbaa7c0fb39fae884cc54feb8c67da">push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>.</p>

</div>
</div>

### set() {#a62237ebe27691377a942abe7446332ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::set ()</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Reference <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#a9f7b165b3b29ea4afc3ff84be0f097b5">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::addLiveOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a6090242d02f8da5fef11db06af3c5783">addRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#ad3ecb1cd79a21ac1f6c064fb0ab8340c">applyBitsNotInRegMaskToRegUnitsMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a225bed9cd6803933d859e79619abc590">llvm::SwitchCG::SwitchLowering::buildBitTests</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a7bd2eaf010a0c53df66932fc514f1cc9">llvm::TargetRegisterInfo::checkAllSuperRegsMarked</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a12d8c4c294b19351dbee6ab588676012">checkNumAlignedDPRCS2Regs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a7984cd880842e26cfce7e3e85a19a650">llvm::ARCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#ae4b28bf746145736c634892f6aa6a6a1">llvm::AVRFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a878a2b864e18e3d074d75b426ea7912d">llvm::HexagonFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a759033addb47f61385c08c441120184a">llvm::LoongArchFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a16d9aef1065a0997fe2ac4b560ca9cce">llvm::M68kFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#a1d6657eee2635fc25cefd2d33163f5e9">llvm::Mips16FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa2e3cf793a3ed0af11da73a0bfbb5ad1">llvm::RISCVFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#ae2560d194f394dd45de1fa04505061ae">llvm::SystemZXPLINKFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6cbb50454d9bb068f4ab6b2d08fb7abf">llvm::X86FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#aee4eef0d0c95682be7d957ad60f6b063">llvm::XtensaFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ab5de88dc9568b784876478e316042ba6">llvm::SwitchCG::SwitchLowering::findBitTestClusters</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#acb823b4b02ad10b373f131ce0180ab13">llvm::ARMFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a647fbf2c5d5bb2fe4f4b5b9af7e0ab00">llvm::TargetFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a1713768600a9f5a62eb74a616aa73428">llvm::BuildVectorSDNode::getConstantRawBits</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node/#a853692dee5306a0d1c6ddafc53e954dd">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Node::getDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#a72abb9be89c086c312ae6dc20b96d09c">getInputSegmentList</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a1a15e8dd266694612ad050ea8d4b4cbd">llvm::SystemZTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedmemprofreader/#af543f9026f539064b643534a8acf1ae5">llvm::IndexedMemProfReader::getMemProfCallerCalleePairs</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#aba7fb21a2d5ab45963fa25629ad883aa">anonymous{MachineCopyPropagation.cpp}::CopyTracker::getPreservedRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#ada3a54f693f7013ac6b22535caccf52f">anonymous{HexagonGenInsert.cpp}::RegisterSet::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a77de311a4aa9ca492ad4fd8e6a363186">isInterestingPHIIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a13c4005ea769c09d88be76fa40744e7e">llvm::LiveRangeCalc::isJointlyDominated</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71b27c25d18516bdcb3f3a44ebf6185b">llvm::optimizeGlobalCtorsList</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a406a444512ca2224d325c9a217c31547">processPSInputArgs</a>, <a href="#a78fbaa7c0fb39fae884cc54feb8c67da">push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a36e2a6d15c30784c94effc174d573c2b">llvm::SmallBitVector::reserve</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa4d444250018e8e065ca05a73bdf3d35">llvm::rdf::Liveness::resetKills</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#aea20ccef4ad810aac64b6a0ac6571d3b">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseframelowering-cpp/#a8058af7f16d3ab91b5a51f5102843b96">setAliasRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#adb26143a53c2c642b1ee05805ba3d3cb">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::setUnallocatableRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a42ba26b731da85ec85d9f4ebb7d27e02">llvm::PPCFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#add05bb6a2fc43dfa726b8a1a02d1b4c0">llvm::PPCFrameLowering::updateCalleeSaves</a>.</p>

</div>
</div>

### set() {#ae384b1e2009113396f689f39a4a04ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::set (unsigned Idx)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>.</p>

</div>
</div>

### set() {#aab8c980ce45e26cd450a52d4e407c087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::set (unsigned I, unsigned E)</td>
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

<p>set - Efficiently set a range of bits in [I, E)</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a>.</p>

</div>
</div>

### set\_bits() {#aa56c07cdb4f03ddef7dfdf460811d36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_set_bits_iterator &gt; llvm::BitVector::set_bits ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#aa25f6d432c1168cc80f102fb515bdc71">set_bits_begin</a> and <a href="#a5c5829390a22af83b66ae1632474dd20">set_bits_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a205e1f9d2dc81b91902dce526a77c5c7">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::calculateCost</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac1cbaebc2a18476b73105d6916a56664">llvm::TargetLoweringBase::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#afb31367a4e0005968619f3418c0a03e1">findTemporariesForLR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#a72abb9be89c086c312ae6dc20b96d09c">getInputSegmentList</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedmemprofreader/#af543f9026f539064b643534a8acf1ae5">llvm::IndexedMemProfReader::getMemProfCallerCalleePairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#adb26143a53c2c642b1ee05805ba3d3cb">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::setUnallocatableRegs</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#afa06aa56938cd078f6e40733f5406dab">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineBasicBlockBefore</a>.</p>

</div>
</div>

### set\_bits\_begin() {#aa25f6d432c1168cc80f102fb515bdc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_set_bits_iterator llvm::BitVector::set_bits_begin ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="#aa56c07cdb4f03ddef7dfdf460811d36e">set_bits</a>.</p>

</div>
</div>

### set\_bits\_end() {#a5c5829390a22af83b66ae1632474dd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_set_bits_iterator llvm::BitVector::set_bits_end ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="#aa56c07cdb4f03ddef7dfdf460811d36e">set_bits</a>.</p>

</div>
</div>

### setBitsInMask() {#a70087136d08e0945efab3c947b5e89c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::setBitsInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
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

<p>setBitsInMask - Add '1' bits from Mask to this vector.</p>


<p>Don't resize. This computes "*this |= Mask".</p>


<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac1cbaebc2a18476b73105d6916a56664">llvm::TargetLoweringBase::findRepresentativeClass</a>.</p>

</div>
</div>

### setBitsNotInMask() {#a8ed8d6c8b5f2e6f8afbabdcfaf40d6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::setBitsNotInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
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

<p>setBitsNotInMask - Add a bit to this vector for every '0' bit in Mask.</p>


<p>Don't resize. This computes "*this |= ~Mask".</p>


<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### size() {#abf86e1383aec181a5a2d9967eb8070fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::BitVector::size ()</td>
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

<p>size - Returns the number of bits in this bitvector.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="#ad6ca449f8f0ec4831ecb61be5b25a15e">apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="#a47f07515f4207097b7e00c345fb4bf95">back</a>, <a href="#ae780a5b785fe506496569586559019d3">operator&amp;=</a>, <a href="#a962cb3c05d00577f5414f225c09c39a0">operator==</a>, <a href="#ac0c95bca131e8866498bb42740ff4393">operator^=</a>, <a href="#a7cca642c52ada1e4ac73618a95c532da">operator|=</a>, <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>, <a href="#a804e552d674729dafd91b7d4f3342aad">pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a2387207e96faf525ff211b5d101f0918">llvm::BuildVectorSDNode::recastRawBits</a>, <a href="#a7b66c6417b49152236d8735fe920b03b">reset</a>, <a href="#a94c1fc728e67d1b7adfd8912fb6dca24">reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a> and <a href="#aab8c980ce45e26cd450a52d4e407c087">set</a>.</p>

</div>
</div>

### swap() {#a25130f27dbf92ccb89c1fec09d956add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::swap (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### test() {#a15d63c566878e964c19139b2c76c0dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::test (unsigned Idx)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp/#a239e4eab401a0f791e5042a89c66dc84">addLiveInRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#ab7263c22653c86a22ff72bc5385e8835">llvm::AggressiveAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a12d8c4c294b19351dbee6ab588676012">checkNumAlignedDPRCS2Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a88484d585ecc86920ebee6396946eae2">llvm::PPCFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa2e3cf793a3ed0af11da73a0bfbb5ad1">llvm::RISCVFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a86ad8db657f0a7ace4758548f09ef59a">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::determineRegsForWWMAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aaab55218a27d024208f67c846f882f2b">findFreePredicateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#afb31367a4e0005968619f3418c0a03e1">findTemporariesForLR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aae7bdcf65f4ce313299a333956258f10">llvm::LoongArchTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a8c03ac21b9348135d67887e1246f2845">llvm::RISCVTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aae11cbd7196aeff4a4b2a12be9835f28">llvm::SIRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a346955acdf30b0ecf7f58b3ba9e32129">llvm::ScheduleDAGTopologicalSort::GetSubGraph</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registerset/#a7f1ed280a80d821d3b1ae74e61768cb6">anonymous{HexagonGenInsert.cpp}::RegisterSet::has</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#a24f5e9f2f1099bdf31d822cb8fe05949">anonymous{HexagonBitSimplify.cpp}::RegisterSet::includes</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ab20d327887091b2623315d7154f115a2">llvm::ARMBaseRegisterInfo::isAsmClobberable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aea7a3432d151faabd6ef46998c204c85">llvm::PPCRegisterInfo::isAsmClobberable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a53ca7cff9e929ba372da9780fdd44b02">llvm::MachineRegisterInfo::isReserved</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a23de116e7a75d0aaae35a539d6a6118e">scavengeStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a27a647930b9f60f83868035dcd46fca8">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::spillCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#abd095bb58a0243946704d20d3559d420">llvm::AggressiveAntiDepBreaker::StartBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#adb4573a84f25279673e3906914132a39">llvm::CriticalAntiDepBreaker::StartBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#add05bb6a2fc43dfa726b8a1a02d1b4c0">llvm::PPCFrameLowering::updateCalleeSaves</a>.</p>

</div>
</div>

### test() {#a4404a4c8d476df9c09f6f2058d6d1c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitVector::test (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RHS)</td>
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

<p>test - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if (This - RHS) is zero.</p>


<p>This is the same as reset(RHS) and <a href="#a72d0f5c7e6117335f31a0cd1753a594b">any()</a>.</p>


<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyMask() {#a4a08b94ae318d4a33aeba3e15a526617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool AddBits, bool InvertMask&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::applyMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords)</td>
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



<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### clear\_unused\_bits() {#af9ef2b1a75cb745bffe64f221af91439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::clear_unused_bits ()</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### init\_words() {#aacada9c3eca9c3e462ca993d33130a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::init_words (bool t)</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### next\_unset\_in\_word() {#a32992c3732d60b7471643ebc6e210073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::BitVector::next_unset_in_word (int WordIndex, BitWord Word)</td>
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



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### NumBitWords() {#af0e459b95ff3e6da5b28784fa6b3c84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitVector::NumBitWords (unsigned S)</td>
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



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### set\_unused\_bits() {#a5514494e8515ce000a47169e1eda80df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::set_unused_bits (bool t=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### wordShl() {#ad9b9b9053c292521a0ca484f3333bd6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::wordShl (uint32_t Count)</td>
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

<p>Perform a logical left shift of <span class="doxyComputerOutput">Count</span> words by moving everything <span class="doxyComputerOutput">Count</span> words to the right in memory.</p>


<p>While confusing, words are stored from least significant at Bits[0] to most significant at Bits[NumWords-1]. A logical shift left, however, moves the current least significant bit to a higher logical index, and fills the previous least significant bits with 0. Thus, we actually need to move the bytes of the memory to the right, not to the left. Example: Words = [0xBBBBAAAA, 0xDDDDFFFF, 0x00000000, 0xDDDD0000] represents a <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> where 0xBBBBAAAA contain the least significant bits. So if we want to shift the <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> left by 2 words, we need to turn this into 0x00000000 0x00000000 0xBBBBAAAA 0xDDDDFFFF by using a memmove which moves right, not left.</p>


<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### wordShr() {#a87571f841702b93e1c45472cb97c4c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BitVector::wordShr (uint32_t Count)</td>
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

<p>Perform a logical right shift of <span class="doxyComputerOutput">Count</span> words by moving those words to the left in memory.</p>


<p>See wordShl for more information.</p>


<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bits {#abea57ef6b7d3251923bf85b04428ae8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Storage llvm::BitVector::Bits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

### Size {#a34b4dcce6c20c59e0727d44da25b141e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitVector::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### apply() {#ad6ca449f8f0ec4831ecb61be5b25a15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class F, class... ArgTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector &amp; llvm::BitVector::apply (<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> &amp;&amp; f, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Arg, ArgTys <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;... Args)</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a460ff64bbb831ae656e54858e5ce4a10">BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a32859a24aa7a3be269855b989d92a4b4">resize</a>, <a href="#abf86e1383aec181a5a2d9967eb8070fd">size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a2d771e664c8cbfcf4ed1e5a51d052b29">llvm::IndexedInstrProfReader::getFunctionBitmap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitvector-h">BitVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
