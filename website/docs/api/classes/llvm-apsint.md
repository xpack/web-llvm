---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/apsint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `APSInt` Class

<p>An arbitrary precision integer that knows its signedness. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::APSInt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">llvm/ADT/APSInt.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class for arbitrary precision integers. <a href="/web-llvm/docs/api/classes/llvm/apint/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor that creates an uninitialized <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#abf56a02cd18e783e040dc0e258deb1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418dc37bbe3a6fbd4192291ace00300d">APSInt</a> (uint32_t BitWidth, bool isUnsigned=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> with the specified width, default to unsigned. <a href="#a418dc37bbe3a6fbd4192291ace00300d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3f9ea222b9abce0f4a502d4504657c">APSInt</a> (APInt I, bool isUnsigned=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3c6bd8729cd1fcbee8b2534affc30d">APSInt</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> from a string representation. <a href="#a8d3c6bd8729cd1fcbee8b2534affc30d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a4b7b345463fcac3ee2a8964556e9e">operator=</a> (APInt RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5f1c10e937b8fccfbb846736c0d1f3">operator=</a> (uint64_t RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3073cdacf70e2530fde9c67be4bdaac">operator%=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d18c5db1edd957046c553be317939ff">operator/=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20e09844a71113a5fe9b80dae48a219">operator%</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0317ddb04fa2f763dd5e3a5c38a914">operator/</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b21f58b23210aaa6dbe1ed62c330a3">operator&gt;&gt;</a> (unsigned Amt) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaba218d0b8ff3581f4fbddb8c68ab4d">operator&gt;&gt;=</a> (unsigned Amt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f54987909b9918d96f059d09dd34bc">operator&lt;</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2bbb768bd4508be2080a7d99c16afb">operator&gt;</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8cf05c10c014362077a5f166ca0ccf6">operator&lt;=</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c08f911e04d76c1e01900fcfcf2a35">operator&gt;=</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1457368e287459e33ec3f528553a94e0">operator==</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7aa405305ba6e728670588f0ed19d96">operator!=</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdf528acf926d7414b19c7883a75562">operator==</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3605b6a7a5f5a3f0be655b9b780d184b">operator!=</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6767921a691e37c3e3b0e3cd84c46109">operator&lt;=</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed9dffe5c89ab30c717fc6084b12408">operator&gt;=</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde5c18030a97c5d599aad221e5b4a56">operator&lt;</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40888540814670ce4544619cd4b09e05">operator&gt;</a> (int64_t RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f30b7fdef45b6381891e15058fde704">operator&lt;&lt;</a> (unsigned Bits) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7be41cf6c4c816244791d3498f26e4">operator&lt;&lt;=</a> (unsigned Amt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec345f698381947eaca2b9c5a8b61c1">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2094babfc54cb625aba1a3c50a39749">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5850ef75730e924d2a3eb1b2b8065e2f">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77cddfafc4d18f0d88d8e2712a1469c5">operator--</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66bf0c96c9859665f6541b4ce8be8532">operator-</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068ebd196df9fdd6a8123fc2a3be51ec">operator+=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada071da8ac7193e577b6363ecc857e08">operator-=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a373350cfe26941337fedf82796444e1d">operator*=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83359a4d7b4dd311575324b73e155035">operator&amp;=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa985a05855fc28f5272a235cd3f40891">operator|=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8467598c22aa3ccba4d04cb56fae3a">operator^=</a> (const APSInt &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743415ef16a31bc7c84e9f7ab43ffd77">operator&amp;</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae79c7a3d485e0b7d6a1e648c71af2536">operator|</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdb5053e7cfd3ab44afd53c2500b7a0">operator^</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362dcab03bc42a305f3c62db691daac7">operator*</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4970be7e89c76c9fc31870e189487c86">operator+</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0855daeef1e9cdbe92fc5fd385eeb5e5">operator-</a> (const APSInt &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de293914759628d50bb12a1ffe6b76a">operator~</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16fd96ce7d6d8206ad35461a688a780f">isNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine sign of this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a>. <a href="#a16fd96ce7d6d8206ad35461a688a780f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a6a6115da7d509ed92c6170568e570">isNonNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is non-negative (&gt;= 0) <a href="#a62a6a6115da7d509ed92c6170568e570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822a1b75482ee26ce45cdcc59c70d13d">isStrictlyPositive</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is positive. <a href="#a822a1b75482ee26ce45cdcc59c70d13d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af482956db6e996054f48726dccc31686">isSigned</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf19504554cdbc9850f6a68b001ddbde">isUnsigned</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf32a4b603863370fba646b4a2a341ac">setIsUnsigned</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a47f2f0f20023cf6ed21dd467202de">setIsSigned</a> (bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42308e3ef28ca0123864b24eeb98b5d">toString</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned Radix=10) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>. <a href="#ab42308e3ef28ca0123864b24eeb98b5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590f094c63a53f5cda018ce31a2e541b">isRepresentableByInt64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this int is representable using an int64_t. <a href="#a590f094c63a53f5cda018ce31a2e541b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477d37efcba589f51c319373cee0294e">getExtValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the correctly-extended <span class="doxyComputerOutput">int64_t</span> value. <a href="#a477d37efcba589f51c319373cee0294e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8baebecc53c1d382802a6066a0d7371">tryExtValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02cf2ea5865f88ae2a21e446d560d5a">trunc</a> (uint32_t width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad62f39c993a3723a7b735652e1e14f57">extend</a> (uint32_t width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0080c63e713e9ead5c33929b9127e96f">extOrTrunc</a> (uint32_t width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4397926a41cfe940d5f071bb707b8aeb">relativeShr</a> (unsigned Amt) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bfb82b935461edaeaff0a95e39d929">relativeShl</a> (unsigned Amt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac422f9ff091a494e6d814c5abd28bdc">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to insert <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> objects, or objects that contain <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> objects, into FoldingSets. <a href="#aac422f9ff091a494e6d814c5abd28bdc">More...</a></p>
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

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35d8164d56add2d7b1f7f84bd01b686">IsUnsigned</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cba4d26a4ef4ecf1cea7faac29b1786">getMaxValue</a> (uint32_t numBits, bool Unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> representing the maximum integer value with the given bit width and signedness. <a href="#a5cba4d26a4ef4ecf1cea7faac29b1786">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a441f49b4e67f435392c937e056d2d4">getMinValue</a> (uint32_t numBits, bool Unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> representing the minimum integer value with the given bit width and signedness. <a href="#a0a441f49b4e67f435392c937e056d2d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40e05cea8e86b8cb58336bf87d0c89b">isSameValue</a> (const APSInt &amp;I1, const APSInt &amp;I2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if two APSInts have the same value, zero- or sign-extending as needed. <a href="#ad40e05cea8e86b8cb58336bf87d0c89b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a> (const APSInt &amp;I1, const APSInt &amp;I2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare underlying values of two numbers. <a href="#a46be5bb239b3fc96e2ff377081579f72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> (int64_t X)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6593f5aa13227a1db6af52069fcfe3b2">getUnsigned</a> (uint64_t X)</td>
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

<p>An arbitrary precision integer that knows its signedness.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### APSInt() {#abf56a02cd18e783e040dc0e258deb1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APSInt::APSInt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default constructor that creates an uninitialized <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>Referenced by <a href="#a8d3c6bd8729cd1fcbee8b2534affc30d">APSInt</a>, <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#ad62f39c993a3723a7b735652e1e14f57">extend</a>, <a href="#a0080c63e713e9ead5c33929b9127e96f">extOrTrunc</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a>, <a href="#a5cba4d26a4ef4ecf1cea7faac29b1786">getMaxValue</a>, <a href="#a0a441f49b4e67f435392c937e056d2d4">getMinValue</a>, <a href="#a6593f5aa13227a1db6af52069fcfe3b2">getUnsigned</a>, <a href="#ad40e05cea8e86b8cb58336bf87d0c89b">isSameValue</a>, <a href="#ab7aa405305ba6e728670588f0ed19d96">operator!=</a>, <a href="#aa20e09844a71113a5fe9b80dae48a219">operator%</a>, <a href="#aa3073cdacf70e2530fde9c67be4bdaac">operator%=</a>, <a href="#a743415ef16a31bc7c84e9f7ab43ffd77">operator&amp;</a>, <a href="#a83359a4d7b4dd311575324b73e155035">operator&amp;=</a>, <a href="#a362dcab03bc42a305f3c62db691daac7">operator*</a>, <a href="#a373350cfe26941337fedf82796444e1d">operator*=</a>, <a href="#a4970be7e89c76c9fc31870e189487c86">operator+</a>, <a href="#a3ec345f698381947eaca2b9c5a8b61c1">operator++</a>, <a href="#a5850ef75730e924d2a3eb1b2b8065e2f">operator++</a>, <a href="#a068ebd196df9fdd6a8123fc2a3be51ec">operator+=</a>, <a href="#a66bf0c96c9859665f6541b4ce8be8532">operator-</a>, <a href="#a0855daeef1e9cdbe92fc5fd385eeb5e5">operator-</a>, <a href="#af2094babfc54cb625aba1a3c50a39749">operator--</a>, <a href="#a77cddfafc4d18f0d88d8e2712a1469c5">operator--</a>, <a href="#ada071da8ac7193e577b6363ecc857e08">operator-=</a>, <a href="#aec0317ddb04fa2f763dd5e3a5c38a914">operator/</a>, <a href="#a4d18c5db1edd957046c553be317939ff">operator/=</a>, <a href="#a44f54987909b9918d96f059d09dd34bc">operator&lt;</a>, <a href="#a6f30b7fdef45b6381891e15058fde704">operator&lt;&lt;</a>, <a href="#afe7be41cf6c4c816244791d3498f26e4">operator&lt;&lt;=</a>, <a href="#ae8cf05c10c014362077a5f166ca0ccf6">operator&lt;=</a>, <a href="#a09a4b7b345463fcac3ee2a8964556e9e">operator=</a>, <a href="#aed5f1c10e937b8fccfbb846736c0d1f3">operator=</a>, <a href="#a1457368e287459e33ec3f528553a94e0">operator==</a>, <a href="#a3f2bbb768bd4508be2080a7d99c16afb">operator&gt;</a>, <a href="#a83c08f911e04d76c1e01900fcfcf2a35">operator&gt;=</a>, <a href="#a19b21f58b23210aaa6dbe1ed62c330a3">operator&gt;&gt;</a>, <a href="#acaba218d0b8ff3581f4fbddb8c68ab4d">operator&gt;&gt;=</a>, <a href="#a2fdb5053e7cfd3ab44afd53c2500b7a0">operator^</a>, <a href="#afb8467598c22aa3ccba4d04cb56fae3a">operator^=</a>, <a href="#ae79c7a3d485e0b7d6a1e648c71af2536">operator|</a>, <a href="#aa985a05855fc28f5272a235cd3f40891">operator|=</a>, <a href="#a8de293914759628d50bb12a1ffe6b76a">operator~</a>, <a href="#aa9bfb82b935461edaeaff0a95e39d929">relativeShl</a>, <a href="#a4397926a41cfe940d5f071bb707b8aeb">relativeShr</a> and <a href="#af02cf2ea5865f88ae2a21e446d560d5a">trunc</a>.</p>

</div>
</div>

### APSInt() {#a418dc37bbe3a6fbd4192291ace00300d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APSInt::APSInt (uint32_t BitWidth, bool isUnsigned=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> with the specified width, default to unsigned.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf19504554cdbc9850f6a68b001ddbde">isUnsigned</a>.</p>

</div>
</div>

### APSInt() {#a8b3f9ea222b9abce0f4a502d4504657c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APSInt::APSInt (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> I, bool isUnsigned=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abf19504554cdbc9850f6a68b001ddbde">isUnsigned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### APSInt() {#a8d3c6bd8729cd1fcbee8b2534affc30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt::APSInt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> from a string representation.</p>


<p>This constructor interprets the string <span class="doxyComputerOutput">Str</span> using the radix of 10. The interpretation stops at the end of the string. The bit width of the constructed <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> is determined automatically.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Str</td>
<td class="doxyParamItemDescription"><p>the string to be interpreted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apsint-cpp">APSInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9f78d7e839322a6bfc0c665d29052242">llvm::APInt::getSignificantBits</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#a66bf0c96c9859665f6541b4ce8be8532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator- ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator-() {#a0855daeef1e9cdbe92fc5fd385eeb5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator- (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator--() {#af2094babfc54cb625aba1a3c50a39749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator-- ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator--() {#a77cddfafc4d18f0d88d8e2712a1469c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator-- (int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator-=() {#ada071da8ac7193e577b6363ecc857e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!=() {#ab7aa405305ba6e728670588f0ed19d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!=() {#a3605b6a7a5f5a3f0be655b9b780d184b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator!= (int64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*() {#a362dcab03bc42a305f3c62db691daac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator* (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*=() {#a373350cfe26941337fedf82796444e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator*= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/() {#aec0317ddb04fa2f763dd5e3a5c38a914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator/ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a>.</p>

</div>
</div>

### operator/=() {#a4d18c5db1edd957046c553be317939ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APSInt &amp; llvm::APSInt::operator/= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a71f7f6e3a4774296efc7274196a74793">llvm::APInt::sdiv</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a05d674becc60ba4ef8cd4dd4d38ac27a">llvm::APInt::udiv</a>.</p>

</div>
</div>

### operator&amp;() {#a743415ef16a31bc7c84e9f7ab43ffd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator&amp; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&amp;=() {#a83359a4d7b4dd311575324b73e155035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator%() {#aa20e09844a71113a5fe9b80dae48a219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator% (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac131d830427393332e440e1d6e3013b6">llvm::APInt::srem</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>

</div>
</div>

### operator%=() {#aa3073cdacf70e2530fde9c67be4bdaac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const APSInt &amp; llvm::APSInt::operator%= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac131d830427393332e440e1d6e3013b6">llvm::APInt::srem</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>

</div>
</div>

### operator^() {#a2fdb5053e7cfd3ab44afd53c2500b7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator^ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator^=() {#afb8467598c22aa3ccba4d04cb56fae3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+() {#a4970be7e89c76c9fc31870e189487c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator+ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator++() {#a3ec345f698381947eaca2b9c5a8b61c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator++ ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator++() {#a5850ef75730e924d2a3eb1b2b8065e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator++ (int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator+=() {#a068ebd196df9fdd6a8123fc2a3be51ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#a44f54987909b9918d96f059d09dd34bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#adafa9575780f9246d1df0b7e2a619356">llvm::APInt::slt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>

</div>
</div>

### operator&lt;() {#abde5c18030a97c5d599aad221e5b4a56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&lt; (int64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a6f30b7fdef45b6381891e15058fde704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator&lt;&lt; (unsigned Bits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator&lt;&lt;=() {#afe7be41cf6c4c816244791d3498f26e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator&lt;&lt;= (unsigned Amt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

### operator&lt;=() {#ae8cf05c10c014362077a5f166ca0ccf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e8226e6453c8bcf7e5c06d28b1e207b">llvm::APInt::sle</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a>.</p>

</div>
</div>

### operator&lt;=() {#a6767921a691e37c3e3b0e3cd84c46109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&lt;= (int64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator=() {#a09a4b7b345463fcac3ee2a8964556e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator= (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3c3ff3a632850951cea84d8c6466890b">llvm::APInt::operator=</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator=() {#aed5f1c10e937b8fccfbb846736c0d1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator= (uint64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3c3ff3a632850951cea84d8c6466890b">llvm::APInt::operator=</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a1457368e287459e33ec3f528553a94e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6e17f9e532ca4a61804f28091b10b522">llvm::APInt::eq</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a0fdf528acf926d7414b19c7883a75562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator== (int64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#a3f2bbb768bd4508be2080a7d99c16afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3d430216d32f4363e4df154599b98055">llvm::APInt::sgt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a46a7cbf3724080a5f4f4c7e7a4551e26">llvm::APInt::ugt</a>.</p>

</div>
</div>

### operator&gt;() {#a40888540814670ce4544619cd4b09e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&gt; (int64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#a83c08f911e04d76c1e01900fcfcf2a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae2b7d8c018c8a37fa8ea422a13bfd412">llvm::APInt::sge</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>.</p>

</div>
</div>

### operator&gt;=() {#aeed9dffe5c89ab30c717fc6084b12408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::operator&gt;= (int64_t RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#a12104865ac55c27d5a97bd72d4b750b7">get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;&gt;() {#a19b21f58b23210aaa6dbe1ed62c330a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator&gt;&gt; (unsigned Amt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6006923d1a3139d70abc8f6552a7960">llvm::APInt::ashr</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>.</p>

</div>
</div>

### operator&gt;&gt;=() {#acaba218d0b8ff3581f4fbddb8c68ab4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator&gt;&gt;= (unsigned Amt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a7e30b3aa214eba50eed018b5b19fc6aa">llvm::APInt::ashrInPlace</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af338e23a90c301183968435e80cd6a27">llvm::APInt::lshrInPlace</a>.</p>

</div>
</div>

### operator|() {#ae79c7a3d485e0b7d6a1e648c71af2536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator| (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|=() {#aa985a05855fc28f5272a235cd3f40891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt &amp; llvm::APSInt::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\~() {#a8de293914759628d50bb12a1ffe6b76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::operator~ ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a> and <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### extend() {#ad62f39c993a3723a7b735652e1e14f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::extend (uint32_t width)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a5c0f7939bae61f761380e0334523469b">llvm::APFixedPoint::convertToInt</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad2268a8da9de7921a854b4f3e0028ae5">llvm::APFixedPoint::getIntPart</a>.</p>

</div>
</div>

### extOrTrunc() {#a0080c63e713e9ead5c33929b9127e96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::extOrTrunc (uint32_t width)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9b5fc98b47d44d1150d3610bdfab1430">llvm::APInt::sextOrTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad1188d3cd694bbba2756d1b7aaad6e19">llvm::APFixedPoint::mul</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aa494dc35a29c6f78f26ea04679887f0d">llvm::APFixedPoint::shl</a>.</p>

</div>
</div>

### getExtValue() {#a477d37efcba589f51c319373cee0294e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::APSInt::getExtValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the correctly-extended <span class="doxyComputerOutput">int64_t</span> value.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="#a590f094c63a53f5cda018ce31a2e541b">isRepresentableByInt64</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>.</p>


<p>Referenced by <a href="#ab8baebecc53c1d382802a6066a0d7371">tryExtValue</a>.</p>

</div>
</div>

### isNegative() {#a16fd96ce7d6d8206ad35461a688a780f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine sign of this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> is negative, false otherwise</p></dd>
</dl>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>.</p>


<p>Referenced by <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#acb7a0970dbe748e4fec6bd94d353476c">llvm::APFixedPoint::div</a> and <a href="#a62a6a6115da7d509ed92c6170568e570">isNonNegative</a>.</p>

</div>
</div>

### isNonNegative() {#a62a6a6115da7d509ed92c6170568e570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isNonNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is non-negative (&gt;= 0)</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> is non-negative, false otherwise</p></dd>
</dl>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>Reference <a href="#a16fd96ce7d6d8206ad35461a688a780f">isNegative</a>.</p>


<p>Referenced by <a href="#a822a1b75482ee26ce45cdcc59c70d13d">isStrictlyPositive</a>.</p>

</div>
</div>

### isRepresentableByInt64() {#a590f094c63a53f5cda018ce31a2e541b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isRepresentableByInt64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this int is representable using an int64_t.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#ae00c35cb040107c05f3fe00c15bb3da0">llvm::APInt::isIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a87d50d10274efe9688166584391ae489">llvm::APInt::isSignedIntN</a>.</p>


<p>Referenced by <a href="#a477d37efcba589f51c319373cee0294e">getExtValue</a> and <a href="#ab8baebecc53c1d382802a6066a0d7371">tryExtValue</a>.</p>

</div>
</div>

### isSigned() {#af482956db6e996054f48726dccc31686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isSigned ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad69d1c99b0af08146faf9bdf2d9c8709">llvm::APFixedPoint::add</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a505208677eadb6d75acfdfc01911c8dc">llvm::APFixedPoint::compare</a>, <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aebaffb4b288b2508f99e75e0e8bd3ed9">llvm::APFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#ab30aaf95486d0b2aac87f3d9e1e450e3">llvm::FixedPointSemantics::fitsInFloatSemantics</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6d9ba22fe2a57b958ba00d8b3382fffd">llvm::APFixedPoint::sub</a>.</p>

</div>
</div>

### isStrictlyPositive() {#a822a1b75482ee26ce45cdcc59c70d13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isStrictlyPositive ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is positive.</p>


<p>This tests if the value of this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> is positive (&gt; 0). Note that 0 is not a positive value.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> is positive.</p></dd>
</dl>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a62a6a6115da7d509ed92c6170568e570">isNonNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>.</p>

</div>
</div>

### isUnsigned() {#abf19504554cdbc9850f6a68b001ddbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isUnsigned ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>Referenced by <a href="#a8b3f9ea222b9abce0f4a502d4504657c">APSInt</a> and <a href="#a418dc37bbe3a6fbd4192291ace00300d">APSInt</a>.</p>

</div>
</div>

### Profile() {#aac422f9ff091a494e6d814c5abd28bdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void APSInt::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to insert <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> objects, or objects that contain <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> objects, into FoldingSets.</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apsint-cpp">APSInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apint/#adb1c052266ebacdbf28164fae9106b0a">llvm::APInt::Profile</a>.</p>

</div>
</div>

### relativeShl() {#aa9bfb82b935461edaeaff0a95e39d929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::relativeShl (unsigned Amt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a793e27a4e7b6ec5ecab8e7616e0d4ac0">llvm::APInt::relativeAShl</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a3bbf73dc4411a52b8d03e582a09893ce">llvm::APInt::relativeLShl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ad2268a8da9de7921a854b4f3e0028ae5">llvm::APFixedPoint::getIntPart</a>.</p>

</div>
</div>

### relativeShr() {#a4397926a41cfe940d5f071bb707b8aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::relativeShr (unsigned Amt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a57604a130a7bf75be0295a8ba37ff4fe">llvm::APInt::relativeAShr</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1aeae6359e573a57ce8db93b8b26b19a">llvm::APInt::relativeLShr</a>.</p>

</div>
</div>

### setIsSigned() {#a83a47f2f0f20023cf6ed21dd467202de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APSInt::setIsSigned (bool Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a04fa4c8635e7f41be7af6f9297db0aff">llvm::APFixedPoint::convert</a>.</p>

</div>
</div>

### setIsUnsigned() {#acf32a4b603863370fba646b4a2a341ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APSInt::setIsUnsigned (bool Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>

</div>
</div>

### toString() {#ab42308e3ef28ca0123864b24eeb98b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APSInt::toString (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned Radix=10)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append this <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> to the specified <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#aff8bfdb27a0027b84b0c3580c0d9f530">llvm::APInt::toString</a>.</p>

</div>
</div>

### toString() {#aff8bfdb27a0027b84b0c3580c0d9f530}

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


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>, definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>.</p>

</div>
</div>

### trunc() {#af02cf2ea5865f88ae2a21e446d560d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::trunc (uint32_t width)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a>.</p>

</div>
</div>

### tryExtValue() {#ab8baebecc53c1d382802a6066a0d7371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; llvm::APSInt::tryExtValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#a477d37efcba589f51c319373cee0294e">getExtValue</a> and <a href="#a590f094c63a53f5cda018ce31a2e541b">isRepresentableByInt64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsUnsigned {#aa35d8164d56add2d7b1f7f84bd01b686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::IsUnsigned = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### compareValues() {#a46be5bb239b3fc96e2ff377081579f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::APSInt::compareValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; I1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; I2)</td>
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

<p>Compare underlying values of two numbers.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#ad62f39c993a3723a7b735652e1e14f57">extend</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="#a16fd96ce7d6d8206ad35461a688a780f">isNegative</a> and <a href="#af482956db6e996054f48726dccc31686">isSigned</a>.</p>


<p>Referenced by <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>, <a href="#ad40e05cea8e86b8cb58336bf87d0c89b">isSameValue</a>, <a href="#a3605b6a7a5f5a3f0be655b9b780d184b">operator!=</a>, <a href="#abde5c18030a97c5d599aad221e5b4a56">operator&lt;</a>, <a href="#a6767921a691e37c3e3b0e3cd84c46109">operator&lt;=</a>, <a href="#a0fdf528acf926d7414b19c7883a75562">operator==</a>, <a href="#a40888540814670ce4544619cd4b09e05">operator&gt;</a> and <a href="#aeed9dffe5c89ab30c717fc6084b12408">operator&gt;=</a>.</p>

</div>
</div>

### get() {#a12104865ac55c27d5a97bd72d4b750b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::get (int64_t X)</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a3605b6a7a5f5a3f0be655b9b780d184b">operator!=</a>, <a href="#abde5c18030a97c5d599aad221e5b4a56">operator&lt;</a>, <a href="#a6767921a691e37c3e3b0e3cd84c46109">operator&lt;=</a>, <a href="#a0fdf528acf926d7414b19c7883a75562">operator==</a>, <a href="#a40888540814670ce4544619cd4b09e05">operator&gt;</a>, <a href="#aeed9dffe5c89ab30c717fc6084b12408">operator&gt;=</a> and <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a07384ea9d8fdfb208574ff59715e5be2">llvm::APFixedPoint::toString</a>.</p>

</div>
</div>

### getMaxValue() {#a5cba4d26a4ef4ecf1cea7faac29b1786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::getMaxValue (uint32_t numBits, bool Unsigned)</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> representing the maximum integer value with the given bit width and signedness.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a5c0f7939bae61f761380e0334523469b">llvm::APFixedPoint::convertToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#ae7ca9ff56521cc2e2c51d96ad9a6005c">llvm::APFixedPoint::getMax</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getMinValue() {#a0a441f49b4e67f435392c937e056d2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::getMinValue (uint32_t numBits, bool Unsigned)</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> representing the minimum integer value with the given bit width and signedness.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a5c0f7939bae61f761380e0334523469b">llvm::APFixedPoint::convertToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a1c4398afd568f2c31f81dcecad35ef7b">llvm::APFixedPoint::getMin</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getUnsigned() {#a6593f5aa13227a1db6af52069fcfe3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APSInt llvm::APSInt::getUnsigned (uint64_t X)</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### isSameValue() {#ad40e05cea8e86b8cb58336bf87d0c89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APSInt::isSameValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; I1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; I2)</td>
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

<p>Determine if two APSInts have the same value, zero- or sign-extending as needed.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a>.</p>


<p>References <a href="#abf56a02cd18e783e040dc0e258deb1f9">APSInt</a> and <a href="#a46be5bb239b3fc96e2ff377081579f72">compareValues</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9f6c692bb79cca65ae3097ddd4c47e69">llvm::ConstantFoldExtractElementInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">APSInt.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp">APInt.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apsint-cpp">APSInt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
