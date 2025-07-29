---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallbitvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SmallBitVector` Class

<p>This is a 'bitvector' (really, a variable-sized bit array), optimized for the case when the array is small. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SmallBitVector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">llvm/ADT/SmallBitVector.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898f4d7d732767d35b3543ef77ff7531">size_type</a> = uintptr_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbcdf377e88062ae0457449c5c1f08d">const_set_bits_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/const-set-bits-iterator-impl">const_set_bits_iterator_impl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505ba44be538449429b5a57b36beef26">set_iterator</a> = <a href="#a8cbcdf377e88062ae0457449c5c1f08d">const_set_bits_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aff194e3d45f7664a0a2b318dfff8a9ee">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an empty bitvector. <a href="#a5d6a9a6677faf3f7627099b26769e083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725fdac92284a40d0e221b39c3107df6">SmallBitVector</a> (unsigned s, bool t=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector of specified number of bits. <a href="#a725fdac92284a40d0e221b39c3107df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739638be46b9ed6cdb18703e8a3969ce">SmallBitVector</a> (const SmallBitVector &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> copy ctor. <a href="#a739638be46b9ed6cdb18703e8a3969ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e83ee6e584c372d96d8490f4c048fe4">SmallBitVector</a> (SmallBitVector &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50d158c2ddb32c8ce0074a76151a199">~SmallBitVector</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b698b5819b3d41ff5b066705a2d9ca">operator~</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector/reference">reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a24b201c3ded6b146a4f7a150c829ce">operator[]</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf02fc0349792701040850333025b6e">operator[]</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e509889272471be8dfcdaa2cc940cc8">operator==</a> (const SmallBitVector &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98cd0f179549f481dd5c3f6a971bb8a">operator!=</a> (const SmallBitVector &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626851f9ade8d8e3c2f7cde2ab1c67c8">operator&amp;=</a> (const SmallBitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf37f317affdd5c72ad07e1ca26e88b0">operator|=</a> (const SmallBitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69725ffe3f92d550e8b98f8712f3afc">operator^=</a> (const SmallBitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8118e1a41c440dc86b37014d2d77bff2">operator&lt;&lt;=</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a936c1e476683479d1f2595bb8e2d9cc3">operator&gt;&gt;=</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b30d4894818c4735be9648da9f97c63">operator=</a> (const SmallBitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7165bb1334c479bcba101b4fedae7a13">operator=</a> (SmallBitVector &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8cbcdf377e88062ae0457449c5c1f08d">const_set_bits_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb804aedf52f05d643c5822bccfca96">set_bits_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8cbcdf377e88062ae0457449c5c1f08d">const_set_bits_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32a57f80eee722b6e49e6e1cbc2ddb3">set_bits_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a8cbcdf377e88062ae0457449c5c1f08d">const_set_bits_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72bc4f47a61dc9d9888561c4dc22e8f6">set_bits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4531049cf26ec8b8b34cfbdbe12691f">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether there are no bits in this bitvector. <a href="#ab4531049cf26ec8b8b34cfbdbe12691f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a898f4d7d732767d35b3543ef77ff7531">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4dce99d953b67f83ef932810a44e21f">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bits in this bitvector. <a href="#aa4dce99d953b67f83ef932810a44e21f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a898f4d7d732767d35b3543ef77ff7531">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0307ad5c950df7f6fb56dc8326184ce">count</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bits which are set. <a href="#ae0307ad5c950df7f6fb56dc8326184ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06e25d03b0091f03f2a25118933236b">any</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if any bit is set. <a href="#ab06e25d03b0091f03f2a25118933236b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cfcd92a373cdd7deefb939dd76b83e3">all</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all bits are set. <a href="#a8cfcd92a373cdd7deefb939dd76b83e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66ea412504abedf84eebd3a5c744bd8">none</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if none of the bits are set. <a href="#af66ea412504abedf84eebd3a5c744bd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12297e7775aa1fc62fbea882aef623fc">find_first</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the first set bit, -1 if none of the bits are set. <a href="#a12297e7775aa1fc62fbea882aef623fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee86eeb3c71ec86d815cedf0fa416ca">find_last</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a880563a86420b886c1aba1b723450">find_first_unset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the first unset bit, -1 if all of the bits are set. <a href="#aa1a880563a86420b886c1aba1b723450">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd105b5c34df8ae3ab825f261056003">find_last_unset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a823f7f9343d9bb1e02104ae3b2d3edb9">find_next</a> (unsigned Prev) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the next set bit following the "Prev" bit. <a href="#a823f7f9343d9bb1e02104ae3b2d3edb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeafa33f43f8775b816c30e68a094482c">find_next_unset</a> (unsigned Prev) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the next unset bit following the "Prev" bit. <a href="#aeafa33f43f8775b816c30e68a094482c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491574255ba72e356166d2655debbd2d">find_prev</a> (unsigned PriorTo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find_prev - Returns the index of the first set bit that precedes the the bit at <span class="doxyComputerOutput">PriorTo</span>. <a href="#a491574255ba72e356166d2655debbd2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d809e29a928b187955f2858a9d98583">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all bits. <a href="#a7d809e29a928b187955f2858a9d98583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a> (unsigned N, bool t=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Grow or shrink the bitvector. <a href="#aa79d9a55d612eb330a0e25dc4170470d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e2a6d15c30784c94effc174d573c2b">reserve</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e2d7efe05987370dc6b5c54797fcf5">set</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10b82f33c3d9c8b7d3695fe0b683aa7">set</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3288c566e87c594943a1bd4e8d8902">set</a> (unsigned I, unsigned E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Efficiently set a range of bits in [I, E) <a href="#a4b3288c566e87c594943a1bd4e8d8902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1232d0679de538d35381496f43e303a">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89740bf6eb425d1a5215fae526b6978a">reset</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233bded0cb20961da9fde9de6c177ec8">reset</a> (unsigned I, unsigned E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Efficiently reset a range of bits in [I, E) <a href="#a233bded0cb20961da9fde9de6c177ec8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0536429e3eebc0aee467b82919258507">flip</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cbc3990e045a84b7622edc491215af">flip</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac2fbe5e3b25110eff93627ac336251">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last element in the vector. <a href="#a6ac2fbe5e3b25110eff93627ac336251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585f149dd8c344a40c53b1694d3161ed">test</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124493b0725e37a6cba223d00946ec8b">push_back</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee088b9cab25c0bb8729c64327378a4">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop one bit from the end of the vector. <a href="#aeee088b9cab25c0bb8729c64327378a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e093eb8f2823c4ec033c43d0d1e316">anyCommon</a> (const SmallBitVector &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if any common bits are set. <a href="#ae4e093eb8f2823c4ec033c43d0d1e316">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a824a41c9438a37a80b7aacf7a6b43b66">reset</a> (const SmallBitVector &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset bits that are set in RHS. Same as *this &amp;= ~RHS. <a href="#a824a41c9438a37a80b7aacf7a6b43b66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22744e70f0f3faf295475ef8cfe92581">test</a> (const SmallBitVector &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if (This - RHS) is zero. This is the same as reset(RHS) and <a href="#ab06e25d03b0091f03f2a25118933236b">any()</a>. <a href="#a22744e70f0f3faf295475ef8cfe92581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ddc9e4a09320d5e460411a558a7f8e">swap</a> (SmallBitVector &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a05ddc4bcf745f56df3a6b7c7abd11">setBitsInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add '1' bits from Mask to this vector. <a href="#a66a05ddc4bcf745f56df3a6b7c7abd11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f129e8f1643e8c9d9b02e0b6a76bce7">clearBitsInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear any bits in this vector that are set in Mask. <a href="#a1f129e8f1643e8c9d9b02e0b6a76bce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22126ae16963966e0c6f65b297428b0">setBitsNotInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a bit to this vector for every '0' bit in Mask. <a href="#ab22126ae16963966e0c6f65b297428b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6957da7ea810cd7ccc7f710f60b1b0a">clearBitsNotInMask</a> (const uint32_t *Mask, unsigned MaskWords=~0u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear a bit in this vector for every '0' bit in Mask. <a href="#ad6957da7ea810cd7ccc7f710f60b1b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30409fc847501d6cb65c0c1e656a2a1d">invalid</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c83f58b7d8f5a300de7a4786181226">isInvalid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uintptr_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a8c5607722079bdad53127c8644ed9">getData</a> (uintptr_t &amp;Store) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb990ca19a5ce908611e4c352785eff6">getPointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638e0a6f43966383a440f8c70e2df9d6">switchToSmall</a> (uintptr_t NewSmallBits, size_type NewSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd6000a49a2b0ad7d9d6599f286f3ce">switchToLarge</a> (BitVector *BV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6126a598d35c2c4c134ebd1c313f29">getSmallRawBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc940847f97f5e7ee66ed2ffbd1ad13">setSmallRawBits</a> (uintptr_t NewRawBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a898f4d7d732767d35b3543ef77ff7531">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da788e8bd9bbcf28b9e1da6cb3a3e30">getSmallSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a62f2b036fc012223b738f24c8cc0f">setSmallSize</a> (size_type Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605df5656f5e13e40d2411651e6d818d">getSmallBits</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7fcbfd649e4838caf317843d18364ff">setSmallBits</a> (uintptr_t NewBits)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bf658c609e862c3d0ae5f5cb64c726c">applyMask</a> (const uint32_t *Mask, unsigned MaskWords)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5f2f31dd2a329a939af006e87acfc2">X</a> = 1</td>
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

<p>This is a 'bitvector' (really, a variable-sized bit array), optimized for the case when the array is small.</p>


<p>It contains one pointer-sized field, which is directly used as a plain collection of bits when possible, or as a pointer to a larger heap-allocated array when necessary. This allows normal "small" cases to be fast without losing generality for large inputs.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_set\_bits\_iterator {#a8cbcdf377e88062ae0457449c5c1f08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallBitVector::const_set_bits_iterator =  const_set_bits_iterator_impl&lt;SmallBitVector&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### set\_iterator {#a505ba44be538449429b5a57b36beef26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallBitVector::set_iterator =  const_set_bits_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### size\_type {#a898f4d7d732767d35b3543ef77ff7531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallBitVector::size_type =  uintptr_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aff194e3d45f7664a0a2b318dfff8a9ee}

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
<td class="doxyEnumItemName">NumBaseBits<a id="aff194e3d45f7664a0a2b318dfff8a9eea07b38ab17efecbfb589b6aaafacb6624"></a></td>
<td class="doxyEnumItemDescription"> (= sizeof(uintptr_t) * CHAR_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SmallNumRawBits<a id="aff194e3d45f7664a0a2b318dfff8a9eea486e864d8855c4d7a5a5c8b77b1d7b8e"></a></td>
<td class="doxyEnumItemDescription"> (= NumBaseBits - 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SmallNumSizeBits<a id="aff194e3d45f7664a0a2b318dfff8a9eeae539539af6801f2b768fd317a3a9929a"></a></td>
<td class="doxyEnumItemDescription">
 (= (NumBaseBits == 32 ? 5 :
                        NumBaseBits == 64 ? 6 :
                        SmallNumRawBits))
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SmallNumDataBits<a id="aff194e3d45f7664a0a2b318dfff8a9eea84da428f2f773a1f0461df6ac856abe9"></a></td>
<td class="doxyEnumItemDescription"> (= SmallNumRawBits - SmallNumSizeBits)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SmallBitVector() {#a5d6a9a6677faf3f7627099b26769e083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallBitVector::SmallBitVector ()</td>
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

<p>Creates an empty bitvector.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Referenced by <a href="#ae4e093eb8f2823c4ec033c43d0d1e316">anyCommon</a>, <a href="#a0536429e3eebc0aee467b82919258507">flip</a>, <a href="#ad4cbc3990e045a84b7622edc491215af">flip</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/reference/#a17b8ef1205145b86c5608045e216ebf9">llvm::SmallBitVector::reference::operator bool</a>, <a href="#af98cd0f179549f481dd5c3f6a971bb8a">operator!=</a>, <a href="#a626851f9ade8d8e3c2f7cde2ab1c67c8">operator&amp;=</a>, <a href="#a8118e1a41c440dc86b37014d2d77bff2">operator&lt;&lt;=</a>, <a href="#a8b30d4894818c4735be9648da9f97c63">operator=</a>, <a href="#a7165bb1334c479bcba101b4fedae7a13">operator=</a>, <a href="#a8e509889272471be8dfcdaa2cc940cc8">operator==</a>, <a href="#a936c1e476683479d1f2595bb8e2d9cc3">operator&gt;&gt;=</a>, <a href="#af69725ffe3f92d550e8b98f8712f3afc">operator^=</a>, <a href="#adf37f317affdd5c72ad07e1ca26e88b0">operator|=</a>, <a href="#af3b698b5819b3d41ff5b066705a2d9ca">operator~</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/reference/#a1a89836e109ba40a243c7a35c2d2c976">llvm::SmallBitVector::reference::reference</a>, <a href="#af1232d0679de538d35381496f43e303a">reset</a>, <a href="#a824a41c9438a37a80b7aacf7a6b43b66">reset</a>, <a href="#a233bded0cb20961da9fde9de6c177ec8">reset</a>, <a href="#a89740bf6eb425d1a5215fae526b6978a">reset</a>, <a href="#a18e2d7efe05987370dc6b5c54797fcf5">set</a>, <a href="#a4b3288c566e87c594943a1bd4e8d8902">set</a>, <a href="#af10b82f33c3d9c8b7d3695fe0b683aa7">set</a>, <a href="#a739638be46b9ed6cdb18703e8a3969ce">SmallBitVector</a>, <a href="#a4e83ee6e584c372d96d8490f4c048fe4">SmallBitVector</a>, <a href="#a30ddc9e4a09320d5e460411a558a7f8e">swap</a> and <a href="#a22744e70f0f3faf295475ef8cfe92581">test</a>.</p>

</div>
</div>

### SmallBitVector() {#a725fdac92284a40d0e221b39c3107df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallBitVector::SmallBitVector (unsigned s, bool t=false)</td>
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

<p>Creates a bitvector of specified number of bits.</p>


<p>All bits are initialized to the specified value.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### SmallBitVector() {#a739638be46b9ed6cdb18703e8a3969ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallBitVector::SmallBitVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> copy ctor.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### SmallBitVector() {#a4e83ee6e584c372d96d8490f4c048fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallBitVector::SmallBitVector (<a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SmallBitVector() {#ab50d158c2ddb32c8ce0074a76151a199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallBitVector::~SmallBitVector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#af98cd0f179549f481dd5c3f6a971bb8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### operator\[\]() {#a0a24b201c3ded6b146a4f7a150c829ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::SmallBitVector::operator[] (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>.</p>

</div>
</div>

### operator\[\]() {#a0cf02fc0349792701040850333025b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::operator[] (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>.</p>

</div>
</div>

### operator&amp;=() {#a626851f9ade8d8e3c2f7cde2ab1c67c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#af1232d0679de538d35381496f43e303a">reset</a>, <a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>

</div>
</div>

### operator^=() {#af69725ffe3f92d550e8b98f8712f3afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>

</div>
</div>

### operator&lt;&lt;=() {#a8118e1a41c440dc86b37014d2d77bff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::operator&lt;&lt;= (unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### operator=() {#a8b30d4894818c4735be9648da9f97c63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallBitVector &amp; llvm::SmallBitVector::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### operator=() {#a7165bb1334c479bcba101b4fedae7a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallBitVector &amp; llvm::SmallBitVector::operator= (<a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#a7d809e29a928b187955f2858a9d98583">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="#a30ddc9e4a09320d5e460411a558a7f8e">swap</a>.</p>

</div>
</div>

### operator==() {#a8e509889272471be8dfcdaa2cc940cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### operator&gt;&gt;=() {#a936c1e476683479d1f2595bb8e2d9cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::operator&gt;&gt;= (unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### operator|=() {#adf37f317affdd5c72ad07e1ca26e88b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>

</div>
</div>

### operator\~() {#af3b698b5819b3d41ff5b066705a2d9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector llvm::SmallBitVector::operator~ ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#a0536429e3eebc0aee467b82919258507">flip</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### all() {#a8cfcd92a373cdd7deefb939dd76b83e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::all ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if all bits are set.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8bd2bb9d716a15d8d914b0236e32e2ee">llvm::CombinerHelper::matchExtractAllEltsFromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a67399cd92cbad7bcf7d0fbe417f779ec">performExtractsShuffleAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a868bc52af4d6fe7f56fb460175735a98">simplifyReductionOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#a90cc54876f57e2f6ee698215c7550ba7">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineUnmergeDefs</a>.</p>

</div>
</div>

### any() {#ab06e25d03b0091f03f2a25118933236b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::any ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if any bit is set.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a> and <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>.</p>

</div>
</div>

### anyCommon() {#ae4e093eb8f2823c4ec033c43d0d1e316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::anyCommon (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
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

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>

</div>
</div>

### back() {#a6ac2fbe5e3b25110eff93627ac336251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::back ()</td>
</tr>
</table>
</td>
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

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4531049cf26ec8b8b34cfbdbe12691f">empty</a> and <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>.</p>

</div>
</div>

### clear() {#a7d809e29a928b187955f2858a9d98583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::clear ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear all bits.</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="#a7165bb1334c479bcba101b4fedae7a13">operator=</a>.</p>

</div>
</div>

### clearBitsInMask() {#a1f129e8f1643e8c9d9b02e0b6a76bce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::clearBitsInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear any bits in this vector that are set in Mask.</p>


<p>Don't resize. This computes "*this &amp;= ~Mask".</p>


<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### clearBitsNotInMask() {#ad6957da7ea810cd7ccc7f710f60b1b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::clearBitsNotInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear a bit in this vector for every '0' bit in Mask.</p>


<p>Don't resize. This computes "*this &amp;= Mask".</p>


<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### count() {#ae0307ad5c950df7f6fb56dc8326184ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallBitVector::count ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bits which are set.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0eea77e7bfa82e0219d2ec7b4efbc94f">llvm::popcount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="#aa1a880563a86420b886c1aba1b723450">find_first_unset</a>, <a href="#a0cd105b5c34df8ae3ab825f261056003">find_last_unset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a> and <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>.</p>

</div>
</div>

### empty() {#ab4531049cf26ec8b8b34cfbdbe12691f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tests whether there are no bits in this bitvector.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="#a6ac2fbe5e3b25110eff93627ac336251">back</a>, <a href="#a30409fc847501d6cb65c0c1e656a2a1d">invalid</a> and <a href="#aeee088b9cab25c0bb8729c64327378a4">pop_back</a>.</p>

</div>
</div>

### find\_first() {#a12297e7775aa1fc62fbea882aef623fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_first ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of the first set bit, -1 if none of the bits are set.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a> and <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp/#a41f57bfb86c16aafc498999912a00614">findMainViewFileID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a048ddb994fd2688e1940fe34f7d706f8">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::isRegUsedByUsesOtherThan</a>.</p>

</div>
</div>

### find\_first\_unset() {#aa1a880563a86420b886c1aba1b723450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_first_unset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of the first unset bit, -1 if all of the bits are set.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ae0307ad5c950df7f6fb56dc8326184ce">count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a> and <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### find\_last() {#a1ee86eeb3c71ec86d815cedf0fa416ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_last ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a> and <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### find\_last\_unset() {#a0cd105b5c34df8ae3ab825f261056003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_last_unset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ae0307ad5c950df7f6fb56dc8326184ce">count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d92de57590536d2f254fe5e903e3372">llvm::countl_one</a> and <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### find\_next() {#a823f7f9343d9bb1e02104ae3b2d3edb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_next (unsigned Prev)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of the next set bit following the "Prev" bit.</p>


<p>Returns -1 if the next set bit is not found.</p>


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a> and <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3f932542066a4a9ff8d9368b1871e9d6">dumpSmallBitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a048ddb994fd2688e1940fe34f7d706f8">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::isRegUsedByUsesOtherThan</a>.</p>

</div>
</div>

### find\_next\_unset() {#aeafa33f43f8775b816c30e68a094482c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_next_unset (unsigned Prev)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of the next unset bit following the "Prev" bit.</p>


<p>Returns -1 if the next unset bit is not found.</p>


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a> and <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### find\_prev() {#a491574255ba72e356166d2655debbd2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SmallBitVector::find_prev (unsigned PriorTo)</td>
</tr>
</table>
</td>
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


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>.</p>

</div>
</div>

### flip() {#a0536429e3eebc0aee467b82919258507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::flip ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>


<p>Referenced by <a href="#af3b698b5819b3d41ff5b066705a2d9ca">operator~</a>.</p>

</div>
</div>

### flip() {#ad4cbc3990e045a84b7622edc491215af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::flip (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### getData() {#a90a8c5607722079bdad53127c8644ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uintptr_t &gt; llvm::SmallBitVector::getData (uintptr_t &amp; Store)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### invalid() {#a30409fc847501d6cb65c0c1e656a2a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::invalid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab4531049cf26ec8b8b34cfbdbe12691f">empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2ca5d48372e4115e4ad8c4f62fea7669/#a0a5adf6decd774362f1f8d57627a4555">llvm::DenseMapInfo&lt; SmallBitVector &gt;::getTombstoneKey</a>.</p>

</div>
</div>

### isInvalid() {#ac0c83f58b7d8f5a300de7a4786181226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::isInvalid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### isSmall() {#ac511bbb3f4cb7d888d439569f94b887f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::isSmall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Referenced by <a href="#a8cfcd92a373cdd7deefb939dd76b83e3">all</a>, <a href="#ab06e25d03b0091f03f2a25118933236b">any</a>, <a href="#ae4e093eb8f2823c4ec033c43d0d1e316">anyCommon</a>, <a href="#a7d809e29a928b187955f2858a9d98583">clear</a>, <a href="#a1f129e8f1643e8c9d9b02e0b6a76bce7">clearBitsInMask</a>, <a href="#ad6957da7ea810cd7ccc7f710f60b1b0a">clearBitsNotInMask</a>, <a href="#ae0307ad5c950df7f6fb56dc8326184ce">count</a>, <a href="#ab4531049cf26ec8b8b34cfbdbe12691f">empty</a>, <a href="#a12297e7775aa1fc62fbea882aef623fc">find_first</a>, <a href="#aa1a880563a86420b886c1aba1b723450">find_first_unset</a>, <a href="#a1ee86eeb3c71ec86d815cedf0fa416ca">find_last</a>, <a href="#a0cd105b5c34df8ae3ab825f261056003">find_last_unset</a>, <a href="#a823f7f9343d9bb1e02104ae3b2d3edb9">find_next</a>, <a href="#aeafa33f43f8775b816c30e68a094482c">find_next_unset</a>, <a href="#a491574255ba72e356166d2655debbd2d">find_prev</a>, <a href="#a0536429e3eebc0aee467b82919258507">flip</a>, <a href="#ad4cbc3990e045a84b7622edc491215af">flip</a>, <a href="#a90a8c5607722079bdad53127c8644ed9">getData</a>, <a href="#af66ea412504abedf84eebd3a5c744bd8">none</a>, <a href="#a626851f9ade8d8e3c2f7cde2ab1c67c8">operator&amp;=</a>, <a href="#a8118e1a41c440dc86b37014d2d77bff2">operator&lt;&lt;=</a>, <a href="#a8b30d4894818c4735be9648da9f97c63">operator=</a>, <a href="#a8e509889272471be8dfcdaa2cc940cc8">operator==</a>, <a href="#a936c1e476683479d1f2595bb8e2d9cc3">operator&gt;&gt;=</a>, <a href="#a0cf02fc0349792701040850333025b6e">operator[]</a>, <a href="#af69725ffe3f92d550e8b98f8712f3afc">operator^=</a>, <a href="#adf37f317affdd5c72ad07e1ca26e88b0">operator|=</a>, <a href="#a36e2a6d15c30784c94effc174d573c2b">reserve</a>, <a href="#af1232d0679de538d35381496f43e303a">reset</a>, <a href="#a824a41c9438a37a80b7aacf7a6b43b66">reset</a>, <a href="#a233bded0cb20961da9fde9de6c177ec8">reset</a>, <a href="#a89740bf6eb425d1a5215fae526b6978a">reset</a>, <a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a>, <a href="#a18e2d7efe05987370dc6b5c54797fcf5">set</a>, <a href="#a4b3288c566e87c594943a1bd4e8d8902">set</a>, <a href="#af10b82f33c3d9c8b7d3695fe0b683aa7">set</a>, <a href="#a66a05ddc4bcf745f56df3a6b7c7abd11">setBitsInMask</a>, <a href="#ab22126ae16963966e0c6f65b297428b0">setBitsNotInMask</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>, <a href="#a22744e70f0f3faf295475ef8cfe92581">test</a> and <a href="#ab50d158c2ddb32c8ce0074a76151a199">~SmallBitVector</a>.</p>

</div>
</div>

### none() {#af66ea412504abedf84eebd3a5c744bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::none ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if none of the bits are set.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>.</p>

</div>
</div>

### pop\_back() {#aeee088b9cab25c0bb8729c64327378a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::pop_back ()</td>
</tr>
</table>
</td>
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

<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab4531049cf26ec8b8b34cfbdbe12691f">empty</a>, <a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a> and <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>.</p>

</div>
</div>

### push\_back() {#a124493b0725e37a6cba223d00946ec8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::push_back (bool Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#aa79d9a55d612eb330a0e25dc4170470d">resize</a> and <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### reserve() {#a36e2a6d15c30784c94effc174d573c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::reserve (unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a6940ad301a9c7053fdcb2acfbda169e5">llvm::BitVector::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>.</p>

</div>
</div>

### reset() {#af1232d0679de538d35381496f43e303a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::reset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a6a56d58ef201c3111c594b541bfef549">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::dropRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>, <a href="#a626851f9ade8d8e3c2f7cde2ab1c67c8">operator&amp;=</a> and <a href="#a824a41c9438a37a80b7aacf7a6b43b66">reset</a>.</p>

</div>
</div>

### reset() {#a89740bf6eb425d1a5215fae526b6978a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::reset (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### reset() {#a233bded0cb20961da9fde9de6c177ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::reset (unsigned I, unsigned E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Efficiently reset a range of bits in [I, E)</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### reset() {#a824a41c9438a37a80b7aacf7a6b43b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset bits that are set in RHS. Same as *this &amp;= ~RHS.</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#af1232d0679de538d35381496f43e303a">reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### resize() {#aa79d9a55d612eb330a0e25dc4170470d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::resize (unsigned N, bool t=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Grow or shrink the bitvector.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a13a5af062b4806f2bd27402b3c6d96ff">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::countRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad5c1c662b1a2674a7059c66dd1c1ab04">lowerShuffleAsSplitOrBlend</a>, <a href="#a626851f9ade8d8e3c2f7cde2ab1c67c8">operator&amp;=</a>, <a href="#af69725ffe3f92d550e8b98f8712f3afc">operator^=</a>, <a href="#adf37f317affdd5c72ad07e1ca26e88b0">operator|=</a>, <a href="#aeee088b9cab25c0bb8729c64327378a4">pop_back</a>, <a href="#a124493b0725e37a6cba223d00946ec8b">push_back</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a3eb3a081cacc38c1381cf09b9bb18896">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::swapAndDropUse</a>.</p>

</div>
</div>

### set() {#a18e2d7efe05987370dc6b5c54797fcf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::set ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">llvm::DwarfExpression::addMachineReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a13a5af062b4806f2bd27402b3c6d96ff">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::countRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a373eb03c4fdd576998906436ebe07001">llvm::LegalizerInfo::getAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4617b6f7b2916249d12f30bc81a17855">getAltInstrMask</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9dbc9a748353035febcc488160ba9956">llvm::MachineInstr::getTypeToPrint</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8bd2bb9d716a15d8d914b0236e32e2ee">llvm::CombinerHelper::matchExtractAllEltsFromBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ab3635230226f6d60dad04b8e83d848fd">llvm::slpvectorizer::BoUpSLP::VLOperands::reorder</a>, <a href="#af10b82f33c3d9c8b7d3695fe0b683aa7">set</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a868bc52af4d6fe7f56fb460175735a98">simplifyReductionOperand</a>.</p>

</div>
</div>

### set() {#af10b82f33c3d9c8b7d3695fe0b683aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::set (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#a18e2d7efe05987370dc6b5c54797fcf5">set</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### set() {#a4b3288c566e87c594943a1bd4e8d8902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector &amp; llvm::SmallBitVector::set (unsigned I, unsigned E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Efficiently set a range of bits in [I, E)</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a> and <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a>.</p>

</div>
</div>

### set\_bits() {#a72bc4f47a61dc9d9888561c4dc22e8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_set_bits_iterator &gt; llvm::SmallBitVector::set_bits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#aecb804aedf52f05d643c5822bccfca96">set_bits_begin</a> and <a href="#ac32a57f80eee722b6e49e6e1cbc2ddb3">set_bits_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dependenceanalysis-cpp/#a3f932542066a4a9ff8d9368b1871e9d6">dumpSmallBitVector</a> and <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>.</p>

</div>
</div>

### set\_bits\_begin() {#aecb804aedf52f05d643c5822bccfca96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_set_bits_iterator llvm::SmallBitVector::set_bits_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Referenced by <a href="#a72bc4f47a61dc9d9888561c4dc22e8f6">set_bits</a>.</p>

</div>
</div>

### set\_bits\_end() {#ac32a57f80eee722b6e49e6e1cbc2ddb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_set_bits_iterator llvm::SmallBitVector::set_bits_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Referenced by <a href="#a72bc4f47a61dc9d9888561c4dc22e8f6">set_bits</a>.</p>

</div>
</div>

### setBitsInMask() {#a66a05ddc4bcf745f56df3a6b7c7abd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::setBitsInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add '1' bits from Mask to this vector.</p>


<p>Don't resize. This computes "*this |= Mask".</p>


<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### setBitsNotInMask() {#ab22126ae16963966e0c6f65b297428b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::setBitsNotInMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords=~0u)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a bit to this vector for every '0' bit in Mask.</p>


<p>Don't resize. This computes "*this |= ~Mask".</p>


<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>

</div>
</div>

### size() {#aa4dce99d953b67f83ef932810a44e21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallBitVector::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bits in this bitvector.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Reference <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>.</p>


<p>Referenced by <a href="#ae4e093eb8f2823c4ec033c43d0d1e316">anyCommon</a>, <a href="#a6ac2fbe5e3b25110eff93627ac336251">back</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a13a5af062b4806f2bd27402b3c6d96ff">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::countRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a6a56d58ef201c3111c594b541bfef549">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::dropRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ae81f2bad7d9fed8d26f20dcd80a9d7b3">llvm::X86TTIImpl::isLegalAltInstr</a>, <a href="#a626851f9ade8d8e3c2f7cde2ab1c67c8">operator&amp;=</a>, <a href="#a8e509889272471be8dfcdaa2cc940cc8">operator==</a>, <a href="#a0a24b201c3ded6b146a4f7a150c829ce">operator[]</a>, <a href="#a0cf02fc0349792701040850333025b6e">operator[]</a>, <a href="#af69725ffe3f92d550e8b98f8712f3afc">operator^=</a>, <a href="#adf37f317affdd5c72ad07e1ca26e88b0">operator|=</a>, <a href="#aeee088b9cab25c0bb8729c64327378a4">pop_back</a>, <a href="#a124493b0725e37a6cba223d00946ec8b">push_back</a>, <a href="#a824a41c9438a37a80b7aacf7a6b43b66">reset</a>, <a href="#a233bded0cb20961da9fde9de6c177ec8">reset</a>, <a href="#a4b3288c566e87c594943a1bd4e8d8902">set</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a3eb3a081cacc38c1381cf09b9bb18896">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::swapAndDropUse</a> and <a href="#a22744e70f0f3faf295475ef8cfe92581">test</a>.</p>

</div>
</div>

### swap() {#a30ddc9e4a09320d5e460411a558a7f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::swap (<a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a7165bb1334c479bcba101b4fedae7a13">operator=</a>.</p>

</div>
</div>

### test() {#a585f149dd8c344a40c53b1694d3161ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::test (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">llvm::DwarfExpression::addMachineReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ae81f2bad7d9fed8d26f20dcd80a9d7b3">llvm::X86TTIImpl::isLegalAltInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a67399cd92cbad7bcf7d0fbe417f779ec">performExtractsShuffleAction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a868bc52af4d6fe7f56fb460175735a98">simplifyReductionOperand</a>.</p>

</div>
</div>

### test() {#a22744e70f0f3faf295475ef8cfe92581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallBitVector::test (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if (This - RHS) is zero. This is the same as reset(RHS) and <a href="#ab06e25d03b0091f03f2a25118933236b">any()</a>.</p>

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>


<p>References <a href="#ac511bbb3f4cb7d888d439569f94b887f">isSmall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aa4dce99d953b67f83ef932810a44e21f">size</a>, <a href="#a5d6a9a6677faf3f7627099b26769e083">SmallBitVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyMask() {#a3bf658c609e862c3d0ae5f5cb64c726c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool AddBits, bool InvertMask&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::applyMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask, unsigned MaskWords)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### getPointer() {#adb990ca19a5ce908611e4c352785eff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector * llvm::SmallBitVector::getPointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### getSmallBits() {#a605df5656f5e13e40d2411651e6d818d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::SmallBitVector::getSmallBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### getSmallRawBits() {#a4a6126a598d35c2c4c134ebd1c313f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::SmallBitVector::getSmallRawBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### getSmallSize() {#a5da788e8bd9bbcf28b9e1da6cb3a3e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallBitVector::getSmallSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### setSmallBits() {#ad7fcbfd649e4838caf317843d18364ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::setSmallBits (uintptr_t NewBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### setSmallRawBits() {#a2bc940847f97f5e7ee66ed2ffbd1ad13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::setSmallRawBits (uintptr_t NewRawBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### setSmallSize() {#ac1a62f2b036fc012223b738f24c8cc0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::setSmallSize (<a href="#a898f4d7d732767d35b3543ef77ff7531">size_type</a> Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### switchToLarge() {#abcd6000a49a2b0ad7d9d6599f286f3ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::switchToLarge (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * BV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

### switchToSmall() {#a638e0a6f43966383a440f8c70e2df9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallBitVector::switchToSmall (uintptr_t NewSmallBits, <a href="#a898f4d7d732767d35b3543ef77ff7531">size_type</a> NewSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### X {#a4a5f2f31dd2a329a939af006e87acfc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::SmallBitVector::X = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">SmallBitVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
