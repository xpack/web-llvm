---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/slowdynamicapint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SlowDynamicAPInt` Class

<p>A simple class providing dynamic arbitrary-precision arithmetic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::detail::SlowDynamicAPInt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">llvm/ADT/SlowDynamicAPInt.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f4607beccb2943924cbd3ace5fca55">abs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Redeclarations of friend declarations above to make it discoverable by lookups. <a href="#a86f4607beccb2943924cbd3ace5fca55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc7f7d8234200325d42e27dc17b6724">ceilDiv</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8852f6b2d9ec867024590f14be36234a">floorDiv</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7badf6fc1b27b0e11d9821902c10fc70">gcd</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The operands must be non-negative for gcd. <a href="#a7badf6fc1b27b0e11d9821902c10fc70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7becd12ece4460ed2827b012da283e50">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload to compute a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for a <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> value. <a href="#a7becd12ece4460ed2827b012da283e50">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a> (int64_t Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce4cdf6c23326febc70d55a3892c166">SlowDynamicAPInt</a> (const APInt &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c00fa06bed413c4253776167c7df87e">operator=</a> (int64_t Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0748dcfa9d89080d1f70c3c05f03967d">operator int64_t</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ea8ef61eafc6ee1009f01753c619ae">operator-</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d50644f90a55900013be55fcb257f42">operator==</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d90fea50ec5a75c894d67fbe2d3b17">operator!=</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c66825db234e73dedb2c3799bfa3f12">operator&gt;</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b9ab408d61ca138628e070cd6bd93a">operator&lt;</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e9d3a334499824e1ff938254e597bf">operator&lt;=</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7171fdf762b090dd88be0697e652be">operator&gt;=</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe3b990798e79cc464f39472699112b">operator+</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7d474fe2bca892a50861086e90cf07">operator-</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc607373675fde318c740e7bc810ff9">operator*</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9284a4735992c0b86c3827ecbd0d0861">operator/</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a080fd4d5bc1f48ec40237895f64b6342">operator%</a> (const SlowDynamicAPInt &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This operation cannot overflow. <a href="#a080fd4d5bc1f48ec40237895f64b6342">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18da247480a2159740cf06c5381ea163">operator+=</a> (const SlowDynamicAPInt &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ae63c8dfa785ff0a9678d1bed168aa">operator-=</a> (const SlowDynamicAPInt &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5826a85058174310d98ff0d83cb118b3">operator*=</a> (const SlowDynamicAPInt &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81664ad422ed05b8b9b6eaedcd355f5">operator/=</a> (const SlowDynamicAPInt &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0dc852a171a2a6a4c8c4f1a6761a983">operator%=</a> (const SlowDynamicAPInt &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6efa59b7aacf80be1e6897f0ffd6bb74">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f622a535f889d45fe847e8cdb73f226">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9affb1f32a8b82fc8346f458925683d8">getBitWidth</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048eab76be75a96b1715bf4780b4c6fd">print</a> (raw_ostream &amp;OS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b8ba867d5f6532f7886d1d7d04e1f5">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d8ad0f5b2be77a4140ad1021030a0c">DynamicAPInt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76069858180debd7db76ef18cf847deb">Val</a></td>
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

<p>A simple class providing dynamic arbitrary-precision arithmetic.</p>


<p>Internally, it stores an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, whose width is doubled whenever an overflow occurs at a certain width. The default constructor sets the initial width to 64. <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> is primarily intended to be used as a slow fallback path for the upcoming <a href="/web-llvm/docs/api/classes/llvm/dynamicapint">DynamicAPInt</a> class.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>


<div class="doxySectionDef">

## Friends

### abs {#a86f4607beccb2943924cbd3ace5fca55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; X</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Redeclarations of friend declarations above to make it discoverable by lookups.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>


<p>References <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### ceilDiv {#a4bc7f7d8234200325d42e27dc17b6724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### floorDiv {#a8852f6b2d9ec867024590f14be36234a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### gcd {#a7badf6fc1b27b0e11d9821902c10fc70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The operands must be non-negative for gcd.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### hash\_value {#a7becd12ece4460ed2827b012da283e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; X</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Overload to compute a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for a <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> value.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>


<p>References <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SlowDynamicAPInt() {#a7ccd6b8cee73c66735677d1044f3121f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt::SlowDynamicAPInt (int64_t Val)</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a86f4607beccb2943924cbd3ace5fca55">abs</a>, <a href="#a4bc7f7d8234200325d42e27dc17b6724">ceilDiv</a>, <a href="#a8852f6b2d9ec867024590f14be36234a">floorDiv</a>, <a href="#a7badf6fc1b27b0e11d9821902c10fc70">gcd</a>, <a href="#a7becd12ece4460ed2827b012da283e50">hash_value</a>, <a href="#a73d90fea50ec5a75c894d67fbe2d3b17">operator!=</a>, <a href="#a080fd4d5bc1f48ec40237895f64b6342">operator%</a>, <a href="#ac0dc852a171a2a6a4c8c4f1a6761a983">operator%=</a>, <a href="#a0fc607373675fde318c740e7bc810ff9">operator*</a>, <a href="#a5826a85058174310d98ff0d83cb118b3">operator*=</a>, <a href="#afbe3b990798e79cc464f39472699112b">operator+</a>, <a href="#a6efa59b7aacf80be1e6897f0ffd6bb74">operator++</a>, <a href="#a18da247480a2159740cf06c5381ea163">operator+=</a>, <a href="#a70ea8ef61eafc6ee1009f01753c619ae">operator-</a>, <a href="#a0a7d474fe2bca892a50861086e90cf07">operator-</a>, <a href="#a2f622a535f889d45fe847e8cdb73f226">operator--</a>, <a href="#a46ae63c8dfa785ff0a9678d1bed168aa">operator-=</a>, <a href="#a9284a4735992c0b86c3827ecbd0d0861">operator/</a>, <a href="#aa81664ad422ed05b8b9b6eaedcd355f5">operator/=</a>, <a href="#ad6b9ab408d61ca138628e070cd6bd93a">operator&lt;</a>, <a href="#a44e9d3a334499824e1ff938254e597bf">operator&lt;=</a>, <a href="#a6c00fa06bed413c4253776167c7df87e">operator=</a>, <a href="#a7d50644f90a55900013be55fcb257f42">operator==</a>, <a href="#a7c66825db234e73dedb2c3799bfa3f12">operator&gt;</a>, <a href="#aed7171fdf762b090dd88be0697e652be">operator&gt;=</a>, <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### SlowDynamicAPInt() {#a0504bdcb9069cb7e2673d8a07af986de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt::SlowDynamicAPInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>


<p>Referenced by <a href="#a080fd4d5bc1f48ec40237895f64b6342">operator%</a>, <a href="#a0fc607373675fde318c740e7bc810ff9">operator*</a>, <a href="#afbe3b990798e79cc464f39472699112b">operator+</a>, <a href="#a70ea8ef61eafc6ee1009f01753c619ae">operator-</a>, <a href="#a0a7d474fe2bca892a50861086e90cf07">operator-</a>, <a href="#a9284a4735992c0b86c3827ecbd0d0861">operator/</a> and <a href="#a6c00fa06bed413c4253776167c7df87e">operator=</a>.</p>

</div>
</div>

### SlowDynamicAPInt() {#a0ce4cdf6c23326febc70d55a3892c166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt::SlowDynamicAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
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



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator int64\_t() {#a0748dcfa9d89080d1f70c3c05f03967d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt::operator int64_t ()</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>

</div>
</div>

### operator-() {#a70ea8ef61eafc6ee1009f01753c619ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt SlowDynamicAPInt::operator- ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator-() {#a0a7d474fe2bca892a50861086e90cf07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt SlowDynamicAPInt::operator- (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a260fae637de414fe27ae28483df4f379">runOpWithExpandOnOverflow</a>, <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a>, <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ae324de5041feaf7eb8433221cdaca9aa">llvm::APInt::ssub_ov</a>.</p>

</div>
</div>

### operator--() {#a2f622a535f889d45fe847e8cdb73f226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator-- ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator-=() {#a46ae63c8dfa785ff0a9678d1bed168aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator!=() {#a73d90fea50ec5a75c894d67fbe2d3b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SlowDynamicAPInt::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator\*() {#a0fc607373675fde318c740e7bc810ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt SlowDynamicAPInt::operator* (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a260fae637de414fe27ae28483df4f379">runOpWithExpandOnOverflow</a>, <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a>, <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ac155d7c568fc1aba25723e77b6888908">llvm::APInt::smul_ov</a>.</p>

</div>
</div>

### operator\*=() {#a5826a85058174310d98ff0d83cb118b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator*= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator/() {#a9284a4735992c0b86c3827ecbd0d0861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt SlowDynamicAPInt::operator/ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a260fae637de414fe27ae28483df4f379">runOpWithExpandOnOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a889c63e93f521abb41e0736a3f42cf02">llvm::APInt::sdiv_ov</a>, <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator/=() {#aa81664ad422ed05b8b9b6eaedcd355f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator/= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator%() {#a080fd4d5bc1f48ec40237895f64b6342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt SlowDynamicAPInt::operator% (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This operation cannot overflow.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator%=() {#ac0dc852a171a2a6a4c8c4f1a6761a983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator%= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator+() {#afbe3b990798e79cc464f39472699112b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt SlowDynamicAPInt::operator+ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a260fae637de414fe27ae28483df4f379">runOpWithExpandOnOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a694293446a074c3d64270e7671bb5052">llvm::APInt::sadd_ov</a>, <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator++() {#a6efa59b7aacf80be1e6897f0ffd6bb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator++ ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator+=() {#a18da247480a2159740cf06c5381ea163}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<hr/>



### Assignment operators, preincrement, predecrement {#autotoc_md109}


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Reference <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator&lt;() {#ad6b9ab408d61ca138628e070cd6bd93a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SlowDynamicAPInt::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator&lt;=() {#a44e9d3a334499824e1ff938254e597bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SlowDynamicAPInt::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator=() {#a6c00fa06bed413c4253776167c7df87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlowDynamicAPInt &amp; SlowDynamicAPInt::operator= (int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="#a0504bdcb9069cb7e2673d8a07af986de">SlowDynamicAPInt</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator==() {#a7d50644f90a55900013be55fcb257f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SlowDynamicAPInt::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<hr/>



### Comparison operators {#autotoc_md107}


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator&gt;() {#a7c66825db234e73dedb2c3799bfa3f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SlowDynamicAPInt::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

### operator&gt;=() {#aed7171fdf762b090dd88be0697e652be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SlowDynamicAPInt::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/slowdynamicapint">SlowDynamicAPInt</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp/#a86cb80d1cfe9f340e28760d24cfef373">getMaxWidth</a> and <a href="#a7ccd6b8cee73c66735677d1044f3121f">SlowDynamicAPInt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a37b8ba867d5f6532f7886d1d7d04e1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlowDynamicAPInt::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a048eab76be75a96b1715bf4780b4c6fd">print</a>.</p>

</div>
</div>

### getBitWidth() {#a9affb1f32a8b82fc8346f458925683d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::detail::SlowDynamicAPInt::getBitWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>

</div>
</div>

### print() {#a048eab76be75a96b1715bf4780b4c6fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlowDynamicAPInt::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<hr/>



### Printing {#autotoc_md110}


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a>.</p>


<p>Referenced by <a href="#a37b8ba867d5f6532f7886d1d7d04e1f5">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DynamicAPInt {#a64d8ad0f5b2be77a4140ad1021030a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::detail::SlowDynamicAPInt::DynamicAPInt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Val {#a76069858180debd7db76ef18cf847deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::SlowDynamicAPInt::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/slowdynamicapint-h">SlowDynamicAPInt.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/slowdynamicapint-cpp">SlowDynamicAPInt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
