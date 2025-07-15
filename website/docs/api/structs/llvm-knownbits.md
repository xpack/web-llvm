---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/knownbits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `KnownBits` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::KnownBits { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b9eeb5b297d56ea1ee595eefa3f6da">KnownBits</a> (unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a known bits object of BitWidth bits initialized to unknown. <a href="#ad8b9eeb5b297d56ea1ee595eefa3f6da">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73524f65f9c0b6998c346e5a34e9b7f5">KnownBits</a> (APInt Zero, APInt One)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e2143cbd13db0b1cbb093919b9b15b">operator&amp;=</a> (const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update known bits based on ANDing with RHS. <a href="#a87e2143cbd13db0b1cbb093919b9b15b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48db7eb3db95cfbfd19f699b996843fb">operator|=</a> (const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update known bits based on ORing with RHS. <a href="#a48db7eb3db95cfbfd19f699b996843fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2632149f66b099426f2dcff58ed93b7">operator^=</a> (const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update known bits based on XORing with RHS. <a href="#ae2632149f66b099426f2dcff58ed93b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bc6f1c1c1a81f7679a9086271b9c4e">operator==</a> (const KnownBits &amp;Other) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75e5a8528fd989ecd2fa91944a1a800">operator!=</a> (const KnownBits &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bit width of this value. <a href="#a4fdc09049a61f952b5d52788dbd2f69b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there is conflicting information. <a href="#a44875c6f48f6c843cf3114a19280b5ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5274c29c7da2473d342adfa98f34a025">isConstant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we know the value of all bits. <a href="#a5274c29c7da2473d342adfa98f34a025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1c330d00d17bd267450ab43d5f0eec">getConstant</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value when all bits have a known value. <a href="#afd1c330d00d17bd267450ab43d5f0eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cf355963391ab8781b2347d495553d">isUnknown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we don't know any bits. <a href="#a28cf355963391ab8781b2347d495553d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c853e7ffb5929484f42ab5b4d48c47b">isSignUnknown</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we don't know the sign bit. <a href="#a5c853e7ffb5929484f42ab5b4d48c47b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538f22b4ea2ff04a0b41403f26eaeb67">resetAll</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the known state of all bits. <a href="#a538f22b4ea2ff04a0b41403f26eaeb67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1620c017d995c7ccbcb59e0212618017">isZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if value is all zero. <a href="#a1620c017d995c7ccbcb59e0212618017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3680fca8d50d56b690bed3ac6c1f68e">isAllOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if value is all one bits. <a href="#af3680fca8d50d56b690bed3ac6c1f68e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make all bits known to be zero and discard any previous information. <a href="#a4816b869391aac5bbcce9c889c2ecd97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f473e7109b116f0337cbe78964e6af">setAllOnes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make all bits known to be one and discard any previous information. <a href="#ab0f473e7109b116f0337cbe78964e6af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc0af41b4437080b27002ed7a1ed656">isNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is known to be negative. <a href="#aabc0af41b4437080b27002ed7a1ed656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157efd68e8b4b838829cad165b1583f8">isNonNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is known to be non-negative. <a href="#a157efd68e8b4b838829cad165b1583f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d774365f4d1120b030d026860193a02">isNonZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is known to be non-zero. <a href="#a5d774365f4d1120b030d026860193a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e89086daed6298a9f768aae9bf9675a">isStrictlyPositive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this value is known to be positive. <a href="#a9e89086daed6298a9f768aae9bf9675a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d9168813b2a8415c085ac551c54458">makeNegative</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make this value negative. <a href="#a36d9168813b2a8415c085ac551c54458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192e15f89a5aa04df018639812e2c4db">makeNonNegative</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make this value non-negative. <a href="#a192e15f89a5aa04df018639812e2c4db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b35c622a902a7a7dc93b807a9fa9265">getMinValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimal unsigned value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>. <a href="#a9b35c622a902a7a7dc93b807a9fa9265">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b0ab35dee6bb5d9d53098111bf5c84">getSignedMinValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimal signed value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>. <a href="#ae0b0ab35dee6bb5d9d53098111bf5c84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825476b2436eb817b735fdd34ee521c4">getMaxValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximal unsigned value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>. <a href="#a825476b2436eb817b735fdd34ee521c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c829b0f51e87159f116f980af6237d">getSignedMaxValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximal signed value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>. <a href="#a30c829b0f51e87159f116f980af6237d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for a truncation of the value we're tracking. <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6661654e5ce1b32651508eec50b6d58">anyext</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for an "any" extension of the value we're tracking, where we don't know anything about the extended bits. <a href="#ac6661654e5ce1b32651508eec50b6d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c3c203b80468b8761416d14e6f5b7f">zext</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for a zero extension of the value we're tracking. <a href="#a51c3c203b80468b8761416d14e6f5b7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781ca23d84995ffb2efaa51267053c19">sext</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for a sign extension of the value we're tracking. <a href="#a781ca23d84995ffb2efaa51267053c19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c649ec21217b3feb2f2a28b4736b689">anyextOrTrunc</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for an "any" extension or truncation of the value we're tracking. <a href="#a0c649ec21217b3feb2f2a28b4736b689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">zextOrTrunc</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for a zero extension or truncation of the value we're tracking. <a href="#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b0f10768256c95094a03348ee5fd32">sextOrTrunc</a> (unsigned BitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for a sign extension or truncation of the value we're tracking. <a href="#af7b0f10768256c95094a03348ee5fd32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c936127975e910ae794122a057b067d">sextInReg</a> (unsigned SrcBitWidth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return known bits for a in-register sign extension of the value we're tracking. <a href="#a0c936127975e910ae794122a057b067d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41beafb710aa35f1b793e5876bf2c70">insertBits</a> (const KnownBits &amp;SubBits, unsigned BitPosition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the bits from a smaller known bits starting at bitPosition. <a href="#ab41beafb710aa35f1b793e5876bf2c70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1c4a256c58844fb8dc8aa154f335a4">extractBits</a> (unsigned NumBits, unsigned BitPosition) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a subset of the known bits from [bitPosition,bitPosition+numBits). <a href="#a6f1c4a256c58844fb8dc8aa154f335a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1c9028cc02b58ce040aa83456c9129">concat</a> (const KnownBits &amp;Lo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concatenate the bits from <span class="doxyComputerOutput">Lo</span> onto the bottom of *this. <a href="#a4d1c9028cc02b58ce040aa83456c9129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed221e7e8b34742e248f6f81ef15f90">makeGE</a> (const APInt &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> based on this, but updated given that the underlying value is known to be greater than or equal to Val. <a href="#a2ed221e7e8b34742e248f6f81ef15f90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eeff70353694cb360b2893553c18e7d">countMinTrailingZeros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum number of trailing zero bits. <a href="#a1eeff70353694cb360b2893553c18e7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7969b5a4964ca451ebc622ecf6bb4120">countMinTrailingOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum number of trailing one bits. <a href="#a7969b5a4964ca451ebc622ecf6bb4120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f47812e8e75b0616a97d7004e5fb909">countMinLeadingZeros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum number of leading zero bits. <a href="#a7f47812e8e75b0616a97d7004e5fb909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d90fff0f1479f662286338ffecd7f05">countMinLeadingOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum number of leading one bits. <a href="#a1d90fff0f1479f662286338ffecd7f05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10303a2ffd5366402dfdb65bc55fcff1">countMinSignBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of times the sign bit is replicated into the other bits. <a href="#a10303a2ffd5366402dfdb65bc55fcff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09e08dbb0765df54b4d2a8fc8a1abca">countMaxSignificantBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of bits needed to represent all possible signed values with these known bits. <a href="#ad09e08dbb0765df54b4d2a8fc8a1abca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad6370e532a52014fe2e5a54bfbaddd">countMaxTrailingZeros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of trailing zero bits possible. <a href="#a2ad6370e532a52014fe2e5a54bfbaddd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3d297e00e7ddbced461c33c84a822b">countMaxTrailingOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of trailing one bits possible. <a href="#a0a3d297e00e7ddbced461c33c84a822b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8d1fc0f6386ef04a4b991fd73d823b">countMaxLeadingZeros</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of leading zero bits possible. <a href="#aaf8d1fc0f6386ef04a4b991fd73d823b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada00227b6d66e62162700f62c56cd98c">countMaxLeadingOnes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of leading one bits possible. <a href="#ada00227b6d66e62162700f62c56cd98c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ecbbccee1ca4e3ddde24cc714ec79e">countMinPopulation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of bits known to be one. <a href="#ad2ecbbccee1ca4e3ddde24cc714ec79e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4676f4bc7da9235ff3b6683dd670d7be">countMaxPopulation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of bits that could be one. <a href="#a4676f4bc7da9235ff3b6683dd670d7be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70674aa792d906276123ab69dbdbfc69">countMaxActiveBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum number of bits needed to represent all possible unsigned values with these known bits. <a href="#a70674aa792d906276123ab69dbdbfc69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a> (const KnownBits &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> information that is known to be true for both this and RHS. <a href="#a76e45a40f2f0b5b09132d1de119765e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb97a9e9a3717af2794011459f03607">unionWith</a> (const KnownBits &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> information that is known to be true for either this or RHS or both. <a href="#a5bb97a9e9a3717af2794011459f03607">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9384ac452485cfed65a93b238080793">abs</a> (bool IntMinIsPoison=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for the absolute value. <a href="#ac9384ac452485cfed65a93b238080793">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4421e5acdca3cb36134d66d5a06e23b2">byteSwap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c734dfebb2a1b9faa891d2d2c3a807">reverseBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18790dbaa8ba6bb118ea10e8643a0597">blsi</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for X &amp; -X, which has only the lowest bit set of X set. <a href="#a18790dbaa8ba6bb118ea10e8643a0597">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3672d546ea0f6b4748807c35d620bdc9">blsmsk</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for X ^ (X - 1), which has all bits up to and including the lowest set bit of X set. <a href="#a3672d546ea0f6b4748807c35d620bdc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0179756dcc99d6a927d88dd0f0014b">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd978f260db7edab0958b174afadb59">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba205f553f24c184ea47fc1a6cb56537">One</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066220c7a472d8793de64a0ad23487d2">makeConstant</a> (const APInt &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create known bits from a known constant. <a href="#a066220c7a472d8793de64a0ad23487d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa7b7625b6a1ce9865f92f9b8387962a">haveNoCommonBitsSet</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if LHS and RHS have no common bits set. <a href="#aaa7b7625b6a1ce9865f92f9b8387962a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae38c1d54e2059046460391f880fa837">computeForAddCarry</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, const KnownBits &amp;Carry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits resulting from adding LHS, RHS and a 1-bit Carry. <a href="#aae38c1d54e2059046460391f880fa837">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a> (bool Add, bool NSW, bool NUW, const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits resulting from adding LHS and RHS. <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79fab52167a8bf5725ab31360b7e1546">computeForSubBorrow</a> (const KnownBits &amp;LHS, KnownBits RHS, const KnownBits &amp;Borrow)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits results from subtracting RHS from LHS with 1-bit Borrow. <a href="#a79fab52167a8bf5725ab31360b7e1546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4bd85cb03fa4d3b2c5c67cd4af39a5">add</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool NSW=false, bool NUW=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from addition of LHS and RHS. <a href="#a7a4bd85cb03fa4d3b2c5c67cd4af39a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaedcbc66cfec0117e98d503c89234716">sub</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool NSW=false, bool NUW=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from subtraction of LHS and RHS. <a href="#aaedcbc66cfec0117e98d503c89234716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0931faba5bc3ca7787159791488769dd">sadd_sat</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from llvm.sadd.sat(LHS, RHS) <a href="#a0931faba5bc3ca7787159791488769dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbef45a09397663c2ffdae818a00e3b5">uadd_sat</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from llvm.uadd.sat(LHS, RHS) <a href="#abbef45a09397663c2ffdae818a00e3b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a205a7518b8f3eef3fa4e9b812fb4f6fe">ssub_sat</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from llvm.ssub.sat(LHS, RHS) <a href="#a205a7518b8f3eef3fa4e9b812fb4f6fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b58fb130fd24756c4e0b59c779969ec">usub_sat</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from llvm.usub.sat(LHS, RHS) <a href="#a1b58fb130fd24756c4e0b59c779969ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bc6da2cdb1e781be6a4ccef2fdf954">avgFloorS</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ac88b16b78495ecc2a39d8ea2edfac348">APIntOps::avgFloorS</a>. <a href="#aa2bc6da2cdb1e781be6a4ccef2fdf954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a724958d37dfb62b07a6e3649f8375469">avgFloorU</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a2ea7b7f0afc0808540ac70cdafa55282">APIntOps::avgFloorU</a>. <a href="#a724958d37dfb62b07a6e3649f8375469">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac275f11600acd55aade8c6aaf9276e">avgCeilS</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ae65bb783d9d91ee10713c1ed6cec2372">APIntOps::avgCeilS</a>. <a href="#afac275f11600acd55aade8c6aaf9276e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ed19a0340f28b453449cbcf090cd5b">avgCeilU</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a21eee0c8f0c796e98feca7ee206bbb83">APIntOps::avgCeilU</a>. <a href="#ab7ed19a0340f28b453449cbcf090cd5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd85d08f35600dd19615a1efe9cacb1d">mul</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool NoUndefSelfMultiply=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits resulting from multiplying LHS and RHS. <a href="#abd85d08f35600dd19615a1efe9cacb1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dae6aee21422ec66b035112413bfe57">mulhs</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits from sign-extended multiply-hi. <a href="#a8dae6aee21422ec66b035112413bfe57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0edc5762eddccb62268e45a5ea231d9c">mulhu</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits from zero-extended multiply-hi. <a href="#a0edc5762eddccb62268e45a5ea231d9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4c03962b079bed0cd6c59256844bb5">sdiv</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool Exact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for sdiv(LHS, RHS). <a href="#a9f4c03962b079bed0cd6c59256844bb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96120d4062fabb503b1b92401e54d14f">udiv</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool Exact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for udiv(LHS, RHS). <a href="#a96120d4062fabb503b1b92401e54d14f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2838364c4863a3b2c55c6fd7052413aa">urem</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for urem(LHS, RHS). <a href="#a2838364c4863a3b2c55c6fd7052413aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905d2324c26b7a6f5aeb929a734ce0bc">srem</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for srem(LHS, RHS). <a href="#a905d2324c26b7a6f5aeb929a734ce0bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5120eaa394627e6c1ec3d66ef77947cd">umax</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for umax(LHS, RHS). <a href="#a5120eaa394627e6c1ec3d66ef77947cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea97402782d7e8098b6ae00c7a6365dd">umin</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for umin(LHS, RHS). <a href="#aea97402782d7e8098b6ae00c7a6365dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137874360a1967ac811fe9e5d7605eee">smax</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for smax(LHS, RHS). <a href="#a137874360a1967ac811fe9e5d7605eee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b6ba94fe7d3ee69dbeed7350fad096">smin</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for smin(LHS, RHS). <a href="#a87b6ba94fe7d3ee69dbeed7350fad096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619bf8b8706419faa337604558a70bdd">abdu</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for abdu(LHS, RHS). <a href="#a619bf8b8706419faa337604558a70bdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a864f5b0ab8f1fa7249cf280e6b572620">abds</a> (KnownBits LHS, KnownBits RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for abds(LHS, RHS). <a href="#a864f5b0ab8f1fa7249cf280e6b572620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool NUW=false, bool NSW=false, bool ShAmtNonZero=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for shl(LHS, RHS). <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool ShAmtNonZero=false, bool Exact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for lshr(LHS, RHS). <a href="#a5c34f40ce539320222a15a88ebcef716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, bool ShAmtNonZero=false, bool Exact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute known bits for ashr(LHS, RHS). <a href="#a1f1be83c0efdaff4af051b7a45faaba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aef6b7958c3eebec986bd226aca7325">eq</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_EQ result. <a href="#a0aef6b7958c3eebec986bd226aca7325">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d526cdaed505fb03e49f7bd0c96724f">ne</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_NE result. <a href="#a2d526cdaed505fb03e49f7bd0c96724f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e582ead745c86654cd8d0e1228f0c5">ugt</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_UGT result. <a href="#a92e582ead745c86654cd8d0e1228f0c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86f53ca31fd59930678248efbfaf516">uge</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_UGE result. <a href="#ad86f53ca31fd59930678248efbfaf516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d9eb764d22c7fabfecf5164123cc18">ult</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_ULT result. <a href="#aa0d9eb764d22c7fabfecf5164123cc18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a47d48d5537edfc125ee8ed5659955">ule</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_ULE result. <a href="#aa8a47d48d5537edfc125ee8ed5659955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20d9f61ec3c5c2a0bd9163cb6c15335">sgt</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_SGT result. <a href="#ad20d9f61ec3c5c2a0bd9163cb6c15335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466e550382eee7535225b95ef91914d1">sge</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_SGE result. <a href="#a466e550382eee7535225b95ef91914d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97cc47234699c26a59495f019e3fb1e3">slt</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_SLT result. <a href="#a97cc47234699c26a59495f019e3fb1e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc61013b6ddecc5b9c8105aa961b71f2">sle</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if these known bits always give the same ICMP_SLE result. <a href="#acc61013b6ddecc5b9c8105aa961b71f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bfd55a2dd28409a0b3fd6be8b48037b">flipSignBit</a> (const KnownBits &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2eeb158fdabbe59f01c0c623706670">remGetLowBits</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS)</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### KnownBits() {#a84015e5252bbac2c6d1174218ff425b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::KnownBits::KnownBits ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Referenced by <a href="#ac6661654e5ce1b32651508eec50b6d58">anyext</a>, <a href="#a4421e5acdca3cb36134d66d5a06e23b2">byteSwap</a>, <a href="#a4d1c9028cc02b58ce040aa83456c9129">concat</a>, <a href="#a6f1c4a256c58844fb8dc8aa154f335a4">extractBits</a>, <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>, <a href="#a066220c7a472d8793de64a0ad23487d2">makeConstant</a>, <a href="#a2ed221e7e8b34742e248f6f81ef15f90">makeGE</a>, <a href="#a48c734dfebb2a1b9faa891d2d2c3a807">reverseBits</a>, <a href="#a781ca23d84995ffb2efaa51267053c19">sext</a>, <a href="#a87b6ba94fe7d3ee69dbeed7350fad096">smin</a>, <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a>, <a href="#aea97402782d7e8098b6ae00c7a6365dd">umin</a>, <a href="#a5bb97a9e9a3717af2794011459f03607">unionWith</a> and <a href="#a51c3c203b80468b8761416d14e6f5b7f">zext</a>.</p>

</div>
</div>

### KnownBits() {#ad8b9eeb5b297d56ea1ee595eefa3f6da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::KnownBits::KnownBits (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a known bits object of BitWidth bits initialized to unknown.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### KnownBits() {#a73524f65f9c0b6998c346e5a34e9b7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::KnownBits::KnownBits (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> Zero, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> One)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aa75e5a8528fd989ecd2fa91944a1a800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator&amp;=() {#a87e2143cbd13db0b1cbb093919b9b15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits &amp; KnownBits::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update known bits based on ANDing with RHS.</p>

<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1095 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### operator^=() {#ae2632149f66b099426f2dcff58ed93b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits &amp; KnownBits::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update known bits based on XORing with RHS.</p>

<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### operator==() {#a69bc6f1c1c1a81f7679a9086271b9c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### operator|=() {#a48db7eb3db95cfbfd19f699b996843fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits &amp; KnownBits::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update known bits based on ORing with RHS.</p>

<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### abs() {#ac9384ac452485cfed65a93b238080793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::abs (bool IntMinIsPoison=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute known bits for the absolute value.</p>

<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#af883359d8cdce0f853270b28d7bfc564">llvm::APInt::clearSignBit</a>, <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="#a4676f4bc7da9235ff3b6683dd670d7be">countMaxPopulation</a>, <a href="#a2ad6370e532a52014fe2e5a54bfbaddd">countMaxTrailingZeros</a>, <a href="#a7f47812e8e75b0616a97d7004e5fb909">countMinLeadingZeros</a>, <a href="#ad2ecbbccee1ca4e3ddde24cc714ec79e">countMinPopulation</a>, <a href="#a1eeff70353694cb360b2893553c18e7d">countMinTrailingZeros</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#aabc0af41b4437080b27002ed7a1ed656">isNegative</a>, <a href="#a157efd68e8b4b838829cad165b1583f8">isNonNegative</a>, <a href="#a066220c7a472d8793de64a0ad23487d2">makeConstant</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a33f9f862dca8ee0f23bff5941bf433d8">llvm::APInt::setBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb95d5d8e87df053e1b53e2ec60de4b6">llvm::APInt::setBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>.</p>

</div>
</div>

### anyext() {#ac6661654e5ce1b32651508eec50b6d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::anyext (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for an "any" extension of the value we're tracking, where we don't know anything about the extended bits.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a0c649ec21217b3feb2f2a28b4736b689">anyextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9eab4ee0cc74f24e0720d3383497f2ca">computeKnownBitsFromICmpCond</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a53ba73377df4268433b190a98516ce8d">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a>.</p>

</div>
</div>

### anyextOrTrunc() {#a0c649ec21217b3feb2f2a28b4736b689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::anyextOrTrunc (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for an "any" extension or truncation of the value we're tracking.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#ac6661654e5ce1b32651508eec50b6d58">anyext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a> and <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### blsi() {#a18790dbaa8ba6bb118ea10e8643a0597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::blsi ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute known bits for X &amp; -X, which has only the lowest bit set of X set.</p>


<p>The name comes from the <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> BMI instruction</p>


<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a2ad6370e532a52014fe2e5a54bfbaddd">countMaxTrailingZeros</a>, <a href="#a1eeff70353694cb360b2893553c18e7d">countMinTrailingZeros</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a33f9f862dca8ee0f23bff5941bf433d8">llvm::APInt::setBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a286d4fa2a50c9ac6ac3a8069cccfcd0c">llvm::APInt::setBitsFrom</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>.</p>

</div>
</div>

### blsmsk() {#a3672d546ea0f6b4748807c35d620bdc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::blsmsk ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute known bits for X ^ (X - 1), which has all bits up to and including the lowest set bit of X set.</p>


<p>The name comes from the <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> BMI instruction.</p>


<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a2ad6370e532a52014fe2e5a54bfbaddd">countMaxTrailingZeros</a>, <a href="#a1eeff70353694cb360b2893553c18e7d">countMinTrailingZeros</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a286d4fa2a50c9ac6ac3a8069cccfcd0c">llvm::APInt::setBitsFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>.</p>

</div>
</div>

### byteSwap() {#a4421e5acdca3cb36134d66d5a06e23b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::byteSwap ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### concat() {#a4d1c9028cc02b58ce040aa83456c9129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::concat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Lo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Concatenate the bits from <span class="doxyComputerOutput">Lo</span> onto the bottom of *this.</p>


<p>This is equivalent to: (this-&gt;zext(NewWidth) &lt;&lt; Lo.getBitWidth()) | Lo.zext(NewWidth)</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### countMaxActiveBits() {#a70674aa792d906276123ab69dbdbfc69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxActiveBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of bits needed to represent all possible unsigned values with these known bits.</p>


<p>This is the inverse of the minimum number of leading zeros.</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a7f47812e8e75b0616a97d7004e5fb909">countMinLeadingZeros</a> and <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5aa226cd70fb4a0c7e597d6455601d5b">combinePMULH</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab60e9136a31f4054b79740f601cba282">detectExtMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d4c97240f140a6a8c3003d0e19798be">getPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#acd87db70cdd379bbe637cdd47902e3c1">llvm::AMDGPUTargetLowering::numBitsUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9843d498d81fb04dfb533d4702589ae8">performSIGN_EXTEND_INREGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0614870543ce4ba5b6f9c7030d6867e2">simplifyLShrInst</a>.</p>

</div>
</div>

### countMaxLeadingOnes() {#ada00227b6d66e62162700f62c56cd98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxLeadingOnes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of leading one bits possible.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### countMaxLeadingZeros() {#aaf8d1fc0f6386ef04a4b991fd73d823b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxLeadingZeros ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of leading zero bits possible.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>.</p>

</div>
</div>

### countMaxPopulation() {#a4676f4bc7da9235ff3b6683dd670d7be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxPopulation ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of bits that could be one.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa9941226cefb2787fa29507c4f5630d6">llvm::isKnownToBeAPowerOfTwo</a>.</p>

</div>
</div>

### countMaxSignificantBits() {#ad09e08dbb0765df54b4d2a8fc8a1abca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxSignificantBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of bits needed to represent all possible signed values with these known bits.</p>


<p>This is the inverse of the minimum number of known sign bits. Examples for bitwidth 5: 110?? --&gt; 4 0000? --&gt; 2</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a10303a2ffd5366402dfdb65bc55fcff1">countMinSignBits</a> and <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>.</p>

</div>
</div>

### countMaxTrailingOnes() {#a0a3d297e00e7ddbced461c33c84a822b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxTrailingOnes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of trailing one bits possible.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### countMaxTrailingZeros() {#a2ad6370e532a52014fe2e5a54bfbaddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMaxTrailingZeros ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the maximum number of trailing zero bits possible.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="#a18790dbaa8ba6bb118ea10e8643a0597">blsi</a>, <a href="#a3672d546ea0f6b4748807c35d620bdc9">blsmsk</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a072564155d82c8422dea82420d368d54">isNonZeroMul</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>.</p>

</div>
</div>

### countMinLeadingOnes() {#a1d90fff0f1479f662286338ffecd7f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMinLeadingOnes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum number of leading one bits.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#a10303a2ffd5366402dfdb65bc55fcff1">countMinSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a9910dce4a3e020d503a0e4062d66646f">llvm::GCNTTIImpl::rewriteIntrinsicWithAddressSpace</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

</div>
</div>

### countMinLeadingZeros() {#a7f47812e8e75b0616a97d7004e5fb909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMinLeadingZeros ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum number of leading zero bits.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aac8364da8771a03bcc990c3c0d6ccfb6">checkDot4MulSignedness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#afa64cc7dfc401b9825b62c2b19808ad0">combineShiftToAVG</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#a70674aa792d906276123ab69dbdbfc69">countMaxActiveBits</a>, <a href="#a10303a2ffd5366402dfdb65bc55fcff1">countMinSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5d6281f602a2d61050f8e8214c34b16e">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getDivNumBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aac5576a66149a9259706758d613ba555">isKnownExactCastIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5a9400ffd60b322631432e54cb995b16">LowerAndToBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7e14f814ee1df3b4559181a7284b0918">llvm::SITargetLowering::lowerSET_ROUNDING</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe25313da4ec14f1e260d91672c31545">lowerShuffleWithVPMOV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac76473b9005e8953bfde5975fc7d2eca">matchTruncateWithPACK</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4a2c60919236f6bec42a5a1cd2e0fadb">llvm::AMDGPUTargetLowering::performShlCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

</div>
</div>

### countMinPopulation() {#ad2ecbbccee1ca4e3ddde24cc714ec79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMinPopulation ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of bits known to be one.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa9941226cefb2787fa29507c4f5630d6">llvm::isKnownToBeAPowerOfTwo</a>.</p>

</div>
</div>

### countMinSignBits() {#a10303a2ffd5366402dfdb65bc55fcff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMinSignBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of times the sign bit is replicated into the other bits.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a1d90fff0f1479f662286338ffecd7f05">countMinLeadingOnes</a>, <a href="#a7f47812e8e75b0616a97d7004e5fb909">countMinLeadingZeros</a>, <a href="#aabc0af41b4437080b27002ed7a1ed656">isNegative</a> and <a href="#a157efd68e8b4b838829cad165b1583f8">isNonNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="#ad09e08dbb0765df54b4d2a8fc8a1abca">countMaxSignificantBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>.</p>

</div>
</div>

### countMinTrailingOnes() {#a7969b5a4964ca451ebc622ecf6bb4120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMinTrailingOnes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum number of trailing one bits.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>.</p>

</div>
</div>

### countMinTrailingZeros() {#a1eeff70353694cb360b2893553c18e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::countMinTrailingZeros ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the minimum number of trailing zero bits.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="#a18790dbaa8ba6bb118ea10e8643a0597">blsi</a>, <a href="#a3672d546ea0f6b4748807c35d620bdc9">blsmsk</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e7b79b3933def717c2a0f2fc6fa38e0">llvm::getOrEnforceKnownAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferalignment-cpp/#a8bceeb1a77614890ce9fc9a637c68b2b">inferAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8d72d0dbb6d5ab8b970a32519122d85c">llvm::SelectionDAG::InferPtrAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#af0a50c83ebf42c8d7a95ee2f13fb557e">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::isDWORDAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aac5576a66149a9259706758d613ba555">isKnownExactCastIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a574081bb34839434016edaf8d3fb16e3">isWordAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>.</p>

</div>
</div>

### dump() {#a9cd978f260db7edab0958b174afadb59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void KnownBits::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a4d0179756dcc99d6a927d88dd0f0014b">print</a>.</p>

</div>
</div>

### extractBits() {#a6f1c4a256c58844fb8dc8aa154f335a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::extractBits (unsigned NumBits, unsigned BitPosition)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a subset of the known bits from [bitPosition,bitPosition+numBits).</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="#a8dae6aee21422ec66b035112413bfe57">mulhs</a>, <a href="#a0edc5762eddccb62268e45a5ea231d9c">mulhu</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### getBitWidth() {#a4fdc09049a61f952b5d52788dbd2f69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::KnownBits::getBitWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the bit width of this value.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="#a0c649ec21217b3feb2f2a28b4736b689">anyextOrTrunc</a>, <a href="#a18790dbaa8ba6bb118ea10e8643a0597">blsi</a>, <a href="#a3672d546ea0f6b4748807c35d620bdc9">blsmsk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63a699ff4d2df76812431793394bf85a">combineFMulcFCMulc</a>, <a href="#aae38c1d54e2059046460391f880fa837">computeForAddCarry</a>, <a href="#a79fab52167a8bf5725ab31360b7e1546">computeForSubBorrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a5974d2150b4875417b407ee6a06ff640">llvm::LanaiTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9af897150a3eb273fe40904424fe49d6">computeKnownBitsFromCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9eab4ee0cc74f24e0720d3383497f2ca">computeKnownBitsFromICmpCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ac9d20e43bcbe654bcafdbab570e64404">computeKnownBitsFromShiftOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="#a70674aa792d906276123ab69dbdbfc69">countMaxActiveBits</a>, <a href="#a4676f4bc7da9235ff3b6683dd670d7be">countMaxPopulation</a>, <a href="#ad09e08dbb0765df54b4d2a8fc8a1abca">countMaxSignificantBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a53ba73377df4268433b190a98516ce8d">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e7b79b3933def717c2a0f2fc6fa38e0">llvm::getOrEnforceKnownAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferalignment-cpp/#a8bceeb1a77614890ce9fc9a637c68b2b">inferAlignment</a>, <a href="#a5274c29c7da2473d342adfa98f34a025">isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="#a2ed221e7e8b34742e248f6f81ef15f90">makeGE</a>, <a href="#a4d0179756dcc99d6a927d88dd0f0014b">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="#a0c936127975e910ae794122a057b067d">sextInReg</a>, <a href="#af7b0f10768256c95094a03348ee5fd32">sextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afcc877a26419c2aef195256bc0aa01e3">llvm::InstCombinerImpl::SimplifyDemandedInstructionBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="#a87b6ba94fe7d3ee69dbeed7350fad096">smin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>, <a href="#a51c3c203b80468b8761416d14e6f5b7f">zext</a> and <a href="#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">zextOrTrunc</a>.</p>

</div>
</div>

### getConstant() {#afd1c330d00d17bd267450ab43d5f0eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APInt &amp; llvm::KnownBits::getConstant ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the value when all bits have a known value.</p>


<p>This just returns One with a protective assertion.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5274c29c7da2473d342adfa98f34a025">isConstant</a> and <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63a699ff4d2df76812431793394bf85a">combineFMulcFCMulc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a1747fa66edae41ea9492c338ef853e12">llvm::GCNTTIImpl::simplifyDemandedLaneMaskArg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4515378302b14f9df5b64311e4c84a80">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### getMaxValue() {#a825476b2436eb817b735fdd34ee521c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::KnownBits::getMaxValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximal unsigned value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac83bcada2a1e9fdfeb3a5215fff012da">llvm::SelectionDAG::canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ac9d20e43bcbe654bcafdbab570e64404">computeKnownBitsFromShiftOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac8a8f784b3b05320fec4c962f5b4505b">llvm::SelectionDAG::computeOverflowForUnsignedAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#a1d8f39cf98f0412e82e2f5bd03a09b99">extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebfb90f3ee1b2d4d5637e74d012424af">llvm::SelectionDAG::getValidShiftAmountRange</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a056e5a535ce9d93f9c20adcce79b519f">setShiftFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ac90052ea1afde8fc28fe6f27181fd5f2">simplifyAndInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>.</p>

</div>
</div>

### getMinValue() {#a9b35c622a902a7a7dc93b807a9fa9265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::KnownBits::getMinValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the minimal unsigned value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#a1d8f39cf98f0412e82e2f5bd03a09b99">extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>.</p>

</div>
</div>

### getSignedMaxValue() {#a30c829b0f51e87159f116f980af6237d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::KnownBits::getSignedMaxValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the maximal signed value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>.</p>

</div>
</div>

### getSignedMinValue() {#ae0b0ab35dee6bb5d9d53098111bf5c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::KnownBits::getSignedMinValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the minimal signed value possible given these <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae5f691e699950ed2bb93f29742112068">cannotBeIntMin</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>.</p>

</div>
</div>

### hasConflict() {#a44875c6f48f6c843cf3114a19280b5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::hasConflict ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if there is conflicting information.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a>, <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>

</div>
</div>

### insertBits() {#ab41beafb710aa35f1b793e5876bf2c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownBits::insertBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; SubBits, unsigned BitPosition)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert the bits from a smaller known bits starting at bitPosition.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### intersectWith() {#a76e45a40f2f0b5b09132d1de119765e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::intersectWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> information that is known to be true for both this and RHS.</p>


<p>When an operation is known to return one of its operands, this can be used to combine information about the known bits of the operands to get the information that must be true about the result.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a864f5b0ab8f1fa7249cf280e6b572620">abds</a>, <a href="#a619bf8b8706419faa337604558a70bdd">abdu</a>, <a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afabf09fd843eff2512ec021a768e50ff">computeKnownBitsBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a5974d2150b4875417b407ee6a06ff640">llvm::LanaiTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a71ac95c34a6f80744df3010b673fc9e6">llvm::SparcTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9af897150a3eb273fe40904424fe49d6">computeKnownBitsFromCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### isAllOnes() {#af3680fca8d50d56b690bed3ac6c1f68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isAllOnes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if value is all one bits.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa142b4be3c3ce29d1c12c39b88ec687d">isTruncateOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### isConstant() {#a5274c29c7da2473d342adfa98f34a025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isConstant ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we know the value of all bits.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63a699ff4d2df76812431793394bf85a">combineFMulcFCMulc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="#afd1c330d00d17bd267450ab43d5f0eec">getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a1747fa66edae41ea9492c338ef853e12">llvm::GCNTTIImpl::simplifyDemandedLaneMaskArg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4515378302b14f9df5b64311e4c84a80">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>.</p>

</div>
</div>

### isNegative() {#aabc0af41b4437080b27002ed7a1ed656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this value is known to be negative.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#abd32d02eec0cbcb44e4b7665babc7125">computeOverflowForSignedAdd</a>, <a href="#a10303a2ffd5366402dfdb65bc55fcff1">countMinSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5d6281f602a2d61050f8e8214c34b16e">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getDivNumBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a660c0e2a422273548d57b9573ee332f2">getKnownSign</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#abe36fa76137ff4c78ce9f558258e1e80">getSign32</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>.</p>

</div>
</div>

### isNonNegative() {#a157efd68e8b4b838829cad165b1583f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isNonNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this value is known to be non-negative.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#abd32d02eec0cbcb44e4b7665babc7125">computeOverflowForSignedAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a874815cd838916d66cd1408438e0cb51">llvm::computeOverflowForSignedMul</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8cb17b09c9253a79ade3ca32113f3eb7">llvm::SelectionDAG::computeOverflowForSignedMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62fdc50378ed0e117f3c4e829f9d68a8">llvm::computeOverflowForUnsignedMul</a>, <a href="#a10303a2ffd5366402dfdb65bc55fcff1">countMinSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a5d6281f602a2d61050f8e8214c34b16e">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::getDivNumBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a660c0e2a422273548d57b9573ee332f2">getKnownSign</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a7735bcf6952625dbe3ccc49f428feb09">getMinUselessShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#abe36fa76137ff4c78ce9f558258e1e80">getSign32</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae406040430d4b1e6f514e5e4686dc831">llvm::isKnownPositive</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a738d3c4d8f36cf843825c2b5a878f58a">simplifyICmpWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>.</p>

</div>
</div>

### isNonZero() {#a5d774365f4d1120b030d026860193a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isNonZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this value is known to be non-zero.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ac9d20e43bcbe654bcafdbab570e64404">computeKnownBitsFromShiftOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae406040430d4b1e6f514e5e4686dc831">llvm::isKnownPositive</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a072564155d82c8422dea82420d368d54">isNonZeroMul</a>, <a href="#a905d2324c26b7a6f5aeb929a734ce0bc">srem</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### isSignUnknown() {#a5c853e7ffb5929484f42ab5b4d48c47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isSignUnknown ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we don't know the sign bit.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### isStrictlyPositive() {#a9e89086daed6298a9f768aae9bf9675a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isStrictlyPositive ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this value is known to be positive.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>.</p>

</div>
</div>

### isUnknown() {#a28cf355963391ab8781b2347d495553d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isUnknown ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we don't know any bits.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a5afb7d50f639285c9ef082439615915e">llvm::FunctionLoweringInfo::AddLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6e77f310e4bf797a1cff5df8c386df70">computeKnownBitsAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a211874a1535ba321cab61942cde9398f">llvm::ConstantRange::fromKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad9804726a37a620da474deef91f667eb">llvm::CombinerHelper::matchRedundantAnd</a> and <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a>.</p>

</div>
</div>

### isZero() {#a1620c017d995c7ccbcb59e0212618017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::isZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if value is all zero.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0a759ab1a22390b2f549a138e92c20e">LowerVectorAllEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac25d8581d098d4c817c5602c5907967f">llvm::SelectionDAG::MaskedVectorIsZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>.</p>

</div>
</div>

### makeGE() {#a2ed221e7e8b34742e248f6f81ef15f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::makeGE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> based on this, but updated given that the underlying value is known to be greater than or equal to Val.</p>

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#aac76bff09195240a482b319136ab6144">llvm::APInt::clearLowBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d92de57590536d2f254fe5e903e3372">llvm::countl_one</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>

</div>
</div>

### makeNegative() {#a36d9168813b2a8415c085ac551c54458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownBits::makeNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make this value negative.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a256114e633f673cf57611169e1ade5c6">unaryOpKnownBitsMapHelper</a>.</p>

</div>
</div>

### makeNonNegative() {#a192e15f89a5aa04df018639812e2c4db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownBits::makeNonNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make this value non-negative.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Reference <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a256114e633f673cf57611169e1ade5c6">unaryOpKnownBitsMapHelper</a>.</p>

</div>
</div>

### print() {#a4d0179756dcc99d6a927d88dd0f0014b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void KnownBits::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a9cd978f260db7edab0958b174afadb59">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0369037599a859efc2fd1179d076ce93">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### resetAll() {#a538f22b4ea2ff04a0b41403f26eaeb67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownBits::resetAll ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resets the known state of all bits.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5be8668f644eaefda25f6905908bd9f3">llvm::PPCTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7b936082e1b7db71c559544b9cb8b0b2">llvm::SITargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a71ac95c34a6f80744df3010b673fc9e6">llvm::SparcTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7e500d9f027b07d62374f0cee5d56724">llvm::InstCombinerImpl::SimplifyDemandedBits</a>.</p>

</div>
</div>

### reverseBits() {#a48c734dfebb2a1b9faa891d2d2c3a807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::reverseBits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### setAllOnes() {#ab0f473e7109b116f0337cbe78964e6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownBits::setAllOnes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make all bits known to be one and discard any previous information.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>.</p>

</div>
</div>

### setAllZero() {#a4816b869391aac5bbcce9c889c2ecd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::KnownBits::setAllZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make all bits known to be zero and discard any previous information.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a>, <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a>, <a href="#a9f4c03962b079bed0cd6c59256844bb5">sdiv</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="#a96120d4062fabb503b1b92401e54d14f">udiv</a>.</p>

</div>
</div>

### sext() {#a781ca23d84995ffb2efaa51267053c19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::sext (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for a sign extension of the value we're tracking.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa16bb473dbb4b04fd2b11ccb72660b0e">computeKnownBitsForPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3caf52501b70f5695183149e578fbd5a">computeKnownBitsForPMADDWD</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="#af7b0f10768256c95094a03348ee5fd32">sextOrTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### sextInReg() {#a0c936127975e910ae794122a057b067d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::sextInReg (unsigned SrcBitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for a in-register sign extension of the value we're tracking.</p>

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### sextOrTrunc() {#af7b0f10768256c95094a03348ee5fd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::sextOrTrunc (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for a sign extension or truncation of the value we're tracking.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#a781ca23d84995ffb2efaa51267053c19">sext</a> and <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### trunc() {#a40a666d8a3b58f5eca5d7f9f26796bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::trunc (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for a truncation of the value we're tracking.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a0c649ec21217b3feb2f2a28b4736b689">anyextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#af7b0f10768256c95094a03348ee5fd32">sextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">zextOrTrunc</a>.</p>

</div>
</div>

### unionWith() {#a5bb97a9e9a3717af2794011459f03607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::unionWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> information that is known to be true for either this or RHS or both.</p>


<p>This can be used to combine different sources of information about the known bits of a single value, e.g. information about the low bits and the high bits of the result of a multiplication.</p>


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6d830b26db3b7e76253b7d2afb906400">llvm::adjustKnownBitsForSelectArm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9af897150a3eb273fe40904424fe49d6">computeKnownBitsFromCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9eab4ee0cc74f24e0720d3383497f2ca">computeKnownBitsFromICmpCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a7ddee2fbb9f51592ab6c0a93bd1b7325">unionWithMinMaxIntrinsicClamp</a>.</p>

</div>
</div>

### zext() {#a51c3c203b80468b8761416d14e6f5b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::zext (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for a zero extension of the value we're tracking.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a286d4fa2a50c9ac6ac3a8069cccfcd0c">llvm::APInt::setBitsFrom</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa16bb473dbb4b04fd2b11ccb72660b0e">computeKnownBitsForPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36334a70d900ffeea3274a6078fce675">computeKnownBitsForPSADBW</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a2af1c2f9cad56166d08fabb205463d15">fromOptionalToKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="#a7ddb13bdf305b1d4eee7bf1a9ac9d35e">zextOrTrunc</a>.</p>

</div>
</div>

### zextOrTrunc() {#a7ddb13bdf305b1d4eee7bf1a9ac9d35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::zextOrTrunc (unsigned BitWidth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return known bits for a zero extension or truncation of the value we're tracking.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a> and <a href="#a51c3c203b80468b8761416d14e6f5b7f">zext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### One {#aba205f553f24c184ea47fc1a6cb56537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::KnownBits::One</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a5afb7d50f639285c9ef082439615915e">llvm::FunctionLoweringInfo::AddLiveOutRegInfo</a>, <a href="#ac6661654e5ce1b32651508eec50b6d58">anyext</a>, <a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1f9b8b85cda6501eec16b6804b22c8c1">llvm::ConstantRange::binaryXor</a>, <a href="#a18790dbaa8ba6bb118ea10e8643a0597">blsi</a>, <a href="#a3672d546ea0f6b4748807c35d620bdc9">blsmsk</a>, <a href="#a4421e5acdca3cb36134d66d5a06e23b2">byteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ac1aa55cef94698e03f5b38274a656b4f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::calculatePointerDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a088862cded43bb2202369f9346535d3a">llvm::SelectionDAGISel::CheckOrMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a97970fd9482411a9be5040e52fedbb53">computeForAddCarry</a>, <a href="#aae38c1d54e2059046460391f880fa837">computeForAddCarry</a>, <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="#a79fab52167a8bf5725ab31360b7e1546">computeForSubBorrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="#a4d1c9028cc02b58ce040aa83456c9129">concat</a>, <a href="#aaf8d1fc0f6386ef04a4b991fd73d823b">countMaxLeadingZeros</a>, <a href="#a2ad6370e532a52014fe2e5a54bfbaddd">countMaxTrailingZeros</a>, <a href="#a1d90fff0f1479f662286338ffecd7f05">countMinLeadingOnes</a>, <a href="#ad2ecbbccee1ca4e3ddde24cc714ec79e">countMinPopulation</a>, <a href="#a7969b5a4964ca451ebc622ecf6bb4120">countMinTrailingOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#ab5a4fedee642c9e9d2323ea22d7ae1cd">llvm::DemandedBits::determineLiveOperandBitsSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ae744642bc86b281d7458f66f962cc154">dumpResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="#a6f1c4a256c58844fb8dc8aa154f335a4">extractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#afd1c330d00d17bd267450ab43d5f0eec">getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a2c6988abbc44623a2f302ede7a8e63b2">llvm::GISelKnownBits::getKnownOnes</a>, <a href="#a9b35c622a902a7a7dc93b807a9fa9265">getMinValue</a>, <a href="#a30c829b0f51e87159f116f980af6237d">getSignedMaxValue</a>, <a href="#ae0b0ab35dee6bb5d9d53098111bf5c84">getSignedMinValue</a>, <a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a>, <a href="#ab41beafb710aa35f1b793e5876bf2c70">insertBits</a>, <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>, <a href="#af3680fca8d50d56b690bed3ac6c1f68e">isAllOnes</a>, <a href="#a5274c29c7da2473d342adfa98f34a025">isConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="#aabc0af41b4437080b27002ed7a1ed656">isNegative</a>, <a href="#a5d774365f4d1120b030d026860193a02">isNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a072564155d82c8422dea82420d368d54">isNonZeroMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="#a5c853e7ffb5929484f42ab5b4d48c47b">isSignUnknown</a>, <a href="#a9e89086daed6298a9f768aae9bf9675a">isStrictlyPositive</a>, <a href="#a28cf355963391ab8781b2347d495553d">isUnknown</a>, <a href="#ad8b9eeb5b297d56ea1ee595eefa3f6da">KnownBits</a>, <a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a>, <a href="#a2ed221e7e8b34742e248f6f81ef15f90">makeGE</a>, <a href="#a36d9168813b2a8415c085ac551c54458">makeNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad9804726a37a620da474deef91f667eb">llvm::CombinerHelper::matchRedundantAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac3416b258eb84253f8111ea33e0beeed">llvm::CombinerHelper::matchRedundantOr</a>, <a href="#abd85d08f35600dd19615a1efe9cacb1d">mul</a>, <a href="#a87e2143cbd13db0b1cbb093919b9b15b">operator&amp;=</a>, <a href="#a69bc6f1c1c1a81f7679a9086271b9c4e">operator==</a>, <a href="#ae2632149f66b099426f2dcff58ed93b7">operator^=</a>, <a href="#a48db7eb3db95cfbfd19f699b996843fb">operator|=</a>, <a href="#a4d0179756dcc99d6a927d88dd0f0014b">print</a>, <a href="#a538f22b4ea2ff04a0b41403f26eaeb67">resetAll</a>, <a href="#a48c734dfebb2a1b9faa891d2d2c3a807">reverseBits</a>, <a href="#a9f4c03962b079bed0cd6c59256844bb5">sdiv</a>, <a href="#ab0f473e7109b116f0337cbe78964e6af">setAllOnes</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="#a781ca23d84995ffb2efaa51267053c19">sext</a>, <a href="#a0c936127975e910ae794122a057b067d">sextInReg</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5bb5f4b5b2420a7f3950939b2de01330">simplifyRightShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="#a87b6ba94fe7d3ee69dbeed7350fad096">smin</a>, <a href="#a905d2324c26b7a6f5aeb929a734ce0bc">srem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4515378302b14f9df5b64311e4c84a80">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a47ce2e594a05222051dc71da56d75d9b">llvm::ConstantRange::toKnownBits</a>, <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a377cd94b272a4c49477b765611e4a434">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryBitfieldInsert</a>, <a href="#aea97402782d7e8098b6ae00c7a6365dd">umin</a>, <a href="#a5bb97a9e9a3717af2794011459f03607">unionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="#a51c3c203b80468b8761416d14e6f5b7f">zext</a>.</p>

</div>
</div>

### Zero {#ac67bca6c764da76f5e152330d92ed916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::KnownBits::Zero</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a5afb7d50f639285c9ef082439615915e">llvm::FunctionLoweringInfo::AddLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a1a88ad7ade00830072f900ca278ea978">adjustForRedundantAnd</a>, <a href="#ac6661654e5ce1b32651508eec50b6d58">anyext</a>, <a href="#a1f1be83c0efdaff4af051b7a45faaba7">ashr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1f9b8b85cda6501eec16b6804b22c8c1">llvm::ConstantRange::binaryXor</a>, <a href="#a18790dbaa8ba6bb118ea10e8643a0597">blsi</a>, <a href="#a3672d546ea0f6b4748807c35d620bdc9">blsmsk</a>, <a href="#a4421e5acdca3cb36134d66d5a06e23b2">byteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#ac1aa55cef94698e03f5b38274a656b4f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::calculatePointerDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a97970fd9482411a9be5040e52fedbb53">computeForAddCarry</a>, <a href="#aae38c1d54e2059046460391f880fa837">computeForAddCarry</a>, <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="#a79fab52167a8bf5725ab31360b7e1546">computeForSubBorrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a249a932d6f75f857e8caf11bcab9f920">llvm::GISelKnownBits::computeKnownBitsForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a59eb700f7620c6a3ebbdc281bc00d3bd">llvm::SITargetLowering::computeKnownBitsForFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a251b4037da222d49a7b332d241f63ea6">llvm::AMDGPUTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a5974d2150b4875417b407ee6a06ff640">llvm::LanaiTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5be8668f644eaefda25f6905908bd9f3">llvm::PPCTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7b936082e1b7db71c559544b9cb8b0b2">llvm::SITargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aef356d85debf0bf890152fe7f872db12">llvm::SystemZTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa0007d0a081ae03902143cb1f001afbb">llvm::SelectionDAG::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="#a4d1c9028cc02b58ce040aa83456c9129">concat</a>, <a href="#ada00227b6d66e62162700f62c56cd98c">countMaxLeadingOnes</a>, <a href="#a4676f4bc7da9235ff3b6683dd670d7be">countMaxPopulation</a>, <a href="#a0a3d297e00e7ddbced461c33c84a822b">countMaxTrailingOnes</a>, <a href="#a7f47812e8e75b0616a97d7004e5fb909">countMinLeadingZeros</a>, <a href="#a1eeff70353694cb360b2893553c18e7d">countMinTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#ab5a4fedee642c9e9d2323ea22d7ae1cd">llvm::DemandedBits::determineLiveOperandBitsSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#ae744642bc86b281d7458f66f962cc154">dumpResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="#a6f1c4a256c58844fb8dc8aa154f335a4">extractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad71a393fe3b7e73d1d8a9368576bf7db">getKnownBitsFromAndXorOr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#afa921e79a9e2303f303c40afb3ab222f">llvm::GISelKnownBits::getKnownZeroes</a>, <a href="#a825476b2436eb817b735fdd34ee521c4">getMaxValue</a>, <a href="#a30c829b0f51e87159f116f980af6237d">getSignedMaxValue</a>, <a href="#ae0b0ab35dee6bb5d9d53098111bf5c84">getSignedMinValue</a>, <a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a>, <a href="#ab41beafb710aa35f1b793e5876bf2c70">insertBits</a>, <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>, <a href="#a5274c29c7da2473d342adfa98f34a025">isConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a373d20116312d859aa88b46b48a8fd8c">isKnownNonEqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="#a157efd68e8b4b838829cad165b1583f8">isNonNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0b799cb5dcb4b61918829571a6aac98f">isNonZeroShift</a>, <a href="#a5c853e7ffb5929484f42ab5b4d48c47b">isSignUnknown</a>, <a href="#a9e89086daed6298a9f768aae9bf9675a">isStrictlyPositive</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa142b4be3c3ce29d1c12c39b88ec687d">isTruncateOf</a>, <a href="#a28cf355963391ab8781b2347d495553d">isUnknown</a>, <a href="#a1620c017d995c7ccbcb59e0212618017">isZero</a>, <a href="#ad8b9eeb5b297d56ea1ee595eefa3f6da">KnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac72c6a7fdaf91e99b6a6232207e57edc">knownBitsForWorkitemID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3b5afe10336a33630e00f86fab07c87">LowerMUL</a>, <a href="#a5c34f40ce539320222a15a88ebcef716">lshr</a>, <a href="#a2ed221e7e8b34742e248f6f81ef15f90">makeGE</a>, <a href="#a192e15f89a5aa04df018639812e2c4db">makeNonNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5738f911a81d4a66c8778d86be098dde">llvm::MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aad8006302bcaef8b07c0b8da5ea36fc2">matchBinaryShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad9804726a37a620da474deef91f667eb">llvm::CombinerHelper::matchRedundantAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac3416b258eb84253f8111ea33e0beeed">llvm::CombinerHelper::matchRedundantOr</a>, <a href="#abd85d08f35600dd19615a1efe9cacb1d">mul</a>, <a href="#a87e2143cbd13db0b1cbb093919b9b15b">operator&amp;=</a>, <a href="#a69bc6f1c1c1a81f7679a9086271b9c4e">operator==</a>, <a href="#ae2632149f66b099426f2dcff58ed93b7">operator^=</a>, <a href="#a48db7eb3db95cfbfd19f699b996843fb">operator|=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4ba6b9afcc5b700d4c09664b5fa009d9">llvm::ARMTargetLowering::PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ada7b7dfe4d829cdafff6278e361547df">llvm::ARMTargetLowering::PerformCMOVToBFICombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a3cb4731330867b7a71460d3f4daa752e">performORCombine</a>, <a href="#a4d0179756dcc99d6a927d88dd0f0014b">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">provablyDisjointOr</a>, <a href="#a538f22b4ea2ff04a0b41403f26eaeb67">resetAll</a>, <a href="#a48c734dfebb2a1b9faa891d2d2c3a807">reverseBits</a>, <a href="#a9f4c03962b079bed0cd6c59256844bb5">sdiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a312de8232fec3e0e128f4a34b7ddc55d">llvm::PPCTargetLowering::SelectAddressRegImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#adaf95509430b29d867f49362e176027d">llvm::PPCTargetLowering::SelectAddressRegImm34</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a521dc9b8649af234d8bf514085b9a640">llvm::PPCTargetLowering::SelectAddressRegReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a36d1b77a885effd5cefdd787a7935226">llvm::LoongArchDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af619c526b5e90968d76fbd4fe4c861cb">llvm::RISCVDAGToDAGISel::selectShiftMask</a>, <a href="#ab0f473e7109b116f0337cbe78964e6af">setAllOnes</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="#a781ca23d84995ffb2efaa51267053c19">sext</a>, <a href="#a0c936127975e910ae794122a057b067d">sextInReg</a>, <a href="#ae9ffa8b50ca6095202b2e8e7686c10b8">shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6fafb0a04f81d44e034566f1a758ea39">llvm::X86TargetLowering::SimplifyDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a49bff27cd8c639d90493b91350d3d9d0">llvm::X86TTIImpl::simplifyDemandedUseBitsIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="#a87b6ba94fe7d3ee69dbeed7350fad096">smin</a>, <a href="#a905d2324c26b7a6f5aeb929a734ce0bc">srem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4515378302b14f9df5b64311e4c84a80">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a47ce2e594a05222051dc71da56d75d9b">llvm::ConstantRange::toKnownBits</a>, <a href="#a40a666d8a3b58f5eca5d7f9f26796bc7">trunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a377cd94b272a4c49477b765611e4a434">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryBitfieldInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a380449a9ad9e4e2d3b6b3fdfa75a64d9">tryBitfieldInsertOpFromOrAndImm</a>, <a href="#a96120d4062fabb503b1b92401e54d14f">udiv</a>, <a href="#aea97402782d7e8098b6ae00c7a6365dd">umin</a>, <a href="#a5bb97a9e9a3717af2794011459f03607">unionWith</a>, <a href="#a2838364c4863a3b2c55c6fd7052413aa">urem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a> and <a href="#a51c3c203b80468b8761416d14e6f5b7f">zext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### abds() {#a864f5b0ab8f1fa7249cf280e6b572620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::abds (<a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> LHS, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> RHS)</td>
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

<p>Compute known bits for abds(LHS, RHS).</p>

<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a> and <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### abdu() {#a619bf8b8706419faa337604558a70bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::abdu (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for abdu(LHS, RHS).</p>

<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a> and <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36334a70d900ffeea3274a6078fce675">computeKnownBitsForPSADBW</a>.</p>

</div>
</div>

### add() {#a7a4bd85cb03fa4d3b2c5c67cd4af39a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool NSW=false, bool NUW=false)</td>
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

<p>Compute knownbits resulting from addition of LHS and RHS.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3caf52501b70f5695183149e578fbd5a">computeKnownBitsForPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36334a70d900ffeea3274a6078fce675">computeKnownBitsForPSADBW</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac680fd9aee1de89385f2ac2d1878ed9b">llvm::SITargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7b936082e1b7db71c559544b9cb8b0b2">llvm::SITargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae6c0c8f0395752e80e10f07861ed7e85">isNonZeroAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>.</p>

</div>
</div>

### ashr() {#a1f1be83c0efdaff4af051b7a45faaba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::ashr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool ShAmtNonZero=false, bool Exact=false)</td>
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

<p>Compute known bits for ashr(LHS, RHS).</p>


<p>NOTE: RHS (shift amount) bitwidth doesn't need to be the same as LHS.</p>


<p>Declaration at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e30b3aa214eba50eed018b5b19fc6aa">llvm::APInt::ashrInPlace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#aa18696894909136556d40020664aefe1">getMaxShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a>, <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>, <a href="#a28cf355963391ab8781b2347d495553d">isUnknown</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### avgCeilS() {#afac275f11600acd55aade8c6aaf9276e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::avgCeilS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ae65bb783d9d91ee10713c1ed6cec2372">APIntOps::avgCeilS</a>.</p>

<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#ab7ed19a0340f28b453449cbcf090cd5b">avgCeilU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### avgCeilU() {#ab7ed19a0340f28b453449cbcf090cd5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::avgCeilU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a21eee0c8f0c796e98feca7ee206bbb83">APIntOps::avgCeilU</a>.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a33a2235df9c9a82feea834f0955c2a4a">avgComputeU</a>.</p>


<p>Referenced by <a href="#afac275f11600acd55aade8c6aaf9276e">avgCeilS</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### avgFloorS() {#aa2bc6da2cdb1e781be6a4ccef2fdf954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::avgFloorS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ac88b16b78495ecc2a39d8ea2edfac348">APIntOps::avgFloorS</a>.</p>

<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#a724958d37dfb62b07a6e3649f8375469">avgFloorU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### avgFloorU() {#a724958d37dfb62b07a6e3649f8375469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::avgFloorU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a2ea7b7f0afc0808540ac70cdafa55282">APIntOps::avgFloorU</a>.</p>

<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a33a2235df9c9a82feea834f0955c2a4a">avgComputeU</a>.</p>


<p>Referenced by <a href="#aa2bc6da2cdb1e781be6a4ccef2fdf954">avgFloorS</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### computeForAddCarry() {#aae38c1d54e2059046460391f880fa837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::computeForAddCarry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Carry)</td>
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

<p>Compute known bits resulting from adding LHS, RHS and a 1-bit Carry.</p>

<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### computeForAddSub() {#a9c1c6dc178ce30e4a6c09f5c08727d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::computeForAddSub (bool Add, bool NSW, bool NUW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits resulting from adding LHS and RHS.</p>

<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#aae38c1d54e2059046460391f880fa837">computeForAddCarry</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa619d96a87c8a5be606b1a4a4ac0115d">llvm::APInt::countl_one</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac8c0157adbe12649beac0009c2f6ad8d">llvm::APInt::isNonNegative</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3c1e0381aeb551ad0ba58effe9232f97">llvm::APInt::sadd_sat</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb95d5d8e87df053e1b53e2ec60de4b6">llvm::APInt::setBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af888cb3cadd9a4e5f422c96e5674de88">llvm::APInt::ssub_sat</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab4c04665274d4f30d732639dc055821c">llvm::APInt::uadd_sat</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a059dc64e71df065315050d2270cbfba5">llvm::APInt::usub_sat</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="#a864f5b0ab8f1fa7249cf280e6b572620">abds</a>, <a href="#a619bf8b8706419faa337604558a70bdd">abdu</a>, <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="#a7a4bd85cb03fa4d3b2c5c67cd4af39a5">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6e77f310e4bf797a1cff5df8c386df70">computeKnownBitsAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a> and <a href="#aaedcbc66cfec0117e98d503c89234716">sub</a>.</p>

</div>
</div>

### computeForSubBorrow() {#a79fab52167a8bf5725ab31360b7e1546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::computeForSubBorrow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Borrow)</td>
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

<p>Compute known bits results from subtracting RHS from LHS with 1-bit Borrow.</p>

<p>Declaration at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>.</p>

</div>
</div>

### eq() {#a0aef6b7958c3eebec986bd226aca7325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::eq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_EQ result.</p>

<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a> and <a href="#a2d526cdaed505fb03e49f7bd0c96724f">ne</a>.</p>

</div>
</div>

### haveNoCommonBitsSet() {#aaa7b7625b6a1ce9865f92f9b8387962a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::KnownBits::haveNoCommonBitsSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Return true if LHS and RHS have no common bits set.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a00b5e7579e9af8d97960c790318cfebf">llvm::haveNoCommonBitsSet</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a376ebfcabb199bc876ed46505c33cb6b">llvm::SelectionDAG::haveNoCommonBitsSet</a>.</p>

</div>
</div>

### lshr() {#a5c34f40ce539320222a15a88ebcef716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::lshr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool ShAmtNonZero=false, bool Exact=false)</td>
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

<p>Compute known bits for lshr(LHS, RHS).</p>


<p>NOTE: RHS (shift amount) bitwidth doesn't need to be the same as LHS.</p>


<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#aa18696894909136556d40020664aefe1">getMaxShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a>, <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>, <a href="#a28cf355963391ab8781b2347d495553d">isUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/giselknownbits-cpp/#a1d8f39cf98f0412e82e2f5bd03a09b99">extractBits</a>.</p>

</div>
</div>

### makeConstant() {#a066220c7a472d8793de64a0ad23487d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::makeConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; C)</td>
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

<p>Create known bits from a known constant.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>.</p>


<p>Referenced by <a href="#ac9384ac452485cfed65a93b238080793">abs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a903bd19e9d31beff55b22fe86111639e">computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a76c547b25150612c3617877e2427e9fa">computeKnownBitsFromCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a2af1c2f9cad56166d08fabb205463d15">fromOptionalToKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#aa61330239617d3120b453b49c8654d3d">knownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a47ce2e594a05222051dc71da56d75d9b">llvm::ConstantRange::toKnownBits</a>.</p>

</div>
</div>

### mul() {#abd85d08f35600dd19615a1efe9cacb1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::mul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool NoUndefSelfMultiply=false)</td>
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

<p>Compute known bits resulting from multiplying LHS and RHS.</p>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8bad27827f46bca6baf814cbd2b64e84">llvm::APInt::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a239abca11deebf2731206dd41cf43c0e">llvm::countr_one</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0fa9845f80fa0642b31c238f4ab0d5ef">llvm::APInt::getLoBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a33f9f862dca8ee0f23bff5941bf433d8">llvm::APInt::setBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a028f4d1eead63cc33499ce3459bd27c7">llvm::APInt::umul_ov</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa16bb473dbb4b04fd2b11ccb72660b0e">computeKnownBitsForPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3caf52501b70f5695183149e578fbd5a">computeKnownBitsForPMADDWD</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3e4b8ac086cdc9c81f7c2eabd77394fc">llvm::ARMTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="#a8dae6aee21422ec66b035112413bfe57">mulhs</a> and <a href="#a0edc5762eddccb62268e45a5ea231d9c">mulhu</a>.</p>

</div>
</div>

### mulhs() {#a8dae6aee21422ec66b035112413bfe57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::mulhs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits from sign-extended multiply-hi.</p>

<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a6f1c4a256c58844fb8dc8aa154f335a4">extractBits</a> and <a href="#abd85d08f35600dd19615a1efe9cacb1d">mul</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### mulhu() {#a0edc5762eddccb62268e45a5ea231d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::mulhu (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits from zero-extended multiply-hi.</p>

<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a6f1c4a256c58844fb8dc8aa154f335a4">extractBits</a> and <a href="#abd85d08f35600dd19615a1efe9cacb1d">mul</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### ne() {#a2d526cdaed505fb03e49f7bd0c96724f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::ne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_NE result.</p>

<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#a0aef6b7958c3eebec986bd226aca7325">eq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4457fd8fd3e2fda5876b5b359775295">llvm::SelectionDAG::isKnownNeverZero</a>.</p>

</div>
</div>

### sadd\_sat() {#a0931faba5bc3ca7787159791488769dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::sadd_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from llvm.sadd.sat(LHS, RHS)</p>

<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa16bb473dbb4b04fd2b11ccb72660b0e">computeKnownBitsForPMADDUBSW</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### sdiv() {#a9f4c03962b079bed0cd6c59256844bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::sdiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool Exact=false)</td>
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

<p>Compute known bits for sdiv(LHS, RHS).</p>

<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="#a96120d4062fabb503b1b92401e54d14f">udiv</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### sge() {#a466e550382eee7535225b95ef91914d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::sge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_SGE result.</p>

<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#ad20d9f61ec3c5c2a0bd9163cb6c15335">sgt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a> and <a href="#acc61013b6ddecc5b9c8105aa961b71f2">sle</a>.</p>

</div>
</div>

### sgt() {#ad20d9f61ec3c5c2a0bd9163cb6c15335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::sgt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_SGT result.</p>

<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0caaab3a18e77b9f48dc88b3b757dd6">llvm::X86TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aac253731b80df3086dc617dc805f7dd5">computeKnownBitsMul</a>, <a href="#a466e550382eee7535225b95ef91914d1">sge</a> and <a href="#a97cc47234699c26a59495f019e3fb1e3">slt</a>.</p>

</div>
</div>

### shl() {#ae9ffa8b50ca6095202b2e8e7686c10b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::shl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool NUW=false, bool NSW=false, bool ShAmtNonZero=false)</td>
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

<p>Compute known bits for shl(LHS, RHS).</p>


<p>NOTE: RHS (shift amount) bitwidth doesn't need to be the same as LHS.</p>


<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#aa18696894909136556d40020664aefe1">getMaxShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a44875c6f48f6c843cf3114a19280b5ca">hasConflict</a>, <a href="#a76e45a40f2f0b5b09132d1de119765e8">intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#a28cf355963391ab8781b2347d495553d">isUnknown</a>, <a href="#a36d9168813b2a8415c085ac551c54458">makeNegative</a>, <a href="#a192e15f89a5aa04df018639812e2c4db">makeNonNegative</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ade8e20ecea1091e835395746448e262e">llvm::APInt::setLowBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4f1e1a4449b58958c5884c689e7f4861">llvm::APInt::setSignBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a97419fdddc400a50c7c40ef5c35903cd">llvm::APInt::ushl_ov</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a16eb7e7dd4fd476ad2fa83cfb84c068d">llvm::AArch64TargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>.</p>

</div>
</div>

### sle() {#acc61013b6ddecc5b9c8105aa961b71f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::sle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_SLE result.</p>

<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#a466e550382eee7535225b95ef91914d1">sge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>.</p>

</div>
</div>

### slt() {#a97cc47234699c26a59495f019e3fb1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::slt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_SLT result.</p>

<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#ad20d9f61ec3c5c2a0bd9163cb6c15335">sgt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a> and <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>.</p>

</div>
</div>

### smax() {#a137874360a1967ac811fe9e5d7605eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::smax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for smax(LHS, RHS).</p>

<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#a5120eaa394627e6c1ec3d66ef77947cd">umax</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### smin() {#a87b6ba94fe7d3ee69dbeed7350fad096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::smin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for smin(LHS, RHS).</p>

<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#a4fdc09049a61f952b5d52788dbd2f69b">getBitWidth</a>, <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="#a5120eaa394627e6c1ec3d66ef77947cd">umax</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### srem() {#a905d2324c26b7a6f5aeb929a734ce0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::srem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for srem(LHS, RHS).</p>

<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a6da514c588b2668280a861a59bfc9fa5">llvm::APInt::intersects</a>, <a href="#a5d774365f4d1120b030d026860193a02">isNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acfae9bdee6027ffa8ffe244cc22e3a76">llvm::APInt::isSubsetOf</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### ssub\_sat() {#a205a7518b8f3eef3fa4e9b812fb4f6fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::ssub_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from llvm.ssub.sat(LHS, RHS)</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### sub() {#aaedcbc66cfec0117e98d503c89234716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::KnownBits::sub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool NSW=false, bool NUW=false)</td>
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

<p>Compute knownbits resulting from subtraction of LHS and RHS.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>.</p>


<p>References <a href="#a9c1c6dc178ce30e4a6c09f5c08727d65">computeForAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a4d74a9468cededc1f4e9887dd009fe66">binaryOpKnownBitsMapHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a77c96ceb55a9bb9f5e9fb6e80e3b6dd6">llvm::InstCombinerImpl::SimplifyMultipleUseDemandedBits</a>.</p>

</div>
</div>

### uadd\_sat() {#abbef45a09397663c2ffdae818a00e3b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::uadd_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from llvm.uadd.sat(LHS, RHS)</p>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### udiv() {#a96120d4062fabb503b1b92401e54d14f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::udiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, bool Exact=false)</td>
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

<p>Compute known bits for udiv(LHS, RHS).</p>

<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa074b9f5a1efaa0fd8aa4522593f299a">llvm::APInt::countLeadingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a45ef044ff35b0079bbb7aebf5460234d">divComputeLowBit</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="#a4816b869391aac5bbcce9c889c2ecd97">setAllZero</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="#a9f4c03962b079bed0cd6c59256844bb5">sdiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### uge() {#ad86f53ca31fd59930678248efbfaf516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::uge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_UGE result.</p>

<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#a92e582ead745c86654cd8d0e1228f0c5">ugt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a> and <a href="#aa8a47d48d5537edfc125ee8ed5659955">ule</a>.</p>

</div>
</div>

### ugt() {#a92e582ead745c86654cd8d0e1228f0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::ugt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_UGT result.</p>

<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>, <a href="#ad86f53ca31fd59930678248efbfaf516">uge</a> and <a href="#aa0d9eb764d22c7fabfecf5164123cc18">ult</a>.</p>

</div>
</div>

### ule() {#aa8a47d48d5537edfc125ee8ed5659955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::ule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_ULE result.</p>

<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#ad86f53ca31fd59930678248efbfaf516">uge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>.</p>

</div>
</div>

### ult() {#aa0d9eb764d22c7fabfecf5164123cc18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; KnownBits::ult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Determine if these known bits always give the same ICMP_ULT result.</p>

<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="#a92e582ead745c86654cd8d0e1228f0c5">ugt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a884b1f40d80313fe00fa303a8943015e">llvm::ICmpInst::compare</a>.</p>

</div>
</div>

### umax() {#a5120eaa394627e6c1ec3d66ef77947cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::umax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for umax(LHS, RHS).</p>

<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="#a137874360a1967ac811fe9e5d7605eee">smax</a>, <a href="#a87b6ba94fe7d3ee69dbeed7350fad096">smin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a0243f30368fd176bd411351538a11c9c">targetOpKnownBitsMapHelper</a> and <a href="#aea97402782d7e8098b6ae00c7a6365dd">umin</a>.</p>

</div>
</div>

### umin() {#aea97402782d7e8098b6ae00c7a6365dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::umin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for umin(LHS, RHS).</p>

<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="#a84015e5252bbac2c6d1174218ff425b3">KnownBits</a>, <a href="#aba205f553f24c184ea47fc1a6cb56537">One</a>, <a href="#a5120eaa394627e6c1ec3d66ef77947cd">umax</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a> and <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>.</p>

</div>
</div>

### urem() {#a2838364c4863a3b2c55c6fd7052413aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::urem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute known bits for urem(LHS, RHS).</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a2780c5606880394d3f07cd2079a27697">llvm::APInt::setHighBits</a> and <a href="#ac67bca6c764da76f5e152330d92ed916">Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2debf575de4ff2120c93986cd0b46f20">llvm::RISCVTargetLowering::computeKnownBitsForTargetNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

### usub\_sat() {#a1b58fb130fd24756c4e0b59c779969ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::usub_sat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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

<p>Compute knownbits resulting from llvm.usub.sat(LHS, RHS)</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp/#a424f831ae238edf63b3f3fc0df29437c">computeForSatAddSub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0138c9b735258330db2232fb84b368bf">llvm::SelectionDAG::computeKnownBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### flipSignBit() {#a9bfd55a2dd28409a0b3fd6be8b48037b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::flipSignBit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Val)</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>

</div>
</div>

### remGetLowBits() {#a1d2eeb158fdabbe59f01c0c623706670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits KnownBits::remGetLowBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS)</td>
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



<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a>, definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">KnownBits.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/knownbits-cpp">KnownBits.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
